# Wiki schema and validation rules

## Layers

- `raw/sources/`: immutable, verifiable source records or permitted source copies. Do not place LLM summaries here.
- `wiki/sources/`: LLM-generated source notes that summarize and interpret one ingested source.
- `wiki/concepts/`: topic pages that integrate evidence and link to source notes.
- `wiki/synthesis/`: cross-concept synthesis, explicitly marked as synthesis rather than a source's direct wording.
- `index.md`: content-oriented catalog and ingest status.
- `log.md`: append-only chronological record of ingests, queries, and lint passes.

## Required source record fields

Each raw source record must contain: source ID, title, authoring group/authors, publication venue/date, DOI or persistent identifier, canonical full-text URL, secondary verification URL where available, retrieval date, verification method, section locators checked, and any access/copyright note. A source record is an acceptable alternative to a local full-text copy when it enables independent verification.

## Required generated page fields

Every generated Wiki page must have YAML frontmatter with `title`, `type`, `status`, `created`, `updated`, and `sources`. Source notes also include `source_id`; concepts include `related` links. Use ISO dates (`YYYY-MM-DD`). Link pages using relative Markdown links. Source-backed factual sentences or list items end in `[Sxx]` citations linking to the matching source note.

## Evidence labels

- **Source statement / guideline recommendation**: what the source explicitly says.
- **Interpretation**: a careful explanation derived from the source; identify it as interpretation and cite supporting source IDs.
- **Uncertainty / limit**: what the source does not establish or where application depends on individual context.
- **Not yet verified**: a claim or source not yet checked; do not use as established knowledge.

Do not infer causation from association, individual diagnosis from general guidance, or universal outcomes from a guideline. Preserve qualifiers and population/context. Attribute clinical or care recommendations to their source. Where behavior changes may signal illness, direct readers to veterinary assessment rather than diagnosing.

## S01 ingest validation checklist

1. The canonical DOI resolves to the titled 2013 article and its bibliographic metadata agrees across PubMed Central and the journal version.
2. When a user-provided local copy is available, inspect it and preserve an unchanged copy under `raw/sources/`; record its SHA-256 and check article identity. The article's five pillar headings and summary points are checked in the full text.
3. Each of the five concept pages links to the S01 source note, and the source note links back to the concepts.
4. Every material factual claim in generated pages has a source ID citation; advice is attributed as guideline advice.
5. Confirm all seven planned sources are marked 已處理; use log.md for historical states.
6. All relative links resolve; no presentation files are created during ingest.

## Ingest workflow

`curate source → verify metadata/full text → record raw source provenance → extract scoped claims → review takeaways → write source note → update concepts/synthesis → update index → append log → validate links, citations, scope and status`.

If a claim fails validation, revise the Wiki page or source mapping and repeat the relevant checks before marking the ingest complete. Record the result and any limitation in `log.md`.

## S02 ingest validation checklist

1. Verify the RSPCA Australia article title, update date, page attribution, and displayed license on the canonical page.
2. Confirm the three named sections and the vet-advice statement against the page text; do not turn its illustrations into a diagnostic scoring system.
3. Record the online source and retrieval date; do not reproduce its illustrations or substantial wording.
4. Link S02's source note to the relevant concept page and keep S01's environment framework distinct from S02's body-language examples.
5. Confirm index, AGENTS and schema share the current state: S01–S07 processed.

## Current state — 2026-11-22

Earlier status checklists are historical snapshots. S01–S07 are processed. S03 checks: official page identity, section-level claim accuracy, missing date recorded honestly, no diagnosis inferred from purring, and relative links resolved.

## S04 validation — 2026-11-22

Check DOI/PMID/PMCID; separate recruited and analysed sample sizes; distinguish approach score from distance; preserve gaze-control limitation. Current state: S01–S07 processed; historical progress is in log.md.

## S05 validation — 2026-11-22

Verify survey design and denominators; distinguish owner-reported association from causation, and parasite hypothesis from tested findings. Current state: S01–S07 processed; historical progress is in log.md.

## S06 validation — 2026-11-22

Verify official university affiliation and full page text; record missing date honestly; distinguish care advice from experimental outcomes; do not invent universal perch dimensions or motivations. Current state: S01–S07 processed; historical progress is in log.md.

## S07 validation — 2026-11-22

Verify official ASPCA source, database caveats and cat-specific list access. Empty dynamic results do not imply safety. Never equate non-toxic with edible or unrestricted intake; check plant identity and species-specific detail at query time. S01–S07 processed; previous status entries are historical snapshots.


## S08 validation — 2026-11-22

Verify preprint identity (SSRN DOI 10.2139/ssrn.5243632) and preserve the user-provided PDF with SHA-256. Label it as a non-peer-reviewed preprint; do not treat it as the journal version of record. Record selection limits (six plant-containing masses from two cats, no control group). Do not infer universal motivation, clinical benefit or hairball prevention.

## Current state — supersedes earlier status lines

As of 2026-11-22, **S01–S08 are processed** (S08 = preprint full text). Earlier lines stating "S01–S07 processed" or "all seven planned sources" are historical snapshots of the original plan; the original seven remain processed and S08 was added through the evidence gap loop.

## Evidence gap handling

Wiki query -> claim check -> if evidence missing, external source search -> verify -> ingest new source -> query again. Stop with documented uncertainty if credible evidence remains insufficient. Missing case details require clarification. New research is logged only after actually performed.


## S09 validation — 2026-11-23

Verify the article on the official dvm360 (Veterinary Medicine) page; record the print date/pages and the online date difference honestly. Mark cat data as preliminary with no sample size. Record that S09 and S05 share an author group, so S09 is supporting, not independent, evidence. Do not use S09 for or against the hair-evacuation hypothesis (not mentioned).

## Source-quality check — 2026-11-23

During Gate 2, check each teaching claim's sources for publisher/venue concerns. If a claim rests only on a contested venue, label it and seek a second source; if none, state the limit on the slide or keep the claim out.

## Current state — supersedes earlier status lines (2026-11-23)

**S01–S09 are processed.** S08 = journal version of record verified at abstract level plus preprint full text. S09 = supporting non-MDPI source for S05. Earlier "S01–S08" lines are historical.

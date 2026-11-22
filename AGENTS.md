# Cat Behavior LLM Wiki — maintainer instructions

This folder is a persistent, source-grounded knowledge base. Follow `wiki/schema.md` for page structure and evidence rules.

## Core rules

- `raw/` is the immutable source layer. Never rewrite, summarize over, or silently replace a source record. Correct metadata by appending a dated note or adding a new version record.
- `wiki/` is the LLM-maintained layer. Every factual claim about cats must cite one or more source IDs (for example `[S01]`) and link to the corresponding page under `wiki/sources/`.
- Keep source statements, practical recommendations, interpretation, and uncertainty distinct. Do not present a guideline recommendation as the result of a new controlled experiment.
- Ingest one source at a time: verify the source, record bibliographic metadata and stable links, discuss scope and key takeaways, create/update the source and concept pages, update `index.md`, append to `log.md`, then run the validation checklist in `wiki/schema.md`.
- Preserve existing pages and links. When new evidence disagrees with an existing claim, record the disagreement and source context; do not silently overwrite.
- Query the wiki by reading `index.md` first, then follow relevant links and cite evidence in the answer. File durable synthesis pages only when they add reusable knowledge.
- Lint periodically for broken links, uncited claims, orphan pages, duplicate concepts, stale source records, and unresolved disagreements. Record each lint pass in `log.md`.
- Do not create the teaching HTML presentation as part of Wiki ingestion. It is a separate downstream deliverable (now located in `presentation/`).

## Current ingest state (updated 2026-11-23)

- S01–S09 are processed.
- S01–S07 are the seven originally planned sources. S07 covers database use and limitations, not exhaustive verification of every plant entry.
- S08 was added through the evidence gap loop (Q02). It is ingested from the user-provided SSRN preprint full text, which is explicitly not peer reviewed; the journal version of record has not been checked for equivalence.
- 2026-11-23: S08 journal version of record (J Vet Behav 82:71–74) verified at abstract level; describe S08 as published, cite preprint-specific details as preprint. S09 (Hart 2008, Veterinary Medicine) added as a non-MDPI supporting source for S05; same research group, not independent replication.
- Source-quality rule: a claim supported only by a source from a publisher with documented quality concerns (e.g. MDPI) must be labelled in the Wiki and cross-checked with at least one other source before it enters teaching output; if none exists, keep the limitation visible.
- Historical progress states are kept in `log.md`.

## Evidence gap loop

When Wiki evidence is insufficient, search primary studies or authoritative official guidance, verify full text and scope, ingest eligible new sources as S08 onward, then re-check the answer. Report conflicting or insufficient evidence honestly. Ask for missing case identity such as plant scientific name; do not infer it from literature. Record actual searches separately from planned searches.

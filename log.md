# Wiki log

Append entries in chronological order. Do not edit or remove earlier entries; append a correction note if needed.

## [2026-11-21] ingest | S01 — AAFP and ISFM Feline Environmental Needs Guidelines

- Status: completed; S01 is the only ingested source. S02–S07 remain 待 ingest.
- Verified the title, authors, journal, publication date, DOI, PMID, and PMCID against PubMed Central and the Journal of Feline Medicine and Surgery version of record.
- Read the full-text abstract, rationale, five pillar sections, and summary points. Created an immutable provenance record instead of copying the article text.
- Added one generated source note, a five-pillar overview, and five linked concept pages. Updated the index and schema.
- Validation: source metadata cross-check passed; all five pillar sections represented; wiki page citations link to S01; manual local-link/status review performed.
- Limitation: this is one 2013 professional guideline, not a new controlled trial. No second source is ingested, so cross-source synthesis and currency assessment remain pending.
- No HTML presentation generated.

## [2026-11-22] ingest update | S01 — local full-text verification

- Located the user's 12-page PDF in `C:\Users\Luna\Desktop\TAICA_1123繳交\10.1177_1098612X13477537.pdf`.
- Confirmed the visible article title, author list, journal pagination (219–230), DOI, five pillar sections, and summary points. The embedded metadata title is “FAB”; the article body identifies the expected source.
- Copied the PDF unchanged into `raw/sources/`; SHA-256 of source and Wiki copy: `FAE043BDFB3DFA2E374D8B92E2543F228A36139E2A6C0927F1AEE47D11765E31`.
- Expanded the S01 source note and all five concept pages with details from the full text; added provenance and validation rules for user-provided source copies.
- Status remains: S01 已處理; S02–S07 待 ingest. S01 is still the only ingested source.
- Validation: local PDF identity/hash checked; section coverage checked against all five pillars and summary points; Markdown links and source-status references checked. No HTML presentation generated.

## [2026-11-22] ingest | S02 — RSPCA: What does my cat’s body language mean?

- Status: completed; S01 and S02 are processed; S03–S07 remain 待 ingest.
- Verified the official RSPCA Australia Knowledgebase page, its 2023-12-14 update date, its attribution to an RSPCA UK article, and the displayed CC BY-NC-ND 4.0 license.
- Extracted the guide's scope, three named sections, combined body-posture examples, and advice to consult a veterinarian if concerned. No image or substantial text copied.
- Added immutable provenance record, generated S02 source note, and linked body-language concept; updated the overview, safe-place and human-cat interaction concepts, index, and schema validation rules.
- Validation: source page checked against recorded section locators; all relative Markdown links and source-status references checked. No HTML presentation generated.

## [2026-11-22] ingest | S03 — Cats Protection: Cat Body Language

- Official page sections reviewed; no explicit publication/update date found.
- Added source record, Traditional Chinese source note, purring concept and body-language link.
- Corrected stale AGENTS status. S01–S03 processed; S04–S07 pending.
- No HTML generated.

## [2026-11-22] ingest | S04 — slow blink study

- Nature fetch redirected; read PMC original full text and cross-checked PubMed metadata.
- Recorded two experiments, recruited/analysed sample sizes, approach outcome and gaze-control limitations.
- Added provenance, source and concept pages; updated S03 link, index and current state.
- S01–S04 processed; S05–S07 pending. No HTML generated.

## [2026-11-22] ingest | S05 — Characteristics of Plant Eating in Domestic Cats

- Read publisher full text and cross-checked PubMed identity; PMC access required browser verification.
- Added source record, Traditional Chinese research note and plant-eating concept; updated index and current state.
- Preserved survey limitations, varying denominators and untested parasite hypothesis. No raw-data reanalysis.
- Five sources now processed (S01–S05); S06–S07 pending. No HTML generated.

## [2026-11-22] ingest | S06 — Indoor Pet Initiative: Perches

- Read the official Ohio State University page in full; publication date and individual author not shown.
- Added provenance, Traditional Chinese source note and linked perches/window-view concept; related to S01 safe-place guidance.
- Preserved limits: no trial outcomes, universal dimensions, or individual motivation diagnosis.
- Current state S01–S06 processed; S07 pending. No HTML generated.

## [2026-11-22] ingest | S07 — ASPCA plant toxicity database

- Confirmed S07 identity against original planning chat; opened official ASPCA entry and followed Cats printable-list link.
- Dynamic selection returned no results; static official cat list readable. Used this fallback without interpreting missing results as safety.
- Added source record, Traditional Chinese source note and plant-safety concept; linked S05 plant-eating topic.
- Scope: database caveats and lookup principles only; no exhaustive species audit or edible-plant recommendation.
- S01–S07 processed; no HTML generated.

## [2026-11-22] query / lint | Teaching Markdown loop

- Produced topic introduction and seven sourced teaching points without speaker script.
- Found and corrected stale schema progress states and inaccurate single-source scope text in environmental overview.
- Checked local links and seven source record/note pairs; HTML validation not performed.

## [2026-11-22] query | Q01 plant-eating versus safety

- Read index, S05/S07 notes, concepts and provenance records.
- Expanded from behaviour evidence to toxicity guidance because source scope was insufficient.
- Saved 實際執行紀錄-Q01.md; individual plant safety remains undetermined without plant identity.
- No external source refresh, raw-data analysis or HTML operation test performed.

## [2026-11-22] planning | Deck scope revision

- Page 8 now discusses cats generally; Luna remains a visual asset.
- Moved workflow verification and reflection to planned Word report.
- Proposed pages 11–12 as guidance for new cat caregivers; awaiting user review. No HTML/Word generated.

## [2026-11-22] workflow update | Evidence gap research loop

- Added user-requested external search, source verification and new-source ingest branch when Wiki lacks evidence.
- Distinguished missing evidence from missing case identity; Q01 did not perform new external searches in this update.

## [2026-11-22] research loop | Q02 hair evacuation

- Searched later original research; located 2025 S08, but publisher and SSRN full-text requests returned 403.
- Saved abstract-only record, not full-text ingest completion; compared scope with S05 and documented unresolved causality/motivation.
- Confirmed slides 11–12 and added slide 13 preparation topic per user.

## [2026-11-22] acquisition retry | S08 full text

- Searched DOI/title/authors and university route, retried publisher and SSRN endpoints.
- Found SSRN preprint metadata (12 pages, posted 2025-05-09; DOI 10.2139/ssrn.5243632), but no readable full text.
- Kept S08 abstract_only; no full-text ingest completion claimed. Author requests and purchases not performed.

## [2026-11-22] ingest | S08 user-provided SSRN full text

- Read 12-page preprint text and inspected Figure 1; preserved PDF with SHA256.
- Recorded opportunistic selection of six plant-containing masses from two cats, methods, results and limits.
- Full-text preprint ingest complete; journal-version equivalence not checked. Updated Q02 with partial resolution, not causal proof.

## [2026-11-22] planning | Slide 6 confirmed

- User approved nuanced plant-eating/hair-evacuation conclusion; mapped to S05 and S08 preprint with limitations.

## [2026-11-22] planning | Slide 13 confirmed

- User approved five preparation points; next review is visual layout.

## [2026-11-22] authoring | Complete teaching HTML

- Created presentation/index.html with 13 pages, embedded Luna sheet, navigation, keyboard shortcuts, three quizzes and source dialog.
- Structural checks: 13 slide sections, 3 correct-answer controls, 8 source entries. JavaScript syntax checked.
- Browser layout and interactive behaviour still require visual/runtime review; no claim of completed mobile or desktop UI test.

## [2026-11-22] lint | Status sync before submission

- Rewrote index.md catalog: frontmatter and status table now list S01–S08; added source types, complete Sources list (S03–S08 were missing), grouped Concepts, Synthesis note (folder empty), presentation links, and current open questions.
- AGENTS.md and schema.md: current state updated to S01–S08 (S08 = non-peer-reviewed preprint full text); added S08 validation rules; earlier "S01–S07" lines marked as historical snapshots.
- 主題介紹與教學重點.md: source count corrected to eight; plant-eating section and review question now include S08 with limits; replaced "HTML 製作尚未執行" with a dated status note linking presentation/index.html.
- wiki/concepts/plant-eating.md: frontmatter sources [S05, S08]; abstract-only paragraph labelled as historical.
- 教學簡報製作計畫.md: stage table updated (ingest S01–S08, HTML created, operation test still pending); added page 13 to page/source map.
- raw/ records, Q01/Q02 and earlier log entries unchanged (append-only / immutable).
- Validation: relative Markdown link check re-run (result below). HTML layout/interaction test not yet performed.
- Link check result: 248 relative links resolved, 0 broken.

## [2026-11-22] qa / fix | HTML browser test and Loop C sticker repack

- Tested presentation/index.html via local server in browser at desktop (1440x900, all 13 slides) and mobile (390x844, slides 1, 6, 10, 11, 13).
- Passed: slide navigation, disabled boundary buttons, progress bar, keyboard shortcuts (ArrowLeft/Right, Home, End), dropdown jump, slide 10 interactive 3-question quiz, S01–S08 source dialog (including keyboard lock while open), and zero JS console errors.
- Loop C issue found: sprite sheet cells overlapped boundaries — top-right sleeping cat bled into right edge of slides 3, 5, 11, and bottom-right cat ear bled into bottom edge of slide 4.
- Fix: repacked all 6 stickers cleanly into centered 512x512 cells with transparent padding in presentation/images/luna-stickers-v1.png and re-embedded the PNG into presentation/index.html.
- Re-verification (1440x900): slides 3, 4, 5, and 11 confirmed clean with no neighboring sticker bleed.
- Minor mobile note (390x844): no horizontal overflow, but bottom nav button labels wrap onto multiple lines on narrow screens.

## [2026-11-22] deliverable | Submission Word & PDF report generated

- Generated NUTC-1811406013-財金碩二-張翔鈞-Cat Behavior LLM Wiki與互動式教學簡報.docx and matching PDF in 20261123繳交/.
- Covers six sections: project architecture, S01–S08 source verification, Graph & Loop A/B/C design, real execution & verification logs (Q01, Q02, lint, HTML browser QA + sticker fix), 13-slide summary, and limits/shift-left reflection.
- Embedded 對話_1.png, 對話_2.png, repacked luna-stickers-v1.png, and verified slide 11 browser screenshot.

## [2026-11-23] final loop | Pre-submission check

- Found the submission .docx body empty (no text, no images) and the referenced PDF missing; rebuilt the report following the course template format.
- Relative link check: 248 resolved, 0 broken.
- Annotated stale "HTML not verified" lines in loop驗證紀錄.md as historical (no deletion).
- Loop C: slide 10 navigation was pushed below the 1440x900 viewport after answering the quiz (nav bottom 955px). Tightened #s10 spacing only; re-test 898px at 1440x900 and 772px at 1366x768; feedback text correct, 0 JS errors.

## [2026-11-23] source-quality loop | S05 (MDPI) cross-check, S08 VoR, S09 ingest

- Trigger: user flagged S05 publisher (MDPI) as possibly predatory. Checked status: Beall's List 2014–2015 then removed; Predatory Reports listing 2023, disputed by MDPI. Decision (user-approved): keep S05 with a source-quality note, add non-MDPI support.
- S08: verified Journal of Veterinary Behavior 82:71–74 (Elsevier, online 2025-08-11) abstract; design matches preprint. Status now VoR abstract + preprint full text. Appended to raw record (no rewrite).
- S09 ingested: Hart, "Why do dogs and cats eat grass?", Veterinary Medicine (Dec 2008, pp. 648–649; dvm360 online dated 2009-12-01). Cat data preliminary, no numbers, same group as S05, no hairball content.
- Updated: S05/S08 notes, new S09 note, plant-eating concept, index, AGENTS (source-quality rule), schema (S09 + source-quality check + current state), 主題介紹, 製作計畫, 簡報內容-13頁, Q02.
- HTML: slide 6 bullets rewritten with S05/S08/S09, quiz Q2 cites S09, source dialog adds S09 and labels S05 (MDPI) and S08 (J Vet Behav). Browser re-test passed at 1440x900, 1366x768, 390x844; 0 JS errors. Republished web version.

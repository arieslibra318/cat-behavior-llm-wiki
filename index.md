---
title: Cat Behavior LLM Wiki — Index
type: index
status: active
created: 2026-11-21
updated: 2026-11-23
sources: [S01, S02, S03, S04, S05, S06, S07, S08, S09]
---

# Cat Behavior LLM Wiki

以「科學知識 × 貓咪生活故事」為方向，逐篇 ingest 可核查資料，累積可追溯、互相連結的貓咪行為知識。目前已處理 **S01–S09 共九份來源**（S08 期刊版已刊出、細節依預印本全文；S09 為補充 S05 的非 MDPI 來源），已達到至少 ingest 五篇資料的數量要求。

## 狀態總覽

| Source ID | 類型 | 狀態 | 資料 |
|---|---|---|---|
| S01 | 專業臨床指引（AAFP/ISFM, 2013） | **已處理（本機全文）** | [來源紀錄](raw/sources/S01-source-record.md) · [知識頁](wiki/sources/S01-feline-environmental-needs.md) |
| S02 | 教育指南（RSPCA） | **已處理** | [來源紀錄](raw/sources/S02-source-record.md) · [知識頁](wiki/sources/S02-cat-body-language.md) |
| S03 | 教育指南（Cats Protection） | **已處理** | [來源紀錄](raw/sources/S03-source-record.md) · [知識頁](wiki/sources/S03-cats-protection-body-language.md) |
| S04 | 實驗研究（慢眨眼, 2020） | **已處理** | [來源紀錄](raw/sources/S04-source-record.md) · [知識頁](wiki/sources/S04-slow-blink-study.md) |
| S05 | 問卷研究（吃植物行為；MDPI 出版，品質有爭議） | **已處理（加註來源品質）** | [來源紀錄](raw/sources/S05-source-record.md) · [知識頁](wiki/sources/S05-plant-eating-study.md) |
| S06 | 教育指南（Ohio State University 棲架） | **已處理** | [來源紀錄](raw/sources/S06-source-record.md) · [知識頁](wiki/sources/S06-perches.md) |
| S07 | 參考資料庫（ASPCA 植物毒性） | **已處理（僅資料庫使用原則）** | [來源紀錄](raw/sources/S07-source-record.md) · [知識頁](wiki/sources/S07-plant-toxicity.md) |
| S08 | 觀察研究（吃植物與毛髮排出, 2025；J Vet Behav） | **已處理（期刊版摘要核對＋預印本全文）** | [來源紀錄](raw/sources/S08-source-record.md) ·  [知識頁](wiki/sources/S08-hair-evacuation.md) |
| S09 | 獸醫實務文章（Hart, Veterinary Medicine 2008） | **已處理（初步資料，與 S05 同團隊）** | [來源紀錄](raw/sources/S09-source-record.md) · [知識頁](wiki/sources/S09-hart-2008-grass-eating.md) |

## Wiki 維護文件

- [AGENTS.md — LLM 維護指示](AGENTS.md)
- [wiki/schema.md — 頁面結構、引用及驗證規則](wiki/schema.md)
- [log.md — chronological ingest / query / lint log](log.md)

## Sources

- [S01 — AAFP/ISFM Feline Environmental Needs Guidelines](wiki/sources/S01-feline-environmental-needs.md) — 2013 年臨床指引的範圍、核心主張、五大環境需求與限制。
- [S02 — RSPCA 貓咪肢體語言指南](wiki/sources/S02-cat-body-language.md) — 放鬆、擔憂及明顯不舒服的組合姿勢線索，以及解讀限制。
- [S03 — Cats Protection 肢體語言與呼嚕聲](wiki/sources/S03-cats-protection-body-language.md) — 肢體線索與呼嚕聲可能出現的不同情境。
- [S04 — 慢眨眼與人貓溝通研究](wiki/sources/S04-slow-blink-study.md) — 兩個實驗的設計、樣本、接近分數與視線對照限制。
- [S05 — 貓咪吃植物行為研究](wiki/sources/S05-plant-eating-study.md) — 飼主問卷結果、分母差異與未經測試的驅蟲假說；MDPI 出版，附來源品質註記。
- [S06 — Ohio State University 棲架指南](wiki/sources/S06-perches.md) — 棲架與窗邊位置的照護建議，非實驗結果。
- [S07 — ASPCA 貓咪植物毒性資料庫](wiki/sources/S07-plant-toxicity.md) — 資料庫使用原則與限制；查不到不等於安全。
- [S08 — 吃植物與毛髮排出：2025 年研究](wiki/sources/S08-hair-evacuation.md) — 兩隻貓六份吐出物的顯微觀察；已刊於 J Vet Behav，小樣本、無對照。
- [S09 — Hart (2008)：狗和貓為什麼吃草？](wiki/sources/S09-hart-2008-grass-eating.md) — 貓吃植物前多半無不適、吃後不常吐的初步資料；非 MDPI，但與 S05 同團隊。

## Concepts

**S01 五大環境需求**

- [貓咪環境需求：總覽](wiki/concepts/feline-environmental-needs.md)
- [安全的躲藏與休息處](wiki/concepts/safe-place.md)
- [分散且分開的關鍵資源](wiki/concepts/separated-resources.md)
- [遊戲與捕食行為機會](wiki/concepts/play-and-predatory-behavior.md)
- [正向且可預期的人貓互動](wiki/concepts/human-cat-interaction.md)
- [嗅覺與氣味安全感](wiki/concepts/sense-of-smell.md)

**行為與溝通**

- [觀察貓咪肢體語言](wiki/concepts/cat-body-language.md)
- [呼嚕聲與情境](wiki/concepts/purring.md)
- [慢眨眼與人貓互動](wiki/concepts/slow-blinking.md)

**吃植物與居家安全**

- [吃植物與吃草](wiki/concepts/plant-eating.md)
- [植物安全查核](wiki/concepts/plant-safety.md)
- [棲架與窗外觀察](wiki/concepts/perches-and-window-view.md)

## Synthesis

- `wiki/synthesis/` 目前沒有獨立的跨概念整合頁；教學用的整合內容保存在根目錄的教學整理文件（見下方）。

## 教學整理與驗證

- [主題介紹與教學重點](主題介紹與教學重點.md)
- [教學簡報製作計畫](教學簡報製作計畫.md)
- [Loop 驗證紀錄](loop驗證紀錄.md)
- [Q01 實際查詢與驗證](實際執行紀錄-Q01.md)：吃草動機與植物安全的檢索擴展。
- [Q02 補充檢索紀錄](補充檢索Loop-Q02.md)：吃草與排毛的外部檢索，S08 由摘要層級升級為預印本全文 ingest；11-23 來源品質 loop：S08 期刊版、S09 補充。

## 教學簡報

- [presentation/index.html](presentation/index.html)：13 頁互動式 HTML 教學簡報（含 3 題測驗與來源清單）。
- [presentation/簡報內容-13頁.md](presentation/簡報內容-13頁.md)：13 頁內容定稿。
- [presentation/preview.html](presentation/preview.html)：早期 2 頁視覺樣稿（歷史版本）。

## 尚待確認

- S07 僅處理資料庫使用原則，未逐項驗證整個植物資料庫。
- S08 期刊版（J. Vet. Behav. 2025）只核對摘要，全文未取得；方法細節依預印本，兩版本逐字一致性未核對。
- S05 為 MDPI 出版；「長短毛無差異」的數據目前只有 S05，尚無非 MDPI 的獨立來源。S09 與 S05 同團隊，不是獨立驗證。
- 目前九份來源中，多數主題只有一至兩份來源支持，跨來源共識與歧異仍無法廣泛評估。
- 本 Wiki 未經獸醫專業審查；外部來源可能日後更新。

# FIND-CKD 評論短信（NEJM Correspondence）投稿包

**標的論文**：Heerspink HJL, Neuen BL, Agarwal R, et al. Finerenone in Persons with Chronic Kidney Disease without Diabetes. *N Engl J Med* 2026;395:533-545. DOI 10.1056/NEJMoa2604625 <!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄。PMID 42246672 📌（PubMed 索引 metadata，未以本地全文驗證）。線上發表 2026-06-04，2026-06-29 更新，紙本 2026-08-06（Vol. 395, No. 6）<!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄

**本檔驗證原則**：所有數字、引號字串均可在下列本地檔案 grep 命中。標 📄 者為本地已落地全文；標 ⚠️📄 者為已落地但**版本受限**（作者自存版／非目標篇章），引用時必須註明限定且不得引頁碼；標 📌 者僅有 metadata（title/authors/journal/year/DOI/PMID），**不對其內文作任何具體斷言**；**【第四輪新增標記】**標 ⚠️ **PDF-only** 者為本機已有 PDF 但**未轉為 MD**，因無法 grep 驗證，**與 📌 同等對待，一律不得引用內文**。

**第二輪更新（2026-08-09）**：FIGARO-DKD、CONFIDENCE、INFINITY pooled、JAMA glomerular、DAPA-CKD correspondence 五者全文已落地並完成 grep 驗證，由 📌 升級為 📄；FIDELIO-DKD correspondence 僅取得其中一封讀者投書之作者自存版，升級為 ⚠️📄；CONFIDENCE correspondence 仍為 📌。

**第四輪更新（2026-08-09，使用者以機構權限下載）**：FIND-CKD 主文之 **NEJM Supplementary Appendix** 與 JAMA glomerular 分析之 **Supplement 2（eTables/eFigures）** 兩者全文已落地並完成 grep 驗證，由 📌 升級為 📄；兩份 **protocol PDF**（NEJM protocol 301 頁、JAMA supplement 1 protocol）依指示**僅存 PDF、未轉 MD**，故**不得引用**。至此仍未落地者僅剩 **CONFIDENCE correspondence** 與 **FIDELIO-DKD 之 Bakris/Agarwal Reply 本文**。

| 標記 | 本地檔案 | 版本 |
|---|---|---|
| 📄 | `/Users/ander/openclaw-research/find-ckd/FIND-CKD main text NEJMoa2604625.md` | NEJM 正式版 |
| 📄 | `/Users/ander/openclaw-research/find-ckd/原始PDF/Bakris_2020_FIDELIO-DKD.md` | NEJM 正式版 |
| 📄 | `/Users/ander/openclaw-research/find-ckd/原始PDF/Heerspink_2020_DAPA-CKD.md`（本檔已落地但**未被引用**） | NEJM 正式版 |
| 📄 | `/Users/ander/openclaw-research/find-ckd/原始PDF/Heerspink_2025_FIND-CKD-design.md` | NDT 正式版 |
| 📄 | `/Users/ander/openclaw-research/find-ckd/原始PDF/Hobbs_2024_BARACK-D.md` | 正式版 |
| 📄 | `/Users/ander/openclaw-research/find-ckd/原始PDF/Juurlink_2004_15295047.md` | NEJM 正式版 |
| 📄 **新** | `/Users/ander/openclaw-research/find-ckd/原始PDF/Pitt_2021_figaro-dkd.md`（FIGARO-DKD） | Publisher's PDF / Version of Record（CURIS, Univ. of Copenhagen 典藏；頁碼 2252-2263 與正式版一致，**可引頁碼**） |
| 📄 **新** | `/Users/ander/openclaw-research/find-ckd/原始PDF/Agarwal_2025_confidence.md`（CONFIDENCE） | Publisher's Version of Record（pure.rug.nl 典藏；N Engl J Med 2025;393:533-43，**可引頁碼**） |
| 📄 **新** | `/Users/ander/openclaw-research/find-ckd/原始PDF/Neuen_2026_infinity-pooled.md`（INFINITY pooled IPD） | Lancet 正式排版版（`Published online June 5, 2026`；線上版頁碼 1-10） |
| 📄 **第三輪新** | `/Users/ander/openclaw-research/find-ckd/原始PDF/Neuen_2026_infinity-appendix.md`（INFINITY supplementary appendix，35 頁） | 出版社官方 appendix（Elsevier CDN `ars.els-cdn.com` 直接下載之 mmc1.pdf；首頁載明 `Supplement to: Neuen BL, Heerspink HJL, Perkovic V, et al.`）。**Table S6（appendix p 23）之 Without diabetes 欄 N=793/791，即 FIND-CKD 全體受試者** |
| 📄 **新** | `/Users/ander/openclaw-research/find-ckd/原始PDF/Neuen_2026_jama-glomerular.md`（JAMA glomerular 分析） | JAMA 正式版（ORBi, Univ. de Liège 典藏；分頁為 E1–E10，**引用時用 E 頁碼或僅引 DOI**）。**【第四輪更新】其 Supplement 2（eTables/eFigures）已另行落地，見下列；Supplement 1（protocol）仍不可引用** |
| 📄 **第四輪新** | `/Users/ander/openclaw-research/find-ckd/原始PDF/FIND-CKD_2026_nejm-appendix.md`（FIND-CKD 主文 NEJM Supplementary Appendix，42 頁） | 出版社官方 appendix（使用者以機構權限自 NEJM 文章頁下載；首頁載明 `Supplement to: Heerspink HJL, Neuen BL, Agarwal R, et al. Finerenone in persons with chronic kidney disease without diabetes. N Engl J Med 2026;395:533-45.`）。轉檔 converter = LlamaParse（agentic tier）。深讀者已核對 MD 涵蓋全部 42 頁、無截斷，並抽 4 處與 `pdftotext` 逐字交叉比對一致。**內含 Supplementary Methods、Figure S1–S9、Table S1–S8** |
| 📄 **第四輪新** | `/Users/ander/openclaw-research/find-ckd/原始PDF/Neuen_2026_jama-glomerular-supp2.md`（JAMA glomerular 之 Supplement 2：eTable 1–4、eFigure 1–7） | JAMA 官方 supplement（使用者以機構權限下載）。轉檔 converter = LlamaParse（agentic tier）。深讀者已做 3 處與來源 PDF 的逐字／逐位交叉比對（標題頁、eTable 4 之 PDF p.16、eFigure 6 之 PDF p.22）皆一致 |
| ⚠️ **PDF-only（不可引用）** | `/Users/ander/openclaw-research/find-ckd/原始PDF/FIND-CKD_2026_nejm-protocol.pdf`（NEJM protocol＋amendment＋SAP，301 頁） | **依指示僅落地 PDF、未轉 MD**。身分已以 `pdftotext` 首頁核對（`Protocol for: Heerspink HJL, ... N Engl J Med 2026;395:533-45.`）。因無 MD 可 grep，本檔**任何內容一律不得引用**；若日後需引用（例如高血鉀 stop/restart 門檻、AESI 通報規則），必須先完成 LlamaParse 轉檔並正式列入本表 |
| ⚠️ **PDF-only（不可引用）** | `/Users/ander/openclaw-research/find-ckd/原始PDF/Neuen_2026_jama-glomerular-supp1-protocol.pdf`（JAMA Supplement 1：Bayer 臨床試驗計畫書 BAY 94-8862/21177） | **依指示僅落地 PDF、未轉 MD**。⚠️ **更嚴重的限制**：該 PDF 全部文字為 Type 3 自訂編碼字型、無 ToUnicode CMap，`pdftotext` 抽取結果為亂碼，**即使轉檔也無法以文字層 grep 驗證**；身分係以 `pdftoppm` 轉圖後目視確認（封面 `FIND-CKD`／Protocol Number 21177／09 JUN 2021）。**一律不得引用，亦不得聲稱曾對其做 grep 驗證** |
| 📄 **新** | `/Users/ander/openclaw-research/find-ckd/原始PDF/Vogt_2021_dapa-ckd-correspondence.md`（DAPA-CKD correspondence） | Publisher's Version of Record（UCL Discovery；含 Vogt 信、Yasuda/Isobe 信、Heerspink/Langkilde/Wheeler 之 Reply 三者全文，頁碼 388-390，**可引頁碼**） |
| ⚠️📄 **新（受限）** | `/Users/ander/openclaw-research/find-ckd/原始PDF/Bunkete_2021_fidelio-correspondence.md`（FIDELIO-DKD correspondence 之**其中一封讀者投書**） | **作者自存版（HAL, hal-03265574），非出版社正式版；且不是 Bakris/Agarwal 的 Reply 本文。**引用時必須註明「作者自存版」，**不得引用頁碼**，**不得**以此檔對「作者 Reply 的內容」作任何斷言 |
| 📌 | CONFIDENCE correspondence（*N Engl J Med* 2025;393:1753-1755, DOI 10.1056/NEJMc2513088）— **全文仍未落地，僅可引 metadata** |  |

---

# 一、NEJM Correspondence 英文投稿稿（主稿）

**Suggested title:** Hyperkalemia-Related Hospitalization in FIND-CKD

**主稿採選項 B（INFINITY 內部一致性版）**；原 RALES 外推版（選項 A）降為備選，附於取捨表之後。理由見取捨表：選項 B 的數字全部出自同一研究團隊自己的論文，證據距離最近、新穎度風險最低（選項 A 的 Juurlink/RALES 論證已有 2021 年 Bunkete 投書前例）。

### Body（正文，171 words）

> **【第五輪修訂（Codex 外部審查採納，2026-08-10）】** Codex review 判定原稿 substantively sound，另提 4 條建議，經逐條錨點核驗後全數採納：(1) `prespecified safety assessment` → **`prespecified safety outcome`** 並補 `serious`——鏡射主文 Outcomes 段逐字 `Prespecified safety outcomes included ... hospitalization for serious hyperkalemia`<!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄，用作者自己的術語預先堵死「narrower category」反駁；(2) 尾句改為 `potassium was assessed at each visit, and the trial regimen was withheld when levels exceeded 5.5 mmol per liter`——`withheld` 為主文逐字、`at each visit` 為附錄逐字，不再用 `dosing was governed by` 之推論式搭配；(3) `which was enrolled entirely from FIND-CKD` → **`all of whom were FIND-CKD participants`**（文法更緊）；(4) Ref 1 頁碼改 NEJM 壓縮式 `533-45`（主文自身引用格式逐字 `N Engl J Med 2026;395:533-45.`）📄。字數 170 → **171 words**。

> **【第四輪唯一一處正文修訂】** 原句「dosing was governed by scheduled **central-laboratory** monitoring」已改為「dosing was governed by scheduled **potassium monitoring at each visit**」。理由：NEJM Supplementary Appendix 的 Central Laboratory Assessment 段明寫**劑量決策依據的是當地實驗室**，中央實驗室僅用於計算論文所報告的 >5.5／>6.0 mmol/L 安全性分類——逐字：`Central laboratory assessments were used for calculation of the primary and all other eGFR-based outcomes, and for the calculation of potassium cutoffs (>5.5 and >6.0 mmol/L). In addition, potassium and eGFR were assessed at local laboratories for dosing decisions at each visit.`<!-- src:原始PDF/FIND-CKD_2026_nejm-appendix.md --> 📄 原措辭把 central-laboratory 與 dosing 直接搭配，與附錄原文不符，會被作者或審稿人抓到而削弱信件的技術權威性。修訂後字數由 167 增為 **170 words**（仍在 175 上限內），其餘句子一字未動。

> **TO THE EDITOR:** Heerspink et al. (Aug. 6 issue)¹ report that finerenone slowed the decline in the estimated glomerular filtration rate among adults with chronic kidney disease who did not have diabetes. We seek clarification regarding hyperkalemia-related hospitalization. The Results section and Table 2 state that hyperkalemia led to hospitalization in 7 participants (0.9%) in the finerenone group and 5 (0.6%) in the placebo group. The Discussion, however, describes the potassium increases as "leading to discontinuation of the trial regimen in few participants and no hospitalizations." The INFINITY pooled analysis likewise reports serious hyperkalemia requiring hospitalization in 7 participants (0.9%) versus 5 (0.6%) in the subgroup without diabetes, all of whom were FIND-CKD participants.² Because hospitalization for serious hyperkalemia was a prespecified safety outcome, does that statement refer to a narrower category, or should it be corrected? Precision matters: eligibility required a serum potassium level of 4.8 mmol per liter or less, potassium was assessed at each visit, and the trial regimen was withheld when levels exceeded 5.5 mmol per liter.

**Word count:** 171 words（NEJM 上限 175；正文不含 references、標題、作者資訊。計數含開頭 `TO THE EDITOR:` 三個 whitespace 分隔詞、不含上標參考文獻號，計數慣例與前幾輪相同）。

### References（2 篇，NEJM 上限 5 篇）

1. Heerspink HJL, Neuen BL, Agarwal R, et al. Finerenone in persons with chronic kidney disease without diabetes. *N Engl J Med* 2026;395:533-45. <!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄（頁碼採 NEJM 壓縮式，主文自身引用格式逐字 `N Engl J Med 2026;395:533-45.`）
2. Neuen BL, Heerspink HJL, Perkovic V, et al. Efficacy and safety of finerenone in patients with chronic kidney disease: an individual participant data pooled analysis (INFINITY). *Lancet* 2026;407:2375-2386. <!-- src:原始PDF/Neuen_2026_infinity-pooled.md --> 📄（⚠️ 卷期頁碼 `407:2375-2386` 出自第一輪 Crossref metadata 驗證 📌，本地 Lancet 線上排版版僅有 online 日期與 DOI，無紙本卷期頁碼；投稿前請再以 Crossref/期刊頁面確認）

### 主稿的核心論證基礎（第三輪升級：INFINITY appendix Table S6 直接引用）

**直接證據（取代先前的算術推論）**：INFINITY supplementary appendix 的 **Table S6**（Treatment-emergent adverse events by treatment arm in participants with and without diabetes，appendix p 23）之 **Without diabetes 欄 N=793／791——正是 FIND-CKD 的隨機分派人數**——其 hyperkalaemia SAE 之 `Requiring hospitalisation` 列報為 **`7 (0·9%)`** vs **`5 (0·6%)`**。<!-- src:原始PDF/Neuen_2026_infinity-appendix.md --> 📄 INFINITY 主文亦明示此高血鉀住院終點依糖尿病狀態的分析（`p<sub>interaction</sub>=0·034; appendix p 33`）。<!-- src:原始PDF/Neuen_2026_infinity-pooled.md --> 📄 換言之，**同一研究團隊已在 2026 年 6 月的 Lancet appendix 中，白紙黑字刊出 FIND-CKD 族群 7 vs 5 件高血鉀住院**——與 FIND-CKD 主文 Discussion 的 `no hospitalizations` 直接互斥。

**輔助算術（仍成立，備作口頭答辯）**：FIDELIO-DKD 40 vs 8 <!-- src:原始PDF/Bakris_2020_FIDELIO-DKD.md --> 📄 ＋ FIGARO-DKD 21 vs 2 <!-- src:原始PDF/Pitt_2021_figaro-dkd.md --> 📄 ＝ 61 vs 10；INFINITY 全體合計 68 vs 15 <!-- src:原始PDF/Neuen_2026_infinity-pooled.md --> 📄；差額 7 vs 5 與 Table S6 的 Without diabetes 欄一致，兩路互證。

> **措辭紅線（第三輪訂立，第五輪句型改為 all of whom were FIND-CKD participants，依據不變）**：主稿句「in the subgroup without diabetes, all of whom were FIND-CKD participants」有雙重依據——Table S6 的 N=793/791 與 FIND-CKD 主文的 793/791 完全相同 <!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄，且 INFINITY 納入的三試驗中僅 FIND-CKD 為非糖尿病族群（FIDELIO/FIGARO 均要求 type 2 diabetes）<!-- src:原始PDF/Neuen_2026_infinity-appendix.md --> 📄。不再需要「a total that matches only with FIND-CKD included」的間接寫法。

### 逐句可核對表（投稿前作者逐字覆核用）

| 稿中字串 | 來源與可 grep 字串 | 檔案 |
|---|---|---|
| hospitalization in 7 participants (0.9%) ... and 5 (0.6%) | Results 逐字：`Hyperkalemia led to hospitalization in 7 participants (0.9%) with finerenone and 5 participants (0.6%) with placebo`；Table 2 列名 `Leading to hospitalization`，其下兩格為 `7 (0.9)` 與 `5 (0.6)` | 📄 主文 <!-- src:FIND-CKD main text NEJMoa2604625.md --> |
| "leading to discontinuation of the trial regimen in few participants and no hospitalizations" | Discussion 逐字：`leading to discontinuation of the trial regimen in few participants and no hospitalizations` | 📄 主文 <!-- src:FIND-CKD main text NEJMoa2604625.md --> |
| hospitalization for serious hyperkalemia was a prespecified safety outcome（**第五輪修訂**） | 主文 Outcomes 段逐字：`Prespecified safety outcomes included a serum potassium level of more than 5.5 mmol per liter or more than 6.0 mmol per liter, hospitalization for serious hyperkalemia`——信中措辭現與主文術語完全鏡射；設計論文佐證（雙欄斷行殘片）：`for hyperkalaemia and permanent discontinuation of study` + 次行 `medication due to hyperkalaemia.` | 📄 主文 <!-- src:FIND-CKD main text NEJMoa2604625.md --> ／📄 設計論文 <!-- src:原始PDF/Heerspink_2025_FIND-CKD-design.md --> |
| eligibility required a serum potassium level of 4.8 mmol per liter or less | Participants 段逐字：`Eligibility criteria included a serum potassium level of 4.8 mmol per liter or less`；**【第四輪新增第二來源】**附錄 Table S1（Inclusion and Exclusion Criteria）逐字：`Serum potassium level ≤4.8 mmol/l` | 📄 主文 <!-- src:FIND-CKD main text NEJMoa2604625.md --> ／📄 附錄 <!-- src:原始PDF/FIND-CKD_2026_nejm-appendix.md --> |
| the trial regimen was withheld when levels exceeded 5.5 mmol per liter（**第五輪修訂**） | Trial procedures 段逐字：`If the serum potassium level exceeded 5.5 mmol per liter, finerenone or placebo was withheld for 72 hours` | 📄 主文 <!-- src:FIND-CKD main text NEJMoa2604625.md --> |
| potassium was assessed at each visit（**第五輪修訂**） | 附錄逐字：`potassium and eGFR were assessed at local laboratories for dosing decisions at each visit`；主文佐證：`were collected for eGFR and serum potassium assessments at the central laboratory`（訪視為篩選、基準、第 1/3/6/9/12 個月，其後每 4 個月）。⚠️ **不得**寫成「central-laboratory 主導 dosing」——附錄明示 dosing 用 local lab、central lab 僅用於計算 >5.5／>6.0 分類；第五輪起亦不再用 `dosing was governed by` 之推論式搭配 | 📄 附錄 <!-- src:原始PDF/FIND-CKD_2026_nejm-appendix.md --> ／📄 主文 <!-- src:FIND-CKD main text NEJMoa2604625.md --> |
| serious hyperkalemia requiring hospitalization in 7 participants (0.9%) versus 5 (0.6%) | Appendix Table S6 hyperkalaemia SAE 之 `Requiring hospitalisation` 列，Without diabetes 兩格 `7 (0·9%)` 與 `5 (0·6%)`（Lancet 用中點小數，稿中依 NEJM 慣例改為句點） | 📄 INFINITY appendix <!-- src:原始PDF/Neuen_2026_infinity-appendix.md --> |
| in the subgroup without diabetes, all of whom were FIND-CKD participants（**第五輪修訂**） | Table S6 表頭 `Without diabetes` 欄 `(N=793)`／`(N=791)`，與 FIND-CKD 主文 `793 were assigned to the finerenone group, and 791 to the placebo group` 完全一致；三試驗中僅 FIND-CKD 為非糖尿病族群（Table S1 study design 對照） | 📄 INFINITY appendix <!-- src:原始PDF/Neuen_2026_infinity-appendix.md --> ／📄 主文 <!-- src:FIND-CKD main text NEJMoa2604625.md --> |

> **轉檔注意（第三輪更新）**：`原始PDF/*.md` 目前有兩種轉檔來源，核對規則相同——**一律用單行連續片段 grep，不要用跨行重組後的句子**。
>
> - **第二輪 6 檔改為 LlamaParse（agentic tier）轉出**：`Vogt_2021_dapa-ckd-correspondence.md`、`Bunkete_2021_fidelio-correspondence.md`、`Pitt_2021_figaro-dkd.md`、`Agarwal_2025_confidence.md`、`Neuen_2026_infinity-pooled.md`、`Neuen_2026_jama-glomerular.md`。斷行已合併、連字號已接回，故整句多半可一次 grep 命中；但版面會帶 Markdown 標記（`<sup>1</sup>` 上標、`*Journal*` 斜體、`**HEADING**`、表格轉為 HTML `<td>`），選片段時須避開這些標記或連同標記一起取。舊的 pdftotext 版本保留為同名 `.pdftotext.md.bak`，**僅供追溯，不作為引用來源**。
> - **第一輪 5 檔仍為 `pdftotext -layout`**：`Bakris_2020_FIDELIO-DKD.md`、`Heerspink_2020_DAPA-CKD.md`、`Heerspink_2025_FIND-CKD-design.md`、`Hobbs_2024_BARACK-D.md`、`Juurlink_2004_15295047.md`。雙欄版面會斷行、拆連字號，逐字引用仍須取**單行殘片**（例如 `No fatal hy-` + 次行 `perkalemia adverse events were reported.`）。
>
> ⚠️ 換版後已查出一處實質更正：FIGARO-DKD 那句住院比例原被標為出自 Discussion，實為 **Results** 的 `**SAFETY OUTCOMES AND VITAL SIGNS**` 段（pdftotext 雙欄把相鄰右欄的 Discussion 文字併在同一行所致），詳見 §2.5(b) 與 §4.4。

### 備選：選項 A（RALES 外推版，160 words；編輯要求縮短時使用）

> **【第五輪同步修訂（Codex 審查採納）】** 與主稿同步：`prespecified safety assessment` → `serious hyperkalemia ... prespecified safety outcome`；尾句改 `potassium was assessed at each visit, and the trial regimen was withheld when levels exceeded 5.5 mmol per liter`；Ref 1 頁碼改壓縮式 `533-45`。字數由 159 增為 **160 words**。

> **TO THE EDITOR:** Heerspink et al. (Aug. 6 issue)¹ report that finerenone slowed the decline in the estimated glomerular filtration rate among adults with chronic kidney disease who did not have diabetes. We seek clarification regarding hyperkalemia-related hospitalization. The Results section and Table 2 state that hyperkalemia led to hospitalization in 7 participants (0.9%) in the finerenone group and 5 (0.6%) in the placebo group. The Discussion, however, describes the potassium increases as "leading to discontinuation of the trial regimen in few participants and no hospitalizations." Because hospitalization for serious hyperkalemia was a prespecified safety outcome,² does the latter statement refer to a narrower category of events, or should it be corrected? Precision matters for implementation: eligibility required a serum potassium level of 4.8 mmol per liter or less, potassium was assessed at each visit, and the trial regimen was withheld when levels exceeded 5.5 mmol per liter. After RALES, hyperkalemia-related hospitalizations rose from 2.4 to 11.0 per 1000 patients.³

#### 選項 A 的 References（3 篇）

1. Heerspink HJL, Neuen BL, Agarwal R, et al. Finerenone in persons with chronic kidney disease without diabetes. *N Engl J Med* 2026;395:533-45. <!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄
2. Heerspink HJL, Agarwal R, Bakris GL, et al. Design and baseline characteristics of the Finerenone, in addition to standard of care, on the progression of kidney disease in patients with Non-Diabetic Chronic Kidney Disease (FIND-CKD) randomized trial. *Nephrol Dial Transplant* 2025;40:308-319. <!-- src:原始PDF/Heerspink_2025_FIND-CKD-design.md --> 📄
3. Juurlink DN, Mamdani MM, Lee DS, et al. Rates of hyperkalemia after publication of the Randomized Aldactone Evaluation Study. *N Engl J Med* 2004;351:543-551. <!-- src:原始PDF/Juurlink_2004_15295047.md --> 📄

> **選項 A 專屬核對句**：`rose from 2.4 to 11.0 per 1000 patients` ← Juurlink abstract 逐字（連續片段）：`1000 patients in 1994 to 11.0 per 1000 patients in 2001 (P<0.001)`，其前一行為 `The rate of hospitalization for hyperkalemia rose from 2.4 per`。<!-- src:原始PDF/Juurlink_2004_15295047.md --> 📄
>
> **注意（給投稿者）**：Juurlink 的母體是安大略、近期因心衰竭住院、正在使用 ACE inhibitor 的高齡病人 <!-- src:原始PDF/Juurlink_2004_15295047.md --> 📄，不是 CKD 族群。若審稿要求更嚴謹，可把最後一句改寫為下列建議句（作者自撰，非引文；+6 words，總計 **165** words，仍在 175 上限內）：
>
> Among older patients treated with ACE inhibitors after RALES, hyperkalemia-related hospitalizations rose from 2.4 to 11.0 per 1000.³

#### 選項 B（主稿）vs 選項 A（備選）的取捨

| | 選項 A（RALES 外推，**備選**） | 選項 B（INFINITY 內部不一致，**主稿**） |
|---|---|---|
| 證據距離 | 遠：spironolactone、心衰竭族群、2004 年安大略行政資料 <!-- src:原始PDF/Juurlink_2004_15295047.md --> 📄 | 近：同一藥、同一試驗、同一作者群、2026 年 |
| 新穎度風險 | **偏高**：2021 年已有讀者投書針對 FIDELIO-DKD 提出「這個第三期試驗的高血鉀安全數據外推到日常實務前應審慎解讀」並引用同一篇 Juurlink（作者自存版逐字：`the safety data concerning hyperkalemia from this phase 3 clinical trial should be` 及參考文獻 `Rates of hyperkalemia after publication of`）<!-- src:原始PDF/Bunkete_2021_fidelio-correspondence.md --> ⚠️📄（作者自存版） | 低：無任何已知前例把 FIND-CKD 的 Table 2／Discussion 矛盾與 INFINITY 總數並列 |
| 可被反駁的空間 | 作者可回「finerenone 非固醇類、族群不同」 | 幾乎沒有：數字全部出自作者自己的兩篇論文 |
| 字數 | 160（第五輪修訂後） | 171（第五輪修訂後） |
| 證據形式 | RALES 類比（外部、間接） | INFINITY appendix Table S6 **直接刊載** FIND-CKD 族群 7 vs 5（第三輪落地後由算術推論升級為直接引用） |

**決定（2026-08-09）**：主稿採**選項 B**；選項 A 僅在編輯要求縮短、或 INFINITY 算術論證被質疑時作為退路。**兩者不可合併**（合併必然超過 175 words）。

### 投稿欄位備忘

- 作者 ≤3 位、每人 1 個 affiliation、1 位 corresponding author。**【第二輪更新】**「≤3 位作者」「≤5 篇參考文獻與 1 個圖或表」「≤175 words（不含 references）」三項已可引 NEJM 2021 年印行之 instructions 原文（見 §4.2 逐字片段）<!-- src:原始PDF/Vogt_2021_dapa-ckd-correspondence.md --> 📄；但**2026 年版本仍須於投稿介面現場確認**，本檔未落地 2026 年規則原文。
- 揭露：與 Bayer／finerenone 相關之任何酬金、演講費、研究經費；以及 AI/LLM 輔助撰稿之使用情形。
- 同一內容在 NEJM 決定前不得先行公開發表。

---

# 二、中文深度評論：為什麼「安全性表述不一致」是唯一該投的角度

## 2.1 這封信攻擊的標的：一個同篇論文內部的直接矛盾

FIND-CKD 主文在 **Results／Table 2** 明確報告：hyperkalemia 導致住院者為 finerenone 組 7 人（0.9%）、placebo 組 5 人（0.6%）；因 hyperkalemia 永久停藥者為 12 人（1.5%）與 1 人（0.1%）；無致死性 hyperkalemia 事件。<!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄

同一篇論文的 **Discussion** 卻寫道：`Hyperkalemia was the most common adverse event, but increases in the serum potassium level were modest, leading to discontinuation of the trial regimen in few participants and no hospitalizations.` <!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄

這不是解讀差異，而是**同一篇論文兩處對同一個 prespecified 安全性終點的敘述互相排斥**：Table 2 有 7 件住院，Discussion 說 no hospitalizations。

補強證據（同向、但較弱，不建議寫進 175 字）：Results 另寫 `Overall, the incidence of any serious hyperkalemia event was less than 1%.`，而 Table 2 的 "Serious adverse event related to hyperkalemia — Overall" 為 finerenone 8 人（1.0%）、placebo 5 人（0.6%）。<!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄 8/793 恰為 1.0%，嚴格說並非「less than 1%」。這顯示 Discussion／Results 的安全性文字傾向於「向下取整式的樂觀措辭」，而非單一筆誤。此點可保留作為審稿或作者回覆後的第二輪材料。

## 2.2 為什麼「作者一定要回答」

三個理由使這個問題無法被含糊帶過：

1. **它是 prespecified 安全性評估項目，不是事後衍生指標。** FIND-CKD 設計論文明列 prespecified safety analysis 包含高血鉀住院與因高血鉀永久停藥（逐字連續片段：`for hyperkalaemia and permanent discontinuation of study` + 次行 `medication due to hyperkalaemia.`）。<!-- src:原始PDF/Heerspink_2025_FIND-CKD-design.md --> 📄 主文 Outcomes 段亦寫 `Prespecified safety outcomes included a serum potassium level of more than 5.5 mmol per liter or more than 6.0 mmol per liter, hospitalization for serious hyperkalemia, and permanent discontinuation of the trial regimen because of hyperkalemia.`<!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄 作者不能主張這只是次要描述。
2. **答案只有兩種，都對讀者有價值。** 要嘛是文字錯誤（→ correction，直接改善公開紀錄）；要嘛作者是指某個更窄的類別（例如經 adjudication 的「serious hyperkalemia 住院」與 investigator-reported 「hyperkalemia 住院」之別），那也必須說明是哪一個定義——因為 Table 2 的分層本身就是 `Any hyperkalemia` 與 `Serious adverse event related to hyperkalemia` 兩層，而住院數 7 vs 5 是列在後者之下。<!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄
3. **它不挑戰主要療效結論，因此沒有防禦性反駁空間。** 主要終點（total eGFR slope 差 0.7 ml/min/1.73 m²/yr，95% CI 0.3–1.1，P<0.001）與 composite kidney–cardiovascular outcome（HR 0.77，95% CI 0.60–0.99，P=0.04）完全不受影響。<!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄 信件的語氣可以完全 collegial。

## 2.3 為什麼「臨床安全意涵」讓它值得佔用 NEJM 版面

單純抓錯字不足以成為 Correspondence；必須說明錯在哪裡會傷人。FIND-CKD 的高血鉀安全紀錄是**一整套人為條件**的產物：

- **納入條件**：`Eligibility criteria included a serum potassium level of 4.8 mmol per liter or less`。<!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄 基準血鉀平均 4.5±0.4 mmol/L。<!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄
- **監測密度**：訪視在篩選、基準、第 1、3、6、9、12 個月，其後每 4 個月一次，且每次訪視都在中央實驗室抽血測 eGFR 與血鉀。<!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄
- **暫停／再啟動規則**：血鉀 >5.5 mmol/L 即停藥 72 小時，待降至 ≤5.0 mmol/L 才以 10 mg/day 重啟。<!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄

即使在這樣的保護下，中央實驗室血鉀 >5.5 mmol/L 者仍達 146/776（18.8%）vs 95/776（12.2%），>6.0 mmol/L 者 34/786（4.3%）vs 18/784（2.3%）；且 Table 2 註腳記載有一位受試者血鉀達 7 mmol/L 而未住院（列為 life-threatening，1 人，0.1%）。<!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄

也就是說：**「no hospitalizations」這句話，恰好落在整篇論文最需要精確的那一格**。真實世界中沒有 K≤4.8 的入場門檻、沒有中央實驗室、沒有 72 小時停藥規則。

RALES 的自然實驗提供了量級：Juurlink 等人在安大略觀察到，在近期因心衰竭住院、正在使用 ACE inhibitor 的高齡病人中，RALES 發表後 spironolactone 處方率由 1994 年每 1000 人 34 張升至 2001 年底 149 張；同族群因高血鉀住院率由每 1000 人 2.4 升至 11.0（P<0.001），相關死亡率由 0.3 升至 2.0（P<0.001）；相較預期值，2001 年單一年度多出 560 件（95% CI 285–754）高血鉀相關住院與 73 件（95% CI 27–120）院內死亡。<!-- src:原始PDF/Juurlink_2004_15295047.md --> 📄 作者更估算，RALES 後每多開 1000 張 spironolactone 處方，就對應多出 50 件高血鉀住院（逐字連續片段：`led to 50 additional admissions for hyperkalemia.`）。<!-- src:原始PDF/Juurlink_2004_15295047.md --> 📄 而 RALES 試驗本身高血鉀僅發生於 2% 的治療組病人；Juurlink 指出這個低比例可能反映異常密集的實驗室監測、限制其他致高血鉀藥物，或排除了進展性腎病病人（逐字連續片段：`ally close laboratory monitoring, restriction of other`）。<!-- src:原始PDF/Juurlink_2004_15295047.md --> 📄

這正是 FIND-CKD 目前這句 Discussion 有可能重演的模式：**試驗條件下的低事件率被文字進一步壓縮成零，再被轉譯成臨床印象。**

（注意：finerenone 是非固醇類 MRA，藥理與 spironolactone 不同；Juurlink 的資料**不是** finerenone 的風險估計，僅用於說明「試驗安全數據外推到常規照護」的普遍失真機制。撰稿時務必維持這個界線。）

> **【第二輪新增．新穎度警訊】** 這條「以 Juurlink／RALES 提醒外推風險」的論證路線**已有前例**：2021 年針對 FIDELIO-DKD 的 NEJM correspondence 中，Bunkete、Mohamadou、Galichon 三位作者即寫道「這個第三期臨床試驗的高血鉀安全數據，在外推至日常實務前應審慎解讀」（作者自存版逐字：`the safety data concerning hyperkalemia from this phase 3 clinical trial should be`，次行 `interpreted with caution before extrapolating it to everyday practice.`），且其參考文獻 2 正是同一篇 Juurlink（逐字：`Rates of hyperkalemia after publication of`）。<!-- src:原始PDF/Bunkete_2021_fidelio-correspondence.md --> ⚠️📄（**作者自存版 / HAL preprint 版，非出版社正式版；不得引用頁碼**）
>
> 意涵：**「外推警示 + Juurlink」本身不再是新穎論點**。本信的新穎性必須完全建立在「FIND-CKD 同篇內部 Table 2 與 Discussion 互相排斥」這個事實上，而非建立在 RALES 類比上。此即上方「選項 B」把 Juurlink 換成 INFINITY 的理由。
>
> **同時要注意的相反面**：INFINITY 的次群分析顯示，finerenone 對「需住院之嚴重高血鉀」的效應**因糖尿病狀態而異**——有糖尿病者 HR 6.21（95% CI 3.18–12.12，p<0.0001），**無糖尿病者 HR 1.48（95% CI 0.47–4.67，p=0.50），交互作用 p=0.034**。<!-- src:原始PDF/Neuen_2026_infinity-pooled.md --> 📄 也就是說，在 FIND-CKD 這種非糖尿病族群中，高血鉀住院的**相對風險增幅並未達統計顯著**。這對本信是重要的自我限制：本信主張的是「**紀錄必須正確**」，**不是**「finerenone 在非糖尿病 CKD 造成顯著的高血鉀住院風險」。信中任何措辭都不得越過這條線，否則作者可用此 HR 直接反駁。

## 2.4 為什麼不用 BARACK-D 當主軸（但值得知道）

FIND-CKD 的 Discussion 引用 BARACK-D 作為固醇類 MRA 耐受性差的對照，寫成「約 1400 名 CKD 受試者中超過一半在隨機分派後 6 個月內停用 spironolactone……hyperkalemia 佔停藥原因逾 10%」。<!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄

回到 BARACK-D 原文核對：共 1,434 名英國基層醫療成人隨機分派；分派至 spironolactone 者有三分之二在 6 個月內停藥，主因是達到預先設定的安全停藥標準（逐字連續片段：`to spironolactone stopped treatment within 6 months, predominantly`）；最常見停藥原因為 eGFR 下降達停藥標準（n=239, 35.4%），其次為副作用退出（n=128, 18.9%）與高血鉀（n=54, 8.0%）；主要結果 113/677（16.7%）vs 111/695（16.0%），HR 1.05（95% CI 0.81–1.37）。<!-- src:原始PDF/Hobbs_2024_BARACK-D.md --> 📄

判讀：FIND-CKD 說「超過一半」，BARACK-D 說「三分之二」——**方向一致、保守表述，不構成錯誤**，因此不適合作為投書標的。它的價值在於背景：真實世界（英國基層照護）的 MRA 停藥率與試驗描述之間本就存在落差，這強化 §2.3 的外推論點，但**不應寫進 175 字**。

## 2.5 哪些角度已被佔據（因此新穎度不足）

**第二輪更新**：FIDELIO-DKD correspondence（部分）、DAPA-CKD correspondence（完整）、FIGARO-DKD、CONFIDENCE、JAMA glomerular、INFINITY 六者全文已落地，以下改為**內文層級**的具體比對；僅 CONFIDENCE correspondence 仍為 📌。

### （a）既有 correspondence 各封信的實際論點

| 交流 | 誰、問了什麼 | 是否與本信重疊 |
|---|---|---|
| **FIDELIO-DKD**（*N Engl J Med* 2021, DOI 10.1056/NEJMc2036175）— Bunkete、Mohamadou、Galichon 之投書 ⚠️📄（**作者自存版**，非正式版；**本檔未取得 Bakris/Agarwal 的 Reply 本文**） | 三點：(a) finerenone 的效果可能是非專一性的、取決於血壓改善，因對照組平均收縮壓全程停在 138 mmHg（逐字：`population with a large proportion of patients remaining above therapeutic goals throughout`／`the study (mean systolic blood pressure stable at 138mmHg in control patients).`）；(b) 第三期試驗的高血鉀安全數據外推到日常實務前應審慎解讀（引 Juurlink）；(c) 不同意「因 4.6% 併用 SGLT2i 而低估療效」的解讀，反而**不能排除**併用 finerenone 與 SGLT2i（兩者皆有利尿作用）的有害效應（逐字：`one cannot exclude a deleterious`）。<!-- src:原始PDF/Bunkete_2021_fidelio-correspondence.md --> ⚠️📄 | **(a) 與本檔第三優先（血壓中介）重疊 → 該角度新穎度顯著下降。(c) 與本檔第二優先（SGLT2i）部分重疊。(b) 與本檔 §2.3 的 Juurlink 論證重疊。** 但**沒有任何一封提及「試驗自身安全性表述前後不一致」** → 本信主軸未被佔據。 |
| **DAPA-CKD**（*N Engl J Med* 2021;384:388-390, DOI 10.1056/NEJMc2032809）📄 正式版 | Vogt（Amsterdam UMC）問：療效是否可完全歸因於矯正容積過多，要求提供受試者每日鈉攝取與利尿劑劑量／種類。Yasuda 與 Isobe（Hamamatsu）問：SGLT2i 能否在無高血糖下經 tubuloglomerular feedback 矯正絲球體高壓，並問無糖尿病者的白蛋白尿降幅、以及 renal functional reserve 之角色。Heerspink、Langkilde、Wheeler 回覆：基線 1882 人（43.7%）使用利尿劑，主要複合終點的 39% 相對風險下降在使用與未使用利尿劑者間一致（P for interaction = 0.96），但試驗未收 24 小時尿液、未測尿量以評估鈉攝取。<!-- src:原始PDF/Vogt_2021_dapa-ckd-correspondence.md --> 📄 | **完全不重疊**：三封信皆為機制／容積／血流動力學題目，無一觸及高血鉀，更無一觸及安全性表述一致性。 |
| **CONFIDENCE**（*N Engl J Med* 2025;393:1753-1755, DOI 10.1056/NEJMc2513088）📌 | **全文仍未落地**（第二輪逐一嘗試 Unpaywall／OpenAlex／PMC／Europe PMC／CORE／BASE／Semantic Scholar／Tavily／Google Scholar／Sci-Hub 全部失敗，見 `NEED-TO-DO.md`）。已知 metadata：4 筆 PMID 41160829/41160830/41160831/41160832，投書人含 Silver S；Assil／Hough；Romagnani／Soler／Fervenza；回覆為 Agarwal／Rossing／Mann。📌 | **不可判定**。此為本檔目前唯一的新穎度盲點，投稿前必須以機構訂閱人工核對。 |

**結論（對本信的直接意涵）**：在已落地的兩組 correspondence（FIDELIO-DKD 之一封、DAPA-CKD 全部三封）中，**沒有任何一封提出「高血鉀住院」相關的問題，也沒有任何一封指出試驗內部安全性敘述互相矛盾**。本信的角度未被佔據。⚠️ 唯二保留：(1) FIDELIO-DKD 的 Bakris/Agarwal Reply 本文未落地；(2) CONFIDENCE correspondence 完全未落地。

### （b）類別效應對照：FIDELIO-DKD 與 FIGARO-DKD 的高血鉀住院數字

| | FIDELIO-DKD 📄 | FIGARO-DKD 📄 | FIND-CKD 📄 |
|---|---|---|---|
| 安全性族群 | N=2827 vs 2831 | N=3683 vs 3658 | N=793 vs 791 |
| 高血鉀導致住院 | 40（1.4%）vs 8（0.3%） | **21（0.6%）vs 2（0.1%）** | 7（0.9%）vs 5（0.6%） |
| 因高血鉀永久停藥 | 64（2.3%）vs 25（0.9%） | **46（1.2%）vs 13（0.4%）** | 12（1.5%）vs 1（0.1%） |
| 研究者通報高血鉀 | 516（18.3%）vs 255（9.0%） | **396（10.8%）vs 193（5.3%）** | — |
| 中央實驗室 K >5.5 | — | **495/3677（13.5%）vs 233/3655（6.4%）** | 146/776（18.8%）vs 95/776（12.2%） |
| 中央實驗室 K >6.0 | — | **86/3677（2.3%）vs 43/3655（1.2%）** | 34/786（4.3%）vs 18/784（2.3%） |
| 納入 K 門檻 | ≤4.8 mmol/L | ≤4.8 mmol/L（逐字：`potassium level of 4.8 mmol per liter or less at`；上調劑量亦要求 `level was no more than 4.8 mmol per liter`） | ≤4.8 mmol/L |

來源：FIDELIO <!-- src:原始PDF/Bakris_2020_FIDELIO-DKD.md --> 📄；FIGARO <!-- src:原始PDF/Pitt_2021_figaro-dkd.md --> 📄；FIND-CKD <!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄。FIDELIO 未報告致死性高血鉀不良事件（逐字連續片段：`perkalemia adverse events were reported.`，其前一行結尾為 `No fatal hy-`）<!-- src:原始PDF/Bakris_2020_FIDELIO-DKD.md --> 📄。

> **這張表最有力的一格不是數字，而是措辭。** FIGARO-DKD 在敘述性安全性段落中主動把住院比例寫進正文：`few events led to permanent discontinuation of the regimen (in 1.2% and 0.4% of the patients, respectively) or hospitalization (in 0.6% and 0.1%).`<!-- src:原始PDF/Pitt_2021_figaro-dkd.md --> 📄
>
> ⚠️ **章節歸屬更正（LlamaParse 重轉後查明）**：此句位於 FIGARO-DKD 的 **Results**（小標 `**SAFETY OUTCOMES AND VITAL SIGNS**`），**不在 Discussion**。本檔第一版依 pdftotext 雙欄輸出誤判為 Discussion（同一實體行的右欄恰為 Discussion 文字）。FIGARO-DKD 的 Discussion 只寫發生率、未寫住院數（逐字：`the incidence of hyperkalemia with finerenone treatment was lower (10.8% vs. 18.3%)`）。<!-- src:原始PDF/Pitt_2021_figaro-dkd.md --> 📄
>
> 更正後的對比仍成立，但層級須寫準：**同一個 finerenone 開發計畫在 2021 年於敘述性安全性文字中如實揭露高血鉀住院比例，而 2026 年 FIND-CKD 的 Discussion 卻寫成 `no hospitalizations`**<!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄。這使「這只是措辭疏忽」的辯護變得更難成立，也讓本信的請求顯得合乎該計畫自身的既有標準。此點屬中文論證，175 字英文稿不放（選項 B 已改用更精簡的 INFINITY 算術）。

### （c）INFINITY pooled IPD：同一團隊如何處理同一個數字

- 納入 FIDELIO-DKD、FIGARO-DKD、FIND-CKD 三試驗共 **14 574 名**受試者（逐字：`14 574 participants`），其中 FIND-CKD 為 1584 名非糖尿病 CKD 患者（逐字：`the effects of finerenone in 1584 patients with non-diabetic`）。<!-- src:原始PDF/Neuen_2026_infinity-pooled.md --> 📄
- **主要安全性終點的定義**：`were hyperkalaemia and acute kidney injury, defined as` / 次行 `events leading to hospitalisation, to focus on clinically` / 再次行 `meaningful events.`——亦即該團隊自己把「導致住院的高血鉀」定義為**臨床上有意義的**安全性事件。<!-- src:原始PDF/Neuen_2026_infinity-pooled.md --> 📄
- 合併結果：`Any treatment-emergent hyperkalaemia` 1043（14.3%）vs 553（7.6%）；`Any serious hyperkalaemia` 77（1.1%）vs 21（0.3%）；其下 `Requiring hospitalisation` **68（0.9%）vs 15（0.2%）**；`Life threatening` 5（0.1%）vs 5（0.1%）；`With fatal outcome` 0 vs 0。中央實驗室 K >5.5 為 1218/7154（17.0%）vs 565/7128（7.9%），>6.0 為 245/7201（3.4%）vs 98/7179（1.4%）。<!-- src:原始PDF/Neuen_2026_infinity-pooled.md --> 📄
- 正文逐字：`hospitalisation occurred very infrequently (68 [0·9%]`（其前一行結尾為 `vs 39 [0·5%] with placebo). Hyperkalaemia requiring`）。<!-- src:原始PDF/Neuen_2026_infinity-pooled.md --> 📄
- **交互作用**：`increased risk observed in participants with diabetes` / `versus without diabetes (HR 6·21 [95% CI 3·18–12·12],` — 有糖尿病者 HR 6.21，無糖尿病者 1.48（0.47–4.67，p=0.50），pinteraction=0.034。<!-- src:原始PDF/Neuen_2026_infinity-pooled.md --> 📄
- **算術核對（本檔作者自行加總，非原文陳述）**：40+21+7 = 68、8+2+5 = 15。三試驗各自 Table 的住院數恰好加總為 INFINITY 的合計，**FIND-CKD 的 7 與 5 被計入了**。⚠️ 注意：三試驗安全性族群相加為 7303／7280，與 INFINITY 表格分母 7282／7265 不完全相同，故**只能主張事件數相符，不得主張分母相符**。

### （d）JAMA glomerular 分析

- 為 FIND-CKD 的 **prespecified exploratory subgroup analysis**（逐字：`Prespecified exploratory subgroup analysis of a phase 3,`）。<!-- src:原始PDF/Neuen_2026_jama-glomerular.md --> 📄
- Abstract RESULTS 段逐字：`Of 1584 participants, 903 (57.0%) had investigator-reported glomerular disease,`，其中 IgA 腎病變 416（46.1%）、FSGS 215（23.8%）、膜性腎病變 90（10.0%）；finerenone n=446 vs placebo n=457。<!-- src:原始PDF/Neuen_2026_jama-glomerular.md --> 📄 （**注意**：903/1584（57.0%）此一比例在 FIND-CKD **設計論文**中亦可查得 <!-- src:原始PDF/Heerspink_2025_FIND-CKD-design.md --> 📄，但 446/457 的分組人數與各亞型細分**只能掛 JAMA**。）
- 主要結果：total eGFR slope 至 32 個月為 −3.50 vs −4.23 ml/min/1.73 m²/yr（差 0.73；95% CI 0.22–1.24）；12 個月白蛋白尿降 42%（95% CI 35%–48%）；kidney failure 或 ≥40% eGFR 下降 7.42 vs 9.60 events/100 patient-years，HR 0.74（95% CI 0.57–0.97）。<!-- src:原始PDF/Neuen_2026_jama-glomerular.md --> 📄
- **安全性措辭**（逐字連續片段）：`no imbalance in serious investigator-reported hyperkalemia events (0.9% in both treatment arms)`；永久停藥 2.7% vs 3.9%。<!-- src:原始PDF/Neuen_2026_jama-glomerular.md --> 📄 **JAMA 主文未報告高血鉀住院數**；它也**沒有**重複「no hospitalizations」的說法。

#### 【第四輪新增】Supplement 2 之 eTable 4：glomerular 次群的完整安全性表（已解封，可引用）

`eTable 4. Summary of Participants With Glomerular Diseases With Treatment-Emergent AEs`（finerenone n=446 vs placebo n=457）<!-- src:原始PDF/Neuen_2026_jama-glomerular-supp2.md --> 📄：

| 列名（逐字） | Finerenone (n=446) | Placebo (n=457) |
|---|---|---|
| `Any hyperkalemia (AESI)` | 73（16.4%） | 70（15.3%） |
| 　`Related to study drug` | 54（12.1%） | 49（10.7%） |
| 　`Leading to permanent discontinuation of study drug` | **8（1.8%）** | **2（0.4%）** |
| `Any serious hyperkalemia` | 4（0.9%） | 4（0.9%） |
| 　`Related to study drug` | 2（0.4%） | 1（0.2%） |
| 　`Leading to hospitalization` | **3（0.7%）** | **4（0.9%）** |
| 　`Life-threatening` | 1（0.2%） | 0 |
| 　`Leading to death` | 0 | 0 |
| `Any SAE` | 87（19.5%） | 98（21.4%） |
| 　`Leading to hospitalization`（全因） | 85（19.1%） | 94（20.6%） |
| 　`Life-threatening`（全因） | 2（0.4%） | 5（1.1%） |
| 　`Leading to death`（全因） | 2（0.4%） | 1（0.2%） |

<!-- src:原始PDF/Neuen_2026_jama-glomerular-supp2.md --> 📄

**判讀（三點，請嚴格區分）：**

1. **對本信主軸是強化，但方向與直覺相反。** eTable 4 顯示：即使把範圍縮到 FIND-CKD 的 glomerular 次群（903 人中的安全性族群），`Any serious hyperkalemia` 之 `Leading to hospitalization` 仍是 **3 vs 4，不是零**。<!-- src:原始PDF/Neuen_2026_jama-glomerular-supp2.md --> 📄 換言之，**在整個 finerenone 開發計畫已公開的所有層級中，沒有任何一格的高血鉀住院數為 0**——這正是 §4.4「更窄類別」退路被封死的第三條佐證（見 §4.4）。
2. **定義注意（極重要）**：eTable 4 的 hyperkalemia 是 **AESI、investigator-reported、MedDRA preferred term** 定義，**不是**中央實驗室血鉀門檻計數——腳註逐字：`Hyperkalemia was an AESI and defined as any investigator-reported AEs with MedDRA codes corresponding to the preferred terms hyperkalemia or blood potassium increased.`<!-- src:原始PDF/Neuen_2026_jama-glomerular-supp2.md --> 📄 因此 **eTable 4 不得被用來支持任何關於 K>5.5／>6.0 mmol/L 事件數的陳述**；那類數字只能掛 FIND-CKD 主文。
3. **對本信是重要的自我限制（必須內化，不可越線）**：在此次群中，`Any hyperkalemia (AESI)` 兩組幾乎相同（16.4% vs 15.3%），`Any serious hyperkalemia` 完全相同（0.9% vs 0.9%），住院數**在數值上還略低於安慰劑**（3 vs 4），且 `Any SAE`、全因住院、life-threatening、death 均**未見 finerenone 較高**。<!-- src:原始PDF/Neuen_2026_jama-glomerular-supp2.md --> 📄 唯一明顯不對稱的是**因高血鉀永久停藥 8（1.8%）vs 2（0.4%）**。**任何把 eTable 4 寫成「顯示廣泛額外傷害」的措辭都不被資料支持**，且會被作者一句話反駁。本信主張始終只有一句：**紀錄必須正確**。

> ⚠️ **eTable 4 的一處來源端內部不一致（勿引用該列）**：`Related to study drug`（Any AE 之下）finerenone 欄印為 `177 (26.2)`，但 177/446 = 39.7%，26.2% 對應的是 117/446；placebo 欄 `86 (18.8)` 則自洽（86/457 = 18.8%）。已用 `pdftotext -f 16 -l 16` 核對來源 PDF，**PDF 原文即為 `177 (26.2)`**，故此為 **JAMA supplement 本身的印刷／製表不一致，非轉檔錯誤**。<!-- src:原始PDF/Neuen_2026_jama-glomerular-supp2.md --> 📄 **本檔一律不引用該列**；若日後需要「藥物相關 AE」比率，須另行向作者確認。

#### 【第四輪新增】Supplement 2 之亞型層級數據（biopsy-confirmed cohort，n=712）

- eFigure 2A（total eGFR slope 差）：Overall `0.89 (0.31 to 1.47)`；IgAN `0.66 (-0.12 to 1.45)`（n=213/174）；FSGS `1.36 (0.16 to 2.56)`（n=73/94）；Membranous nephropathy `1.26 (-0.51 to 3.03)`（n=42/34）；MPGN `0.12 (-3.17 to 3.41)`（n=8/17）；P_interaction `0.865`。<!-- src:原始PDF/Neuen_2026_jama-glomerular-supp2.md --> 📄
- eFigure 6（kidney failure 或 ≥40% eGFR 下降）：Overall `0.74 (0.55 to 0.99)`；IgAN `0.81 (0.54 to 1.21)`；FSGS `0.68 (0.38 to 1.21)`；Membranous `0.87 (0.30 to 2.54)`；MPGN `0.54 (0.06 to 5.23)`；P_interaction `0.956`。<!-- src:原始PDF/Neuen_2026_jama-glomerular-supp2.md --> 📄
- **對本信的意涵：無**（本信不談療效異質性）。但這組數字**進一步關閉**「各 glomerular 亞型效果是否一致」這個備選角度——所有 P_interaction 均遠大於 0.05，且 MPGN（n=8 vs 17）之 CI 寬到完全不具資訊量，任何以 MPGN 為題的提問都會被視為 ghost novelty。詳見「不建議的角度」表。
- ⚠️ **轉檔風險註記**：eFigure 2／3／6／7 的數字在來源 PDF 中**以圖形（forest plot）呈現、不在文字層**，`pdftotext` 抓不到，僅能靠 LlamaParse 的視覺抽取。深讀者已將 eFigure 6 之 PDF p.22 轉圖目視逐位核對一致；**eFigure 2／3／7 僅做結構性抽查**。若要在正式稿件中逐字使用 eFigure 2／3／7 的個別 CI，**須先再做一次 pdftoppm 目視核對**。

### （e）本信角度的最終佔據性判定

| 檢查項 | 結果 |
|---|---|
| 是否有前例質疑 FIND-CKD 的 Table 2 vs Discussion 不一致？ | 已落地文獻中**無**（FIND-CKD 2026-06-04 上線，INFINITY 與 JAMA 於 2026-06-05 上線，均未評論此點） |
| 是否有前例以「高血鉀住院」為題投書 finerenone 試驗？ | 已落地之 FIDELIO 投書（Bunkete）談的是「外推應審慎」，**未指出住院數字**；DAPA-CKD 三封信與高血鉀無關 |
| 剩餘盲點 | (1) FIDELIO-DKD 之 Bakris/Agarwal Reply 本文未落地；(2) CONFIDENCE correspondence 全部未落地 ⚠️ 投稿前必須以機構訂閱人工核對這兩者。**【第四輪更新】**原列為盲點的 FIND-CKD NEJM appendix 與 JAMA Supplement 2 已落地並查核完畢，**均未出現「no hospitalizations」式的表述、亦未提供可供退守的第三種住院數字**（見 §4.3、§4.4） |

## 2.6 邏輯鏈總結

1. 高血鉀住院是 FIND-CKD 的 **prespecified** 安全性終點 <!-- src:原始PDF/Heerspink_2025_FIND-CKD-design.md --> 📄；
2. Results／Table 2 給出 7 vs 5 <!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄；
3. Discussion 說 no hospitalizations <!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄；
4. 兩者不能同時為真 → 作者必須擇一回答；
5. 這一格的正確性直接決定臨床醫師如何在**沒有 K≤4.8 門檻、沒有中央實驗室排程**的常規照護中做風險溝通 <!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄；
6. RALES 後的自然實驗證明這種轉譯失真會造成可測量的住院與死亡增量 <!-- src:原始PDF/Juurlink_2004_15295047.md --> 📄。
7. **【第二輪新增】** 同一研究團隊在 INFINITY 中把「導致住院的高血鉀」定義為主要安全性終點，並報出三試驗合計 68（0.9%）vs 15（0.2%）<!-- src:原始PDF/Neuen_2026_infinity-pooled.md --> 📄；同計畫的 FIGARO-DKD Discussion 亦如實寫出住院比例 <!-- src:原始PDF/Pitt_2021_figaro-dkd.md --> 📄。因此「no hospitalizations」既不符合本試驗的表，也不符合本計畫自身的既有敘述標準。

這條鏈上每一環都可 grep，沒有任何一環需要作者未公開的資料。**這是它比其他所有角度都強的唯一理由。**

---

# 三、備選角度（第二、三優先）與不建議的角度

## 第二優先：基準僅 17.0% 使用 SGLT2i，是否代表當代標準治療

- 事實：1580 名（99.7%）使用 RAS inhibitor，270 名（17.0%）使用 SGLT2i；Table 1 為 finerenone 135（17.0%）vs placebo 135（17.1%）。<!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄
- SGLT2i 使用者的 slope 差為 0.84（95% CI −0.06 至 1.73），未使用者 0.65（95% CI 0.25 至 1.06）。<!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄
- 可提問：能否提供 **treatment-emergent SGLT2i 使用**（試驗期間新開始者）的資料，或依時間變動的 SGLT2i 暴露分析？
- **風險**：主文 Discussion 已主動承認此限制（`we hypothesize that the use of both finerenone and SGLT2 inhibitors may provide complementary effects, this was not directly tested in the present trial`）<!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄，且 CONFIDENCE 的 correspondence 交流已存在 📌。新穎度中等。

**【第二輪新增】CONFIDENCE 全文落地後，這個角度的證據面貌變得具體——也變得更不利於投書：**

- CONFIDENCE 為三臂隨機試驗（finerenone＋empagliflozin 併用 vs finerenone 單用 vs empagliflozin 單用），安全性族群 268／264／266，合計 798 人。<!-- src:原始PDF/Agarwal_2025_confidence.md --> 📄
- **主要終點是 180 天的尿白蛋白／肌酸酐比值（UACR）相對變化，不是 eGFR slope，也不是臨床終點**：併用組較 finerenone 單用多降 29%（LS mean ratio 0.71；95% CI 0.61–0.82；P<0.001），較 empagliflozin 單用多降 32%（0.68；95% CI 0.59–0.79；P<0.001）。<!-- src:原始PDF/Agarwal_2025_confidence.md --> 📄
- **族群為第 2 型糖尿病 CKD**（eGFR 30–90、UACR 100 至 ≤5000 mg/g），**與 FIND-CKD 的非糖尿病族群不同**。<!-- src:原始PDF/Agarwal_2025_confidence.md --> 📄
- 安全性：高血鉀 25（9.3%）併用 vs 30（11.4%）finerenone 單用 vs 10（3.8%）empagliflozin 單用；K >5.5 為 40/262（15.3%）vs 48/258（18.6%）vs 25/257（9.7%）；K >6.0 為 12/263（4.6%）vs 12/262（4.6%）vs 7/262（2.7%）。<!-- src:原始PDF/Agarwal_2025_confidence.md --> 📄 作者敘述併用時高血鉀頻率「相對低約 15 至 20%」（逐字：`tively lower by approximately 15 to 20% with`）。<!-- src:原始PDF/Agarwal_2025_confidence.md --> 📄 **CONFIDENCE 的 Table 3 完全未列「高血鉀導致住院」一列**——這反而再次凸顯本檔主軸（住院這一格的紀錄品質）在整個 finerenone 計畫中並未被系統性處理。
- INFINITY 亦已把此題處理掉：合併三試驗基線 SGLT2i 使用者僅 1142（7.8%），且複合腎臟終點的療效在 SGLT2i 使用與否間一致（森林圖交互作用 p=0.99），作者並在 limitations 自承試驗開始時 SGLT2i 尚非 CKD 指引建議用藥（逐字：`before SGLT2 inhibitors were guideline-recommended`）。<!-- src:原始PDF/Neuen_2026_infinity-pooled.md --> 📄
- **判定**：CONFIDENCE（併用起始的 180 天 UACR 證據）＋ INFINITY（一致性與 limitation 自陳）已把這個角度的可提問空間壓縮到很小；再加上 2021 年 FIDELIO 投書已提過「不能排除 finerenone＋SGLT2i 併用的有害效應」<!-- src:原始PDF/Bunkete_2021_fidelio-correspondence.md --> ⚠️📄（作者自存版）。**維持第二優先，但新穎度應下修為「低至中等」。**

## 第三優先：約 5 mmHg 的收縮壓差異是否中介腎臟效益

- 事實：第 3 個月收縮壓變化 −5.1 mmHg（finerenone）vs −0.1 mmHg（placebo）；舒張壓 −3.1 vs 小於 −0.1 mmHg。<!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄
- 對照：FIDELIO-DKD 的血壓效應較小（第 1、12 個月收縮壓變化 −3.0 與 −2.1 mmHg vs placebo −0.1 與 0.9 mmHg）。<!-- src:原始PDF/Bakris_2020_FIDELIO-DKD.md --> 📄 FIND-CKD 的 5.0 mmHg 差距明顯較大，提問有立足點。
- 正確措辭：血壓是**隨機化之後**產生的變項，屬 mediator 而非 confounder；應要求 causal mediation analysis 或依早期血壓反應分層的描述性結果，**不可**要求「調整血壓後重算」。
- **風險**：需要作者做新分析，175 字內難以說清方法學要求。
- **【第二輪新增．新穎度下修】** 這個角度**已有明確前例**：2021 年 FIDELIO-DKD 的 correspondence 中，Bunkete 等人第一點即主張 finerenone 的效果可能是非專一性的、取決於血壓改善（逐字：`finerenone's effect might be non-specific, depending on blood pressure improvement in a`）。<!-- src:原始PDF/Bunkete_2021_fidelio-correspondence.md --> ⚠️📄（作者自存版）**由於本檔未取得 Bakris/Agarwal 的 Reply 本文，無法判斷作者當時如何回應**——這反而使重複投同一題的風險更高（可能被編輯視為已答覆過的問題）。建議由第三優先**下修至第四優先之後**。
- 另可補充的量級對照（已落地）：FIGARO-DKD 明言 finerenone 對血壓的效應「modest」——finerenone 與 placebo 在收縮壓變化上的平均差為第 4 個月 −3.5 mm Hg、第 24 個月 −2.6 mm Hg（逐字連續片段：`sure was –3.5 mm Hg at month 4 and –2.6 mm Hg`）；基線收縮壓 135.8±14.0 mm Hg、基線血鉀 4.33±0.43 mmol/L。<!-- src:原始PDF/Pitt_2021_figaro-dkd.md --> 📄 對照 FIND-CKD 第 3 個月的 5.0 mm Hg 組間差 <!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄，FIND-CKD 的血壓效應確實較大——**但這強化的是「該問」，不改變上述「已被 FIDELIO 投書問過」的新穎度問題。**

## 第四優先：hierarchical testing 的解讀邊界

- 事實：kidney-only composite HR 0.78（95% CI 0.60–1.01，P=0.06）；CV composite 僅 10 vs 16 件，HR 0.60（95% CI 0.27–1.33）。<!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄
- 論點：階層檢定在第三層未達 P<0.05 後，CV composite 不能作為 confirmatory claim；FIND-CKD 本質仍是 **eGFR slope trial with supportive event data**。
- **風險**：主文已寫 `our trial was not powered to assess the effects of the trial regimens on clinical outcomes`<!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄，編輯可能認為重複。

## 不建議的角度

| 角度 | 不建議原因 |
|---|---|
| 各 glomerular disease 亞型效果是否一致 | **已被完整回答**：JAMA 2026 的 prespecified exploratory 分析涵蓋 903/1584（57.0%）有 glomerular disease 者（IgAN 416、FSGS 215、膜性 90），並明示效果在各亞型間一致、亦不因基線 SGLT2i 使用而異（P for interaction = .16 與 .34）。<!-- src:原始PDF/Neuen_2026_jama-glomerular.md --> 📄 **【第四輪加強】** Supplement 2 的 biopsy-confirmed cohort（n=712）逐亞型森林圖亦全數無異質性：eGFR slope P_interaction `0.865`、kidney failure/≥40% 下降 P_interaction `0.956`，且 MPGN（n=8 vs 17）之 CI 寬至 `0.12 (-3.17 to 3.41)`／`0.54 (0.06 to 5.23)` 完全不具資訊量。<!-- src:原始PDF/Neuen_2026_jama-glomerular-supp2.md --> 📄 再問即為 ghost novelty |
| 「整體證據是否足夠」／跨病因一致性 | **已被完整回答**：INFINITY 合併 14 574 人，複合腎臟終點 HR 0.76（95% CI 0.68–0.86），且在 glycaemic status、CKD aetiology、baseline eGFR、albuminuria、SGLT2i 使用各層一致。<!-- src:原始PDF/Neuen_2026_infinity-pooled.md --> 📄 |
| 「非糖尿病 CKD 的高血鉀住院風險是否被低估」 | **不可投**：INFINITY 顯示無糖尿病者的高血鉀住院 HR 為 1.48（95% CI 0.47–4.67，p=0.50）。<!-- src:原始PDF/Neuen_2026_infinity-pooled.md --> 📄 本檔主張的是**紀錄一致性**，不是風險大小；越線即被此數據直接反駁 |
| 族群代表性（33.8% 女性、56.4% 亞裔、Black 僅 2.8%/1.9%）<!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄 | 主文 limitations 已逐項自陳，屬 ghost novelty |
| 用 flawed／misleading／invalid 等對抗性措辭 | NEJM 通信欄語域不符，且此題根本不需要 |
| 一封信同時談 hyperkalemia + SGLT2i + 血壓 + surrogate endpoint | 175 字必定失焦（本檔作者之編輯判斷，非引自任何來源） |

---

# 四、投稿時效與程序 caveats

## 4.1 已知的日期事實

- 主文標註：`This article was published on June 4, 2026, and updated on June 29, 2026, at NEJM.org.`<!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄
- 紙本卷期：`N Engl J Med 2026;395:533-45.`，頁眉為 `AUGUST 6, 2026`，Vol. 395 No. 6。<!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄
- 今日為 2026-08-09。

## 4.2 三週規則：條文原文已落地（2021 年版），但起算日仍須現場確認

**【第二輪更新】規則原文已落地（但為 2021 年版本）。** DAPA-CKD correspondence 的出版社正式版 PDF（*N Engl J Med* 2021;384:390）在版面右欄印有標題為 `INSTRUCTIONS FOR LETTERS TO THE EDITOR` 的欄位，逐字連續片段包括：

- `article must not exceed 175 words (excluding references) and must be received within 3 weeks after publication of the article.`（該句以 `Letters in reference to a *Journal* article` 起首，`*Journal*` 為斜體標記，故 grep 取其後之連續片段）
- `* A letter can have no more than five references and one figure or table.`
- `* A letter can be signed by no more than three authors.`
- `* All letters must be submitted through our online submission system at NEJM.org.`

<!-- src:原始PDF/Vogt_2021_dapa-ckd-correspondence.md --> 📄

> ⚠️ **重大限定**：這是 **2021 年 1 月 28 日該期**所印的 instructions。本檔**未落地** 2026 年版之 NEJM 投稿規則，**不得**據此斷言 2026 年仍為同樣條文。此段只證明「175 words／5 references／3 authors／3 weeks 這組規則在 2021 年確實存在且為官方文字」，可用於**規劃**，不可用於**保證**。

「3 週」自何日起算，原文並未定義（僅寫 `after publication of the article`）。可確定的只是**三個候選起算日彼此相差近兩個月**：6/4（online）、6/29（updated）、8/6（print issue）。三種可能：

| 起算日 | 截止日（若為 3 週） | 今日狀態 |
|---|---|---|
| 2026-06-04 online | 約 2026-06-25 | 已逾期 |
| 2026-06-29 updated | 約 2026-07-20 | 已逾期 |
| 2026-08-06 print | 約 2026-08-27 | 仍在窗口內 |

**行動順序（今天就做）：**

1. 登入 NEJM 投稿系統，查詢 FIND-CKD (NEJMoa2604625) 是否仍可被選為被評論文章。系統顯示的可選狀態就是唯一權威，不要靠推論。
2. 若仍開放 → 直接投第一節主稿。
3. 若已關閉 → 改走 **correction inquiry**：以同樣內容寄 NEJM 編輯部（不是寄給通訊作者本人），主旨建議寫成 Possible discrepancy between Table 2 and the Discussion — NEJMoa2604625（作者自撰主旨，非引文），並附上兩段原文逐字引用與頁碼（Results 與 Table 2 見 p.539–540；Discussion 見 p.543）。<!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄

## 4.3 投稿前最後檢查清單

- [ ] 重新檢視 NEJM 線上全文與 PDF，確認 2026-06-29 那次 update **是否已經修掉**「no hospitalizations」這句。若已修正，本信失去標的，應立即停止投稿。**這是最高優先的查核項。**
- [ ] 確認是否已有 erratum／correction 掛在 DOI 10.1056/NEJMoa2604625 下。
- [x] **【第四輪完成，2026-08-09】確認 Supplementary Appendix（Table S8 等）是否對 hyperkalemia 住院有第三種數字 →「沒有」。** FIND-CKD 主文之 NEJM Supplementary Appendix（42 頁）已落地為 `原始PDF/FIND-CKD_2026_nejm-appendix.md` 📄。逐項結論：
  - 附錄目錄僅列 Table S1–S8，其中**唯一涉及不良事件者為 `Table S8. Adverse Events by Primary System Organ Class (Safety Analysis Set).`**，粒度僅到 MedDRA **System Organ Class** 層級（例：`Metabolism and nutrition disorders` 209（26.4%）vs 176（22.3%）），**未拆出 hyperkalemia 這個 preferred term，亦無任何 hospitalization 子分類**；表格腳註逐字：`Participants were counted only once within each primary system organ class.`<!-- src:原始PDF/FIND-CKD_2026_nejm-appendix.md --> 📄
  - 對整份附錄以 `grep -ci` 計數：`hyperkalemia` = 0、`hyperkalaemia` = 0、`serious` = 0、`adjudicat` = 0。**附錄完全沒有 hyperkalemia 專屬表格、沒有安全性事件定義章節、沒有 SAE／adjudication 流程說明。**<!-- src:原始PDF/FIND-CKD_2026_nejm-appendix.md --> 📄（Supplementary Methods 之全部小節皆為統計方法：Central Laboratory Assessment、Primary Estimand、Alternative Estimand、Main Analytical Approach、Multiple Testing Procedure、Handling of Missing Data、Sensitivity Analyses for the Primary Endpoint、Analysis of eGFR Slopes Using Other eGFR Equations）
  - **對 §4.4 的影響**：作者**無法**從自家附錄裡找出「第三種住院數字」來退守 → §4.4 的「更窄類別」退路再少一條。但務必區分兩件事：**(a) 已證實**＝附錄不存在可供退守的第三種數字；**(b) 不成立**＝「附錄排除了 adjudicated vs investigator-reported 的定義差異」——附錄對 adjudication **保持沉默**，沉默不等於排除。§4.4 行文已依此措辭處理。
  - 副產品（非核心，存為第二輪材料）：Figure S7（`Change from Baseline in Serum Potassium`）之數值表顯示：第 0 個月兩組平均血鉀同為 4.5 mmol/L（N=793／791），其後 finerenone 組持續高於 placebo（例：第 6 個月 4.68 vs 4.52；第 44 個月 4.69 vs 4.55），組間差約 0.10–0.16 mmol/L 且維持至第 44 個月；圖說逐字：`Effects of finerenone and placebo on serum potassium levels from baseline to 44 months in the safety analysis set.`<!-- src:原始PDF/FIND-CKD_2026_nejm-appendix.md --> 📄 **175 字內用不到，不放主稿。**
  - 資料缺口（供作者回覆後追問用）：附錄 Table S2（Medications of Interest）**未列任何鉀結合劑**（patiromer／sodium zirconium cyclosilicate），全文 binder/patiromer/zirconium 均 0 命中 → 無法從附錄判斷高血鉀處置是否倚賴鉀結合劑。<!-- src:原始PDF/FIND-CKD_2026_nejm-appendix.md --> 📄
- [x] **【第四輪完成，2026-08-09】JAMA glomerular 之 Supplement 2（eTables/eFigures）已落地** 為 `原始PDF/Neuen_2026_jama-glomerular-supp2.md` 📄；eTable 4 顯示 glomerular 次群 `Any serious hyperkalemia` 之 `Leading to hospitalization` = 3（0.7%）vs 4（0.9%），**同樣不是零**（定義為 investigator-reported AESI，非中央實驗室門檻）。詳見 §2.5(d)。⚠️ 兩份 protocol PDF 依指示僅存 PDF、未轉 MD，**不得引用**。
- [ ] **【第二輪新增】** 以機構訂閱人工取得 **CONFIDENCE correspondence（DOI 10.1056/NEJMc2513088，4 封信）** 全文，確認其中是否已有人提出高血鉀住院或安全性敘述一致性的問題。**這是目前唯一未被排除的新穎度風險。**
- [ ] **【第二輪新增】** 以機構訂閱人工取得 **FIDELIO-DKD correspondence 之 Bakris/Agarwal/Filippatos Reply（PMID 33730470）**，確認作者當年如何回應「高血鉀安全數據外推應審慎」與「血壓中介」兩題；若已有明確回覆，第三優先（血壓）角度應直接放棄。
- [x] **【第三輪完成，2026-08-09】** INFINITY 線上 appendix（35 頁，mmc1.pdf 自 Elsevier CDN 直接下載）已落地為 `原始PDF/Neuen_2026_infinity-appendix.md`。**Table S6（appendix p 23）確認：Without diabetes 欄（N=793/791，即 FIND-CKD 全體）之 hyperkalaemia SAE `Requiring hospitalisation` = `7 (0·9%)` vs `5 (0·6%)`** <!-- src:原始PDF/Neuen_2026_infinity-appendix.md --> 📄。主稿選項 B 已依此從「算術吻合」升級為「直接引用」寫法（當時 167 words、2 refs；第四輪修訂措辭後為 **170 words**）。Figure S9（appendix p 33）另有依糖尿病狀態的森林圖。
- [ ] **【第二輪新增】** 於投稿介面確認 **2026 年版** NEJM letters instructions（175 words／5 refs／3 authors／3 weeks 是否仍適用）；本檔僅落地 2021 年版原文。
- [ ] 正文嚴格維持單一問題，不加入 SGLT2i、血壓、surrogate endpoint。
- [ ] 所有共同作者逐字核對 Table 2 與 Discussion 原文。
- [ ] 依投稿介面揭露利益衝突與 AI/LLM 輔助撰稿。
- [ ] 在 NEJM 做出決定前，不將同一英文內容公開於社群、部落格或其他期刊。

## 4.4 若作者回覆「指的是更窄的類別」

> **【第四輪結論：這條退路已正式封死（但封死的方式要說準）】**
>
> **(1) 附錄裡沒有第三種數字。** FIND-CKD 的 NEJM Supplementary Appendix 全部 42 頁中，唯一與不良事件相關的表是 `Table S8. Adverse Events by Primary System Organ Class (Safety Analysis Set).`，僅到 System Organ Class 層級、**未拆出 hyperkalemia、亦無 hospitalization 子分類**（腳註逐字：`Participants were counted only once within each primary system organ class.`），且全文 `hyperkalemia`／`hyperkalaemia`／`serious`／`adjudicat` 之 `grep -ci` 命中數皆為 **0**。<!-- src:原始PDF/FIND-CKD_2026_nejm-appendix.md --> 📄 **作者無法從自家附錄取得任何比 Table 2 更窄、且住院數為 0 的類別。**
>
> **(2) 連 glomerular 次群這個「更窄的族群」也不是零。** JAMA glomerular 分析的 eTable 4（finerenone n=446 vs placebo n=457）在**最窄的定義下**（investigator-reported AESI、MedDRA preferred term、且限 serious）仍報 `Leading to hospitalization` **3（0.7%）vs 4（0.9%）**。<!-- src:原始PDF/Neuen_2026_jama-glomerular-supp2.md --> 📄 亦即：同一團隊在同一批受試者上，**用了與主文不同的定義、切了更小的族群，得到的住院數依然不是 0。**
>
> **(3) 必須守住的界線（勿過度推論）**：附錄**沒有討論** adjudication 流程（`adjudicat` 0 命中），因此**不能**宣稱「附錄排除了 adjudicated vs investigator-reported 的定義差異」。若要在第二輪回應中援引此點，建議措辭為：*the Supplementary Appendix contains no table or definitional section that could supply such a narrower number, though it also does not address adjudication procedures directly*（作者自撰句，非引文）。**沉默 ≠ 排除**。
>
> **(4) 兩份 protocol PDF 不可用**：NEJM protocol（301 頁）與 JAMA Supplement 1（Bayer protocol）依指示僅落地 PDF、未轉 MD；後者更因 Type 3 自訂字型而**根本無法以文字層 grep**。其中可能存在的 stop/restart 門檻（>5.5 暫停、≤5.0 恢復）與 AESI 通報規則，**一律不得在本檔或稿件中引用**。所幸「>5.5 暫停 72 小時」這一點本檔原就掛在**主文** Trial procedures 段（逐字：`If the serum potassium level exceeded 5.5 mmol per liter, finerenone or placebo was withheld for 72 hours`）<!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄，不受影響。

預備第二輪回應素材（皆已落地、可 grep）：

- Table 2 已把住院列在 `Serious adverse event related to hyperkalemia` 之下，該層 Overall 為 8（1.0%）vs 5（0.6%），`Leading to hospitalization` 為 7（0.9%）vs 5（0.6%）——**已經是最窄的類別了**，不存在更窄的層級可供退守。<!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄
- 設計論文的 prespecified safety 條列僅寫到高血鉀住院此一層級，未再細分（逐字連續片段：`for hyperkalaemia and permanent discontinuation of study`）。<!-- src:原始PDF/Heerspink_2025_FIND-CKD-design.md --> 📄
- **【第二輪新增，最強的一段】** 同一團隊（Neuen、Heerspink、Agarwal 等）在 INFINITY 中把「以住院定義的高血鉀」明訂為主要安全性終點，理由正是要聚焦於臨床上有意義的事件（逐字連續片段：`were hyperkalaemia and acute kidney injury, defined as` / `events leading to hospitalisation, to focus on clinically` / `meaningful events.`）。<!-- src:原始PDF/Neuen_2026_infinity-pooled.md --> 📄 若作者主張 FIND-CKD Discussion 指的是某個「更窄的類別」，將與其自身於 INFINITY 採用的定義相衝突。
- **【第二輪新增，已於第三輪更正章節歸屬】** 同一開發計畫的 FIGARO-DKD 曾在**正文敘述**中如實寫出住院比例（逐字連續片段：`few events led to permanent discontinuation of the regimen (in 1.2% and 0.4% of the patients, respectively) or hospitalization (in 0.6% and 0.1%).`）。<!-- src:原始PDF/Pitt_2021_figaro-dkd.md --> 📄 ⚠️ 該句在 **Results**（小標 `**SAFETY OUTCOMES AND VITAL SIGNS**`）而非 Discussion（先前的 Discussion 標註為 pdftotext 雙欄誤判，已更正）。前例存在，故「正文敘述慣例上不寫住院比例」不成立；但**不得**再主張「FIGARO 的 Discussion 寫了住院數」。

---

## 附：「危險數字」清單（第二輪已大幅解封）

**【第二輪已解除的封鎖】**（原因：全文落地並完成 grep 驗證）

| 原被封鎖的數字 | 現況 | 正確掛法 |
|---|---|---|
| JAMA glomerular 分析的內文數字 | ✅ **解除** | 903/1584（57.0%）、IgAN 416（46.1%）／FSGS 215（23.8%）／膜性 90（10.0%）、n=446 vs 457、slope −3.50 vs −4.23（差 0.73；95% CI 0.22–1.24）、UACR −42%（35%–48%）、HR 0.74（0.57–0.97）→ 掛 <!-- src:原始PDF/Neuen_2026_jama-glomerular.md --> 📄。**注意**：903/1584 亦可掛設計論文，但 446/457 與各亞型細分**只能**掛 JAMA |
| INFINITY 的 n=14,574 與 HR | ✅ **解除** | `14 574 participants`、複合腎臟終點 HR 0.76（0.68–0.86）、kidney failure 0.85（0.74–0.99）、複合心血管 0.80（0.70–0.91）、HF 住院 0.78（0.66–0.92）、CV death 0.82（0.67–0.999）、all-cause death 0.88（0.79–0.99）、高血鉀住院 68（0.9%）vs 15（0.2%）→ 掛 <!-- src:原始PDF/Neuen_2026_infinity-pooled.md --> 📄 |
| FIGARO-DKD 內文數字 | ✅ **解除** | 高血鉀住院 21（0.6%）vs 2（0.1%）、永久停藥 46（1.2%）vs 13（0.4%）、K>5.5 495/3677（13.5%）vs 233/3655（6.4%）、主要複合終點 458/3686（12.4%）vs 519/3666（14.2%），HR 0.87（0.76–0.98），P=0.03 → 掛 <!-- src:原始PDF/Pitt_2021_figaro-dkd.md --> 📄 |
| CONFIDENCE 內文數字 | ✅ **解除** | 三臂 268/264/266（合計 798）、UACR ratio 0.71（0.61–0.82）與 0.68（0.59–0.79）、高血鉀 9.3%/11.4%/3.8% → 掛 <!-- src:原始PDF/Agarwal_2025_confidence.md --> 📄 |
| DAPA-CKD correspondence 各信論點 | ✅ **解除**（正式版全文） | Vogt／Yasuda-Isobe／Heerspink-Langkilde-Wheeler Reply 之論點與 1882（43.7%）用利尿劑、P for interaction = 0.96 → 掛 <!-- src:原始PDF/Vogt_2021_dapa-ckd-correspondence.md --> 📄 |

**【第四輪新解除的封鎖】**（原因：使用者以機構權限下載，LlamaParse 轉 MD 並完成 grep／逐字交叉驗證）

| 原被封鎖的數字 | 現況 | 正確掛法與紅線 |
|---|---|---|
| FIND-CKD 主文 Supplementary Appendix（Table S1–S8、Figure S1–S9、Supplementary Methods） | ✅ **解除** | Table S8 之 SOC 層級數字（例：`Metabolism and nutrition disorders` 209（26.4%）vs 176（22.3%）；Overall adverse events 542（68.3%）vs 517（65.4%））、Table S1 之 `Serum potassium level ≤4.8 mmol/l`、Central Laboratory Assessment 段之 local-lab dosing 陳述、Figure S7 血鉀時間曲線 → 掛 <!-- src:原始PDF/FIND-CKD_2026_nejm-appendix.md --> 📄。**紅線：附錄無 hyperkalemia 專項數字、無 serious／adjudication 定義（4 個關鍵字 grep 0 命中），不得從附錄推導任何高血鉀住院數。** |
| JAMA glomerular 之 Supplement 2（eTable 1–4、eFigure 1–7） | ✅ **解除** | eTable 4 之 `Any hyperkalemia (AESI)` 73（16.4%）vs 70（15.3%）、因高血鉀永久停藥 8（1.8%）vs 2（0.4%）、`Any serious hyperkalemia` 4（0.9%）vs 4（0.9%）、其 `Leading to hospitalization` 3（0.7%）vs 4（0.9%）；eFigure 2A／6 之亞型 CI 與 P_interaction；baseline 903（57.0%）→ 掛 <!-- src:原始PDF/Neuen_2026_jama-glomerular-supp2.md --> 📄。**三條紅線：(1) eTable 4 是 investigator-reported AESI，不得用來陳述 K>5.5／>6.0 事件數；(2) `Related to study drug` 之 `177 (26.2)` 列為來源端內部不一致（177/446=39.7%），一律不引；(3) eFigure 2／3／7 的數字僅存在於圖形層、pdftotext 抓不到，逐字使用前須再做 pdftoppm 目視核對。** |
| ~~JAMA Supplement 1（protocol）／NEJM protocol~~ | ❌ **仍封鎖** | 僅落地 PDF、未轉 MD → 見下方「仍然封鎖」 |

**【仍然封鎖，投稿時不得寫入】**

- **CONFIDENCE correspondence（DOI 10.1056/NEJMc2513088）各封信的具體論點** 📌 — 全文仍未落地（第二輪已窮盡 10 條管道，見 `NEED-TO-DO.md`）。僅可引「存在此交流」。
- **FIDELIO-DKD correspondence 中 Bakris/Agarwal/Filippatos 之 Reply 本文** 📌 — 本地僅有同 DOI 下 Bunkete 等人投書之**作者自存版**，**不得**用它推斷作者當時如何回覆。
- **Bunkete 投書的頁碼** ⚠️ — 該檔為 HAL 作者自存版，雖 metadata 標 `pp.e42`，本檔仍**不引用頁碼**、且引用時一律註明「作者自存版」。
- ~~INFINITY 線上 appendix~~ **【第三輪解封】** INFINITY appendix 已全文落地（`原始PDF/Neuen_2026_infinity-appendix.md`，35 頁）📄，Table S6 之 FIND-CKD 族群 7 vs 5 住院數已可直接引用（見 §1 核心論證基礎）。
- ~~JAMA 之 Supplement（eTable 4、eFigure 2/3/5/6/7 等）~~ **【第四輪解封】** 已全文落地為 `原始PDF/Neuen_2026_jama-glomerular-supp2.md` 📄 — 詳見下方新增解封表。
- ~~FIND-CKD 主文之 Supplementary Appendix（Table S8 等）~~ **【第四輪解封】** 已全文落地為 `原始PDF/FIND-CKD_2026_nejm-appendix.md` 📄 — 詳見下方新增解封表。
- **兩份 protocol PDF 的任何內容** ⚠️ — `FIND-CKD_2026_nejm-protocol.pdf`（301 頁）與 `Neuen_2026_jama-glomerular-supp1-protocol.pdf` 依指示**僅落地 PDF、未轉 MD**，**一律不得引用**；後者且因 Type 3 自訂字型無 ToUnicode CMap，`pdftotext` 輸出為亂碼，**即使轉檔也不可能以文字層 grep 驗證**，**不得聲稱曾對其做過 grep**。特別點名禁止引用的內容：高血鉀 stop/restart 具體門檻（>5.5 暫停／≤5.0 恢復）、AESI 通報時限規則、SAP 條文原文。
- **Nature Reviews Nephrology 評論的內容** 📌 — 連 metadata 都未經本流程驗證，**完全不引用**。
- **「FIND-CKD 貢獻了 7 與 5 件住院給 INFINITY」的敘述** ⚠️ — 這是本檔作者的**算術推論**（40+21+7=68、8+2+5=15），**不是**任何來源的原文陳述。投稿措辭必須寫成可自行驗證的形式（見 §1「選項 B」注意事項）。

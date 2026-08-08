# NEED-TO-DO：未取得全文的文獻清單

**用途**：本檔列出 FIND-CKD 文獻回顧流程中**嘗試取得但最終未落地全文**的文獻。所有標記 📌 的引用僅能使用 metadata（title/authors/journal/year/DOI/PMID），**不得**在 `評論短信 FIND-CKD.md` 或任何後續稿件中對其內文（樣本數、HR、百分比、結論）作具體斷言，直到本清單中的項目被劃記為已取得並完成 grep 驗證為止。

**狀態欄定義**：`fetched=false` 表示未取得任何可用全文；`content_verified=false` 表示內容未經本地 grep 驗證。凡下載工具回傳「不相符文獻」（title/DOI 與目標不符），一律視為 **POLLUTED**，立即刪除，不計入 fetched。

---

## 1. DAPA-CKD correspondence

| 項目 | 內容 |
|---|---|
| id | `dapa-ckd-correspondence` |
| 篇名/系列 | DAPA-CKD 讀者信與作者 Reply |
| 期刊 | *N Engl J Med* 2021;384:388-390 |
| DOI | 10.1056/NEJMc2032809 |
| PMID | 33503360 / 33503361 / 33503362（涵蓋此 DOI 的 3 筆） |
| 狀態 | fetched=false, content_verified=false |
| 未取得原因 | Paywall（NEJM correspondence，訂閱限定）。`download_with_fallback` 以模糊書名比對回傳不相符文獻（*Journals of Gerontology* frailty-subgroup study, PMID 37527836，DOI/標題均不符），經目視核對後判定為 POLLUTED，已立即刪除，不計入 fetched。Sci-Hub（鏡像 sci-hub.wf）查無可嵌入 PDF。Europe PMC 對涵蓋此 DOI 的 3 個 PMID 均標示 `is_open_access=false`；其中 PMID 33503360 的一個候選 OA 連結（diposit.ub.edu）僅解析為 HTML 頁面而非真實 PDF，已捨棄。 |
| 建議取得管道 | (1) 機構圖書館館際互借（ILL）調取 NEJM 該期紙本或 PDF；(2) 查詢 NEJM.org 該 DOI 頁面是否已過 12 個月 embargo 轉為部分開放；(3) 透過 ResearchGate／作者個人網頁尋找作者自存版（author copy）；(4) 直接聯絡通訊作者索取 reprint。 |

---

## 2. CONFIDENCE correspondence

| 項目 | 內容 |
|---|---|
| id | `confidence-correspondence` |
| 篇名/系列 | CONFIDENCE 試驗 correspondence 交流（4 篇構成） |
| 期刊 | *N Engl J Med* 2025;393:1753-1755 |
| DOI | 10.1056/NEJMc2513088 |
| PMID | 涵蓋此 DOI 之 4 筆 PMID |
| 狀態 | fetched=false, content_verified=false |
| 未取得原因 | Paywall（NEJM correspondence，2025/2026，訂閱限定）。`download_with_fallback`：CrossRef 無直接 PDF，Unpaywall 查無 OA URL，Sci-Hub（鏡像 sci-hub.wf）備援亦失敗（查無可嵌入 PDF）。Europe PMC 確認涵蓋此 DOI 的 4 個 PMID 均 `is_open_access=false`，無 PMCID。**未取回任何不相符檔案**——工具正確回報失敗，而非誤判為相符文獻。 |
| 建議取得管道 | (1) 機構圖書館館際互借（ILL）；(2) 追蹤 NEJM.org 12 個月 embargo 到期後是否開放；(3) 作者個人網頁／ResearchGate 查找 author copy；(4) 直接聯絡通訊作者索取 reprint。 |

---

## 3. JAMA glomerular disease 分析

| 項目 | 內容 |
|---|---|
| id | `jama-glomerular` |
| 篇名/系列 | Neuen BL, et al. FIND-CKD glomerular disease 亞群分析 |
| 期刊 | *JAMA* 2026 |
| DOI | 10.1001/jama.2026.9923 |
| PMID | 42246414 |
| 狀態 | fetched=false, content_verified=false |
| 未取得原因 | Paywall（JAMA 2026 文章，訂閱限定，出版時間過近，Sci-Hub 尚未收錄）。`download_with_fallback` 以模糊書名比對回傳不相符文獻（*American Journal of Cardiovascular Drugs* 評論文章〈Spironolactone or Finerenone...〉, PMID 42162505，DOI/標題均不符），經目視核對後判定為 POLLUTED，已立即刪除，不計入 fetched。Sci-Hub（鏡像 sci-hub.wf）查無可嵌入 PDF。Europe PMC 對 PMID 42246414 確認 `is_open_access=false`，無 PMCID。 |
| 建議取得管道 | (1) 機構圖書館館際互借（ILL）調取 JAMA 該期；(2) 追蹤 JAMA Network 是否於出版後 12 個月開放；(3) 作者個人網頁／ResearchGate 查找 author copy；(4) 直接聯絡通訊作者索取 reprint；(5) 待 Sci-Hub 收錄更新後重試（新刊通常有數月延遲）。 |

---

## 4. FIDELIO-DKD correspondence

| 項目 | 內容 |
|---|---|
| id | `fidelio-correspondence` |
| 篇名/系列 | FIDELIO-DKD correspondence 交流（含 Bakris/Agarwal/Filippatos 之 Reply） |
| 期刊 | *N Engl J Med* |
| DOI | 10.1056/NEJMc2036175 |
| PMID | 33730470（Reply）；交流共 6 封信 |
| 狀態 | fetched=false, content_verified=false |
| 未取得原因 | Paywall（NEJM correspondence）。已嘗試：`download_with_fallback`（source=pubmed, use_scihub=true）失敗，Unpaywall 查無 OA URL；`search_unpaywall` 直接查詢回傳空結果；`search_europepmc` 以確切 DOI 查得交流全部 6 封信（含 PMID 33730470 之 Reply），但每筆記錄均 `is_open_access=false`、`pmcid` 與 `pdf_url` 皆空；`mcp__scihub__find_pdf`（以 DOI 及 PMID 分別查詢）跑過 5 個鏡像，均回報「article not in Sci-Hub database」或「no embed/iframe with PDF found」；`download_scihub` 亦失敗。全網無任何 OA 副本，確認為 NEJM 訂閱限定文獻，符合預期。 |
| 建議取得管道 | (1) 機構圖書館館際互借（ILL）；(2) 追蹤 NEJM.org embargo 到期狀態；(3) 直接聯絡通訊作者（Bakris/Agarwal/Filippatos）索取 reprint；(4) 若僅需引用「交流存在」而非內文論點，可維持現狀（本檔已依此原則處理，見 `評論短信 FIND-CKD.md` §2.5）。 |

---

## 5. FIGARO-DKD（主要試驗全文）

| 項目 | 內容 |
|---|---|
| id | `figaro-dkd` |
| 篇名/系列 | FIGARO-DKD 主要試驗報告 |
| 期刊 | *N Engl J Med* 2021;385:2252-2263 |
| DOI | 10.1056/NEJMoa2110956 |
| PMID | 34449181 |
| 狀態 | fetched=false, content_verified=false |
| 未取得原因 | Paywall（NEJM 原始論文）。`download_with_fallback`（source=pubmed）回傳一份檔案（europepmc_PMID_40551874.pdf），但目視核對第 1 頁後確認為**完全不同的論文**（〈Efficacy and Safety of Finerenone in Asian Patients with Type 2 Diabetes and Chronic Kidney Disease: A FIDELITY Analysis〉, *Kidney Dis* 2025）——判定為 POLLUTED（Europe PMC 關鍵字誤配，非目標 DOI），已立即刪除，未存入 `原始PDF/`。直接以 DOI 查 `mcp__scihub__find_pdf`，跑過全部 5 個鏡像，均回報「no embed/iframe with PDF found」（無法取得）。`download_scihub` 同樣失敗。`search_unpaywall` 查詢該 DOI 回傳空結果。**正確地保持未取得狀態，未接受誤判的相符文獻。** |
| 建議取得管道 | (1) 機構圖書館館際互借（ILL）；(2) 追蹤 NEJM.org embargo 到期狀態（2021 年文獻理論上已過 12 個月，應優先重新確認是否已轉 OA）；(3) 作者個人網頁／ResearchGate 查找 author copy；(4) 直接聯絡通訊作者索取 reprint。 |

---

## 6. INFINITY pooled 分析

| 項目 | 內容 |
|---|---|
| id | `infinity-pooled` |
| 篇名/系列 | Neuen BL, Heerspink HJL, et al. INFINITY pooled IPD 分析 |
| 期刊 | *Lancet* 2026;407:2375-2386 |
| DOI | 10.1016/S0140-6736(26)01009-3 |
| PMID | 42248158 |
| 狀態 | fetched=false, content_verified=false |
| 未取得原因 | Paywall（*The Lancet* 2026 pooled analysis）。`download_with_fallback`（source=pubmed）回傳一份檔案（europepmc_PMID_36128573.pdf），但目視核對後確認為**完全不相關的俄語文獻**（心理情緒壓力與卵泡發生相關研究，*Vavilov Journal of Genetics and Breeding*, 2022）——判定為 POLLUTED（語言與主題均不符），已立即刪除，未存入。`search_europepmc` 以確切 DOI 查得正確紀錄（標題/摘要/n=14574 與候選描述完全相符），但 `is_open_access=false`，`pmcid` 與 `pdf_url` 皆空——Europe PMC 無 OA 副本。`mcp__scihub__find_pdf` 跑過全部 5 個鏡像，均回報「no embed/iframe with PDF found」（預期結果：2026 年出版，Sci-Hub 尚未索引）。`download_scihub` 與 `search_unpaywall` 亦失敗／空結果。 |
| 建議取得管道 | (1) 機構圖書館館際互借（ILL）調取 *Lancet* 該期；(2) 追蹤 Sci-Hub 收錄更新（出版過近，需假以時日）；(3) 作者個人網頁／ResearchGate 查找 preprint 或 author copy；(4) 直接聯絡通訊作者（Neuen BL / Heerspink HJL）索取 reprint。 |

---

## 7. CONFIDENCE（主要試驗全文）

| 項目 | 內容 |
|---|---|
| id | `confidence` |
| 篇名/系列 | CONFIDENCE 主要試驗報告 |
| 期刊 | *N Engl J Med* 2025;393:533-543 |
| DOI | 10.1056/NEJMoa2410659 |
| PMID | （未提供；主要試驗報告，2025-08-07 出版） |
| 狀態 | fetched=false, content_verified=false |
| 未取得原因 | Paywall（NEJM 2025 原始論文），PMC／Europe PMC 均無 OA 副本。Sci-Hub（全部 5 個鏡像：ru, st, red, ee, wf）均無法解析出 PDF——可能因出版過近（2025-08-07）尚未被索引。Europe PMC 搜尋確認僅有 CONFIDENCE 之**衍生／次分析**為 OA（例如 PMID 40886054 KDIGO-risk 亞群分析、PMID 40968755 GLP-1 RA 亞群分析）——主要 NEJM 報告本身全網無 OA 副本。首次 europepmc-fallback 嘗試回傳一份不相關的 POLLUTED PDF（ERA「call to action」special report, PMID 41578941），已刪除。 |
| 建議取得管道 | (1) 機構圖書館館際互借（ILL）；(2) 追蹤 Sci-Hub 收錄更新（出版過近，建議 1-2 個月後重試）；(3) 追蹤 NEJM.org embargo 到期狀態；(4) 直接聯絡通訊作者索取 reprint；(5) 暫以已落地的衍生次分析（PMID 40886054、40968755）之 metadata 層級引用替代，不對主要試驗內文數字作斷言。 |

---

## 查無候選

本輪流程未產生「查無候選」項目（空清單）。

---

## 使用限制提醒

- 本清單中所有項目在取得全文並完成本地 grep 驗證前，一律維持 📌 標記，僅可引用 metadata。
- 若後續任一項目成功取得全文，應：(1) 存入 `原始PDF/` 並依現有命名慣例命名；(2) 於 `評論短信 FIND-CKD.md` 對應處補上 `<!-- src: -->` 註記並改標 📄；(3) 更新本檔對應列的 `狀態` 為 `fetched=true`（並在完成逐字 grep 核對後再改 `content_verified=true`）。
- 任何工具回傳「不相符文獻」（POLLUTED）一律不得誤認為已取得，須立即刪除且不計入 fetched。

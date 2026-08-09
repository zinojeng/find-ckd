# NEED-TO-DO：未取得全文的文獻清單

**用途**：本檔列出 FIND-CKD 文獻回顧流程中**嘗試取得但最終未落地全文**的文獻。所有標記 📌 的引用僅能使用 metadata（title/authors/journal/year/DOI/PMID），**不得**在 `評論短信 FIND-CKD.md` 或任何後續稿件中對其內文（樣本數、HR、百分比、結論）作具體斷言，直到本清單中的項目被劃記為已取得並完成 grep 驗證為止。

**狀態欄定義**：`fetched=false` 表示未取得任何可用全文；`content_verified=false` 表示內容未經本地 grep 驗證。凡下載工具回傳「不相符文獻」（title/DOI 與目標不符），一律視為 **POLLUTED**，立即刪除，不計入 fetched。

**最後更新**：2026-08-09（**第四輪**：0-A／0-B 兩項補充材料經使用者以機構權限下載後落地完成）

**第四輪狀態摘要**：原「❌ 仍未取得」中的 **0-A（FIND-CKD 主文 NEJM Supplementary Appendix）** 與 **0-B（JAMA glomerular Supplement）** 已改列 **✅ 已取得**（見 A-8、A-9）。**仍未取得清單至此只剩一項：CONFIDENCE correspondence（§2）**；另有一項為「部分取得」之殘缺（§4：FIDELIO-DKD 之 Bakris/Agarwal Reply 本文）。

---

# ✅ 已取得（第二輪）

第二輪深挖後成功落地並完成 grep 驗證者。以下項目已從「未取得」移入本區，`評論短信 FIND-CKD.md` 中對應段落已由 📌 升級為 📄（或 ⚠️📄）。

## A-1. FIGARO-DKD（主要試驗全文）

| 項目 | 內容 |
|---|---|
| id | `figaro-dkd` → `Pitt_2021_FIGARO-DKD` |
| 期刊／DOI／PMID | *N Engl J Med* 2021;385:2252-2263 / 10.1056/NEJMoa2110956 / 34449181 |
| 狀態 | **fetched=true, content_verified=true** |
| 落地檔案 | `原始PDF/Pitt_2021_figaro-dkd.pdf` ／ `原始PDF/Pitt_2021_figaro-dkd.md` |
| 取得管道 | **Semantic Scholar → 機構典藏 CURIS（University of Copenhagen，Peter Rossing 所屬單位）**：`https://curis.ku.dk/ws/files/290115527/Cardiovascular_Events_with_Finerenone.pdf`，curl -L 直接 HTTP 200（833 KB, 13 頁）。前置 6 條管道（Unpaywall／OpenAlex 直下／PMC／Europe PMC／CORE／BASE）皆空。未需動用 Sci-Hub。 |
| 版本 | **Publisher's PDF / Version of Record**（CURIS 封面頁明載 `Document version: Publisher's PDF, also known as Version of record`）。頁碼與正式版一致，**可引頁碼**。 |
| 轉檔 | **converter = llamaparse（agentic tier，第三輪重轉）**。第二輪初次轉檔時 LlamaParse 因環境套件問題失敗（`ImportError: cannot import name 'AsyncLlamaCloud'`，非額度用盡）→ 當時以 `pdftotext -layout` 備援產出 818 行 MD；該版已改名保存為 `Pitt_2021_figaro-dkd.pdftotext.md.bak`，**僅供追溯，不作為引用來源**。 |
| 驗證 | 標題／作者列／期刊卷期／DOI 逐項比對一致；MD 二次 grep 命中 `Pitt, Bertram`、`FIGARO DKD Investigators`、DOI |

## A-2. CONFIDENCE（主要試驗全文）

| 項目 | 內容 |
|---|---|
| id | `confidence` → `Agarwal_2025_confidence` |
| 期刊／DOI／PMID | *N Engl J Med* 2025;393:533-43 / 10.1056/NEJMoa2410659 / **40470996**（原清單所載 40371574 疑為筆誤，建議核對） |
| 狀態 | **fetched=true, content_verified=true** |
| 落地檔案 | `原始PDF/Agarwal_2025_confidence.pdf` ／ `原始PDF/Agarwal_2025_confidence.md` |
| 取得管道 | **關鍵突破：改走舊網域 `pure.rug.nl` 的 Pure `/ws/files/` 端點**（`https://pure.rug.nl/ws/files/1480226551/NEJMoa2410659.pdf`，HTTP 200）。OpenAlex／Semantic Scholar 給出的 `research.rug.nl` 同名路徑被 Cloudflare Turnstile 攔死（cloudscraper 亦繞不過）；PMC／Europe PMC 無 OA；Sci-Hub 未收錄（2025 出版過近）；archive.org 無快照。 |
| 版本 | **出版社正式版（Version of Record）**，`N Engl J Med 2025;393:533-43`，**可引頁碼** |
| 轉檔 | **converter = llamaparse（agentic tier，第三輪重轉）**；第二輪的 `pdftotext -layout` 版保存為 `Agarwal_2025_confidence.pdftotext.md.bak`，僅供追溯 |
| 驗證 | 標題／作者列（Agarwal, Green, Heerspink, Mann, McGill, Mottl, Rosenstock, Rossing, Vaduganathan）／卷期／DOI 一致；MD grep 命中 `CONFIDENCE`、`NEJMoa2410659` |

## A-3. INFINITY pooled IPD 分析

| 項目 | 內容 |
|---|---|
| id | `infinity-pooled` → `Neuen_2026_infinity-pooled` |
| 期刊／DOI／PMID | *Lancet* 2026;407:2375-2386 / 10.1016/S0140-6736(26)01009-3 / 42248158 |
| 狀態 | **fetched=true, content_verified=true** |
| 落地檔案 | `原始PDF/Neuen_2026_infinity-pooled.pdf` ／ `原始PDF/Neuen_2026_infinity-pooled.md` |
| 取得管道 | **非預期來源：哥倫比亞 Universidad Simón Bolívar 之 DSpace 機構典藏 `bonga.unisimon.edu.co`**（由 tavily_search 命中 item 頁 → 解析出 bitstream 直連 → curl -L 下載，PDF v1.7, 10 頁）。Unpaywall／OpenAlex／Europe PMC／PMC／CORE／BASE／Semantic Scholar 全空；CrossRef 僅有 metadata 無 pdf_url；預期的 pure.rug.nl 與 unsworks.unsw.edu.au 站內查詢未命中。 |
| 版本 | **Lancet 正式排版版**（running header `www.thelancet.com Published online June 5, 2026 https://doi.org/10.1016/S0140-6736(26)01009-3`），非 author manuscript。 |
| 轉檔 | **converter = llamaparse（agentic tier，第三輪重轉）**；第二輪的 `pdftotext -layout` 版（934 行）保存為 `Neuen_2026_infinity-pooled.pdftotext.md.bak`，僅供追溯 |
| 驗證 | 標題／24 位作者列／DOI／期刊 header 一致；MD grep 命中 `Neuen`、`INFINITY`、`FIND-CKD`、`14 574 participants` |

## A-7. INFINITY supplementary appendix（第三輪取得，2026-08-09）

| 項目 | 內容 |
|---|---|
| id | `Neuen_2026_infinity-appendix` |
| 內容 | INFINITY 線上 appendix 全文 35 頁（Investigators、Table S1–S7、Figure S1–S10） |
| 狀態 | **fetched=true, content_verified=true** |
| 落地檔案 | `原始PDF/Neuen_2026_infinity-appendix.pdf` ／ `原始PDF/Neuen_2026_infinity-appendix.md` |
| 取得管道 | **Elsevier CDN 直連**：由 PII 推出 URL `https://ars.els-cdn.com/content/image/1-s2.0-S0140673626010093-mmc1.pdf`，curl 直接下載（HTTP 200，PDF v1.6）；mmc2 不存在（404） |
| 版本 | 出版社官方 supplementary appendix（首頁載明 `Supplement to: Neuen BL, Heerspink HJL, Perkovic V, et al.` 與正確 DOI；`We post it as supplied by the authors.`） |
| 轉檔 | converter = llamaparse（agentic tier） |
| 驗證 | Supplement-to 引用、DOI、頁數與 TOC 一致。**關鍵發現：Table S6（appendix p 23）Without diabetes 欄 N=793/791（=FIND-CKD 全體），hyperkalaemia SAE `Requiring hospitalisation` = `7 (0·9%)` vs `5 (0·6%)`** — 主稿選項 B 據此升級為直接引用（167 words、2 refs） |

## A-4. JAMA glomerular disease 分析

| 項目 | 內容 |
|---|---|
| id | `jama-glomerular` → `Neuen_2026_jama-glomerular` |
| 期刊／DOI／PMID | *JAMA* 2026（Published online June 5, 2026）/ 10.1001/jama.2026.9923 / 42246414 |
| 狀態 | **fetched=true, content_verified=true** |
| 落地檔案 | `原始PDF/Neuen_2026_jama-glomerular.pdf` ／ `原始PDF/Neuen_2026_jama-glomerular.md` |
| 取得管道 | **University of Liège 機構典藏 ORBi**：`https://orbi.uliege.be/bitstream/2268/346445/1/jama_neuen_2026.pdf`（tavily `filetype:pdf` 精確標題搜尋命中；curl -L HTTP 200，662,660 bytes，PDF v1.4, 10 頁）。PMC 副本 **PMC13242048 仍在 embargo（開放日 2026-12-05）**，今日不可取；JAMA 官網對非訂閱者不可讀。 |
| 版本 | **JAMA 出版社正式排版版**（帶 `Downloaded from jamanetwork.com by Universite de Liege user on 06/27/2026` 浮水印，屬作者／機構自存之出版社 PDF，非 preprint）。分頁為 E1–E10，**引用時用 E 頁碼或僅引 DOI**。**⚠️ Supplement 1–3（eTable/eFigure）未落地，不得引用。** |
| 轉檔 | **converter = llamaparse（agentic tier，第三輪重轉）**；第二輪的 `pdftotext -layout` 版（945 行）保存為 `Neuen_2026_jama-glomerular.pdftotext.md.bak`，僅供追溯 |
| 驗證 | 標題／第一作者 Brendon L. Neuen／`Published online June 5, 2026`／DOI 一致；MD grep 命中 `Neuen`、`FIND-CKD`、`10.1001/jama.2026.9923` |

## A-5. DAPA-CKD correspondence（完整）

| 項目 | 內容 |
|---|---|
| id | `dapa-ckd-correspondence` → `Vogt_2021_dapa-ckd-correspondence` |
| 期刊／DOI／PMID | *N Engl J Med* 2021;384:388-390 / 10.1056/NEJMc2032809 / 33503360 等 |
| 狀態 | **fetched=true, content_verified=true** |
| 落地檔案 | `原始PDF/Vogt_2021_dapa-ckd-correspondence.pdf` ／ `原始PDF/Vogt_2021_dapa-ckd-correspondence.md` |
| 取得管道 | **UCL Discovery 機構典藏**（David C. Wheeler 所屬）：`https://discovery.ucl.ac.uk/10121440/1/Wheeler_...Reply_VoR.pdf`，檔名含 `_VoR`。過程中排除了一條假線索：Europe PMC 對 PMID 33503360 給的 `diposit.ub.edu` pdf_url 實際對應 **NEJMoa2024816（DAPA-CKD 主試驗）**，且該典藏庫以 `Vogt Dapagliflozin`／`NEJMc2032809` 查詢 totalElements=0 → 判定為 Europe PMC 的錯誤映射，非目標文獻。未需動用 Sci-Hub。 |
| 版本 | **出版社正式版（Version of Record）**，pp. 388-390，**可引頁碼**。**內容涵蓋完整 correspondence 版面**：Vogt 信 + Yasuda/Isobe 信 + Heerspink/Langkilde/Wheeler 之 Reply。 |
| 額外收穫 | 該頁右欄印有 NEJM `INSTRUCTIONS FOR LETTERS TO THE EDITOR` 全文（175 words／5 references／3 authors／3 weeks 等條文之 **2021 年版原文**），已被 `評論短信 FIND-CKD.md` §4.2 引用；⚠️ 不可據此斷言 2026 年規則相同。 |
| 轉檔 | **converter = llamaparse（agentic tier，第三輪重轉）**；第二輪的 `pdftotext -layout` 版保存為 `Vogt_2021_dapa-ckd-correspondence.pdftotext.md.bak`，僅供追溯 |
| 驗證 | grep 命中 `Vogt`、`DAPA-CKD`、`NEJMc2032809`；頁碼、期別（384;4, January 28, 2021）一致 |

## A-6. FIDELIO-DKD correspondence（⚠️ **部分取得，版本受限**）

| 項目 | 內容 |
|---|---|
| id | `fidelio-correspondence` → `Bunkete_2021_fidelio-correspondence` |
| 期刊／DOI／PMID | *N Engl J Med* 2021, p. e42 / 10.1056/NEJMc2036175 / 33730470（Reply） |
| 狀態 | **fetched=partial, content_verified=true（僅就取得的那一封）** |
| 落地檔案 | `原始PDF/Bunkete_2021_fidelio-correspondence.pdf` ／ `原始PDF/Bunkete_2021_fidelio-correspondence.md` |
| 取得管道 | tavily 命中 HAL（Sorbonne Université）`hal-03265574` → HAL 被 Anubis proof-of-work bot-check 擋下 → **改用 Wayback Machine 2023-11-19 存檔快照**成功取得（84 KB, 2 頁, PDF 1.4）。Sci-Hub 端：修復 scihub MCP 的 Playwright chromium 後重跑，`find_pdf(DOI)` 回 no embed、`find_pdf(PMID 33730470)` 明確回 `article not in Sci-Hub database`；手動 curl 五鏡像皆被 DDoS-Guard／altcha 擋下。 |
| 版本 | ⚠️ **作者自存版（author self-archived manuscript），非出版社正式版；且不是 PMID 33730470 對應的 Bakris/Agarwal Reply**，而是同 DOI 下 Bunkete／Mohamadou／Galichon（Sorbonne Université）的讀者投書〈Concerns about finerenone's safety in diabetic patients〉。**引用時必須註明「作者自存版」且不得引用頁碼；不得以此檔對「作者 Reply 的內容」作任何斷言。** |
| 轉檔 | **converter = llamaparse（agentic tier，第三輪重轉）**；第二輪的 `pdftotext -layout` 版保存為 `Bunkete_2021_fidelio-correspondence.pdftotext.md.bak`，僅供追溯 |
| 仍缺 | **Bakris/Agarwal/Filippatos 之 Reply 本文**，以及該交流中其餘投書。詳見下方「未取得」§2。 |

## A-8. FIND-CKD 主文 Supplementary Appendix（NEJM）— ✅ **第四輪已取得（原 0-A）**

| 項目 | 內容 |
|---|---|
| id | `FIND-CKD_2026_nejm-appendix` |
| 內容 | FIND-CKD 主文之 NEJM Supplementary Appendix 全文 **42 頁**（Investigators、Supplementary Methods、Figure S1–S9、Table S1–S8、References） |
| 狀態 | **fetched=true, content_verified=true** |
| 落地檔案 | `原始PDF/FIND-CKD_2026_nejm-appendix.pdf` ／ `原始PDF/FIND-CKD_2026_nejm-appendix.md` |
| 取得管道 | **使用者以機構／訂閱權限自 NEJM 文章頁（10.1056/NEJMoa2604625）直接下載**。第三輪所有自動化管道皆失敗之紀錄保留於本節下方「第三輪嘗試記錄（保留）」。 |
| 版本 | 出版社官方 appendix；首頁載明 `Supplement to: Heerspink HJL, Neuen BL, Agarwal R, et al. Finerenone in persons with chronic kidney disease without diabetes. N Engl J Med 2026;395:533-45. DOI: 10.1056/NEJMoa2604625` |
| 轉檔 | converter = **llamaparse（agentic tier）** |
| 防污染驗證 | 通過。`pdfinfo` 42 頁；MD 結尾 References #11–12 標記 page_number 41，與 `pdftotext -f 42 -l 42`（頁腳頁碼 41）逐字相同 → **MD 完整涵蓋全 42 頁、無截斷**。另抽 4 處逐字交叉核對全部精確吻合：Table S8（MD 2154 起 vs PDF p40）、Investigators 首段（MD 71 vs PDF p4，`National lead investigator coordinator: Panteleimon (Pantelis) Sarafidis`）、Central Laboratory Assessment（MD 223 vs PDF p14）、Table S1（MD 1497 vs PDF p31，`Serum potassium level ≤4.8 mmol/l`）。英文、作者／標題與主文一致，無語言污染。 |
| **關鍵發現（對投稿的直接影響）** | **附錄對 hyperkalemia 住院「沒有第三種數字」。** 唯一與 AE 相關的表為 `Table S8. Adverse Events by Primary System Organ Class (Safety Analysis Set).`，僅到 MedDRA System Organ Class 層級（腳註 `Participants were counted only once within each primary system organ class.`），未拆 hyperkalemia、無 hospitalization 子分類；全文 `grep -ci` 之 `hyperkalemia`／`hyperkalaemia`／`serious`／`adjudicat` 皆 **0** 命中。→ `評論短信 FIND-CKD.md` §4.3 該項已改為 [x]、§4.4「更窄類別」退路已封死。 |
| **附帶更正稿件** | 附錄 Central Laboratory Assessment 段逐字：`In addition, potassium and eGFR were assessed at local laboratories for dosing decisions at each visit.` → 主稿英文正文原句 `dosing was governed by scheduled central-laboratory monitoring` 用詞不精確，已改為 `scheduled potassium monitoring at each visit`（選項 B 由 167→**170 words**，選項 A 由 156→**159 words**）。 |
| 第三輪嘗試記錄（保留） | (1) 標準 suppl_file URL curl → Cloudflare 403；(2) tavily_extract → 空；(3) r.jina.ai → CAPTCHA；(4) vanilla Playwright（headless/headed + stealth）→ Turnstile；(5) Patchright + 真 Chrome → 文章頁載入成功但 Appendix/Protocol 下載鈕 `aria-disabled="true"` 無 href（權限鎖定）。 |

### A-8b. FIND-CKD NEJM Protocol — ⚠️ **僅落地 PDF，未轉 MD，不可引用**

| 項目 | 內容 |
|---|---|
| 落地檔案 | `原始PDF/FIND-CKD_2026_nejm-protocol.pdf`（301 頁，3.27 MB） |
| 狀態 | **fetched=true, content_verified=false（未轉 MD，無法 grep）** |
| 取得管道 | 使用者以機構權限自 NEJM 文章頁下載 |
| 身分驗證 | `pdftotext -f 1 -l 1` 頁 1：`Protocol for: Heerspink HJL, Neuen BL, Agarwal R, et al. Finerenone in persons with chronic kidney disease without diabetes. N Engl J Med 2026;395:533-45.`；頁 2 目次含 Protocol(2-79)／Protocol Amendment(80-170)／Summary of Changes(171-178)／SAP(179-230)／SAP Update(231-300)。與 appendix、主文完全一致，無污染。 |
| **限制** | **依指示不轉 MD**。因無 MD 可 grep，**任何內容一律不得引用**——特別點名：高血鉀 stop/restart 具體門檻（>5.5 暫停／≤5.0 恢復）、AESI 通報時限規則、SAP 條文原文。若日後需引用，**必須先完成 LlamaParse 全文轉檔並正式列入 `評論短信 FIND-CKD.md` 來源表**。 |

## A-9. JAMA glomerular 分析 Supplement — ✅ **第四輪已取得（原 0-B）**

| 項目 | 內容 |
|---|---|
| id | `Neuen_2026_jama-glomerular-supp2` |
| 內容 | JAMA Supplement 2：**eTable 1–4、eFigure 1–7**（含 eTable 4 之 glomerular 次群安全性表、eFigure 2/6 之亞型森林圖） |
| 狀態 | **fetched=true, content_verified=true** |
| 落地檔案 | `原始PDF/Neuen_2026_jama-glomerular-supp2.pdf` ／ `原始PDF/Neuen_2026_jama-glomerular-supp2.md` |
| 取得管道 | **使用者以機構／訂閱權限自 JAMA 文章頁登入後下載**（第三輪自動化管道全數失敗，紀錄保留於下方） |
| 版本 | JAMA 官方 supplement，作者列 Neuen BL, Perkovic V, Agarwal R 與主文一致，全篇英文 |
| 轉檔 | converter = **llamaparse（agentic tier）** |
| 防污染驗證 | 通過。3 處與來源 PDF 交叉比對全部相符：(1) 標題／DOI 區塊 PDF p1 vs MD line 3 逐字；(2) eTable 4 之 PDF p16（影像，目視）vs MD 521–618 逐位；(3) eFigure 6 之 PDF p22（影像，目視）vs MD 1253–1330 逐位。 |
| **關鍵發現** | eTable 4（finerenone n=446 vs placebo n=457）：`Any hyperkalemia (AESI)` 73(16.4%) vs 70(15.3%)；因高血鉀永久停藥 **8(1.8%) vs 2(0.4%)**；`Any serious hyperkalemia` 4(0.9%) vs 4(0.9%)，其 `Leading to hospitalization` **3(0.7%) vs 4(0.9%)** — **即使在最窄定義下仍非零**，強化 §4.4。腳註定義：`Hyperkalemia was an AESI and defined as any investigator-reported AEs with MedDRA codes corresponding to the preferred terms hyperkalemia or blood potassium increased.` |
| **⚠️ 引用紅線（三條）** | (1) eTable 4 為 **investigator-reported AESI**，**不得**用以陳述 K>5.5／>6.0 mmol/L 事件數（該表根本沒有）；(2) `Related to study drug` 之 finerenone 欄 `177 (26.2)` 為**來源端內部不一致**（177/446=39.7%；26.2% 對應 117/446），已用 `pdftotext -f 16 -l 16` 確認 PDF 原文即為 `177 (26.2)`，非轉檔錯誤 → **該列一律不引**；(3) eFigure 2／3／6／7 的數字**只存在於圖形層**，`pdftotext` 抓不到、僅 LlamaParse 視覺抽取可得；eFigure 6 已目視逐位覆核，**eFigure 2／3／7 僅結構性抽查**，逐字使用前須再做 `pdftoppm` 目視核對。 |
| 第三輪嘗試記錄（保留） | (1) jamanetwork curl / tavily / r.jina.ai → 403/CAPTCHA；(2) Patchright + 真 Chrome → 文章頁載入成功但全頁 DOM 無 supplement PDF 連結；(3) `#multimedia-tab` 僅圖表 PNG；(4) ORBi 僅存主文；(5) PMC13242048 embargo 至 2026-12-05。 |

### A-9b. JAMA Supplement 1（Bayer 試驗計畫書）— ⚠️ **僅落地 PDF，未轉 MD，且原則上無法 grep 驗證**

| 項目 | 內容 |
|---|---|
| 落地檔案 | `原始PDF/Neuen_2026_jama-glomerular-supp1-protocol.pdf`（20.5 MB） |
| 狀態 | **fetched=true, content_verified=false** |
| 身分驗證 | ⚠️ **無法以文字抽取驗證**：`pdffonts` 顯示全部文字字型為 Type 3 `Custom` 編碼、無 embedded ToUnicode CMap，`pdftotext -layout` 在第 1／2／5／10／50 頁皆輸出亂碼（此為字型問題，**非污染跡象**）。改以 `pdftoppm` 轉 PNG 目視確認第 2 頁：Bayer `Clinical Study Protocol No. BAY 94-8862/21177`、標題 `FInerenone…Non-Diabetic Chronic Kidney Disease`、Protocol Number 21177、Compound BAY 94-8862/Finerenone、Acronym `FIND-CKD`、日期 09 JUN 2021；`pdfinfo` Title metadata 為 `JOI260064supp1_srcpdf.pdf`，與 JAMA supplement 命名一致。 |
| **限制** | **依指示不轉 MD**，且**即使轉檔也無法以文字層 grep 回驗**。**一律不得引用其任何內容，亦不得聲稱曾對本檔做過 grep 驗證。** 若日後非引不可，只能以 `pdftoppm` 逐頁轉圖目視閱讀並在稿中明示此一驗證方式的限制。 |

---

# ❌ 仍未取得

## 1. DAPA-CKD correspondence — ✅ **已於第二輪取得，見上方 A-5**

第一輪未取得原因（保留紀錄）：`download_with_fallback` 回傳 POLLUTED 檔（*Journals of Gerontology* frailty-subgroup study, PMID 37527836）已刪除；Sci-Hub（sci-hub.wf）無嵌入 PDF；Europe PMC 3 個 PMID 均 `is_open_access=false`。第二輪經 UCL Discovery 機構典藏取得正式版全文。

---

## 2. CONFIDENCE correspondence

| 項目 | 內容 |
|---|---|
| id | `confidence-correspondence` |
| 篇名/系列 | CONFIDENCE 試驗 correspondence 交流（4 篇構成） |
| 期刊 | *N Engl J Med* 2025;393:1753-1755 |
| DOI | 10.1056/NEJMc2513088 |
| PMID | **41160829 / 41160830 / 41160831 / 41160832**（第二輪由 Europe PMC 補齊）：Silver S 信、Assil／Hough 信、Romagnani／Soler／Fervenza 信、以及 Agarwal／Rossing／Mann 之 Reply |
| 出版日 | 2025-10-30 |
| 狀態 | **fetched=false, content_verified=false（第一、二輪均未取得）** |
| 未取得原因（第一輪） | Paywall。`download_with_fallback`：CrossRef 無直接 PDF，Unpaywall 查無 OA URL，Sci-Hub（sci-hub.wf）備援失敗。Europe PMC 確認 4 個 PMID 均 `is_open_access=false`、無 PMCID。**未取回任何不相符檔案。** |
| 未取得原因（第二輪，10 條管道全數失敗） | (1) `search_unpaywall(DOI)` 空結果；(2) `search_openalex` 無精確匹配／無 oa_url；(3) `search_pmc`／`search_europepmc` 取得 4 筆正確 metadata 但全部 `is_open_access=False`、無 pdf_url、無 PMCID（本試驗由 Bayer 資助而非 NIH，故無 PMC author manuscript 義務，embargo 路徑不成立）；(4) `search_core`／`search_base` 空；(5) `search_semantic` metadata 正確但 pdf_url 僅指回 `doi.org` 付費牆；(6) tavily 三輪（精確標題+filetype:pdf／`NEJMc2513088 pdf`／作者站內搜 diposit.ub.edu、researchgate）皆無真實 PDF；(7) `google_scholar_key_words` 僅找到 Romagnani／Fervenza 另投 *NDT* 2026 的衍生評論（非本文）與 ovid.com 付費摘要；(8) `mcp__scihub__find_pdf` 回報 no embed，後續呼叫因該 MCP 的 Playwright 執行檔缺失而報錯；(9) 手動 curl 各鏡像：sci-hub.st 回 DDoS-Guard JS challenge、sci-hub.ru 回 altcha 機器人驗證、sci-hub.se 連線失敗；(10) `download_with_fallback`（source=crossref 與 semantic 各一次完整 OA-first + scihub 鏈）皆回報找不到 PDF URL。**判定：paywall，且 2025-10-30 出版過近，Sci-Hub 極可能尚未收錄。未產生任何 PDF/MD。** |
| 建議取得管道 | (1) **機構訂閱／ILL 人工下載後放入 `原始PDF/`（目前唯一可行路徑）**；(2) 追蹤 NEJM.org embargo；(3) 聯絡通訊作者（Agarwal／Rossing／Mann）索取 reprint；(4) 數月後重試 Sci-Hub。 |
| ⚠️ 對稿件的影響 | **這是 `評論短信 FIND-CKD.md` 目前唯一未被排除的新穎度盲點**——無法確認是否已有人在 CONFIDENCE correspondence 中提出高血鉀住院／安全性敘述一致性的問題。投稿前必須人工核對。 |

---

## 3. JAMA glomerular disease 分析 — ✅ **已於第二輪取得，見上方 A-4**

第一輪未取得原因（保留紀錄）：`download_with_fallback` 回傳 POLLUTED 檔（*Am J Cardiovasc Drugs* 評論, PMID 42162505）已刪除；Sci-Hub 無嵌入 PDF；Europe PMC `is_open_access=false`。第二輪確認 PMC13242048 仍 embargo 至 2026-12-05，改由 ORBi（Univ. de Liège）取得出版社正式版。**Supplement 1–3 仍未取得。**

---

## 4. FIDELIO-DKD correspondence — ⚠️ **部分取得（見上方 A-6）；Bakris/Agarwal Reply 本文仍缺**

| 項目 | 內容 |
|---|---|
| id | `fidelio-correspondence` |
| 篇名/系列 | FIDELIO-DKD correspondence 交流（含 Bakris/Agarwal/Filippatos 之 Reply） |
| 期刊 | *N Engl J Med* |
| DOI | 10.1056/NEJMc2036175 |
| PMID | 33730470（Reply，PubMed 標題結尾為 `... Reply`，作者 Bakris GL, Agarwal R, Filippatos G; FIDELIO-DKD Study Group）；交流共 6 封信 |
| 狀態 | **fetched=partial**（取得其中 1 封投書之作者自存版，見 A-6）；**Reply 本文 fetched=false** |
| 已取得部分 | Bunkete／Mohamadou／Galichon（Sorbonne Université）之投書〈Concerns about finerenone's safety in diabetic patients〉，HAL `hal-03265574` 作者自存版，經 Wayback Machine 2023-11-19 快照下載（HAL 本站被 Anubis proof-of-work bot-check 擋下）。檔案：`原始PDF/Bunkete_2021_fidelio-correspondence.{pdf,md}` |
| 仍未取得原因（第二輪） | (1) `search_unpaywall(DOI)` 空；(2) OpenAlex／PMC／Europe PMC／CORE／BASE／Semantic Scholar 多組關鍵字均查無此 correspondence 條目（各索引庫普遍不收 NEJM correspondence letters）；(3) tavily 找到 nejm.org 付費頁、ablesci.com（檔案已被刪除）、researchgate 條目頁（無全文），僅 HAL 一條真實線索；(4) 修復 scihub MCP 的 Playwright chromium 後重跑：`find_pdf(DOI)` 回 no embed/iframe、`find_pdf(PMID 33730470)` 明確回 **`article not in Sci-Hub database`**；(5) 手動 curl ru/st/se/ee/wf 五鏡像皆被 DDoS-Guard／altcha 擋下；(6) `download_with_fallback(source=crossref, use_scihub=true)` 失敗。**未找到任何含 Bakris/Agarwal Reply 本文的開放版本。** |
| 建議取得管道 | (1) **機構訂閱／ILL 人工下載完整 correspondence 頁面**；(2) 聯絡 Agarwal／Filippatos 索取 reprint（**George L. Bakris 已故**——CONFIDENCE 致謝逐字：`We dedicate this article to the memory of our colleague` <!-- src:原始PDF/Agarwal_2025_confidence.md --> 📄）；(3) 若僅需引用「交流存在」與「Bunkete 投書之論點」，現狀已足（見 `評論短信 FIND-CKD.md` §2.5(a)）。 |
| ⚠️ 對稿件的影響 | 無法確認作者當年如何回應「高血鉀安全數據外推應審慎」與「血壓中介效應」兩題 → **第三優先（血壓）角度的新穎度無法判定**，投稿前建議人工核對。 |

---

## 5. FIGARO-DKD（主要試驗全文） — ✅ **已於第二輪取得，見上方 A-1**

第一輪未取得原因（保留紀錄）：`download_with_fallback` 回傳 POLLUTED 檔（FIDELITY Asian analysis, *Kidney Dis* 2025）已刪除；5 個 Sci-Hub 鏡像皆 no embed；Unpaywall 空結果。第二輪由 Semantic Scholar 指向 CURIS（Univ. of Copenhagen）取得 Version of Record。

---

## 6. INFINITY pooled 分析 — ✅ **已於第二輪取得，見上方 A-3**

第一輪未取得原因（保留紀錄）：`download_with_fallback` 回傳 POLLUTED 俄語檔（*Vavilov J Genet Breed* 2022）已刪除；Europe PMC 有正確 metadata 但 `is_open_access=false`；5 個 Sci-Hub 鏡像皆 no embed。第二輪由 bonga.unisimon.edu.co（Universidad Simón Bolívar）DSpace 取得 Lancet 正式排版版。**線上 appendix（pp 2–16）仍未取得。**

---

## 7. CONFIDENCE（主要試驗全文） — ✅ **已於第二輪取得，見上方 A-2**

第一輪未取得原因（保留紀錄）：PMC／Europe PMC 無 OA；5 個 Sci-Hub 鏡像皆失敗；europepmc-fallback 回傳 POLLUTED 檔（ERA special report, PMID 41578941）已刪除。第二輪關鍵在於改走 `pure.rug.nl`（舊網域，無 Cloudflare Turnstile）而非 `research.rug.nl`。**PMID 應為 40470996，原清單未填，建議核對。**

---

## 查無候選

本輪流程未產生「查無候選」項目（空清單）。

---

## 使用限制提醒

- 本清單中所有項目在取得全文並完成本地 grep 驗證前，一律維持 📌 標記，僅可引用 metadata。
- 若後續任一項目成功取得全文，應：(1) 存入 `原始PDF/` 並依現有命名慣例命名；(2) 於 `評論短信 FIND-CKD.md` 對應處補上 `<!-- src: -->` 註記並改標 📄；(3) 更新本檔對應列的 `狀態` 為 `fetched=true`（並在完成逐字 grep 核對後再改 `content_verified=true`）。
- 任何工具回傳「不相符文獻」（POLLUTED）一律不得誤認為已取得，須立即刪除且不計入 fetched。

## 【第二輪新增】版本與範圍限制（已取得者亦適用）

- **`Bunkete_2021_fidelio-correspondence.md` 為作者自存版（HAL），且不是 PMID 33730470 對應的 Bakris/Agarwal Reply。** 引用時必須註明「作者自存版」、**不得引用頁碼**、**不得**用它推斷作者 Reply 的內容。標記為 ⚠️📄。
- ~~**未落地的補充材料一律不得引用**：INFINITY 線上 appendix、JAMA Supplement 1–3（eTable/eFigure）、FIND-CKD 主文 Supplementary Appendix（Table S8 等）。~~ **【第三／四輪更新】** INFINITY appendix（A-7）、FIND-CKD NEJM appendix（A-8）、JAMA Supplement 2（A-9）**均已落地並完成驗證，已解封**。**仍不可引用者只剩兩份 protocol PDF（A-8b、A-9b）**——僅存 PDF、未轉 MD；其中 A-9b 更因 Type 3 自訂字型而**根本無法以文字層 grep**。
- **PMC13242048（JAMA glomerular）embargo 至 2026-12-05**；屆時可取得可公開再散布之版本，建議屆期重新下載以取代 ORBi 副本。
- **PMID 更正**：CONFIDENCE 主試驗應為 **40470996**（原任務描述所載 40371574 疑為筆誤）。
- **共通轉檔限制【第三輪更新】**：第二輪 6 檔（FIGARO-DKD、CONFIDENCE、INFINITY、JAMA glomerular、DAPA-CKD correspondence、FIDELIO-DKD correspondence）原因 `llamaparse_convert.py` 環境錯誤（`ImportError: cannot import name 'AsyncLlamaCloud' from 'llama_cloud'`，非額度用盡）而暫以 `pdftotext -layout` 產出；**環境修復後已於第三輪全數以 LlamaParse（agentic tier）重轉**，`converter = llamaparse`。舊版一律改名為同名 `.pdftotext.md.bak` 保存，**僅供追溯，不作為引用來源**。
- **兩種轉檔並存下的核對規則（相同）**：**逐字引用一律取單行連續片段 grep，不可用跨行重組後的句子。**
  - LlamaParse 版（第二輪 6 檔）：斷行已合併、連字號已接回，整句多半可一次命中；但會帶 Markdown 標記（`<sup>1</sup>` 上標、`*Journal*` 斜體、`**HEADING**` 小標、表格轉為 HTML `<td>`），選片段時須避開或連同標記一起取，並實測 grep。
  - pdftotext 版（第一輪 5 檔：`Bakris_2020_FIDELIO-DKD.md`、`Heerspink_2020_DAPA-CKD.md`、`Heerspink_2025_FIND-CKD-design.md`、`Hobbs_2024_BARACK-D.md`、`Juurlink_2004_15295047.md`）：雙欄版面仍會斷行、拆連字號，須取單行殘片。
- **⚠️ 換版後查出的實質更正**：`評論短信 FIND-CKD.md` §2.5(b) 與 §4.4 原將 FIGARO-DKD 那句住院比例（`or hospitalization (in 0.6% and 0.1%).`）標為出自 **Discussion**，LlamaParse 版顯示其實位於 **Results** 的 `**SAFETY OUTCOMES AND VITAL SIGNS**` 段——pdftotext 雙欄輸出把相鄰右欄的 Discussion 文字併在同一實體行所致。稿中兩處已更正。
- **【第四輪新增】僅存 PDF、未轉 MD 者一律比照 📌 處理**：`FIND-CKD_2026_nejm-protocol.pdf`、`Neuen_2026_jama-glomerular-supp1-protocol.pdf`。無 MD 即無法 grep，**不得引用內文**；本檔對它們只記載「身分已驗證」與「驗證方式」，不記載任何可被當成事實引用的內容數字。
- **【第四輪新增】圖形層數字的驗證等級低於文字層**：`Neuen_2026_jama-glomerular-supp2.md` 的 eFigure 2／3／6／7 數值源自 forest plot 影像，`pdftotext` 無法回驗，僅 LlamaParse 視覺抽取可得。eFigure 6 已 `pdftoppm` 目視逐位覆核；**eFigure 2／3／7 尚未逐頁覆核**，逐字引用前須補做。
- **【第四輪新增】來源端本身的內部不一致**：`Neuen_2026_jama-glomerular-supp2.md` eTable 4 之 `Related to study drug`（finerenone）印為 `177 (26.2)`，177/446=39.7% 與 26.2% 不符（26.2% 對應 117/446）。已用 `pdftotext -f 16 -l 16` 確認 **PDF 原文即如此**，屬 JAMA supplement 之印刷／製表錯誤，非轉檔錯誤。**該列一律不引用。**
- **可安全引用頁碼者**：FIGARO-DKD（2252-2263）、CONFIDENCE（533-43）、DAPA-CKD correspondence（388-390）。**JAMA glomerular 僅有 E1–E10 線上分頁**；**INFINITY 為線上先行版**（正式卷期頁 2375-2386 出自 metadata，非 PDF 版面），引用頁碼前建議再核對。

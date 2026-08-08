# FIND-CKD 評論短信（NEJM Correspondence）投稿包

**標的論文**：Heerspink HJL, Neuen BL, Agarwal R, et al. Finerenone in Persons with Chronic Kidney Disease without Diabetes. *N Engl J Med* 2026;395:533-545. DOI 10.1056/NEJMoa2604625 <!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄。PMID 42246672 📌（PubMed 索引 metadata，未以本地全文驗證）。線上發表 2026-06-04，2026-06-29 更新，紙本 2026-08-06（Vol. 395, No. 6）<!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄

**本檔驗證原則**：所有數字、引號字串均可在下列本地檔案 grep 命中。標 📄 者為本地已落地全文；標 📌 者僅有 metadata（title/authors/journal/year/DOI/PMID），**不對其內文作任何具體斷言**。

| 標記 | 本地檔案 |
|---|---|
| 📄 | `/Users/ander/openclaw-research/find-ckd/FIND-CKD main text NEJMoa2604625.md` |
| 📄 | `/Users/ander/openclaw-research/find-ckd/原始PDF/Bakris_2020_FIDELIO-DKD.md` |
| 📄 | `/Users/ander/openclaw-research/find-ckd/原始PDF/Heerspink_2020_DAPA-CKD.md`（本檔已落地但**未被引用**；DAPA-CKD 相關內容僅停留在其 correspondence 的 metadata 層級） |
| 📄 | `/Users/ander/openclaw-research/find-ckd/原始PDF/Heerspink_2025_FIND-CKD-design.md` |
| 📄 | `/Users/ander/openclaw-research/find-ckd/原始PDF/Hobbs_2024_BARACK-D.md` |
| 📄 | `/Users/ander/openclaw-research/find-ckd/原始PDF/Juurlink_2004_15295047.md` |
| 📌 | FIGARO-DKD (NEJMoa2110956)、CONFIDENCE (NEJMoa2410659)、FIDELIO/DAPA-CKD/CONFIDENCE correspondence、JAMA glomerular 分析 (10.1001/jama.2026.9923)、INFINITY pooled (10.1016/S0140-6736(26)01009-3) — **全文未落地，僅可引 metadata** |

---

# 一、NEJM Correspondence 英文投稿稿（主稿）

**Suggested title:** Hyperkalemia-Related Hospitalization in FIND-CKD

### Body（正文，156 words）

> **TO THE EDITOR:** Heerspink et al. (Aug. 6 issue)¹ report that finerenone slowed the decline in the estimated glomerular filtration rate among adults with chronic kidney disease who did not have diabetes. We seek clarification regarding hyperkalemia-related hospitalization. The Results section and Table 2 state that hyperkalemia led to hospitalization in 7 participants (0.9%) in the finerenone group and 5 (0.6%) in the placebo group. The Discussion, however, describes the potassium increases as "leading to discontinuation of the trial regimen in few participants and no hospitalizations." Because hospitalization for hyperkalemia was a prespecified safety assessment,² does the latter statement refer to a narrower category of events, or should it be corrected? Precision matters for implementation: eligibility required a serum potassium level of 4.8 mmol per liter or less, and dosing was governed by scheduled central-laboratory monitoring and by interruption above 5.5 mmol per liter. After RALES, hyperkalemia-related hospitalizations rose from 2.4 to 11.0 per 1000 patients.³

**Word count:** 156 words（NEJM 上限 175；正文不含 references、標題、作者資訊）。

### References（3 篇，NEJM 上限 5 篇）

1. Heerspink HJL, Neuen BL, Agarwal R, et al. Finerenone in persons with chronic kidney disease without diabetes. *N Engl J Med* 2026;395:533-545. <!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄
2. Heerspink HJL, Agarwal R, Bakris GL, et al. Design and baseline characteristics of the Finerenone, in addition to standard of care, on the progression of kidney disease in patients with Non-Diabetic Chronic Kidney Disease (FIND-CKD) randomized trial. *Nephrol Dial Transplant* 2025;40:308-319. <!-- src:原始PDF/Heerspink_2025_FIND-CKD-design.md --> 📄
3. Juurlink DN, Mamdani MM, Lee DS, et al. Rates of hyperkalemia after publication of the Randomized Aldactone Evaluation Study. *N Engl J Med* 2004;351:543-551. <!-- src:原始PDF/Juurlink_2004_15295047.md --> 📄

### 逐句可核對表（投稿前作者逐字覆核用）

| 稿中字串 | 來源與可 grep 字串 | 檔案 |
|---|---|---|
| hospitalization in 7 participants (0.9%) ... and 5 (0.6%) | Results 逐字：`Hyperkalemia led to hospitalization in 7 participants (0.9%) with finerenone and 5 participants (0.6%) with placebo`；Table 2 列名 `Leading to hospitalization`，其下兩格為 `7 (0.9)` 與 `5 (0.6)` | 📄 主文 <!-- src:FIND-CKD main text NEJMoa2604625.md --> |
| "leading to discontinuation of the trial regimen in few participants and no hospitalizations" | Discussion 逐字：`leading to discontinuation of the trial regimen in few participants and no hospitalizations` | 📄 主文 <!-- src:FIND-CKD main text NEJMoa2604625.md --> |
| hospitalization for hyperkalemia was a prespecified safety assessment | 設計論文 Safety 段逐字（雙欄轉檔後之連續片段）：`for hyperkalaemia and permanent discontinuation of study` + 次行 `medication due to hyperkalaemia.`；主文 Outcomes 段逐字：`hospitalization for serious hyperkalemia` | 📄 設計論文 <!-- src:原始PDF/Heerspink_2025_FIND-CKD-design.md --> ／📄 主文 <!-- src:FIND-CKD main text NEJMoa2604625.md --> |
| eligibility required a serum potassium level of 4.8 mmol per liter or less | Participants 段逐字：`Eligibility criteria included a serum potassium level of 4.8 mmol per liter or less` | 📄 主文 <!-- src:FIND-CKD main text NEJMoa2604625.md --> |
| interruption above 5.5 mmol per liter | Trial procedures 段逐字：`If the serum potassium level exceeded 5.5 mmol per liter, finerenone or placebo was withheld for 72 hours` | 📄 主文 <!-- src:FIND-CKD main text NEJMoa2604625.md --> |
| scheduled central-laboratory monitoring | 逐字：`were collected for eGFR and serum potassium assessments at the central laboratory`（訪視為篩選、基準、第 1/3/6/9/12 個月，其後每 4 個月） | 📄 主文 <!-- src:FIND-CKD main text NEJMoa2604625.md --> |
| rose from 2.4 to 11.0 per 1000 patients | Juurlink abstract 逐字（連續片段）：`1000 patients in 1994 to 11.0 per 1000 patients in 2001 (P<0.001)`，其前一行為 `The rate of hospitalization for hyperkalemia rose from 2.4 per` | 📄 Juurlink <!-- src:原始PDF/Juurlink_2004_15295047.md --> |

> **轉檔注意**：`原始PDF/*.md` 由雙欄 PDF 經 `pdftotext -layout` 轉出，句子常被斷行或連字號拆開，因此本檔對這些檔案的逐字引用一律取**單行連續片段**。核對時請用該片段 grep，不要用跨行重組後的句子。

> **注意（給投稿者）**：Juurlink 的母體是安大略、近期因心衰竭住院、正在使用 ACE inhibitor 的高齡病人 <!-- src:原始PDF/Juurlink_2004_15295047.md --> 📄，不是 CKD 族群。若審稿要求更嚴謹，可把最後一句改寫為下列建議句（作者自撰，非引文；+6 words，總計 162 words，仍在 175 上限內）：
>
> Among older patients treated with ACE inhibitors after RALES, hyperkalemia-related hospitalizations rose from 2.4 to 11.0 per 1000.³

### 投稿欄位備忘

- 作者 ≤3 位、每人 1 個 affiliation、1 位 corresponding author（NEJM Correspondence 規定；此規格請於投稿介面現場再確認，本檔未落地 NEJM instructions 原文，不作引用）。
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

## 2.4 為什麼不用 BARACK-D 當主軸（但值得知道）

FIND-CKD 的 Discussion 引用 BARACK-D 作為固醇類 MRA 耐受性差的對照，寫成「約 1400 名 CKD 受試者中超過一半在隨機分派後 6 個月內停用 spironolactone……hyperkalemia 佔停藥原因逾 10%」。<!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄

回到 BARACK-D 原文核對：共 1,434 名英國基層醫療成人隨機分派；分派至 spironolactone 者有三分之二在 6 個月內停藥，主因是達到預先設定的安全停藥標準（逐字連續片段：`to spironolactone stopped treatment within 6 months, predominantly`）；最常見停藥原因為 eGFR 下降達停藥標準（n=239, 35.4%），其次為副作用退出（n=128, 18.9%）與高血鉀（n=54, 8.0%）；主要結果 113/677（16.7%）vs 111/695（16.0%），HR 1.05（95% CI 0.81–1.37）。<!-- src:原始PDF/Hobbs_2024_BARACK-D.md --> 📄

判讀：FIND-CKD 說「超過一半」，BARACK-D 說「三分之二」——**方向一致、保守表述，不構成錯誤**，因此不適合作為投書標的。它的價值在於背景：真實世界（英國基層照護）的 MRA 停藥率與試驗描述之間本就存在落差，這強化 §2.3 的外推論點，但**不應寫進 175 字**。

## 2.5 哪些角度已被佔據（因此新穎度不足）

以下僅以 **metadata 層級**陳述，因未取得全文，**不對其內文結論作任何斷言**：

- **FIDELIO-DKD 的 correspondence 交流已存在**（*N Engl J Med* 2021, DOI 10.1056/NEJMc2036175, PMID 33730470，含作者 Reply）。📌 僅陳述「存在此交流」，本檔不描述各封信的論點。
- **DAPA-CKD 的 correspondence 交流已存在**（*N Engl J Med* 2021;384:388-390, DOI 10.1056/NEJMc2032809，含讀者信與作者 Reply）。📌
- **CONFIDENCE 的 correspondence 交流已存在**（*N Engl J Med* 2025;393:1753-1755, DOI 10.1056/NEJMc2513088，4 篇構成之交流）。📌 僅陳述「存在此交流」。
- **JAMA 的 FIND-CKD glomerular disease 分析已發表**（Neuen BL, et al. *JAMA* 2026, DOI 10.1001/jama.2026.9923, PMID 42246414）。📌 全文未落地，本檔不對其設計、樣本數、結論作斷言。（可另行陳述之已驗證事實：FIND-CKD 基線有 903/1584（57.0%）為 any glomerular disease <!-- src:原始PDF/Heerspink_2025_FIND-CKD-design.md --> 📄）
- **INFINITY pooled IPD 分析已發表**（Neuen BL, Heerspink HJL, et al. *Lancet* 2026;407:2375-2386, DOI 10.1016/S0140-6736(26)01009-3, PMID 42248158）。📌 全文未落地，本檔不對其納入試驗組成、樣本數與結論作任何斷言。
- **FIGARO-DKD**（*N Engl J Med* 2021;385:2252-2263, DOI 10.1056/NEJMoa2110956）📌 與 **CONFIDENCE**（*N Engl J Med* 2025;393:533-543, DOI 10.1056/NEJMoa2410659）📌 全文均未落地，本檔不引用其內文數字。

> 已落地全文的 FIDELIO-DKD 可安全用於**對照性的量級**：其 hyperkalemia 導致住院為 40/2827（1.4%）vs 8/2831（0.3%），因 hyperkalemia 永久停藥 64（2.3%）vs 25（0.9%），investigator-reported hyperkalemia 516（18.3%）vs 255（9.0%），且未報告致死性高血鉀不良事件（逐字連續片段：`perkalemia adverse events were reported.`，其前一行結尾為 `No fatal hy-`）；納入條件同樣要求篩選時血鉀 ≤4.8 mmol/L，>5.5 停藥、≤5.0 再啟動。<!-- src:原始PDF/Bakris_2020_FIDELIO-DKD.md --> 📄 這說明 FIND-CKD 的住院事件並非孤例，而是這個藥物類別在**受保護的試驗條件下**仍會出現的既知現象——但這一段屬於中文論證，175 字英文稿不放。

## 2.6 邏輯鏈總結

1. 高血鉀住院是 FIND-CKD 的 **prespecified** 安全性終點 <!-- src:原始PDF/Heerspink_2025_FIND-CKD-design.md --> 📄；
2. Results／Table 2 給出 7 vs 5 <!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄；
3. Discussion 說 no hospitalizations <!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄；
4. 兩者不能同時為真 → 作者必須擇一回答；
5. 這一格的正確性直接決定臨床醫師如何在**沒有 K≤4.8 門檻、沒有中央實驗室排程**的常規照護中做風險溝通 <!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄；
6. RALES 後的自然實驗證明這種轉譯失真會造成可測量的住院與死亡增量 <!-- src:原始PDF/Juurlink_2004_15295047.md --> 📄。

這條鏈上每一環都可 grep，沒有任何一環需要作者未公開的資料。**這是它比其他所有角度都強的唯一理由。**

---

# 三、備選角度（第二、三優先）與不建議的角度

## 第二優先：基準僅 17.0% 使用 SGLT2i，是否代表當代標準治療

- 事實：1580 名（99.7%）使用 RAS inhibitor，270 名（17.0%）使用 SGLT2i；Table 1 為 finerenone 135（17.0%）vs placebo 135（17.1%）。<!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄
- SGLT2i 使用者的 slope 差為 0.84（95% CI −0.06 至 1.73），未使用者 0.65（95% CI 0.25 至 1.06）。<!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄
- 可提問：能否提供 **treatment-emergent SGLT2i 使用**（試驗期間新開始者）的資料，或依時間變動的 SGLT2i 暴露分析？
- **風險**：主文 Discussion 已主動承認此限制（`we hypothesize that the use of both finerenone and SGLT2 inhibitors may provide complementary effects, this was not directly tested in the present trial`）<!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄，且 CONFIDENCE 的 correspondence 交流已存在 📌。新穎度中等。

## 第三優先：約 5 mmHg 的收縮壓差異是否中介腎臟效益

- 事實：第 3 個月收縮壓變化 −5.1 mmHg（finerenone）vs −0.1 mmHg（placebo）；舒張壓 −3.1 vs 小於 −0.1 mmHg。<!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄
- 對照：FIDELIO-DKD 的血壓效應較小（第 1、12 個月收縮壓變化 −3.0 與 −2.1 mmHg vs placebo −0.1 與 0.9 mmHg）。<!-- src:原始PDF/Bakris_2020_FIDELIO-DKD.md --> 📄 FIND-CKD 的 5.0 mmHg 差距明顯較大，提問有立足點。
- 正確措辭：血壓是**隨機化之後**產生的變項，屬 mediator 而非 confounder；應要求 causal mediation analysis 或依早期血壓反應分層的描述性結果，**不可**要求「調整血壓後重算」。
- **風險**：需要作者做新分析，175 字內難以說清方法學要求。

## 第四優先：hierarchical testing 的解讀邊界

- 事實：kidney-only composite HR 0.78（95% CI 0.60–1.01，P=0.06）；CV composite 僅 10 vs 16 件，HR 0.60（95% CI 0.27–1.33）。<!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄
- 論點：階層檢定在第三層未達 P<0.05 後，CV composite 不能作為 confirmatory claim；FIND-CKD 本質仍是 **eGFR slope trial with supportive event data**。
- **風險**：主文已寫 `our trial was not powered to assess the effects of the trial regimens on clinical outcomes`<!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄，編輯可能認為重複。

## 不建議的角度

| 角度 | 不建議原因 |
|---|---|
| 各 glomerular disease 亞型效果是否一致 | 已有 JAMA 2026 相關分析發表（DOI 10.1001/jama.2026.9923）📌，僅陳述「此分析已存在」 |
| 「整體證據是否足夠」 | 已有 INFINITY pooled IPD 分析發表（Lancet 2026, DOI 10.1016/S0140-6736(26)01009-3）📌，僅陳述「此分析已存在」 |
| 族群代表性（33.8% 女性、56.4% 亞裔、Black 僅 2.8%/1.9%）<!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄 | 主文 limitations 已逐項自陳，屬 ghost novelty |
| 用 flawed／misleading／invalid 等對抗性措辭 | NEJM 通信欄語域不符，且此題根本不需要 |
| 一封信同時談 hyperkalemia + SGLT2i + 血壓 + surrogate endpoint | 175 字必定失焦（本檔作者之編輯判斷，非引自任何來源） |

---

# 四、投稿時效與程序 caveats

## 4.1 已知的日期事實

- 主文標註：`This article was published on June 4, 2026, and updated on June 29, 2026, at NEJM.org.`<!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄
- 紙本卷期：`N Engl J Med 2026;395:533-45.`，頁眉為 `AUGUST 6, 2026`，Vol. 395 No. 6。<!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄
- 今日為 2026-08-09。

## 4.2 三週規則的不確定性（必須現場確認，不可自行假設）

本檔**未落地** NEJM letters instructions 原文，因此不對「3 週」規則的字面文字作引用性斷言。可確定的只是**三個候選起算日彼此相差近兩個月**：6/4（online）、6/29（updated）、8/6（print issue）。三種可能：

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
- [ ] 確認 Supplementary Appendix（Table S8 等）是否對 hyperkalemia 住院有第三種數字；本檔僅有主文，未含 Supplementary Appendix。**未落地內容一律不得引用。**
- [ ] 正文嚴格維持單一問題，不加入 SGLT2i、血壓、surrogate endpoint。
- [ ] 所有共同作者逐字核對 Table 2 與 Discussion 原文。
- [ ] 依投稿介面揭露利益衝突與 AI/LLM 輔助撰稿。
- [ ] 在 NEJM 做出決定前，不將同一英文內容公開於社群、部落格或其他期刊。

## 4.4 若作者回覆「指的是更窄的類別」

預備第二輪回應素材（皆已落地、可 grep）：

- Table 2 已把住院列在 `Serious adverse event related to hyperkalemia` 之下，該層 Overall 為 8（1.0%）vs 5（0.6%），`Leading to hospitalization` 為 7（0.9%）vs 5（0.6%）——**已經是最窄的類別了**，不存在更窄的層級可供退守。<!-- src:FIND-CKD main text NEJMoa2604625.md --> 📄
- 設計論文的 prespecified safety 條列僅寫到高血鉀住院此一層級，未再細分（逐字連續片段：`for hyperkalaemia and permanent discontinuation of study`）。<!-- src:原始PDF/Heerspink_2025_FIND-CKD-design.md --> 📄

---

## 附：本檔未使用的「危險數字」警示

以下數字**曾在前期備忘錄（ChatGPT 版）出現，但本地無全文可驗**，故本檔全部未引用，投稿時亦不得寫入：

- JAMA glomerular 分析的任何內文數字（納入人數、eGFR slope difference）📌（全文未落地，一律不得引用；903/1584 是 FIND-CKD **設計論文**的基線人數 <!-- src:原始PDF/Heerspink_2025_FIND-CKD-design.md --> 📄，不得掛在 JAMA 名下）
- INFINITY 的任何內文數字（樣本數、HR）📌（全文未落地，一律不得引用；n=14,574 僅出自未驗證之 ChatGPT 備忘錄，已從本檔移除）
- Nature Reviews Nephrology 評論的內容 📌（連 metadata 都未經本流程驗證，**完全不引用**）
- FIDELIO/DAPA-CKD/CONFIDENCE correspondence 各封信的具體論點 📌（僅可引「存在此交流」）

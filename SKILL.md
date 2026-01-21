---
name: Medical Paper Analysis
description: Comprehensive framework for analyzing medical research papers with critical appraisal, statistical interpretation, and clinical application assessment
---

# Medical Paper Analysis Skill

This skill provides a structured approach to analyzing medical research papers, from quick summaries to in-depth critical appraisal. It helps extract key findings, evaluate study quality, and assess clinical applicability.

## When to Use This Skill

Use this skill when you need to:
- Quickly summarize medical research papers
- Perform critical appraisal of study methodology
- Interpret complex statistical analyses
- Compare multiple studies
- Evaluate clinical applicability of research findings
- Analyze systematic reviews and meta-analyses

## Core Analysis Framework

### 1. Quick Summary (5-Minute Review)

For rapid assessment of any medical paper, provide:

**Study Purpose**: What clinical question does this research address? (1 sentence)

**Study Design**: Research type and sample size (1-2 sentences)

**Key Findings**: Main results with specific data (p-values, 95% CI, effect sizes)

**Clinical Significance**: Impact on clinical practice and current treatment guidelines

**Evidence Level**: Strength of evidence (High/Moderate/Low)

Output should be:
- Concise (under 1000 words)
- Bullet-point format
- Each point maximum 2 sentences
- Include specific numerical data
- 使用繁體中文

### 2. In-Depth Critical Appraisal

For comprehensive analysis, evaluate:

#### Part A: Study Quality Assessment

**Study Design**
- Type: RCT / Cohort / Case-Control / Cross-sectional
- Appropriateness for research question
- Evidence pyramid level

**Methodological Quality** (Use CONSORT checklist for RCTs)
- Randomization method and execution
- Allocation concealment adequacy
- Blinding (single/double/triple)
- Sample size calculation and statistical power

**Subject Characteristics**
- Inclusion/exclusion criteria appropriateness
- Baseline characteristics balance
- Loss to follow-up rate
- ITT vs PP analysis

#### Part B: Statistical Analysis Review

**Method Selection**
- Appropriateness of statistical tests
- Multiple comparison handling
- Missing data management

**Results Reporting**
- Primary endpoint statistical significance
- Clinical significance of effect size
- Confidence interval interpretation
- Secondary endpoint interpretation

#### Part C: Bias Risk Assessment (Cochrane RoB 2.0)

Assess risk in five domains:
1. Randomization process
2. Deviations from intended interventions
3. Missing outcome data
4. Outcome measurement
5. Selective reporting

Label each: Low risk / Some concerns / High risk

#### Part D: Evidence Quality (GRADE System)

Evaluate and grade from:
- Study design (starting score)
- Risk of bias (downgrade factor)
- Inconsistency (downgrade factor)
- Indirectness (downgrade factor)
- Imprecision (downgrade factor)
- Publication bias (downgrade factor)

Final grade: High / Moderate / Low / Very Low

#### Part E: Comprehensive Commentary

1. Main strengths (3 points)
2. Main limitations (3 points)
3. External validity: Generalizability to your patients
4. Conflicts of interest or sponsorship influence
5. Overall recommendation: Should clinical practice change?

### 3. Statistical Methods Deep Dive

For complex statistical sections:

**Method Identification**
- List all statistical methods used
- Provide Chinese and English full names

**Method Selection Rationale**
- Why was this method chosen?
- What data types does it suit? (continuous/categorical/time-to-event)
- How did research question influence method selection?

**Statistical Assumptions**
- Key assumptions for each method
- Were assumptions tested?
- Consequences of assumption violations

**Results Interpretation Guide**
- p-value meaning: Statistical vs clinical significance
- 95% CI interpretation and relationship to minimal clinically important difference
- Effect size clinical meaning (Cohen's d / OR / HR)
- Interaction term interpretation if present

**Alternative Methods Discussion**
- Other applicable statistical approaches
- Pros and cons of alternatives
- Why author's choice may (or may not) be optimal

**Common Pitfalls**
- Typical interpretation errors clinicians make
- Critical details to watch for

### 4. Figure and Table Interpretation

For any figure/table in the paper:

**Basic Information**
- Figure/table type identification
- Why this visualization was chosen
- What information type it best conveys

**Axis and Legend Interpretation**
- X-axis meaning and units
- Y-axis meaning and units
- Legend interpretation
- Color/symbol/line meanings
- Error bar meaning (SD/SE/95% CI)

**Data Interpretation**
- Observable trends
- Between-group differences and statistical significance
- p-value markings and their meaning
- Effect size magnitude and clinical importance

**Special Figure Types**

*For Forest Plots:*
- Diamond meaning
- Horizontal line meaning
- Vertical dashed line (typically at 1.0) meaning
- Study weight determination
- Pooled effect size
- Heterogeneity index (I²) and interpretation

*For Kaplan-Meier Curves:*
- Survival curve trajectory
- When curves separate
- Log-rank test p-value
- Median survival times
- Survival rates at specific timepoints (e.g., 5-year)
- Censoring marks and frequency

*For ROC Curves:*
- AUC (area under curve) value
- AUC interpretation for diagnostic value
- Optimal cut-off point location
- Sensitivity and specificity at that cut-off
- Distance from diagonal line meaning

**Potential Issues**
- Misleading presentation
- Y-axis manipulation exaggerating differences
- Selective data presentation concerns
- Missing important information (sample sizes, confidence intervals)
- Statistical method appropriateness

### 5. Clinical Application Assessment

Evaluate clinical practice impact:

#### Evidence-Based Medicine Triangle

**A) Best Evidence**
- Evidence level: 1a/1b/2a/2b/3a/3b/4/5
- Study quality: High/Moderate/Low
- Recommendation strength: Strong/Weak/Against

**B) Clinical Expertise**
- Intervention usage in your specialty:
  * Routine use
  * Occasional use
  * Rare use
  * Never used
- Required special skills or equipment
- Learning curve considerations

**C) Patient Values**
- Patient benefits
- Patient risks
- Potential patient concerns
- How to discuss this treatment option with patients

#### PICO Applicability Analysis

**Population**
Compare study population vs your patients:
- Age
- Gender
- Disease severity
- Comorbidities
- Race/geographic region

Conclusion: Similarity (High/Moderate/Low)

**Intervention**
- Feasibility in your setting
- Drug/device regulatory approval and insurance coverage
- Dose/frequency appropriateness for your patients
- Needed adjustments

**Comparison**
- Is study control group current standard of care?
- What is current standard of care in your practice?
- How do differences affect result interpretation?

**Outcome**
- Are measured outcomes important to your patients?
- Missing important outcome measures?
- Adequate follow-up duration?

#### Number Needed to Treat (NNT) Calculation

If paper provides sufficient information:
- NNT = [number]
- Interpretation: Need to treat X patients for 1 to benefit
- Number Needed to Harm (NNH) = [number] (if adverse event data available)
- Benefit-harm ratio: NNH/NNT

#### Clinical Decision Analysis

**Scenario 1: Typical Patient**
Patient meeting study inclusion criteria:
- Should new treatment be used?
- Rationale:

**Scenario 2: Marginal Patient**
Patient partially meeting criteria (older, comorbidities):
- Should new treatment be used?
- Additional considerations?
- Rationale:

**Scenario 3: Patient Not Meeting Inclusion Criteria**
- Can results be extrapolated?
- What requires special monitoring?
- Risk assessment:

#### Guideline Integration

- Current guideline recommendations
- Consistency between study findings and guidelines
- Is this study sufficient to change guidelines?
- When to wait for more evidence vs early adoption?

#### Implementation Plan

If adopting this new treatment:
- Required resources (personnel/equipment/budget)
- Needed training
- How to monitor efficacy and safety
- Documentation and tracking
- When to reassess

#### Patient Communication Script

Provide:
- Plain language explanation of new treatment
- How to explain potential benefits (use absolute risk, not relative risk)
- How to explain potential risks
- How to address common patient questions
- Shared decision-making dialogue examples

### 6. Systematic Review Evaluation

For systematic reviews, use PRISMA checklist:

#### Methodology Assessment

**Search Strategy**
- Databases searched - comprehensive?
- Search strategy appropriateness (sensitivity and specificity)
- Search timeframe
- Grey literature searched?
- Hand-searching of references?
- Language restrictions and potential bias

**Study Selection**
- Clear inclusion/exclusion criteria
- PICO framework present
- Two independent reviewers for screening
- Disagreement resolution method
- PRISMA flow diagram analysis:
  * Initial search results
  * After duplicate removal
  * After title/abstract screening
  * After full-text assessment
  * Finally included
  * Exclusion reasons at each stage

**Data Extraction**
- Extracted data elements
- Standardized form used
- Two independent extractors
- Missing data handling
- Contact with original authors for data

**Quality Assessment**
- Tool used for bias risk assessment:
  * RCTs: Cochrane RoB 2.0
  * Observational studies: Newcastle-Ottawa Scale
  * Other tools
- Assessment results and bias risk per study
- Sensitivity analysis excluding low-quality studies

#### Results Evaluation

**Included Studies Characteristics**
Create table of study characteristics:
| Study | Year | Design | Sample Size | Intervention | Control | Follow-up | Bias Risk |

**Heterogeneity Assessment**
- I² statistic value:
  * I² <25%: Low heterogeneity
  * I² 25-50%: Moderate heterogeneity
  * I² >50%: High heterogeneity
- Cochran's Q test p-value
- Possible sources of heterogeneity (explore via subgroup analysis or meta-regression)

**Pooled Effect**
- Fixed-effect or random-effects model? Why?
- Pooled effect size:
  * Odds Ratio / Risk Ratio / Hazard Ratio
  * 95% CI
  * p-value
- Forest plot interpretation:
  * Overall effect direction
  * Consistency across studies
  * Does diamond cross line of no effect?

**Publication Bias**
- Publication bias assessed?
- Methods used:
  * Funnel plot (visual)
  * Egger's test
  * Begg's test
- Results - evidence of publication bias?
- If yes, trim-and-fill analysis performed?

#### GRADE Evidence Quality

Assess certainty, starting from high quality, consider downgrading factors:

| GRADE Factor | Assessment | Downgrade? | Reason |
|--------------|------------|------------|---------|
| 1. Study design | | | |
| 2. Risk of bias | | | |
| 3. Inconsistency | | | |
| 4. Indirectness | | | |
| 5. Imprecision | | | |
| 6. Publication bias | | | |

Final evidence level: ⊕⊕⊕⊕ High / ⊕⊕⊕◯ Moderate / ⊕⊕◯◯ Low / ⊕◯◯◯ Very Low

### 7. Meta-Analysis Deep Dive

For meta-analyses:

#### Statistical Model Selection
- Fixed-effect vs random-effects model
- Selection rationale (based on I² or predetermined)
- If random-effects, which method:
  * DerSimonian-Laird
  * Restricted maximum likelihood (REML)
  * Hartung-Knapp adjustment

#### Heterogeneity In-Depth Analysis

**Statistical Heterogeneity**
- I² = [value] %
- Cochran's Q test:
  * Q statistic
  * p-value
  * df
- τ² (tau-squared, heterogeneity variance)

**Heterogeneity Source Investigation**
1. Subgroup analyses
   - Defined subgroups
   - Test for subgroup differences results

2. Meta-regression
   - Covariates used
   - Can results explain heterogeneity?
   - R² (proportion of heterogeneity explained)

3. Sensitivity analysis
   - Leave-one-out analysis
   - Does result change after excluding specific studies?
   - Which are influential studies?

#### Forest Plot Detailed Interpretation

**Visual Inspection**
- Point estimate distribution across studies
- Confidence interval overlap
- Obvious outliers
- Weight distribution (square sizes)

**Pooled Effect**
- Pooled estimate = [value]
- 95% CI = [lower, upper]
- p-value
- Diamond position relative to line of no effect (RR/OR=1 or MD=0)

**Clinical Significance**
- Effect size clinical importance
  * Reaches minimal clinically important difference (MCID)?
- Does CI include clinically important difference threshold?
- Absolute risk reduction (ARR)
- Number Needed to Treat (NNT)

#### Publication Bias Assessment

**Funnel Plot**
- Plot symmetry
- Small-study effect present?
- Which part is missing (potential unpublished studies)

**Statistical Tests**
- Egger's test: p = ?
- Begg's test: p = ?
- Conclusion: [Evidence/No evidence] of publication bias

**Adjustment Analysis**
If publication bias exists:
- Trim and fill method
  * How many studies added?
  * Adjusted pooled estimate = ?
- Other methods (selection models)

#### Advanced Analyses

**Cumulative Meta-Analysis**
- Performed?
- When did evidence reach statistical significance?
- Do recent studies change conclusions?

**Trial Sequential Analysis (TSA)**
- Performed?
- Required information size (RIS) = ?
- Sufficient information reached?
- Does Z-curve cross monitoring boundary?
- Conclusion: More studies needed?

## 8. Critical Appraisal Framework by Study Design (文獻評讀架構)

This section provides evidence-based critical appraisal tools tailored to different study designs. Always start by identifying the study type, then apply the appropriate evaluation framework.

### Study Design Identification Decision Tree

```
START: What is the research question?
│
├─ Treatment/Intervention effectiveness?
│  ├─ Randomized allocation? → RCT
│  ├─ Non-randomized comparison? → Quasi-experimental / Controlled trial
│  └─ No intervention, just observation? → Observational study
│
├─ Diagnostic accuracy?
│  └─ Compare test to gold standard? → Diagnostic study
│
├─ Prognosis/Risk prediction?
│  ├─ Follow patients forward? → Cohort study
│  └─ Develop/validate prediction model? → Prognostic model study
│
├─ Etiology/Risk factors?
│  ├─ Start with disease-free, follow forward? → Prospective cohort
│  ├─ Start with cases vs controls, look back? → Case-control study
│  └─ One-time assessment? → Cross-sectional study
│
├─ Prevalence/Disease burden?
│  └─ Survey at single timepoint? → Cross-sectional study
│
└─ Synthesize existing evidence?
   ├─ Quantitative pooling? → Meta-analysis
   ├─ Systematic synthesis? → Systematic review
   └─ Best practice guidance? → Clinical practice guideline
```

### 8.1 Randomized Controlled Trial (RCT) 評讀

**使用時機**: 評估治療或介入措施的療效

**評讀工具**: CONSORT Checklist + Cochrane RoB 2.0

#### CONSORT 核心項目 (簡化版)

| 項目 | 評估重點 | 評分 |
|------|----------|------|
| **1. 標題與摘要** | 是否註明為 RCT？ | ✓/✗ |
| **2. 背景** | 研究理由與目的清楚？ | ✓/✗ |
| **3. 參與者** | 納入/排除標準明確？招募地點與時間？ | ✓/✗ |
| **4. 介入措施** | 各組介入措施詳細描述？ | ✓/✗ |
| **5. 結果指標** | 主要與次要結果事前定義？測量時間？ | ✓/✗ |
| **6. 樣本數** | 是否事前計算？檢定力？ | ✓/✗ |
| **7. 隨機化** | 隨機序列如何產生？誰執行？ | ✓/✗ |
| **8. 分配隱藏** | 如何確保分配隱藏？ | ✓/✗ |
| **9. 盲法** | 誰被設盲？如何執行？ | ✓/✗ |
| **10. 統計方法** | 主要分析方法？ITT？次群組分析預定？ | ✓/✗ |
| **11. 參與者流程** | CONSORT 流程圖？各階段人數？ | ✓/✗ |
| **12. 基線資料** | 各組基線特徵是否平衡？ | ✓/✗ |
| **13. 主要結果** | 主要終點結果與效應量？ | ✓/✗ |
| **14. 不良反應** | 是否報告？ | ✓/✗ |
| **15. 利益衝突** | 是否揭露？ | ✓/✗ |

#### Cochrane RoB 2.0 偏差風險評估

對每個領域評估：**低風險 / 一些疑慮 / 高風險**

1. **隨機化過程的偏差**
   - 分配序列是否真正隨機？
   - 分配隱藏是否適當？
   - 基線特徵是否有重要差異？

2. **偏離預定介入措施的偏差**
   - 參與者與執行者是否知道分配？
   - 是否有偏離介入且與結果相關？
   - 是否適當分析（ITT）？

3. **結果數據缺失的偏差**
   - 缺失數據多嗎？
   - 缺失原因與真實結果相關嗎？
   - 缺失數據可能影響結果嗎？

4. **結果測量的偏差**
   - 結果測量方法是否適當？
   - 評估者是否被設盲？
   - 測量是否受介入知識影響？

5. **選擇性報告結果的偏差**
   - 結果是否按預先計畫報告？
   - 結果選擇是否基於多重測量/分析？

**整體偏差風險判斷**:
- **低風險**: 所有領域都是低風險
- **一些疑慮**: 至少一個領域有疑慮，但無高風險
- **高風險**: 至少一個領域是高風險，或多個領域有疑慮

### 8.2 系統性文獻回顧與 Meta-analysis 評讀

**使用時機**: 評估綜合多個研究的證據

**評讀工具**: PRISMA Checklist + AMSTAR 2

#### PRISMA 2020 核心檢核表

**第一部分：標題、摘要、引言**
- [ ] 標題中註明為系統性文獻回顧
- [ ] 摘要包含結構化格式
- [ ] 背景說明研究理由

**第二部分：方法**
- [ ] 資格標準：明確的 PICO
- [ ] 資訊來源：搜尋哪些資料庫？時間範圍？
- [ ] 搜尋策略：至少一個資料庫的完整策略
- [ ] 研究選擇：誰篩選？如何解決分歧？
- [ ] 資料收集：使用標準化表格？
- [ ] 偏差風險評估：使用什麼工具？
- [ ] 效應測量：使用什麼統計量（OR/RR/MD）？
- [ ] 綜合方法：如何整合資料？Meta-analysis 方法？
- [ ] 異質性評估：如何評估與處理？
- [ ] 發表偏差：如何評估？

**第三部分：結果**
- [ ] 研究選擇：PRISMA 流程圖完整
- [ ] 研究特徵：特徵表完整
- [ ] 偏差風險：每個研究都評估了嗎？
- [ ] 結果綜合：森林圖？異質性數據（I²）？
- [ ] 發表偏差：漏斗圖？統計檢定？

**第四部分：討論與其他**
- [ ] 證據總結：GRADE 評估？
- [ ] 限制：研究與文獻回顧層級的限制
- [ ] 資金來源與利益衝突揭露

#### AMSTAR 2 (簡化版質量評估)

**關鍵領域** (這些對結果影響最大):
1. 事前登記研究方案
2. 文獻搜尋全面性（至少2個資料庫）
3. 雙重獨立篩選
4. 雙重獨立資料萃取
5. 偏差風險評估
6. Meta-analysis 方法適當
7. 考慮偏差風險於結果解讀

**評級**:
- **高品質**: 無或僅1個非關鍵弱點
- **中等品質**: 1個關鍵弱點，無非關鍵弱點
- **低品質**: 1個關鍵弱點 + 非關鍵弱點
- **極低品質**: 2個以上關鍵弱點

### 8.3 觀察性研究評讀

#### A. 世代研究 (Cohort Study)

**使用時機**: 評估暴露因子與結果的關聯、預後

**評讀工具**: Newcastle-Ottawa Scale (NOS) + STROBE

**Newcastle-Ottawa Scale 評分**:

*選擇 (Selection) - 最多4顆星*
- [ ] 世代代表性 (1星)
- [ ] 未暴露組的選擇 (1星)
- [ ] 暴露的確認 (1星)
- [ ] 研究開始時結果未發生 (1星)

*可比性 (Comparability) - 最多2顆星*
- [ ] 世代的可比性（主要混淆因子）(1星)
- [ ] 額外因子控制 (1星)

*結果 (Outcome) - 最多3顆星*
- [ ] 結果評估 (1星)
- [ ] 追蹤時間足夠長 (1星)
- [ ] 追蹤完整度 (1星)

**評分標準**: ≥7星 = 高品質；5-6星 = 中等；≤4星 = 低品質

**關鍵問題**:
1. 是否有未測量的混淆因子？
2. 失訪率高嗎（>20%）？
3. 時序關係明確嗎（暴露→結果）？

#### B. 病例對照研究 (Case-Control Study)

**使用時機**: 研究罕見疾病的危險因子

**評讀工具**: Newcastle-Ottawa Scale (病例對照版)

*選擇 - 最多4顆星*
- [ ] 病例定義適當 (1星)
- [ ] 病例代表性 (1星)
- [ ] 對照組選擇 (1星)
- [ ] 對照組定義 (1星)

*可比性 - 最多2顆星*
- [ ] 病例與對照的可比性 (2星)

*暴露 - 最多3顆星*
- [ ] 暴露確認 (1星)
- [ ] 病例與對照使用相同方法 (1星)
- [ ] 未回應率 (1星)

**特別注意的偏差**:
- **選擇偏差**: 對照組是否來自相同族群？
- **回憶偏差**: 病例組是否更容易記得暴露？
- **匹配過度**: 是否匹配了中介變項？

#### C. 橫斷面研究 (Cross-sectional Study)

**使用時機**: 盛行率調查、多因子關聯

**評讀重點**:
- 抽樣方法（隨機？便利？）
- 樣本代表性
- 回應率
- 測量工具效度
- **限制**: 無法確定因果關係（暴露與結果同時測量）

### 8.4 診斷準確度研究評讀

**使用時機**: 評估診斷工具的效能

**評讀工具**: QUADAS-2 (Quality Assessment of Diagnostic Accuracy Studies)

#### QUADAS-2 評估領域

**領域 1: 病人選擇**
- 偏差風險：是否為連續或隨機樣本？是否避免病例-對照設計？
- 適用性疑慮：納入病人是否符合問題情境？

**領域 2: 待測試驗 (Index Test)**
- 偏差風險：結果解讀是否不知道參考標準結果？是否預先設定閾值？
- 適用性疑慮：待測試驗的執行是否符合臨床情境？

**領域 3: 參考標準 (Reference Standard)**
- 偏差風險：參考標準是否正確分類目標疾病？是否不知道待測試驗結果？
- 適用性疑慮：參考標準定義是否符合問題？

**領域 4: 流程與時序**
- 偏差風險：所有病人都接受參考標準嗎？時間間隔適當？所有病人納入分析？

**評估**: 低風險 / 高風險 / 不清楚

**診斷指標解讀**:
- 敏感度 (Sensitivity): 有病的人中，檢查陽性的比例
- 特異度 (Specificity): 沒病的人中，檢查陰性的比例
- PPV (陽性預測值): 檢查陽性的人中，真有病的比例
- NPV (陰性預測值): 檢查陰性的人中，真沒病的比例
- LR+ (陽性似然比): >10 大幅增加疾病機率
- LR- (陰性似然比): <0.1 大幅降低疾病機率

### 8.5 預後/預測模型研究評讀

**使用時機**: 評估預後因子或臨床預測模型

**評讀工具**: PROBAST (Prediction model Risk Of Bias ASsessment Tool)

#### PROBAST 評估領域

**領域 1: 參與者**
- 資料來源適當？
- 納入與排除標準適當？
- 適用性：參與者是否符合目標族群？

**領域 2: 預測因子**
- 定義與評估方式明確？
- 是否所有參與者以相同方式評估？
- 適用性：預測因子定義是否符合問題？

**領域 3: 結果**
- 結果定義適當？
- 結果的確定是否不受預測因子影響（盲性）？
- 適用性：結果定義是否符合問題？

**領域 4: 分析**
- 樣本數是否足夠？
- 缺失資料處理是否適當？
- 模型建立時，預測因子選擇是否適當？
- 模型效能報告完整？
- 是否過度擬合 (overfitting)？
- 是否有外部驗證？

**C-statistic (AUC) 解讀**:
- 0.9-1.0: 優秀
- 0.8-0.9: 良好
- 0.7-0.8: 尚可
- 0.6-0.7: 差
- 0.5-0.6: 失敗

**Calibration (校準)**: 預測機率與觀察到的事件發生率是否一致

### 8.6 臨床實務指引評讀

**使用時機**: 評估臨床指引的質量

**評讀工具**: AGREE II (Appraisal of Guidelines for Research & Evaluation)

#### AGREE II 六大領域 (每項 1-7 分)

**領域 1: 範疇與目的**
- 整體目標明確描述
- 健康問題明確描述
- 目標族群明確定義

**領域 2: 利害關係人參與**
- 指引發展小組包含所有相關專業
- 考慮目標族群的觀點與偏好
- 目標使用者明確定義

**領域 3: 發展嚴謹性** (最重要)
- 系統性方法搜尋證據
- 證據選擇標準明確
- 證據的優缺點明確描述
- 建議與證據之間的連結清楚
- 外部專家審查
- 更新程序

**領域 4: 表達清晰性**
- 建議明確具體
- 提供不同處置選項
- 關鍵建議容易辨識

**領域 5: 應用性**
- 討論實施的促進與阻礙因子
- 提供實施建議/工具
- 考慮資源影響
- 提供監測/稽核標準

**領域 6: 編輯獨立性**
- 資金來源不影響內容
- 利益衝突記錄與處理

**整體評估**:
- 強烈推薦
- 有修改後推薦
- 不推薦

### 8.7 質性研究評讀

**使用時機**: 評估病人經驗、態度、意見

**評讀工具**: COREQ (Consolidated criteria for Reporting Qualitative research)

**關鍵評估面向**:
1. **研究團隊與反思性**
   - 研究者背景與偏見說明
   - 與參與者的關係

2. **研究設計**
   - 理論架構說明
   - 參與者選擇方式
   - 飽和度達成

3. **分析與發現**
   - 資料分析方法明確
   - 引用原始資料支持主題
   - 參與者檢核 (member checking)

### 8.8 評讀工具快速選擇表

| 研究類型 | 主要評讀工具 | 次要參考 | 評估重點 |
|---------|-------------|---------|---------|
| **RCT** | Cochrane RoB 2.0 | CONSORT, Jadad | 隨機化、盲法、ITT |
| **世代研究** | Newcastle-Ottawa | STROBE | 混淆控制、失訪率 |
| **病例對照** | Newcastle-Ottawa | - | 對照選擇、回憶偏差 |
| **橫斷面** | - | STROBE | 抽樣、因果推論限制 |
| **診斷研究** | QUADAS-2 | STARD | 參考標準、盲性 |
| **預後模型** | PROBAST | TRIPOD | 驗證、校準、過度擬合 |
| **系統性文獻回顧** | AMSTAR 2 | PRISMA | 搜尋策略、偏差評估 |
| **Meta-analysis** | Cochrane handbook | PRISMA | 異質性、發表偏差 |
| **臨床指引** | AGREE II | - | 證據基礎、獨立性 |
| **質性研究** | COREQ | - | 可信度、反思性 |

### 8.9 GRADE 證據等級整合評估

所有研究類型最終都應使用 GRADE 系統評估證據確定性：

**起始等級**:
- RCT: 高 (⊕⊕⊕⊕)
- 觀察性研究: 低 (⊕⊕◯◯)

**降級因素** (每項可降 1-2 級):
1. **偏差風險** (Risk of bias): 研究設計或執行有嚴重缺陷
2. **不一致性** (Inconsistency): 研究間結果變異大且無法解釋
3. **間接性** (Indirectness): PICO 與問題不完全吻合
4. **不精確性** (Imprecision): 樣本數小、信賴區間寬
5. **發表偏差** (Publication bias): 有小研究效應證據

**升級因素** (僅適用於觀察性研究):
1. 大效應量 (RR >2 或 <0.5)
2. 劑量效應梯度
3. 所有可能的混淆因子會降低效應

**最終證據等級**:
- ⊕⊕⊕⊕ **高**: 非常確信真實效應接近估計效應
- ⊕⊕⊕◯ **中**: 中度確信，真實效應可能接近估計效應
- ⊕⊕◯◯ **低**: 確信度有限，真實效應可能與估計效應有很大差異
- ⊕◯◯◯ **極低**: 幾乎不確信估計效應

**建議強度連結**:
- 高證據等級 → 通常是強建議
- 低證據等級 → 通常是弱建議（但不絕對，還需考慮效益風險比、病人價值觀等）

### 8.10 文獻評讀實戰步驟

**步驟 1: 快速篩選** (1分鐘)
- 看標題：相關嗎？
- 看摘要：符合 PICO 嗎？
- 看期刊：可信嗎？

**步驟 2: 設計識別** (2分鐘)
- 使用決策樹確定研究類型
- 選擇對應的評讀工具

**步驟 3: 系統化評讀** (15-30分鐘)
- 使用檢核表逐項評估
- 記錄關鍵缺陷
- 標註偏差風險

**步驟 4: 證據整合** (5分鐘)
- GRADE 評級
- 撰寫評論摘要
- 決定是否改變實務

**步驟 5: 臨床轉譯** (依需求)
- 套用 PICO 到自己病人
- 計算 NNT
- 準備 SDM 對話

---

## Output Formatting Guidelines

All analyses should:
- Use clear, structured formatting
- Include tables for comparative data
- Highlight key statistical values
- Provide both statistical and clinical interpretations
- Use bullet points and numbered lists for readability
- Include visual descriptions when discussing figures
- Mark statistical significance: * for p<0.05, ** for p<0.01
- Use symbols for results: ↑ positive, ↓ negative, → no difference

## Adaptation for Different Users

Adjust complexity based on user background:
- **Medical students**: Focus on basic concepts, use more analogies
- **Residents**: Balance between learning and application
- **Attending physicians**: Emphasize clinical application and practice changes
- **Researchers**: Include methodological details and statistical nuances

## Language Considerations

Default to English for medical papers, but can provide:
- Chinese (Traditional) for Taiwanese medical terminology
- Bilingual summaries when requested
- Culturally appropriate clinical examples

## Key Principles

1. **Evidence-based**: All assessments grounded in established frameworks (CONSORT, PRISMA, GRADE, etc.)
2. **Clinical focus**: Always connect findings to clinical practice
3. **Critical thinking**: Identify both strengths and limitations
4. **Clear communication**: Translate complex statistics into clinically meaningful language
5. **Actionable**: Provide specific recommendations for practice changes
6. **Comprehensive yet concise**: Thorough analysis without unnecessary verbosity

## Example Usage

When analyzing a paper, specify:
- Analysis type needed (quick summary, full critical appraisal, statistical focus, etc.)
- Your background/specialty
- Specific questions or concerns
- Target patient population for applicability assessment

The skill will then provide structured analysis using the appropriate framework from above.

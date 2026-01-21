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

---

## Analysis Workflow

### Step 1: Study Design Identification → Step 2: Quick Summary → Step 3: Critical Appraisal → Step 4: Statistical Analysis → Step 5: Clinical Translation

---

## 1. Study Design Identification

Before analyzing any paper, identify the study type using this decision tree:

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

### Quick Reference Table: Study Design → Critical Appraisal Tool

| Study Type | Primary Tool | Secondary Reference | Key Assessment Points |
|------------|-------------|---------------------|----------------------|
| **RCT** | Cochrane RoB 2.0 | CONSORT, Jadad | Randomization, blinding, ITT |
| **Cohort Study** | Newcastle-Ottawa | STROBE | Confounding control, loss to follow-up |
| **Case-Control** | Newcastle-Ottawa | - | Control selection, recall bias |
| **Cross-sectional** | - | STROBE | Sampling, causal inference limitations |
| **Diagnostic Study** | QUADAS-2 | STARD | Reference standard, blinding |
| **Prognostic Model** | PROBAST | TRIPOD | Validation, calibration, overfitting |
| **Systematic Review** | AMSTAR 2 | PRISMA | Search strategy, bias assessment |
| **Meta-analysis** | Cochrane handbook | PRISMA | Heterogeneity, publication bias |
| **Clinical Guideline** | AGREE II | - | Evidence base, independence |
| **Qualitative Study** | COREQ | - | Credibility, reflexivity |

---

## 2. Quick Summary (5-Minute Review)

For rapid assessment of any medical paper, provide:

**Study Purpose**: What clinical question does this research address? (1 sentence)

**Study Design**: Research type and sample size (1-2 sentences)

**Key Findings**: Main results with specific data (p-values, 95% CI, effect sizes)

**Clinical Significance**: Impact on clinical practice and current treatment guidelines

**Evidence Level**: Strength of evidence (High/Moderate/Low)

**Output Format**:
- Concise (under 1000 words)
- Bullet-point format
- Each point maximum 2 sentences
- Include specific numerical data

---

## 3. Critical Appraisal by Study Design

### 3.1 Randomized Controlled Trial (RCT)

**When to Use**: Evaluating treatment or intervention efficacy

**Appraisal Tools**: CONSORT Checklist + Cochrane RoB 2.0

#### CONSORT Core Items (Simplified)

| Item | Assessment Point | Score |
|------|-----------------|-------|
| **1. Title & Abstract** | Identified as RCT? | ✓/✗ |
| **2. Background** | Rationale and objectives clear? | ✓/✗ |
| **3. Participants** | Inclusion/exclusion criteria clear? Recruitment settings and dates? | ✓/✗ |
| **4. Interventions** | Detailed description of interventions for each group? | ✓/✗ |
| **5. Outcomes** | Primary and secondary outcomes predefined? Measurement times? | ✓/✗ |
| **6. Sample Size** | Sample size calculated a priori? Statistical power? | ✓/✗ |
| **7. Randomization** | How was random sequence generated? Who performed it? | ✓/✗ |
| **8. Allocation Concealment** | How was allocation concealment ensured? | ✓/✗ |
| **9. Blinding** | Who was blinded? How was it implemented? | ✓/✗ |
| **10. Statistical Methods** | Primary analysis method? ITT? Subgroup analyses prespecified? | ✓/✗ |
| **11. Participant Flow** | CONSORT flow diagram? Numbers at each stage? | ✓/✗ |
| **12. Baseline Data** | Baseline characteristics balanced between groups? | ✓/✗ |
| **13. Primary Outcomes** | Primary endpoint results and effect sizes? | ✓/✗ |
| **14. Adverse Events** | Reported? | ✓/✗ |
| **15. Conflicts of Interest** | Disclosed? | ✓/✗ |

#### Cochrane RoB 2.0 Bias Risk Assessment

Assess each domain as: **Low risk / Some concerns / High risk**

1. **Bias arising from the randomization process**
   - Was allocation sequence truly random?
   - Was allocation concealment adequate?
   - Were there important baseline differences?

2. **Bias due to deviations from intended interventions**
   - Were participants and personnel aware of assignments?
   - Were there deviations related to outcomes?
   - Was appropriate analysis used (ITT)?

3. **Bias due to missing outcome data**
   - Was there much missing data?
   - Were reasons for missing data related to true outcomes?
   - Could missing data affect results?

4. **Bias in measurement of outcomes**
   - Was outcome measurement method appropriate?
   - Were assessors blinded?
   - Was measurement influenced by knowledge of intervention?

5. **Bias in selection of reported results**
   - Were results reported according to prespecified plan?
   - Was result selection based on multiple measurements/analyses?

**Overall Bias Risk**:
- **Low risk**: All domains are low risk
- **Some concerns**: At least one domain has concerns but no high risk
- **High risk**: At least one domain is high risk, or multiple domains have concerns

### 3.2 Systematic Review & Meta-analysis

**When to Use**: Evaluating synthesized evidence from multiple studies

**Appraisal Tools**: PRISMA Checklist + AMSTAR 2

#### PRISMA 2020 Core Checklist

**Part 1: Title, Abstract, Introduction**
- [ ] Title identified as systematic review
- [ ] Abstract structured format
- [ ] Background explains rationale

**Part 2: Methods**
- [ ] Eligibility criteria: Clear PICO
- [ ] Information sources: Which databases? Time period?
- [ ] Search strategy: Complete strategy for at least one database
- [ ] Study selection: Who screened? How were disagreements resolved?
- [ ] Data collection: Standardized forms used?
- [ ] Risk of bias assessment: What tools used?
- [ ] Effect measures: What statistics (OR/RR/MD)?
- [ ] Synthesis methods: How was data integrated? Meta-analysis methods?
- [ ] Heterogeneity assessment: How assessed and handled?
- [ ] Publication bias: How assessed?

**Part 3: Results**
- [ ] Study selection: Complete PRISMA flow diagram
- [ ] Study characteristics: Complete characteristics table
- [ ] Risk of bias: Assessed for each study?
- [ ] Results synthesis: Forest plots? Heterogeneity data (I²)?
- [ ] Publication bias: Funnel plots? Statistical tests?

**Part 4: Discussion & Other**
- [ ] Evidence summary: GRADE assessment?
- [ ] Limitations: Study-level and review-level limitations
- [ ] Funding sources and conflicts of interest disclosed

#### AMSTAR 2 (Simplified Quality Assessment)

**Critical Domains** (greatest impact on results):
1. Protocol registered a priori
2. Comprehensive literature search (at least 2 databases)
3. Duplicate independent screening
4. Duplicate independent data extraction
5. Risk of bias assessment
6. Appropriate meta-analysis methods
7. Consider bias risk in result interpretation

**Rating**:
- **High quality**: No or only 1 non-critical weakness
- **Moderate quality**: 1 critical weakness, no non-critical weaknesses
- **Low quality**: 1 critical weakness + non-critical weaknesses
- **Critically low quality**: 2+ critical weaknesses

### 3.3 Observational Studies

#### A. Cohort Study

**When to Use**: Assessing exposure-outcome associations, prognosis

**Appraisal Tool**: Newcastle-Ottawa Scale (NOS) + STROBE

**Newcastle-Ottawa Scale Scoring**:

*Selection (max 4 stars)*
- [ ] Representativeness of exposed cohort (1 star)
- [ ] Selection of non-exposed cohort (1 star)
- [ ] Ascertainment of exposure (1 star)
- [ ] Outcome not present at start (1 star)

*Comparability (max 2 stars)*
- [ ] Comparability of cohorts (main confounders) (1 star)
- [ ] Additional factor control (1 star)

*Outcome (max 3 stars)*
- [ ] Outcome assessment (1 star)
- [ ] Follow-up duration sufficient (1 star)
- [ ] Adequacy of follow-up (1 star)

**Scoring**: ≥7 stars = high quality; 5-6 stars = moderate; ≤4 stars = low quality

**Key Questions**:
1. Are there unmeasured confounders?
2. Is loss to follow-up high (>20%)?
3. Is temporal relationship clear (exposure→outcome)?

#### B. Case-Control Study

**When to Use**: Studying risk factors for rare diseases

**Appraisal Tool**: Newcastle-Ottawa Scale (Case-Control version)

*Selection (max 4 stars)*
- [ ] Case definition adequate (1 star)
- [ ] Representativeness of cases (1 star)
- [ ] Control selection (1 star)
- [ ] Control definition (1 star)

*Comparability (max 2 stars)*
- [ ] Comparability of cases and controls (2 stars)

*Exposure (max 3 stars)*
- [ ] Exposure ascertainment (1 star)
- [ ] Same method for cases and controls (1 star)
- [ ] Non-response rate (1 star)

**Special Attention to Biases**:
- **Selection bias**: Do controls come from same population?
- **Recall bias**: Do cases remember exposure better?
- **Over-matching**: Were intermediate variables matched?

#### C. Cross-sectional Study

**When to Use**: Prevalence surveys, multifactorial associations

**Assessment Points**:
- Sampling method (random? convenience?)
- Sample representativeness
- Response rate
- Measurement tool validity
- **Limitation**: Cannot determine causality (exposure and outcome measured simultaneously)

### 3.4 Diagnostic Accuracy Studies

**When to Use**: Evaluating diagnostic tool performance

**Appraisal Tool**: QUADAS-2 (Quality Assessment of Diagnostic Accuracy Studies)

#### QUADAS-2 Assessment Domains

**Domain 1: Patient Selection**
- Bias risk: Consecutive or random sample? Case-control design avoided?
- Applicability concerns: Do included patients match question context?

**Domain 2: Index Test**
- Bias risk: Were results interpreted without knowing reference standard? Threshold prespecified?
- Applicability concerns: Was index test execution consistent with clinical context?

**Domain 3: Reference Standard**
- Bias risk: Does reference standard correctly classify target condition? Were results interpreted without knowing index test?
- Applicability concerns: Does reference standard definition match question?

**Domain 4: Flow and Timing**
- Bias risk: Did all patients receive reference standard? Appropriate time interval? All patients included in analysis?

**Assessment**: Low risk / High risk / Unclear

**Diagnostic Metrics Interpretation**:
- Sensitivity: Among diseased, proportion with positive test
- Specificity: Among non-diseased, proportion with negative test
- PPV (Positive Predictive Value): Among positive tests, proportion truly diseased
- NPV (Negative Predictive Value): Among negative tests, proportion truly non-diseased
- LR+ (Positive Likelihood Ratio): >10 substantially increases disease probability
- LR- (Negative Likelihood Ratio): <0.1 substantially decreases disease probability

### 3.5 Prognostic/Prediction Model Studies

**When to Use**: Evaluating prognostic factors or clinical prediction models

**Appraisal Tool**: PROBAST (Prediction model Risk Of Bias ASsessment Tool)

#### PROBAST Assessment Domains

**Domain 1: Participants**
- Appropriate data sources?
- Appropriate inclusion and exclusion criteria?
- Applicability: Do participants match target population?

**Domain 2: Predictors**
- Clear definitions and assessment methods?
- All participants assessed same way?
- Applicability: Do predictor definitions match question?

**Domain 3: Outcome**
- Appropriate outcome definition?
- Was outcome determination independent of predictors (blinding)?
- Applicability: Does outcome definition match question?

**Domain 4: Analysis**
- Sufficient sample size?
- Appropriate handling of missing data?
- Appropriate predictor selection during model development?
- Complete model performance reporting?
- Overfitting addressed?
- External validation performed?

**C-statistic (AUC) Interpretation**:
- 0.9-1.0: Excellent
- 0.8-0.9: Good
- 0.7-0.8: Fair
- 0.6-0.7: Poor
- 0.5-0.6: Failed

**Calibration**: Do predicted probabilities match observed event rates?

### 3.6 Clinical Practice Guidelines

**When to Use**: Evaluating guideline quality

**Appraisal Tool**: AGREE II (Appraisal of Guidelines for Research & Evaluation)

#### AGREE II Six Domains (each item scored 1-7)

**Domain 1: Scope and Purpose**
- Overall objectives clearly described
- Health questions clearly described
- Target population clearly defined

**Domain 2: Stakeholder Involvement**
- Guideline development group includes all relevant professions
- Target population views and preferences considered
- Target users clearly defined

**Domain 3: Rigor of Development** (Most important)
- Systematic methods to search for evidence
- Evidence selection criteria explicit
- Strengths and limitations of evidence clearly described
- Clear link between recommendations and evidence
- External expert review
- Update procedure

**Domain 4: Clarity of Presentation**
- Recommendations specific and unambiguous
- Different management options provided
- Key recommendations easily identifiable

**Domain 5: Applicability**
- Facilitators and barriers to implementation discussed
- Implementation advice/tools provided
- Resource implications considered
- Monitoring/auditing criteria provided

**Domain 6: Editorial Independence**
- Funding body did not influence content
- Conflicts of interest recorded and addressed

**Overall Assessment**:
- Recommend
- Recommend with modifications
- Not recommend

### 3.7 Qualitative Research

**When to Use**: Evaluating patient experiences, attitudes, opinions

**Appraisal Tool**: COREQ (Consolidated criteria for Reporting Qualitative research)

**Key Assessment Dimensions:**
1. **Research Team and Reflexivity**
   - Researcher background and bias stated
   - Relationship with participants

2. **Study Design**
   - Theoretical framework explained
   - Participant selection method
   - Saturation achieved

3. **Analysis and Findings**
   - Data analysis method clear
   - Original data quotes support themes
   - Member checking performed

---

## 4. GRADE Evidence Quality Assessment

All study types should ultimately use GRADE system to assess certainty of evidence:

**Starting Level**:
- RCT: High (⊕⊕⊕⊕)
- Observational study: Low (⊕⊕◯◯)

**Downgrading Factors** (each can decrease 1-2 levels):
1. **Risk of bias**: Serious flaws in study design or execution
2. **Inconsistency**: Large unexplained variability across studies
3. **Indirectness**: PICO doesn't perfectly match question
4. **Imprecision**: Small sample size, wide confidence intervals
5. **Publication bias**: Evidence of small-study effects

**Upgrading Factors** (only for observational studies):
1. Large effect size (RR >2 or <0.5)
2. Dose-response gradient
3. All plausible confounders would reduce effect

**Final Evidence Levels**:
- ⊕⊕⊕⊕ **High**: Very confident true effect close to estimated effect
- ⊕⊕⊕◯ **Moderate**: Moderately confident, true effect likely close to estimated
- ⊕⊕◯◯ **Low**: Limited confidence, true effect may differ substantially
- ⊕◯◯◯ **Very Low**: Little confidence in estimated effect

**Recommendation Strength Link**:
- High evidence level → Usually strong recommendation
- Low evidence level → Usually weak recommendation (but not absolute; must also consider benefit-risk ratio, patient values)

---

## 5. Statistical Methods Analysis

For complex statistical sections:

### Method Identification
- List all statistical methods used
- Provide English and alternative language full names

### Method Selection Rationale
- Why was this method chosen?
- What data types does it suit? (continuous/categorical/time-to-event)
- How did research question influence method selection?

### Statistical Assumptions
- Key assumptions for each method
- Were assumptions tested?
- Consequences of assumption violations

### Results Interpretation Guide
- p-value meaning: Statistical vs clinical significance
- 95% CI interpretation and relationship to minimal clinically important difference
- Effect size clinical meaning (Cohen's d / OR / HR)
- Interaction term interpretation if present

### Alternative Methods Discussion
- Other applicable statistical approaches
- Pros and cons of alternatives
- Why author's choice may (or may not) be optimal

### Common Pitfalls
- Typical interpretation errors clinicians make
- Critical details to watch for

---

## 6. Figure and Table Interpretation

For any figure/table in the paper:

### Basic Information
- Figure/table type identification
- Why this visualization was chosen
- What information type it best conveys

### Axis and Legend Interpretation
- X-axis meaning and units
- Y-axis meaning and units
- Legend interpretation
- Color/symbol/line meanings
- Error bar meaning (SD/SE/95% CI)

### Data Interpretation
- Observable trends
- Between-group differences and statistical significance
- p-value markings and their meaning
- Effect size magnitude and clinical importance

### Special Figure Types

**For Forest Plots:**
- Diamond meaning
- Horizontal line meaning
- Vertical dashed line (typically at 1.0) meaning
- Study weight determination
- Pooled effect size
- Heterogeneity index (I²) and interpretation

**For Kaplan-Meier Curves:**
- Survival curve trajectory
- When curves separate
- Log-rank test p-value
- Median survival times
- Survival rates at specific timepoints (e.g., 5-year)
- Censoring marks and frequency

**For ROC Curves:**
- AUC (area under curve) value
- AUC interpretation for diagnostic value
- Optimal cut-off point location
- Sensitivity and specificity at that cut-off
- Distance from diagonal line meaning

### Potential Issues
- Misleading presentation
- Y-axis manipulation exaggerating differences
- Selective data presentation concerns
- Missing important information (sample sizes, confidence intervals)
- Statistical method appropriateness

---

## 7. Clinical Application Assessment

Evaluate clinical practice impact:

### Evidence-Based Medicine Triangle

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

### PICO Applicability Analysis

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

### Number Needed to Treat (NNT) Calculation

If paper provides sufficient information:
- NNT = [number]
- Interpretation: Need to treat X patients for 1 to benefit
- Number Needed to Harm (NNH) = [number] (if adverse event data available)
- Benefit-harm ratio: NNH/NNT

### Clinical Decision Analysis

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

### Guideline Integration
- Current guideline recommendations
- Consistency between study findings and guidelines
- Is this study sufficient to change guidelines?
- When to wait for more evidence vs early adoption?

### Implementation Plan

If adopting this new treatment:
- Required resources (personnel/equipment/budget)
- Needed training
- How to monitor efficacy and safety
- Documentation and tracking
- When to reassess

### Patient Communication Script

Provide:
- Plain language explanation of new treatment
- How to explain potential benefits (use absolute risk, not relative risk)
- How to explain potential risks
- How to address common patient questions
- Shared decision-making dialogue examples

---

## 8. Practical Workflow

**Step 1: Rapid Screening** (1 minute)
- Check title: Relevant?
- Check abstract: Matches PICO?
- Check journal: Credible?

**Step 2: Design Identification** (2 minutes)
- Use decision tree to determine study type
- Select corresponding appraisal tool

**Step 3: Systematic Appraisal** (15-30 minutes)
- Use checklist to assess each item
- Record key flaws
- Note bias risks

**Step 4: Evidence Integration** (5 minutes)
- GRADE assessment
- Write summary commentary
- Decide whether to change practice

**Step 5: Clinical Translation** (as needed)
- Apply PICO to your patients
- Calculate NNT
- Prepare SDM dialogue

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

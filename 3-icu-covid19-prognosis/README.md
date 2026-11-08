# Project 3: Prognostic Markers in ICU COVID-19 Patients

**Question:** which admission variables are associated with mortality in COVID-19 patients in an intensive care unit?

**Data:** 50 patients (15 deaths) from a Portuguese hospital, with laboratory markers at admission, demographic and clinical variables. Confidential data, not included.

**Methods:** descriptive statistics, outlier and skewness analysis, Shapiro-Wilk, Mann-Whitney, Student's t-test, Fisher's exact test, chi-square test, relative risk and odds ratio, ROC-style cut-off analysis, logistic regression with AIC model selection (α = 5%).

**Main results**
- CRP, ALT and troponin were strongly right-skewed with outliers, so medians were used.
- Patients with other pathologies were significantly older (median 74 vs 62 years, p = 0.039).
- No single marker discriminated mortality significantly; eGFR was the most promising.
- Final logistic model: age + troponin above 20 pg/mL had the lowest AIC (52.16); troponin above 20 was associated with about 4x higher odds of death, controlling for age.

**Limitations:** small sample (15 deaths), a cut-off chosen on the same data used to fit the model, and no external validation. Results are exploratory.

**Software:** R.

**File:** [ReportP3.pdf](ReportP3.pdf) (in Portuguese). Dataset and code not included.

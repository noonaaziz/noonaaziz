# Noon Salih

**Data Scientist. Machine learning and analytics on enterprise-scale data.**

I build models that get used: predictive and unsupervised pipelines that run on a
schedule, feed a decision, and can be defended when somebody asks how they were
validated. Three years at Momenta Analytics operating production ML on Databricks
and Snowflake, built on a statistics degree.

The work I care most about is the part after the model trains: whether the
validation matches how the model will actually be used, what the number would look
like if the split were honest, and which result does not survive a closer look.

---

## Projects

Independent work on public data. Each repository documents the decisions and the
limitations, not only the results.

| | What it demonstrates |
|---|---|
| **[Telecom Subscriber Analytics](https://github.com/noonaaziz/telecom-churn-segmentation)**<br>Churn · Segmentation · CLV · Cross-sell | Four connected models where each output feeds the next. Churn ROC-AUC **0.845**; the default 0.50 threshold replaced with an optimum derived from campaign economics, raising net retention value **52%**. CLV by Kaplan-Meier survival on right-censored tenure, after finding and correcting **immortal-time bias**. |
| **[Prescriber Segmentation & Targeting](https://github.com/noonaaziz/prescriber-segmentation-targeting)**<br>26.8m records | Segment count chosen by **split-half stability** rather than silhouette, which was flat and declined to choose. Adoption model trained on **2023 features against 2024 outcomes**: PR-AUC **0.537** on a 7.7% base rate, top decile reaching **65% of adopters**. The same-year random split that would have scored 0.961 is reported as the counter-example, not the headline. |
| **[Hospital Readmission & Length of Stay](https://github.com/noonaaziz/hospital-readmission-los)**<br>Two targets, two leakage boundaries | 30-day readmission under **patient-grouped** cross-validation, ROC-AUC 0.669 against a 0.604 single-variable baseline. Quantified a leakage boundary in length-of-stay regression: R² **0.102** from admission-time features versus **0.437** once stay-derived columns were admitted, a **4.3× inflation**. A second leakage hypothesis was tested and **refuted**, and the null result reported. |
| **[State-Level Drug Need & Allocation](https://github.com/noonaaziz/drug-need-allocation)**<br>Regression · anomaly detection · optimisation | Expected-utilisation regression treating the **residual as unmet need**; the resulting priority list shares **none of its top five states** with a ranking by raw volume. Budget allocated by **linear programming**, covering +177% more weighted need than an equal split, with an equity-floor curve pricing the cost of funding every state. |

---

## What I work with

**Machine learning:** classification, regression, clustering, survival analysis,
propensity and CLV modelling, anomaly detection, class imbalance, cost-sensitive
thresholds, constrained optimisation

**Validation:** ROC-AUC and PR-AUC, calibration, grouped and out-of-time splits,
permutation importance, decile lift, leakage diagnosis

**Engineering:** Python, SQL, PySpark · Databricks (Unity Catalog, Delta Lake),
Snowflake · ETL pipelines, data lineage, semantic layers, dimensional modelling

**Deep learning & LLM:** TensorFlow/Keras, CNNs and transfer learning ·
text-to-SQL benchmarking, RAG evaluation (nugget benchmarks, LLM-as-judge, NLI
entailment), large-scale batch inference

**Delivery:** Tableau, Power BI, KPI frameworks, executive reporting

---

## Background

**B.Sc. Mathematical Sciences & Informatics** (Statistics and Computer Science),
University of Khartoum. Thesis: monkeypox detection from skin-lesion images with a
custom CNN against four transfer-learning baselines, reaching **96.6% accuracy**
and outperforming four published benchmarks.

Previously Teaching Assistant in Bayesian statistics, regression and design of
experiments at the University of Khartoum.

---

Arabic (native) · English (fluent) · French (intermediate)
[LinkedIn](https://linkedin.com/in/noon-salih) · noon.a.aziz1999@gmail.com

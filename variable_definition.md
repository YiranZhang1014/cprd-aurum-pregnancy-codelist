# Data Dictionary: Variable Definitions and Retrieval Time Windows

This document outlines the definitions, derivation logic, and temporal retrieval windows for the variables included in the study.

**Data Sources:**
* **CPRD:** Clinical Practice Research Datalink (Primary Care)
* **HES-APC:** Hospital Episode Statistics - Admitted Patient Care (Secondary Care)
* **Pregnancy Register:** CPRD Pregnancy Register


---

| Variable | Definition | Retrieval Time Window |
| :--- | :--- | :--- |
| **Maternal age** | As recorded in the Pregnancy Register | - |
| **Parity** | Previous live or still baby after 24 weeks | - |
| **Gestational length** | Calculated by difference in pregnancy start and end dates | - |
| **Height** | Most recent record | 5 years before the pregnancy start to the end of first trimester |
| **Weight** | Most recent record | 5 years before the pregnancy start to the end of first trimester |
| **BMI** | Last record in the time windows if non-missing.<br>Calculated using height and weight if missing. | 5 years before the pregnancy start to the end of first trimester (implied) |
| **Diastolic blood pressure** | Most recent record | 1 year before the pregnancy start to the end of first trimester |
| **Systolic blood pressure** (mmHg) | Most recent record | 1 year before the pregnancy start to the end of first trimester |
| **Birthweight** (g) | Most recent record | Pregnancy episode |
| **Ethnicity** | Records in HES-APC if non-missing.<br>Most recent record in CPRD if missing in HES-APC.<br>"Unknown" if missing in both HES and CPRD. | - |
| **Baby sex** | Most recent record | Pregnancy episode |
| **Antiphospholipid syndrome** | Most recent record | 5 years before the pregnancy start to the end of first trimester |
| **Assisted conception** | Most recent record | 1 year before the pregnancy start to the end of first trimester |
| **Chronic kidney disease** | Most recent record | 5 years before the pregnancy start to the end of first trimester |
| **Type 1 or Type 2 Diabetes** | Most recent record | 5 years before the pregnancy start to the end of first trimester |
| **Family history of diabetes** | Most recent record | 5 years before the pregnancy start to the end of first trimester |
| **Family history of hypertension** | Most recent record | 5 years before the pregnancy start to the end of first trimester |
| **Family history of pre-eclampsia** | Most recent record | 5 years before the pregnancy start to the end of first trimester |
| **Gestational diabetes** | Most recent record | Pregnancy episode |
| **Gestational hypertension** | Most recent record | Pregnancy episode |
| **Hypertension** | Most recent record | 5 years before the pregnancy start to the end of first trimester |
| **Infertility** | Most recent record | 5 years before the pregnancy start to the end of first trimester |
| **Ovulation induction** | Most recent record | 6 months before the pregnancy start to the end of first trimester |
| **Previous fetal microsomia** | Any records | Any previous pregnancy episode |
| **Previous gestational diabetes** | Any records | Any previous pregnancy episode |
| **Previous gestational hypertension** | Any records | Any previous pregnancy episode |
| **Previous gestational pre-eclampsia** | Any records | Any previous pregnancy episode |
| **Previous pre-eclampsia** | Any records | Any previous pregnancy episode |
| **Previous small for gestational age** | Any records | Any previous pregnancy episode |
| **Previous stillbirth** | Any records | Any previous pregnancy episode |
| **Pre-eclampsia (early onset)** | Last record | 24 – 33 gestational weeks in pregnancy |
| **Pre-eclampsia (late onset)** | Most recent record | 34 gestational weeks - the end of pregnancy |
| **Pre-eclampsia** | Most recent record | Pregnancy episode |
| **Smoking status** | Most recent record | 5 years before the pregnancy start to the end of first trimester |
| **Small for gestational age** | Birthweight < 10th centile | Pregnancy episode |
| **SGA with preterm/serious outcome** | Birthweight < 10th centile AND<br>(birth before 34 gestational weeks OR stillbirth OR neonatal death) | Pregnancy episode |
| **Stillbirth (≥24 weeks)** | Most recent record | 24 gestational weeks - the end of pregnancy |
| **Stillbirth (≥32 weeks)** | Most recent record | 32 gestational weeks - the end of pregnancy |
| **Systemic lupus erythematosus** | Most recent record | 5 years before the pregnancy start to the end of first trimester |
| **Thrombophilia** | Most recent record | 5 years before the pregnancy start to the end of first trimester |
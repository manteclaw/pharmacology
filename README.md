# Drug Interaction and Pharmacology

Clinical pharmacology dataset covering drug interactions, patient prescriptions, vital signs, lab results, and comorbidities for healthcare AI research.

## Dataset Overview

| Property | Value |
|----------|-------|
| **Total Records** | 2,500 |
| **Sample Included** | 100 rows |
| **License** | CC-BY-SA-4.0 |
| **Price (Full)** | $59 |

## Purchase Full Dataset

The complete dataset (2,500 records) is available for purchase:

- **Store:** [https://payhip.com/Manteclaw](https://payhip.com/Manteclaw)
- **Email:** manteclaw@proton.me

## Files

| File | Description |
|------|-------------|
| `sample_data.csv` | 100-row representative sample |
| `metadata.json` | Dataset schema, tags, pricing |
| `notebooks/starter.ipynb` | Jupyter notebook for exploration |

## Sample Preview (first 10 rows)

| id | condition | age | gender | symptoms | vital_signs | lab_results | prescribed_medications | diagnosis_confidence | follow_up_required | severity | comorbidities | allergies | timestamp | data_source | is_synthetic | disclaimer |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| CLIN-000457 | arthritis | 55 | female | ['symptom_b', 'symptom_c', 'symptom_a'] | {'systolic_bp': 125, 'diastolic_bp': 75, 'heart_rate': 81... | {'glucose_mg_dl': 285, 'hba1c_percent': 7.6, 'cholesterol... | ['medication_b', 'medication_a'] | 0.86 | True | severe | ['parkinsons'] | ['none', 'sulfa'] | 2026-08-08T00:01:52.488819+00:00 | synthetic_clinical_scenario | True | This is synthetic data for AI training only. Not for clin... |
| CLIN-000103 | diabetes_type2 | 50 | male | ['fatigue', 'polyuria', 'slow_healing', 'polydipsia'] | {'systolic_bp': 139, 'diastolic_bp': 86, 'heart_rate': 11... | {'glucose_mg_dl': 133, 'hba1c_percent': 9.8, 'cholesterol... | ['empagliflozin', 'sitagliptin'] | 0.95 | False | moderate | [] | ['sulfa', 'latex'] | 2026-08-08T00:01:52.479819+00:00 | synthetic_clinical_scenario | True | This is synthetic data for AI training only. Not for clin... |
| CLIN-001127 | heart_disease | 36 | male | ['shortness_of_breath', 'palpitations', 'fatigue', 'edema... | {'systolic_bp': 141, 'diastolic_bp': 88, 'heart_rate': 59... | {'glucose_mg_dl': 170, 'hba1c_percent': 8.8, 'cholesterol... | ['clopidogrel', 'aspirin'] | 0.78 | True | moderate | ['cancer_prostate', 'arthritis'] | ['latex'] | 2026-08-08T00:01:52.556829+00:00 | synthetic_clinical_scenario | True | This is synthetic data for AI training only. Not for clin... |
| CLIN-001004 | cancer_prostate | 49 | female | ['symptom_c', 'symptom_a', 'symptom_b'] | {'systolic_bp': 138, 'diastolic_bp': 79, 'heart_rate': 65... | {'glucose_mg_dl': 215, 'hba1c_percent': 5.5, 'cholesterol... | ['medication_a', 'medication_b'] | 0.62 | False | severe | ['depression'] | ['none'] | 2026-08-08T00:01:52.521819+00:00 | synthetic_clinical_scenario | True | This is synthetic data for AI training only. Not for clin... |
| CLIN-000915 | copd | 56 | male | ['symptom_b', 'symptom_c'] | {'systolic_bp': 174, 'diastolic_bp': 103, 'heart_rate': 5... | {'glucose_mg_dl': 256, 'hba1c_percent': 8.5, 'cholesterol... | ['medication_b', 'medication_a'] | 0.94 | True | moderate | ['depression', 'sleep_apnea'] | ['penicillin'] | 2026-08-08T00:01:52.518820+00:00 | synthetic_clinical_scenario | True | This is synthetic data for AI training only. Not for clin... |
| CLIN-000572 | parkinsons | 50 | male | ['symptom_b', 'symptom_c', 'symptom_a'] | {'systolic_bp': 161, 'diastolic_bp': 76, 'heart_rate': 73... | {'glucose_mg_dl': 273, 'hba1c_percent': 4.0, 'cholesterol... | ['medication_b', 'medication_a'] | 0.63 | False | moderate | ['parkinsons', 'depression'] | ['penicillin'] | 2026-08-08T00:01:52.491819+00:00 | synthetic_clinical_scenario | True | This is synthetic data for AI training only. Not for clin... |
| CLIN-000420 | anxiety | 72 | other | ['symptom_b', 'symptom_a'] | {'systolic_bp': 131, 'diastolic_bp': 84, 'heart_rate': 58... | {'glucose_mg_dl': 234, 'hba1c_percent': 5.6, 'cholesterol... | ['medication_a', 'medication_b'] | 0.98 | True | severe | ['depression'] | ['latex'] | 2026-08-08T00:01:52.487820+00:00 | synthetic_clinical_scenario | True | This is synthetic data for AI training only. Not for clin... |
| CLIN-002234 | cancer_colorectal | 56 | female | ['symptom_b', 'symptom_c'] | {'systolic_bp': 150, 'diastolic_bp': 73, 'heart_rate': 78... | {'glucose_mg_dl': 212, 'hba1c_percent': 5.2, 'cholesterol... | ['medication_a', 'medication_b'] | 0.71 | True | moderate | ['copd', 'anxiety'] | ['latex'] | 2026-08-08T00:01:52.605346+00:00 | synthetic_clinical_scenario | True | This is synthetic data for AI training only. Not for clin... |
| CLIN-000357 | alzheimers | 26 | other | ['symptom_a', 'symptom_b'] | {'systolic_bp': 100, 'diastolic_bp': 98, 'heart_rate': 95... | {'glucose_mg_dl': 182, 'hba1c_percent': 5.1, 'cholesterol... | ['medication_a', 'medication_b'] | 0.67 | False | critical | [] | ['none'] | 2026-08-08T00:01:52.485820+00:00 | synthetic_clinical_scenario | True | This is synthetic data for AI training only. Not for clin... |
| CLIN-002419 | cancer_prostate | 66 | male | ['symptom_b', 'symptom_c', 'symptom_a'] | {'systolic_bp': 127, 'diastolic_bp': 89, 'heart_rate': 11... | {'glucose_mg_dl': 200, 'hba1c_percent': 5.9, 'cholesterol... | ['medication_a', 'medication_b'] | 0.83 | False | mild | [] | ['latex', 'penicillin'] | 2026-08-08T00:01:52.610350+00:00 | synthetic_clinical_scenario | True | This is synthetic data for AI training only. Not for clin... |

## License

This dataset is licensed under [CC-BY-SA-4.0](https://creativecommons.org/licenses/by-sa/4.0/).

## Citation

```bibtex
@dataset{pharmacology_2026,
  title        = {Drug Interaction and Pharmacology},
  author       = {Manteclaw},
  year         = {2026},
  url          = {https://github.com/manteclaw/pharmacology},
  license      = {CC-BY-SA-4.0},
  note         = {Sample dataset. Full version available at https://payhip.com/Manteclaw},
}
```

---
*Dataset curated by [Manteclaw](https://github.com/manteclaw). For inquiries: manteclaw@proton.me*

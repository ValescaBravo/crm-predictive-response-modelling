# CRM Predictive Modelling — Campaign Response

This project builds a customer-level response model to support prioritised targeting and improve campaign efficiency under budget constraints.

## Business question
Which customers are most likely to respond to a campaign, so marketing can prioritise outreach and maximise ROI?

## Approach (summary)
- **Target:** campaign response (classification)
- **Models:** interpretable baseline (Logistic Regression) + non-linear benchmark (Random Forest)
- **Imbalance handling:** class weighting and evaluation beyond accuracy
- **Evaluation:** ROC-AUC, precision/recall, confusion matrix and threshold considerations
- **Output:** ranked customer scores + insights for targeting strategy

## Key outputs
- **Notebook:** `notebooks/01_predictive_response.ipynb`
- **Full report (HTML):**  
  `https://valescabravo.github.io/reports/predictive_model_report.htm`
- **VBDA InsightLab library (narrative + styling helpers):**  
  `https://github.com/ValescaBravo/vbda-insightlab`

## How to run (local)
```bash
pip install -r requirements.txt
```
jupyter notebook

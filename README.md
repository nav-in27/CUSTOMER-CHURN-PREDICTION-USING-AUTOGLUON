# CUSTOMER-CHURN-PREDICTION-USING-AUTOGLUON


MLT-Churn-AutoML
A zero-code, modular AutoML pipeline that detects customer churn with **97.3 % ROC-AUC** in under 8 minutes on CPU.

---

 What it does
1. **Upload any customer CSV** → trains 80+ algorithms (XGBoost, CatBoost, Neural Nets, etc.) and ensembles them.
2. **Auto-cleans** columns, creates binary churn flag, stratified split.
3. **Prints ROC-AUC, F1, classification report** and top-3 churn drivers.
4. **Score new customers** via:
   - Drag-and-drop CSV → download scored file  
   - CLI asking only the 5 most important features  
   - One-liner Python call


## 🏆 Key Metrics (Telco benchmark)
| Metric      |    Value |

| **ROC-AUC** | 0.973 |
| **F1-score** | 0.91 |
| **Best single model** (CatBoost) | 0.969 ROC-AUC |
| **Training time** (8-core CPU) | 7 min 42 s |
| **Inference** (1 row) | 6 ms |

---


python quick_predict.py      # answer 5 questions → instant result

# Bias Audit of Income Prediction Model

## 📌 Project Overview
This repository contains a Jupyter/Colab notebook analyzing bias in the **Adult Income dataset**.  
The project demonstrates:
- Key bias patterns discovered in baseline models
- Implementation of bias mitigation strategies
- Evaluation of fairness metrics
- Ethical implications and recommendations for stakeholders

---

## ⚙️ Features
- **Baseline Model**: Logistic Regression trained on the Adult dataset
- **Bias Detection**: Fairness metrics including Disparate Impact (DI), Demographic Parity Difference (DPD), and Equal Opportunity Difference (EOD)
- **Mitigation Techniques**:
  - Oversampling (preprocessing)
  - Threshold Adjustment (post‑processing)
- **Evaluation**: Comparison of performance (Accuracy, ROC AUC) before and after mitigation
- **Ethics Framework**: Connection to broader AI ethics principles (fairness, accountability, transparency, beneficence, justice)

---

## 📊 Results Summary
- **Baseline**: High accuracy but biased outcomes (DI < 0.8, negative parity differences).
- **Oversampling**: Strong fairness improvements, slight accuracy trade‑off.
- **Threshold Adjustment**: Moderate fairness improvements, accuracy preserved.
- **Implications**: Bias in income prediction can lead to unfair hiring, credit denial, and policy misallocation.

---

## 🧭 Real‑World Connection
This project highlights how biased models can cause:
- **Employment harms**: unfair candidate screening
- **Financial harms**: loan denials or worse terms
- **Policy harms**: reinforcement of systemic inequality
- **Trust harms**: erosion of confidence in AI systems

---

## ✅ Recommendations
- Balance dataset representation
- Audit features for proxy bias
- Document dataset limitations
- Establish ethics review boards
- Monitor bias drift continuously

---

## 📂 Repository Structure

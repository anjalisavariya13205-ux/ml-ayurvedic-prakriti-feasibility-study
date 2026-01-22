# Machine Learning–Based Feasibility Analysis of Ayurvedic Prakriti Classification

## Overview

This project presents a **research-oriented feasibility study** exploring whether classical machine learning models can effectively classify **Ayurvedic Prakriti types** using psychological and lifestyle indicators. The work evaluates the limits of data-driven approaches when applied to a traditionally holistic and non-reductionist medical system.

The project is designed as an **academic research prototype**, emphasizing methodology, evaluation rigor, and interpretability rather than raw predictive performance.

> 📄 The full research paper is available in the `paper/` directory.

---

## Research Motivation

Ayurvedic Prakriti classification is traditionally determined through expert assessment, incorporating physiological, psychological, and behavioral traits. Translating this complex process into a computational framework presents fundamental challenges.

This study aims to:

* Assess whether **psychological and lifestyle variables alone** contain sufficient signal for Prakriti classification
* Evaluate the **feasibility and limitations** of applying standard ML models in this domain
* Highlight sources of **class overlap and model uncertainty**

---

## Dataset Description

* **Samples:** 500 individuals
* **Features:** Psychological well-being metrics, lifestyle indicators, and human-need variables
* **Target:** Multiclass Prakriti classification
* **Data Type:** Structured, tabular, multivariate

---

## Models Implemented

The following supervised learning models were implemented and evaluated under a consistent experimental setup:

* **Logistic Regression**
* **Support Vector Machine (SVM)**
* **Random Forest Classifier**

Each model was trained using standardized preprocessing and evaluated using identical metrics to ensure fair comparison.

---

## Evaluation Metrics

* Accuracy
* Macro-averaged Precision
* Macro-averaged Recall
* Macro-averaged F1-score

Macro-averaged metrics were used due to the multiclass nature of the problem and potential class imbalance.

---

## Key Findings

* All models achieved **modest performance**, only marginally above chance level
* Significant **class overlap** was observed across predictions
* Psychological and lifestyle indicators alone were found to have **limited discriminative power** for reliable Prakriti identification

These results suggest that Ayurvedic constitution may require **multi-modal or physiological data** for meaningful computational modeling.

---

## Project Structure

```
ml-ayurvedic-prakriti-feasibility-study/
├── notebooks/   # Jupyter notebooks for each ML model
├── results/     # Evaluation outputs (optional summaries)
├── paper/       # Research paper PDF and notes
├── README.md    # Project documentation
```

---

## Research Status

* ✔ Models implemented and evaluated
* ✔ Results analyzed and documented
* ✔ Research paper written
* ⏳ Manuscript not yet published (unpublished academic study)

---

## Disclaimer

This project is intended for **research and educational purposes only** and does not aim to replace traditional Ayurvedic diagnosis or clinical decision-making.

---

## Author

**Anjali Savariya**
BCA (Honors) – Big Data Analytics
Aspiring Data Scientist

---

## Keywords

Machine Learning · Multiclass Classification · Healthcare Analytics · Ayurvedic Informatics · Feasibility Study

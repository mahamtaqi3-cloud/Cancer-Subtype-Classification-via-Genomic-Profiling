# 🧬 Cancer Subtype Classification via Genomic Profiling

A robust machine learning pipeline designed to classify clinical cancer subtypes (BRCA, KIRC, COAD, LUAD, PRAD) using high-dimensional RNA-Seq gene expression data.

---

## 📖 Project Overview

This project addresses the challenge of tumor classification by leveraging transcriptomic profiles from the **TCGA Pan-Cancer dataset**. By utilizing a **Random Forest Classifier**, we demonstrate how computational models can identify complex, non-linear gene expression patterns to distinguish between distinct cancer types with high accuracy. This work serves as a methodological foundation for linking genomic variants to behavioral and clinical phenotypes.

## 🚀 Technical Highlights

* **Dimensionality Management:** Handles high-dimensional data (20,531 features) using automated feature selection and ensemble learning.
* **Data Integrity:** Implements rigorous data cleaning, including missing value imputation, to ensure model robustness.
* **Predictive Modeling:** Deploys a Random Forest architecture optimized for multiclass classification.
* **Explainable AI:** Extracts and ranks "Top Biomarker Genes," providing insights into the molecular drivers of tumor classification.

## 🛠 Tech Stack

| Domain | Tools |
| --- | --- |
| **Language** | Python 3.x |
| **Machine Learning** | `scikit-learn`, `imblearn` |
| **Data Science** | `pandas`, `numpy`, `scipy` |
| **Visualization** | `seaborn`, `matplotlib` |
| **Environment** | Google Colab |

---

## 📊 Key Results

### Model Performance

The model exhibits exceptional predictive accuracy, as evidenced by the confusion matrix below, which shows clear separation between the five tumor subtypes:

### Biomarker Identification

Through feature importance analysis, the model identified a signature set of genes critical for differentiation. Mapping these genes allows for the correlation of specific genomic signatures with clinical cancer phenotypes.

---

## 🔬 How to Run

1. **Clone this repository.**
2. **Upload to Colab:** Import the provided `.ipynb` notebook into Google Colab.
3. **Load Datasets:** Ensure `data.csv` and `labels.csv` are present in your workspace.
4. **Execute:** Run the cells sequentially to reproduce the preprocessing, training, and evaluation phases.

## 🔮 Future Directions

* **Cross-Species Translation:** Mapping human biomarker orthologs to *Drosophila* genomic variants to explore conserved phenotypic drivers.
* **Advanced Architectures:** Transitioning to Deep Neural Networks to capture intricate, latent features in expression datasets.
* **Hyperparameter Optimization:** Implementing `GridSearchCV` to further refine classification precision.

---

# Ethnic Influences on ASD — Applied Machine Learning & Fairness Analysis

An end-to-end machine learning project investigating ethnic disparities in autism spectrum disorder (ASD) diagnosis using advanced modeling, clustering, neural networks, and fairness auditing.

This repository contains structured workflows, analysis notebooks, and modeling pipelines demonstrating real-world applied ML & data science skills, with emphasis on fairness, interpretability, and decision-ready insights.

---

## 🚀 Project Summary

Ethnic biases and disparities in healthcare outcomes are complex and critical to understand for equitable AI systems. This project:

✔ Explores ethnic influences in ASD diagnosis  
✔ Applies clustering and representation learning (K-Means, DBSCAN, Hierarchical, VAE)  
✔ Trains predictive models (GNNs, TabTransformer)  
✔ Audits models using explainable AI (SHAP, LIME)  
✔ Evaluates fairness using demographic parity and equal opportunity

It reflects a robust ML pipeline from **data preprocessing → modeling → evaluation → fairness auditing**, aligning with real industry expectations for ML engineering, fairness, and responsible AI.

---

## 📌 Problem Space

Diagnoses of autism spectrum disorder can vary across demographic groups due to systemic, cultural, and socioeconomic differences. Machine learning offers a scalable way to:

1. Identify patterns and subgroups within heterogeneous populations  
2. Predict outcomes while assessing bias  
3. Audit models for fairness and explainability  
4. Recommend model adjustments to reduce disparity

This project addresses these objectives using structured pipelines designed for clarity, reproducibility, and validation.

---

## 🧠 ML & Technical Methodology

### 🚀 Data Processing & Augmentation
- Expanded raw dataset using oversampling, SMOTE, and noise injection  
- Ensured balanced representation and robust model training  

### 📊 Unsupervised Learning
- Clustering: K-Means, DBSCAN, Hierarchical  
- Variational Autoencoder (VAE) for latent representations  
- Identification of subgroups and latent structure

### 🤝 Supervised Modeling
- **Graph Neural Networks (GNNs)** for relational pattern detection  
- **TabTransformer** for structured tabular data with feature interactions  
- Baseline and advanced model comparisons

### 🧪 Fairness & Explainability
- **SHAP** and **LIME** for model interpretability  
- Fairness metrics: demographic parity, equal opportunity difference  
- Bias audits across ethnic groups

---

## 📁 Repository Structure

Ethnic-influences-on-ASD/
├── data/
│ └── ASD_Adult_Expanded.csv
├── notebooks/
│ ├── clustering_analysis.ipynb
│ ├── GNN_modeling.ipynb
│ ├── TabTransformer_modeling.ipynb
│ └── VAE_analysis.ipynb
├── src/
│ ├── data_processing.py
│ ├── clustering.py
│ ├── modeling.py
│ ├── fairness_audit.py
│ └── explainability_tools.py
├── README.md
└── requirements.txt


---

## 📈 Key Outcomes & Insights

### 🔍 Clustering
- Identified meaningful subgroups across ethnic dimensions
- Latent representation via VAE revealed hidden structure

### 🤖 Predictive Modeling
- GNN and TabTransformer demonstrated improved predictive performance over baselines
- TabTransformer captured feature interactions in structured data

### 🧠 Explainability & Fairness
- SHAP and LIME revealed which features drive model decisions
- Fairness audit indicated disparities across ethnicities
- Recommendations for mitigation strategies provided

---

## 💡 Core ML Engineering Skills Demonstrated

✔ End-to-end pipeline design from raw data to insights  
✔ Feature engineering and augmentation for balanced training  
✔ Advanced modeling (GNNs, Transformer architectures)  
✔ Fairness auditing and interpretability analysis  
✔ Statistical and performance evaluation  
✔ Modular and reusable code structure

---

## 📌 Why This Matters

This project aligns with industry-level expectations for:

### Machine Learning Engineers
- Designing robust, maintainable pipelines
- Integrating model fairness and audit capabilities
- Scalable and reproducible workflows

### Data Scientists
- Interpreting model behavior
- Understanding demographic impact
- Communicating analytic insights with actionable recommendations

This work exemplifies responsible AI practices and ethical modeling in sensitive domains such as healthcare.

---

## 🔮 Future Enhancements

- Deploy as reproducible ML pipelines using Airflow or Prefect  
- Add real-time dashboards for model performance and fairness metrics  
- Expand dataset sources for greater demographic coverage  
- Integrate automated hyperparameter search (Optuna)

---

## 👤 Author

Dhruv Sharma  
Machine Learning Engineer | Data Scientist

GitHub: https://github.com/Dhruvsharma132  
LinkedIn: https://www.linkedin.com/in/dhruv-sharma-4791b723a/

---


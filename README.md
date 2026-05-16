# Multimodal Schizophrenia Relapse Prediction using Behavioral Sensing, Patient Similarity Networks, and NLP

A multimodal AI framework for early schizophrenia relapse prediction using smartphone behavioral sensing, temporal deep learning, graph-based patient similarity modeling, and NLP-based mental health analysis.

---

# 📌 Overview

Early relapse detection in schizophrenia is a major challenge in mental healthcare. Traditional clinical assessments often fail to capture continuous real-world behavioral changes preceding relapse events.

This project proposes a **multimodal machine learning framework** that combines:

- 📱 Smartphone behavioral sensing
- 🧠 Bi-LSTM temporal modeling
- 👥 Patient similarity graph analysis
- 💬 NLP-based mental health understanding using BERT
- 🔀 Multimodal fusion learning

The system leverages passive behavioral signals collected from smartphones along with mental-health-related textual data to predict relapse risk and behavioral instability.

---

# 🚀 Key Features

✔ Smartphone behavioral sensing analysis  
✔ Bi-LSTM temporal sequence modeling  
✔ Personalized patient similarity graph  
✔ Graph-based contextual feature extraction  
✔ NLP mental health understanding using BERT embeddings  
✔ Multimodal fusion framework  
✔ Explainable AI using SHAP  
✔ Cross-validation and ROC-AUC evaluation  
✔ Research-oriented modular architecture  

---

# 🧠 System Architecture

```text
Smartphone Behavioral Signals
        ↓
Feature Engineering
        ↓
Temporal Sequence Generation
        ↓
Bi-LSTM Temporal Modeling
        ↓
Temporal Embeddings
                ↘
                 Multimodal Fusion → Final Prediction
                ↗
Patient Similarity Graph → Graph Features

Mental Health Text Data
        ↓
BERT Embeddings
        ↓
NLP Features
```

---

# 📂 Datasets Used

## 1️⃣ CrossCheck Dataset

Smartphone sensing dataset collected from schizophrenia patients over long-term monitoring.

Behavioral features include:

- Mobility patterns
- Physical activity
- Conversation activity
- Device usage
- Sleep behavior

Dataset Link:  
https://www.kaggle.com/datasets/dartweichen/crosscheck

Dataset Paper:
https://pac.cs.cornell.edu/pubs/Ubicomp2016_Crosscheck.pdf

---

## 2️⃣ Mental Health NLP Dataset

Mental health text dataset containing labeled mental-health-related statements used for NLP analysis.

Dataset Link:  
https://www.kaggle.com/datasets/suchintikasarkar/sentiment-analysis-for-mental-health

---

# 🏗 Methodology

## 🔹 Behavioral Signal Processing

- Data preprocessing and normalization
- Sliding temporal window generation
- Daily behavioral aggregation

## 🔹 Temporal Deep Learning

- Bidirectional LSTM for sequential behavioral modeling
- Temporal embedding extraction

## 🔹 Patient Similarity Modeling

- Behavioral baseline profiling
- Proxy Social Functioning Score (SFS)
- Similarity graph construction
- Graph-based feature extraction

## 🔹 NLP Branch

- Text preprocessing
- BERT embedding generation
- Mental health semantic representation

## 🔹 Multimodal Fusion

Fusion of:
- Temporal embeddings
- Graph features
- NLP embeddings

using ensemble learning techniques.

---

# 📊 Evaluation Metrics

The framework is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Cross-Validation
- SHAP Explainability

---

# 📈 Results

The proposed framework demonstrates strong performance in multimodal relapse prediction by combining:

- temporal behavioral learning,
- personalized graph-based analysis,
- and NLP semantic understanding.

Key findings include:

- Improved performance using multimodal fusion
- Better personalization using patient similarity networks
- Effective temporal pattern learning using Bi-LSTM
- Improved explainability through SHAP analysis

---

# 🛠 Technologies Used

- Python
- TensorFlow / Keras
- Scikit-learn
- Transformers (BERT)
- PyTorch
- SHAP
- NetworkX
- Pandas / NumPy
- Matplotlib

---

# 🔬 Research Contribution

This work proposes a personalized multimodal framework integrating:

- behavioral sensing,
- temporal deep learning,
- graph-based patient similarity,
- and NLP-based mental health analysis

for schizophrenia relapse prediction in real-world settings.

---

# ⭐ Future Improvements

- Graph Neural Networks (GNNs)
- Transformer-based temporal modeling
- Audio emotion analysis
- Video-based behavioral analysis
- Real-time deployment using Streamlit/FastAPI
- Clinical decision support integration

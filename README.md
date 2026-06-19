# fraud-detection-ml

# Projeto de detecção de fraude em cartões de crédito desenvolvido durante o Bootcamp Bradesco - GenAI, Dados & Cyber da DIO em parceria com o Bradesco.

## Objetivo
Desenvolver modelos de Machine Learning para identificar transações fraudulentas em cartões de crédito, considerando o forte desbalanceamento entre as classes.

---

## 📊 Dataset

O projeto utiliza o conjunto de dados **Credit Card Fraud Detection**, disponibilizado pelo TensorFlow.

[Download dataset](https://storage.googleapis.com/download.tensorflow.org/data/creditcard.csv)

Características do dataset:

- 284.807 transações
- 492 fraudes registradas
- Dados altamente desbalanceados
- Variáveis anonimizadas por PCA (V1 a V28)
- Variáveis adicionais:
  - `Time`
  - `Amount`
  - `Class` (0 = Normal, 1 = Fraude)

---

### 🛠 Tecnologias utilizadas
- Python
- Pandas
- NumPy
- Scikit-Learn
- XGBoost
- SHAP
- SMOTE
  
---

### 🔍 Modelos Avaliados
- Logistic Regression
- Random Forest
- XGBoost
- Métricas
- Precision
- Recall
- F1-Score
- ROC-AUC

---

### Resultados

#### Logistic Regression

| Métrica | Classe Fraude |
|----------|----------|
| Precision | 0.84 |
| Recall | 0.66 |
| F1-Score | 0.73 |
| ROC-AUC | 0.93 |

#### Random Forest

| Métrica | Classe Fraude |
|----------|----------|
| Precision | 0.84 |
| Recall | 0.76 |
| F1-Score | 0.79 |

#### XGBoost

| Métrica | Classe Fraude |
|----------|----------|
| Precision | 0.93 |
| Recall | 0.78 |
| F1-Score | 0.85 |

O modelo `XGBoost` apresentou o melhor desempenho para detecção de fraudes.

---

Dataset
- Credit Card Fraud Detection Dataset disponibilizado pelo TensorFlow.

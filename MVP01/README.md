# MVP 01 — Machine Learning & Analytics

## 📌 Objetivo

Este projeto tem como objetivo desenvolver e avaliar modelos de Machine Learning capazes de classificar indivíduos em três categorias:

- Sem Diabetes
- Pré-Diabetes
- Diabetes

utilizando o dataset **CDC Diabetes Health Indicators (BRFSS 2015)**.

---

## 📊 Dataset

**Nome:** CDC Diabetes Health Indicators (BRFSS 2015)

**Fonte:** UCI Machine Learning Repository

https://archive.ics.uci.edu/dataset/891/cdc+diabetes+health+indicators

Características do conjunto de dados:

- 253.680 registros
- 22 variáveis
- Dados relacionados à saúde e hábitos de vida
- Problema de classificação multiclasses

---

## 🧠 Modelos avaliados

Durante o desenvolvimento do MVP foram comparados os seguintes modelos:

- Baseline (DummyClassifier)
- Logistic Regression
- Decision Tree
- Random Forest
- Random Forest (Otimizado)

Também foram realizados experimentos complementares envolvendo:

- Balanceamento das classes
- Classificação binária

---

## 📈 Melhor modelo

O modelo selecionado foi o **Random Forest (Otimizado)**, por apresentar o melhor desempenho geral considerando o F1-Score, principal métrica utilizada devido ao desbalanceamento das classes.

---

## 🛠 Tecnologias utilizadas

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## 📂 Estrutura do projeto

```text
MVP01/
│
├── dataset/
│   └── diabetes_012_health_indicators_BRFSS2015.csv
│
├── MVP01_CDC_Diabetes_Health_Indicators.ipynb
│
└── README.md
```

---

## ▶️ Como executar

1. Abra o notebook no Google Colab.
2. Execute as células em ordem.
3. O dataset será carregado automaticamente a partir do GitHub.
4. Não é necessário realizar upload manual do arquivo CSV.

---

## 👨‍💻 Autor

**João Paulo do Espírito Santo Queiroz**

Especialização em **Machine Learning & Analytics**

**PUC-Rio**

# Previs-o_de_Inten-o_de_Compra_de_Clientes_em_Loja_Web# Previsão da Intenção de Compra Online

## Descrição do Projeto

Este projeto aplica técnicas de análise de dados e machine learning para prever a intenção de compra online de clientes com base em informações demográficas, comportamentais e de consumo.

O objetivo é identificar padrões no comportamento dos consumidores e construir modelos preditivos capazes de estimar a probabilidade de um cliente realizar compras pela internet.

O projeto segue um fluxo completo de ciência de dados, incluindo exploração dos dados, pré-processamento, modelagem preditiva e avaliação de desempenho.

---

## Dataset

O conjunto de dados contém informações sobre clientes, incluindo:

- Dados demográficos (idade, estado civil, escolaridade)
- Informações econômicas (renda)
- Histórico de compras
- Interações com campanhas de marketing
- Frequência de visitas ao site

Essas variáveis são utilizadas para identificar fatores associados à compra online.

---

## Etapas do Projeto

### 1. Análise Exploratória de Dados (EDA)

- análise das distribuições das variáveis
- identificação de valores ausentes
- tratamento de dados inconsistentes
- visualização de padrões e correlações

### 2. Pré-processamento

- tratamento de valores ausentes
- remoção de duplicatas
- criação da variável idade
- codificação de variáveis categóricas
- normalização de variáveis numéricas

### 3. Modelagem Preditiva

Foram treinados diferentes modelos de classificação:

- Logistic Regression
- Random Forest
- Logistic Regression com PCA

### 4. Avaliação dos Modelos

Os modelos foram avaliados utilizando:

- Accuracy
- Precision
- Recall
- F1-score
- AUC-ROC

---

## Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Resultados

A comparação entre os modelos permitiu avaliar diferentes abordagens para previsão da intenção de compra online. Modelos baseados em árvores, como Random Forest, mostraram boa capacidade de capturar relações não lineares entre as variáveis, enquanto a regressão logística forneceu uma base interpretável para análise dos fatores associados à compra.

---

## Possíveis Melhorias

- uso de validação cruzada
- ajuste de hiperparâmetros
- análise de importância das variáveis
- uso de técnicas de interpretabilidade (SHAP)

---

Projeto desenvolvido como estudo de ciência de dados aplicado à análise de comportamento do consumidor e previsão de compras online.

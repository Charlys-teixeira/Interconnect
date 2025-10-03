📌 Sobre o Projeto

Este projeto tem como objetivo prever a rotatividade de clientes (churn) da operadora fictícia Interconnect, utilizando dados contratuais, pessoais e de serviços.

Além da previsão, também foi realizado um agrupamento de clientes (clustering) para auxiliar em estratégias de segmentação e retenção.

🗂️ Estrutura dos Dados

Foram utilizados 4 conjuntos de dados:

personal.csv → informações pessoais dos clientes

contract.csv → tipo e duração do contrato, forma de cobrança, status de churn

internet.csv → serviços de internet contratados

phone.csv → serviços de telefonia contratados

🔎 Etapas do Projeto

Análise Exploratória de Dados (EDA)

Tratamento de valores ausentes

Conversão de tipos de dados

Análise de distribuições e outliers

Estudo de correlações

Pré-processamento

Normalização de variáveis numéricas

Codificação de variáveis categóricas (One-Hot Encoding)

Divisão dos dados em treino e teste com estratificação

Modelagem

Regressão Logística

Random Forest

Gradient Boosting

Avaliação

Accuracy, Precision, Recall, F1-Score

Matriz de confusão

Relatório de classificação

Clusterização (extra)

Redução de dimensionalidade com PCA

Agrupamento de clientes via K-Means

📊 Principais Resultados

O Gradient Boosting apresentou o melhor desempenho no teste.

O modelo é capaz de identificar clientes propensos ao churn, permitindo estratégias de retenção mais eficazes.

A clusterização mostrou padrões de comportamento úteis para campanhas de marketing segmentadas.


🛠️ Tecnologias Utilizadas

Python (pandas, numpy, matplotlib, seaborn)

scikit-learn

PCA & K-Means



# 🏙️ Prevendo Preços de Aluguel de Apartamentos com Machine Learning

Este projeto tem como objetivo **desenvolver um modelo de Machine Learning capaz de prever o preço de aluguel de apartamentos na cidade de São Paulo**, utilizando dados reais do mercado imobiliário.

A solução percorre **todas as etapas de um pipeline de Ciência de Dados**, desde a limpeza e análise exploratória até a modelagem, validação e otimização do modelo final, com foco em aplicação prática e tomada de decisão orientada por dados.

---

## 📊 Fonte dos Dados

Os dados utilizados são públicos e foram obtidos no Kaggle:

- **Dataset:** *Imóveis em São Paulo – Venda / Aluguel – Abril de 2019*
- **Período:** Abril de 2019
- **Volume:** ~13.000 anúncios de apartamentos
- **Origem:** Sites de classificados imobiliários

🔗 Link: https://www.kaggle.com/datasets/argonalyst/sao-paulo-real-estate-sale-rent-april-2019

---

## 🎯 Objetivo do Projeto

Construir e avaliar modelos de **regressão supervisionada** capazes de prever o **valor de aluguel de imóveis residenciais**, considerando características como localização, tamanho, número de cômodos, vagas de garagem, entre outras variáveis relevantes.

---

## 🧠 Técnicas e Bibliotecas Utilizadas

- Limpeza, padronização e **Análise Exploratória de Dados (EDA)**
- Engenharia de atributos e tratamento de variáveis categóricas
- Modelos de regressão supervisionada
- Avaliação com **Cross Validation** e métricas (RMSE, MAE, R²)
- Otimização de hiperparâmetros com **GridSearchCV**
- **Python (Pandas, NumPy)** para manipulação de dados
- **Matplotlib e Seaborn** para visualização
- **Scikit-learn** para modelagem (Regressão Linear, Decision Tree e Random Forest)

---

## 🤖 Modelos Avaliados

- Regressão Linear  
- Decision Tree Regressor  
- Random Forest Regressor  

Os modelos foram comparados utilizando **validação cruzada**, e o **Random Forest Regressor otimizado** apresentou o melhor desempenho e maior capacidade de generalização para o problema proposto.

---

## 📈 Resultados e Aplicação em Negócios

O modelo final demonstrou boa capacidade de prever preços de aluguel com base nas características dos imóveis, evidenciando seu potencial de uso em cenários reais, como:

- Apoio à precificação em imobiliárias  
- Auxílio a proprietários na definição de valores de aluguel  
- Geração de inteligência de mercado imobiliário  
- Automação de análises antes realizadas de forma manual  

O projeto reforça a importância de boas práticas em Machine Learning, como **validação adequada, comparação entre modelos e otimização de hiperparâmetros**, garantindo maior confiabilidade em aplicações reais.

---

## 🏗️ Estrutura do Projeto

```text
prevendo_precos_apartamento_ML/
│
├── base_de_dados/
│   └── sao_paulo_real_estate_april_2019.csv
│
├── analise_de_mercado_imobiliario.ipynb
│
├── requirements.txt
│
└── README.md

---

## 📌 Observações Finais

Este é um projeto pessoal com fins educacionais, desenvolvido com foco em consolidar conhecimentos em Ciência de Dados e Machine Learning, utilizando dados reais e boas práticas de mercado.

---

👤 Autor

Anderson Junior
Projeto desenvolvido para fins de estudo e portfólio em Ciência de Dados.



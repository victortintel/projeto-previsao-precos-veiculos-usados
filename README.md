# Previsão de Preços de Veículos Usados

Este projeto tem como objetivo prever os preços de veículos usados com base em suas características técnicas e de design, utilizando técnicas de Machine Learning.

## 📌 Objetivos
- Desenvolver um modelo preditivo preciso para estimar o preço de veículos usados
- Identificar os fatores que mais influenciam o preço dos veículos
- Fornecer insights valiosos para concessionárias, vendedores e compradores

## 📊 Dados
O dataset utilizado contém informações sobre 205 veículos usados, com 26 características cada, incluindo:
- Especificações técnicas (tamanho do motor, potência, peso, etc.)
- Características de design (tipo de carroceria, número de portas, etc.)
- Informações sobre o sistema de combustível e tração

Fonte dos dados: [Kaggle](https://www.kaggle.com)

## 🛠️ Tecnologias Utilizadas
- Python 3
- Jupyter Notebook
- Bibliotecas:
  - Pandas, NumPy
  - Matplotlib, Seaborn
  - Scikit-learn
  - XGBoost

## 📈 Métricas de Desempenho
O modelo final (Random Forest otimizado) alcançou:
- **R²:** 0.96
- **MAE:** $1.232
- **RMSE:** $1.816

## 🚀 Como Executar
1. Clone o repositório
2. Instale as dependências: `pip install -r requirements.txt`
3. Execute o Jupyter Notebook: `jupyter notebook CarPricePrediction.ipynb`

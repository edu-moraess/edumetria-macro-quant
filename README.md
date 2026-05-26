# Edumetria — Sectorial Macro Quant Model v3.0

Pipeline de Machine Learning e Econometria aplicado à previsão de demanda no atacado de bens de capital (Segmentos: Agrícola e Construção Civil) utilizando dados de 2024.

## 🧠 Inteligência do Modelo
* **Abordagem Quantitativa:** O modelo cruza o histórico de vendas no atacado com indicadores macroeconômicos domésticos estruturais (como Taxa Selic e PIB dos respectivos setores) para prever o comportamento de mercado.
* **Engenharia de Atributos:** Utiliza defasagens temporais ($Lag_1$, $Lag_2$) e médias móveis combinadas para capturar a inércia de curto prazo e os ciclos de crédito antes de aplicar os algoritmos preditivos.

* **Python 3.12**
* **Pandas & NumPy** (Saneamento e Engenharia de Atributos)
* **Statsmodels** (Diagnóstico Estatístico e Regressão OLS)
* **Scikit-Learn** (Algoritmos Regressores & Backtesting Out-of-Sample)
* **Seaborn & Matplotlib** (Visualizações Técnicas)

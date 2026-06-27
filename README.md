# ⚽ Projeto de Ciência de Dados — Previsão de Gols no Futebol

## Sobre o projeto

Este projeto tem como objetivo analisar estatísticas de jogadores de futebol e identificar quais fatores mais influenciam o número de gols marcados. Além da análise exploratória dos dados, foi desenvolvido um modelo de Machine Learning capaz de prever a quantidade de gols com base em características específicas dos jogadores e do contexto analisado.

O trabalho foi desenvolvido como atividade da disciplina de **Introdução à Ciência de Dados**, aplicando conceitos fundamentais de análise de dados, visualização e modelagem preditiva.

---

## Objetivos

* Explorar e entender os dados relacionados ao desempenho de jogadores de futebol.
* Identificar padrões e relações entre variáveis importantes.
* Visualizar tendências através de gráficos.
* Construir modelos de regressão para prever a quantidade de gols.
* Comparar diferentes algoritmos e selecionar o modelo com melhor desempenho.

---

## Etapas do projeto

### 1. Análise Exploratória de Dados (EDA)

Inicialmente foi realizada uma análise da base de dados para compreender:

* Quantidade de registros
* Tipos de variáveis
* Valores ausentes
* Estatísticas descritivas
* Distribuição dos dados

Essa etapa permitiu entender melhor a estrutura do dataset e preparar os dados para modelagem.

---

### 2. Visualização de Dados

Foram criados gráficos para identificar padrões e relações importantes, incluindo:

* Distribuição de gols
* Relação entre experiência e gols
* Comparação entre posições
* Evolução ao longo do tempo
* Correlação entre variáveis

As visualizações ajudaram a destacar fatores com maior impacto no desempenho ofensivo.

---

### 3. Modelagem Preditiva

Após o pré-processamento, os dados foram divididos em treino e teste para treinamento dos modelos.

Modelos avaliados:

* Regressão Linear
* Random Forest Regressor
* Gradient Boosting

O modelo final escolhido foi o **Random Forest Regressor**, por apresentar melhor equilíbrio entre precisão e capacidade de generalização.

---

## Métricas de Avaliação

Para medir a qualidade do modelo foram utilizadas:

* **MAE (Mean Absolute Error)** → erro médio absoluto
* **RMSE (Root Mean Squared Error)** → penaliza erros maiores
* **R² Score** → mede o quanto o modelo explica a variação dos dados

---

## Principais Resultados

A análise mostrou que algumas variáveis possuem grande influência na previsão de gols, como:

* Posição do jogador
* Nível de experiência
* País ou liga de atuação
* Histórico de desempenho

O modelo treinado conseguiu capturar padrões relevantes e gerar previsões consistentes.

---

## Tecnologias Utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Conclusão

Este projeto permitiu aplicar na prática conceitos importantes de Ciência de Dados, desde a análise exploratória até a construção de modelos de Machine Learning. Além de gerar insights relevantes sobre o desempenho no futebol, também demonstrou como técnicas de regressão podem ser utilizadas para previsão em cenários esportivos.


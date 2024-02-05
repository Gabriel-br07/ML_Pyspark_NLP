# ML_Pyspark_NLP
Este repositório contém um projeto de análise de sentimento voltado para avaliações de filmes em português. Utilizando PySpark e XGBoost, realizei a criação e treinamento de um modelo de classificação capaz de distinguir avaliações positivas de negativas.

## Resumo do Projeto:

### Objetivo:
O principal objetivo deste projeto é desenvolver um modelo de análise de sentimento para avaliações de filmes , utilizando ferramentas como PySpark.

### Etapas Principais:

* Análise Exploratória de Dados (EDA): Durante a análise exploratória de dados, utilizei técnicas para entender melhor a natureza do meu conjunto de dados. Uma das abordagens que adotei foi a criação de nuvens de palavras (word clouds) para visualizar as palavras mais frequentes nos textos do meu conjunto de dados. Essa técnica proporcionou uma visão rápida das palavras-chave e temas predominantes.
  
* Pré-processamento de Texto: Realizei etapas como remoção de caracteres especiais, tokenização e remoção de stopwords para preparar os dados para o treinamento do modelo.

* Criação do Modelo: Utilizei o XGBoost via PySpark para criar um modelo de classificação capaz de predizer se uma avaliação é positiva ou negativa.

* Avaliação do Modelo: Avaliei o desempenho do modelo utilizando métricas como acurácia.

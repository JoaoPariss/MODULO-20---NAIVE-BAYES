# MODULO-20---NAIVE-BAYES
# Projeto de Classificação de Score de Crédito com Naive Bayes

## Descrição

Este projeto tem como objetivo aplicar o algoritmo de **Naive Bayes** para prever o **score de crédito** de clientes, utilizando uma base de dados previamente dividida em treino e teste. O foco principal está na análise do desempenho do modelo, avaliando suas métricas e capacidade de generalização.

## Etapas do Projeto

1. **Carregamento e Verificação dos Dados**
   - Leitura das bases `X_treino`, `y_treino`, `X_teste` e `y_teste`.
   - Verificação de consistência entre as dimensões das bases.
   - Confirmação de que a variável `score` está isolada na base `y`.
   - Checagem de balanceamento da base de teste.

2. **Treinamento do Modelo**
   - Aplicação do algoritmo de Naive Bayes nos dados de treino.
   - Avaliação do modelo com as métricas de **acurácia**, **recall** e **matriz de confusão**.

3. **Avaliação na Base de Teste**
   - Aplicação do modelo treinado aos dados de teste.
   - Cálculo das mesmas métricas de desempenho.
   - Comparação entre o desempenho do modelo em treino e teste.

## Resultados

- **Treinamento:**
  - Acurácia: 0,98
  - Recall: 0,98

- **Teste:**
  - Acurácia: 0,975
  - Recall: 0,944
  - Apenas 1 erro de classificação na matriz de confusão

## Conclusão

O modelo de Naive Bayes apresentou ótimo desempenho tanto na base de treino quanto na de teste. A pequena diferença entre os resultados sugere que o modelo generalizou bem, sem overfitting, sendo eficiente para a tarefa de classificação de score de crédito.


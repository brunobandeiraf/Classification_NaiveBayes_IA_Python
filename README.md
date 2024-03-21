# Classification - Naive Bayes

O Naive Bayes é um conjunto de algoritmos de classificação probabilística baseado no Teorema de Bayes, que foi nomeado em homenagem ao estatístico britânico Thomas Bayes. Esses algoritmos são chamados "naive" (ingênuos) porque eles fazem uma suposição simplificadora, que é a independência condicional entre cada par de recursos, dado o valor da variável de classe. Essa suposição simplifica o cálculo das probabilidades, tornando o Naive Bayes um algoritmo eficiente e fácil de implementar.

## Vantagens:
- Simplicidade e facilidade de implementação.
- Eficiência computacional, especialmente em grandes conjuntos de dados.
- Pode ser usado em problemas de classificação binária ou multiclasse.
- Lida bem com dados com muitas dimensões.

## Desvantagens:
- Faz uma suposição forte de independência condicional, que pode ser violada na prática.
- Não lida bem com características correlacionadas.
- Pode ser sensível a valores atípicos.
- A qualidade do modelo pode ser afetada por dados desbalanceados.

## Métricas de Classificação
- Acurácia: é a proporção de instâncias corretamente classificados em relação ao total de instâncias. Apesar de fácil interpretação, pode ser enganosa em conjuntos de dados desbalanceados, pois favorece a classe majoritária. 
- Precisão: A precisão é a razão de instâncias verdadeiramente positivas em relação ao total de instâncias classificdas como positivas. A precisão é importante quando o custo de falsos 

|           | Positivo           | Negativo           |
|-----------|--------------------|--------------------|
| **Positivo**  | Verdadeiro Positivo | Falso Negativo     |
| **Negativo**  | Falso Positivo      | Verdadeiro Negativo|

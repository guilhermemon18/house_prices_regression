# Algoritmos de *Machine Learning* de Regressão no R

## Descrição

Este projeto implementa vários algoritmos de *machine learning* de regressão na linguagem R num *dataset* sobre características de casas e seus respectivos preços, tentando aprender e estimar o preço de casas.

## Pré-processamento

A base de dados estava livre de dados faltantes e inconsistentes, portanto só foram realizados alguns ajustes:

-   Remoção de atributos como ID, data da compra não relevantes para a análise do problema.

## Resultados

Na tabela a seguir são listados os resultados obtidos para cada algoritmo para este *dataset,* utilizando 70% dos dados para treinamento e 30% para teste.

| Algoritmo            | R²    |
|----------------------|-------|
| Regressão Linear     | 0.689 |
| Regressão Polinomial | 0.769 |
| Árvore Decisão       | 0.714 |
| Random Forest        | 0.876 |
| SVR                  | 0.82  |
| Redes Neurais        | 0.862 |

## Código

-   **Linguagem:** R
-   **Bibliotecas:** rpart, caTools, randomForest, miscTools, ggplot2, h2o, e1071

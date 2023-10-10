# DesafioFalhaIndustrial
Identificar se houve ou não falha em cada uma das máquinas de acordo com cada um dos parâmetros gerados.

O modelo foi dividido em 1º: Classificar se houve ou não falha e 2º Qual o tipo de falha caso ocorra.

O maior objetivo foi explorar 4 diferentes formas de balancear os dados usando:
  - RandomUnderSampler
  - ClusterCentroids
  - NearMiss
  - RandomOverSampler (passando o parâmetro shrinkage)

Em seguida, aplicar o KNN para cada um dos balanceamentos, e o melhor usar em outros modelos de classificação para compará-los, no caso Gboost e XGboost.
Também foi usado otimização de hiperparâmetros em cada um dos modelos.


Sugestões de melhoria:
  - Trabalhar melhor as estatísticas.
  - Procurar outro modelo ou ajustar os existentes para substituir o Gboost (que foi o melhor, porém muito demorado).
  - Trabalhar com mais funções e melhorar perfomance. 

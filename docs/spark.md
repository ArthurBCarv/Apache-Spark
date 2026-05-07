# Apache Spark

## O que é Apache Spark
O **Apache Spark** é um motor de processamento distribuído para grandes volumes de dados, com APIs para SQL, ETL, streaming e machine learning.

## Arquitetura (Driver e Executors)
- **Driver**: coordena o plano de execução e controla o SparkSession.
- **Executors**: executam tarefas em paralelo e manipulam partições de dados.

## RDD, DataFrame, Dataset
- **RDD**: abstração distribuída de baixo nível.
- **DataFrame**: estrutura tabular otimizada pelo Spark SQL.
- **Dataset**: API tipada (mais comum em Scala/Java).

## Por que usar Spark para Big Data
- Escalabilidade horizontal.
- Alto desempenho com otimizações internas.
- Ecossistema unificado para múltiplos tipos de workload.

## Casos de uso
- ETL em larga escala.
- Lakehouse analytics.
- Feature engineering para ML.
- Streaming analítico.

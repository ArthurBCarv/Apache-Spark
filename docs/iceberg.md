# Apache Iceberg

## O que é Apache Iceberg
O **Apache Iceberg** é um formato aberto de tabela para data lakes com foco em escalabilidade, interoperabilidade e governança.

## Características principais
- Snapshots e versionamento de metadados.
- Suporte multi-engine.
- DML moderno e evolução de schema.

## ACID transactions
Implementa commits atômicos e leitura consistente baseada em snapshots.

## Time Travel e Snapshots
Permite navegar entre snapshots e consultar estados históricos da tabela.

## Schema Evolution
Evolução segura por IDs de coluna, minimizando impactos de mudanças estruturais.

## Hidden Partitioning
Abstrai detalhes de particionamento para simplificar consultas.

## Comparação com Delta Lake
- **Delta**: integração forte com Spark.
- **Iceberg**: excelente interoperabilidade entre engines.

## Casos de uso
- Lakehouses multi-engine.
- Ambientes com alta necessidade de governança.
- Workloads analíticos com evolução frequente.

# Delta Lake

## O que é Delta Lake
O **Delta Lake** é uma camada transacional para data lakes baseada em Parquet, com histórico de versões e confiabilidade operacional.

## Características principais
- Transações ACID
- Log transacional (`_delta_log`)
- DML completo (`INSERT`, `UPDATE`, `DELETE`, `MERGE`)

## ACID transactions
Garante atomicidade, consistência, isolamento e durabilidade para operações concorrentes em dados analíticos.

## Time Travel
Permite consultar estados anteriores com `versionAsOf` e `timestampAsOf`.

## Schema Evolution
Suporta evolução de esquema de forma controlada e auditável.

## Vantagens sobre Parquet
- Confiabilidade transacional.
- Melhor governança e rastreabilidade.
- Manutenção simplificada de pipelines.

## Casos de uso
- Camadas Silver/Gold.
- CDC e auditoria.
- Tabelas analíticas com correções frequentes.

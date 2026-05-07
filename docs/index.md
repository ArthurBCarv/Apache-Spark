# Projeto Acadêmico: Apache Spark com Delta Lake e Apache Iceberg

## Contextualização
Este projeto acadêmico apresenta um cenário de **engenharia de dados para e-commerce** usando Apache Spark com dois formatos de tabela lakehouse: **Delta Lake** e **Apache Iceberg**.

## Objetivo Acadêmico
- Demonstrar o uso de Spark para processamento distribuído.
- Implementar operações `INSERT`, `UPDATE`, `DELETE` e `SELECT` em Delta e Iceberg.
- Explorar **ACID**, **Time Travel**, **Snapshots** e **Schema Evolution**.
- Comparar abordagens de governança em formatos lakehouse.

## Tecnologias Utilizadas
- Apache Spark (PySpark)
- Delta Lake
- Apache Iceberg
- JupyterLab
- MkDocs + Material
- UV

## Estrutura do Trabalho
1. Preparação do ambiente com UV.
2. Carga do dataset de e-commerce.
3. Execução do notebook `delta_lake.ipynb`.
4. Execução do notebook `iceberg.ipynb`.
5. Consolidação teórica em `docs/`.

## Cenário de E-commerce
O dataset `data/vendas.csv` simula pedidos de 2024 com cliente, produto, categoria, quantidade, valores e status (pendente, pago, cancelado).

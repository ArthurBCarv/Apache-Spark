# Apache Spark: Delta Lake e Apache Iceberg

Projeto de engenharia de Dados, utilizando um cenário ficticio de e-commerce.

## Objetivo acadêmico
- Demonstrar modelagem e manipulação de dados em Delta Lake e Iceberg.
- Aplicar conceitos de ACID e versionamento.
- Comparar práticas de lakehouse.

## Tecnologias utilizadas
- Apache Spark (PySpark)
- Delta Lake
- Apache Iceberg
- JupyterLab
- MkDocs + Material
- UV

## Setup com UV

### Pré-requisitos
- Python 3.10+
- Java (JDK 11+)

### Instalação do UV
```bash
pip install uv
```

### Clone do repositório
```bash
git clone https://github.com/ArthurBCarv/Apache-Spark.git
cd Apache-Spark
```

### Inicialização do ambiente
```bash
uv sync
```

ou
```bash
uv install
```

### Ativação do ambiente
```bash
uv shell
```

## Como executar

### Rodar Jupyter
```bash
uv run jupyter lab
```

### Acessar notebooks
- `notebooks/delta_lake.ipynb`
- `notebooks/iceberg.ipynb`

### Ordem de execução
1. `delta_lake.ipynb`
2. `iceberg.ipynb`

## Estrutura do projeto
```text
Apache-Spark/
├── notebooks/
│   ├── delta_lake.ipynb
│   └── iceberg.ipynb
├── data/
│   └── vendas.csv
├── docs/
│   ├── index.md
│   ├── spark.md
│   ├── delta.md
│   └── iceberg.md
├── pyproject.toml
├── README.md
└── mkdocs.yml
```

## Documentação Web

### Servir localmente
```bash
uv run mkdocs serve
```

### Deploy
```bash
uv run mkdocs gh-deploy
```

## Conceitos principais
- ACID
- Versionamento de tabelas
- Delta Lake vs Apache Iceberg

## Autores e licença
- Autores: Equipe acadêmica do projeto
- Licença: Educacional (ajuste para MIT, Apache-2.0 etc. conforme necessidade)

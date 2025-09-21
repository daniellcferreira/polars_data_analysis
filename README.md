# Polars Data Analysis

![Python](https://img.shields.io/badge/Python-Linguagem-3776AB?style=flat-square&logo=python&logoColor=white)
![Polars](https://img.shields.io/badge/Polars-DataFrame_API-FF4A00?style=flat-square&logo=polars&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Compatibilidade-150458?style=flat-square&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualização-11557c?style=flat-square&logo=plotly&logoColor=white)

## Descrição

Este repositório contém os notebooks e exemplos desenvolvidos durante os estudos de **análise de dados com Polars**.  
O objetivo é explorar as funcionalidades dessa biblioteca de DataFrame moderna e otimizada em Rust, que oferece alto desempenho para manipulação, transformação e análise de grandes volumes de dados.  

Cada aula foi organizada para abordar conceitos importantes, desde a criação de DataFrames até operações mais avançadas, como **joins, pivoteamento, despivoteamento e particionamento de dados**.  

## Funcionalidades

- **Aula 1 – Introdução ao Polars**
  - Criação e manipulação de DataFrames.
  - Operações básicas de seleção e filtragem.

- **Aula 2 – Expressões e Transformações**
  - Conversão de colunas para datetime.
  - Criação de colunas derivadas como "Duração do envio" e "Margem de Lucro".
  - Substituição de valores e categorização de colunas.
  - Análise de pedidos críticos com extração de mês/ano.
  - Criação de histogramas e boxplots.

- **Aula 3 – Joins e Concatenções**
  - Aplicação de diferentes tipos de *joins* (inner, left, outer).
  - Demonstração de produto cartesiano.
  - Concatenação de DataFrames.

- **Aula 4 – Pivoteamento e Despivotamento**
  - Aplicação do método `pivot` para reorganizar dados.
  - Geração de tabelas dinâmicas (região × tipo de item).
  - Visualização gráfica com barras empilhadas.
  - Uso do método `unpivot` para retornar ao formato longo.

- **Aula 5 – Salvamento dos Dados**
  - Exportação de DataFrames em **CSV**.
  - Escrita e leitura em **Parquet**.
  - Particionamento de dados por múltiplas colunas.
  - Leitura com suporte a **Hive Partitioning**

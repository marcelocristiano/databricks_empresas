# Processamento de Dados de Empresas com PySpark e Delta Lake

Este projeto demonstra como processar dados de um arquivo Excel contendo informações de empresas utilizando PySpark, e salvar os resultados em uma tabela Delta Lake utilizando a plataforma Databricks. O arquivo é formatado de forma complexa, não podendo ser lido de forma simples, é executado varias transformações para chegar um schema confiaval.

Os dados contidos no arquivo são dados simulados não representando nenhuma empresa real.

## Pré-requisitos

- [Apache Spark](https://spark.apache.org/)
- [Databricks](https://databricks.com/)
- [openpyxl](https://openpyxl.readthedocs.io/en/stable/)

## Instalação

1. Certifique-se de ter todos os pré-requisitos.
2. Instale a biblioteca `openpyxl` para ler arquivos Excel:

   ```bash
   !pip install openpyxl

# Imagem de representação do aquivo.

<img width="937" alt="image" src="https://github.com/marcelocristiano/empresas/assets/25067628/924afd09-5eb5-4022-9303-2b11e4742eff">

# Imagem da tabela gerada.

<img width="585" alt="image" src="https://github.com/marcelocristiano/empresas/assets/25067628/a1864233-72f4-4ff5-a1c2-be014bf0436c">

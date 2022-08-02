# CheckPoint 5 de Engenharia de Dados da How Bootcamp

## Objetivo
O objetivo do projeto é captar os dados a partir da API do site The Movie DB e gerar um relatório a respeito das animações mais populares,
verificando itens como qual a emissora mais comum, as palavras-chave mais utilizadas.

## Métodos do projeto
- A primeira lambda será acionada e coletará os dados da API https://www.themoviedb.org/documentation/api?language=pt-BR
- Os dados serão armazenados no S3 gerando a camada Bronze do Data Lake
- Em seguida os dados serão tratados e particionados, sendo salvos como parquet gerando assim a camada Silver do Data Lake
- Por fim os dados poderão ser consumidos da camada Gold, utilizando Redshift e ferramentas de BI
- Os dados também poderão ser consultados pelo Athena.
 
## Serviços
Nesse projeto, as soluções AWS abaixo serão utilizadas:
- AWS Lambda
- AWS S3
- AWS Redshift
- Aws Athena
- Power BI | Metabase | Qlik ...

# Análise de Dados de Segurança Pública de Fortaleza

## Descrição

Este projeto tem como objetivo analisar dados de segurança pública de Fortaleza, Ceará, disponibilizados pela SSPDS (Secretaria da Segurança Pública e Defesa Social). O projeto utiliza dados sobre Crimes Violentos Letais Intencionais (CVLI) e Furtos, abrangendo o período de 2009 a 2023.

## Dados

Os dados foram obtidos a partir de arquivos Excel disponibilizados no site da SSPDS. Os arquivos foram baixados, limpos e tratados para análise. O arquivo `dados_tratados.csv` contém os dados tratados e utilizados nas análises.


## Análises Realizadas

O projeto realiza as seguintes análises:

- **Distribuição Temporal:**
  - Crimes Violentos Letais Intencionais e Furtos por ano (2009-2023).
  - Distribuição dos crimes por mês, dia do mês e dia da semana.
  - Análise detalhada da distribuição temporal por tipo de crime (CVLI e Furto).

- **Perfil da Vítima:**
  - Distribuição de crimes com morte por faixa etária.
  - Distribuição de crimes por escolaridade da vítima.
  - Distribuição de crimes por gênero da vítima.
  - Distribuição de crimes por raça da vítima.

- **Distribuição Geográfica:**
  - Distribuição de crimes por Área Integrada de Segurança (AIS).


## Bibliotecas Utilizadas

- pandas
- numpy
- requests
- os
- matplotlib
- seaborn
- plotly

## Como Executar

1. **Clonar o repositório:**
2. **Abrir o notebook `analise_seguranca_publica.ipynb` no Google Colab.**
3. **Executar as células do notebook.**


## Observações

- Certifique-se de ter as bibliotecas listadas acima instaladas em seu ambiente.
- Os dados utilizados estão disponíveis no arquivo `dados_tratados.csv`.
- O notebook `analise_seguranca_publica.ipynb` contém o código completo para a análise dos dados.

## Autores

1. Alison do Santos
2. Marcos Vinícius
3. Samuel de Sousa
4. Elieudo Márcio
5. Antônio Vitor

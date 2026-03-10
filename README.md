# Análise de Evasão de clientes - TelecomX

Este projeto apresenta uma análise exploratória de evasão de clientes (churn) da empresa TelecomX.

## Objetivo
Identificar padrões associados ao cancelamento de clientes, considerando variáveis como:
- tipo de contrato
- tipo de serviço de internet
- método de pagamento
- tempo de permanência
- cobrança mensal e total

## Etapas do projeto
- importação e leitura de dados em JSON
- tratamento de dados aninhados com `json_normalize`
- limpeza e tratamento de valores ausentes
- renomeação de colunas
- análise exploratória dos dados
- construção de gráficos para interpretação dos resultados

## Principais insights
- clientes com contrato month-to-month apresentam maior taxa de churn
- clientes com fibra óptica mostraram maior evasão
- o método de pagamento electronic check apresentou maior percentual de cancelamento

## Tecnologias utilizadas
- Python
- Pandas
- Matplotlib
- Seaborn
- Plotly
- Google Colab

## Arquivos do projeto
- `TelecomX_Analise_Churn.ipynb`: notebook principal
- `TelecomX_tratado.csv`: base tratada
- `imagens/`: gráficos gerados na análise

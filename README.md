# Estratégia de Retenção de Clientes - Alô Telecomunicações

Este repositório contém uma solução completa de Machine Learning para predição de Churn.

## Como Visualizar o Projeto
1. **Análise Interativa:** Para uma exploração completa dos dados, baixe o arquivo `notebooks/relatorio_eda_completo.html` e abra-o no seu navegador.
2. **Notebook Técnico:** O arquivo `notebooks/churn_prediction_poc.ipynb` contém todo o pipeline de dados, desde o saneamento até a escolha do modelo Random Forest.
3. **Execução Direta:** Clique no botão "Open in Colab" no topo do notebook para executar o código em nuvem.

### Instruções de Execução
Para reproduzir a análise:
1. Clone este repositório.
2. Certifique-se de que o dataset `Customer-Churn.csv` está localizado na pasta `/data`.
3. O notebook está configurado para buscar os dados em caminhos relativos, garantindo a execução tanto em ambiente local quanto via Google Colab.

## Insights de Negócio 
* Foi identificado que 47% do churn ocorre nos primeiros 12 meses. O modelo foca em prever o risco antes do primeiro ano de contrato.
* O threshold foi ajustado para **0.35**, garantindo que 70% dos clientes em risco sejam identificados. Em uma operação de setup caro, o custo de prevenir é muito menor que o custo de perder o cliente.

## Requisitos
Para reproduzir este projeto localmente, utilize:
`pip install -r requirements.txt`

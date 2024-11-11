# Análise de Valores da IBOVESPA

Este projeto realiza uma análise dos dados históricos da IBOVESPA, buscando identificar padrões e insights para auxiliar investidores a entenderem melhor o comportamento do índice ao longo do tempo. 

## Objetivo

O objetivo deste projeto é explorar dados históricos da IBOVESPA, aplicando técnicas de análise de dados e visualização, e identificar tendências e variações ao longo do tempo. O projeto também visa construir uma base sólida para modelos de previsão e oferecer uma ferramenta visual de fácil compreensão para o acompanhamento de dados.

## Funcionalidades

- **Importação e Limpeza de Dados**: Obtenção de dados históricos da IBOVESPA, limpeza e tratamento dos dados.
- **Análise Exploratória dos Dados**: Análise de médias, correlação.
- **Visualização**: Gráficos que mostram a evolução do índice, distribuição de preços, variação percentual, entre outros.
- **Previsão**: Implementação de modelos de machine learning para prever a tendência do índice IBOVESPA em intervalos específicos.

## Estrutura do Projeto

- `datasets/`: Contém os dados brutos e processados.
- `0EDA.ipynb`: Notebook Jupyter com a análise exploratória dos dados.
- `1ARIMA.ipynb`: Notebook contendo a implementação do modelo ARIMA
- `2PROPHET`: Notebook contendo a implementação do modelo Prophet.

## Tecnologias Utilizadas

- **Python**
  - Pandas e NumPy para manipulação de dados
  - Matplotlib e Seaborn para visualizações estáticas
  - ARIMA para validação de modelo
  - Prophet para validação de modelo de previsão
  - Scikit-learn avaliação de modelos
- **Jupyter Notebook** para prototipação e exploração de dados

## Considerações
Dados coletados em https://br.investing.com/indices/bovespa-historical-data

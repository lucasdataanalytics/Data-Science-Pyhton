<img src="https://www.divvino.com.br/blog/wp-content/uploads/2021/03/vinho-mais-caro.jpg"
width="750px"/>

# **Análise de Dados** (Vinhos)

Análise do motivo de cancelamento do cartão.

## Requesitos

 - Ter o Jupyter Notebook instalado ou utilizar Google Colab
 - Ter o arquivo winemag-data_first150k.csv

## Bibliotecas Utilizadas:

 - Pandas
 ```bash
  pip install pandas
```
 - Plotly
```bash
  pip install plotly
```
 - Numpay
 ```bash
  pip install numpay
```
 - Matplotlib
 ```bash
  pip install matplotlib
```
 - Seaborn
 ```bash
  pip install seaborn
```


## Descrição dos Dados
O conjunto de dados utilizado contém informações detalhadas sobre vinhos de diferentes países, incluindo:

- **unnamed:** Coluna de índice (removida na análise).
- **country:** País onde o vinho foi feito.
- **description:** Descrição do vinho.
- **designation:** Vinhedo dentro da adega de onde as uvas que fizeram o vinho foram coletadas.
- **points:** Número de pontos que o vinho obteve em sua avaliação (escala a ser investigada).
- **price:** Preço da garrafa de vinho.
- **province:** Província (estado) onde o vinho foi feito.
- **region_1:** Região onde o vinho foi feito.
- **region_2:** Região mais específica dentro de uma vitícola (removida na análise).
- **title:** Nome do vinho analisado, incluindo o ano de fabricação.
- +**variety:** Tipo de uvas utilizadas na fabricação do vinho.
- **winery:** Adega onde o vinho foi feito.

## Análise Realizada

**Análise Exploratória de Dados (EDA)**: Investigação das relações entre país de origem, preço e qualidade do vinho, além da identificação de tipos de uva de maior qualidade.

## Resultados

- **País com Melhor Avaliação:** A Inglaterra obteve as maiores pontuações em qualidade de vinho, apesar de ter um número reduzido de avaliações em comparação a outros países.

- **Relação Preço vs. Qualidade:** Observou-se uma relação positiva entre preço e qualidade, mas com outliers significativos. Alguns vinhos mais caros receberam avaliações mais baixas, sugerindo que o preço nem sempre reflete a qualidade.

- **ipo de Uva e Qualidade:** A uva 'Nebbiolo' se destacou como a que apresenta os vinhos de melhor qualidade, baseada nas avaliações disponíveis.

- **Faixas de Preço:** Os melhores vinhos para cada faixa de preço foram identificados e podem ser consultados nos DataFrames gerados durante a análise.





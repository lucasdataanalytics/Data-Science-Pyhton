# Análise de Investimentos

Este projeto tem como objetivo analisar o desempenho de diferentes ativos financeiros ao longo do tempo. Utilizando dados do Yahoo Finance e do Banco Central do Brasil, calculamos métricas importantes como retorno acumulado, volatilidade e Índice de Sharpe.

### Bibliotecas Utilizadas

- `pandas`: Para manipulação e análise de dados.
- `yfinance`: Para coleta de dados financeiros do Yahoo Finance.
- `bcb`: Para acessar dados do Banco Central do Brasil (SGS e câmbio).
- `numpy`: Para cálculos numéricos.
- `matplotlib`: Para visualização de dados.

### Coleta de Dados
- **Importação das Bibliotecas**: Importação das bibliotecas necessárias para manipulação de dados e coleta de informações financeiras.
- **Coleta da Cotação do Dólar**: Extração da cotação do dólar ao longo do tempo para conversão dos preços dos ativos.
- **Coleta de Dados do Yahoo Finance**: Download das cotações ajustadas de fechamento dos ativos selecionados.

### Tratamento e Limpeza de Dados
- **Ajuste dos Dados**: Remoção de fusos horários e conversão dos preços dos ativos para reais com base na cotação do dólar. Renomeação da coluna de Bitcoin para `BTC-BRL`.
- **Cálculo de Retornos Diários**: Cálculo dos retornos diários dos ativos, removendo valores ausentes.

### Análise Exploratória
- **Importação de Dados de Índices**: Leitura de um arquivo CSV contendo dados de índices adicionais.
- **Coleta do Rendimento do CDI**: Extração do rendimento do CDI para inclusão na análise de desempenho.
- **Consolidação dos Dados**: Junção dos dados de retornos dos ativos, índices e rendimento do CDI em um único DataFrame.

### Modelagem e Predição
- **Cálculo da Volatilidade Histórica**: Cálculo da volatilidade histórica dos ativos, ajustando para uma base anual.
- **Cálculo do Retorno Acumulado**: Cálculo do retorno acumulado dos ativos ao longo do período analisado.
- **Simulação de Investimento**: Simulação do desempenho de um investimento de R$100 em cada ativo ao longo do tempo.
- **Cálculo do Retorno Anualizado**: Cálculo do retorno anualizado com base no retorno acumulado.
- **Cálculo do Índice de Sharpe**: Cálculo do Índice de Sharpe para avaliar a relação risco-retorno dos ativos.
- **Criação da Tabela Final**: Consolidação dos resultados em uma tabela com retorno anualizado, volatilidade e Índice de Sharpe.

### Visualizações
- **Estilização da Tabela**: Aplicação de formatação e estilização à tabela final para facilitar a interpretação dos resultados.
- **Visualização dos Resultados**: Geração de gráficos para demonstrar o desempenho dos investimentos ao longo do tempo.

### Conclusão
- **Resumo dos Insights Obtidos**: A análise fornece uma visão clara do desempenho de diversos ativos financeiros.
- **Sugestões de Próximas Etapas**: Recomenda-se a exploração de análises mais profundas e possíveis modelos preditivos para o desempenho futuro dos ativos.

## Licença
Este projeto está licenciado sob a MIT License.

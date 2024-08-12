<img src="https://www.foregon.com/media/uploads/2018/06/aprenda-a-como-cancelar-o-cartao-de-credito-caixa.jpg"
width="750px"/>

# **Análise de Dados** (Cartão de Crédito)

Análise do motivo de cancelamento do cartão.

## Requesitos

 - Ter o Jupyter Notebook instalado ou utilizar Google Colab
 - Ter o arquivo ClientesBanco.csv 

## Bibliotecas Utilizadas:

 - Pandas
 ```bash
  pip install pandas
```
 - Plotly
```bash
  pip install plotly
```

## Descrição dos Dados
O conjunto de dados utilizado contém informações de mais de 10.000 clientes, incluindo:

- **Idade:** Idade do cliente.
- **Sexo:** Gênero do cliente.
- **Dependentes:** Número de dependentes.
- **Educação:** Nível de educação.
- **Estado Civil:** Estado civil.
- **Faixa Salarial Anual:** Faixa salarial anual do cliente.
- **Categoria do Cartão:** Categoria do cartão de crédito.
- **Meses como Cliente:** Tempo em meses como cliente do banco.
- **Limite de Crédito:** Limite total de crédito do cliente.
- **Taxa de Utilização do Cartão:** Percentual do limite de crédito - utilizado pelo cliente.
- **Número de Produtos Contratados:** Quantidade de produtos bancários adquiridos pelo cliente.
- **Inatividade nos últimos 12 meses:** Número de meses de inatividade.
- **Contatos com o cliente nos últimos 12 meses:** Número de contatos feitos com o cliente.

## Análise Realizada

**Análise Exploratória de Dados (EDA)**: Análise das distribuições e padrões nos dados para identificar características comuns entre clientes que cancelam seus cartões.

## Resultados

- **Transações e Cancelamento:** Clientes que realizaram entre 40 e 60 transações nos últimos 12 meses têm uma maior taxa de cancelamento. Isso pode indicar uma insatisfação com o serviço ou o uso esporádico do cartão antes de decidir pelo cancelamento.

- **Contatos e Cancelamento:** As chances de cancelamento aumentam quanto maior for a quantidade de contatos realizados com o cliente. Isso sugere que muitos contatos podem ser um indicador de insatisfação ou problemas não resolvidos.

- **Produtos Contratados e Cancelamento:** Quanto maior o número de produtos bancários contratados pelo cliente, menor a chance de cancelamento do cartão. Clientes com mais produtos estão mais engajados e, portanto, menos propensos a cancelar.




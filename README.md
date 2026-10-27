# Análise de Cancelamento de Clientes | Serviço de Internet

Análise exploratória sobre a alta taxa de cancelamento de contratos de uma empresa de serviço de internet, com o objetivo de entender os motivos dos cancelamentos e propor ações para reduzi-los.

## Problema de negócio

A empresa vem perdendo clientes em um ritmo alto. A pergunta que guiou a análise foi: **o que está levando os clientes a cancelar o serviço?

## Base de dados

- Arquivo: `telecom_users.csv`
- Origem: desafio do Kaggle
- 5974 clientes, com 20 colunas

## Ferramentas

- Python
- pandas (tratamento e análise dos dados)
- plotly (gráficos interativos)
- Jupyter Notebook

## Etapas da análise

1. Tratamento de dados: Conversão do tipo de algumas colunas e exclusão de linhas e colunas vazias ou em branco
2. Análise da proporção entre contratos ativos e cancelamentos
3. Gráficos comparando o perfil de quem cancela e de quem permanece

## Principais conclusões

- 1° Clientes que pagam mensalmente tem mais chance de cancelar
- 2° Clientes com pouco tempo de contrato tem mais chance de cancelar
- 3° Pessoas com filhos e casados tem menos chance de cancelar o plano
- 4° Oferecer mais serviços para os clientes
- 5° Verificar a qualidade da fibra
- 6° A forma de pagamento
  
## Sugestões para reduzir os cancelamentos

1° Fazer uma promoção mais agressiva para o plano anual.
2° Primeira experiência com a operadora pode estar causando algum descontentamento com o cliente, 
3° Trazer algum incentivo para manter os clientes, focar em planos para famílias.
4° Planos mais acessíveis com mais serviços.
5° A quantidade de cancelamento por causa da fibra muito alto comparado ao modelo DSL.
6° Podemos oferecer algum desconto com o pagamento em debito automático dando a possibilidade dos clientes migrarem para essa opção.

## Como acessar

O código e os gráficos estão no notebook `Analise de cancelamento internet.ipynb`.

## Autor

Bruno Fogaça
[LinkedIn](link) | [GitHub](https://github.com/Bruno-Fogaca)

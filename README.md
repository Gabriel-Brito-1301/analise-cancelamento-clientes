# Análise de Cancelamento de Clientes

Projeto de estudo em Python, feito seguindo o curso "Python Insights - Analisando Dados com Python".

## O que o projeto faz

O case é de uma empresa com mais de 800 mil clientes, em que a maioria cancelou o serviço. O objetivo é entender os motivos dos cancelamentos e achar o que pode reduzir esse número.

## Etapas

1. Importar a base de dados (pandas)
2. Limpar a base: remover colunas desnecessárias, valores nulos e linhas duplicadas (de 50.000 para 48.527 linhas)
3. Ver quantos clientes cancelaram: cerca de 56% da base
4. Criar um gráfico para cada coluna (plotly) e ver como ela se relaciona com o cancelamento
5. Testar filtros nos perfis de maior risco e ver quanto o cancelamento cai

## O que a análise mostrou

- Clientes com contrato mensal cancelaram em todos os casos
- Clientes com mais de 4 ligações para o callcenter também cancelaram em todos os casos
- Clientes com mais de 20 dias de atraso no pagamento cancelaram
- Tirando esses três perfis, a taxa de cancelamento cai de 56% para cerca de 26%

## Ferramentas

Python, pandas, plotly e Jupyter Notebook (VS Code)

## Observação

Os gráficos do plotly são interativos e não aparecem no GitHub. Para ver tudo, é só baixar o projeto e rodar o notebook.
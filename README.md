Análise de Métricas de Vendas e Clientes
Introdução:
Este projeto tem como objetivo realizar o tratamento e a análise de dados de vendas e clientes de uma loja de varejo. A partir das bases de vendas e clientes fornecidas, serão calculadas diversas métricas que ajudarão a monitorar o desempenho do negócio e a compreender melhor o comportamento dos clientes.

Objetivos:

Identificar os departamentos mais vendidos.
Calcular a média de preço com frete por nome de departamento.
Determinar a quantidade de vendas por mês.
Calcular a média de renda para cada tipo de canal de venda.
Calcular a média de idade de clientes por bandeira.
Premissas
Para compras sem informação do estado (UF), consideraremos o estado do Mato Grosso do Sul (MS).
O preço não pode ser maior que o preço com frete.


Etapas do Projeto

1. Tratamento de Dados
Carregar as bases de vendas e clientes.
Tratar dados ausentes, como o estado (UF) das vendas.
Corrigir erros nos dados, como preços inconsistentes.
Unir as bases de vendas e clientes, utilizando uma chave comum, como o ID do cliente.

2. Análise de Métricas
Departamentos mais vendidos
Agrupar as vendas por departamento.
Calcular a quantidade total de vendas para cada departamento.
Identificar os departamentos com maior volume de vendas.
Média de preço com frete por Nome de Departamento
Calcular o preço total (preço do produto + frete) para cada venda.
Agrupar as vendas por departamento.
Calcular a média de preço com frete para cada departamento.
Quantidade de vendas por Mês
Extrair o mês da data de venda.
Agrupar as vendas por mês.
Contar o número de vendas em cada mês.
Média de renda para cada tipo de canal de venda
Agrupar os clientes por tipo de canal de venda.
Calcular a média de renda para cada tipo de canal.
Média de idade de clientes por bandeira
Agrupar os clientes por bandeira.
Calcular a média de idade para cada bandeira.

3. Resultados e Visualização
Apresentar os resultados obtidos para cada métrica em um formato compreensível, como tabelas ou gráficos.
Interpretar os resultados e fornecer insights relevantes para o negócio.

Tecnologias Utilizadas
Linguagem de programação: Python
Bibliotecas: Pandas, Plotly, Matplotlib (para visualização de dados)

Conclusão:
Este projeto visa fornecer insights valiosos para a loja de varejo, permitindo uma melhor compreensão de seu desempenho de vendas e perfil de clientes. Ao acompanhar as métricas definidas e interpretar os resultados, a loja poderá tomar decisões mais embasadas e eficazes para otimizar seus negócios.

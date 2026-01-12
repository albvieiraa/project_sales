# Análise de Vendas com SQL no Databricks — Dataset Olist

## 📌 Visão Geral do Projeto

Este projeto tem como objetivo realizar uma análise exploratória e analítica de vendas utilizando SQL no Databricks, a partir do dataset público Olist.
O foco está no desenvolvimento de habilidades práticas de SQL, pensamento analítico e organização de um projeto de dados próximo a um cenário real de mercado.

O projeto foi estruturado em etapas progressivas, abordando desde exploração básica até análises com JOINs e geração de insights de negócio.


## 🎯 Objetivos

* Explorar dados de vendas, clientes e produtos
* Construir métricas fundamentais de negócio
* Analisar faturamento sob diferentes perspectivas
* Identificar padrões e concentrações de vendas
* Gerar insights e recomendações para tomada de decisão

## 🧱 Camadas de Dados

O projeto utiliza a camada Bronze, contendo os dados brutos do dataset Olist, incluindo as seguintes tabelas:

`orders`

`customers`

`order_items`

`products`

As análises foram realizadas diretamente sobre essas tabelas, com foco em leitura, agregações e relacionamentos.

## Principais Métricas Calculadas

### Métricas Gerais

- Total de pedidos
- Total de clientes
- Faturamento total
- Ticket médio por pedido

### Análises Avançadas

- Faturamento por status do pedido
- Faturamento por estado do cliente
- Faturamento por categoria de produto
- Identificação de concentração de vendas

## Principais Insights

O faturamento está majoritariamente concentrado em pedidos entregues, indicando que pedidos cancelados ou não entregues têm impacto financeiro direto reduzido, embora possam gerar custos operacionais e impacto na experiência do cliente.

Existe forte concentração de faturamento em poucas categorias de produtos, enquanto a maioria das categorias possui participação marginal na receita total.

O portfólio da plataforma é diversificado, porém a geração de receita depende de um conjunto restrito de categorias líderes.

## Tecnologias Utilizadas

- Databricks
- SQL
- Dataset Olist (dados públicos)

## Conclusão

Este projeto demonstra a aplicação prática de SQL para análise de dados, com foco não apenas na execução de queries, mas também na interpretação dos resultados e geração de insights acionáveis, simulando desafios reais enfrentados por analistas de dados.
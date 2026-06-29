# Analise de Vendas

Projeto desenvolvido como desafio do curso **Fundamentos de Linguagem Python - Do Basico a Aplicacoes de IA**, da **DataScience Academy**.

## Objetivo

O objetivo do projeto e praticar fundamentos de Python aplicados a uma analise exploratoria de vendas, usando dados simulados de pedidos, produtos, clientes, cidades, estados e faturamento.

A analise foi feita em um notebook Jupyter, com foco em:

- criacao de dados simulados;
- manipulacao de dados com pandas;
- calculo de faturamento;
- agrupamentos por produto, mes, estado e categoria;
- visualizacao dos principais resultados com graficos.

## Arquivo principal

- `analise.ipynb`: notebook com toda a geracao dos dados, tratamento, analise e visualizacoes.

## Bibliotecas utilizadas

O projeto utiliza:

- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`
- `random`
- `datetime`

## Estrutura da analise

### 1. Geracao dos dados

O notebook cria uma base simulada de vendas com informacoes como:

- ID do pedido;
- data do pedido;
- produto;
- categoria;
- preco unitario;
- quantidade vendida;
- cliente;
- cidade;
- estado.

### 2. Criacao de novas colunas

Foram criadas colunas auxiliares para enriquecer a analise:

- `Faturamento`: calculado a partir de `Preco_Unitario * Quantidade`;
- `Status_Entrega`: classifica entregas como rapidas ou normais conforme o estado;
- `Mes`: extrai o mes da data do pedido para analise temporal.

### 3. Analises realizadas

O notebook responde perguntas como:

- Quais foram os produtos mais vendidos?
- Como o faturamento evoluiu ao longo dos meses?
- Qual estado gerou mais faturamento?
- Qual categoria teve maior faturamento total?

### 4. Visualizacoes

Foram criados graficos para facilitar a interpretacao dos resultados:

- grafico de barras horizontais para os produtos mais vendidos;
- grafico de linha para evolucao mensal do faturamento;
- grafico de barras para faturamento por estado;
- grafico de barras para faturamento por categoria.

## Como executar

1. Abra o arquivo `analise.ipynb` no Jupyter Notebook, JupyterLab ou VS Code.
2. Execute as celulas em ordem, do inicio ao fim.
3. Os dados serao gerados automaticamente pelo proprio notebook.

Nao e necessario baixar uma base externa, pois os dados sao simulados durante a execucao.

## Observacoes

Este projeto tem finalidade educacional e foi criado para praticar conceitos de Python, pandas e visualizacao de dados em um contexto simples de analise de vendas.

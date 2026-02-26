# Trabalho Prático 1 - O Analista de Dados

Este projeto foi feito para a disciplina **ADS308 - Inteligência Artificial**.
A ideia é pegar um dataset de vendas com problemas e fazer:

- limpeza dos dados;
- tratamento de valores faltantes e outliers;
- análise exploratória com gráficos;
- geração de insights simples para apoiar decisões.

## O que tem no projeto

- `TP1_O_Analista_de_Dados.ipynb`: notebook principal com todo o passo a passo.
- `dataset_vendas_sujo_25994.csv`: base de dados usada no trabalho.

## Links rápidos (GitHub)

- Notebook: https://github.com/Luizguilherme110/Analista-de-Dados/blob/main/TP1_O_Analista_de_Dados.ipynb
- Dataset: https://github.com/Luizguilherme110/Analista-de-Dados/blob/main/dataset_vendas_sujo_25994.csv

## O que o notebook faz (resumo)

1. **Carrega e inspeciona** o dataset.
2. **Mostra informações gerais** (linhas, colunas e tipos de dados).
3. **Trata dados faltantes**:
   - colunas numéricas: preenche com mediana;
   - colunas de texto: preenche com moda (ou "Não informado").
4. **Converte coluna de data** automaticamente (quando encontra coluna com "data" ou "date").
5. **Trata outliers** nas colunas numéricas com regra de Z-Score (3 desvios).
6. **Faz EDA** para responder perguntas como:
   - como as vendas variam por mês;
   - relação entre preço e quantidade vendida;
   - categorias com maior faturamento.

## Tecnologias e bibliotecas

- Python 3
- pandas
- numpy
- matplotlib
- seaborn

## Como executar

1. Abra o arquivo `TP1_O_Analista_de_Dados.ipynb` no VS Code ou Jupyter.
2. Garanta que as bibliotecas estão instaladas no ambiente.
3. Deixe o arquivo `dataset_vendas_sujo_25994.csv` na mesma pasta do notebook.
4. Execute as células em ordem, do início ao fim.

## Como abrir no Google Colab

1. Acesse o notebook direto por este link:
   https://colab.research.google.com/github/Luizguilherme110/Analista-de-Dados/blob/main/TP1_O_Analista_de_Dados.ipynb
2. Faça login na sua conta Google, se necessário.
3. Execute as células em ordem.
4. Se o CSV não estiver carregado, faça upload do arquivo quando o notebook solicitar.

## Observações

- O notebook tenta identificar automaticamente colunas de **data**, **venda**, **quantidade**, **preço** e **categoria**.
- Se alguma coluna não for detectada, basta ajustar manualmente na célula indicada.

## Autor

Luiz Guilherme Gomes Coelho

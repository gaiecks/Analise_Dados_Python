# Análise de Vendas de Supermercado

## Descrição do Projeto

Este projeto visa analisar as vendas de um supermercado em três filiais (A, B e C) ao longo de três meses. A análise foi conduzida para entender o comportamento de compras de clientes masculinos e femininos, além de identificar tendências e padrões de vendas por diferentes linhas de produto em cada filial.

## Estrutura do Projeto

- `Annálise_de_Vendas.ipynb`: O notebook principal que contém todo o código para a análise dos dados.
- `README.md`: Arquivo de documentação do projeto.

## Objetivos

1. Examinar as vendas mensais por linha de produto e filial.
2. Analisar a correlação entre gênero e total de vendas por mês para cada filial.
3. Fornecer insights baseados nos padrões de vendas observados.
4. Demonstrar comandos e ferramentas em Python úteis para análise de dados

## Conclusões Principais

- **Correlação entre Gênero e Total de Vendas:**
  - Filial A: Correlação geral de 0.08, indicando uma leve tendência de vendas maiores para clientes femininos.
  - Filial B: Correlação geral de 0.03, sugerindo uma relação muito fraca entre gênero e total de vendas.
  - Filial C: Correlação geral de 0.04, também sugerindo uma relação fraca.
  - Correlação geral para todas as filiais combinadas: 0.05.

- **Correlação Mensal entre Gênero e Total de Vendas:**
  - Filial A:
    - Mês 1: 0.06
    - Mês 2: 0.04
    - Mês 3: 0.12
  - Filial B:
    - Mês 1: -0.07
    - Mês 2: 0.19
    - Mês 3: -0.03
  - Filial C:
    - Mês 1: 0.06
    - Mês 2: 0.06
    - Mês 3: 0.00

- **Análise de Vendas por Linha de Produto:**
  - Filial A teve um desempenho estável, com destaque para "Home and Lifestyle" e "Sports and Travel".
  - Filial B mostrou consistência nas vendas de "Fashion Accessories" e um aumento notável em "Health and Beauty" no terceiro mês.
  - Filial C apresentou forte desempenho em "Food and Beverages" e "Fashion Accessories".

Esses padrões indicam que há variabilidade na demanda por diferentes linhas de produto entre as filiais, sugerindo a necessidade de estratégias de marketing e estoque personalizadas para cada filial.

1. Clone o repositório para sua máquina local:
    ```sh
    git clone https://github.com/seu-usuario/Analise_Dados_Python.git
    ```
2. Navegue até o diretório do projeto:
    ```sh
    cd Analise_Dados_Python
    ```
3. Abra o notebook `Análise_de_Vendas.ipynb` no Google Colab ou em um ambiente Jupyter Notebook:
    ```sh
    jupyter notebook Análise_de_Vendas.ipynb
    ```
4. Execute as células no notebook para reproduzir a análise e visualizar os resultados.

## Dependências

- Python 3.x
- Pandas
- NumPy
- Matplotlib


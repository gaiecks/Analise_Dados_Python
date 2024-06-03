# Análise de Vendas de Supermercado

## Descrição do Projeto

Este projeto visa realizar uma análise exploratória de dados de vendas de um supermercado em três filiais (A, B e C) ao longo de três meses. A análise foi conduzida para entender o comportamento de compras de clientes masculinos e femininos, além de identificar tendências e padrões de vendas por diferentes linhas de produto em cada filial.
Dataset: https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales/data


## Projeto Completo

Acesse o projeto completo através do link (Analise_Dados_Python)_[https://github.com/gaiecks/Analise_Dados_Python/blob/main/An%C3%A1lise_de_Vendas.ipynb]


## Estrutura do Projeto

- `Annálise_de_Vendas.ipynb`: O notebook principal que contém todo o código para a análise dos dados.
- `README.md`: Arquivo de documentação do projeto.


## Objetivos

1. Examinar as vendas mensais por linha de produto e filial.
2. Analisar a correlação entre gênero e total de vendas por mês para cada filial.
3. Fornecer insights baseados nos padrões de vendas observados.
4. Demonstrar comandos e ferramentas em Python úteis para análise de dados


## Principais Análises Realizadas

### 1. Faturamento por Filial
O faturamento total das três filiais foi analisado e comparado, indicando paridade no faturamento bruto total do período.

- **Filial A**: $106,200.37
- **Filial B**: $106,197.67
- **Filial C**: $110,568.71

### 2. Faturamento por Filial ao Longo dos Meses
Analisamos o faturamento de cada filial ao longo dos três meses.

- No mês 2, todas as filiais apresentaram uma queda no faturamento.
- As filiais A e C conseguiram recuperar boa parte do faturamento em março, enquanto a filial B permaneceu estagnada na queda, indicando uma defasagem em relação ás demais.

### 3. Faturamento por Linha de Produto e por mês
Foi analisado o faturamento de cada linha de produto por filial.

#### Filial A
- A Filial A teve um desempenho estável com flutuações em algumas categorias, sendo "Home and Lifestyle" e "Sports and Travel" as mais destacadas

#### Filial B
- A Filial B apresentou consistência nas vendas de "Fashion Accessories" e um aumento notável em "Health and Beauty" e "Home and lifestyle" no terceiro mês.
- Apesar do crescimento em algumas linhas, apresentou queda constante em outras como "Food and beverages" e "Electronic accessories", o que fez a filial repetir o patamar mais baixo do mês 2 no mês 3.

#### Filial C
- A **Filial C** se destacou nas categorias "Food and Beverages" e "Fashion Accessories" com bom desempenho estável ou crescente ao longo do período.
  
Todas as filiais apresentaram flutuações no desempenho de cada linha de produtos ao longo dos meses. Para verificar os números, basta acessar o arquivo com o código disponibilizado no repositório.

### 4. Faturamento geral por Gênero
Analisamos a paridade de gastos entre os gêneros em diferentes linhas de produto.

- Os gastos com "Health and Beauty" foram maiores no público masculino.
- "Fashion Accessories", "Food and Beverages" e "Home and Lifestyle" tiveram maior expressividade no público feminino.

### 6. Padrão de Consumo por Gênero, Filial e Mês
Observamos o padrão de consumo considerando os gêneros "Male" e "Female" para cada filial ao longo dos meses.

#### Filial A
- Paridade de consumo entre os gêneros com flutuações mensais.

#### Filial B
- Similar à Filial A, com alternância nas flutuações mensais.

#### Filial C
- Maior tendência de gastos do público feminino.

### 7. Análise de Correlação entre Gênero e Total de Gastos
Analisamos a correlação entre o gênero dos clientes e o total de gastos.

- Correlação geral foi de 0.05, indicando uma correlação fraca.
- Correlação por filial:
  - Filial A: 0.08
  - Filial B: 0.03
  - Filial C: 0.04

Também foi realizada a análise de correlações entre gênero e total de gastos por filial e por mês para entender o comportamento ao longo do perído mais detalhadamente. 
Os resultados demonstraram que a análise das correlações entre o gênero do cliente e o total de vendas em cada filial revela padrões de compra variados. A relação entre gênero e vendas é leve e variável. Na Filial A, há uma correlação positiva sutil. A Filial B mostra flutuações, com correlações negativas e positivas ao longo dos meses, sugerindo uma dinâmica de compra distinta. Na Filial C, as correlações são positivas nos dois primeiros meses e próxima a zero no terceiro mês. Esses resultados destacam que é crucial considerar diversos fatores além do gênero ao desenvolver estratégias de vendas e marketing, já que o comportamento do consumidor é complexo e multifacetado.


## Conclusão

As 3 filiais apresentam variações de faturamento em linhas de produto ao longo dos meses, mas através da análise dos dados é possível entender tais variações e elaborar diferentes estratégias tanto para recuperar linhas com quedas em vendas quanto para impulsionar as que já são boas. Os insights relacionados ao padrão de consumo das filiais e suas linhas relacionados ao gênero também podem dar um direcionamento nas estratégias, uma vez que foi possível diagnosticar, ainda que sutilmente, leves tendências relacionadas aos padrões de gastos e preferências de consumo.


## Dependências do projeto

- Python 3.x
- Pandas
- NumPy
- Matplotlib


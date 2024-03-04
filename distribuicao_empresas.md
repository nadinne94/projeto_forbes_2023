# Análise Estatística e Distribuição das Empresas da Lista Forbes

<div align="justify">

## Introdução

Através desta análise exploramos a distribuição das empresas por faixa de valor de mercado, identificando tendências, padrões e parâmetros importantes sobre o cenário empresarial global. Além disso, examinamos a correlação entre o valor de mercado das empresas e outras métricas-chave, bem como sua distribuição geográfica e por setores. Esta análise busca compreender o panorama empresarial atual e quais são as características das empresas com melhor desempenho no mercado.

## Análise da Distribuição das Empresas

### 1. Por País

![Distribuição das Empresas por País](https://github.com/nadinne94/projeto_forbes_2023/assets/129687299/136dd604-d513-4b93-b6d2-4dc3aff65c3c)

O gráfico revela que os Estados Unidos lideram como país de origem, contribuindo com pouco mais de 600 empresas na lista da Forbes. Cerca de 75% das empresas estão distribuídas entre os 10 principais países, todos pertencentes ao Norte Global.

### 2. Por Setor

![Distribuição das Empresas por Setor](https://github.com/nadinne94/projeto_forbes_2023/assets/129687299/3f6e93e5-1b54-40b8-a001-cded0a29036a)

Ao analisarmos os 10 setores com maior número de empresas, observamos que eles abrangem 1820 das 2000 empresas listadas, representando aproximadamente 90% do total. O setor de bancos e finanças se destaca, representando cerca de 30% das empresas.

### 3. Por País e Setor

![Distribuição das Empresas por País e Setor](https://github.com/nadinne94/projeto_forbes_2023/assets/129687299/82b3c683-5e12-49b8-9fac-2ad813a83098)

![Distribuição das Empresas por País e Setor](https://github.com/nadinne94/projeto_forbes_2023/assets/129687299/71d0c05c-74e8-4877-8c82-2aac31d9e712)

Ao considerarmos os países mais significativos, notamos que os Estados Unidos, China e Japão concentram mais de 50% das empresas ranqueadas, totalizando 1104 empresas. Entre os 24 setores, serviços financeiros, indústria, exploração de recursos naturais, tecnologia e farmacêutica se destacam, representando 72% das empresas listadas.

Nos Estados Unidos e no Japão, a maioria das empresas listadas está no setor financeiro, enquanto na Índia, predominam empresas de engenharia e indústria.

## Análise das Métricas das Empresas

### 1. As 10 Maiores Empresas

![As 10 Maiores Empresas](https://github.com/nadinne94/projeto_forbes_2023/assets/129687299/2d549b29-2bfb-4ece-b196-dd1144585871)

Ao analisar as 10 maiores empresas, observamos que 6 delas estão localizadas nos Estados Unidos e 3 na China, o que está em linha com o fato de que esses dois países têm o maior número de empresas listadas.

### 2. Melhor Desempenho em Cada Categoria

- **Vendas (Sales)**

![Melhores Desempenhos em Vendas](https://github.com/nadinne94/projeto_forbes_2023/assets/129687299/b1ee5991-4213-450a-a25f-7853e8ae3b34)

- **Lucro (Profit)**

![Melhores Desempenhos em Lucro](https://github.com/nadinne94/projeto_forbes_2023/assets/129687299/daf4f53e-6a63-4f08-9281-830cc27ba897)

- **Ativos (Assets)**

![Melhores Desempenhos em Ativos](https://github.com/nadinne94/projeto_forbes_2023/assets/129687299/c729da97-a49b-4def-94f6-00b8de6ae942)

- **Valor de Mercado (Market Value)**

![Melhores Desempenhos em Valor de Mercado](https://github.com/nadinne94/projeto_forbes_2023/assets/129687299/01048107-9df4-4ab7-9c0f-d06bdb7933e3)

Observamos que a posição em cada categoria não necessariamente determina a classificação geral. Por exemplo, a JPMorgan Chase, uma empresa do setor financeiro, ocupa o 1º lugar em vendas, mas está em 9º lugar em lucros, 6º em ativos e não está entre as 10 primeiras em valor de mercado. Isso sugere um processo complexo para determinar a classificação geral.

### 3. Faixa de Valor de Mercado

A distribuição das empresas por faixa de valor de mercado revela insights interessantes sobre a concentração de empresas em diferentes intervalos de valor. 

Observamos que cerca de metade das empresas têm um valor de mercado entre 10 e 50 bilhões de dólares. No entanto, apenas 0,4% das empresas têm um valor de mercado acima de 500 bilhões de dólares, indicando a raridade de empresas com valores extremamente altos. Por outro lado, 2,2% das empresas têm um valor de mercado inferior a 1 bilhão de dólares, destacando a presença de empresas de menor porte no mercado.

Essa distribuição ilustra a diversidade no tamanho e na escala das empresas presentes na lista da Forbes, refletindo a complexidade e a dinâmica do cenário empresarial global.

![Distribuição das Empresas por Faixa de Valor de Mercado](https://github.com/nadinne94/projeto_forbes_2023/assets/129687299/fabe7dc6-12b8-4f54-9c0b-0e1c827b8dc8)

### 3. Análise Cruzada das 100 Melhores Empresas em Cada Categoria

![Análise Cruzada das 100 Melhores Empresas](https://github.com/nadinne94/projeto_forbes_2023/assets/129687299/a3f7e81e-6fd0-4706-8bd4-662933ece83b)

Apenas 17 empresas estão presentes entre as 100 melhores classificadas em todas as categorias. Isso indica que essas empresas têm um desempenho excepcional em várias métricas e, consequentemente, ocupam as primeiras posições no ranking geral.

## Análise da Correlação entre as Métricas

Buscamos entender a relação entre as métricas das empresas através de um mapa de calor, tanto para o conjunto de dados completo quanto para as 100 melhores classificadas no ranking geral.

### 1. Mapa de Calor - Conjunto de Dados Completo

![Mapa de Calor - Conjunto de Dados Completo](https://github.com/nadinne94/projeto_forbes_2023/assets/129687299/423f3b5a-6e3b-4797-84fc-99c673f6a3f2)

Observamos no mapa de calor do conjunto de dados completo que algumas métricas apresentam uma correlação mais forte entre si. Por exemplo, as vendas (Sales) e o valor de mercado (Market Value) mostram uma correlação positiva significativa. Por outro lado, o lucro (Profit) parece ter uma correlação mais fraca com outras métricas.

### 2. Mapa de Calor - Top 100 Empresas

![Mapa de Calor - Top 100 Empresas](https://github.com/nadinne94/projeto_forbes_2023/assets/129687299/7d66c9df-bba0-45d0-ac89-45d96786c619)

Ao delimitar a análise para as 100 melhores empresas do ranking geral, observamos uma variação significativa na correlação entre as métricas. As relações que antes indicavam uma correlação mais forte, com valores acima de 0.5, agora apresentam uma correlação ainda mais significativa. Por outro lado, as relações que mostravam uma correlação mais fraca, com valores menores que 0.5, agora parecem ter uma correlação ainda mais distante.

Essas mudanças na correlação sugerem que as empresas de maior destaque no ranking geral podem apresentar relações mais fortes entre suas métricas, o que pode ser um indicativo de um desempenho financeiro mais sólido e consistente.

## Considerações
Observamos uma concentração expressiva de empresas em faixas de valor intermediárias, com uma parcela menor de empresas representando valores extremos. Além disso, identificamos correlações entre o valor de mercado das empresas e outras métricas, como receita, lucro e ativos, destacando a complexidade e interconexão dos fatores que influenciam a avaliação empresarial. 

## 

Parte I: [Análise Exploratória](analise_exploratoria.md)

Parte II: [Tratamento dos Dados](tratamento.md)

Parte III: [Análise Estatística](estatistica.md)

**Parte IV: Outliers](Parte I: [Análise Exploratória](analise_exploratoria.md)

Parte II: [Tratamento dos Dados](tratamento.md)

Parte III: [Análise Estatística](estatistica.md)

**Parte IV: Outliers**

Parte V: [Manipulando os Outliers](manipulacao_outliers.md))

Parte V: [Manipulando os Outliers](manipulacao_outliers.md)

</div>

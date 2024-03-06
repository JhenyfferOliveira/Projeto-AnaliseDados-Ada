# Análise e Visualização de Dados 
Código desenvolvido para limpeza, processamento, análise estatística e visualização de dados com a base de dados [iFood Restaurants Data](https://www.kaggle.com/datasets/ricardotachinardi/ifood-restaurants-data/data) disponível no Kaggle. 

O projeto visou cumprir os requisitos de Técnicas de Programação I, do bootcamp de Ciência de Dados da **Ada Tech**, patrocinado pelo **Potência Tech**, do **iFood**. 

O projeto foi realizado em janeiro de 2024 e contou com a colaboração de 4 integrantes:
* Carlos André
* Jhenyffer Oliveira
* Rodrigo Udenal
* Wallace Souza


# Análise Geral

## Tendências Gerais com base nos gráficos

**1. Top 5 Mais Pedidos e Menos Pedidos:** Com base nas categorias de restaurantes mais populares e menos populares entre os usuários do iFood, pode-se afirmar que as preferências dos consumidores estão entre lanches, comida brasileira e doces; e as categorias menos interessantes são as de comidas típicas.

A preferência dos consumidores por categorias como lanches, comida brasileira e doces sugere que esses tipos de estabelecimentos têm uma demanda consistente e podem atrair um grande número de clientes. Portanto, investir em um restaurante que ofereça esses tipos de alimentos pode representar uma oportunidade promissora de negócio.

Por outro lado, a baixa popularidade das categorias de comidas típicas indica uma demanda potencialmente menor nesse segmento de mercado. Abrir um restaurante especializado em comidas típicas pode ser mais desafiador devido à menor demanda e à concorrência com outras opções de restaurantes mais populares.

**2. Avaliação por Faixa de Preço:** A média de avaliação aumenta com a faixa de preço. Isso indica que os consumidores geralmente estão dispostos a pagar mais por produtos de melhor qualidade.


A maior diferença na média de avaliação está entre as faixas de preço "CHEAPEST" e "CHEAP", o que sugere que os consumidores podem ser mais sensíveis ao preço quando se trata de produtos mais baratos. Já a menor diferença na média de avaliação está entre as faixas de preço "EXPENSIVE" e "MOST_EXPENSIVE", o que pode indicar que os consumidores não percebem uma diferença significativa na qualidade entre produtos de alto preço.


**3. Relação entre Taxa de Entrega e Distância:** A taxa de entrega aumenta com o aumento da distância. Isso indica que os restaurantes geralmente cobram mais para entregar pedidos em locais mais distantes.

A relação entre taxa de entrega e distância é linear. Isso significa que o aumento na taxa de entrega é proporcional ao aumento na distância. Ou seja, a taxa de entrega pode ser um fator importante na decisão do consumidor de pedir comida delivery. Os restaurantes que estão localizados em áreas mais distantes podem ter que oferecer taxas de entrega mais baixas para serem competitivos.


**4. Top 10 Cidades que Mais Consomem iFood:** 7 das 10 cidades estão no Sudeste, o que pode ser explicado pela maior concentração populacional e renda per capita da região. Além disso, 8 das 10 cidades são capitais, demonstrando a centralização do consumo de delivery nas principais cidades do país. A presença de Manaus e Salvador no ranking indica a expansão do iFood para outras regiões do país, com potencial de crescimento futuro.


**5. Preço de Entrega por Estado:** 7 dos 10 estados com os preços de entrega mais altos estão nas regiões Norte e Nordeste, o que pode ser explicado por fatores como menor densidade populacional.

Todos os estados possuem preços de entrega inferiores a R$ 10,00, demonstrando que o iFood está presente em todo o território nacional, mesmo com preços de entrega mais altos em algumas regiões.

## Observações:
+ Os gráficos foram criados com base em dados reais do iFood.
+ As cores dos gráficos foram escolhidas para facilitar a visualização dos dados.
+ Os gráficos estão legendado em português para facilitar a compreensão dos resultados.


# Ferramentas utilizadas

| Python | Pandas | Seaborn | Matplotlib | Git | 
| ------ | ------ | ------- | ---------- | --- | 
| <img src="https://s3.dualstack.us-east-2.amazonaws.com/pythondotorg-assets/media/files/python-logo-only.svg" width="100"> | <img src="https://upload.wikimedia.org/wikipedia/commons/e/ed/Pandas_logo.svg" width="180"> |<img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" width="130"> | <img src="https://upload.wikimedia.org/wikipedia/commons/8/84/Matplotlib_icon.svg" width="110"> | <img src="https://git-scm.com/images/logos/downloads/Git-Icon-1788C.svg" width="100"> |

# Como rodar

> Clique [aqui](https://github.com/JhenyfferOliveira/Projeto-AnaliseDados-Ada/blob/main/projeto_final_modulo_4.ipynb) e veja a limpeza e as visualizações realizadas.

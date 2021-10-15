# Alura Challenge BI

<img src='https://user-images.githubusercontent.com/79534537/137535548-3582fabe-7f01-4976-aeb7-df727cbf3b6d.png' alt='Badge Alura BI' width=300 title='Badge Alura BI'>

Desafios completados do Alura Challenge BI (https://www.alura.com.br/artigos/alura-challenges-bi) de Setembro de 2021.

O Alura challenge BI consiste em uma imersão no mundo do BI com foco em resolver problemas propostos pela equipe da Alura usando ferramentas como Power BI.

## Semana 1
A primeira semana consiste em um Dashboard com informações sobre a operação de uma empresa de Logística fictícia chamada Alura Log.

Abaixo o print da tela principal:

![dashboard-aluralog](https://user-images.githubusercontent.com/4923677/132736751-acbe54ef-277c-4f16-907d-ac87672ba647.PNG)

Indicadores incluídos no Dashboard:
- **Entregas no prazo**: quadro com os pedidos que foram entregues antes ou no mesmo dia da previsão de entrega. O cálculo foi feito usando uma coluna adicional que recebe os valores "No prazo" ou "Atrasada" conforme diferença entre as datas de previsão e de entrega.
- **Entregas atrasadas**: semelhante às entregas no prazo, só que contando as entrefas feitas após o prazo previsto.
- **Veículos disponíveis**: mostra os veículos disponíveis e detalha por tipo de veículo. Calculo feito usando indicadores de veículo disponíveis com as fórmulas de CALCULATE e COUNT filtrando por tipo, quando necessário.
- **Localização dos pedidos**: usando dados disponíveis no dataset de latitude e longitude, plotados no gráfico de mapa, mostra a quantidade de pedidos em cada região do país.
- **Ship to door**: média histórica de dias necessários para entregar o produto desde a data do pedido até a data da entrega.
- **Estoque médio por ano**: mostra a evolução do estoque médio.

## Semana 2
Na segunda semana, o desafio foi analisar os dados com o resultado de uma campanha de anúncios digitais para uma plataforma de ecommerce.

![image](https://user-images.githubusercontent.com/4923677/134990575-b56ef81e-7f9c-4635-966f-f589c9fb78a6.png)

Os arquivos disponibilizados estavam em formato json e continham dados de dispositivos dos usuários e da idade e gênero. Os arquivos também tinham valores de quanto foi gasto na campanha e dos resultados, com diversos indicadores, tudo de forma segmentada a nível de faixa etária e gênero.

Os principais indicadores calculados foram:
- Taxa de Conversão: de todos que visitaram o site, quanto finalizaram uma compra. Uma boa taxa de conversão gira em torno de 1,6%.
- Investimento convertido: gastos em anúncios que trouxeram conversão.
- Valor de conversão: valor dos produtos comprados pelos clientes convertidos.
- ROAS: retorno sobre o investimento = Valor total de conversão / Valor total gasto com anúncios na campanha.
- Ticket Médio. Valor total de conversão / Número de compras.

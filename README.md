# Alura Challenge BI
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


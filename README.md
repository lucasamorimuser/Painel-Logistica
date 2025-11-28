# Dashboard-Logistica

<div style = "display: inline_block"><br>
<img align = "center" height = "800" width = "450" src="https://github.com/lucasamorimuser/icons_images/blob/main/dashboard_logistica_overview.png" /> <img align = "center" height = "800" width = "450" src="https://github.com/lucasamorimuser/icons_images/blob/main/dashboard_logistica_fretes_expedicoes.png" />  
  <img align = "center" height = "800" width = "450" src="https://github.com/lucasamorimuser/icons_images/blob/main/dashboard_logistica_ocorrencias.png" />
</div>

### Linguagem e Ferramentas

Excel - Armazenamento dos dados em arquivo no formato .CSV

Power BI - Ferramenta de elaboração e análise gráfica

### Roteiro

Importação dos dados no formato .CSV

Elaboração do painel:

#### KPIS (página 1)

 - Cartões de quantidade de expedições, On Time in Full (entregas no prazo), On Time Delivery (tempo decorrido entre o pedido e a entrega) e custo médio por km, com gráficos de linha abaixo de cada um dos indicadores.
 - Gráfico de linhas com as expedições por transportadora ao longo do período
 - Gráfico de linhas com On Time in Full por transportadora ao longo do período
 - Gráfico de linhas com On Time in Delivery por transportadora ao longo do período
 - Gráfico de Dunots com a distribuição percentual das expedições por transportadora

#### Análise de Expedições e Frete (página 2)

- Cartões de quantidade de expedições, custo total com frete, On Time Delivery (tempo decorrido entre o pedido e a entrega) e custo médio por km, com gráficos de linha abaixo de cada um dos indicadores.
- Gráfico de linhas com as expedições por estado ao longo do período
- Gráficos de Donuts com a distribuição percentual das expedições por estado
- Gráfico de barras horizontais com o custo médio do frete por estado e transportadora
- Gráfico de barras horizontais com On Time Delivery por estado e transportadora
- Gráfico de barras horizontais com custo por km por transportadora

#### Análise Ocorrências (página 3)

- Cartões de quantidade de ocorrências, índice de atraso, On Time Delivery (tempo decorrido entre o pedido e a entrega) e ocorrências graves, com gráficos de linha abaixo de cada um dos indicadores.
- Gráfico de colunas com ocorrências por estado no período
- Gráfico de Donuts com representação percentual das ocorrências por estado
- Gráfico de barras horizontais com ocorrências por nível de gravidade e por transportadora
- Gráfico de colunas com ocorrências por transportadora no período
- Gráfico de Donuts com representação percentual das ocorrências por transportadora
- Gráfico de barras horizontais com índice de atraso por transportadora

#### Interatividade com o usuário:

- Além dos campos "clicáveis" dos gráficos que funcionam como interface interativa, foram adicionados filtros por datas, estados e transportadoras em todas as páginas.

### Análise dos dados

O estado de São Paulo lidera como destino mais frequente entre os demais, correspondendo a mais de 40% dos envios. Outros indicadores possuem influência direta desse grande volume, como o custo médio no frete e tempo de entrega mais baixos decorrentes da maior concentração de entregas com destino São Paulo, sendo ela mais assistida que as demais.

Em contrapartida, os índices de ocorrência em São Paulo (que correspondem a mais de 80% dos casos) liderando o ranking entre os estados, sendo o único com mais de 10% das entregas com atraso. Esta situação abre oportunidades de atacar diretamente indicadores de atrasos em entregas potencializado pelo alto volume demandado por São Paulo. 

É necessário avaliar pontos da cadeia logística do estado, sondando alternativas como pulverização das entregas, reorganização de rotas, entre outros.

O estado do Espírito Santo tem a menor representação percentual nas entregas, a maior média de custo de frete e ótimos índices de cumprimento de prazo. Existe a oportunidade de expansão dos envios para o Espírito Santo aumentando as expedições para o estado através da empresa VelozTrans que tem bons índices relacionados a prazo e custo. Além de reduzir o custo médio do frete, pode aumentar a participação da empresa nas expedições.

É necessário atuar junto as transportadoras Rápido Sudeste e LogBrasil em função das ocorrências de atrasos. 

A LogBrasil vem de um decréscimo nas ocorrências, porém, possui o custo de frete mais elevado por km, e representação de mais de 35% entre as transportadoras. Cabe avaliar penalidades financeiras nas ocorrências de atraso ou redução no valor do frete de forma geral até que atinja índices melhores. 

A Rápido Sudeste detém a liderança dos fretes realizados com 44% das expedições e números parecidos nas ocorrências. Além disso é a única entre as demais que não apresentou melhora nos índices de conformidade com os prazos. É necessário acionar os representantes da Rápido Sudeste para que atuem neste indicador, caso não haja melhora, pode-se explorar a diversificação dos fretes com a empresa VelozTrans.




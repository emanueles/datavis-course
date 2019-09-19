---
title: 'Tarefa 2'
date: '2019-09-19'
description: Introdução ao Tableau (parte 2)
layout: post
categories: tarefa tableau
---

A data limite dessa tarefa é 23:59h do dia 04/10/2019. **Você deverá compactar todos os arquivos pedidos em um único arquivo zip e enviá-lo pelo SIGAA. Se o arquivo ficar maior que 10MB, coloque-o disponível na nuvem e envie apenas o link no SIGAA.**

O objetivo principal dessa tarefa é certificar-se que você se familiarizou com os conceitos básicos do Tableau e saberá utilizá-lo ao longo da disciplina.

Se você ainda não instalou o Tableau, instale no seu computador, ou utilize alguma das máquinas do LEC I para fazer essa tarefa.

## Parte 1: Dados de Vendas de uma Rede de Cafeterias
O seguinte arquivo csv contém dados fictícios de vendas de produtos de uma cafeteria. Crie uma planilha no Tableau para responder cada uma das perguntas abaixo.

Baixe o arquivo [aqui](https://drive.google.com/open?id=1l4HmiXPQq3yLbOLf4VLgf7jCgbDHkxx0).

### Questão 1.

Reproduza exatamente a visualização abaixo que compara o lucro (profit) com as despesas de marketing para 2013 para os produtos e os tipos de produtos vendidos. O tamanho das marcas é proporcional ao total de vendas.

<center><img src="/datavis-course/assets/images/2019_p1_tarefa2.png" /></center>
 
### Questão 2.

Com base nos dados, crie uma visualização para responder cada uma das perguntas abaixo:

**1. Existe algum indício de sazonalidade nas vendas na cafeteria? Justifique a sua resposta**

**2. Que produtos cujas vendas (sales) não atingiram a meta (budget sales)?**

**3. De modo geral, essa rede vende na mesma proporção em todos os estados onde atua?**  

> Crie anotações nas visualizações com comentários respondendo as perguntas. 

**Exporte o arquivo como Packaged Workbook (possui a extensão .twbx) com o nome parte1.twbx e inclua no arquivo zip a ser submetido. Use uma planilha ou dashboard diferente para cada pergunta dessa parte.**

## Parte 2: Melhore a visualização

O [The World Bank](https://data.worldbank.org/indicator/EN.ATM.CO2E.PC?end=2014&locations=AU-BE-CA-CN-DK-DE-IN-MX-US&start=1960&view=chart) criou a seguinte visualização para mostrar as emissões de gás carbônico per capita de certos países como mostra o screenshot abaixo.

<center><img src="/datavis-course/assets/images/2019_p2_world_bank.png"  /></center>

O que funciona e o que não funciona nessa visualização? Use o seguinte arquivo [csv](https://drive.google.com/open?id=1l3lQzf5yZLO0s-q2fQlgz48AY71k3ksH) para construir outras visualizações que comparam o **Brasil** com outros países. Seja criativo na escolha dos países a serem comparados. Produza um arquivo pdf com a sua crítica ao gráfico original e explicando porque você fez a sua visualização do modo que fez. Nomeie esse arquivo como **parte2.pdf** e inclua no arquivo zip a ser enviado. Não precisa incluir o workbook do Tableau. Não se esqueça de identificar-se no arquivo pdf.  

> **Dica:** Use o menu Planilha > Exportar > Imagem... para gerar os screenshots e inseri-los no documento. 

## Parte 3: Visualização de Dados de Inspeções de Restaurantes de NYC (apenas para a Pós-Graduação).

Você irá criar visualizações usando esse[data set de resultados de inspeções de restaurantes da cidade de Nova Iorque](https://drive.google.com/open?id=1l6Cs8_QNuiRxiOnQlISmD9SA32SQQWpm). Esse data set contém informações sobre como [restaurantes em NYC](https://data.cityofnewyork.us/Health/DOHMH-New-York-City-Restaurant-Inspection-Results/rs6k-p7g6) são avaliados e qual o resultado da inspeção de janeiro de 2016 a setembro de 2019.

Você deve produzir uma apresentação em pdf com as respostas das questões a seguir. Você deve construir os slides da seguinte maneira:

Para cada questão, produza três slides:
* No primeiro você coloca a questão
* No segundo a visualização (exporte a imagem do Tableau)
* E no terceiro uma explicação porque a visualização está correta.

Você pode usar qualquer programa para construir os slides (powerpoint, google slides, etc.) mas lembre-se de converter para pdf antes de incluí-lo no zip a ser enviado pelo SIGAA.

As perguntas que você deverá responder são as seguintes:

**1: Como o número de inspeções muda ao longo do tempo? Aumenta, diminui? Há algum indício de sazonalidade?**

**2. Há alguma diferença no modo como o número de inspeções muda ao longo do tempo entre os 5 diferentes bairros (*boro*) de NYC?**

**3. Como os tipos de culinárias (*cuisines*) estão distribuídos em Nova Iorque? Existem regiões onde certos tipos de culinária tendem a se concentrar (ou seja, áreas onde certas cozinhas são mais prevalentes dos que outras)?**

**4. Como o escore médio se compara entre os diferentes tipos de culinária? Existem tipos de culinária que tendem a ter consistentemente escores médios mais altos/mais baixos quando comparados a outros?**

> **Dica:** Nas questões 3 e 4, foque apenas nas 5 categorias de *"Cuisine Description"* mais frequentes.
 
**5. Existe alguma relação entre tipo de culinária e violação? Por exemplo, alguns tipos de culinária tendem a ter mais de certos tipos de violação do que outras culinárias?**
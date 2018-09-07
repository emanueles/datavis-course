---
title: 'Tarefa 1'
date: '2018-09-06'
description: Introdução ao Tableau
layout: post
categories: tarefa tableau
---

A data limite dessa tarefa é 23:59h do dia 21/09/2017. **Você deverá compactar todos os arquivos pedidos em um único arquivo zip e enviá-lo pelo SIGAA. Se o arquivo ficar maior que 10MB, coloque-o disponível na nuvem e envie apenas o link no SIGAA.**

O objetivo principal dessa tarefa é certificar-se que você se familiarizou com os conceitos básicos do Tableau e saberá utilizá-lo ao longo da disciplina.

Se você ainda não instalou o Tableau, instale no seu computador, ou utilize alguma das máquinas do LEC I para fazer essa tarefa.

## Parte 1: Dados de Vendas de Medicamentos
O seguinte arquivo do Excel contém dados fictícios de vendas de medicamentos. Crie uma planilha no Tableau para responder cada uma das perguntas abaixo.

Baixe o arquivo [aqui](https://drive.google.com/open?id=1n4JOtfxwgpcGWSn-IOoy7vx6UNtuz8cB).

### Questão 1.

Reproduza exatamente a visualização abaixo contendo o preço médio das receitas ao longo do tempo.

<center><img src="/datavis-course/assets/images/tarefa1-q1-p1.gif" /></center>

>Observação: A sua visualização não é para ser animada. A animação é apenas para ilustrar o usuário interagindo com a visualização.

 
### Questão 2.

Reproduza exatamente a visualização abaixo que compara quantidade e o lucro das receitas. As cores das marcas denotam a região (assim como na questão anterior) e suas formas se referem ao fornecedor do medicamento.

<center><img src="/datavis-course/assets/images/tarefa1-q2-p1.png" style="width: 80%;"/></center>


Use a a visualização acima para responder:

**1. Qual médico e fornecedor obtiveram o lucro mais alto em todas as regiões?**

**2. Qual médico e fornecedor obtiveram o lucro mais alto na região leste?** 

> Crie anotações nas visualizações com comentários respondendo as perguntas. 

**Exporte o arquivo como Packaged Workbook (possui a extensão .twbx) com o nome parte1.twbx e inclua no arquivo zip a ser submetido.**

## Parte 2: Crimes em Fortaleza

Em uma das aulas passadas, você aprendeu a fazer uma visualização dos crimes de Fortaleza para o ano de 2012. A visualização no entanto apresenta problemas porque os dados não levam em consideração a população do bairro e normalmente a taxa de homicídios é mostrada em número de homicídios por 100.000 habitantes.

Para essa tarefa, serão disponibilizados os dados de homicídios mês a mês e o mesmo arquivo geojson apresentado em sala ([dados e o geojson](https://drive.google.com/open?id=1nC7dJgJhb_WbdjUT2bdniTum_sBRHgso). Além disso, use o arquivo [Excel](https://drive.google.com/open?id=1nDy_y9zf8GvdtSameDV2qojQzKUn_iTj) para extrair os dados populacionais por bairro. Note que talvez você precise gerar um arquivo manualmente com os dados limpos. Crie um campo calculado com a taxa de homicídios por habitante e use essa informação para gerar o novo mapa. Na visualização, indique os 5 bairros mais perigosos. Crie um dashboard para explorar as informações de homicídios espacialmente e temporalmente.

**Exporte o arquivo como Packaged Workbook (possui a extensão .twbx) com o nome parte2.twbx e inclua no arquivo zip a ser submetido.** 

## Parte 3: Ajude um aluno de mestrado

Um certo aluno de mestrado aparentemente esqueceu de tudo o que aprendeu em Visualização de Dados quando cursou na graduação há alguns anos! Vamos ajudá-lo? Ele está fazendo um levantamento bibliográfico de artigos e para mostrar a distribuição dos Qualis<sup>[1](#qualis)</sup> dos artigos, gerou a seguinte visualização: 


<center><img src="/datavis-course/assets/images/vizfail.png"  /></center>


Quais os problemas dessa visualização? Use o seguinte arquivo [Excel](https://drive.google.com/open?id=1nJGEGDH7IBIa_Kk8P9PlDXmLwLeAF--B) para construir uma visualização melhor (pode incluir mais de um gráfico). Escreva um relatório com as críticas à visualização original e porque você fez a sua visualização do modo que fez. Leve em consideração principalmente a utilização dos atributos pré-atentivos. Nomeie esse arquivo como **parte3.pdf** e inclua no arquivo zip a ser enviado. Não precisa incluir o workbook do Tableau. Não se esqueça de identificar-se no relatório. 

> **Dica:** Use o menu Planilha > Exportar > Imagem... para gerar os screenshots e inseri-los no documento. 


## Parte 4: Visualização de dados do SAEB (apenas para a pós-graduação)

A [Folha de São Paulo](https://www1.folha.uol.com.br/educacao/2018/08/so-9-estados-crescem-em-portugues-e-matematica-no-ensino-medio.shtml) publicou um artigo sobre os resultados do Saeb (Sistema de Avaliação da Educação Básica), divulgados no dia 30 de agosto de 2018. As provas foram realizadas em 2017 e os últimos dados disponíveis eram de 2015.

Elabore uma história no Tableau para comparar os resultados de 2015 e 2017. Os dados oficiais do Saeb podem ser obtidos nesse [link](http://portal.inep.gov.br/web/guest/educacao-basica/saeb/resultados). Use as planilhas por estado e por município. 

Na notícia da Folha, há algumas visualizações não muito adequadas para mostrar essa comparação. Por exemplo, veja a figura abaixo:

<center><img src="/datavis-course/assets/images/folha.gif" /></center>

Ela mostra como a Folha mostrou a mudança de ranking dos estados em relação à prova de Português para o Ensino médio. Se o título da notícia é **Só 9 estados crescem em português e matemática no ensino médio**, essa visualização é mais adequada? De que outra forma você mostraria essas informações? 

Seja criativo e crie visualizações interessantes, fazendo uso de visualizações, mapas, textos e outros elementos aprendidos em sala, tais como filtros, highlights, anotações, etc. 

**Exporte o arquivo como Packaged Workbook (possui a extensão .twbx) com o nome parte4.twbx e inclua esse arquivo no zip a ser enviado.**

---
**Notas**

<a name="qualis">1</a>: O Qualis-Periódicos é um sistema usado para classificar a produção científica dos programas de pós-graduação no que se refere aos artigos publicados em periódicos científicos. A classificação de periódicos é realizada pelas áreas de avaliação e passa por processo anual de atualização. Esses veículos são enquadrados em estratos indicativos da qualidade - A1, o mais elevado; A2; B1; B2; B3; B4; B5; C - com peso zero. Para saber mais sobre o Qualis veja esse [link](https://sucupira.capes.gov.br/sucupira/public/index.jsf).
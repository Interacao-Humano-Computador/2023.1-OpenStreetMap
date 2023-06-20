# Guia de Estilo
## Introdução

Segundo a norma internacional ISO/IEC/IEEE 12207:2017(E) (ISO/IEC/IEEE, 2017, p. 82) [1], o objetivo da verificação se define em "prover evidência objetiva que o sistema ou elemento do sistema atende completamente seus requisitos e características especificados". Com isso, afim de garantir qualidade e consistência dos requisitos, realizaremos a verificação dos documentos do nosso grupo, [OpenStreetMap](https://interacao-humano-computador.github.io/2023.1-OpenStreetMap/)[2], da disciplina de Interação Humano Computador.

## Objetivos
O objetivo deste documento é realizar a verificação do Guia de Estilo, artefato da Entrega 3, do Grupo 4 ([OpenStreetMap](https://requisitos-de-software.github.io/2023.1-Caesb/)). De forma impessoal, este documento não deseja avaliar os membros do grupo, mas o artefato em si.


## Metodologia
Como método de investigação e produção da verificação, utilizaremos a inspeção, mais especificamente a _Fagan Inspection_. Na qual, segundo Bush [3], consiste na "inspeção de documentos entendidos como prontos para uso e busca por defeitos". Seguindo as etapas de planejamento, visão geral, preparação, inspecção e correção. Maiores detalhes de planejamento, estão apresentados no [Planejamento da Entrega 3](./0planejamento.md)

<div id="artefatos"></div>

## Verificações anteriores
 Uma das atividades da disciplina de Interação Humano Computador, ministrada pelo professor André Barros, é realizar a verificação do projeto de outro grupo. A nossa verificação foi feita sobre o Guia de Estilo do grupo 5 ([Alistamento Militar](https://interacao-humano-computador.github.io/2023.1-OpenStreetMap/Verificacao/grupo5/ponto3/))<!--, conforme a figura 1  -->. E o grupo 3 ([Banco Central](https://interacao-humano-computador.github.io/2023.1-BancoCentral/#/verificacao/ponto_controle_3/guia_estilo_g4)), fez a inspeção do nosso projeto (OpenStreeMap)<!--, conforme a Figura 2.  -->

Dessa forma, reavaliamos nosso checklist, levando em conta os pontos levantados pelo grupo 3, mas principalmente baseando-se nas literaturas de referência. Assim, um novo checklist foi criado para a avaliação do nosso próprio guia de estilo.

<!-- <center>
<img src="../../assets/img/guiaG4.png"></img>

<p>Figura 1 - Checklist Guia de Estilo - Grupo 4 (Fonte: Autores)</p>
</center>

<center>
<img src="../../assets/img/guiaG3.png"></img>

<p>Figura 2 - Checklist Guia de Estilo - Grupo 3 (Fonte: Autores)</p>
</center> -->


## Checklist
<!-- LIVRO BASE PARA CRIAÇÃO DAS PERGUNTAS -->
Os checklists foram estabelecido com base nos critérios da literatura Guia de Estilos BI[4], Style Guide[5], Estilos de Interação[6]. E como citado, nas verificações realizadas anteriormente, pelo nosso grupo, OpenStreetMap[7] e pelo Grupo 3, Banco Central[8]. Além das perguntas padrões estabelecidas no [Planejamento Geral](../0planejamento-geral.md).

<center>
<!-- ADICIONAR O CHECKLIST OU OS CHECKLISTS DA ENTREGA REFERENTE -->
| ID| Descrição | Avaliação | Observação |
|---|---|---|---|
| 1 | O artefato possui uma introdução condizente com o conteúdo do texto? |Sim| -|
| 2 | Todas as bibliografias/referências bibliográficas são utilizadas de forma correta? | Não | - |
| 3 | Todas as tabelas e figuras são chamadas no texto, possuem legendas e fontes? |Sim  |-|
| 4 | A metodologia esta de acordo com o artefato analisado? | Não | Não possui |
|5|É apresentado como os princípios Gerais serão adicionados ao trabalho? |Não|Não foi explicitado |
|6|Os motivos de manter ou não os padrões do site, foram apresentados e bem justificados? |Não|Não foi explicitado |
|7|É apresentado e definido o público-alvo? <br> (Pessoas ligadas com a definição de requisitos até a codificação e criação da camada de apresentação - analistas de negócio, desenvolvedores, design, estudantes da matéria de IHC...) |Incompleto|Por mas que complemente na introdução, falta jogar para a seção de público-alvo|
|8|As informações de como utilizar e manter o guia são bem apresentadas? |Incompleto|Muito simples|
|9|O resultado de análise é apresentado? <br> (Fazendo a descrição do ambiente de trabalho do usuário e ligando com artefatos anteriores, ex: personas) |Incompleto|Muito simples, falta linkar com putros artefatos|
|10|Dos elementos de interface, a **disposição espacial** é apresentada de forma correta? <br> (Uso de uma página por assunto, sem rolagem de tela, acoplando todos os dados necessários) |Sim|-|
|11|Dos elementos de interface, a **grid** é apresentada de forma correta? <br> (criadas pensando em manter a padronização da interface, como o alinhamento) |Incompleto|Separar a grid da disposição|
|12|Dos elementos de interface, a **janelas** é apresentada de forma correta? <br> (Se a quantidade de janelas esta em uma quantidade boa, sem excesso. Se elas são ligadas entre si...) |Não|Muitas janelas que poderiam ser reduzidas|
|13|Dos elementos de interface, a **tipografia** é apresentada de forma correta? <br> (Se a escolha da tipografia é apresentada e justificada para o projeto) |Não|Não é justificado|
|14|Dos elementos de interface, as **cores** são apresentadas de forma correta? <br> (Se foram pensadas evitando excessos e trabalhando com tons e sombra) |Não|Uso de muitas cores|
|15|Dos elementos de interação, os **estilos de interação** são apresentados de forma correta? (menu, manipulação direta, formulário...)|Sim|-|
|16|Dos elementos de interação, a **seleção de estilo** é apresentada de forma correta? <br> (organizada, estruturada, com elementos fáceis de associar e distintos uns dos outros) |Sim|-|
|17|Dos elementos de interação, os **aceleradores** são apresentados de forma correta? <br> (atalhos que prevê ações e projetado a erros) |Sim|-|
|18|Dos elementos de ação, o **preenchimento de campos** é apresentado de forma correta? <br>(torna a interação mais produtiva possível) |Sim|-|
|19|Dos elementos de ação, a **seleção** é apresentada de forma correta?<br> (botões funcionais, bem espaçados, botões com conteúdo crítico longe de um botões muito usuais) |Sim|-|
|20|Dos elementos de ação, a **ativação** é apresentada de forma correta?<br> (hiperlinks - torna a interação mais produtiva possível de forma organizada, estruturada) |Não|Não foi apresentado|
|21|Os vocabulários e padrões são bem apresentados?<br> (Terminologia, tipos de tela, sequências de diálogos) |Incompleto|Exemplifica melhor|


<p>Tabela 1 - Checklist Guia de Estilo (Fonte: Autores)</p>
</center>

### Gráfico
Com base no checklist feito no processo de inspeção do Guia de Estilo, foi produzido o gráfico de avaliação do artefato, que pode ser visualizado/analisado na Figura 1.
<center>
<img src="../../assets/img/grafico-guia-estilo.png"></img>
<p>Figura 1 - Gráfico Guia de Estilo (Fonte: Autores)</p>
</center>


## Correções
O planejamento e a situação da correção dos artefatos do Guia de Estilo será registrado na Tabela 2. 

<center>

|ID |Descrição |Detalhes |Corretor|Revisor|Status|
|-------|------|------|---------|---|--|
|2|Bibliografias/referências bibliográficas|Corrigir conforme ABNT|[Raquel](https://github.com/raqueleucaria)|[Caetano](https://github.com/caeslucio)|ok|
|4|Metodologia|Acrescentar|[Raquel](https://github.com/raqueleucaria)|[Caetano](https://github.com/caeslucio)|-|
|5|Princípios Gerais|Referenciar e deixar de forma explicita o uso|[Raquel](https://github.com/raqueleucaria)|[Caetano](https://github.com/caeslucio)|-|
|6|Os motivos dos padrões do site|Deixar explícito|[Raquel](https://github.com/raqueleucaria)|[Caetano](https://github.com/caeslucio)|-|
|7|Público-alvo?|Complementar e ligar com artefatos anteriores do projeto como personas e questionário|[Raquel](https://github.com/raqueleucaria)|[Caetano](https://github.com/caeslucio)|ok|
|8|Como utilizar e manter o guia|Complementar|[Raquel](https://github.com/raqueleucaria)|[Caetano](https://github.com/caeslucio)|ok|
|9|Resultado de análise|Complementar e ligar com artefatos anteriores do projeto como personas e questionário|[Raquel](https://github.com/raqueleucaria)|[Caetano](https://github.com/caeslucio)|ok|
|11|Grid |Separar o tópico|[Raquel](https://github.com/raqueleucaria)|[Caetano](https://github.com/caeslucio)|-|
|12|Janelas |Reduzir a quantidade|[Raquel](https://github.com/raqueleucaria)|[Caetano](https://github.com/caeslucio)|-|
|13|Tipografia |Definir e justificar o uso no projeto|[Raquel](https://github.com/raqueleucaria)|[Caetano](https://github.com/caeslucio)|-|
|14|Cores |Reduzir o número de cores|[Raquel](https://github.com/raqueleucaria)|[Caetano](https://github.com/caeslucio)|-|
|20|Ativação|Definir e apresentar os elementos|[Raquel](https://github.com/raqueleucaria)|[Caetano](https://github.com/caeslucio)|-|
|21|Vocabulário|Trazer os exemplos|[Raquel](https://github.com/raqueleucaria)|[Caetano](https://github.com/caeslucio)|-|

<p>Tabela 2 - Distribuição da Correção dos Artefatos (Fonte: Autores)</p>
</center>

## Gráfico Correções
Depois das correções se foi verificado novamente, e o resultado pode ser visto na figura 2.
<center>
<img src="../../assets/img/correcoes-guia.png"></img>
<p>Figura 2 - Gráfico Guia de Estilo com Correções (Fonte: Autores)</p>
</center>


## Referência bibliográfica

> [1] ISO/IEC/IEEE 12207:2017(E) (ISO/IEC/IEEE, 2017, p. 82). Disponível em: <https://www.iso.org/obp/ui/#iso:std:iso-iec-ieee:24765:ed-2:v1:en> . Acesso em: 13 jun. 2023

> [2] OPENSTREETMAP, grupo 4. Disponível em <https://interacao-humano-computador.github.io/2023.1-OpenStreetMap/>. Acesso em: 15 jun. 2023.

> [3] BUSH, Marilyn, Chris Gerrard, Clifford Shelley. Fagan Inspection: The Silver Bullet No-one Wants to Fire. London SPIN, 25 mar. 2010.

> [4] GUIA de Estilos BI - Estratégia de identidade visual, conceitos, orientações e boas práticas a serem utilizadas nas interfaces gráfcas dos sistemas de Business Intelligence. 2016. Disponibilizado em: [Link](../assets/referencias/GuiAEstilos_BI.pdf). Acesso em 17/06/2023

> [5] STYLE Guide: Como Desenvolver o Guia de Estilo da Sua Interface? Aelaschool, 2021. Disponível em: <https://aelaschool.com/designvisual/style-guide-como-desenvolver-o-guia-de-estilo-da-sua-interface/>. Acesso em 15/06/2023

> [6]Estilos de Interação, INF1403 – Introdução a IHC, Aula 18. Informática da PUC-Rio. 2014. Disponível em: <http://www.inf.puc-rio.br/~inf1403/docs/alberto2014-1/Aula18_EstilosDeInteracao.pdf>

> [7] EUCARIA, Raquel. Verificação do artefato "Guia de Estilo". Repositório do Grupo OpenStreetMap da disciplina de Interação Humano Computador da Universidade de Brasília, 2023. Disponível em: <https://interacao-humano-computador.github.io/2023.1-BancoCentral/#/verificacao/ponto_controle_3/guia_estilo_g4>. Acesso em 15/06/2023

> [8] BOSI, Rafael. Verificação do artefato "Guia de Estilo". Repositório do Grupo Banco Central da disciplina de Interação Humano Computador da Universidade de Brasília, 2023. Disponível em: <https://interacao-humano-computador.github.io/2023.1-BancoCentral/#/verificacao/ponto_controle_3/guia_estilo_g4>. Acesso em 15/06/2023


## Bibliografia
> MACIEL, Geovanna. Planejamento da Verificação da Etapa 1 do Grupo 2. Repositório do Grupo Bilheteria Digital da disciplina de Requisitos da Universidade de Brasília, 2023. Disponível em: <https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/verificacao/grupo2/entrega1/planejamento-verificacao-e1-grupo2/>. Acesso em: 15 de Junho de 2023.

> PENHA, Igor, Lucas Gobbi. Planejamento da Verificação da Etapa 2 do Grupo 4. Repositório do Grupo VLC da disciplina de Requisitos da Universidade de Brasília, 2023. Disponível em: <https://requisitos-de-software.github.io/2023.1-VLC/#/verificacao/entrega_2/planejamento_verificacao_etapa2>. Acesso em: 15 de Junho de 2023.

> REINEHR, Sheila. Engenharia de requisitos. E-book. ISBN 9786556900674. Disponível em: https://integrada.minhabiblioteca.com.br/#/books/9786556900674/. Acesso em: 15 de Junho 2023.

> Sommerville, Ian. Engenharia de software. 08. ed. São Paulo: Pearson Addison Wesley, 2007.

> SERRANO, Milene, SERRANO, Maurício. Análise de Requisitos (Aula 23). UnB Gama, Brasília, 2023. Disponível no [link](../assets/referencias/Requisitos%20-%20Aula%20023.pdf).

## Histórico de Versão
|    Data    | Data Prevista de Revisão | Versão |      Descrição       |                                 Autor                                  |               Revisor               |
| :--------: | :----------------------: | :----: | :------------------: | :--------------------------------------------------------------------: | :---------------------------------: |
| 18/06/2023 |        19/06/2023        |  1.0   | Criação do documento |  [Raquel](https://github.com/raqueleucaria) | [Caetano](https://github.com/caeslucio)  |
# Análise de Tarefas

## Introdução
Segundo a norma internacional ISO/IEC/IEEE 12207:2017(E) (ISO/IEC/IEEE, 2017, p. 82) [1], o objetivo da verificação se define em "prover evidência objetiva que o sistema ou elemento do sistema atende completamente seus requisitos e características especificados". Com isso, a fim de garantir qualidade e consistência dos requisitos, realizaremos a verificação dos documentos do nosso grupo, [OpenStreetMap](https://interacao-humano-computador.github.io/2023.1-OpenStreetMap/)[2], da Interação Humano Computador.

## Objetivos
O objetivo deste documento é realizar a verificação da Análise de Tarefas, artefato da Entrega 2, do Grupo 4 ([OpenStreetMap](https://requisitos-de-software.github.io/2023.1-Caesb/)). De forma impessoal, este documento não deseja avaliar os membros do grupo, mas o artefato em si.

## Metodologia
Como método de investigação e produção da verificação, utilizaremos a inspeção, mais especificamente a _Fagan Inspection_. Na qual, segundo Bush [3], consiste na "inspeção de documentos entendidos como prontos para uso e busca por defeitos". Seguindo as etapas de planejamento, visão geral, preparação, inspeção e correção, e depois realizando o acompanhamento das correções. Maiores detalhes de planejamento, estão apresentados no [Planejamento da Entrega 2](0planejamento.md)

## Verificações anteriores
Durante as aulas das disciplinas de Interação Humano Computador, ministrada pelo professor André Barros, existiu uma atividade de se realizar a verificação dos artefatos de outro grupo, onde o grupo 3 ([Banco Central](https://interacao-humano-computador.github.io/2023.1-BancoCentral/#/)) fez a verificação dos artefatos do grupo 04, onde essa verificação será levada em conta, onde será considerado se algum ponto mencionado faz sentido está presente no checklist, sempre levanto em conta a literatura de referência da disciplina.

## Checklist
Os checklists foram estabelecidos com base nos critérios da literatura o livro interação humano computador[4] e os pontos apontados pelo grupo 3, do [Banco Central](https://interacao-humano-computador.github.io/2023.1-BancoCentral/#/), contendo também algumas perguntas básicas para avaliar a padronização, sendo apresentados na tabela 1 as questões mais gerais, e na tabela 2 e 3 questões específicas dos métodos escolhidos, todas já devidamente preenchidas.

<center>

| ID| Descrição | Avaliação | Observação |
|:-:|---|:-:|---|
| 1 | O artefato possui uma introdução condizente com o conteúdo do texto? | Sim ||
| 2 | Todas as bibliografias/referências bibliográficas são utilizadas de forma correta? | Sim ||
| 3 | Todas as tabelas e figuras são chamadas no texto, possuem legendas e fontes? | Sim ||
| 4 | A metodologia está de acordo com o artefato analisado? | Sim ||
| 5 | As tarefas analisadas correspondem as tarefas principais do usuário?<a href="#1">¹</a> | Sim ||
| 6 | Todas as tarefas possuem um objetivo?<a href="#2">²</a> | Sim ||
| 7 | É detalhado o processo da tarefa?<a href="#3">³</a> | Sim ||
| 8 | É demostrado como essa análise sera útil para o desenvolvimento do projeto? | Não ||

<p>Tabela 1 - Checklist da Análise de Tarefas Geral. (Fonte: Autor)</p>

</center>

<div id="1"></div> 
¹ - Aquelas que eles mais realizam apresentadas no perfíl de usuário.
<div id="2"></div> 
² - Algo a ser alcançado com sua execução.
<div id="3"></div> 
³ - Todas as partes que envolver alcançar o objetivo.

<center>

| ID | Descrição | Avaliação | Observação |
|:--:|---|:-:|---|
| 9 | Existe o diagrama visual representando a tarefa, tendo os elementos corretamente identificados como demostrado na <a href="#4">figura 1</a>? | Sim ||
| 10 | O plano para a realização dessa tarefa apresenta todos os subobjetivos necessários para alcançá-la? | Sim ||
| 11 | O plano apresenta a ordem correta de como os subobjetivos devem ser alcançados?<a href="#5">⁴</a> | Sim ||
| 12 | Existe a representação das relações entre os subobjetivos que compõem o plano demostrado na <a href="#4">figura 1</a>? | Sim ||
| 13 | Estão presentes as operações para alcançar os subobjetivos?<a href="#6">⁵</a> | Sim ||

<p>Tabela 2 - Checklist da Análise Hierárquica de Tarefas. (Fonte: Autor)</p>

</center>

<div id="4"></div>

<center>

![](../assets/img/HTA.png)

Figura 1 - Elementos da Análise Hierárquica de Tarefas. (Fonte: Livro Interação Humano Computador[1]())


</center>

<div id="5"></div>
⁴ - A ordem a qual a tarefa é realmente executada.
<div id="6"></div> 
⁵ - São circunstâncias de ativação do objetivo (input ou entrada), atividades ou ações (actions) para alcançá-lo e condições que indicam seu atingimento (feedback).

<center>

| ID | Descrição | Avaliação | Observação |
|:--:|---|:-:|---|
| 14 | O GMOS apresenta os elementos descritos no Livro Interação Humano Computador[4]()?<a href="#7">⁶</a> | Incompleto | Alguns elementos não são observados no GMOS |
| 15 | É apresentado uma ordem sequencial?<a href="#8">⁷</a> | Sim ||
| 16 | Existem os Objetivos e Subobjetivos? | Sim ||
| 17 | Os operadores fazem sentido?<a href="#7">⁶</a>| Sim ||

<p>Tabela 3 - CMN - GOMS. (Fonte: Autor)</p>

</center>

<div id="7"></div>
⁶ - São eles:

* Objetivos: O que o usuário quer realizar com o software.
* Operadores: Ações concretas que o software permite que o usuário faça.
* Métodos: Sequências de subobjetivos e operadores que permitem atingir um objetivo maior.
* Regras de Seleção: Quando há mais de um método deve se ter regras de seleção, que são as tomadas de decisão do usuário sobre qual método utilizar em cada situação.

<div id="8"></div>
⁷ - Sua elaboração está em uma ordem que faz sentido para a realização da tarefa.

## Gráfico
Com base no checklist feito no processo de inspeção da Análise de Tarefas, foi produzido o gráfico de avaliação do artefato, que pode ser visualizado/analisado na Figura 2.

<center>

![](../assets/img/grafico_analise.png)

Figura 2 - Gráfico Análise de Tarefas. (Fonte: Autor)

</center>

## Correções
O planejamento e a situação da correção dos artefatos da Análise de Tarefas será registrado na Tabela 4.

<center>

| ID | Descrição resumida| Detalhes da correção| Responsável pela correção | Revisor | Status |
|:--:|------|------|:---------:|:---:|:--:|
| 08 | Não é dito como elas serão usadas no projeto | Explicar a sua utilização. | [Daniel](https://github.com/daniel-de-sousa) | [Guilherme](https://github.com/guilhermekishimoto) | OK |
| 08 | O GMOS não apresenta todos os elementos | Refazer as tarefas com GMOS | [Raquel](https://github.com/raqueleucaria) | [Daniel](https://github.com/daniel-de-sousa) | - |


<p>Tabela 4 - Distribuição da Correção do Artefato (Fonte: Autor)</p>
</center>


## Gráfico das Correções
Depois das correções se foi verificado novamente, e o resultado pode ser visto na figura 2.

<center>

![](../assets/img/grafico_analise_corre.png)

<p>Figura 3 - Gráfico da Análise de Tarefas com Correções. (Fonte: Autor)</p>

</center>

## Referência bibliográfica

> [1] ISO/IEC/IEEE 12207:2017(E) (ISO/IEC/IEEE, 2017, p. 82). Disponível em: https://www.iso.org/obp/ui/#iso:std:iso-iec-ieee:24765:ed-2:v1:en . Acesso em: 13 jun. 2023

> [2] OPENSTREETMAP, grupo 4. Disponível em https://interacao-humano-computador.github.io/2023.1-OpenStreetMap/. Acesso em: 15 jun. 2023.

> [3] BUSH, Marilyn, Chris Gerrard, Clifford Shelley. Fagan Inspection: The Silver Bullet No-one Wants to Fire. London SPIN, 25 mar. 2010.

> [4] Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1 . Acesso em 19 de jun.2023


## Bibliografia

> Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1 . Acesso em 19 de jun.2023

> SERRANO, Milene, SERRANO, Maurício. Análise de Requisitos (Aula 23). UnB Gama, Brasília, 2023. Disponível no [link](../assets/referencias/Requisitos%20-%20Aula%20023.pdf).

> BANCOCENTRAL, grupo 03. Disponível em https://interacao-humano-computador.github.io/2023.1-BancoCentral/#/ . Acesso em 19 de jun.2023


## Histórico de Versão
|    Data    | Data Prevista de Revisão | Versão |      Descrição       |                                 Autor                                  |               Revisor               |
| :--------: | :----------------------: | :----: | :------------------: | :--------------------------------------------------------------------: | :---------------------------------: |
| 19/06/2023 |        19/06/2023        |  1.0   | Criação do documento |  [Daniel](https://github.com/daniel-de-sousa) | [Guilherme](https://github.com/guilhermekishimoto)  |
| 05/07/2023 |        05/07/2023        |  1.1   | Ajustes no documento |  [Daniel](https://github.com/daniel-de-sousa) | [Guilherme](https://github.com/guilhermekishimoto)  |
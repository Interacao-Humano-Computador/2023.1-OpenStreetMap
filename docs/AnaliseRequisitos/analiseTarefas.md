# Análise de Tarefas

## Introdução

A análise de tarefas é uma abordagem sistemática e metodológica usada para compreender como as pessoas realizam suas atividades no OpenStreetMap. Foi necessário identificar os objetivos, ações, interações e os desafios enfrentados durante o uso do site. Essa compreensão é fundamental para o desenvolvimento de interfaces mais eficientes, intuitivos e amigáveis.

## Etapas


1. **Identificação do objetivo:** Determinar qual é a tarefa principal que será analisada e compreender o propósito geral por trás dessa tarefa.
2. **Observação e coleta de dados:** Observar e registrar as ações dos usuários enquanto realizam a tarefa, no caso por meio dos [questionários]() e [perfil do usuário](perfil_usuario.md).
3. **Decomposição da tarefa:** Dividir a tarefa em etapas menores e mais gerenciáveis, a fim de entender a sequência de ações e interações envolvidas.
4. **Análise das interações e fluxo de trabalho:** Analisar como as diferentes etapas se relacionam, identificando dependências, restrições e possíveis problemas de fluxo de trabalho.
5. **Identificação de pontos fortes e pontos fracos:** Identificar os aspectos positivos e negativos da execução da tarefa, como eficiência, usabilidade, dificuldades ou confusões encontradas pelos usuários. E possíveis recomendações.


## Metodologias 
Para fazer uso das principais metodologias de análise de tarefas, selecionamos as tarefas "Cadastrar novos pontos de referência", "Procurar rotas" e Contribuir com o desenvolvimento do site#, as tarefas mais utilizadas pelos usuários. As metodologias mais usadas são:

- Análise	Hierárquica	de	Tarefas	(HTA	– Hierarchical Task Analysis)
- GOMS	(Goals,	Operators,	Methods, e	Selection	Rules)
<!-- - ConcurTaskTrees (CTT) -->


### 1. Análise Hierárquica de Tarefas (HTA)
A HTA ajuda a identificar a estrutura hierárquica das tarefas, decompondo-as em sub-tarefas menores e mais gerenciáveis. Isso permite uma compreensão mais detalhada de como as tarefas são executadas, identificando as relações entre as sub-tarefas e ajudando a identificar gargalos e oportunidades de melhoria. Ao compreender a estrutura hierárquica das tarefas, os projetistas podem propor designs mais eficientes e intuitivos, otimizando a interação dos usuários com os sistemas e interfaces.

A análise hierárquica de tarefas possui os seguintes elementos:

- **Tarefa**: qualquer parte de um trabalho a ser realizado;
- **Objetivo**: um estado final, que pode ser definido por eventos ou valores fisicamente observáveis
- **Subobjetivo**: um objetivo de alto nível é dividido em subobjetivos, por exemplo o objetivo "iniciar uma partida de xadrez" possui, dentre outros, os seguintes subobjetivos: "definir o tipo de oponente, definir a modalidade de jogo e configurar o incremento";
- **Plano**: o conjunto de subobjetivos de um objetivo e suas relações consiste em um plano;
- **Operação**: circunstâncias de ativação do objetivo (_input_ ou entrada), atividades ou ações (_actions_) para alcançá-lo e condições que indicam seu atingimento (_feedback_)

A análise hierárquica de tarefas foi feita por meio de uma tabela (Tabela 1) e por um diagrama (Figura 2). No segundo caso, utiliza-se a notação representada na Figura 1.

![Elementos do diagrama](./../assets/analise_requisitos/hta-1.png)

<div style="text-align: center">
<p> Figura 1: Elementos do diagrama (Fonte: [1]).</p>
</div>

#### **Análise da tarefa: Cadastrar novos pontos de referência**


| Objetivos/Operações | Problemas e recomendações |
| - | - |
| 0. Cadastrar novos pontos de referência (1>2)| **input**:  Acesso ao menu "iniciar partida" na tela inicial;<br/> **feedback**: tela de pesquisa e mapa geral  <br/> **plano**: selecionar novo ponto de refereência e cadastrar-lo <br/> **recomendação**: permitir que usuário cadastre tarefa a partir da tela inicial |
| 1.  Selecionar novo ponto de refereência (1>2) | **plano**: dar zoom no mapa para o local desejado e selecionar o ponto de referência no mapa<br/> **recomendação**: abrir o mapa com zoom na área em que o usuário esta|
| 1.1  Dar zoom no mapa para o local desejado |   | |
| 1.2  Selecionar o ponto de referência no mapa |  | |
| 2  Cadastrar ponto de referÊncia (1>2)| **plano**: preencher as informações sobre o ponto de referência e salvar <br/> **recomendação**: salvar automáticamente, sem precisar apertar botão| |
| 2.1 Preencher as informações sobre o ponto de referência |  | |
| 2.2 Salvar as informações sobre o ponto de referência |  | |
<div style="text-align: center">
<p> Tabela 1: Análise Hierárquica de Tarefas para o objetivo "Cadastrar novos pontos de referência" <br/>(Fonte: autor, 2022).</p>
</div>

![Diagrama da Análise Hierárquica de Tarefas para o objetivo "Cadastrar novos pontos de referência"](./../assets/analise_requisitos/diagrama.png)

<div style="text-align: center">
<p> Figura 2: Diagrama da Análise Hierárquica de Tarefas para o objetivo "Cadastrar novos pontos de referência" <br/> (Fonte: autor, 2022).</p>
</div>


<!-- ### 2. Objetivos, Operadores, Métodos e Regras de Seleção (GOMS)

O GOMS visa modelar o desempenho humano em interações com sistemas computacionais. Ele analisa as metas dos usuários, os operadores disponíveis, os métodos seguidos e as regras de seleção utilizadas. Essa análise permite identificar os passos cognitivos e as ações necessárias para realizar uma tarefa, bem como possíveis gargalos cognitivos. Com base nessas informações, os projetistas podem otimizar o design dos sistemas, simplificando as interações, reduzindo a carga cognitiva e tornando as tarefas mais eficientes e fáceis de serem executadas.

    #### Citar autores dos livros indicados

#### Análise da tarefa: Procurar rotas

O modelo GOMS foi utilizado para analisar a tarefa "Procurar rotas", sendo o escopo de avaliação a situação em que um usuário experiente com a plataforma deseja aprender os conceitos iniciais de xadrez. -->

<!-- GOAL 0: aprender a jogar xadrez
<p style="padding-left: 1vw">GOAL 1: encontrar a seção de estudo da plataforma</p>
<p style="padding-left: 3vw">OP. 1.1: posicionar o cursor do mouse sobre o menu aprender</p>
<p style="padding-left: 3vw">OP. 1.2: clicar no menu "básicos do xadrez" </p>
<p style="padding-left: 1vw">GOAL 2: selecionar o assunto para estudar </p>
<p style="padding-left: 3vw">OP. 2.1: girar a roda do mouse para a modalidade desejada </p>
<p style="padding-left: 3vw">OP. 2.2: clicar na opção desejada </p>
<p style="padding-left: 1vw">GOAL 3: estudar o assunto escolhido </p>
<p style="padding-left: 3vw">OP. 3.1: fazer a leitura do tutorial à direita da página </p>
<p style="padding-left: 3vw">OP. 3.2: movimentar as peças no tabuleiro clicando nelas e nas posições de destino </p> -->

<!-- ### 3. ConcurTaskTrees (CTT)
    #### Explicar e a metodologia e a tarefa z

#### Análise da tarefa: Contribuir com o desenvolvimento do site
    #### Usar a metodologia na tarefa z -->



## Bibliografia

[1] Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1.

## Histórico de Versão
|    Data    | Data Prevista de Revisão | Versão |      Descrição       |                                                                Autor                                                                 |               Revisor               |
| :--------: | :----------------------: | :----: | :------------------: | :----------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------: |
| 07/05/2023 |        08/05/2023        |  1.0   | Criação do documento | [Raquel](https://github.com/raqueleucaria) | [Daniel](https://github.com/daniel-de-sousa)|
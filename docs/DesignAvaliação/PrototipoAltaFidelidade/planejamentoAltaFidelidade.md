# Planejamento da Avaliação do Protótipo de Alta Fidelidade do Protótipo

## Introdução
Este documento descreve o Planejamento da Avaliação de Alta Fidelidade do protótipo do OpenStreetMap, visando identificar problemas de usabilidade, coletar feedback dos usuários e validar o design proposto. O protótipo de alta fidelidade é uma versão interativa e visualmente mais próxima do produto final, permitindo uma avaliação mais precisa das funcionalidades e da experiência do usuário. A avaliação será realizada seguindo uma abordagem sistemática, utilizando técnicas específicas e considerando aspectos éticos.
## Metodologia
O Planejamento da Avaliação do Protótipo de Alta Fidelidade será conduzido pelas atividades básicas: Preparação, Coleta de Dados, Interpretação, Consolidação e Relato dos Resultados, propostas por Simone no livro IHC-UX[[1](#referencia-bibliografia)]. E também será usado como base o Framework DECIDE, de Preece et al. (2002)[[2](#referencia-bibliografia)], também citado no livro, onde cada letra do Framework representa uma fase específica do planejamento, na tabela 1 é definido cada fase.


<center>

| Letra |                             Definição                              |
| :---: | :----------------------------------------------------------------: |
|   [D](#d-objetivos)   |            Determinar os objetivos da avaliação de IHC.             |
|   [E](#e-explorar-perguntas)   |     Explorar as perguntas a serem respondidas com a avaliação.      |
|   [C](#c-metodo-de-avaliacao)   |  (*Chose*) Escolher os métodos que serão utilizados na avaliação.   |
|   [I](#i-questoes-praticas-preparacao)   |    Identificar e administrar as questões práticas da avaliação.     |
|   [D](#d-questoes-eticas)   |             Decidir como lidar com as questões éticas.              |
|   [E](#e-interpretacao-e-resultados-dos-dados)   | (*Evaluate*) Interpretar e apresentar os dados da avaliação de IHC. |

Tabela 1 - Metodologia DECIDE (Fonte: Autor, 2023)

</center>


## D - Objetivos
<!-- Avaliação formativa ou somativa? -->
Os objetivos são os aspectos alvos da investigação do OpenStreetMap. E são os seguintes:

- **1. Análise de ideias e alternativas de design**: Avaliar a facilidade de aprendizado (quanto ao uso) e o tempo necessários para o desenvolvimento de cada alternativa (quanto a construção) comparando com o [Protótipo de Baixa Fidelidade]().
- **2. Identificação de problemas na interação e na interface**: Identificar problemas na interação e na interface que prejudiquem a qualidade de uso do sistema, classificados em grau de impacto nocivo, frequência e fatores de qualidade (usabilidade, experiência do usuário, acessibilidade ou comunicabilidade).
<br>

¹ Stakeholders são todos os  envolvidos no sistema, como os usuários, designers, cliente (proprietário do sistema), desenvolvedores...

## E - Explorar Perguntas
Levando em consideração os objetivos da avaliação, foram estabelecidas as seguintes perguntas:

**Análise de alternativa**

  - Qual das alternativas é a mais eficiente? Mais fácil de aprender?
  - Qual delas pode ser construída em menos tempo?
  - De qual delas se espera que tenha um impacto negativo menor ao ser adotada?
  - Qual delas torna mais evidente os diferenciais da solução projetada?
  - Qual delas os usuários preferem? Por quê?
  
**Identificação de problemas**

  - O usuário consegue operar o sistema?
  - Ele atinge seu objetivo? Com quanta eficiência? Em quanto tempo? Após cometer quantos erros?
  - Que parte da interface e da interação o deixa insatisfeito?
  - Que parte da interface o desmotiva a explorar novas funcionalidades?
  - Ele entende o que significa e para que serve cada elemento de interface?
  - Ele vai entender o que deve fazer em seguida?
  - Que problemas de IHC dificultam ou impedem o usuário de alcançar seus objetivos?
  - Onde esses problemas se manifestam? Com que frequência tendem a ocorrer? Qual é a gravidade desses problemas?
  - Quais barreiras o usuário encontra para atingir seus objetivos?
  - Ele tem acesso a todas as informações oferecidas pelo sistema

## C - Método de Avaliação
O método de avaliação escolhido, dentro dos métodos de observação, foi o **teste de usabilidade** que visa avaliar a usabilidade de um sistema interativo a partir de experiências de uso dos seus usuários-alvo (Rubin, 1994[[3](#referencia-bibliografia)]; Rubin e Chisnell, 2008[[4](#referencia-bibliografia)]). Tendo os objetivos definidos, podemos estabelecer os critérios de avaliação, relacionados a dados mensuráveis. Assim, será observado e registrado os dados referentes ao desempenho dos participantes na realização das tarefas, suas opiniões e sentimentos ao usarem o sistema. Seguindo as atividades do teste de usabilidade, conforme a Figura 1.

<center>

![Alt text](teste-usabilidade.png)
<p>Figura 1 - Atividades do teste de usabilidade (Fonte: Simone [<a href="#referencia-bibliografia">5</a>] )</p>
</center>


## I - Questões Práticas (Preparação)

### Tarefas
As tarefas a serem executadas pelos participantes foram retiradas da [Análise de Tarefas](../../AnaliseRequisitos/analiseTarefas.md), e são:

1. Buscar local;
2. Cadastrar Ponto de Referência;
3. Compartilhar localização em tempo real;
4. Cadastrar Estrada.

### Perfil dos participantes
A quantidade mínima de participantes será de 3 pessoas, sendo esse um número adequado segundo Krug. Considerando o [perfil de usuário](../../../AnaliseRequisitos/perfil_usuario/#resultado-dos-usuarios) e as [personas](../../AnaliseRequisitos/Personas.md) estabelecidas anteriormente, devem ser priorizados os participantes com o seguinte perfil:

- 18 a 30 anos;
- Superior incompleto;
- Atuante na área de TI;
- Tenha afinidade com tecnologia.

### Custos e Ferramentas
O [Protótipo de Alta Fidelidade](./prototipo-alta.md) será criado no Figma que permite que os participantes possam interagir com o sistema a partir de um link. Além disso, as avaliações devem ser feitas de modo que a equipe e os participantes (usuários) não tenham custos. Para isso, será utilizado as seguintes ferramentas:

- Computador;
- Microfone;
- Câmera;
- Microsoft Teams;
- Roteiro de Avaliação.

### Teste-Piloto
O teste piloto será realizado com os membros da equipe, para permitir identificar possíveis problemas no roteiro de testes e entrevistas, ajustar o tempo necessário para cada atividade e familiarizar-se com o processo de condução dos testes e entrevistas. E os seus resultados serão utilizados para aprimorar o roteiro e a abordagem geral.

   
### Coleta de Dados
A coleta de dados consiste no questionário pré-teste, pós-teste (Tabela 2 e 3) e no registro/respostas as perguntas mensuráveis. Além da gravação do teste, via Teams, com o participante compartilhando sua tela e sua câmera.

<details>
<summary>Questionário Pré-Teste (Tabela 2)</summary>
<center>
    
<table>
  <thead>
    <tr>
      <th>Número</th>
      <th>Perguntas</th>
      <th>Opções de resposta</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>Qual a sua idade?</td>
      <td>Aberta</td>
    </tr>
    <tr>
      <td>2</td>
      <td>Qual o seu nível de formação acadêmica atual?</td>
      <td>Aberta</td>
    </tr>
    <tr>
      <td>3</td>
      <td>Qual o seu nível de experiência com tecnologias?</td>
      <td>[ ] Alto<br>[ ] Médio<br>[ ] Baixo</td>
    </tr>
    <tr>
      <td>4</td>
      <td>Qual o seu nível de experiência com o OpenStreetMap?</td>
      <td>[ ] Alto<br>[ ] Médio<br>[ ] Baixo<br>[ ] Nenhum</td>
    </tr>
  </tbody>
</table>

<p>Tabela 2 - Perguntas pré-teste (Fonte: Autor, 2023)</p>
</center>
</details>


<details>
<summary>Questionário Pós-Teste (Tabela 3)</summary>
<center>

<table>
  <thead>
    <tr>
      <th>Número</th>
      <th>Perguntas</th>
      <th>Opções de resposta</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>Como você descreveria a aparência visual do protótipo?</td>
      <td>Aberta</td>
    </tr>
    <tr>
      <td>2</td>
      <td>Quais elementos da interface chamaram sua atenção?</td>
      <td>Aberta</td>
    </tr>
    <tr>
      <td>3</td>
      <td>O protótipo é fácil de usar?</td>
      <td>[ ] Sim<br>[ ] Não</td>
    </tr>
    <tr>
      <td>4</td>
      <td>As interações e animações presentes no protótipo são adequadas e contribuem para sua experiência?</td>
      <td>[ ] Sim<br>[ ] Não</td>
    </tr>
    <tr>
      <td>5</td>
      <td>Em geral, qual foi a sua experiência ao interagir com o protótipo?</td>
      <td>Aberta</td>
    </tr>
    <tr>
      <td>6</td>
      <td>Você teria alguma sugestão de melhoria?</td>
      <td>Aberta</td>
    </tr>
  </tbody>
</table>


<p>Tabela 3 - Perguntas pós-teste (Fonte: Autor, 2023)</p>
</center>
</details>



### Cronograma
A seguir, apresenta-se o cronograma para as atividades da avaliação do protótipo de alta fidelidade do OpenStreetMap, as quais deverão ser realizadas em um ambiente controlado, com o auxílio de um computador e um microfone para a gravação das avaliações. O cronograma está apresentado na tabela 4:

<center>

| Data       | Hora  | Local           | Avaliador | Participante  | Tarefa              |
|------------|-------|-----------------|-----------|---------------|---------------------|
| 23/06/2023 | 19:00 | Online - Microsoft Teams | Raquel       | - | Teste Piloto |
| 24/06/2023 | 20:00 | Online - Microsoft Teams | Caetano       | Participante 1 | Teste de Usabilidade 1 |
| 24/06/2023 | 20:00 | Online - Microsoft Teams | Caetano       | Participante 2 | Teste de Usabilidade 2 |
| 25/06/2023 | 20:00 | Online - Microsoft Teams | Caetano       | Participante 3 | Teste de Usabilidade 3|

Tabela 4 - Cronograma (Fonte: Autor, 2023)

</center>

## D - Questões Éticas
Durante todo o processo de avaliação, serão consideradas [questões éticas](../../Planejamento/Aspectos_Eticos.md), incluindo privacidade, consentimento informado e confidencialidade dos participantes. Será fornecido um [termo de consentimento](../../Planejamento/Aspectos_Eticos.md) para os participantes no qual eles concordarão em participar da avaliação e permitir a gravação das sessões, garantindo que suas informações sejam utilizadas apenas para fins acadêmicos e que sua identidade seja protegida. Além disso, durante a gravação será perguntado e confirmado sobre o consentimento do participantes.

O avaliador deve ser cordial e deixar os participantes bem à vontade. Deve explicar ao participante os objetivos do estudo, o sistema de interesse, o procedimento da avaliação e as questões éticas. É importante ser bem simples e direto, evitando ambiguidade quanto ao que o convidado deve fazer em consideração a tarefa que deve realizar e como deve realizar (falando em voz alta o que esta pensando e os passos que irá segui).


## E - Interpretação e Resultados dos Dados
Na atividade de interpretação e consolidação, a partir das informações quantitativas, serão construídos gráficos e tabelas com médias, porcentagens e demais indicadores necessários para identificar se as [metas de usabilidade](../../AnaliseRequisitos/Metas_usabilidade.md) estão sendo alcançadas, com base nos seguintes critérios: 

- Eficácia: Taxa de conclusão de tarefas maior ou igual a 50%.
- Eficiência: Média de 2 passos para conclusão das tarefas.

<!-- - Eficácia: Garantir que os usuários consigam completar suas tarefas de forma correta e completa. Por exemplo, aumentar em 50% a taxa de conclusão de tarefas complexas em comparação com a versão atual do OpenStreetMap.

- Eficiência: Assegurar que os usuários consigam completar suas tarefas de maneira rápida e direta. Por exemplo, reduzir em média 2 passos em cada tarefa complexa em comparação com a versão atual do OpenStreetMap.

- Segurança: Proporcionar um ambiente de uso seguro, onde os erros são minimizados e, quando ocorrem, podem ser facilmente corrigidos. Por exemplo, reduzir em 70% o tempo médio para correção de erros em comparação com a versão atual do OpenStreetMap.

- Utilidade: Oferecer funcionalidades que atendam tanto às necessidades básicas dos usuários, como também aos desejos e demandas adicionais. Por exemplo, aumentar em 30% a taxa de conclusão de tarefas por usuários menos experientes.

- Aprendizagem: Permitir que os usuários aprendam a usar o sistema de maneira intuitiva e sem esforço. Por exemplo, aumentar em 80% a aderência às diretrizes de design em comparação com a versão atual do OpenStreetMap.

- Memorização: Facilitar para que os usuários se lembrem como usar o sistema, mesmo depois de um período sem uso. Por exemplo, reduzir em 50% o uso de termos pouco comuns em comparação com a versão atual do OpenStreetMap. -->

Para a consolidação dos dados, será realizada uma categorização informações encontrados durante a interação. Descrevendo a categoria do problema, em que parte da interface ela ocorre e os impactos na usabilidade do sistema. Além de explicar suas hipóteses às possíveis causas do problema e sugerir melhorias na interface e interação. No documento de [Planejamento do Relato dos Resultados da Avaliação](./planejamento_relato.md) será mais detalhado como relatar tais resultados.


## Referência Bibliografia
> [1] Barbosa, Simone. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Cap. 11, pág. 261 a 280. Cáp. 12, pág. 301 a 304.

> [2] Preece, Jennifer, Rogers, Yvonne, e Sharp, Helen (2002). Interaction Design: Beyond Human-Computer Interaction. John Wiley & Sons.

> [3] Rubin, Jeffrey (1994). Handbook of Usability Testing: How to Plan, Design, and Conduct Effective Tests. John Wiley & Sons, Inc., USA, 1st edition.

> [4] Rubin, Jeffrey e Chisnell, Dana (2008). Handbook of Usability Testing: How to Plan, Design, and Conduct Effective Tests. Wiley, Indianapolis, IN, 2nd edition edition.

> [5] Barbosa, Simone. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Cáp. 12, pág. 302.
> 
## Bibliografia

> Barbosa, Simone. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário.


## Histórico de Versão
|    Data    | Data Prevista de Revisão | Versão |      Descrição       |                                                                Autor                                                                 |               Revisor               |
| :--------: | :----------------------: | :----: | :------------------: | :----------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------: |
| 12/06/2023 |        12/06/2023        |  1.0   | Criação do documento | [Guilherme](https://github.com/guilhermekishimoto) e [Raquel](https://github.com/raqueleucaria)| [Paulo](https://github.com/PauloVictorFS) |
| 13/06/2023 |        14/06/2023        |  2.0   | Correção e atualização| [Guilherme](https://github.com/guilhermekishimoto) e [Raquel](https://github.com/raqueleucaria)| [Paulo](https://github.com/PauloVictorFS) |
| 30/06/2023 |        01/07/2023        |  3.0   | Refatoração do artefato (DECIDE)| [Guilherme](https://github.com/guilhermekishimoto)| [Paulo](https://github.com/PauloVictorFS) |
| 02/07/2023 |        03/07/2023        |  4.0   | Inclusão das atividades do teste de usabilidade (etapas e relação com as metas de usabilidade) | [Raquel](https://github.com/raqueleucaria)| [Daniel](https://github.com/daniel-de-sousa) |



<!-- 
## D - Objetivos
O principal objetivo dessa avaliação de alta fidelidade é identificar problemas na interação e na interface no protótipo de alta fidelidade do OpenStreetMap, coletando feedback dos usuários sobre a usabilidade, experiência do usuário, acessibilidade ou comunicabilidade.

## E - Perguntas a Serem Respondidas
Levando em consideração os objetivos da avaliação, deverão ser respondidas as seguintes perguntas para que seja possível alcançar os objetivos, as perguntas são baseadas no Captítulo 11 do livro Interação Humano-Computador e Experiência o Usuário da Simone Barbosa e Bruno Silva (2021, pg. 266 e 267). As perguntas a serem respondidas são:

- O usuário consegue operar o sistema?

- O usuário atinge seus objetivos? Após cometer quantos erros?

- O usuário entende o que significa e para que serve cada elemento de interface?

- Que parte da interface e da interação deixa o usuário insatisfeito?

- Quais barreiras o usuário encontra para atingir seus objetivos?

## C - Métodos de Avaliação
O método de avaliação escolhido para a avaliação foi o de investigação por meio de entrevistas e observação, onde será realizado um teste de usabilidade pelo usuário e em seguida um integrante do grupo 4 da disciplina de IHC realizará algumas perguntas para o usuário.

## I - Questões Práticas

### Recrutamento dos Prticipantes
Os participantes serão selecionados utilizando como base o [perfil de usuário](../../AnaliseRequisitos/perfil_usuario.md) elicitado. A quantidade de participantes será de 3 pessoas, sendo esse um número adequado segundo Krug.

### Tarefas
As avaliações utilizarão as seguintes tarefas para testar a usabilidade do protótipo:

1. Buscar local;

2. Cadastrar Ponto de Referência;

3. Compartilhar localização em tempo real;

4. Cadastrar Estrada.

### Custos e Ferramentas
As avaliações devem ser feitas de modo que a equipe e os participantes (usuários) não tenham custos. Para isso, será utilizado as seguintes ferramentas:

- Computador;

- Microfone;

- Câmera;

- Microsoft Teams;

- Figama;

- Roteiro de Avaliação;

### Teste Piloto
Antes da avaliação com os participantes reais, será realizado um teste piloto com membros da equipe de IHC. O teste piloto permitirá identificar possíveis problemas no roteiro de testes e entrevistas, ajustar o tempo necessário para cada atividade e familiarizar-se com o processo de condução dos testes e entrevistas. Os resultados do teste piloto serão analisados e utilizados para aprimorar o roteiro e a abordagem geral da avaliação.

Durante o teste piloto, serão conduzidos testes de usabilidade e entrevistas simuladas, seguindo o roteiro proposto. Os participantes serão os próprios membros da equipe de IHC. O objetivo é obter feedback sobre a clareza das tarefas, o tempo necessário para realizá-las, a compreensão geral do processo de avaliação e ver se as ferramentas estão funcionando corretamente.

### Cronograma
A seguir, apresenta-se o cronograma para as atividades da avaliação do protótipo de alta fidelidade do OpenStreetMap, as quais deverão ser realizadas em um ambiente controlado, com o auxílio de um computador e um microfone para a gravação das avaliações. O cronograma está apresentado na tabela 2:

<center>

| Data       | Hora  | Local           | Avaliador | Participante  | Tarefa              |
|------------|-------|-----------------|-----------|---------------|---------------------|
| 14/06/2023 | 19:00 | Online - Microsoft Teams | Paulo       | Guilherme | Teste Piloto |
| 14/06/2023 | 20:00 | Online - Microsoft Teams | Caetano       | Participante 1 | Teste de Usabilidade e Entrevista |
| 14/06/2023 | 20:00 | Online - Microsoft Teams | Caetano       | Participante 2 | Teste de Usabilidade e Entrevista |
| 14/06/2023 | 20:00 | Online - Microsoft Teams | Caetano       | Participante 3 | Teste de Usabilidade e Entrevista |

Tabela 2 - Cronograma (Fonte: Autor, 2023)

</center>

### D - Questões Éticas
Durante todo o processo de avaliação, serão consideradas [questões éticas](../../Planejamento/Aspectos_Eticos.md), incluindo privacidade, consentimento informado e confidencialidade dos participantes. Será fornecido um [termo de consentimento](../../Planejamento/Aspectos_Eticos.md) para os participantes no qual eles concordarão em participar da avaliação e permitir a gravação das sessões, garantindo que suas informações sejam utilizadas apenas para fins acadêmicos e que sua identidade seja protegida. Além disso, durante a gravação será perguntado e confirmado sobre o consentimento do participantes.

### Roteiro de Avaliação
O avaliador deve ser cordial e deixar os participantes bem à vontade. O avaliador deve explicar ao participante os objetivos do estudo, o sistema de interesse, o procedimento da avaliação e as questões éticas. Em seguida serão realizadas as perguntas pré-teste, o teste de usabilidade e as perguntas pós-teste. A tabela 3 apresenta as perguntas pré-teste e a tabela 4 apresenta as perguntas pós-teste.

<center>

| Número | Perguntas | Opções de resposta |
| --- | --- | --- |
| 1 | Qual a sua idade? | Aberta |
| 2 | Qual o seu nível de formação acadêmica atual? | Aberta |
| 3 | Qual o seu nível de experiência com tecnologias? | [ ]Alto <br>[ ]Médio <br> [ ]Baixo |
| 4 | Qual o seu nível de experiência com o OpenStreetMap? | [ ]Alto <br>[ ]Médio <br> [ ]Baixo <br>[ ]Nenhum |

Tabela 3 - Perguntas pré-teste (Fonte: Autor, 2023)

<br>

| Número | Perguntas | Opções de resposta |
| --- | --- | --- |
| 1 | Como você descreveria a aparência visual do protótipo? | Aberta |
| 2 | Quais elementos da interface chamaram sua atenção? | Aberta |
| 3 | O protótipo é fácil de usar?  | [ ]Sim <br>[ ]Não |
| 4 | As interações e animações presentes no protótipo são adequadas e contribuem para sua experiência?  | [ ]Sim <br>[ ]Não |
| 5 | Em geral, qual foi a sua experiência ao interagir com o protótipo?  | Aberta |


Tabela 4 - Perguntas pós-teste (Fonte: Autor, 2023)

</center>


## E - Interpretação e Resultados dos Dados
Os avaliadorem interpretam os dados coletados de cada participante individualmente, buscando respostas às questões definidas no planejamento da avaliação. Em seguida, após a interpretação dos dados, os avaliadores irão discutir os resultados buscando recorrências nos resultados e assim deve-se chegar em resultados comuns, que serão documentados e poderão ser utilizados para aprimorar o protótipo do OpenStreetMap. -->

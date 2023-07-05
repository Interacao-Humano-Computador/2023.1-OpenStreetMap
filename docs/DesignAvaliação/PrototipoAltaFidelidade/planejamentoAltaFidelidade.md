# Planejamento da Avaliação do Protótipo de Alta Fidelidade do Protótipo

## Introdução
Este documento descreve o Planejamento da Avaliação de Alta Fidelidade do protótipo do OpenStreetMap, visando identificar problemas de usabilidade, coletar feedback dos usuários e validar o design proposto. O protótipo de alta fidelidade é uma versão interativa e visualmente mais próxima do produto final, permitindo uma avaliação mais precisa das funcionalidades e da experiência do usuário. A avaliação será realizada seguindo uma abordagem sistemática, utilizando técnicas específicas e considerando aspectos éticos.
## Metodologia
O Planejamento da Avaliação do Protótipo de Alta Fidelidade será conduzido através do uso do Framework DECIDE, de Preece et al. (2002)[[1](#referencia-bibliografia)], onde cada letra representa uma fase específica do planejamento. E também será usado como base as atividades básicas: Preparação, Coleta de Dados, Interpretação, Consolidação e Relato dos Resultados, propostas por Simone no livro IHC-UX[[2](#referencia-bibliografia)].

- [D](#d-objetivos)   -           Determinar os objetivos da avaliação de IHC.             
- [E](#e-explorar-perguntas)   -     Explorar as perguntas a serem respondidas com a avaliação.      
- [C](#c-metodo-de-avaliacao)   -  (*Chose*) Escolher os métodos que serão utilizados na avaliação.   
- [I ](#i-questoes-praticas-preparacao)  -    Identificar e administrar as questões práticas da avaliação.     
- [D](#d-questoes-eticas)   -          Decidir como lidar com as questões éticas.              
- [E](#e-interpretacao-e-resultados-dos-dados)   - (*Evaluate*) Interpretar e apresentar os dados da avaliação de IHC. 



## D - Objetivos
<!-- Avaliação formativa ou somativa? -->
Os objetivos são os aspectos alvos da investigação do OpenStreetMap. E são os seguintes:

- **Identificação de problemas na interação e na interface**: Identificar problemas na interação e na interface que prejudiquem a qualidade de uso do sistema, classificados em grau de impacto nocivo, frequência e fatores de qualidade (usabilidade).

## E - Explorar Perguntas
Levando em consideração os objetivos da avaliação, foram estabelecidas as seguintes perguntas:
  
  - O usuário consegue operar o sistema?
  - Ele concluiu a tarefa?
  - Quantos passos foram necessários para concluir a tarefa (cadastrar ponto, cadastrar estrada e explorar local turístico)?
  - Em quanto tempo concluiu a tarefa?
  - Quantos erros cometeu?
  - Onde esses problemas se manifestam? Qual é a gravidade desses problemas?
  - Quais barreiras o usuário encontra para atingir seus objetivos?
  - Ele desistiu da tarefa?
  - Quantas vezes apresentou ter dúvidas?
  - Ele entende o que significa e para que serve cada elemento de interface?
  - Ele vai entender o que deve fazer em seguida?
  - Que problemas de IHC dificultam ou impedem o usuário de alcançar seus objetivos?

## C - Método de Avaliação
O método de avaliação escolhido, dentro dos métodos de observação, foi o **teste de usabilidade** que visa avaliar a usabilidade de um sistema interativo a partir de experiências de uso dos seus usuários-alvo (Rubin, 1994[[3](#referencia-bibliografia)]; Rubin e Chisnell, 2008[[4](#referencia-bibliografia)]). Tendo os objetivos definidos, podemos estabelecer os critérios de avaliação, relacionados a dados mensuráveis. Assim, será observado e registrado os dados referentes ao desempenho dos participantes na realização das tarefas, suas opiniões e sentimentos ao usarem o sistema. Seguindo as atividades do teste de usabilidade, conforme a Figura 1.

<center>

![Alt text](teste-usabilidade.png)
<p>Figura 1 - Atividades do teste de usabilidade (Fonte: Simone [<a href="#referencia-bibliografia">5</a>] )</p>
</center>


## I - Questões Práticas (Preparação)

### Tarefas
As tarefas a serem executadas pelos participantes foram retiradas da [Análise de Tarefas](../../AnaliseRequisitos/analiseTarefas.md), e são:

1. [Buscar local](../../../AnaliseRequisitos/analiseTarefas/#tarefa-2-buscar-locais-desejados);
2. [Cadastrar Ponto de Referência](../../../AnaliseRequisitos/analiseTarefas/#tarefa-1-cadastrar-ponto-de-referencia);
3. [Compartilhar localização em tempo real](../../../AnaliseRequisitos/analiseTarefas/#tarefa-4-compartilhar-localizacao-em-tempo-real);
4. [Cadastrar Estrada](../../../AnaliseRequisitos/analiseTarefas/#tarefa-3-adicionar-uma-nova-estrada).

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
A coleta de dados consiste no questionário pré-teste, pós-teste (Tabela 1 e 2) e no registro/respostas as perguntas mensuráveis. Além da gravação do teste, via Teams, com o participante compartilhando sua tela e sua câmera.

<details>
<summary>Questionário Pré-Teste (Tabela 1)</summary>
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

<p>Tabela 1 - Perguntas pré-teste (Fonte: Autor, 2023)</p>
</center>
</details>


<details>
<summary>Questionário Pós-Teste (Tabela 2)</summary>
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


<p>Tabela 2 - Perguntas pós-teste (Fonte: Autor, 2023)</p>
</center>
</details>



### Cronograma
A seguir, apresenta-se o cronograma para as atividades da avaliação do protótipo de alta fidelidade do OpenStreetMap, as quais deverão ser realizadas em um ambiente controlado, com o auxílio de um computador e um microfone para a gravação das avaliações. A equipe deixou a cargo da integrante [Raquel](https://github.com/raqueleucaria) o desenvolvimento de todos os protótipos, referente a cada tarefa que será testada. O cronograma está apresentado na tabela 3:

<center>

| Data       | Hora  | Local           | Avaliador | Participante  | Tarefa              |
|------------|-------|-----------------|-----------|---------------|---------------------|
| 23/06/2023 | 19:00-19:30 | Online - Microsoft Teams | [Raquel](https://github.com/raqueleucaria)       | - | Teste Piloto |
| 26/06/2023 | 09:00-09:30 | UnB FGA |[Daniel](https://github.com/daniel-de-sousa)| <span style="color: brown;">Participante 1</span> | Testes de Usabilidade 1 |
| 26/06/2023 | 09:40-10:10 | UnB FGA |[Guilherme](https://github.com/guilhermekishimoto)| <span style="color: brown;">Participante 2</span> | Testes de Usabilidade 2 |
| 26/06/2023 | 10:30-11:00 | UnB FGA | [Caetano](https://github.com/caeslucio)| <span style="color: brown;">Participante 3</span> | Testes de Usabilidade 3 |
| 26/06/2023 | 11:10-11:40 | UnB FGA | [Paulo](https://github.com/PauloVictorFS)| <span style="color: brown;">Participante 4</span> | Testes de Usabilidade 4 |


Tabela 3 - Cronograma (Fonte: Autor, 2023)

</center>

## D - Questões Éticas
Durante todo o processo de avaliação, serão consideradas [questões éticas](../../Planejamento/Aspectos_Eticos.md), incluindo privacidade, consentimento informado e confidencialidade dos participantes. Será fornecido um [termo de consentimento](../../../Planejamento/Aspectos_Eticos/#termo-de-consentimento) para os participantes no qual eles concordarão em participar da avaliação e permitir a gravação das sessões, garantindo que suas informações sejam utilizadas apenas para fins acadêmicos e que sua identidade seja protegida. Além disso, durante a gravação será perguntado e confirmado sobre o consentimento do participantes.

O avaliador deve ser cordial e deixar os participantes bem à vontade. Deve explicar ao participante os objetivos do estudo, o sistema de interesse, o procedimento da avaliação e as questões éticas. É importante ser bem simples e direto, evitando ambiguidade quanto ao que o convidado deve fazer em consideração a tarefa que deve realizar e como deve realizar (falando em voz alta o que esta pensando e os passos que irá segui).

## E - Interpretação e Resultados dos Dados
Na atividade de interpretação e consolidação, a partir das informações quantitativas, serão construídos gráficos e tabelas com médias, porcentagens e demais indicadores necessários para identificar se as [metas de usabilidade](../../AnaliseRequisitos/Metas_usabilidade.md) estão sendo alcançadas, com base nas faixas de valores almejadas, da seguinte maneira:

- Tarefas concluídas com sucesso (%) - 100%
- Número de passos por cadastro de ponto (média) - 3 passos
- Número de passos por cadastro de estrada (média) - 3 passos
- Número de erros por interação (média) - 0.5 erros
- Tempo para concluir com sucesso (minutos) 1.5 minutos
- Número de desistências por tarefa (média) - 0 desistências
- Números de dúvidas ao acessar o sistema (média) - 1.5 dúvidas

Para a consolidação dos dados, será realizada uma categorização das informações encontrados durante a interação. Descrevendo a categoria do problema, em que parte da interface ela ocorre e os impactos na usabilidade do sistema. Além de explicar suas hipóteses às possíveis causas do problema e sugerir melhorias na interface e interação. No documento de [Planejamento do Relato dos Resultados da Avaliação](./planejamento_relato.md) será mais detalhado como relatar tais resultados.


## Referência Bibliografia
> [1] Preece, Jennifer, Rogers, Yvonne, e Sharp, Helen (2002). Interaction Design: Beyond Human-Computer Interaction. John Wiley & Sons.

> [2] Barbosa, Simone. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Cap. 11, pág. 261 a 280. Cáp. 12, pág. 301 a 304.

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

# Protótipo de Papel

## Introdução 
O Protótipo de Papel é uma forma de representação da interface e suas interações, com um nível mais abstrato da informação. Utilizamos esse material para o desenvolvimento do Teste de Usabilidade do OpenStreetMap.

## Teste de Usabilidade
O teste de usabilidade é um método de observação que visa avaliar a usabilidade de um sistema interativo a partir de experiências de uso dos seus usuários-alvo (Rubin, 1994[[1](#referencia-bibliografia)]; Rubin e Chisnell, 2008[[2](#referencia-bibliografia)]). E possui as determinadas etapas, conforme a Figura 1. Assim, o Protótipo de Baixa Fidelidade apresentado aqui, corresponde ao material que irá representar o sistema e ser avaliado no [Planejamento da Avaliação do Protótipo de Papel](./planejamento_Prototipopapel.md).

<center>

![Alt text](../PrototipoAltaFidelidade/teste-usabilidade.png)
<p>Figura 1 - Atividades do teste de usabilidade (Fonte: Simone [<a href="#referencia-bibliografia">3</a>] )</p>
</center>

## Preparação 
Os protótipos seguem o [guia de estilo](../../AnaliseRequisitos/guia-de-estilo.md), para delimitar as interfaces de forma mais concreta. Além, é claro, das  [tarefas definidas](../planejamento_Prototipopapel/#tarefas) durante a preparação do teste de usabilidade, que são:

1. [Buscar local](#buscar-local);
2. [Cadastrar Ponto de Referência](#cadastrar-ponto-de-referencia);
3. [Compartilhar localização em tempo real](#compartilhar-localizacao-em-tempo-real);
4. [Cadastrar Estrada](#cadastrar-estrada);
5. [Explorar local turístico](#explorar-local-turistico);

<!-- 1. [Buscar local](../../../AnaliseRequisitos/analiseTarefas/#tarefa-2-buscar-locais-desejados);
1. [Cadastrar Ponto de Referência](../../../AnaliseRequisitos/analiseTarefas/#tarefa-1-cadastrar-ponto-de-referencia);
2. [Compartilhar localização em tempo real](../../../AnaliseRequisitos/analiseTarefas/#tarefa-4-compartilhar-localizacao-em-tempo-real);
3. [Cadastrar Estrada](../../../AnaliseRequisitos/analiseTarefas/#tarefa-3-adicionar-uma-nova-estrada);
4. [Explorar local turístico](../../../AnaliseRequisitos/analiseTarefas/#tarefa-5-explorar-local-turistico). -->



## Protótipos de Papel

Durante a produção dos protótipos, foi criado o protótipo 0, conforme as Figuras 2 a 7 e os Vídeos 1 e 2. O qual representada a tarefa de buscar local do site OpenStreetMap fugindo do objetivo do teste de usabilidade, pois não apresenta a alternativa de design feitas pelo grupo e possui outras tarefas dentro do protótipo (como realizar login e buscar local). Dessa forma, os demais protótipos foram corrigidos e adequados. Porém, serve de comparação para ver a eficiência das novas propostas.

<style>
  .no-border {
    border-collapse: collapse;
  }
  .no-border th,
  .no-border td {
    border: none;
  }
</style>

<details>
<summary>Protótipo 0</summary>
<center>

<table class="no-border">
  <thead>
    <tr>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><img src="../../../assets/prototipo-papel/1.jpg" width=600px></img></td>
      <td><img src="../../../assets/prototipo-papel/2.jpg" width=600px></img></td>
    </tr>
    <tr>
      <td align="center">Figura 2: Janela principal (Fonte: Raquel, 2023).</td>
      <td align="center">Figura 3: Janela login (Fonte: Raquel, 2023).</td>
    </tr>
    <tr>
      <td></br></td>
      <td></br></td>
    </tr>
    <tr>
      <td><img src="../../../assets/prototipo-papel/3.jpg" width=600px></img></td>
      <td><img src="../../../assets/prototipo-papel/4.jpg" width=600px></img></td>
    </tr>
    <tr>
      <td align="center">Figura 4: Mapas (Fonte: Raquel, 2023)</td>
      <td align="center">Figura 5: Barras laterais (Fonte: Raquel, 2023)</td>
    </tr>
    <tr>
      <td></br></td>
      <td></br></td>
    </tr>
  </tbody>
</table>

<img src="../../../assets/prototipo-papel/5.jpg" width=500px></img>
<p> Figura 6: Componentes (Fonte: Raquel, 2023).</p>

<img src="../../../assets/prototipo-papel/6.jpg" width=500px></img>
<p> Figura 7: Inputs (Fonte: Raquel, 2023).</p>

<table class="no-border">
  <thead>
    <tr>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><iframe width="650" height="405" src="https://www.youtube.com/embed/diwnWaYMBiw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></td>
      <td><iframe width="650" height="405" src="https://www.youtube.com/embed/ns1IIUtlCeA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></td>
    </tr>
    <tr>
      <td align="center">Vídeo 1: Teste Piloto (Fonte: Raquel, 2023).</td>
      <td align="center">Vídeo 2: Teste de Usabilidade (Fonte: Raquel, 2023).</td>
  </tbody>
</table>

</center>

<h4>Perguntas e Respostas</h4>
Temos as seguintes respostas do entrevistado, na Tabela 1.
<center>
<table>
  <tr>
    <th>ID</th>
    <th>Pergunta</th>
    <th>Resposta</th>
  </tr>
  <tr>
    <td>P01</td>
    <td>Você consegue entender o propósito e funcionalidade do protótipo de papel do OpenStreetMap?</td>
    <td>Sim, o protótipo de papel visa testar uma implementação que mesmo sem animações e highlights de botões executaria as tarefas desejadas.</td>
  </tr>
  <tr>
    <td>P02</td>
    <td>As informações apresentadas no protótipo de papel são claras e fáceis de entender?</td>
    <td>No geral sim, o protótipo em si estava bastante claro, só tive algumas dificuldades em relação a apresentação de salvar.</td>
  </tr>
  <tr>
    <td>P03</td>
    <td>Você encontrou alguma dificuldade específica ao interagir com o protótipo de papel?</td>
    <td>Tive uma certa dificuldade em realizar o salvamento do ponto que eu estava cadastrando, e também em relação ao botão de editar ponto de referência.</td>
  </tr>
  <tr>
    <td>P04</td>
    <td>O protótipo de papel apresenta um fluxo lógico de interações?</td>
    <td>Sim</td>
  </tr>
  <tr>
    <td>P05</td>
    <td>O protótipo de papel fornece informações relevantes para a realização das tarefas?</td>
    <td>Sim</td>
  </tr>
  <tr>
    <td>P06</td>
    <td>O protótipo de papel apresenta tarefas condizentes com a realidade?</td>
    <td>Sim</td>
  </tr>
  <tr>
    <td>P07</td>
    <td>Você conseguiu encontrar e utilizar as funcionalidades necessárias para alcançar seu objetivo?</td>
    <td>Sim</td>
  </tr>
</table>

<p align="center"> Tabela 1: Respostas - Entrevista (Fonte: Autor).</p>
</center>

<h4>Conclusões</h4>
- Botão de editar não ficou a vista;<br>
- Botão de salvar ficou com o ícone ambíguo;<br>
- Local do botão de salvar não muito bom;<br>
- Os botão de criação de ponto de referência ocultos, tem uma etapa a mais de criar em edição.<br>

</details>

### Buscar Local

### Cadastrar Ponto de Referência
O protótipo da [Tarefa 2 - Cadastrar Ponto de Referência](../../../AnaliseRequisitos/analiseTarefas/#tarefa-2-buscar-locais-desejados) está representado nas Figuras 8 a 14.


<center>

<table class="no-border">
  <thead>
    <tr>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><img src="../img/ponto1.jpg" width=600px></img></td>
      <td><img src="../img/ponto2.jpg" width=600px></img></td>
    </tr>
    <tr>
      <td align="center">Figura 8: Janela principal, edição (Fonte: Raquel, 2023, 2023).</td>
      <td align="center">Figura 9: Seleção da edição (Fonte: Raquel, 2023, 2023).</td>
    </tr>
    <tr>
      <td></br></td>
      <td></br></td>
    </tr>
    <tr>
      <td><img src="../img/ponto3.jpg" width=600px></img></td>
      <td><img src="../img/ponto4.jpg" width=600px></img></td>
    </tr>
    <tr>
      <td align="center">Figura 10: Seleção do tipo do elemento (Fonte: Raquel, 2023)</td>
      <td align="center">Figura 11: Seleção do tipo do elemento (Fonte: Raquel, 2023)</td>
    </tr>
    <tr>
    <tr>
      <td></br></td>
      <td></br></td>
    </tr>
    <tr>
      <td><img src="../img/ponto5.jpg" width=600px></img></td>
      <td><img src="../img/ponto6.jpg" width=600px></img></td>
    </tr>
    <tr>
      <td align="center">Figura 12: Informações do ponto (Fonte: Raquel, 2023)</td>
      <td align="center">Figura 13: Comentário da edição (Fonte: Raquel, 2023)</td>
    </tr>
    <tr>
      <td></br></td>
      <td></br></td>
    </tr>
  </tbody>
</table>

<img src="../img/ponto7.jpg" width=500px></img>
<p> Figura 14: Pop-up (Fonte: Raquel, 2023).</p>



</center>


### Compartilhar localização em tempo real
O protótipo da [Tarefa 3 - Cadastrar Ponto de Referência](../../../AnaliseRequisitos/analiseTarefas/#tarefa-2-buscar-locais-desejados) está representado nas Figuras 15 a 17.


<center>

<table class="no-border">
  <thead>
    <tr>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><img src="../img/Tela.png" width=600px></img></td>
      <td><img src="../img/Centro.png" width=600px></img></td>
    </tr>
    <tr>
      <td align="center">Figura 15: Janela principal, edição (Fonte: Daniel, 2023).</td>
      <td align="center">Figura 16: Zoom na localização (Fonte: Daniel, 2023).</td>
    </tr>
  </tbody>
</table>

<img src="../img/Elementos.png" width=200px></img>
<p> Figura 17: Elemento de Seleção, Marcador e Link (Fonte: Daniel, 2023)</p>

</center>

### Cadastrar Estrada

### Explorar local turístico

Outro protótipo que será apresentados é o referente a [Tarefa 5 - Explorar local turístico](../../../AnaliseRequisitos/analiseTarefas/#tarefa-5-explorar-local-turistico) que esta representado nas Figuras 18, 19, 20 e 21.

<table class="no-border">
  <thead>
    <tr>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><img src="../../../assets/prototipo-papel/7.png" width=600px></img></td>
      <td><img src="../../../assets/prototipo-papel/8.png" width=600px></img></td>
    </tr>
    <tr>
      <td align="center">Figura 18: Janela principal (Fonte: Guilherme, 2023, 2023).</td>
      <td align="center">Figura 19: Lista locais turísticos (Fonte: Guilherme, 2023).</td>
    </tr>
    <tr>
      <td></br></td>
      <td></br></td>
    </tr>
    <tr>
      <td><img src="../../../assets/prototipo-papel/9.png" width=600px></img></td>
      <td><img src="../../../assets/prototipo-papel/10.png" width=600px></img></td>
    </tr>
    <tr>
      <td align="center">Figura 20: Local turístico selecionado (Fonte: Guilherme, 2023)</td>
      <td align="center">Figura 21: 10: Rota (Fonte: Guilherme, 2023)</td>
    </tr>
  </tbody>
</table>

</center>


## Teste Piloto
Uma das etapas finais da preparação é a realização do teste piloto. Ele é realizado com o objetivo de identificar possíveis problemas nos protótipos, assegurar que o protótipo será disponibilizado para o participante, além de verificar a possibilidade de realizar o teste no ambiente programado. Os seus resultados serão utilizados para aprimorar o roteiro e a abordagem geral. No [Relato dos Resultados do Protótipo de Papel](../relatos/#teste-piloto) será apresentado o teste piloto realizado.

## Referência Bibliografia

> [1] Rubin, Jeffrey (1994). Handbook of Usability Testing: How to Plan, Design, and Conduct Effective Tests. John Wiley & Sons, Inc., USA, 1st edition.

> [2] Rubin, Jeffrey e Chisnell, Dana (2008). Handbook of Usability Testing: How to Plan, Design, and Conduct Effective Tests. Wiley, Indianapolis, IN, 2nd edition edition.

> [3] BARBOSA, Simone. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Cáp. 12, pág. 302.


## Bibliografia

> BARBOSA, Simone. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. Interação Humano-Computador e Experiência do usuário, 2021.

> BARBOSA, Simone; SILVA, Bruno. Interação Humano-Computador, 1a. Edição, Editora Campus, 2010.


## Histórico de Versão
| Data | Data Prevista de Revisão | Versão | Descrição | Autor | Revisor |
| :-: | :-: | :-: | :-: | :-: | :-: 
| 12/06/2023 |        13/06/2023        |  1.0   | Criação inicial do documento | [Raquel](https://github.com/raqueleucaria) | [Caetano](https://github.com/caeslucio) |
| 03/07/2023 | 04/07/2023 | 2.0 | Adequação ao teste de usabilidade | [Raquel](https://github.com/raqueleucaria)|  [Caetano](https://github.com/caeslucio) |
| 05/07/2023 | 05/07/2023 | 2.1 | Adição de mais um Protótipo | [Daniel](https://github.com/daniel-de-sousa)| [Raquel](https://github.com/raqueleucaria) |
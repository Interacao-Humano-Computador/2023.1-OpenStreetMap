# Introdução
Ao longo do projeto, percebemos que algumas formas de interação com a página de documentação gerada a partir do MkDocs, disponível através da GitPage, não tinham o efeito desejado ou que poderia melhorar a usabilidade como um todo. Segue as melhorias com utilização de funções do MkDocs que não estavam em outros projetos pesquisados, as quais estão descritas a seguir:

## Barra lateral ancorada

```
theme:
  features:
    - toc.follow
``` 

- Faz com que a barra lateral seja rolada automaticamente para que o menu da sessão ativa esteja sempre visível.

## Carregamento instantâneo

```
theme:
  features:
    - navigation.instant
```

- Quando o carregamento instantâneo está ativado, os cliques em todos os links internos serão interceptados e despachados via XHR sem recarregar totalmente a página.
- A página resultante é analisada e injetada e todos os manipuladores de eventos e componentes são religados automaticamente, ou seja, o Material for MkDocs agora se comporta como um aplicativo de página única.


## Botão de voltar ao topo

```
theme:
  features:
    - navigation.top
```

- Um botão voltar ao topo será mostrado quando o usuário rolar a página para baixo, para rolar para o topo da página novamente. Ele é renderizado centralizado e logo abaixo do cabeçalho.

## Tabelas ordenáveis

```
extra_javascript:
  - https://unpkg.com/tablesort@5.3.0/dist/tablesort.min.js
  - javascripts/tablesort.js
```

- docs/javascripts/tablesort.js

```
document$.subscribe(function() {
  var tables = document.querySelectorAll("article table:not([class])")
  tables.forEach(function(table) {
    new Tablesort(table)
  })
})
```

- Agora os dados das tabelas são classificáveis, de acordo com a coluna selecionada. É integrado nativamente ao Material for MkDocs e também funcionará com carregamento instantâneo.

# Referências

> Setting up navigation - Material for MkDocs. https://squidfunk.github.io/mkdocs-material/setup/setting-up-navigation/

> MkDocs: <a>https://www.mkdocs.org/</a>

> MkDocs Material: <a>https://squidfunk.github.io/mkdocs-material/</a>


## Histórico de Versão
| Data | Data Prevista de Revisão | Versão | Descrição | Autor | Revisor |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 27/06/2023 | 28/06/2023 | 1.0 | Criação do documento | [Caetano](https://github.com/caeslucio) | [Raquel](https://github.com/raqueleucaria) |
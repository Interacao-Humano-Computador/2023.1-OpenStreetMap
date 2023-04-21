# MkDocs 

<h4>Uma pequena introdução sobre MkDocs</h4>

## Como começar?

Instale o MkDocs

```
pip install mkdocs
```

Se você estiver utilizando o sistema operacional Linux e ocorrer o problema a baixo, tente instalá-lo utilizando o sudo.

```
 Defaulting to user installation because normal site-packages is not writeable
```

```
 sudo pip install mkdocs
```

## Inicializando o repositório

Abra o terminal na pasta escolhida e execute o seguinte comando:

```
mkdosc new nome_do_projeto
```

Vai aparecer os arquivos:

```
mkdosc.yml
docs
	-index.md
```
## Criando as Páginas

Para fazer as páginas do seu projeto basta criar novos arquivos na pasta "docs" e refenciá-los no arquivo mkdocs.yml. Por exemplo, se criarmos um arquivo chamado "teste.md" na pasta docs, o mkdocs.yml deve estar da seguinte forma:

```
site_name: My Docs

nav: 
    - Home: teste.md
```

Nesse caso, teremos uma nova aba com o nome "Home" que nos mostrará o conteúdo do aquivo teste.md

## Como estilizar? 

Nossa dica é utilizar o pacote MkDocs Material. Para isso, basta instalá-lo no seu projeto com o seguinte comando:

```
pip install mkdocs-material
```

Esse pacote vai te dar diversas opções de estilização como: mudar as cores da página, acrescentar um link para o github, estruturar a sidebar, acrescentar a opção dark mode.
Para ver as opções de estilização que a biblioteca fornece acesse [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/).

## Como rodar? 

Abra o terminal dentro do seu projeto e rode o seguinte comando:

```
mkdocs serve
```

Se seu projeto não tiver nenhum erro de sintaxe, sei projeto estará rodando na porta 8000.

## Como deployar? 

Para deployar seu projeto, primeiro precisamos gerar o html da página para que seja possível utilizar o github pages. Para isso, vamos utilizar o seguinte comando:

```
mkdocs build
```

Vai aparecer um pasta "site" na raiz do projeto.

Em seguida, para deployar basta rodar o seguinte comando e sua página já estará disponível no github pages:

```
mkdocs gh-deploy
```

Obs.: Esse comando criará uma branch "gh-deploy" para realizar o deploy.

# Referências

> MkDocs: <a>https://www.mkdocs.org/</a>

> MkDocs Material: <a>https://squidfunk.github.io/mkdocs-material/</a>

## Histórico de Versão
|    Data    | Data Prevista de Revisão | Versão |      Descrição       |                                                                Autor                                                                 |               Revisor               |
| :--------: | :----------------------: | :----: | :------------------: | :----------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------: |
| 16/04/2023 |        16/04/2023        |  1.0   | Criação do documento | [Carla](https://github.com/ccarlaa) | [Daniel](https://github.com/PauloVictorFS) |
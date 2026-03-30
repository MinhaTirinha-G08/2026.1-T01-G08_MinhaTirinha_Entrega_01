# MinhaTirinha

Repositório do Grupo 08 para a disciplina de **Arquitetura e Desenho de Software** — Turma 01, semestre 2026.1.

## Sobre o Projeto

**MinhaTirinha** é um aplicativo interativo de histórias em formato de gibi, no qual o usuário participa ativamente da narrativa por meio da **pintura dos cenários**. A experiência é guiada e condicionada às interações do usuário: os balões de fala ficam ocultos e só são revelados após a conclusão da pintura do respectivo quadrinho.

O aplicativo oferece uma galeria de histórias organizadas por temas (infantil, humor, tecnologia, educação), com suporte a progresso salvo e revisitação de histórias concluídas.

## Tecnologia

A geração do site de documentação é realizada utilizando o [docsify](https://docsify.js.org/).

```shell
"Docsify generates your documentation website on the fly. Unlike GitBook, it does not generate static html files. Instead, it smartly loads and parses your Markdown files and displays them as a website. To start using it, all you need to do is create an index.html and deploy it on GitHub Pages."
```

### Instalando o docsify

Execute o comando:

```shell
npm i docsify-cli -g
```

### Executando localmente

Para iniciar o site localmente, utilize o comando:

```shell
docsify serve ./docs
```

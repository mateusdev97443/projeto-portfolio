# Portfólio Front-end — Mateus Ernandes

Este é o meu projeto de portfólio pessoal, criado para reunir um pouco da minha evolução como desenvolvedor front-end em formação.

A ideia desse projeto foi construir uma página simples, organizada e com visual moderno, usando HTML e CSS. Durante o desenvolvimento, trabalhei a estrutura do site, a imagem de capa, as seções principais, os cards de projetos e a responsividade para diferentes tamanhos de tela.

## Sobre o projeto

O portfólio foi criado para apresentar minhas informações, minhas habilidades e alguns projetos que estou desenvolvendo durante meus estudos.

Ele ainda pode receber melhorias com o tempo, mas já representa uma base importante para praticar organização de código, estrutura de páginas e construção de interfaces.

## O que tem na página

- Menu de navegação
- Capa com imagem de fundo
- Apresentação profissional
- Seção sobre mim
- Lista de habilidades
- Área de projetos
- Formulário de contato
- Layout adaptável para telas menores

## Tecnologias usadas

- HTML5
- CSS3
- Flexbox
- CSS Grid
- Media Queries
- Live Server

## Estrutura do projeto

```txt
pagina-portfolio/
├── index.html
├── README.md
└── assets/
    ├── css/
    │   └── style.css
    └── img/
        ├── banner.png
        ├── img1.jpg
        └── image.png
```

## Organização dos arquivos

O arquivo principal do projeto é o `index.html`.

O CSS fica dentro da pasta:

```txt
assets/css/style.css
```

As imagens ficam dentro da pasta:

```txt
assets/img/
```

A imagem usada na capa do site está neste caminho:

```txt
assets/img/banner.png
```

Como o CSS está dentro da pasta `css`, o caminho usado para chamar a imagem de fundo foi:

```css
url("../img/banner.png")
```

Esse foi um dos pontos importantes do projeto, porque me ajudou a entender melhor como funcionam os caminhos entre pastas dentro de um site.

## O que aprendi fazendo esse projeto

Durante esse projeto, pratiquei bastante a organização de uma página real.

Aprendi melhor como separar os arquivos do projeto, como chamar imagens pelo CSS, como montar seções com HTML semântico e como ajustar o layout para funcionar melhor em telas diferentes.

Também tive que corrigir alguns detalhes no caminho da imagem da capa, o que foi importante para entender na prática a diferença entre abrir o projeto direto pelo arquivo e abrir usando o Live Server.

## Como visualizar

Para abrir o projeto da forma correta, use o Live Server no VS Code.

O endereço no navegador deve ficar parecido com:

```txt
http://127.0.0.1:3000/
```

Abrir direto pelo arquivo `file://` pode fazer alguns recursos não carregarem corretamente, então o ideal é sempre usar o Live Server durante o desenvolvimento.

## Status

Projeto em desenvolvimento.

A estrutura principal já está pronta, mas ainda posso melhorar algumas partes, adicionar novos projetos, ajustar detalhes visuais e futuramente incluir JavaScript.

## Autor

Mateus Ernandes

Desenvolvedor front-end em formação, estudando HTML, CSS, responsividade e boas práticas para criar páginas modernas, organizadas e funcionais.

# GCSI-Teste-Commits
# Alteração de Imagem Web

Projeto desenvolvido com **HTML, CSS e JavaScript** com o objetivo de demonstrar a alteração dinâmica de uma imagem através de uma interação do usuário.

Ao clicar no botão **"Mudar Imagem"**, a imagem exibida na página é substituída por outra imagem utilizando JavaScript.

## Funcionalidades

- Exibição de uma imagem inicial.
- Botão para alterar a imagem.
- Alteração dinâmica do atributo `src` da imagem através do JavaScript.
- Efeito visual de `hover` no botão.
- Interface estilizada com CSS.
- Utilização de fonte personalizada através de `@font-face`.

## Tecnologias utilizadas

- **HTML5** — Estrutura da página.
- **CSS3** — Estilização, layout, fonte personalizada e efeitos visuais.
- **JavaScript** — Lógica responsável pela alteração da imagem.

## Estrutura do projeto

```text
GCSI-Teste-Commits/
│
├── images/
│   ├── image1.png
│   └── image2.png
│
├── fonts/
│   └── BricolageGrotesque_24pt_SemiCondensed-Regular.ttf
│
├── index.html
├── style.css
├── script.js
└── README.md
```

## Funcionamento

A página inicia exibindo `image1.png`.

O JavaScript identifica o botão e a imagem através dos seus respectivos IDs:

```javascript
const botao = document.getElementById("botao");
const imagem = document.getElementById("image");
```

Quando o usuário clica no botão, o atributo `src` da imagem é alterado:

```javascript
botao.addEventListener("click", function() {
    imagem.src = "images/image2.png";
});
```

Dessa forma, a imagem é substituída sem a necessidade de recarregar a página.

## Como executar

Não é necessário instalar dependências ou configurar um servidor.

1. Baixe ou clone o repositório.
2. Abra a pasta do projeto.
3. Execute o arquivo `index.html` em um navegador.
4. Clique no botão **"Mudar Imagem"** para testar a funcionalidade.

### Clonando o repositório

```bash
git clone <URL_DO_REPOSITORIO>
```

Depois, abra o arquivo `index.html` no navegador.

## Interface

A aplicação possui uma estrutura simples composta por:

- Uma área central contendo a imagem.
- Um botão localizado abaixo da imagem.
- Alteração visual do botão quando o cursor passa sobre ele.

## Objetivo do projeto

Este projeto foi desenvolvido como um exercício prático de desenvolvimento **Front-End**, trabalhando principalmente conceitos básicos de:

- Manipulação do DOM;
- Eventos em JavaScript;
- Alteração de propriedades de elementos HTML;
- Seletores CSS;
- Flexbox;
- Estilização de componentes;
- Organização de arquivos em um projeto web.

## Licença

Este projeto foi desenvolvido para fins educacionais.
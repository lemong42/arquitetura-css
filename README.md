<h1 align="center">Arquitetura CSS</h1>

![GitHub Org's stars](https://img.shields.io/github/stars/lemong42/arquitetura-css?style=social)

![image](https://user-images.githubusercontent.com/90742197/185270437-d58faf2c-bf7c-47f9-ba1b-c477feb3fa61.png)

<img alt="Shield de status finalizado" src="http://img.shields.io/static/v1?label=STATUS&message=FINALIZADO&color=green&style=for-the-badge">
<img alt="Shield de last update no dia 17.08.2022" src="http://img.shields.io/static/v1?label=LAST%20UPDATE&message=27.07.2022&color=blue&style=for-the-badge">

Esse projeto foi desenvolvido para aprofundar meus conhecimentos em CSS e na arquitetura do CSS. O site desenvolvido visa divulgar receitas simples e rápidas para os usuários. Porém, apesar de ser visualmente simples, seu código está muito bem organizado, estruturado e padronizado para fácil edição.

## Funcionalidades do projeto

`Funcionalidade 1`: imagens ilustrativas importadas pelo CSS.

```
.pessoa__imagem {
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    border-radius: 100%;
    height: 300px;
    margin: 0 auto;
    width: 300px;
}

.pessoa__imagem--roberta {
    background-image: url('../../img/pessoas/roberta.jpg');
}

.pessoa__imagem--marcela {
    background-image: url('../../img/pessoas/marcela.jpg');
}

.pessoa__imagem--andreia {
    background-image: url('../../img/pessoas/andreia.jpg');
}
```

`Funcionalidade 2`: diferentes arquivos CSS para cada section do código, fazendo com que a edição de uma parte específica seja de fácil acesso.

![image](https://user-images.githubusercontent.com/90742197/185270886-5733f476-56dc-4569-9b0d-f82e94bc5b90.png)

`Funcionalidade 3`: estilos organizados por ordem alfabética em todos os arquivos CSS.

```
.banner__titulo {
    color: #fdfdfd;
    font-family: Pacifico, cursive;
    font-size: 5.0625rem;
    left: 50%;
    position: absolute;
    text-align: center;
    text-shadow: 0 4px 4px rgba(0, 0, 0, 0.75);
    top: 50%;
    transform: translate(-50%, -50%);
    width: 100%;
}
```

`Funcionalidade 4`: design responsivo.

### Projeto web
<img alt="Print da tela inicial do site na versão web" src="https://user-images.githubusercontent.com/90742197/185270193-e15aaa19-3cb7-4ba8-9fbb-e6896ffb4ec6.png">

### Projeto mobile
<img width=25% align="top" alt="Print da tela inicial do site na versão mobile" src="https://user-images.githubusercontent.com/90742197/185272873-06e19127-12a4-47e4-a76e-3290bf43b492.png"><img width=25% align="top" alt="Print da tela inicial do site na versão mobile" src="https://user-images.githubusercontent.com/90742197/185272954-b902a173-d3a3-468b-a079-5815d55b794c.png"><img width=25% align="top" alt="Print da tela inicial do site na versão mobile" src="https://user-images.githubusercontent.com/90742197/185272997-ee64052d-117f-4e6e-8e7b-86660652ff49.png"><img width=25% align="top" alt="Print da tela inicial do site na versão mobile" src="https://user-images.githubusercontent.com/90742197/185273018-ff646ce7-cf6a-449d-b5a8-92f5847ed7c1.png">

### Tecnologias utilizadas 

<div>
  <img align="center" alt="logo-HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" alt="logo-CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
</div>

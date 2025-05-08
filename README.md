# Maison Rosée: Explorando Bootstrap e Tailwind CSS 🌹

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge)

Este projeto foi desenvolvido como um *desafio* da disciplina de Desenvolvimento Web I no curso de Tecnologia em Desenvolvimento de Software Multiplataforma da Fatec Jahu. O objetivo principal foi explorar o máximo possível de *componentes Bootstrap 5* e, em seguida, criar uma página visualmente idêntica utilizando *Tailwind CSS* para fins comparativos, tudo construído com *HTML, CSS* e *JavaScript* puros.

## 📜 Índice

- [🌸 Sobre o Projeto](#-sobre-o-projeto)
- [📌 Desafio](#-desafio)
- [✨ Funcionalidades Implementadas](#-funcionalidades-implementadas)
- [🛠️ Tecnologias Utilizadas](#️-tecnologias-utilizadas)
- [📂 Estrutura do Projeto](#-estrutura-do-projeto)
- [🚀 Como Executar](#-como-executar)
- [📸 Screenshots](#-screenshots)
- [👩‍💻 Autora](#-autora)

## 🌸 Sobre o projeto

O Maison Rosée é um site fictício de uma floricultura de luxo. Ele serve como base para demonstrar a *aplicação* e as *diferenças* entre duas abordagens populares de estilização e componentização no *desenvolvimento front-end*: Bootstrap, um framework rico em componentes prontos, e Tailwind CSS, um framework utility-first.

A proposta foi criar uma experiência de usuário elegante e funcional, explorando diversos componentes interativos em ambas as tecnologias.

## 📌 Desafio

-   Implementar uma interface *responsiva e interativa*.
-   Utilizar ao máximo os componentes do *Bootstrap 5* (Navbar, Carousel, Modals, Accordion, etc.).
-   Recriar a mesma interface utilizando a abordagem utility-first do *Tailwind CSS*.
-   *Comparar* as metodologias, desafios e resultados de ambas as tecnologias.

## ✨ Funcionalidades Implementadas

- **Design Responsivo:** Adaptação para visualização em desktops, tablets e smartphones.
- **Navbar:** Com *Offcanvas* para navegação e *Dropdown Button* para opções de perfil.
- **Seção Hero:** *Carrosel* de destaques interativos no Bootstrap e *Card Estático* no Tailwind.
- **Letreiro (Scrolling Banner):** Texto animado que se move na horizontal infinitamente, exibindo uma mensagem.
- **Cards de Produtos:** Exibição básica de produtos com botão para abrir um modal com mais detalhes.
- **Modais:** Janelas pop-up para exibir informações detalhadas dos produtos (e ao fim do site, para o formulário de pedido personalizado).
- **Seção de FAQ:** Utilizando o componente *Accordion* para exibir perguntas e respostas.
- **Seção de "Histórias":** Com funcionalidade de *Multi-collapse* para depoimentos de clientes.
- **Seção de Pedido Personalizado:** Permite que o usuário inicie a solicitação de um buquê personalizado. Abre um *modal de formulário*.
- **Formulário de Pedido Personalizado:** Localizado dentro de um modal, permitindo ao usuário customizar seu buquê. Utiliza de componentes como *Input*, *Select*, *Range*, *Switch*, *Checkbox Group* e *Textarea*.
- **Footer:** Com informações sobre o projeto e links para as redes sociais.

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estrutura semântica das páginas.
- **CSS3:** Estilizações customizadas (principalmente no `css/style.css` para a versão Bootstrap) e animações.
- **JavaScript (Vanilla):** Para toda a interatividade dos componentes (modais, offcanvas, accordion, etc.) em Bootstrap.
- **Bootstrap 5.3.5:** Utilizado extensivamente na página `index.html`.
- **Tailwind CSS (via CDN):** Utilizado na página `tailwind.html`, com configuração inline.
- **Bootstrap Icons 1.11.3:** Para os ícones em ambas as versões.
- **Google Fonts:** Para as fontes personalizadas (Raleway, Pinyon Script, etc.).

## 📂 Estrutura do Projeto
atividade-bootstrap-tailwind/

├── index.html # Página principal do projeto com o máximo de componentes Bootstrap 5
├── tailwind.html # Página com Tailwind CSS
├── outros-componentes.html # Página com outros componentes Bootstrap que não foram utilizados na principal
├── css/
│ └── style.css # CSS customizado
├── imgs/ # Pasta com todas as imagens do projeto
└── README.md # Este arquivo

## 🚀 Como Executar

1.  Clone este repositório:
    ```bash
    git clone https://github.com/N4rdelli/atividade-bootstrap-tailwind.git
    ```
2.  Navegue até a pasta do projeto:
    ```bash
    cd atividade-bootstrap-tailwind
    ```
3.  Abra o arquivo `index.html` em seu navegador para ver a versão Bootstrap.
4.  Abra o arquivo `tailwind.html` em seu navegador para ver a versão Tailwind CSS.

Não são necessárias instalações adicionais, pois todas as dependências são carregadas via CDN.

## 📸 Screenshots

**Hero Maison Rosée**
![Imagem da hero da página principal.](/imgs/readme/screenshot_hero.png "This is a sample image.")

**Seção de Produtos**
![Imagem da seção de produtos do Maison Rosée.](/imgs/readme/screenshot_shopping.png "This is a sample image.")

**Detalhes do Produto**
![Imagem do modal que mostra os detalhes de um produto.](/imgs/readme/screenshot_modal.png "This is a sample image.")

**FAQ**
![Imagem da seção de FAQ, com accordions.](/imgs/readme/screenshot_faq.png "This is a sample image.")

**Seção de Histórias**
![Imagem da seção de histórias, com multi-collapse.](/imgs/readme/screenshot_stories.png "This is a sample image.")

**Footer Maison Rosée**
![Imagem da seção de personalização e do footer..](/imgs/readme/screenshot_footer.png "This is a sample image.")

**Formulário de buquê personalizado**
![Imagem do formulário de buquê personalizado.](/imgs/readme/screenshot_form.png "This is a sample image.")

## 👩‍💻 Autora

Desenvolvido por **Anelize Nardelli**.

-   [![LinkedIn](https://img.shields.io/badge/LinkedIn-Anelize%20Nardelli-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/anelize-n4rdelli)
-   [![GitHub](https://img.shields.io/badge/GitHub-N4rdelli-181717?style=for-the-badge&logo=github)](https://github.com/N4rdelli)
-   [![Instagram](https://img.shields.io/badge/Instagram-aa_nardelli-E4405F?style=for-the-badge&logo=instagram)](https://www.instagram.com/aa_nardelli/)


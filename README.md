# 🎨 Exercício CSS - Fundamentos de Estilização

![Status](https://img.shields.io/badge/Status-Finalizado-green)
![HTML5](https://img.shields.io/badge/Code-HTML5-orange?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/Style-CSS3-1572B6?logo=css3&logoColor=white)

> Uma demonstração prática de como a Folha de Estilos em Cascata (CSS) transforma a estrutura bruta do HTML em uma interface visualmente organizada.

## 🎯 Motivação e Propósito

Este repositório contém a resolução de exercícios focados na aplicação pura de **CSS3**. O objetivo principal é consolidar o entendimento sobre como os elementos visuais da web são construídos "do zero", sem a ajuda de frameworks.

O projeto resolve o desafio de apresentação de conteúdo, garantindo que textos sejam legíveis, imagens estejam alinhadas e que o layout respeite hierarquias visuais através de espaçamentos (padding/margin) e cores.

## 🛠️ Tecnologias Utilizadas

Por ser um projeto focado em fundamentos, a stack é nativa e leve:

* **[HTML5](https://developer.mozilla.org/pt-BR/docs/Web/HTML):** Responsável pela estrutura semântica (O "esqueleto" da página).
* **[CSS3](https://developer.mozilla.org/pt-BR/docs/Web/CSS):** Responsável pela camada de apresentação (A "pele" e "roupa" da página).
    * Uso de Classes e IDs.
    * Manipulação de Backgrounds.
    * Formatação de Fontes (Webfonts).

## 📦 Instalação e Execução

Este é um projeto de site estático (`static site`), o que facilita muito a visualização pois não requer compilação.

### Pré-requisitos
* Um navegador web atualizado (Chrome, Firefox, Edge, Safari).
* (Opcional) VS Code para leitura do código.

### Passo a Passo

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/DouglassenG/exercicio_css.git](https://github.com/DouglassenG/exercicio_css.git)
    ```

2.  **Acesse o diretório:**
    ```bash
    cd exercicio_css
    ```

3.  **Visualização:**
    * Localize o arquivo `index.html`.
    * Dê um duplo clique para abrir diretamente no navegador.

## 💻 Estrutura e Conceitos

O código demonstra a separação de interesses (Separation of Concerns), onde o HTML não contém estilos inline, delegando essa função ao arquivo CSS externo.

**Estrutura de Arquivos:**
```text
exercicio_css/
├── index.html       # Estrutura (Markup)
├── main.css         # Estilos (Presentation)
└── images/          # Ativos visuais

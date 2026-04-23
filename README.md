# 🃏 Yu-Gi-Oh! Card Slider Clone

![GitHub repo size](https://img.shields.io/github/repo-size/gio488/yugioh-clone)

Um projeto interativo que simula um seletor de cartas do universo Yu-Gi-Oh!, permitindo navegar entre diferentes monstros com efeitos visuais de seleção.

---

## 🚀 Funcionalidades

* **Navegação Dinâmica:** Sistema de "Avançar" e "Voltar" que alterna entre as cartas da lista.
* **Slider de Cartões:** Uso de classes CSS para destacar a carta selecionada e ocultar as demais.
* **Informações Detalhadas:** Exibição de Nome, Nível (estrelas), Descrição e Atributos (ATK/DEF) de cada monstro.
* **Design Temático:** Fundo personalizado para cada tipo de carta, mantendo a estética do jogo original.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estrutura da lista de personagens e botões de navegação.
* **CSS3:** Estilização dos cartões, animações de seleção e responsividade.
* **JavaScript (Vanilla):** Lógica de controle do slider, manipulação de classes (`classList`) e ouvintes de evento (`addEventListener`).

---

## 📂 Estrutura de Arquivos

```text
├── index.html        # Estrutura principal
├── index.js          # Lógica de transição das cartas
├── index.css         # Estilos globais e reset
├── estilos.css       # Design específico dos cartões
└── responsivo.css    # Ajustes para dispositivos móveis
```
⚙️ Como Funciona o JS
O script identifica o clique nos botões e gerencia o índice da carta atual:
Remove a classe .selecionado da carta visível.
Incrementa ou decrementa o contador cartaoAtual.
Adiciona a classe .selecionado à nova carta, fazendo-a aparecer na tela.
👨‍💻 Desenvolvedora
Projeto desenvolvido por Giovanna durante treinamento de desenvolvimento web.
GitHub: @gio488
Email: giovannacaxias6@gmail.com

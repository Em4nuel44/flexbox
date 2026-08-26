<div align="center">

# 🐾 Patas & Lar — Adoção Responsável

[![CSS3](https://img.shields.io/badge/CSS3-Flexbox-1572B6?style=for-the-badge&logo=css3&logoColor=white)](#)
[![HTML5](https://img.shields.io/badge/HTML5-Semantic-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#)
[![Status](https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge)](#)

*Uma plataforma web moderna, responsiva e focada na conscientização e facilitação da adoção responsável de cães e gatos resgatados.*

---

</div>

## 📌 Sobre o Projeto

O **Patas & Lar** é um projeto desenvolvido para consolidar na prática os conceitos fundamentais do **CSS Flexbox**. A página foi construída com foco em **design responsivo**, garantindo uma navegação fluida em desktops, tablets e dispositivos móveis sem perder a elegância visual.

---

## 🛠️ Tecnologias & Conceitos Aplicados

O projeto atende rigorosamente a **todos os 11 requisitos técnicos de Flexbox** exigidos:

| Propriedade CSS | Aplicação no Projeto |
| :--- | :--- |
| **`display: flex;`** | Ativado em todos os containers estruturais (`.navbar`, `.hero`, `.cards-container`, etc.) |
| **`flex-direction`** | Alternado entre `row` (desktop) e `column` (formulários e rodapé) |
| **`justify-content`** | Alinhamento dinâmico no eixo principal (`space-between`, `center`) |
| **`align-items`** | Centralização vertical dos elementos no eixo transversal (`center`) |
| **`align-content`** | Organização das linhas de cards no container (`space-around`) |
| **`flex-wrap`** | Quebra automática de linha para adaptação responsiva (`wrap`) |
| **`gap`** | Espaçamento padronizado entre elementos flex |
| **`flex-grow`** | Expansão proporcional dos conteúdos |
| **`flex-shrink`** | Encolhimento dinâmico dos cards em telas menores |
| **`flex-basis`** | Dimensionamento base inicial de componentes e imagens |
| **`order`** | Reordenação explícita de elementos na seção *Sobre Nós* |

---

## 🏛️ Estrutura das Seções

- ** Header:** Navegação principal com logo e links ancorados.
- ** Hero Section:** Apresentação de impacto com chamada para ação (CTA) e destaque visual.
- ** Serviços (Como Ajudar):** Cards informativos dinâmicos (*Adoção*, *Lar Temporário* e *Doações*).
- ** Sobre Nós:** História da instituição com foto da equipe reordenada via Flexbox.
- ** Contato:** Formulário estruturado em coluna para fácil preenchimento.
- ** Footer:** Rodapé completo com contatos, redes sociais e direitos autorais.

---

## 📁 Estrutura de Arquivos

```text
projeto/
├── 📄 index.html        # Estrutura semântica da página
├── 📁 css/
│   └── 🎨 style.css     # Estilização completa e regras de Flexbox
├── 📁 images/
│   ├── 🖼️ logo.png      # Identidade visual principal
│   └── 🖼️ sobre.png     # Imagem ilustrativa da equipe/abrigo
└── 📘 README.md         # Documentação do projeto

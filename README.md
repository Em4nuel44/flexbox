# 🐾 Patas & Lar — Plataforma de Adoção de Animais

Este projeto é uma landing page moderna, profissional e totalmente responsiva desenvolvida para a ONG **Patas & Lar**, focada na conscientização e facilitação da adoção responsável de cães e gatos resgatados.

O objetivo principal desta aplicação é demonstrar na prática o domínio completo do modelo de layout **CSS Flexbox**, utilizando suas propriedades para estruturar componentes, alinhar conteúdos e garantir uma interface adaptável a múltiplos tamanhos de tela.

---

## 📁 Estrutura de Pastas do Projeto

```text
projeto/
│
├── index.html          # Arquivo estrutural com o conteúdo da página
├── css/
│   └── style.css       # Estilização completa e regras de Flexbox
├── images/
│   ├── logo.png        # Logotipo da Patas & Lar
│   └── sobre.png       # Imagem ilustrativa da equipe/abrigo
└── README.md           # Documentação técnica do projeto
🧩 Seções Obrigatórias Desenvolvidas
Cabeçalho (Header / .navbar)

Contém o logotipo da marca e o menu de navegação principal.

Utiliza display: flex, flex-direction: row, justify-content: space-between e align-items: center para distribuir a marca e os links nos extremos da barra.

Seção Principal (Hero / .hero)

Área de destaque contendo título impactante, mensagem de conscientização, botão de chamada para ação (CTA) e visualização do logotipo da instituição.

Organizada em colunas lado a lado no desktop usando flex-wrap: wrap e flex-basis para garantir que a imagem e o texto se ajustem em telas menores.

Seção de Serviços (Como Você Pode Ajudar / .servicos)

Apresenta 3 cards informativos (Adoção Responsável, Lar Temporário e Doações & Apadrinhamento).

Utiliza flex-wrap: wrap e align-content: space-around para gerenciar a distribuição e quebra dos cards em múltiplas linhas.

Seção Sobre Nós (Sobre a Patas & Lar / .sobre)

Exibe informações sobre o trabalho do abrigo juntamente com a foto da equipe de voluntários.

Faz uso das propriedades order: 1 e order: 2 nos elementos filhos para controlar a sequência visual e estrutural do layout.

Seção de Contato (Fale Conosco / .contato)

Formulário completo para interessados em adotar ou colaborar (Campos: Nome, E-mail, Telefone e Mensagem).

Organizado com flex-direction: column para um alinhamento vertical limpo e intuitivo de todos os campos de entrada.

Rodapé (Footer / .footer)

Contém a marca, contatos diretos, links para redes sociais e os direitos autorais.

Estruturado em coluna centralizada via Flexbox (align-items: center e justify-content: center).

🛠️ Requisitos Técnicos de Flexbox Aplicados
Todos os 11 conceitos técnicos de Flexbox exigidos foram implementados no código CSS:

display: flex; — Aplicado em múltiplos elementos como .navbar, .hero, .cards-container, .sobre, .form-contato e .footer.

flex-direction — Utilizado como row (no cabeçalho, hero e sobre) e column (no formulário de contato e no rodapé).

justify-content — Empregado para distribuição dos elementos no eixo principal (ex: space-between no header e center no footer).

align-items — Aplicado para o alinhamento vertical dos itens no eixo transversal (align-items: center).

align-content — Utilizado na classe .cards-container com o valor space-around para gerenciar o alinhamento de linhas extras quando ocorre a quebra de linha.

flex-wrap — Aplicado como wrap no container de cards e nas seções responsivas para permitir a adaptação em dispositivos móveis.

gap — Define os espaçamentos dinâmicos entre os itens filhos de um container flex sem a necessidade de margens manuais.

flex-grow — Define a capacidade de expansão proporcional dos elementos (ex: flex-grow: 1 no hero e nos cards).

flex-shrink — Configurado para permitir que os elementos encolham adequadamente conforme a viewport diminui (flex-shrink: 1).

flex-basis — Define a dimensão base inicial dos componentes flex antes da distribuição do espaço restante (ex: flex-basis: 250px nos cards e flex-basis: 400px nos textos).

order — Aplicado explicitamente nas sub-seções de .sobre-img (order: 1) e .sobre-texto (order: 2) para modificar a ordem padrão de renderização.

💻 Como Executar o Projeto
Faça o download ou clone este repositório em sua máquina.

Certifique-se de manter a estrutura de pastas conforme demonstrado na seção Estrutura de Pastas.

Abra o arquivo index.html em qualquer navegador web de sua preferência.

© 2026 Patas & Lar. Todos os direitos reservados.

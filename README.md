# Deborah Mattos — Personal Brand

Site de portfólio pessoal da Deborah Mattos, criadora de conteúdo UGC (User Generated Content). O site apresenta seu posicionamento, formato de trabalho, identidade visual e moodboard, servindo como cartão de visita para marcas e parceiros.

O layout foi desenhado no Canva e depois traduzido para HTML e CSS puros, mantendo fidelidade visual ao design original.

## 🔗 Referência de design

Layout original criado no Canva: [ver design](https://www.canva.com/design/DAHS10MQONU/edit)

## 📄 Estrutura do site

O site é uma página única (`index.html`), dividida nas seguintes seções:

| Seção | Descrição |
|---|---|
| **Home** | Hero com nome, subtítulo "Personal Brand" e foto de destaque |
| **Propósito** | Apresentação do trabalho e valores |
| **Formato** | Explica os formatos de conteúdo oferecidos (Cinema-Vendas, Cinema-Branding) |
| **Big Ideias** | Detalha a ideia central de conteúdo, com exemplos práticos |
| **Identidade Visual** | Paleta de cores e conceito visual da marca |
| **Estilos Gráficos** | Emojis, tipografia e tom de voz usados nos conteúdos |
| **Posicionamento** | Quem é a Deborah, como quer ser vista e seu nicho (maternidade, bem-estar e crochê) |
| **Moodboard** | Referências visuais de estilo (estilo contemporâneo) |
| **Contato (Final)** | Foto final e links para WhatsApp e Instagram |

## 🛠️ Tecnologias

- **HTML5** — semântico, uma seção por bloco de conteúdo
- **CSS3**
  - Fonte customizada `Lovelace Text` (`@font-face`, regular e bold, `.woff2`/`.woff`)
  - **CSS Grid** e **Flexbox** para os layouts de cada seção
  - Posicionamento percentual sobre uma "prancheta" com `aspect-ratio` para replicar seções com layout livre do Canva (Estilos Gráficos, Moodboard, Contato)
  - **Responsivo**, com breakpoint em `768px` — menu escondido, colunas empilhadas e imagens reordenadas para leitura mobile

## 📁 Assets

Todas as imagens ficam na pasta `Assets/`, exportadas diretamente do Canva (fotos, ícones e elementos gráficos já com bordas/fundos prontos).

## 🎨 Paleta de cores

| Cor | Uso |
|---|---|
| `#f1ba4f` | Destaque amarelo (`.primeiro`) |
| `#000000` | Texto principal (`.segundo`) |
| `#AF8E72` | Subtítulos |
| `#B35D24` | Etiquetas e links de contato |
| `#EFE9E4` | Fundo geral do site |

## 🚀 Como visualizar

Basta abrir o arquivo `index.html` num navegador. Não há build nem dependências — é HTML e CSS puros.

## 📬 Contato

- [WhatsApp](https://wa.me/5521967448898)
- [Instagram](https://www.instagram.com/deborah.park/)

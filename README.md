# ☕ Cafeteria Caio&cofee

Site de uma cafeteria com tema escuro, feito com **HTML** e **CSS** puro. O projeto une café e tecnologia: o texto e o visual foram pensados para quem passa as madrugadas programando.

## 📋 Sobre o projeto

Página única (one page) com navegação por âncoras entre as seções. O foco foi praticar layout com Flexbox e CSS Grid, variáveis CSS, efeitos de hover e organização de um site completo, do cabeçalho ao rodapé.

## 🧩 Seções

- **Header fixo:** logo, menu de navegação (Home, Sobre, Menu, Endereço) e ícones de carrinho e busca.
- **Home:** imagem de fundo em tela cheia, título de destaque, texto de apresentação e botão de chamada.
- **Sobre nós:** conteúdo centralizado com título, parágrafo e botão.
- **Nosso menu:** grid com 6 cafés (Café Latte, Macchiato, Flat White, Cappuccino, Cortado e Mocha), cada um com imagem, nome, preço, preço antigo riscado e botão "Adicione ao Carrinho".
- **Nosso endereço:** mapa do Google Maps incorporado com `iframe`.
- **Footer:** ícones de redes sociais (Instagram, X e WhatsApp).

## 🎨 Detalhes de estilo

- Variáveis CSS no `:root` para cor principal, cor de fundo e borda.
- Reset global com `*` (margin, padding, transição e fonte).
- Botão `.btn` com efeito de flutuar no hover (`transform: translateY`).
- Cards do menu com troca de cor no hover.
- Fonte **Roboto** pelo Google Fonts.
- Ícones fornecidos pelo [Icons8](https://icons8.com).

## 🛠️ Tecnologias

- HTML5
- CSS3 (Flexbox, Grid, variáveis CSS, transições)
- Google Fonts
- Google Maps (embed)

## 📁 Estrutura de pastas

```
projeto-cafeteria/
├── img/
│   ├── logo.png
│   ├── home-img.jpg
│   └── menu-1.png ... menu-6.png
├── index.html
├── style.css
└── README.md
```

## ▶️ Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
2. Abra a pasta do projeto no VS Code.
3. Abra o `index.html` no navegador ou use a extensão **Live Server**.

## 📚 O que foi praticado

- Estruturação semântica de uma página completa em HTML.
- Layout responsivo com `grid-template-columns` e Flexbox.
- Centralização de elementos com `justify-content` e `align-items`.
- Uso de variáveis CSS para manter o padrão visual.
- Efeitos de `hover` e `transition`.
- Incorporação de mapa externo com `iframe`.

## 🔮 Próximos passos

- [ ] Tornar o menu totalmente responsivo para celular com `@media`.
- [ ] Adicionar menu hambúrguer na navegação.
- [ ] Criar interação para o carrinho com JavaScript.

## 👨‍💻 Autor

**Caio Rafael Silva Teixeira**
GitHub: [Caio Rafael-dev](https://github.com/)
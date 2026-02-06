# 🎮 Lords of Logic

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Domine o conhecimento. Conquiste a lógica.**

Landing page estilo 8-bit/pixel art para o jogo de trivia Lords of Logic - um jogo de perguntas e respostas criado especialmente para desenvolvedores.

---

## 📖 Sobre o Projeto

Lords of Logic é um jogo de trivia focado em desenvolvedores, com perguntas sobre:

- 💻 **Stack Web & Mobile**: HTML, CSS, JavaScript, React, Next.js, Node.js, Express, NestJS, Java, C#, PHP
- 🏪 **Plataformas**: Salesforce, VTEX, Shopify
- 🛠️ **Desenvolvimento Geral**: Boas práticas, DevOps, Git, Arquitetura, Clean Code

Esta landing page apresenta o conceito do jogo com um visual nostálgico inspirado em jogos arcade clássicos dos anos 80/90.

---

## ✨ Características

### 🎨 Visual Retro 8-bit
- Paleta de cores vibrantes estilo NES/SNES
- Tipografia pixel art (Press Start 2P + VT323)
- Animações pixeladas e efeitos arcade
- Sombras e bordas no estilo retro gaming
- Efeitos de scanlines e starfield animado

### 📱 Totalmente Responsivo
- Design adaptável para desktop, tablet e mobile
- Grid flexível que se ajusta a diferentes tamanhos de tela
- Imagens e textos otimizados para cada dispositivo

### ⚡ Performance
- Código HTML, CSS e JavaScript puro (sem frameworks)
- Sem dependências externas
- Carregamento rápido
- Animações CSS otimizadas

### 🎯 Funcionalidades
- Scroll suave entre seções
- Animações fade-in ao rolar a página
- Indicador de scroll animado
- Efeito de paralaxe no hero
- Hover effects em todos os elementos interativos
- Botões com feedback visual

---

## 🚀 Como Usar

### Opção 1: Abrir Diretamente
1. Faça o download do arquivo `lords-of-logic.html`
2. Abra o arquivo em qualquer navegador moderno
3. Pronto! A landing page está funcionando

### Opção 2: Servidor Local
```bash
# Com Python 3
python -m http.server 8000

# Com Node.js (http-server)
npx http-server

# Com PHP
php -S localhost:8000
```

Depois acesse: `http://localhost:8000/lords-of-logic.html`

---

## 📂 Estrutura do Projeto

```
lords-of-logic/
│
├── lords-of-logic.html    # Arquivo HTML principal (standalone)
└── README.md              # Este arquivo
```

O projeto é composto por um **único arquivo HTML** que contém:
- Estrutura HTML completa
- Estilos CSS incorporados (tag `<style>`)
- JavaScript incorporado (tag `<script>`)

---

## 🎨 Paleta de Cores

```css
/* Backgrounds */
--color-bg-primary: #1a1c2c;      /* Fundo principal escuro */
--color-bg-secondary: #252736;    /* Fundo secundário */
--color-bg-card: #2e3145;         /* Fundo dos cards */

/* Acentos */
--color-accent-pink: #d77bba;     /* Rosa pixel */
--color-accent-blue: #5fcde4;     /* Azul ciano */
--color-accent-cyan: #76e5c8;     /* Ciano claro */
--color-accent-yellow: #ffd541;   /* Amarelo pixel */

/* Textos */
--color-text-primary: #ffffff;    /* Texto principal */
--color-text-secondary: #b0b5cd;  /* Texto secundário */

/* Bordas e sombras */
--color-border: #4a4e69;          /* Bordas */
--color-pixel-shadow: #0f0f1b;    /* Sombra pixelada */
```

---

## 🎯 Seções da Landing Page

### 1. 🎮 Hero Section
- Título principal com animação float
- Subtítulo com efeito blink
- Descrição do jogo
- Botões de CTA (Começar a Jogar / Conheça o Jogo)
- Indicador de scroll animado

### 2. 📚 Sobre o Jogo
- Explicação clara do conceito
- Badges com características principais
- Design limpo e direto

### 3. 📁 Categorias de Perguntas
- 3 cards interativos
- Ícones temáticos
- Descrição de cada categoria
- Borda animada colorida

### 4. 🎯 Como Funciona
- 4 passos numerados
- Cards com números coloridos diferentes
- Animações no hover
- Explicação visual do fluxo

### 5. ❓ Tipos de Perguntas
- 2 tipos: Múltipla escolha e Resposta em texto
- Cards com ícones grandes
- Efeito de hover com listras diagonais

### 6. 💎 Benefícios
- Dividido em 2 colunas: Desenvolvedores e Empresas
- Listas com marcadores animados
- Estrela rotativa decorativa

### 7. 🚀 CTA Final
- Chamada motivadora
- Botão principal destacado
- Fundo com listras animadas

### 8. 📄 Footer
- Nome do projeto
- Tagline
- Copyright
- Barra colorida animada no topo

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Uso |
|------------|-----|
| HTML5 | Estrutura semântica da página |
| CSS3 | Estilização completa e animações |
| JavaScript | Interatividade e efeitos dinâmicos |
| Google Fonts | Fontes pixel art (Press Start 2P, VT323) |

---

## 🎨 Fontes Utilizadas

- **[Press Start 2P](https://fonts.google.com/specimen/Press+Start+2P)**: Títulos e elementos pixel art
- **[VT323](https://fonts.google.com/specimen/VT323)**: Textos corridos estilo terminal

---

## ⚡ Animações e Efeitos

### CSS Animations
- `@keyframes scanlines` - Efeito de TV antiga
- `@keyframes starfield` - Estrelas em movimento
- `@keyframes float` - Flutuação suave
- `@keyframes blink` - Pisca-pisca retro
- `@keyframes glitch` - Efeito glitch (removido dos títulos principais)
- `@keyframes bounce-pixel` - Bounce pixelado
- `@keyframes pulse` - Pulsação suave
- `@keyframes spin` - Rotação
- `@keyframes rainbow-border` - Bordas multicoloridas
- `@keyframes slide-border` - Bordas deslizantes
- E muito mais!

### JavaScript Features
- Smooth scroll entre seções
- Intersection Observer para fade-in
- Efeito de paralaxe no hero
- Animações ao clicar nos botões
- Controle de visibilidade do scroll indicator

---

## 📱 Responsividade

A landing page é totalmente responsiva com breakpoints em:

```css
@media (max-width: 768px) {
  /* Ajustes para tablets e mobile */
  - Grid de 1 coluna
  - Espaçamentos reduzidos
  - Fonte responsiva com clamp()
  - Botões full-width em mobile
}
```

---

## 🎯 Próximos Passos

- [ ] Integração com backend
- [ ] Sistema de login/cadastro
- [ ] Banco de perguntas real
- [ ] Sistema de pontuação
- [ ] Ranking de jogadores
- [ ] Modo multiplayer
- [ ] Conquistas e badges
- [ ] Progressão de níveis

---

## 🤝 Contribuindo

Este é um projeto em desenvolvimento. Sugestões e melhorias são bem-vindas!

1. Fork o projeto
2. Crie sua feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

---

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

---

## 👨‍💻 Autor

**Criado por desenvolvedores, para desenvolvedores.**

---

## 🎮 Inspirações

Este projeto foi inspirado em:
- Jogos arcade clássicos (Pac-Man, Space Invaders, Donkey Kong)
- Consoles retro (NES, SNES, Game Boy)
- Estética pixel art dos anos 80/90
- Cultura gamer nostálgica

---

## 📞 Contato & Suporte

Se você tiver dúvidas, sugestões ou encontrar algum bug, sinta-se à vontade para:

- Abrir uma issue no repositório
- Enviar um pull request
- Entrar em contato diretamente

---

<div align="center">

**⭐ Se você gostou deste projeto, considere dar uma estrela! ⭐**

**[ INSERT COIN TO CONTINUE ]**

Made with 💜 and lots of ☕

</div>
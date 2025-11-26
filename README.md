🔗 Linktree Clone - Rodrigo Azevedo

Um clone moderno e elegante do Linktree, desenvolvido com HTML e CSS puro, apresentando design glassmorphism, animações suaves e totalmente responsivo.

![Preview]([https://rodrigoazevedo1988.github.io/site-tipo-linktree/preview.png](https://github.com/rodrigoazevedo1988/site-tipo-linktree/blob/main/Screenshot_6.png?raw=true))

---

✨ Características

- **Design Glassmorphism** — Efeito de vidro fosco com blur e transparências
- **Animações Fluidas** — Background animado com partículas flutuantes
- **Hover Effects** — Efeitos interativos nos links com shimmer e elevação
- **Foto de Perfil Animada** — Borda gradiente pulsante com indicador de status
- **100% Responsivo** — Adaptável para desktop, tablet e mobile
- **Performance Otimizada** — Apenas HTML e CSS, sem dependências JavaScript
- **Dark Mode Nativo** — Tema escuro elegante por padrão

---

## 🚀 Início Rápido

### 1. Clone o Repositório

```bash
git clone https://github.com/rodrigoazevedo1988/site-tipo-linktree.git
cd site-tipo-linktree
```

### 2. Personalize suas Informações

Abra o arquivo `index.html` e edite as seguintes seções:

#### Foto de Perfil
```html
<img src="SUA_FOTO_URL_AQUI" alt="Seu Nome" class="profile-image">
```

#### Nome e Título
```html
<h1>Seu Nome</h1>
<p class="title">Seu Cargo / Título</p>
<p class="bio">Sua descrição profissional aqui...</p>
```

#### Links Principais
```html
<a href="https://seu-linkedin.com" target="_blank" class="link-item linkedin">
    <i class="fab fa-linkedin"></i>
    <span>LinkedIn</span>
    <i class="fas fa-arrow-right arrow"></i>
</a>
```

#### Email de Contato
```html
<a href="mailto:seu@email.com" class="social-icon email">
```

### 3. Deploy

#### Opção A: GitHub Pages (Recomendado)

1. Faça push das alterações para o repositório
2. Acesse **Settings** > **Pages**
3. Em **Source**, selecione a branch `main`
4. Seu site estará disponível em `https://seuusuario.github.io/site-tipo-linktree`

#### Opção B: Netlify

1. Arraste a pasta do projeto para [netlify.com/drop](https://netlify.com/drop)
2. Seu site estará online instantaneamente

#### Opção C: Vercel

```bash
npm i -g vercel
vercel
```

---

## 🎨 Personalização

### Alterar Cores

Edite as variáveis CSS no início do arquivo `<style>`:

```css
:root {
    --primary: #6366f1;      /* Cor principal (roxo) */
    --primary-dark: #4f46e5; /* Cor principal escura */
    --secondary: #ec4899;    /* Cor secundária (rosa) */
    --dark: #0f172a;         /* Fundo escuro */
    --light: #f8fafc;        /* Texto claro */
}
```

### Adicionar Novos Links

Copie e cole este bloco dentro da `<div class="links">`:

```html
<a href="https://seu-link.com" target="_blank" class="link-item">
    <i class="fab fa-icon-name"></i>
    <span>Nome do Link</span>
    <i class="fas fa-arrow-right arrow"></i>
</a>
```

### Ícones Disponíveis

Este projeto utiliza [Font Awesome 6](https://fontawesome.com/icons). Alguns ícones úteis:

| Plataforma | Classe do Ícone |
|------------|-----------------|
| LinkedIn | `fab fa-linkedin` |
| GitHub | `fab fa-github` |
| Instagram | `fab fa-instagram` |
| Twitter/X | `fab fa-x-twitter` |
| YouTube | `fab fa-youtube` |
| TikTok | `fab fa-tiktok` |
| WhatsApp | `fab fa-whatsapp` |
| Telegram | `fab fa-telegram` |
| Email | `fas fa-envelope` |
| Website | `fas fa-globe` |
| Portfólio | `fas fa-briefcase` |

### Desativar Animações

Para remover as animações de fundo, delete ou comente:

```html
<!-- <div class="bg-animation">...</div> -->
```

---

## 📁 Estrutura do Projeto

```
site-tipo-linktree/
│
├── index.html      # Arquivo principal (HTML + CSS inline)
├── README.md       # Documentação
├── preview.png     # Screenshot para o README
└── assets/         # (opcional) Imagens e recursos
    └── profile.jpg
```

---

## 📱 Responsividade

| Dispositivo | Largura | Status |
|-------------|---------|--------|
| Mobile | < 480px | ✅ |
| Tablet | 481px - 768px | ✅ |
| Desktop | > 769px | ✅ |

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** — Estrutura semântica
- **CSS3** — Estilos e animações
- **Google Fonts** — Tipografia Inter
- **Font Awesome 6** — Biblioteca de ícones

---

## 📄 Licença

Este projeto está sob a licença MIT. Sinta-se livre para usar, modificar e distribuir.

---

## 👤 Autor

**Rodrigo Azevedo**

- LinkedIn: [@rodrigo-azevedo88](https://www.linkedin.com/in/rodrigo-azevedo88)
- Website: [rsolutionsbr.com](https://www.rsolutionsbr.com)
- GitHub: [@rodrigoazevedo1988](https://github.com/rodrigoazevedo1988)

---

## ⭐ Apoie o Projeto

Se este projeto foi útil para você, considere dar uma ⭐ no repositório!

---

<p align="center">
  Feito com 💜 por Rodrigo Azevedo
</p>

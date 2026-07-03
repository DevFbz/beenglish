# beenglish — Site do Curso de Inglês

Site institucional do curso **beenglish** — métodos modernos de ensino de inglês com foco em conversação e neurociência.

## 📁 Estrutura

```
beenglish-site/
├── index.html    # Landing page completa (single-page)
└── README.md     # Este arquivo
```

## 🎨 Identidade Visual

- **Fundo:** Navy escuro (`#0a1628`)
- **Destaque:** Dourado (`#f5c518`) — gradiente dourado nos títulos
- **Texto:** Branco (`#ffffff`) e cinzas claros
- **Fonte:** Inter (Google Fonts)
- **Logo:** `been` (branco) + `english` (gradiente dourado) + ★ (estrela dourada flutuante)

## 📄 Seções

1. **Hero** — "Aprenda Inglês de Verdade" + CTA para WhatsApp
2. **Stats** — 500k+ alunos, 20+ anos, 12 meses, 4.9★
3. **Método** — Neurociência, conversação, acompanhamento personalizado
4. **Currículo** — Jornada de 12 meses em grid de cards
5. **Diferenciais** — 6 pilares do método
6. **Garantia** — Selo de garantia de fluência
7. **Depoimentos** — 3 cards de alunos
8. **Planos** — Mensal (R$97), Premium (R$197), Anual (R$67/mês)
9. **App** — Funcionalidades do aplicativo beenglish
10. **FAQ** — Accordion com perguntas frequentes
11. **CTA Final** — Chamada final para WhatsApp
12. **Footer** — Links, contato, termos

## 🛠️ Tecnologias

- HTML5 + CSS3 (vanilla)
- Tailwind CSS (CDN para utilitários)
- JavaScript (scroll animations, FAQ accordion, menu mobile)
- Google Fonts (Inter)
- Ícones: Emoji + SVG inline

## ✨ Funcionalidades

- Responsivo (mobile-first)
- Animações de fade-in ao scroll
- FAQ accordion interativo
- Menu mobile com hamburguer
- Gradientes dourados dinâmicos
- Cards com efeito glassmorphism
- Partículas/glows no background
- Navegação suave com scroll

## 🚀 Como visualizar

Abra o arquivo `index.html` no navegador ou use um servidor local:

```bash
# Opção 1: direto no navegador
start index.html

# Opção 2: servidor Python
python -m http.server 8765
# Depois abra http://localhost:8765
```

## ✏️ Para editar

- **Cores:** altere as variáveis CSS em `:root` no `<style>`
- **Conteúdo:** textos fictícios estão no HTML, só substituir
- **WhatsApp:** link em `wa.me/5511912451993` — troque o número
- **Preços:** valores nos cards de plano

## 📱 Próximos passos sugeridos

- [ ] Adicionar página "Sobre" (/sobre)
- [ ] Adicionar formulário de lead (email capture)
- [ ] Adicionar blog / artigos
- [ ] Integrar com WhatsApp API
- [ ] Subir para produção (Vercel, Netlify, ou hospedagem própria)

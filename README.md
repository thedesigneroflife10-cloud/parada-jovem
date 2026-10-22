# PARADA JOVEM — protótipo da loja (HTML/CSS/JS puro)

Sem dependências e sem build. Abra `index.html` no navegador ou envie a pasta para qualquer hospedagem estática (Netlify, Vercel, GitHub Pages, Hostinger).

## Estrutura
- `index.html` — página única (navegação por JavaScript, sem URLs reais como /checkout)
- `css/styles.css` — estilos e paleta (variáveis `--y`, `--y2`, `--gd`, `--bg`, `--card`)
- `js/app.js` — produtos de exemplo, sacola (localStorage), filtros, checkout e mensagem do WhatsApp
- `images/logo-parada-jovem.png` — logo recortado do Instagram (baixa resolução; trocar pelo original)

## Para colocar no ar com dados reais
1. Produtos: editar a lista `P` em `js/app.js` (preço `p`, promoção `pp`, estoque `st`, fotos em `img`, salvas em `images/`). Os itens atuais são EXEMPLOS.
2. WhatsApp: variável `WA` em `js/app.js` (atualmente 5531983740560).
3. Fotos: colocar arquivos em `images/` e usar `img:["images/arquivo.jpg"]` no produto.

## Limitações
Não há banco de dados, login nem painel administrativo; pedidos não são gravados (só a mensagem do WhatsApp). A sacola fica só no navegador de cada cliente. Para isso é preciso um backend (ex.: Supabase) — o projeto real da loja está no Lovable.

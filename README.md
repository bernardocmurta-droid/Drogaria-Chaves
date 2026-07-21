# Site — Drogaria Chaves

Site institucional simples em HTML/CSS puro, pronto para publicar no GitHub Pages.

## Estrutura
```
index.html          → Página inicial (com banner da fachada)
quem-somos.html      → Aba "Quem Somos"
atendimento.html     → Aba "Atendimento / Redes Sociais"
faq.html             → Aba "Perguntas Frequentes (FAQ)" com acordeão
style.css            → Estilos de todas as páginas
banner.jpg           → Foto da fachada usada no banner da página inicial
assets/logo.png       → Logotipo da Drogaria Chaves
```

## Como publicar no GitHub Pages

1. Crie um repositório novo no GitHub (ex: `drogaria-chaves`).
2. Envie todos os arquivos desta pasta (`index.html`, `quem-somos.html`,
   `atendimento.html`, `faq.html`, `style.css`, `banner.jpg` e a pasta
   `assets/`) para a raiz do repositório.
3. No repositório, vá em **Settings → Pages**.
4. Em **Source**, selecione a branch `main` (ou `master`) e a pasta `/root`.
5. Clique em **Save**. Em alguns minutos o site estará disponível em
   `https://SEU-USUARIO.github.io/drogaria-chaves/`.

Não é necessário nenhum passo de build — são apenas arquivos HTML/CSS
estáticos.

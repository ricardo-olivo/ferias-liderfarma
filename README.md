# ferias-site

Página de entrada do **Controle de Férias (Líderfarma)** no GitHub Pages.
Ela só carrega o Web App do Apps Script em tela cheia (iframe 100% da tela) —
nenhum dado fica aqui; login e dados continuam no Apps Script.

- Configuração: variável `APP_URL` no `index.html` = link `/exec` da implantação.
- `?page=painel` no endereço abre direto o painel.
- Domínio próprio: arquivo `CNAME` + DNS (CNAME `ferias` → `<usuario>.github.io`).

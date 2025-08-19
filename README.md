## Bio — Matheus

Página de links (bio) estática, mobile-first, usando HTML + Bootstrap 5 via CDN.

### Estrutura
- `index.html`: página principal
- `assets/css/styles.css`: estilos customizados
- `assets/img/avatar.svg`: avatar placeholder (substitua pela sua foto)

### Personalização
Edite em `index.html`:
- Título e descrição
- Nome e bio curta
- Botões/links (href, rótulo e ícone)
- Troque `assets/img/avatar.svg` pela sua imagem

### Boas práticas
- Sem dependências de build; código estático
- Acessibilidade: `aria-label`, foco visível, `rel="noopener noreferrer"`
- Segurança (OWASP): sem JS de terceiros além de CDNs confiáveis; links externos com isolamento

### Publicação com GitHub + Cloudflare Pages
1) Inicialize o Git local e primeiro commit
```bash
git init
git add .
git commit -m "feat: bio inicial (HTML + Bootstrap 5)"
```

2) Crie um repositório no GitHub (via site) e conecte o remoto
```bash
git remote add origin https://github.com/<seu-usuario>/<seu-repo>.git
git branch -M main
git push -u origin main
```

3) No Cloudflare Pages
- Create project → Connect to Git → Selecione o repositório
- Framework preset: `None`
- Build command: deixe vazio
- Output directory: `/` (raiz) ou `.`
- Deploy

4) (Opcional) Domínio customizado
- Configure o domínio em Pages → Custom domains
- Adicione DNS (CNAME) conforme instruções

### Licença
Uso livre para seu perfil.



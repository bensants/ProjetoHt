# ProjetoHt

Site estático simples com HTML/CSS/JS e deploy automático no GitHub Pages.

## Como usar

- Abra `index.html` no navegador.
- Edite os arquivos em `assets/` para personalizar estilos e scripts.

## Deploy automático (GitHub Pages)

Ao fazer push na branch `main`, o workflow em `.github/workflows/deploy.yml` publica o site no GitHub Pages.

Passos iniciais (uma vez no repositório do GitHub):
- Habilite Pages: Settings → Pages → Source: GitHub Actions.

## Estrutura

- `index.html` – página principal
- `assets/styles.css` – estilos
- `assets/script.js` – comportamento básico
- `.github/workflows/deploy.yml` – CI/CD para Pages

## Licença

MIT

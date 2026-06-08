# EuroTrip 2026 — Roteiro de Viagem

Roteiro editorial (estilo revista) de uma viagem de 10 dias pela Espanha e Portugal: **Barcelona → Madrid → Valência → Ibiza → Lisboa**, de 12 a 21 de setembro de 2026.

Site estático de página única, sem dependências de build. As imagens são carregadas do Wikimedia Commons por URL.

## Arquivos

- `index.html` — o site (página única, autocontida)
- `.nojekyll` — desliga o processamento Jekyll do GitHub Pages
- `README.md` — este arquivo

## Publicar no GitHub Pages

1. Crie um repositório no GitHub e envie estes arquivos para o branch `main`.
2. No repositório: **Settings → Pages**.
3. Em **Build and deployment → Source**, escolha **Deploy from a branch**.
4. Selecione o branch `main` e a pasta `/ (root)`. Salve.
5. Aguarde ~1 minuto. O site fica disponível em `https://SEU-USUARIO.github.io/NOME-DO-REPO/`.

### Atualizar o site

Basta substituir o `index.html` por uma nova versão e dar commit/push no branch `main`. O GitHub Pages republica automaticamente.

## Atualizar via linha de comando (opcional)

```bash
git add index.html README.md .nojekyll
git commit -m "Atualiza roteiro EuroTrip 2026"
git push origin main
```

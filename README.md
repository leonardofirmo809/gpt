# repo-gpt

Projeto pronto para deploy (Vite + React).

## Scripts
- `npm run dev` — modo desenvolvimento
- `npm run build` — build de produção (gera `dist/`)
- `npm run preview` — serve a pasta `dist/` localmente

## Deploy rápido

### Netlify
- Build command: `npm run build`
- Publish directory: `dist`
- Node: 20 (config no `netlify.toml`)

### Vercel
- Framework Preset: Vite
- Install: `npm install`
- Build: `npm run build`
- Output: `dist`
- (já inclui `vercel.json`)

> Se usa variáveis no front, prefixe com `VITE_` e configure no painel (Netlify/Vercel).

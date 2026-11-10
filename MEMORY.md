# MEMORY — paulorgdc (perfil GitHub)
App Next.js que serve o banner HUD do perfil (`/api/hud-banner`), publicado na Vercel (paulorgdc.vercel.app).

## Stack
- Next.js 16.3 · React 19.2 · Tailwind 4 · TypeScript 5 · ESLint · npm

## Comandos
- `npm install`
- `npm run dev` · `npm run build` · `npm start` · `npm run lint`

## Variáveis de ambiente
- `.env.local`: VERCEL_OIDC_TOKEN (gerada por `vercel env pull`; não editar à mão)

## Regras de ouro
1. Código em `src/app/` (App Router); o banner é uma rota de API, não um asset estático.
2. A URL do banner no README usa `?v=N`: incrementar N ao mudar o visual (cache do GitHub).
3. Next 16 tem mudanças de API: consultar `node_modules/next/dist/docs/` antes de usar APIs novas.

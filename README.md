# TS Refrigeração — versão corrigida para Vercel

Esta versão usa JavaScript + Vite para evitar o erro de build TypeScript da versão anterior.

## Vercel
- Framework: Vite
- Build command: `npm run build`
- Output directory: `dist`

## Variáveis
`VITE_SUPABASE_URL`
`VITE_SUPABASE_PUBLISHABLE_KEY`

Nunca coloque `sb_secret_...` no frontend.

O projeto espera as tabelas Supabase já criadas no banco.

# GLA Tracker

Site estático (HTML único, sem build, sem dependências).

## Publicar na Vercel
1. Suba esta pasta para um repositório no GitHub.
2. Na Vercel: Add New > Project > importe o repositório.
3. Framework Preset: "Other". Deixe build e output em branco. Deploy.

Alternativa sem GitHub: arraste esta pasta no painel da Vercel, ou rode `npx vercel` dentro dela.

## Para substituir o site atual
Troque o `index.html` do repositório do gla-tracker.vercel.app por este e faça commit.

## Observação
Os dados ficam no localStorage de cada navegador (não sincronizam entre aparelhos).

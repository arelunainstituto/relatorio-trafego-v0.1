# Relatório Meta Ads · Instituto Areluna

Dashboard analítico estático do desempenho de tráfego pago (Meta Ads) — período **01/01/2026 a 31/03/2026** comparado a **01/10/2025 a 31/12/2025**.

## Stack

- HTML / CSS / Vanilla JavaScript (single-file)
- Chart.js 4.4.1 via CDN
- Inter & JetBrains Mono via Google Fonts

## Estrutura

- `index.html` — dashboard principal (entry point Vercel)
- `dashboard.html` — cópia idêntica do dashboard
- `vercel.json` — configuração de deploy estático
- `relatorio_de_instituto_areluna_01-01-2026_a_31-03-2026.pdf` — relatório de origem
- `campanhas_paises.md` — mapeamento campanha → países (Meta Ads Manager)

## Abas do dashboard

1. Resumo Consolidado
2. CA01 · Lead Gen
3. CA02 · Tráfego
4. Público & Demografia
5. Investimento por País

## Deploy

Projeto estático — deploy direto na Vercel apontando para a raiz. Sem build step.

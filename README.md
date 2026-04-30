# Dashboard Marketing Vendemmia 2026

Dashboard executivo interativo com os números de marketing da Vendemmia, consolidando o ano e a evolução mês a mês para apresentação à diretoria.

## Conteúdo

- `index.html` — Dashboard executivo completo (HTML + Chart.js, single file).
- `data/relatorio_marco26.md` — Conteúdo extraído do relatório fonte (Março/2026).

## Como visualizar

Basta abrir o arquivo `index.html` em qualquer navegador moderno. Não há build nem servidor: ele carrega Chart.js via CDN e funciona offline depois do primeiro acesso.

```bash
# macOS
open index.html
# Linux
xdg-open index.html
# Windows
start index.html
```

## O que está no dashboard

- **Visão geral do ano (YTD 2026)**: 317 leads · 37 reuniões · 9 propostas · 1 ganho
- **Progresso da meta anual**: 80 / 212 leads (37,7%) — pago, orgânico e e-mail
- **Evolução mês a mês**:
  - Funil completo por mês (leads, reuniões, propostas, ganhos)
  - Acumulado real vs. pace ideal para 212 leads
  - Investimento em mídia (Google Ads + Meta Ads)
  - Crescimento de seguidores (LinkedIn + Instagram)
  - Distribuição de leads por origem
- **Funil consolidado YTD** + comparativo Q1 2025 vs Q1 2026
- **Eventos**: Pit Stop Supply Chain (14 empresas, 17 reuniões YTD, cronograma de 10 ações de divulgação) + Intermodal
- **Detalhe por canal**: Google Ads, Site & LPs, Instagram, LinkedIn, E-mail Marketing
- **Resultados de Março**: 10 reuniões, 4 propostas, 1 ganho (ChargeOn)
- **Direcionamentos** para Q2 (o que está funcionando, o que precisa melhorar)

## Identidade visual

Cores extraídas do Manual da Marca Vendemmia:

| Cor | HEX | Uso |
|-----|-----|-----|
| Roxo | `#422C75` | Primária |
| Off-white | `#FFFCF8` | Fundo |
| Vermelho | `#FF2F69` | Destaque / alerta |
| Verde | `#00E290` | Sucesso / positivo |

## Fonte dos dados

Relatório de Março/2026 — Marketing Vendemmia.

## Stack

- HTML / CSS / Vanilla JS — single file, sem build
- [Chart.js 4.4.0](https://www.chartjs.org/) via CDN

## Histórico de versões

- **v1.0** · Abril/2026 · Dashboard inicial com Q1 2026

# Finance Skills

Este repositório é a oficina de **análise financeira**. As skills ficam em `.claude/skills/`.

## Como responder

- O usuário escreve em **português do Brasil**: responda sempre em português, mesmo que a skill esteja escrita em inglês. Termos técnicos podem ficar em inglês quando não houver tradução comum, com uma explicação curta na primeira vez.
- O usuário tem conhecimento **intermediário**: comece com uma explicação curta do que vai ser feito e por quê, depois entregue o trabalho principal. Textos claros, completos e didáticos.
- Em estratégias e planos, seja o mais avançado e completo possível.
- **Não invente informações.** Se um dado não puder ser verificado (preço, número, fato, fonte), diga que não sabe ou que está no limite do seu conhecimento.

## Como escolher a skill

- Os pedidos chegam em português; as descrições das skills estão em inglês. Use o mapa abaixo para traduzir o pedido na skill certa.
- Se o pedido não bater claramente com uma skill, comece pelo **roteador** indicado no mapa: ele escolhe a especialista.
- Diga ao usuário, em uma linha, qual skill está usando e por quê.

## Arquivos gerados

Sessões na nuvem são apagadas ao terminar. Quando uma skill gerar um arquivo que valha guardar (relatório, plano, contexto), salve-o dentro deste repositório e ofereça fazer commit.

## Mapa de pedidos

Roteador: `finance-skills` (quando o pedido for genérico).

| Pedido em português | Skill |
|---|---|
| "analisa a empresa X", "essa ação está cara?", "fundamentos", "IPO" | `stock-analysis` |
| "valuation", "DCF", "análise de índices", "orçamento", "projeção" | `financial-analyst` |
| "vale a pena investir em (equipamento, imóvel, negócio)?", "VPL/TIR/payback" | `business-investment-advisor` |
| "avalia essa oportunidade de investimento privado/sindicação/crédito privado" | `passive-deal-screener` |
| "métricas de SaaS", "MRR/ARR", "churn", "CAC/LTV" | `saas-metrics-coach` |
| "fechamento do mês", "conciliação" | `month-end-close` |
| "é estatisticamente significativo?", "intervalo de confiança" | `statistical-analyst` |
| "esses dados estão bons?", "outliers" | `data-quality-auditor` |
| "pesquisa a fundo", "decisão importante, preciso de fontes" | `deep-research` |
| "due diligence de empresa/pessoa", "dossiê" | `dossier` |
| "lê esse relatório/10-K/prospecto com atenção" | `deepread` |

Nenhuma skill daqui dá recomendação personalizada de investimento; deixe isso claro quando o usuário pedir "devo comprar?".

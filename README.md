# Finance Skills

Repositório-oficina para **análise financeira** com o Claude Code. Abra uma sessão (claude.ai/code ou local) com este repositório selecionado e o Claude descobre automaticamente as skills em `.claude/skills/`.

Curadoria de [alirezarezvani/claude-skills](https://github.com/alirezarezvani/claude-skills) (licença MIT, ver `LICENSE-claude-skills`), copiada do commit `27cfcd0`.

## O que tem aqui (12 skills)

| Skill | Para que serve |
|---|---|
| `finance-skills` | Índice: escolhe a skill financeira certa quando o pedido é genérico. |
| `stock-analysis` | Análise fundamentalista de uma empresa listada (EUA/global ou Índia) contra o setor: margens, ROE/ROIC, P/L, EV/EBITDA, fluxo de caixa, qualidade contábil, IPOs. Não dá recomendação pessoal nem sinal de trade. |
| `financial-analyst` | Análise de índices, valuation por DCF, orçamento e previsões. |
| `business-investment-advisor` | Vale a pena investir? Equipamento, imóvel, novo negócio, contratação (VPL, TIR, payback). |
| `passive-deal-screener` | Triagem de investimentos privados como cotista passivo (sindicações, crédito privado, fundos). |
| `saas-metrics-coach` | Métricas de SaaS: ARR/MRR, churn, CAC, LTV, NRR. |
| `month-end-close` | Fechamento contábil do mês: calendário, conciliações, análise de variações. |
| `statistical-analyst` | Testes de hipótese, intervalos de confiança, tamanho de amostra. |
| `data-quality-auditor` | Auditoria de dados: lacunas, outliers, inconsistências. |
| `deep-research` | Pesquisa aprofundada, com várias fontes, para perguntas de alto risco. |
| `dossier` | Due diligence sobre empresa/pessoa, com veredito e citações. |
| `deepread` | Leitura rigorosa de documentos que você fornece (relatórios, 10-K, prospectos). |

## Como atualizar

Copie de novo as pastas correspondentes do repositório de origem (`finance/skills/*`, `finance/business-investment-advisor/skills/*`, `engineering/statistical-analyst/skills/*`, `engineering/data-quality-auditor/skills/*`, `research/deep-research/skills/*`, `research/dossier/skills/*`, `research/deepread`) para `.claude/skills/`.

Só as skills foram copiadas; agentes e slash commands dos plugins originais não fazem parte deste repositório.

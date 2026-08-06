# skill-copy-dr-lens

Skill de **copywriting de resposta direta** para Claude Code — nutra, info e nutracêutico.

Cobre anúncios, ganchos, ângulos, corpos, microleads, leads, VSL e ofertas, em pt-BR, espanhol/Latam e inglês.

---

## Instalação

```bash
git clone https://github.com/brinquedo69/skill-copy-dr-lens.git ~/.claude/skills/copy-dr
```

Pronto. Funciona em **qualquer projeto** — `~/.claude/skills/` é o diretório de skills pessoais do Claude Code.

**Para um projeto específico** em vez de global:

```bash
git clone https://github.com/brinquedo69/skill-copy-dr-lens.git <projeto>/.claude/skills/copy-dr
```

---

## Uso

```
/copy-dr preciso de 5 anúncios de emagrecimento pra Latam,
mecanismo é o truque da gelatina, front $9, no Meta
```

Ou só descreva a tarefa — a skill ativa sozinha ao detectar trabalho de copy.

### Casos de uso

| Situação | Exemplo |
|---|---|
| Leva de anúncios | `5 anúncios de <nicho> pra <geo>, mecanismo <X>, ticket <Y>` |
| Nicho novo | `peguei um freela de neuropatia e nunca escrevi pra esse nicho` |
| Modelar oferta | `esse anúncio tá com 400 duplicações. quero entrar sem cair no leilão dele` |
| Diagnóstico | `CTR bom, CPC 0,40, mas CPA 3x o ticket. o que tá errado?` |
| Anúncio bloqueado | `meus anúncios de diabetes tão sendo rejeitados` |
| Ressuscitar oferta | `minha VSL caiu de ROI 2 pra 0.8, quero uma microlead nova` |
| Pesquisa de público | `roda a pesquisa de público de próstata pra EUA` |
| Variar vencedor | `esse criativo fez 47 vendas e nunca variei` |
| Revisão | `revisa esse anúncio` |
| Trocar de geo | `tenho VSL BR com expert, quero levar pro Latam` |

---

## Estrutura

```
SKILL.md          método operacional — carrega primeiro
FONTES.md         proveniência e como estender
referencias/      13 arquivos, ~3.800 linhas destiladas
templates/        artefatos para preencher e colar
```

### Referências

| # | Conteúdo |
|---|---|
| 01 | Ângulos, ganchos e formatos · 7 vícios ocultos · minerar gancho |
| 02 | Empilhar ângulos · nome chiclete · fórmula UGC · sofisticação |
| 03 | 7 frameworks de corpo · provas · gatilhos · erros fatais |
| 04 | Processo completo ao vivo · Frankenstein · bater o controle |
| 05 | Dimensionalização · metáfora de mecanismo · sexy canvas |
| 06 | Microleads · superestrutura · encadeamento de corrente |
| 07 | 8 passos de pesquisa de público · matriz de crenças |
| 08 | Nicho novo em 24h · 6 camadas · comunicação por nível |
| 09 | Deeper Core · 5 porquês · shell vs. core |
| 10 | Rotina · contradição ativa · destravar |
| 11 | Cluster e fatias · métricas · ROI vs. ROAS |
| 12 | Por que copiar parou de funcionar · Latam · bloqueio |
| 13 | Dereck Carneiro — leilão oculto · tendências · diagnóstico de funil |

---

## Benchmarks consolidados

| Métrica | Referência |
|---|---|
| Duração de anúncio | 1 a 3 min |
| Retenção no pitch — info | >30% ideal · <20% problema |
| Retenção no pitch — nutra | ~15% já escala |
| Conversão de upsell | 20-30% |
| Conversão de página fria | 1 a 2% |
| ROI mínimo saudável | **1,6** |
| Funil validado | 1 anúncio + 1 lead + 1 upsell |
| Oferta validada | dinheiro volta com ROI — não é "fez 2 vendas" |
| Ticket de entrada Latam | $9 → $17 → sobe |
| Métricas primárias | CPA e conversão. CTR/CPC são secundárias |

---

## Estendendo

Ao adicionar aula, call ou material novo, siga o protocolo em `FONTES.md` — ele tem o prompt de destilação pronto e as convenções (preservar exemplo literal, número e ferramenta; marcar contradição em vez de sobrescrever).

Buracos conhecidos, para preencher com material futuro: **estrutura de VSL completa**, **tráfego** e **back-end/recorrência**.

---

## Nota

Material destilado de curso e call de comunidade para uso próprio como referência de trabalho. Contém método e números relatados por terceiros, não verificados de forma independente. Proveniência completa em `FONTES.md`.

A skill nunca fabrica estudo, autoridade, certificação ou depoimento — onde a peça exige prova sem fonte real, ela marca `[PROVA A VALIDAR]` para substituição por fonte verificável.

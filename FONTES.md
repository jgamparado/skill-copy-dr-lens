# Fontes e como estender esta skill

## O que está aqui dentro

```
copy-dr/
  SKILL.md                    ← o método operacional (o que carrega primeiro)
  FONTES.md                   ← este arquivo
  referencias/                ← 13 arquivos, ~3.800 linhas destiladas
  templates/                  ← artefatos para preencher e colar
```

**A skill é autocontida.** Não depende de nenhum arquivo fora desta pasta — dá para copiar o diretório inteiro para outra máquina, para `.claude/skills/` de um projeto específico, ou versionar em git.

---

## Proveniência

| # | Referência | Origem | Volume |
|---|---|---|---|
| 01 | Ângulos, ganchos e formatos — a base de tudo | Curso Copy DR, aula 01 | 18.376 palavras |
| 02 | Os 3 pilares de ótimos anúncios | aula 02 | 14.620 |
| 03 | Corpos de anúncio — topo de funil | aula 03 | 11.746 |
| 04 | Escrevendo anúncios ao vivo | aula 04 | 18.706 |
| 05 | Dimensionalizando comunicações | aula 05 | 7.358 |
| 06 | Construindo microleads do zero | aula 06 | 8.266 |
| 07 | Pesquisa de público do zero ao avançado | aula 07 | 17.604 |
| 08 | Dominar um novo nicho em 24h | aula 08 | 11.054 |
| 09 | Deeper Core e Core Influence | aula 09 | 13.902 |
| 10 | Tomadas de decisão do copywriter de 6 e 7 dígitos | aula 10 | 14.164 |
| 11 | Cluster e fatias de público | aula 11 | 12.960 |
| 12 | Finalizando o módulo de anúncios | aula 12 | 14.739 |
| 13 | Método de copy — Dereck Carneiro | Call da comunidade Digital Club | 16.455 |

**Instrutor das aulas 01-12:** Gabriel Covolan (formação Copy DR), líder de squad no Grupo Experience.
**Referência 13:** Dereck Carneiro, em call da comunidade Digital Club.

Transcrições originais em `THOMAS LATAM/CALLS DR CLUB/TRANSCRICOES/` (fora da skill, por peso).

---

## Tensões deliberadamente preservadas

Estas contradições **não foram resolvidas** — os dois lados estão registrados porque a escolha é sua e depende do momento do seu negócio.

**Onde está o jogo.** Covolan e Dereck descrevem a mesma saturação de mercado (a onda de "famoso no anúncio") e reagem de forma oposta:
- **Covolan:** dobra a aposta em anúncio. *"Oferta virou commodity. O 80/20 das operações é anúncio."*
- **Dereck:** migra para marca/DTC, porque tráfego direto é ótimo para fazer caixa e ruim para construir negócio.

**IA no processo.**
- **Covolan** é contra agentes: *"fica automático, você para de ler as pesquisas e perde a mão."* Usa IA como extensão do cérebro, para gerar ideias — nunca para escrever a peça final.
- **Dereck:** *"100% dos meus anúncios são escritos por IA. Sem exceção."* A VSL ele escreve à mão.

**"Estrutura invisível".** Covolan afirma que não existe (*"ela é visível, você que não sabe ler"*) — e o anúncio de maior performance dele foi justamente atacar essa crença.

---

## Como adicionar conteúdo novo

Quando subir uma nova aula, call, transcrição ou material:

**1. Destile num arquivo em `referencias/`**, numerado na sequência (`14-`, `15-`…). Convenções que valem a pena manter:
- Preservar **exemplos literais de copy** — ganchos, leads e anúncios escritos ao vivo são o ativo mais reaproveitável
- Preservar **números, benchmarks e nomes de ferramenta**
- Registrar **quem disse** e em que contexto
- **Marcar contradição** com o que já existe, em vez de sobrescrever
- Não inventar: se a transcrição está confusa ou truncada, anotar

**2. Adicione a linha no índice do `SKILL.md`** — a coluna "abra quando precisar de" é o que faz a referência ser encontrada na hora certa.

**3. Se o material mudar uma regra**, atualize a seção correspondente do `SKILL.md` (não-negociáveis, benchmarks, anti-padrões) e **anote a mudança aqui**, com a data e a fonte. O método é sensível a timing — o que valia há 6 meses pode não valer mais.

**4. Se for material de outro autor**, registre na tabela de proveniência acima e, havendo divergência, adicione às tensões preservadas.

### Prompt para destilar material novo

```
Leia a transcrição em [CAMINHO] na íntegra.

Destile num arquivo de referência para a skill copy-dr, seguindo o padrão
dos arquivos em referencias/. Preserve:
- exemplos literais de copy (ganchos, leads, anúncios escritos ao vivo)
- números, benchmarks e nomes de ferramenta
- processos passo a passo, na ordem em que foram executados
- quem disse e em que contexto

Marque explicitamente onde contradiz o que já está nas referências existentes.
Não invente nada — se a transcrição estiver confusa, anote.

Depois adicione a linha no índice do SKILL.md e registre a origem no FONTES.md.
```

---

## Escopo e limite

Método de **resposta direta para nutra, info e nutracêutico**, com foco em topo de funil (anúncio) e início de funil (gancho, lead, microlead).

Cobertura mais rasa, por serem tratados de passagem nas fontes:
- **Estrutura de VSL completa** — as fontes preparam o terreno mas o módulo de oferta não está nas 12 aulas
- **Tráfego** — o próprio instrutor se declara não especialista
- **Back-end, recorrência e reembolso** — aparecem em casos pontuais

São os buracos naturais para preencher com o próximo material que você subir.

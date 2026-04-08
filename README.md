# Copywriter Skill for Claude Code

Skill de redator publicitário e institucional para o [Claude Code](https://claude.ai/code).

Transforma o Claude em um copywriter profissional que domina frameworks clássicos de persuasão, redação institucional e comunicação de marketing — com foco em **português brasileiro (pt-BR)**.

## O que faz

- Textos de marketing e publicidade (landing pages, e-mails, anúncios)
- Redação institucional (sobre, missão, manifesto, proposta de valor)
- Chamadas e CTAs de alta conversão
- Posts para redes sociais
- Comunicados, releases e propostas comerciais
- Scripts de vídeo (VSL, institucional)
- Naming e taglines

## Frameworks incluídos

| Framework | Quando usar |
|---|---|
| **AIDA** | Landing pages, e-mails de vendas |
| **PAS** | Produtos que resolvem dor forte |
| **BAB** | Posts curtos, ads, blurbs promocionais |
| **FAB** | Páginas de produto, propostas B2B |
| **PPPP** | Alta desconfiança, B2B complexo |
| **PASTOR** | Cartas de venda longas, VSLs, webinars |
| **SLAP** | Flash sales, ofertas rápidas |

## Referências teóricas

- **Eugene Schwartz** — 5 estágios de consciência do consumidor
- **David Ogilvy** — headlines, especificidade, pesquisa
- **Gary Halbert** — escrita para uma pessoa, voz do cliente
- **Robert Cialdini** — gatilhos mentais (reciprocidade, prova social, escassez, autoridade, afinidade, coerência)
- **Checklist 4Cs** — Claro, Conciso, Convincente, Crível
- **Checklist anti-AI** — para textos que soam humanos, não robóticos

## Instalacao

Clone este repositorio na pasta de skills do Claude Code:

```bash
cd ~/.claude/skills
git clone https://github.com/durvs/copywriter-skill.git copywriter
```

Pronto. O comando `/copywriter` fica disponivel automaticamente.

## Uso

No Claude Code, chame:

```
/copywriter Escreva o hero de uma landing page para um app de gestao condominial.
O publico sao administradoras de condominios. Tom profissional mas acessivel.
```

O skill vai:
1. Diagnosticar publico-alvo e estagio de consciencia
2. Escolher o framework mais adequado
3. Redigir o copy
4. Aplicar checklist de revisao (4Cs + anti-AI)
5. Entregar variacoes de headlines e CTAs

## Licenca

MIT

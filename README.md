# Claude Cowork — Guia Completo

Curso completo sobre **Claude Cowork** (Projects no claude.ai), recurso por recurso.

**Site publicado:** https://inematds.github.io/cccoworkfull/

## Estrutura

3 trilhas, 18 módulos:

- **T1 — Fundamentos do Cowork** (Emerald) — 6 módulos
  1. O que é Cowork (Projects)
  2. Anatomia da interface
  3. Planos e limites (Pro/Max/Team/Enterprise)
  4. Chat / Cowork / Code — o veículo certo
  5. Criando seu primeiro projeto
  6. Segurança e governança

- **T2 — Recursos Centrais** (Blue) — 6 módulos
  1. Custom Instructions
  2. Knowledge Files
  3. Conversas e histórico
  4. Artifacts
  5. Opus / Sonnet / Haiku
  6. Extended Thinking, Search, Research

- **T3 — Workflows e Operação** (Purple) — 6 módulos
  1. Templates de projeto
  2. Trabalho em equipe
  3. Integrações e MCP
  4. Skills, Slash Commands e Agents
  5. Manutenção e drift
  6. Métricas, custos e migração

## Formato

HTML estático com Tailwind CDN. Sem build step — abre direto no browser ou via GitHub Pages.

Padrão visual: [INEMA.CLUB](https://inema.club).

## Estrutura de arquivos

```
cccoworkfull/
├── index.html                    # Landing
├── curso/
│   ├── trilha1/
│   │   ├── index.html
│   │   ├── modulo-1-1.html ... modulo-1-6.html
│   ├── trilha2/
│   │   └── (mesma estrutura)
│   └── trilha3/
│       └── (mesma estrutura)
└── README.md
```

## Como atualizar GitHub Pages

`Settings → Pages → Source: Deploy from a branch → main → / (root) → Save`
(Já configurado.)

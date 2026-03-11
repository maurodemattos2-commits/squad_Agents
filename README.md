# Squads Agents

Colecao com 12 squads de agentes IA especializados para estrategia, marketing, execucao e operacao tecnica.

## Status de Verificacao (2026-03-11)

Verificacao executada no repositorio para garantir que cada squad possui os componentes essenciais.

- Squads mapeadas: 12
- Agentes totais: 144
- Tasks totais: 120
- Workflows totais: 24
- Arquivos de dados totais: 27

### Checklist usado na verificacao

- `README.md`
- `agents/` com agentes definidos
- `tasks/` com tarefas definidas
- `workflows/` com fluxos definidos
- `checklists/`
- `data/`
- Manifesto (`squad.yaml` ou `config.yaml`, dependendo da arquitetura)
- Configuracao (`config/` ou `config.yaml`)

## Inventario Completo das Squads

| Squad | Agentes | Tasks | Workflows | Dados | Manifesto/Config | Status |
|------|---------|-------|-----------|-------|------------------|--------|
| advisory-board | 11 | 7 | 2 | 2 | `squad.yaml` + `config/` | Completa |
| brand-squad | 15 | 9 | 2 | 2 | `squad.yaml` + `config/` | Completa |
| c-level-squad | 6 | 7 | 2 | 2 | `squad.yaml` + `config/` | Completa |
| claude-code-mastery | 8 | 26 | 3 | 5 | `config.yaml` (arquitetura propria) | Completa |
| copy-squad | 23 | 13 | 2 | 2 | `squad.yaml` + `config/` | Completa |
| cybersecurity | 15 | 9 | 2 | 2 | `squad.yaml` + `config/` | Completa |
| data-squad | 7 | 7 | 2 | 2 | `squad.yaml` + `config/` | Completa |
| design-squad | 8 | 8 | 2 | 2 | `squad.yaml` + `config/` | Completa |
| hormozi-squad | 16 | 10 | 2 | 2 | `squad.yaml` + `config/` | Completa |
| movement | 7 | 7 | 1 | 2 | `squad.yaml` + `config/` | Completa |
| storytelling | 12 | 8 | 2 | 2 | `squad.yaml` + `config/` | Completa |
| traffic-masters | 16 | 9 | 2 | 2 | `squad.yaml` + `config/` | Completa |

## Como Usar

1. Entre na pasta da squad desejada.
2. Leia o `README.md` da squad para o quick start.
3. Ative o agente orquestrador (exemplo: `@board-chair`, `@copy-chief`).
4. Execute uma task (exemplo: `*diagnose`).
5. Quando existir, rode workflow completo para entregas maiores.

Exemplo:

```txt
@copy-chief
*diagnose
*full-copy-project
```

## Estrutura Padrao de Squad

```txt
squad-name/
├── squad.yaml          # Manifesto da squad (ou config.yaml em arquitetura propria)
├── agents/             # Definicoes dos agentes
├── tasks/              # Tasks executaveis
├── workflows/          # Workflows multi-agente
├── checklists/         # Checklists de qualidade
├── config/             # Configuracoes
└── data/               # Catalogos e frameworks de apoio
```

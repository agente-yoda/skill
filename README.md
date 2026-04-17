# 📚 Engineering Team Skills — Índice Mestre
> Conjunto de skills para uso no OpenClaw / Claude Code  
> Baseado na estrutura de engenharia para aplicações críticas

---

## Como usar no Claude Code

```bash
# Carregar um skill específico para uma conversa
/skill load cto
/skill load tech-lead
/skill load sre-devops
```

No OpenClaw, referencie o caminho do arquivo:
```
skills/[nome-do-papel]/SKILL.md
```

---

## 📋 Índice de Skills (13 skills disponíveis)

| # | Papel | Arquivo | Foco Principal |
|---|---|---|---|
| 1 | CTO | `cto/SKILL.md` | Visão estratégica, decisões arquiteturais macro, liderança executiva |
| 2 | VP de Engenharia | `vp-engineering/SKILL.md` | Gestão de times, processos, entrega e people management |
| 3 | VP de Arquitetura | `vp-architecture/SKILL.md` | Coerência técnica cross-squad, ADRs, Tech Radar, fitness functions |
| 4 | Engineering Manager | `engineering-manager/SKILL.md` | Pessoas, processo, 1:1s, saúde do time |
| 5 | Tech Lead | `tech-lead/SKILL.md` | Arquitetura de squad, code review, mentoria técnica |
| 6 | Desenvolvedor Senior / Full-Stack | `fullstack-developer/SKILL.md` | Backend, frontend, banco de dados, qualidade de código |
| 7 | SRE / DevOps | `sre-devops/SKILL.md` | Cloud, Kubernetes, CI/CD, observabilidade, IaC |
| 8 | Data Engineer | `data-engineer/SKILL.md` | Pipelines, warehousing, dbt, qualidade de dados |
| 9 | ML Engineer | `ml-engineer/SKILL.md` | Modelos em produção, MLOps, LLMs, serving |
| 10 | QA Engineer | `qa-engineer/SKILL.md` | Automação, testes de performance, qualidade de processo |
| 11 | Security Engineer | `security-engineer/SKILL.md` | AppSec, cloud security, compliance, pentest |
| 12 | Product Manager | `product-manager/SKILL.md` | Discovery, roadmap, histórias de usuário, métricas |
| 13 | UX Designer | `ux-designer/SKILL.md` | Pesquisa, design system, acessibilidade, handoff |

---

## 🏗️ Estrutura de Cada Skill

Todos os skills seguem o mesmo template:

```
# SKILL: [Nome do Papel]

## Identidade e Propósito
## Responsabilidades Primárias
## Habilidades Técnicas (Hard Skills)
## Habilidades de Liderança/Processo/Colaboração (Soft Skills)
## Comportamento Esperado
## Formato de Saída Preferido
## Restrições e Limites
```

---

## 🔄 Combinações de Skills Recomendadas

### Para revisão de arquitetura
```
CTO + VP Arquitetura + Tech Lead
```

### Para planejamento de sprint
```
Engineering Manager + Tech Lead + Product Manager
```

### Para incident response
```
SRE/DevOps + Tech Lead + Security Engineer
```

### Para design de nova feature
```
Product Manager + UX Designer + Tech Lead
```

### Para pipeline de dados com ML
```
Data Engineer + ML Engineer + SRE/DevOps
```

---

## 📏 Princípios Transversais a Todos os Skills

1. **Segurança é responsabilidade de todos** — não apenas do Security Engineer
2. **Documentação é parte da entrega** — não uma tarefa posterior
3. **Observabilidade primeiro** — nada vai a produção sem logs, métricas e traces
4. **Feedback rápido** — loops curtos de validação em todos os papéis
5. **You build it, you run it** — ownership completo, do código ao on-call

---

## 🔧 Manutenção dos Skills

- Revisão trimestral recomendada para atualizar ferramentas e práticas
- Versione os skills junto ao código (git)
- Contribuições: abra PR com justificativa para qualquer alteração

# RevisAI

Plataforma web de revisão inteligente de documentos com IA — trabalho final da disciplina **Engenharia de Requisitos e Gestão Ágil de Produtos / Gestão Ágil de Projetos**.

## Sobre o Produto

O RevisAI permite que organizações automatizem a revisão de documentos com base em checklists curados por especialistas, usando RAG (Retrieval Augmented Generation) e LLMs. Gestores de Tema configuram checklists, contexto documental e critérios de análise; Autores de Relatório submetem documentos e recebem um parecer automatizado por item de verificação.

**Personas:** Administrador do Sistema · Gestor de Tema · Autor do Relatório

## Estrutura do Repositório

```
/
├── README.md
├── canvas-url.txt          # URL do board Miro com a Lean Inception completa
├── product-backlog.pdf     # Backlog do produto com épicos, features, histórias, DoR e DoD
├── sprint-backlog.pdf      # Backlog da Sprint 1 com histórias detalhadas e critérios de aceitação
├── wireframes/             # Protótipos (Figma)
│   ├── geral.png
│   ├── gerenciamento_checklist.png
│   ├── nova_revisao.png
│   ├── resultado_revisao.png
│   └── historico.png
└── video-url.txt               # Vídeo de apresentação do projeto
```

## Artefatos

### Lean Inception (Miro)
Board completo com todas as etapas da Lean Inception: Visão do Produto, É / Não É / Faz / Não Faz, Objetivos do Produto, Personas, Jornadas, Brainstorming de Features, Revisão Técnica/de Negócio/UX, Sequencer e MVP Canvas.

→ Ver `canvas-url.txt`

### Backlog do Produto (Jira)
Backlog estruturado em 6 épicos (3 de MVP + 3 incrementos), com 13 features e 24 histórias de usuário/enablers. Inclui Definition of Ready (DoR) e Definition of Done (DoD) com requisitos não funcionais.

Rastreado em: [Board Jira](https://ttozatto.atlassian.net/jira/software/projects/SCRUM/boards/1?atlOrigin=eyJpIjoiOWIzZjJhMzczNjA1NDFlMGIwM2EwNTk3MDY4ZjkyYjQiLCJwIjoiaiJ9)

→ Ver `product-backlog.pdf`

### Backlog da Sprint 1 (Jira)
Sprint com meta definida e 18 story points planejados, cobrindo infraestrutura base, autenticação/RBAC e as primeiras histórias de administração de temas. Todos os itens com estimativas e critérios de aceitação.

→ Ver `sprint-backlog.pdf`

### Wireframes (Figma)
Protótipos das telas: gerenciamento de checklist, nova revisão, resultado da revisão e histórico.

→ Ver pasta `wireframes/`

### Vídeo de Apresentação
Showcase do projeto em 2–4 minutos.

→ Ver `video-url.txt`

## Time Scrum

| Papel | Habilidades |
|---|---|
| Product Owner | Domínio do negócio, priorização de backlog |
| Scrum Master / Dev Backend | Python/FastAPI, LLM APIs, RAG, banco de dados |
| Dev Backend / IA | Embeddings, processamento de documentos, LLMs |
| Dev Frontend | React, TypeScript, UX |

**Duração do MVP:** 3 meses · **Capacidade:** ~20 SP/sprint · **Total planejado:** 157 SP

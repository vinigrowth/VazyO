---
name: novo-projeto
description: Cria uma pasta isolada para um novo cliente ou projeto dentro do Vazyo.
---

# /novo-projeto

Perguntar:
1. "Nome do cliente ou projeto?"
2. "Qual é o objetivo principal? (ex: página de vendas, site institucional, lançamento)"

Criar estrutura:
```
projetos/[nome-do-projeto]/
├── briefing.md      — contexto do cliente
├── entregas/        — arquivos gerados
└── notas.md         — observações e histórico
```

Preencher `briefing.md` com as respostas.

> "Projeto [nome] criado. Próximo passo: /pagina-de-vendas, /site ou /ebook?"

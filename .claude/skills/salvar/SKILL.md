---
name: salvar
description: Faz commit e push de tudo no GitHub. Usar ao fim de cada sessão ou entrega importante.
---

# /salvar

Executar em sequência:

```bash
git add .
git commit -m "vazyo: atualização $(date +'%d/%m/%Y %H:%M')"
git push
```

Se der erro de remote não configurado:
> "Repositório não conectado ainda. Rode: git remote add origin https://github.com/vinigrowth/VazyO.git"

Ao finalizar:
> "Salvo. Tudo no GitHub."

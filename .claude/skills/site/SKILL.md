---
name: site
description: Cria site completo para empresa ou profissional — institucional, portfólio ou landing. UI/UX profissional, identidade própria por nicho, deploy automático.
---

# /site

## Briefing

1. "Tipo de site: institucional, portfólio, landing page ou outro?"
2. "Qual o nicho? (clínica, advogado, restaurante, agência...)"
3. "Quais páginas ou seções precisa?"
4. "Tem identidade visual? (cores, logo, fontes)"
5. "Qual ação principal você quer que o visitante tome?"

---

## Diretrizes por nicho

Antes de escrever uma linha de código, definir:
- Paleta de cores específica do nicho (nunca reutilizar entre nichos diferentes)
- Tipografia com personalidade — não usar Inter + Roboto pra tudo
- Elemento de assinatura visual único para este site
- Tom do copy alinhado com o público

Exemplos de personalidade por nicho:
- Clínica odontológica → clean, confiança, branco + tom suave, foto real
- Escritório de advocacia → autoridade, escuro, serifa, sobriedade
- Personal trainer → energia, contraste alto, bold, antes/depois
- Restaurante → sensorial, cores quentes, tipografia expressiva
- Agência criativa → ousado, movimento, identidade forte

---

## Estrutura padrão

**Header** — logo + nav limpa + CTA
**Hero** — proposta de valor em até 2 linhas + CTA + visual forte
**Prova/Credibilidade** — números, clientes, selos
**Serviços/Produtos** — benefícios, não características
**Depoimentos** — reais, com nome e contexto
**Sobre** — humano, direto, sem corporativês
**Contato/CTA final** — simples, sem atrito
**Footer** — mínimo necessário

---

## Padrões obrigatórios

- Mobile-first
- Máximo 3 linhas por parágrafo no mobile
- Zero linhas órfãs
- Zero travessão em títulos e copy
- Scroll suave, animações de entrada discretas
- Imagens com alt text
- Meta title e description preenchidos

---

## Deploy

Mesmo fluxo de `/pagina-de-vendas`:
1. Netlify token presente → deploy + URL pública
2. Sem token → servidor local porta 8080

Salvar em `saidas/[nome-projeto]/`

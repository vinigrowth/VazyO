---
name: ebook
description: Cria e-book completo em HTML elegante — estrutura, copy, layout visual por nicho, ilustrações em SVG e prompts de imagem prontos para cada seção-chave.
---

# /ebook

## Briefing

1. "Qual o título ou tema do e-book?"
2. "Para quem é? (perfil do leitor em uma linha)"
3. "Quantos capítulos ou módulos?"
4. "Qual a transformação que o leitor vai ter ao terminar?"
5. "Tem identidade visual definida?"

---

## Estrutura obrigatória

```
Capa
Sumário
Introdução
Capítulo 1
  ...
Capítulo N
Conclusão + CTA
Sobre o autor
```

---

## Páginas-chave com elemento visual

Nas seguintes páginas, gerar **SVG ilustrativo** integrado ao layout:
- Capa — composição visual forte com título
- Sumário — ícones por capítulo
- Abertura de cada capítulo — ilustração abstrata alinhada ao tema
- Conclusão — elemento de encerramento

Além do SVG, gerar **prompt de imagem** logo abaixo de cada um:
```
[PROMPT PARA IMAGEM IA]
Estilo: ...
Elemento principal: ...
Paleta: ...
Proporção: 16:9 / quadrado
```
O leitor pode usar no Midjourney, Leonardo ou DALL-E e substituir pelo resultado.

---

## Padrões visuais

- Layout elegante, moderno — nunca parecer Word ou Google Docs
- Tipografia com personalidade: título display + corpo legível
- Paleta derivada do nicho
- Máximo 250 palavras por página no mobile
- Parágrafos curtos — nunca mais de 4 linhas seguidas
- Citações destacadas visualmente (blockquote estilizado)
- Zero travessão em títulos e subtítulos
- Zero linhas órfãs

---

## Entrega

- Arquivo único `ebook.html` com CSS interno
- Cada capítulo em `<section>` com classe própria
- Print-friendly: `@media print` definido
- Salvar em `saidas/ebooks/[titulo]/ebook.html`
- Preview automático no browser ao finalizar

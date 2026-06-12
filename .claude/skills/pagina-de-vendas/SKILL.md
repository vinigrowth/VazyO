---
name: pagina-de-vendas
description: Cria uma página de vendas completa com copy estratégica para público frio, UI/UX profissional e deploy automático.
---

# /pagina-de-vendas

## Briefing (perguntar em sequência)

1. "O que você vende? (produto, curso, serviço — uma linha)"
2. "Qual o maior medo ou dor do seu cliente antes de comprar?"
3. "Qual a transformação que você entrega? Antes e depois."
4. "Tem prova social? (depoimentos, números, resultados)"
5. "Qual o preço e o que está incluído?"
6. "Tem prazo, bônus ou escassez real?"

---

## Estrutura da página (ordem obrigatória)

**1. Hero**
- Headline: dor ou desejo em até 7 palavras
- Subheadline: a transformação em uma frase
- CTA primário acima da dobra
- Elemento visual de credibilidade (selo, número, logo)

**2. Agitação do problema**
- 3 blocos curtos — dor específica, não genérica
- Linguagem do cliente, não do vendedor

**3. Apresentação da solução**
- O que é, o que não é
- Por que funciona — mecanismo único

**4. Prova social**
- Depoimentos com foto, nome e resultado específico
- Números quando existirem

**5. O que está incluído**
- Lista visual, ícones, benefícios não características

**6. Sobre você**
- Autoridade em 3 linhas — resultado, não currículo

**7. Oferta e garantia**
- Preço com ancoragem se possível
- Garantia destacada — remove risco

**8. CTA final**
- Urgência real ou escassez
- Botão com verbo + benefício

---

## Padrões de código

- HTML + CSS em arquivo único
- Mobile-first — testar mentalmente no celular antes de entregar
- Fonte: Inter ou similar — limpa, moderna, legível
- Paleta derivada do nicho — nunca roxo-azul genérico
- Animações sutis no scroll — nada que distraia
- Parágrafos máximo 3 linhas no mobile
- Nenhuma linha órfã
- Zero travessão em títulos

---

## Deploy

Ao finalizar o HTML:

**Se `_config/netlify.token` existir:**
```bash
npm install -g netlify-cli 2>/dev/null
export NETLIFY_AUTH_TOKEN=$(cat _config/netlify.token)
netlify deploy --prod --dir=saidas/[nome-projeto] --message "Página de vendas"
```
Retornar a URL pública.

**Se não existir:**
```bash
cd saidas/[nome-projeto] && python3 -m http.server 8080
```
> "Preview rodando em http://localhost:8080 — abre no navegador."

Salvar o arquivo em `saidas/[nome-projeto]/index.html`

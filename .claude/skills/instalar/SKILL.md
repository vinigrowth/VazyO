---
name: instalar
description: Setup inicial do Vazyo. Entrevista o usuário, monta a memória e configura o sistema. Rodar uma única vez.
---

# /instalar

Boas-vindas ao Vazyo. Vamos configurar tudo em minutos.

Fazer as perguntas abaixo em sequência — uma por vez, aguardar resposta antes de continuar. Tom leve e encorajador.

---

## Perguntas de setup

**1. Qual é o seu nome?**

**2. Como se chama seu negócio ou projeto?**

**3. O que você faz? Escolha o que mais se encaixa:**
- [ ] Criador de infoprodutos (cursos, e-books, mentorias)
- [ ] Agência ou freelancer de marketing/design
- [ ] Negócio local ou prestador de serviços
- [ ] Outro (descreva em uma linha)

**4. Quem é seu cliente ideal? Descreva em uma frase.**
Ex: "Mulheres 30-45 que querem emagrecer sem academia"

**5. Qual o maior resultado que você já entregou ou quer entregar?**
Ex: "Ajudei 200 alunos a faturarem R$10k/mês"

**6. Como você quer que o Vazyo escreva pra você?**
- [ ] Direto e objetivo
- [ ] Próximo e conversacional
- [ ] Sofisticado e profissional
- [ ] Ousado e provocativo

**7. Tem identidade visual definida? (cores, fonte, logo)**
- [ ] Sim (me fala as cores principais e o nome da fonte se souber)
- [ ] Não ainda

**8. Quer conectar o Netlify pra publicar sites automaticamente?**
- [ ] Sim (vou te guiar em 2 passos)
- [ ] Agora não

---

## Após as respostas

1. Criar e preencher `_memoria/negocio.md` com nome, negócio, cliente ideal, resultado
2. Criar e preencher `_memoria/foco.md` com prioridade inicial baseada no tipo de negócio
3. Criar e preencher `_memoria/preferencias.md` com tom de voz escolhido
4. Se tiver identidade visual → preencher `identidade/guia.md`
5. Se quiser Netlify → orientar: "Acesse app.netlify.com → User Settings → Applications → New access token → copie e me cole aqui"
   - Salvar token em `_config/netlify.token`
   - Adicionar `_config/netlify.token` ao `.gitignore`

Ao finalizar:
> "[Nome], o Vazyo tá pronto. Seus primeiros comandos: /pagina-de-vendas, /site ou /ebook. Qual projeto quer atacar primeiro?"

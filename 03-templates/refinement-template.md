# Template de Refinamento

## Objetivo

Este documento fornece um modelo padrão para preparação e condução de refinamentos.

O objetivo é garantir que a funcionalidade seja apresentada com contexto suficiente, regras claras e critérios de aceite compreensíveis para Engenharia e QA, reduzindo dúvidas antes do desenvolvimento.

Este template deve ser adaptado conforme a complexidade da demanda.

---

## Quando usar este template

Usar este template quando for necessário:

- preparar uma funcionalidade para refinamento;
- organizar a apresentação de uma demanda ao time;
- estruturar os principais pontos de discussão;
- registrar dúvidas, riscos e encaminhamentos após a conversa.

---

## Estrutura padrão

### Título

Identificar claramente a funcionalidade refinada.

**Exemplo:**

```text
Refinamento — Filtro por CNPJ na listagem do Cofre
```

---

### Objetivo da entrega

Descrever de forma objetiva o que a funcionalidade pretende resolver ou viabilizar.

**Modelo:**

```text
Objetivo: [descrever o objetivo da funcionalidade]
```

---

### Problema

Registrar qual problema motivou a funcionalidade.

Responder, sempre que possível:

- o que acontece hoje;
- por que isso é um problema;
- qual impacto gera;
- quem é afetado.

---

### Contexto

Descrever o contexto necessário para entendimento da funcionalidade.

Pode incluir:

- comportamento atual;
- fluxo relacionado;
- funcionalidades impactadas;
- regra já existente;
- limitação conhecida;
- dependência com outro fluxo.

---

### Escopo da conversa

Registrar o que será tratado no refinamento.

Isso ajuda a alinhar expectativa e evita que a conversa fique solta.

**Modelo:**

```text
Neste refinamento serão abordados:
- [ponto 1]
- [ponto 2]
- [ponto 3]
```

---

### Feature relacionada

Inserir a Feature que está sendo refinada ou o link para ela, quando aplicável.

Também pode ser incluído um resumo breve da estrutura da Feature:

- história do usuário;
- regras de negócio;
- critérios de aceite;
- observações.

---

### Pontos principais para validação

Listar o que precisa ser validado com o time durante o refinamento.

Exemplos:

- entendimento do fluxo;
- entendimento das regras;
- impactos técnicos;
- clareza dos cenários;
- dependências;
- riscos;
- necessidade de quebra de escopo;
- impactos em QA.

**Modelo:**

```text
- [Ponto de validação 1]
- [Ponto de validação 2]
- [Ponto de validação 3]
```

---

### Regras de negócio em foco

Destacar as regras mais importantes ou mais sensíveis da funcionalidade.

Essa seção ajuda a conduzir a conversa para o que realmente exige validação.

**Modelo:**

```text
- [Regra relevante 1]
- [Regra relevante 2]
- [Regra relevante 3]
```

---

### Dúvidas em aberto antes do refinamento

Registrar dúvidas já identificadas antes da conversa.

O objetivo é não entrar no refinamento fingindo que tudo está resolvido.

**Modelo:**

```text
- [Dúvida 1]
- [Dúvida 2]
- [Dúvida 3]
```

---

### Riscos e dependências

Registrar riscos, impactos e dependências que precisam ser considerados.

Exemplos:

- dependência de outro time;
- limitação técnica;
- impacto em outro fluxo;
- necessidade de validação externa;
- alinhamento com Design;
- alinhamento com stakeholders.

**Modelo:**

```text
- [Risco ou dependência 1]
- [Risco ou dependência 2]
```

---

### Encaminhamentos após o refinamento

Após a conversa, registrar o que ficou decidido e o que precisa de ajuste.

Pode incluir:

- ajustes na Feature;
- pendências;
- validações necessárias;
- necessidade de novo alinhamento;
- mudança de escopo;
- definição de próximos passos.

**Modelo:**

```text
- [Encaminhamento 1]
- [Encaminhamento 2]
- [Encaminhamento 3]
```

---

## Template base

Copiar e preencher conforme a necessidade:

```markdown
# Refinamento — [Título da funcionalidade]

## Objetivo da entrega

[Descrever o objetivo da funcionalidade]

## Problema

[Descrever o problema que motivou a demanda]

## Contexto

[Descrever o comportamento atual, fluxo relacionado e contexto necessário]

## Escopo da conversa

- [Ponto 1]
- [Ponto 2]
- [Ponto 3]

## Feature relacionada

[Link ou resumo da Feature]

## Pontos principais para validação

- [Ponto de validação 1]
- [Ponto de validação 2]
- [Ponto de validação 3]

## Regras de negócio em foco

- [Regra 1]
- [Regra 2]
- [Regra 3]

## Dúvidas em aberto antes do refinamento

- [Dúvida 1]
- [Dúvida 2]

## Riscos e dependências

- [Risco ou dependência 1]
- [Risco ou dependência 2]

## Encaminhamentos após o refinamento

- [Encaminhamento 1]
- [Encaminhamento 2]
```

---

## Boas práticas

Ao usar este template:

- começar a conversa pelo problema e pelo objetivo;
- dar contexto antes de entrar em regra;
- destacar regras sensíveis;
- explicitar dúvidas antes da conversa;
- usar a seção de encaminhamentos para registrar o que mudou;
- revisar a Feature após o refinamento, quando necessário.

---

## O que evitar

Evitar:

- refinamento sem contexto;
- reunião guiada apenas por leitura de card;
- esconder dúvida relevante;
- discutir solução sem explicar o problema;
- sair da conversa sem registrar pendências;
- usar o template como ata extensa sem foco prático.

---

## Objetivo final

Este template deve ajudar a tornar o refinamento mais claro, mais direcionado e mais útil para Produto, Engenharia e QA.

Se ao final da conversa ainda não estiver claro o que fazer, como aplicar as regras ou como validar a funcionalidade, a demanda precisa ser ajustada antes de seguir.

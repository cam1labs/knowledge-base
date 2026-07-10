# Template de Discovery

## Objetivo

Este documento fornece um modelo padrão para condução e registro de discovery.

O objetivo é organizar o entendimento da demanda, reduzir incertezas, explicitar regras e gerar insumos suficientes para definição da solução e posterior escrita da Feature.

Este template deve ser adaptado conforme a complexidade da demanda.

---

## Quando usar este template

Usar este template quando for necessário:

- entender melhor um problema;
- investigar contexto antes da solução;
- levantar regras de negócio;
- mapear riscos e dependências;
- estruturar uma demanda antes da definição da solução;
- registrar o discovery de forma reutilizável.

---

## Estrutura padrão

### Título

O título deve identificar claramente a demanda ou problema analisado.

**Exemplo:**

```text
Discovery — Filtro por CNPJ na listagem do Cofre
```

---

### Origem da demanda

Registrar de onde surgiu a necessidade.

Exemplos:

- feedback de usuário;
- ticket;
- solicitação interna;
- problema operacional;
- oportunidade identificada por Produto;
- análise de dados;
- necessidade estratégica.

**Modelo:**

```text
Origem: [descrever origem da demanda]
```

---

### Problema

Descrever qual problema está sendo investigado.

Responder, sempre que possível:

- o que acontece hoje;
- por que isso é um problema;
- qual impacto gera;
- quem é impactado.

**Modelo:**

```text
[Descrever o problema de forma objetiva]
```

---

### Objetivo do discovery

Descrever o que este discovery busca esclarecer.

**Modelo:**

```text
Este discovery tem como objetivo entender [problema], levantar [regras, riscos, contexto, limitações] e gerar direcionamento para definição da solução.
```

---

### Usuário ou área impactada

Registrar quem é impactado pelo problema ou pela futura solução.

Pode incluir:

- usuário final;
- suporte;
- CS;
- comercial;
- operação interna;
- áreas técnicas;
- múltiplos perfis.

---

### Contexto atual

Descrever como funciona hoje.

Responder, quando aplicável:

- qual fluxo existe atualmente;
- onde o problema acontece;
- como o usuário executa a tarefa hoje;
- quais limitações existem;
- se há comportamento parecido em outro lugar do produto.

---

### Evidências e insumos

Registrar os insumos utilizados no discovery.

Podem incluir:

- dados do negócio;
- dados de comportamento;
- Mixpanel;
- tickets;
- falas de usuários;
- testes;
- pesquisas;
- jornada atual;
- alinhamento com outras áreas;
- documentação existente;
- benchmark ou concorrentes.

**Modelo:**

```text
- [Insumo 1]
- [Insumo 2]
- [Insumo 3]
```

---

### Descobertas principais

Registrar os principais achados do discovery.

Esses achados devem refletir o que foi aprendido sobre:

- problema;
- comportamento do usuário;
- fluxo atual;
- limitações;
- oportunidades;
- dependências;
- riscos;
- inconsistências.

**Modelo:**

```text
- [Descoberta 1]
- [Descoberta 2]
- [Descoberta 3]
```

---

### Regras de negócio identificadas

Listar regras já levantadas durante o discovery.

Aqui devem entrar regras que impactam diretamente a solução ou a especificação futura.

**Modelo:**

```text
- [Regra 1]
- [Regra 2]
- [Regra 3]
```

---

### Riscos e dependências

Registrar riscos, restrições e dependências identificadas.

Exemplos:

- dependência de outro time;
- limitação técnica;
- limitação de integração;
- dependência de alinhamento com stakeholders;
- impacto em fluxo existente;
- necessidade de validação adicional.

**Modelo:**

```text
- [Risco ou dependência 1]
- [Risco ou dependência 2]
```

---

### Dúvidas em aberto

Registrar explicitamente o que ainda não está resolvido.

O objetivo é não deixar lacunas invisíveis.

**Modelo:**

```text
- [Dúvida 1]
- [Dúvida 2]
- [Dúvida 3]
```

---

### Direcionamento da solução

Registrar, quando já houver maturidade suficiente, o direcionamento construído a partir do discovery.

Não precisa ser a Feature pronta, mas deve indicar o caminho que a solução tende a seguir.

Pode incluir:

- escopo inicial;
- comportamento esperado;
- critérios principais;
- limitações;
- hipóteses validadas;
- hipóteses ainda pendentes.

---

### Próximos passos

Registrar o que precisa acontecer depois do discovery.

Exemplos:

- validar com outra área;
- ajustar priorização;
- aprofundar regra;
- envolver Design;
- envolver QA;
- escrever Feature;
- levar para gateway;
- complementar dados.

**Modelo:**

```text
- [Próximo passo 1]
- [Próximo passo 2]
```

---

## Template base

Copiar e preencher conforme a necessidade:

```markdown
# Discovery — [Título da demanda]

## Origem da demanda

[Descrever origem da demanda]

## Problema

[Descrever o problema identificado]

## Objetivo do discovery

[Descrever o que este discovery busca esclarecer]

## Usuário ou área impactada

[Descrever quem é impactado]

## Contexto atual

[Descrever como funciona hoje]

## Evidências e insumos

- [Insumo 1]
- [Insumo 2]
- [Insumo 3]

## Descobertas principais

- [Descoberta 1]
- [Descoberta 2]
- [Descoberta 3]

## Regras de negócio identificadas

- [Regra 1]
- [Regra 2]
- [Regra 3]

## Riscos e dependências

- [Risco ou dependência 1]
- [Risco ou dependência 2]

## Dúvidas em aberto

- [Dúvida 1]
- [Dúvida 2]

## Direcionamento da solução

[Descrever o direcionamento construído a partir do discovery]

## Próximos passos

- [Próximo passo 1]
- [Próximo passo 2]
```

---

## Boas práticas

Ao usar este template:

- começar pelo problema, não pela solução;
- registrar insumos reais;
- deixar regras explícitas;
- evidenciar riscos e dependências;
- não esconder dúvidas;
- evitar texto genérico;
- garantir que o discovery ajude de fato a escrever a Feature depois.

---

## O que evitar

Evitar:

- discovery sem problema claro;
- solução definida sem contexto suficiente;
- achados vagos;
- regras implícitas;
- dúvidas não registradas;
- discovery usado apenas como formalidade;
- copiar estrutura sem gerar clareza real.

---

## Objetivo final

Este template deve ajudar a transformar uma demanda em algo mais compreendido, estruturado e pronto para definição da solução.

Se ao final do discovery ainda não estiver claro o problema, o comportamento atual ou os principais riscos, ele precisa ser aprofundado antes de seguir.

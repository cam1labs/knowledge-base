# Template de Feature

## Objetivo

Este documento fornece um modelo padrão para escrita de Features.

O objetivo é garantir consistência na documentação, facilitar o entendimento por Engenharia e QA e reduzir dúvidas durante refinamento, desenvolvimento e testes.

Este template deve ser usado como base e adaptado conforme a complexidade da funcionalidade.

---

## Estrutura padrão

Toda Feature deve seguir, sempre que aplicável, a estrutura abaixo:

### Título

O título deve ser direto e indicar claramente o objetivo da funcionalidade.

Evitar títulos genéricos ou vagos.

**Exemplo:**

```text
Filtrar notas por CNPJ na listagem do Cofre
```

---

### História do Usuário

A história do usuário deve contextualizar:

- quem quer realizar a ação;
- o que precisa fazer;
- qual valor espera obter com isso.

O objetivo não é escrever algo genérico apenas para cumprir formato, mas dar contexto suficiente para entendimento da necessidade.

**Modelo:**

```text
Como [tipo de usuário]
Quero [ação desejada]
Para [benefício esperado]
```

**Exemplo:**

```text
Como usuário do Cofre
Quero filtrar os documentos por CNPJ
Para localizar mais rapidamente as notas relacionadas a uma empresa específica
```

---

### Contexto

Descrever brevemente o problema ou necessidade da funcionalidade.

Responder, sempre que possível:

- qual problema está sendo resolvido;
- por que essa funcionalidade é necessária;
- qual impacto ela gera;
- se existe comportamento atual relacionado.

**Exemplo:**

```text
Atualmente a listagem de documentos permite localizar notas por diferentes critérios, mas não possui uma forma clara e centralizada de busca por CNPJ considerando toda a pasta. Isso gera dificuldade para localizar documentos específicos e aumenta o tempo necessário para consulta.
```

---

### Regras de negócio

Descrever as regras relevantes de forma explícita.

Incluir:

- comportamentos esperados;
- limites;
- exceções;
- dependências;
- validações;
- impactos em fluxos relacionados.

As regras não devem depender de interpretação.

**Exemplo:**

- A busca por CNPJ deve considerar toda a pasta, e não apenas os registros visíveis na página atual.
- O campo deve aceitar apenas números válidos para CPF ou CNPJ.
- Quando houver filtros já aplicados, a busca deve respeitá-los.
- O comportamento deve substituir a necessidade de uma busca paralela com a mesma finalidade.

---

### Critérios de aceite

Os critérios de aceite devem ser escritos em BDD.

Os cenários devem ser:

- numerados;
- claros;
- aplicáveis;
- testáveis;
- escritos com **Dado**, **Quando**, **Então** e **E** em negrito.

**Modelo:**

```text
Cenário 1 — [título do cenário]

**Dado** que [...]
**E** que [...]
**Quando** [...]
**Então** [...]
**E** [...]
```

---

### Observações

Utilizar esta seção quando houver pontos complementares importantes para entendimento da funcionalidade, como:

- decisões de escopo;
- fora de escopo;
- limitações conhecidas;
- alinhamentos com outras áreas;
- dependências externas;
- links úteis;
- referência a outras Features.

---

## Template base

Copiar e preencher conforme a necessidade:

```markdown
# [Título da Feature]

## História do Usuário

Como [tipo de usuário]  
Quero [ação desejada]  
Para [benefício esperado]

## Contexto

[Descrever o problema, a necessidade e o contexto da funcionalidade.]

## Regras de negócio

- [Regra 1]
- [Regra 2]
- [Regra 3]

## Critérios de Aceite

Cenário 1 — [Nome do cenário]

**Dado** que [...]
**E** que [...]
**Quando** [...]
**Então** [...]
**E** [...]

Cenário 2 — [Nome do cenário]

**Dado** que [...]
**Quando** [...]
**Então** [...]

## Observações

- [Observação complementar]
- [Fora de escopo]
- [Dependência]
```

---

## Quando adaptar o template

O template deve ser adaptado conforme o tipo e a complexidade da funcionalidade.

Exemplos:

- Features simples podem exigir menos contexto e menos regras.
- Features complexas podem exigir detalhamento maior de regras, observações e critérios.
- Quando a funcionalidade envolver múltiplos comportamentos independentes, considerar quebrar em mais de uma Feature em vez de inflar a mesma documentação.

---

## Boas práticas

Ao usar este template:

- deixar regras explícitas;
- evitar comportamento implícito;
- escrever cenários aplicáveis;
- revisar se QA conseguiria testar sem dúvidas;
- revisar se Engenharia conseguiria implementar sem depender de interpretação;
- manter consistência com Features anteriores.

---

## O que evitar

Evitar:

- história do usuário genérica;
- contexto superficial;
- regras incompletas;
- BDD vago;
- excesso de cenários sem necessidade;
- misturar múltiplas responsabilidades na mesma Feature;
- usar observações como lugar para esconder regra importante.

---

## Objetivo final

Este template deve servir como base para escrita de Features claras, consistentes e executáveis.

Se a documentação ainda gerar dúvida sobre o que fazer, como fazer ou como validar, ela precisa ser revisada antes de seguir.

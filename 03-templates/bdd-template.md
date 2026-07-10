# Template de BDD

## Objetivo

Este documento fornece um modelo padrão para escrita de critérios de aceite em BDD.

O objetivo é garantir que os cenários sejam claros, testáveis, aplicáveis e úteis para Engenharia e QA, reduzindo dúvidas durante implementação e validação.

Este template deve ser usado como base e adaptado conforme o contexto da funcionalidade.

---

## Estrutura padrão

Cada cenário deve conter:

- número;
- título objetivo;
- contexto inicial;
- ação;
- resultado esperado;
- complementos necessários.

O cenário deve deixar claro:

- onde se aplica;
- em que condição se aplica;
- o que acontece;
- o que deve ser validado.

---

## Formato obrigatório

Todos os cenários devem seguir este padrão:

- `Cenário X — Nome do cenário`
- **Dado**
- **Quando**
- **Então**
- **E**

---

## Template base

Copiar e preencher conforme a necessidade:

```text
Cenário 1 — [Nome do cenário]

**Dado** que [contexto inicial]
**E** que [condição adicional, se necessário]
**Quando** [ação executada]
**Então** [resultado principal esperado]
**E** [resultado complementar, validação ou regra adicional]
```

---

## Exemplo base

```text
Cenário 1 — Filtrar documentos por CNPJ

**Dado** que o usuário está na tela de listagem de documentos
**E** que existem documentos de diferentes empresas na pasta
**Quando** informar um CNPJ válido no campo de busca
**Então** o sistema deve exibir apenas os documentos relacionados ao CNPJ informado
**E** deve manter os demais filtros já aplicados
```

---

## Como preencher cada parte

### Título do cenário

O título deve indicar claramente o comportamento validado.

Evitar títulos vagos.

**Ruim:**

```text
Cenário 1 — Busca
```

**Bom:**

```text
Cenário 1 — Filtrar documentos por CNPJ válido
```

---

### **Dado**

Usar para definir o contexto inicial.

Responder, quando necessário:

- em qual tela ou fluxo o usuário está;
- qual estado do sistema existe;
- quais dados, permissões ou condições já estão presentes.

---

### **Quando**

Usar para descrever a ação executada.

A ação deve ser objetiva e específica.

Evitar termos genéricos como:

- realiza a ação;
- faz a operação;
- interage com o sistema.

---

### **Então**

Usar para descrever o principal resultado esperado.

O resultado deve ser verificável.

---

### **E**

Usar para complementar:

- validações;
- efeitos adicionais;
- manutenção de filtros;
- mensagens;
- comportamentos secundários;
- restrições.

---

## Modelos prontos por tipo de cenário

### Cenário principal

```text
Cenário X — [Ação principal]

**Dado** que [contexto inicial]
**Quando** [ação do usuário]
**Então** [resultado esperado]
**E** [complemento necessário]
```

---

### Validação de campo

```text
Cenário X — Validar [campo/regra]

**Dado** que [contexto inicial]
**Quando** [ação com valor inválido ou condição específica]
**Então** [mensagem, bloqueio ou comportamento esperado]
**E** [regra complementar]
```

---

### Estado vazio

```text
Cenário X — Exibir estado vazio [condição]

**Dado** que [contexto sem dados ou sem ação prévia]
**Quando** [ação executada ou ausência de resultado]
**Então** [mensagem ou estado vazio esperado]
**E** [comportamento complementar]
```

---

### Erro ou exceção

```text
Cenário X — Tratar erro [situação]

**Dado** que [contexto inicial]
**E** que [condição de erro]
**Quando** [ação executada]
**Então** [comportamento esperado em erro]
**E** [mensagem, bloqueio ou orientação ao usuário]
```

---

### Regra condicional

```text
Cenário X — Aplicar [regra] quando [condição]

**Dado** que [contexto inicial]
**E** que [condição específica]
**Quando** [ação]
**Então** [resultado esperado sob essa condição]
**E** [restrição ou comportamento complementar]
```

---

## Checklist antes de finalizar o cenário

Antes de considerar um cenário pronto, validar:

- O cenário indica claramente onde se aplica?
- O contexto inicial está claro?
- A ação está objetiva?
- O resultado está testável?
- Existe alguma regra implícita?
- Falta alguma informação importante?
- QA conseguiria criar caso de teste sem perguntar?
- Engenharia entenderia o comportamento sem deduzir?

---

## Boas práticas

Ao usar este template:

- preferir cenários diretos;
- garantir contexto suficiente;
- escrever apenas o necessário para gerar clareza;
- evitar cenários inflados;
- manter foco em comportamento testável;
- usar títulos objetivos;
- revisar se o cenário realmente ajuda quem vai implementar e testar.

---

## O que evitar

Evitar:

- cenário genérico;
- cenário sem contexto;
- cenário que não diz quando se aplica;
- cenário sem resultado verificável;
- excesso de cenários sem necessidade;
- esconder regra importante em observação solta;
- usar BDD apenas para cumprir formato.

---

## Objetivo final

Este template deve ajudar a escrever cenários que orientem a implementação e a validação com clareza.

Se o cenário ainda gera dúvida sobre onde aplicar, como validar ou qual comportamento esperar, ele precisa ser reescrito.

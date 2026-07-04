# Padrão de BDD

## Objetivo

Este documento define o padrão de escrita de critérios de aceite em BDD.

O objetivo é garantir que os cenários sejam claros, testáveis e aplicáveis, reduzindo dúvidas durante o desenvolvimento e a validação.

---

## O que é um bom BDD

Um bom BDD é aquele que:

- é claro;
- é testável;
- indica quando deve ser aplicado;
- não deixa comportamento implícito;
- pode ser entendido rapidamente por QA e Engenharia.

Se um cenário gera dúvida, ele não está bem escrito.

---

## O que é um BDD ruim

Um BDD é considerado ruim quando:

- é genérico;
- não deixa claro quando se aplica;
- não pode ser testado;
- está faltando informação relevante;
- depende de interpretação;
- descreve comportamento de forma vaga.

---

## Formato obrigatório

Todos os cenários devem seguir:

- numeração sequencial;
- uso de **Dado**, **Quando**, **Então**, **E** em negrito;
- estrutura clara e consistente.

---

## Estrutura de um cenário

### **Dado**
Define o contexto inicial.

Deve deixar claro:

- onde o usuário está;
- qual é o estado do sistema;
- quais condições já existem.

---

### **Quando**
Define a ação.

Deve ser objetiva e específica.

---

### **Então**
Define o resultado esperado.

Deve ser claro e testável.

---

### **E**
Complementa o comportamento.

Pode ser usado para:

- condições adicionais;
- validações;
- efeitos colaterais;
- regras complementares.

---

## Princípios

### Cenários devem indicar quando se aplicam

Um cenário precisa deixar claro em qual situação ele deve ser usado.

Se não dá pra saber quando aplicar, está errado.

---

### Cenários devem ser testáveis

QA deve conseguir transformar o cenário diretamente em caso de teste.

Se não dá pra testar, não serve.

---

### Menos cenários, mais qualidade

Preferir menos cenários, mas que sejam:

- claros;
- completos;
- aplicáveis.

Evitar inflar a quantidade sem necessidade.

---

### Não deixar comportamento implícito

Se uma regra existe, ela precisa aparecer no cenário.

Não confiar que alguém vai deduzir.

---

## Tipos de cenários

Sempre que aplicável:

- cenário principal (fluxo esperado);
- validações;
- exceções;
- estados alternativos;
- erros.

---

## Exemplos

### ❌ Cenário ruim

```
Cenário 1

Dado que o usuário está na tela
Quando ele realiza a ação
Então o sistema deve funcionar corretamente
```

Problemas:

- genérico;
- não diz qual tela;
- não diz qual ação;
- não define resultado;
- impossível de testar.

---

### ✅ Cenário bom

```
Cenário 1 — Filtrar notas por CNPJ

Dado que o usuário está na tela de listagem de notas
E possui notas de diferentes CNPJs
Quando informar um CNPJ válido no campo de busca
Então o sistema deve exibir apenas as notas relacionadas ao CNPJ informado
E deve manter os demais filtros aplicados
```

---

## O que QA precisa entender rapidamente

Ao ler um cenário, QA deve conseguir identificar:

- onde aplicar;
- como executar;
- o que validar;
- qual o resultado esperado;
- o que não deve acontecer.

Se isso não está claro, o cenário precisa ser reescrito.

---

## Checklist de validação

Antes de considerar o BDD pronto:

- O cenário indica claramente quando se aplica?
- Está possível testar sem interpretação?
- Existe alguma regra implícita?
- Está claro o resultado esperado?
- Falta alguma informação importante?
- Está consistente com outros cenários?

---

## Objetivo final

O BDD deve eliminar dúvidas.

Se alguém precisa perguntar “como deveria funcionar” "e onde deve aplicar", o cenário não está bom.

Clareza gera velocidade.

Ambiguidade gera erro.

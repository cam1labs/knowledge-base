# Como Revisar Documentação

## Objetivo

Este documento define como revisar documentações de Produto de forma crítica, objetiva e útil para a execução.

O objetivo da revisão não é apenas corrigir texto. É verificar se a documentação está clara, consistente, aplicável e suficiente para que Engenharia e QA consigam seguir sem depender de interpretação.

Revisar bem uma documentação é reduzir dúvida antes que ela vire retrabalho.

---

## O que significa revisar documentação

Revisar documentação é validar se o material realmente cumpre sua função.

Uma documentação pode estar bem escrita do ponto de vista textual e ainda assim estar ruim para execução.

A revisão deve verificar, principalmente:

- clareza;
- completude;
- consistência;
- aplicabilidade;
- testabilidade;
- ausência de regras implícitas.

---

## O que uma boa revisão precisa responder

Ao revisar uma documentação, é preciso conseguir responder:

- Está claro qual problema está sendo resolvido?
- Está claro o que deve ser feito?
- Está claro como a funcionalidade deve funcionar?
- As regras de negócio estão explícitas?
- Os cenários estão aplicáveis?
- QA conseguiria validar sem depender de interpretação?
- Engenharia conseguiria implementar sem precisar descobrir o básico?

Se a resposta for não para qualquer um desses pontos, a documentação precisa de ajuste.

---

## Princípios

### Clareza acima de volume

Documentação extensa não significa documentação boa.

O importante é que a informação certa esteja no lugar certo, com clareza suficiente para orientar execução.

---

### Regra implícita é falha de documentação

Se a funcionalidade depende de uma regra e ela não está explícita, isso deve ser tratado como problema de documentação.

---

### Cenários devem orientar, não apenas existir

Não basta verificar se existe BDD.

É preciso verificar se os cenários realmente dizem:

- onde aplicar;
- em qual condição aplicar;
- o que validar;
- qual resultado esperar.

---

### Revisar é testar mentalmente a execução

Uma boa revisão simula o uso da documentação por quem vai desenvolver e testar.

A pergunta principal é:

> Alguém conseguiria executar isso sem depender de suposição?

---

## O que revisar em uma Feature

### Título

Verificar se o título representa com clareza a funcionalidade.

Evitar títulos genéricos ou vagos.

---

### História do Usuário

Verificar se a história dá contexto suficiente e se realmente ajuda a entender a necessidade da funcionalidade.

Ela não precisa ser rebuscada, mas precisa fazer sentido.

---

### Contexto

Verificar se o problema está bem explicado.

Deve ficar claro:

- o que acontece hoje;
- o que precisa mudar;
- por que isso importa;
- quem é impactado.

---

### Regras de negócio

Verificar se:

- estão explícitas;
- são aplicáveis;
- não estão genéricas;
- não dependem de interpretação;
- não contradizem outras regras já conhecidas;
- incluem exceções, limitações e dependências quando necessário.

---

### Critérios de aceite

Verificar se os cenários em BDD:

- estão numerados;
- têm título claro;
- dizem onde se aplicam;
- são testáveis;
- cobrem os comportamentos realmente relevantes;
- não estão vagos;
- não deixam comportamento implícito.

---

### Observações

Verificar se a seção de observações está sendo usada corretamente.

Observações devem complementar.

Se houver regra importante escondida nessa seção, ela precisa ser movida para o lugar correto.

---

## O que revisar em um Discovery

Ao revisar um discovery, verificar se ele esclarece:

- qual é o problema;
- quem é impactado;
- como funciona hoje;
- quais insumos foram usados;
- quais descobertas realmente saíram da análise;
- quais regras foram identificadas;
- quais dúvidas continuam em aberto;
- se existe base suficiente para definição da solução.

Se o discovery só descreve uma solução, ele não cumpriu bem seu papel.

---

## O que revisar em um BDD

Ao revisar cenários em BDD, verificar:

- o cenário indica claramente quando se aplica?
- o contexto inicial está claro?
- a ação está objetiva?
- o resultado esperado está verificável?
- existe regra implícita?
- falta alguma informação relevante?
- existe cenário demais sem necessidade?
- existe cenário de menos a ponto de deixar lacuna importante?

---

## Como identificar que a documentação ainda está fraca

Sinais comuns de documentação fraca:

- termos genéricos;
- excesso de interpretação possível;
- regras soltas;
- contexto superficial;
- cenário que “parece certo” mas não explica quando aplicar;
- exceções não documentadas;
- dúvidas centrais ainda presentes;
- necessidade de explicar verbalmente o que não está escrito.

Se precisa explicar demais fora da documentação, a documentação ainda não está boa.

---

## Perguntas de revisão

Durante a revisão, vale se perguntar:

- O que alguém pode entender errado aqui?
- Existe alguma regra que eu estou assumindo como óbvia?
- Está claro quando cada cenário se aplica?
- Está claro o que acontece em casos alternativos?
- Está claro o que não deve acontecer?
- Se eu entregasse isso para outra pessoa, ela conseguiria seguir sem mim?

---

## O que evitar na revisão

Evitar:

- revisar apenas ortografia e formatação;
- considerar suficiente porque “na conversa o time entende”;
- aprovar documentação com regra implícita;
- aceitar cenário genérico só porque está em formato BDD;
- confiar que QA ou Engenharia vão preencher lacunas;
- deixar passar inconsistências com outras funcionalidades.

---

## Checklist de revisão

Antes de considerar a documentação aprovada, validar:

- O problema está claro?
- O objetivo está claro?
- As regras estão explícitas?
- Os cenários estão direcionados?
- O conteúdo está consistente com outros fluxos?
- Existe alguma lacuna importante?
- QA conseguiria testar?
- Engenharia conseguiria implementar?
- Existe algo que ainda depende de explicação fora do documento?

---

## Objetivo final

Revisar documentação é garantir que ela realmente possa ser usada.

Se a documentação ainda gera dúvida sobre o que fazer, quando aplicar ou como validar, ela ainda não está pronta.

Boa documentação não é a que parece completa.

É a que reduz interpretação e facilita execução.

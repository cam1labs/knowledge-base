# Definition of Ready

## Objetivo

Este documento define os critérios mínimos para considerar uma demanda pronta para seguir para desenvolvimento.

O objetivo é reduzir ambiguidades, evitar início prematuro de implementação e garantir que o time tenha contexto suficiente para desenvolver com segurança.

Uma demanda pronta não significa que tudo está perfeito ou definitivo, mas que já existe clareza suficiente para começar sem depender de deduções básicas.

---

## O que é Definition of Ready

Definition of Ready é o conjunto de critérios que indica que uma demanda possui nível mínimo de clareza, contexto e estrutura para ser refinada e desenvolvida.

Ela existe para evitar que o time comece a trabalhar em algo que ainda está mal definido, com regras implícitas, cenários vagos ou dúvidas centrais em aberto.

---

## Princípios

### Clareza antes de velocidade

Começar rápido uma demanda mal definida costuma gerar retrabalho, dúvidas e desalinhamento.

É melhor investir tempo deixando a demanda clara do que transferir a incerteza para Engenharia e QA.

---

### Ready não é perfeição

Uma demanda pronta não precisa prever absolutamente tudo.

Mas precisa ter clareza suficiente sobre:

- problema;
- objetivo;
- comportamento esperado;
- regras principais;
- critérios de aceite;
- dúvidas relevantes já identificadas.

---

### O time não deve começar pelo escuro

Se o time ainda precisa descobrir o básico sobre o que fazer, como funciona ou onde aplicar os cenários, a demanda ainda não está pronta.

---

## Critérios mínimos

Uma demanda pode ser considerada pronta quando possui, no mínimo:

### 1. Título claro

O título deve indicar de forma objetiva o que será feito.

Títulos genéricos dificultam entendimento e priorização.

---

### 2. Contexto do problema

A demanda deve explicar:

- qual problema existe;
- por que essa entrega é necessária;
- qual impacto se espera;
- quem será afetado.

Sem contexto, o time tende a discutir solução sem entender a necessidade real.

---

### 3. Objetivo da funcionalidade

Deve estar claro o que a funcionalidade pretende resolver ou viabilizar.

---

### 4. Regras de negócio conhecidas

As regras principais precisam estar explícitas.

Não é aceitável depender de suposições para entender o comportamento esperado.

---

### 5. Critérios de aceite em BDD

Os critérios de aceite devem estar escritos em BDD, com cenários claros, aplicáveis e testáveis.

Eles devem indicar:

- onde aplicar;
- qual ação ocorre;
- qual resultado é esperado.

---

### 6. Cenários minimamente direcionados

Os cenários não precisam ser numerosos, mas precisam ser suficientes para indicar o comportamento esperado.

Cenários vagos, genéricos ou que não deixam claro quando se aplicam não atendem ao padrão de pronto.

---

### 7. Dúvidas já identificadas

Se existirem dúvidas relevantes, elas devem estar registradas de forma explícita.

O problema não é existir dúvida. O problema é a dúvida estar invisível.

---

### 8. Referências importantes anexadas

Quando existirem materiais complementares relevantes, eles devem estar vinculados à demanda, como:

- protótipo;
- documentação anterior;
- prints;
- fluxos;
- links úteis;
- dependências relacionadas.

---

## Critérios complementares

Dependendo do tipo de demanda, também pode ser necessário ter:

- mensagens e estados definidos;
- validações descritas;
- impactos em fluxos existentes;
- comportamento em erro;
- dependências externas identificadas;
- definição de escopo e fora de escopo;
- alinhamento com Design;
- alinhamento com stakeholders.

---

## Quando a demanda ainda não está pronta

Uma demanda ainda não está pronta quando:

- o problema não está claro;
- o objetivo não está claro;
- as regras estão implícitas;
- os cenários estão genéricos;
- não dá para saber onde aplicar os critérios;
- QA não consegue visualizar como testar;
- Engenharia ainda não entende por onde começar;
- existem dúvidas centrais sem registro ou encaminhamento.

---

## O que não deve acontecer

Não deve acontecer:

- iniciar desenvolvimento só para “ganhar tempo”;
- tratar refinamento como substituto de documentação básica;
- confiar que o time vai subentender regras;
- considerar pronta uma demanda com critérios vagos;
- esconder incerteza para destravar card.

---

## Como usar este documento

Antes de mover uma demanda para desenvolvimento, validar se ela atende aos critérios mínimos deste documento.

Se não atender, o ideal é:

- complementar a documentação;
- revisar regras;
- ajustar cenários;
- registrar dúvidas;
- alinhar pendências antes de seguir.

---

## Sinais de que a demanda está pronta

Uma demanda está pronta quando:

- o problema está compreendido;
- o objetivo está claro;
- os critérios de aceite estão direcionados;
- as regras principais estão explícitas;
- o time entende o comportamento esperado;
- QA consegue visualizar a validação;
- Engenharia consegue iniciar sem depender de interpretações básicas.

---

## Objetivo final

Definition of Ready existe para aumentar previsibilidade, reduzir dúvidas e melhorar a qualidade da execução.

Se uma demanda entra em desenvolvimento sem clareza mínima, a incerteza não desaparece. Ela apenas muda de lugar.

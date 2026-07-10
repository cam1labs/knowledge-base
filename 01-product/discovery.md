# Discovery

## Objetivo

Este documento define como conduzir o discovery de uma funcionalidade, melhoria ou problema de produto.

O objetivo do discovery é reduzir incertezas antes da especificação e do desenvolvimento, garantindo que a solução proposta tenha contexto, direção e regras suficientemente claras.

Discovery não deve servir apenas para registrar uma ideia. Deve ajudar a entender o problema, validar premissas, identificar riscos e evitar que a Feature nasça com lacunas.

---

## O que é Discovery

Discovery é a etapa em que buscamos entender:

- qual problema precisa ser resolvido;
- por que ele importa;
- quem é impactado;
- quais comportamentos existem hoje;
- quais comportamentos são esperados;
- quais regras de negócio influenciam a solução;
- quais exceções e riscos precisam ser considerados.

O discovery existe para dar base à decisão e à especificação.

---

## O que um bom Discovery precisa fazer

Um bom discovery precisa:

- esclarecer o problema real;
- separar problema de solução;
- reduzir suposições;
- levantar regras de negócio;
- identificar cenários e exceções;
- antecipar riscos;
- revelar dúvidas importantes;
- dar base para escrever uma Feature melhor.

Se depois do discovery a especificação continua cheia de lacunas, então o discovery não foi suficiente.

---

## Princípios

### Entender o problema antes da solução

Não começar pelo “como vai ser”.

Primeiro é preciso entender:

- o que acontece hoje;
- o que está errado, faltando ou limitando o usuário;
- qual impacto isso gera.

Sem isso, existe risco de documentar uma solução sem clareza do problema.

---

### Reduzir incerteza

O discovery não precisa responder tudo, mas precisa reduzir as principais incertezas antes do refinamento e do desenvolvimento.

Se uma dúvida importante existir, ela deve aparecer.

---

### Tornar regras visíveis

Uma parte importante do discovery é descobrir regras que normalmente ficam implícitas.

Se a solução depende de uma regra, essa regra precisa ser levantada.

---

### Evitar decisões frágeis

Quando uma definição ainda depende de premissas não validadas, isso deve ser registrado.

É melhor explicitar a incerteza do que seguir com uma definição aparentemente pronta, mas frágil.

---

## O que investigar no Discovery

Sempre que aplicável, o discovery deve responder:

### Problema

- Qual problema está acontecendo?
- O que motivou essa demanda?
- Quem percebe esse problema?
- Qual impacto ele gera?

---

### Usuário e contexto

- Quem é o usuário impactado?
- Em que fluxo esse problema acontece?
- Em qual momento da jornada ele aparece?
- O usuário depende de alguma condição específica para passar por esse cenário?

---

### Comportamento atual

- Como funciona hoje?
- O que já existe relacionado a esse fluxo?
- Existe comportamento parecido em outra funcionalidade?
- Existe alguma regra já consolidada que precisa ser mantida?

---

### Comportamento esperado

- O que precisa acontecer?
- O que muda em relação ao comportamento atual?
- Quais condições alteram o comportamento?

---

### Regras de negócio

- Quais regras influenciam essa funcionalidade?
- Existe limitação?
- Existe exceção?
- Existe dependência de outro fluxo, permissão, configuração, status ou integração?

---

### Riscos e dependências

- Existe risco técnico?
- Existe dependência externa?
- Existe impacto em outras áreas, times ou funcionalidades?
- Existe algo que ainda precisa ser validado antes de seguir?

---

## Fontes de informação

O discovery pode se apoiar em diferentes fontes, como:

- contexto de negócio;
- feedback de usuários;
- tickets;
- suporte;
- stakeholders;
- time técnico;
- QA;
- dados de uso;
- protótipos;
- documentação existente;
- comportamento atual do produto.

A qualidade do discovery melhora quando ele cruza diferentes fontes, em vez de depender apenas de opinião.

---

## O que deve sair de um Discovery

Ao final do discovery, deve ser possível ter pelo menos:

- entendimento claro do problema;
- objetivo da entrega;
- principais regras de negócio;
- cenários mais relevantes;
- dúvidas pendentes registradas;
- riscos identificados;
- direcionamento suficiente para especificação.

O discovery não precisa sair com a Feature pronta, mas precisa deixar o caminho claro para escrevê-la.

---

## Quando o Discovery ainda não está bom

Um discovery ainda não está bom quando:

- o problema está genérico;
- a solução apareceu antes do entendimento do contexto;
- as regras continuam implícitas;
- existem muitas suposições não validadas;
- ninguém sabe exatamente quem será impactado;
- não está claro como funciona hoje;
- não está claro o que muda;
- ainda existem dúvidas centrais invisíveis.

---

## O que evitar

Evitar:

- usar discovery apenas para formalizar uma solução já decidida;
- pular entendimento do problema;
- confiar em regra subentendida;
- ignorar exceções;
- deixar dúvidas importantes sem registro;
- documentar solução sem contexto;
- tratar discovery como burocracia.

---

## Relação entre Discovery e Feature

O discovery prepara a base da Feature.

Uma Feature bem escrita depende de um discovery minimamente bem feito.

Quando o discovery é fraco, a tendência é que a Feature tenha:

- regras implícitas;
- cenários vagos;
- dúvidas no refinamento;
- retrabalho no desenvolvimento;
- dificuldade para QA testar.

---

## Objetivo final

O discovery existe para dar clareza antes da especificação.

Ele reduz incerteza, melhora a qualidade da documentação e aumenta a chance de que o time desenvolva a solução certa, da forma certa, com menos retrabalho.

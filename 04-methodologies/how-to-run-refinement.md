# Como Conduzir Refinamentos

## Objetivo

Este documento define como conduzir refinamentos de forma clara, objetiva e produtiva.

O objetivo do refinamento é garantir que Produto, Engenharia, QA e demais envolvidos tenham entendimento comum sobre a funcionalidade antes do desenvolvimento.

Refinamento não deve servir apenas para apresentar uma demanda. Deve servir para reduzir dúvidas, validar entendimento, identificar riscos e ajustar a especificação antes da implementação.

---

## O que é um bom refinamento

Um bom refinamento é aquele em que:

- o problema está claro;
- a solução proposta está clara;
- as regras de negócio estão explícitas;
- os cenários estão direcionados;
- as dúvidas relevantes foram levantadas;
- os riscos e dependências foram identificados;
- Engenharia e QA saem sabendo por onde começar.

Se o time sai do refinamento com muitas dúvidas básicas, o refinamento não cumpriu seu papel.

---

## Objetivo do refinamento

Durante o refinamento, é preciso garantir clareza sobre:

- o problema que está sendo resolvido;
- o objetivo da entrega;
- o comportamento esperado;
- as regras de negócio;
- as exceções;
- as validações;
- os impactos em fluxos existentes;
- as dependências;
- os pontos ainda indefinidos.

---

## O que deve estar preparado antes do refinamento

Antes do refinamento, a documentação deve estar minimamente estruturada.

Sempre que possível, a Feature deve conter:

- título claro;
- contexto da funcionalidade;
- história do usuário;
- critérios de aceite em BDD;
- regras de negócio conhecidas;
- dúvidas já identificadas;
- referências de protótipo, quando existirem;
- observações importantes para entendimento.

O refinamento não deve começar do zero quando a funcionalidade já exige detalhamento prévio.

---

## Como conduzir a conversa

O refinamento deve seguir uma lógica simples:

### 1. Contextualizar o problema

Antes de entrar em tela, regra ou critério, alinhar:

- qual problema existe hoje;
- por que a funcionalidade está sendo feita;
- qual impacto se espera;
- quem será afetado.

Sem contexto, o time discute solução sem entender o motivo.

---

### 2. Explicar o comportamento esperado

Depois do contexto, apresentar como a funcionalidade deve funcionar na prática.

O foco deve ser o comportamento, não apenas a interface.

É importante deixar claro:

- onde a funcionalidade começa;
- o que o usuário faz;
- o que o sistema deve fazer;
- quais condições mudam o comportamento;
- quais exceções podem acontecer.

---

### 3. Validar regras de negócio

As regras devem ser confirmadas de forma explícita.

Não assumir que o time vai deduzir comportamento com base em experiência anterior ou em fluxos parecidos.

Quando houver exceção, limitação ou condição especial, isso deve ser trazido para a conversa.

---

### 4. Revisar os cenários

Os cenários em BDD devem ser revisados com foco em:

- clareza;
- aplicabilidade;
- cobertura suficiente;
- testabilidade.

O importante não é ter muitos cenários, e sim cenários que realmente indiquem onde aplicar cada comportamento.

---

### 5. Levantar dúvidas e riscos

O refinamento deve abrir espaço para questionamentos reais.

É esperado levantar:

- lacunas na especificação;
- conflitos de regra;
- riscos técnicos;
- impactos em outras funcionalidades;
- dependências externas;
- pontos que ainda exigem validação.

---

## O que deve ser evitado

Evitar durante o refinamento:

- leitura mecânica da Feature;
- passar rapidamente por regras importantes;
- assumir comportamento sem validação;
- encerrar a conversa com dúvidas relevantes em aberto;
- usar o refinamento apenas como repasse de tarefa;
- discutir somente interface sem discutir regra;
- seguir com definição frágil apenas para destravar card.

---

## Quando um refinamento ainda não está bom

Um refinamento ainda não está bom quando:

- existem regras implícitas;
- o time não entende onde aplicar os cenários;
- QA não consegue enxergar como testar;
- Engenharia ainda não consegue entender por onde começar;
- existem dúvidas centrais sem encaminhamento;
- a funcionalidade depende de muitas interpretações.

Nesses casos, o correto é ajustar a documentação, registrar as dúvidas e validar o que falta antes de seguir.

---

## Papel de Produto no refinamento

Durante o refinamento, o papel de Produto é:

- dar contexto;
- explicitar regras;
- esclarecer comportamento;
- organizar a discussão;
- registrar lacunas;
- validar inconsistências;
- garantir entendimento comum entre as áreas.

Produto não deve apenas ler a documentação. Deve conduzir a conversa de forma que o time compreenda a entrega com segurança.

---

## Papel da Engenharia e do QA

Engenharia e QA devem participar de forma ativa no refinamento.

Espera-se que o time:

- questione pontos ambíguos;
- aponte riscos;
- valide viabilidade;
- identifique lacunas;
- confronte regras contraditórias;
- ajude a transformar a especificação em algo implementável e testável.

Refinamento bom não é monólogo.

---

## Como lidar com dúvidas em aberto

Quando surgir uma dúvida relevante durante o refinamento, ela deve ser tratada explicitamente.

As possibilidades são:

- responder na hora, quando houver segurança;
- registrar como pendência;
- validar com outra área ou stakeholder;
- ajustar a Feature depois da conversa.

O que não deve acontecer é a dúvida ficar invisível e virar interpretação no desenvolvimento.

---

## Sinais de que o refinamento foi bem feito

Ao final do refinamento, deve ser possível perceber que:

- o problema está entendido;
- os cenários fazem sentido;
- as regras estão claras;
- as dúvidas principais foram resolvidas ou registradas;
- o time sabe o que fazer;
- QA sabe o que validar;
- existe segurança maior para seguir com a implementação.

---

## Objetivo final

Refinamento bom reduz incerteza.

Quanto mais clara for a conversa, menor a chance de retrabalho, desalinhamento e dúvida durante o desenvolvimento.

Se o time ainda precisa descobrir sozinho como a funcionalidade deve funcionar, o refinamento não terminou.

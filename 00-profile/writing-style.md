# Estilo de Escrita

## Objetivo

Este documento define os padrões de escrita utilizados na documentação de Produto.

O objetivo é manter consistência entre diferentes documentos, facilitar a leitura e reduzir ambiguidades durante o desenvolvimento.

---

## Princípios

Toda documentação deve priorizar:

- Clareza.
- Objetividade.
- Consistência.
- Contexto suficiente para tomada de decisão.
- Facilidade de execução pelo time.

A documentação deve explicar o comportamento esperado, não apenas descrever telas.

---

## Linguagem

Prefiro uma escrita:

- direta;
- natural;
- profissional;
- simples;
- objetiva.

Evito:

- excesso de formalidade;
- frases muito longas;
- linguagem rebuscada;
- floreios;
- elogios desnecessários;
- textos que não agregam informação.

---

## Nível de detalhamento

A documentação deve conter informação suficiente para que Engenharia e QA consigam implementar e validar uma funcionalidade sem depender de interpretações.

Ao mesmo tempo, deve evitar repetições e descrições que não agreguem valor.

O foco é qualidade da informação, não quantidade de texto.

---

## Escrita de Features

Toda Feature deve seguir a estrutura:

- Título
- História do Usuário
- Critérios de Aceite

Sempre que necessário, incluir regras de negócio e observações complementares.

Quando uma funcionalidade possuir muitas responsabilidades, ela deve ser dividida em múltiplas Features menores.

---

## Critérios de Aceite

Os critérios de aceite devem ser escritos em BDD.

Os cenários devem ser numerados.

As palavras **Dado**, **Quando**, **Então** e **E** devem estar sempre em negrito.

Os cenários devem representar situações reais de utilização da funcionalidade.

Sempre que necessário, incluir:

- cenário principal;
- validações;
- exceções;
- estados vazios;
- mensagens ao usuário;
- erros esperados.

---

## Consistência

Regras já definidas em outras funcionalidades devem ser reaproveitadas sempre que fizer sentido.

Fluxos semelhantes devem apresentar comportamento semelhante.

Evitar criar exceções sem justificativa.

---

## Escrita de regras

As regras devem ser explícitas.

Não assumir que Engenharia ou QA irão deduzir comportamentos.

Quando existir uma exceção, ela deve estar documentada.

Quando existir uma limitação conhecida, ela também deve estar documentada.

---

## Escrita para Engenharia

A documentação deve responder, sempre que possível:

- O que será desenvolvido?
- Por que será desenvolvido?
- Como deve funcionar?
- Quais validações existem?
- Quais exceções existem?
- O que acontece em casos de erro?
- Existe impacto em outra funcionalidade?

---

## Escrita para QA

Os critérios de aceite devem ser testáveis.

Sempre que possível, deixar claro:

- comportamento esperado;
- comportamento não permitido;
- estados iniciais;
- estados finais;
- mensagens;
- validações.

---

## Uso de exemplos

Sempre que um exemplo facilitar o entendimento de uma regra de negócio, ele deve ser incluído.

Exemplos devem esclarecer o comportamento esperado, nunca substituir a regra.

---

## O que evitar

Evitar:

- comportamento implícito;
- regras contraditórias;
- excesso de texto;
- repetição da mesma informação;
- critérios vagos;
- termos subjetivos como "rápido", "intuitivo" ou "adequado" sem definição;
- requisitos que não possam ser testados.

---

## Revisão

Antes de considerar uma documentação pronta, verificar:

- O problema está claro?
- A solução está clara?
- Existem regras implícitas?
- Existem exceções não documentadas?
- Os critérios de aceite são testáveis?
- Existe consistência com outras funcionalidades?
- Engenharia conseguiria implementar sem depender de perguntas adicionais?

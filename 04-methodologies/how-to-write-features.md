# Como Escrever Features

## Objetivo

Este documento define como estruturar e escrever Features de forma clara, objetiva e executável.

O objetivo é eliminar ambiguidades, reduzir dúvidas durante o desenvolvimento e garantir que Engenharia e QA consigam implementar e validar uma funcionalidade sem depender de interpretação.

---

## O que é uma boa Feature

Uma boa Feature é aquela que:

- resolve um problema claro;
- possui comportamento bem definido;
- não depende de suposições;
- possui regras explícitas;
- contém cenários aplicáveis;
- pode ser implementada e testada sem dúvidas.

Se Engenharia ou QA precisam “deduzir” comportamento, a Feature não está bem escrita.

---

## Princípios

### Regras devem ser explícitas

Nunca assumir que o time vai subentender comportamento.

Toda regra relevante deve estar documentada.

Se existe exceção, ela deve estar documentada.

---

### Cenários devem ser aplicáveis

Não adianta ter muitos cenários.

O importante é ter cenários que realmente representem:

- como a funcionalidade será usada;
- quando aplicar cada comportamento;
- quais condições ativam cada regra.

Cenários genéricos ou vagos não ajudam.

---

### Clareza acima de quantidade

Mais texto não significa mais clareza.

A documentação deve ser suficiente para execução, sem excesso.

---

### Reduzir dúvidas é o objetivo

Se uma Feature gera muitas dúvidas no refinamento ou durante o desenvolvimento, ela falhou.

---

## Estrutura padrão

Toda Feature deve conter:

### Título

Deve ser direto e refletir claramente o objetivo da funcionalidade.

---

### História do Usuário

Deve contextualizar:

- quem é o usuário;
- o que ele quer fazer;
- por quê.

Sem exagero. O foco não é storytelling, é contexto.

---

### Critérios de Aceite

Devem ser escritos em BDD.

---

## Como escrever BDD

### Formato obrigatório

- Cenários numerados
- **Dado**, **Quando**, **Então**, **E** em negrito

---

### O que um bom cenário precisa ter

- contexto claro (Dado)
- ação específica (Quando)
- resultado esperado (Então)
- condições adicionais (E)

---

### O que evitar

- cenários genéricos;
- cenários que não indicam quando se aplicam;
- cenários que deixam comportamento implícito;
- cenários que não podem ser testados.

---

## Tipos de cenários que devem existir

Sempre que aplicável, considerar:

- cenário principal (fluxo feliz);
- validações;
- exceções;
- estados vazios;
- erros;
- comportamentos alternativos.

---

## Regras de negócio

Regras devem ser descritas fora ou dentro dos cenários, dependendo do caso.

Mas nunca devem ficar implícitas.

Se uma regra impacta comportamento, ela deve estar clara.

---

## Quando quebrar uma Feature

Uma Feature deve ser quebrada quando:

- possui múltiplos comportamentos independentes;
- mistura responsabilidades diferentes;
- gera cenários demais;
- dificulta entendimento;
- dificulta implementação.

Features menores são mais fáceis de entender, implementar e testar.

---

## Impacto no desenvolvimento

Uma Feature bem escrita deve permitir que Engenharia responda:

- o que fazer;
- como deve funcionar;
- quando aplicar cada regra;
- o que acontece em cada cenário.

Sem precisar perguntar o básico.

---

## Impacto no QA

Uma Feature bem escrita deve permitir que QA:

- derive casos de teste diretamente;
- entenda o comportamento esperado;
- identifique erros facilmente;
- valide cenários sem ambiguidade.

Se QA precisa perguntar “como deveria funcionar”, a Feature não está clara.

---

## Principais erros a evitar

- regras implícitas;
- confiar que o time vai “entender”;
- cenários vagos;
- cenários sem contexto;
- excesso de texto sem valor;
- falta de cenários importantes;
- inconsistência com outras funcionalidades.

---

## Checklist antes de finalizar

Antes de considerar a Feature pronta, validar:

- Todas as regras estão explícitas?
- Existe algum comportamento implícito?
- Os cenários indicam claramente quando se aplicam?
- Engenharia conseguiria implementar sem dúvidas?
- QA conseguiria testar sem precisar perguntar?
- Existe consistência com outras funcionalidades?
- A Feature está grande demais?

---

## Objetivo final

Uma Feature bem escrita reduz dúvidas, evita retrabalho e garante que todos os envolvidos tenham o mesmo entendimento sobre o comportamento esperado.

Se houver interpretação, haverá erro.

Se houver clareza, haverá velocidade e qualidade.

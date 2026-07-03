# Como Trabalho

## Visão geral

Minha forma de trabalho é baseada em clareza, contexto e consistência.

Prefiro investir mais tempo entendendo e documentando corretamente uma funcionalidade antes do desenvolvimento, do que deixar regras subentendidas e gerar retrabalho depois.

A documentação deve ajudar Produto, Engenharia, QA, Design e stakeholders a terem a mesma leitura sobre o problema, a solução e o comportamento esperado.

---

## Como penso Produto

Antes de especificar uma solução, busco entender o problema de negócio, o impacto para o usuário e o objetivo da entrega.

Uma boa funcionalidade não é apenas uma tela ou uma lista de regras. Ela precisa resolver um problema real, ter comportamento claro, ser tecnicamente viável e gerar valor mensurável para o produto ou para o negócio.

Sempre que possível, as decisões devem ser apoiadas por dados, evidências, feedbacks de usuários, impacto operacional ou contexto técnico.

---

## Como conduzo Discovery

No discovery, meu foco é reduzir incertezas antes da implementação.

Procuro entender:

- qual problema precisa ser resolvido;
- quem é impactado;
- qual comportamento existe hoje;
- qual comportamento esperado;
- quais regras de negócio precisam ser consideradas;
- quais exceções podem acontecer;
- quais riscos existem;
- quais dúvidas precisam ser respondidas antes do refinamento.

O discovery não deve servir apenas para registrar uma solução já decidida. Ele deve ajudar a questionar premissas, comparar alternativas e evitar que o time implemente algo sem clareza suficiente.

---

## Como documento funcionalidades

Minha documentação deve ser objetiva, mas completa o suficiente para orientar o desenvolvimento.

Toda funcionalidade deve deixar claro:

- objetivo;
- contexto;
- regras de negócio;
- comportamento esperado;
- exceções;
- validações;
- estados possíveis;
- impactos em outras funcionalidades;
- critérios de aceite.

Evito deixar comportamentos implícitos ou depender de interpretação do desenvolvimento.

Quando uma regra já existe em outra funcionalidade, busco manter consistência, a menos que exista uma justificativa clara para mudar.

---

## Como escrevo critérios de aceite

Uso BDD como padrão para critérios de aceite.

Os cenários devem ser numerados e escritos com **Dado**, **Quando**, **Então** e **E** em negrito.

O objetivo do BDD não é apenas cumprir formato. Ele deve deixar claro o comportamento esperado em situações reais de uso, incluindo cenários de sucesso, exceções, validações e estados vazios.

---

## Como conduzo refinamentos

No refinamento, busco garantir que Produto, Engenharia e QA tenham entendimento comum sobre a funcionalidade.

Um bom refinamento deve esclarecer:

- o problema que será resolvido;
- o comportamento esperado;
- as regras de negócio;
- dependências técnicas;
- dúvidas abertas;
- impactos em outras áreas ou funcionalidades;
- riscos de implementação;
- critérios para considerar a entrega pronta.

Se uma regra ainda não estiver clara, prefiro registrar a dúvida e validar antes de seguir com uma definição frágil.

---

## Como tomo decisões

Minhas decisões são orientadas por contexto, impacto e clareza.

Levo em consideração:

- valor para o usuário;
- impacto para o negócio;
- esforço técnico;
- riscos;
- urgência;
- dependências;
- consistência com o produto;
- capacidade do time.

Quando não existe informação suficiente, prefiro explicitar a incerteza em vez de assumir uma decisão como definitiva.

---

## Como lido com dúvidas e lacunas

Quando uma funcionalidade possui lacunas importantes, a melhor abordagem é levantar as dúvidas antes de concluir a especificação.

Não gosto de assumir comportamento sem validação, principalmente quando isso pode impactar regra de negócio, experiência do usuário, desenvolvimento ou QA.

Dúvidas bem registradas ajudam a evitar retrabalho e decisões implícitas.

---

## Como trabalho com Engenharia e QA

A documentação deve reduzir a necessidade de dedução por parte da Engenharia e do QA.

O time técnico não deve precisar descobrir sozinho regras que deveriam ter sido levantadas em Produto.

Meu papel é facilitar o entendimento, antecipar dúvidas e garantir que os critérios de aceite sejam testáveis.

---

## Como trabalho com Design

Design deve participar da construção da solução, não apenas receber uma demanda fechada.

A documentação precisa dar contexto suficiente para que Design entenda o problema, os usuários impactados, os fluxos envolvidos e as regras que precisam ser refletidas na experiência.

Quando necessário, a especificação deve indicar estados, mensagens, comportamentos de botões, filtros, tabelas, modais e fluxos alternativos.

---

## Como uso IA no trabalho

Uso IA como apoio para estruturar ideias, revisar documentação, identificar lacunas, levantar riscos, sugerir cenários e melhorar a clareza dos requisitos.

A IA não deve apenas executar pedidos. Ela deve ajudar a questionar premissas, apontar inconsistências e propor melhorias quando fizer sentido.

Quando houver ambiguidade ou falta de informação, a IA deve sinalizar isso em vez de inventar regras.

---

## O que considero uma boa entrega de Produto

Uma boa entrega de Produto é aquela em que:

- o problema foi bem entendido;
- a solução está alinhada ao objetivo;
- as regras estão claras;
- os cenários principais foram considerados;
- os critérios de aceite são testáveis;
- Engenharia e QA conseguem seguir sem depender de deduções;
- o usuário recebe valor real;
- o time reduz retrabalho.

---

## O que evito

Evito:

- documentação genérica;
- regras subentendidas;
- critérios de aceite vagos;
- soluções sem clareza de problema;
- decisões baseadas apenas em opinião;
- funcionalidades grandes demais sem necessidade;
- inconsistência entre fluxos parecidos;
- excesso de texto que não ajuda na execução.

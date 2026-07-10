# Fluxo de Discovery

## Objetivo

Este documento descreve o fluxo enxuto de discovery utilizado para conduzir demandas desde o entendimento inicial até a preparação para desenvolvimento.

O objetivo desse fluxo é transformar uma demanda em algo claro, priorizável, documentado e pronto para seguir para o Azure com o nível de definição necessário para Produto, Design e QA.

Esse fluxo não existe para burocratizar. Ele existe para reduzir incerteza, organizar responsabilidades e evitar que a demanda chegue ao desenvolvimento com lacunas importantes.

---

## Visão geral do fluxo

O fluxo de discovery é composto por seis etapas:

1. Entendimento da demanda
2. Descoberta
3. Definição da solução
4. Gateway
5. DoR
6. Azure atualizado

Cada etapa possui um objetivo específico e ajuda a amadurecer a demanda antes do início da implementação.

---

## 1. Entendimento da demanda

### Objetivo

Entender qual é o escopo inicial da demanda e qual impacto ela gera para o negócio e para o usuário.

### Participantes principais

- Produto
- Design

### Papel de Produto

Produto avalia como a demanda impacta o negócio.

Esse entendimento pode envolver valor estratégico, impacto operacional, impacto em resultados, necessidade percebida por áreas internas ou externas e urgência do problema.

### Papel de Design

Design avalia como a demanda impacta o usuário.

Esse entendimento considera experiência, jornada, pontos de fricção, entendimento do fluxo atual e possíveis efeitos na usabilidade.

### Resultado esperado da etapa

Ao final dessa etapa, deve existir clareza inicial sobre:

- qual demanda está sendo analisada;
- qual o escopo inicial;
- por que ela importa;
- como impacta o negócio;
- como impacta o usuário.

---

## 2. Descoberta

### Objetivo

Levantar informações que ajudem a entender melhor o problema, o contexto da demanda e os insumos necessários para definir uma solução.

### Fontes de descoberta

A etapa de descoberta pode envolver:

- dados do negócio;
- dados de comportamento;
- pesquisa ou testes com usuário;
- levantamento da jornada atual;
- consumo de informações de outros setores;
- alinhamento com outros setores;
- análise de concorrentes.

### Tipos de insumo considerados

#### Dados do negócio

Exemplos:

- churn;
- retenção;
- NPS;
- indicadores estratégicos ou operacionais.

#### Dados de comportamento

Exemplo:

- Mixpanel ou outras fontes de comportamento do usuário.

#### Pesquisa ou testes com usuário

Quando necessário, utilizar insumos qualitativos para entender comportamentos, dores, expectativas e reações.

#### Levantamento de jornada

Mapeamento do fluxo atual, do cenário “as is” e da experiência existente.

#### Outros setores

Considerar insumos de áreas como:

- suporte;
- comercial;
- CS;
- desenvolvimento;
- outras áreas envolvidas na demanda.

#### Concorrentes

Analisar mercado, referências e experiência para ampliar repertório de solução e entendimento do problema.

### Resultado esperado da etapa

Ao final da descoberta, a demanda deve ter um entendimento mais consistente sobre:

- problema;
- contexto;
- impactos;
- comportamento atual;
- oportunidades;
- restrições;
- riscos iniciais;
- dependências relevantes.

---

## 3. Definição da solução

### Objetivo

Transformar os insumos levantados em uma proposta de solução clara.

### Participantes principais

- Produto
- Design

### Papel de Produto

Produto define:

- escopo;
- critérios;
- limitações.

Essa definição deve indicar com clareza o que será entregue, o que fica fora, quais regras precisam ser respeitadas e quais restrições existem.

### Papel de Design

Design define:

- fluxo;
- arquitetura;
- protótipo.

Essa etapa traduz a solução em experiência e estrutura, ajudando a tornar o comportamento mais tangível para as demais áreas.

### Resultado esperado da etapa

Ao final dessa etapa, deve estar claro:

- o que será entregue;
- como a solução deve funcionar;
- quais critérios orientam a entrega;
- quais limitações precisam ser consideradas.

---

## 4. Gateway

### Objetivo

Validar a solução com outros setores e abrir espaço para ajustes de necessidade e priorização.

### Participantes principais

- Comercial
- CS
- Suporte
- outras áreas quando necessário

### Papel do Gateway

Essa etapa existe para comunicar a solução a outros setores e validar se existem impactos, restrições, necessidades ou percepções adicionais que influenciam a direção da demanda.

O gateway também pode gerar ajustes de necessidade e priorização antes da preparação final.

### Comitê

Quando aplicável, a solução passa por comitê com áreas como:

- Comercial;
- CS;
- Suporte.

### Resultado esperado da etapa

Ao final dessa etapa, a solução deve estar:

- comunicada às áreas relevantes;
- ajustada, se necessário;
- priorizada de forma mais consistente;
- validada o suficiente para seguir para preparação final.

---

## 5. DoR

### Objetivo

Preparar a demanda para entrada formal no Azure, com os materiais necessários para desenvolvimento e validação.

### Participantes principais

- Produto
- Design
- QA

### Papel de Produto

Produto é responsável por:

- documentação;
- cards.

### Papel de Design

Design é responsável por:

- especificações.

### Papel de QA

QA é responsável por:

- planos;
- casos de teste.

### Resultado esperado da etapa

Ao final dessa etapa, a demanda deve estar pronta para seguir com o nível de documentação e definição necessário para execução.

---

## 6. Azure atualizado

### Objetivo

Formalizar a conclusão do discovery e registrar a demanda no Azure de forma atualizada.

### Resultado esperado da etapa

Ao final do fluxo:

- o discovery está concluído;
- a documentação está organizada;
- o Azure está atualizado;
- a demanda está preparada para seguir adiante dentro do processo definido.

---

## Papel do fluxo

Esse fluxo existe para garantir que a demanda amadureça antes da implementação.

Ele ajuda a evitar problemas como:

- solução definida sem contexto suficiente;
- documentação incompleta;
- regras implícitas;
- falta de alinhamento entre áreas;
- dúvidas excessivas no refinamento;
- retrabalho no desenvolvimento.

---

## O que evitar

Evitar:

- pular etapas sem critério;
- avançar sem entendimento claro da demanda;
- definir solução antes da descoberta mínima;
- seguir para DoR com lacunas importantes;
- tratar gateway como formalidade;
- atualizar Azure sem que o discovery esteja realmente concluído.

---

## Objetivo final

O fluxo de discovery deve garantir que a demanda chegue mais madura às etapas seguintes.

Quanto melhor esse processo for executado, maior a chance de a solução ser bem direcionada, compreendida pelas áreas envolvidas e preparada com qualidade para desenvolvimento.

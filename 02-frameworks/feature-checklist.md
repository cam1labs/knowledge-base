# Checklist de Feature

## Objetivo

Este documento define um checklist prático para revisão de Features antes de seguir para refinamento ou desenvolvimento.

O objetivo é garantir que a Feature tenha clareza suficiente, regras explícitas e critérios de aceite utilizáveis por Engenharia e QA.

Este checklist não substitui análise crítica, mas ajuda a identificar lacunas comuns antes que elas virem dúvida, retrabalho ou interpretação.

---

## Quando usar este checklist

Usar este checklist:

- ao terminar de escrever uma Feature;
- antes de refinamento;
- ao revisar documentação escrita por outra pessoa;
- antes de considerar uma demanda pronta para seguir no processo.

---

## Checklist

### 1. Problema e objetivo

- [ ] Está claro qual problema a funcionalidade resolve?
- [ ] Está claro por que essa entrega é necessária?
- [ ] Está claro quem será impactado?
- [ ] O objetivo da funcionalidade está explícito?

---

### 2. Título e contexto

- [ ] O título representa claramente a funcionalidade?
- [ ] O contexto está suficiente para entender o cenário atual?
- [ ] Está claro o que existe hoje e o que muda com a entrega?
- [ ] A documentação evita texto genérico?

---

### 3. Regras de negócio

- [ ] As regras principais estão explícitas?
- [ ] Existe alguma regra importante que está implícita?
- [ ] As regras estão claras e aplicáveis?
- [ ] Exceções, limites e dependências foram documentados quando necessário?
- [ ] Existe alguma contradição com regras de outras funcionalidades?

---

### 4. Critérios de aceite

- [ ] Os critérios estão escritos em BDD?
- [ ] Os cenários estão numerados?
- [ ] Os cenários têm título claro?
- [ ] Está claro onde cada cenário se aplica?
- [ ] Os cenários são testáveis?
- [ ] Os resultados esperados estão verificáveis?
- [ ] Existe algum cenário vago ou genérico?
- [ ] Existe comportamento importante faltando?

---

### 5. Clareza para Engenharia

- [ ] Engenharia conseguiria entender o que fazer?
- [ ] Engenharia conseguiria entender como a funcionalidade deve funcionar?
- [ ] A documentação evita depender de dedução?
- [ ] O comportamento principal e os alternativos estão suficientemente claros?

---

### 6. Clareza para QA

- [ ] QA conseguiria derivar casos de teste a partir da documentação?
- [ ] Está claro o que validar?
- [ ] Está claro o que deve acontecer?
- [ ] Está claro o que não deve acontecer?
- [ ] Existem estados, validações ou erros importantes faltando?

---

### 7. Escopo e consistência

- [ ] O escopo da Feature está claro?
- [ ] Existe algo fora de escopo que precisa ser registrado?
- [ ] A Feature está grande demais?
- [ ] Faz sentido quebrar a funcionalidade em mais de uma Feature?
- [ ] A documentação está consistente com padrões já usados em outras Features?

---

### 8. Complementos

- [ ] Links, referências ou protótipos relevantes foram anexados?
- [ ] Dependências externas ou de outras áreas foram registradas?
- [ ] Dúvidas em aberto foram registradas explicitamente?
- [ ] Existe alguma informação importante que ainda está só “na conversa” e não no documento?

---

## Sinais de alerta

Se a resposta for sim para qualquer item abaixo, a Feature provavelmente precisa de revisão:

- [ ] Existem muitas regras implícitas?
- [ ] Os cenários parecem corretos, mas não deixam claro quando aplicar?
- [ ] A documentação só faz sentido para quem já conhece o contexto?
- [ ] O time precisaria de explicação verbal para entender o básico?
- [ ] Existem decisões importantes não documentadas?
- [ ] A Feature parece ampla demais para ser entendida com segurança?

---

## Como usar o checklist

Este checklist deve ser usado como apoio de revisão.

Ele não serve apenas para “marcar itens”, mas para forçar perguntas importantes antes de seguir com a demanda.

Se a Feature falhar em pontos centrais deste checklist, o ideal é revisar a documentação antes de refinamento ou desenvolvimento.

---

## Objetivo final

Uma Feature pronta deve ser clara, aplicável e suficiente para orientar implementação e validação.

Se a documentação ainda deixa espaço demais para interpretação, o checklist deve ajudar a evidenciar isso antes que vire problema.

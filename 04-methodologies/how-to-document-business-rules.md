# Como Documentar Regras de Negócio

## Objetivo

Este documento define como identificar, estruturar e documentar regras de negócio de forma clara, objetiva e sem margem desnecessária para interpretação.

O objetivo é evitar que comportamentos importantes fiquem implícitos e acabem sendo deduzidos por Engenharia, QA ou qualquer outra área envolvida na entrega.

Regra de negócio mal documentada gera dúvida, inconsistência e retrabalho.

---

## O que é uma regra de negócio

Regra de negócio é toda definição que condiciona o comportamento da funcionalidade.

Pode ser uma regra de:

- validação;
- permissão;
- restrição;
- cálculo;
- exibição;
- obrigatoriedade;
- dependência;
- exceção;
- limite operacional;
- fluxo condicional.

Se uma funcionalidade se comporta de forma diferente dependendo de uma condição, provavelmente existe uma regra de negócio envolvida.

---

## O principal problema

O erro mais comum ao documentar regras de negócio é assumir que elas estão óbvias.

Quando isso acontece, a regra fica implícita e o time precisa:

- adivinhar;
- deduzir com base em experiência anterior;
- comparar com outro fluxo;
- perguntar durante o desenvolvimento;
- descobrir no teste;
- corrigir depois.

Se a regra é importante para o comportamento, ela precisa estar explícita.

---

## Como identificar regras de negócio

Algumas perguntas ajudam a identificar se existe uma regra que precisa ser documentada:

- Quando isso pode ou não pode acontecer?
- Existe alguma condição para esse comportamento ocorrer?
- Existe alguma limitação?
- Existe uma exceção?
- Existe uma dependência de status, permissão, configuração ou tipo?
- O comportamento muda dependendo do contexto?
- Existe alguma validação obrigatória?
- Existe alguma restrição de escopo, volume, período ou formato?

Se a resposta for sim para qualquer uma delas, existe uma regra que precisa ser registrada.

---

## Princípios

### Regra importante não pode ficar implícita

Se o comportamento depende da regra, ela precisa estar documentada.

Não confiar que o time vai subentender.

---

### Regra precisa ser clara e aplicável

Uma regra bem documentada deve permitir entender:

- quando ela se aplica;
- qual comportamento ela aciona;
- o que muda quando ela não se aplica.

---

### Exceção também é regra

Sempre que existir exceção, limitação ou condição especial, isso também precisa ser documentado.

---

### Regra deve reduzir interpretação

Uma boa regra de negócio não é apenas informativa.

Ela deve orientar decisão, implementação e validação.

---

## Onde documentar regras de negócio

As regras podem aparecer em lugares diferentes, dependendo da função que cumprem.

### No contexto

Quando a regra ajuda a explicar o cenário geral da funcionalidade ou uma limitação relevante do processo atual.

---

### Na seção de regras de negócio da Feature

Quando a regra precisa ficar explícita como definição funcional da solução.

Essa costuma ser a melhor opção para regras centrais.

---

### No BDD

Quando a regra precisa aparecer aplicada em um cenário específico.

O BDD não substitui a regra geral, mas mostra como ela se comporta em uso real.

---

### Em observações

Apenas quando for complemento.

Observação não deve ser usada para esconder regra importante.

Se a regra impacta comportamento, ela não deve ficar só em observação.

---

## Como escrever uma boa regra

Uma boa regra deve responder, sempre que possível:

- qual condição existe;
- quando ela se aplica;
- qual comportamento é esperado;
- qual limite ou exceção existe.

---

## Exemplos

### ❌ Regra ruim

```text
O sistema deve tratar corretamente as notas.
```

Problemas:

- genérica;
- não diz o que significa tratar;
- não diz quando;
- não diz como;
- não é testável.

---

### ✅ Regra melhor

```text
Quando o usuário aplicar o filtro por CNPJ, o sistema deve considerar todos os documentos da pasta, e não apenas os registros visíveis na página atual.
```

Essa regra deixa claro:

- quando se aplica;
- qual comportamento esperado;
- qual interpretação incorreta deve ser evitada.

---

### ❌ Regra ruim

```text
O campo deve validar o documento.
```

---

### ✅ Regra melhor

```text
O campo deve aceitar apenas CPF ou CNPJ válidos, permitindo digitação com ou sem máscara.
```

---

## Como documentar exceções

Exceções devem ser tratadas explicitamente.

Modelo:

```text
Exceto quando [condição], o sistema deve [comportamento esperado].
```

ou

```text
Quando [condição específica], o comportamento deve ser [comportamento alternativo].
```

### Exemplo

```text
Quando o tipo de documento selecionado não possuir CFOP como atributo aplicável, o filtro de CFOP não deve ser exibido.
```

---

## Como documentar limites

Sempre que houver limite, ele deve ser objetivo.

Evitar palavras subjetivas como:

- muitos;
- grande volume;
- rapidamente;
- adequadamente;
- se necessário.

### Melhor forma

```text
O campo deve permitir no máximo 14 dígitos para CNPJ.
```

```text
A consulta deve permitir seleção de até X empresas por processamento.
```

Se o limite ainda não estiver definido, isso deve aparecer como pendência, não como regra fechada.

---

## Como documentar dependências

Quando uma regra depende de outra funcionalidade, configuração ou condição externa, isso deve ser explicitado.

### Exemplo

```text
A listagem deve exibir apenas empresas cadastradas e ativas nas configurações gerais do sistema.
```

---

## Como documentar regras condicionais

Quando o comportamento muda conforme tipo, status, perfil ou configuração, a regra precisa deixar isso visível.

### Exemplo

```text
Quando o usuário selecionar mais de um tipo de documento, a tabela deve refletir apenas as colunas aplicáveis aos tipos escolhidos.
```

---

## Como saber se a regra está boa

Antes de considerar a regra pronta, validar:

- Está claro quando ela se aplica?
- Está claro o que o sistema deve fazer?
- Existe alguma exceção não documentada?
- Existe alguma interpretação possível que ainda gere dúvida?
- QA conseguiria testar essa regra?
- Engenharia conseguiria implementá-la sem perguntar o básico?

---

## Erros mais comuns

Evitar:

- regra genérica;
- regra subjetiva;
- regra sem condição de aplicação;
- regra escondida em observação;
- regra contraditória com outro fluxo;
- regra incompleta;
- exceção não documentada;
- dependência não mencionada.

---

## Relação entre regra e BDD

A regra define o comportamento.

O BDD mostra esse comportamento aplicado em um cenário.

Os dois se complementam.

Não é ideal depender apenas do BDD para explicar uma regra ampla, e nem depender apenas da regra sem mostrar como ela se comporta em cenários importantes.

---

## Objetivo final

Documentar regra de negócio é transformar conhecimento implícito em definição clara.

Se a funcionalidade depende de uma regra, essa regra precisa ser visível, compreensível e aplicável.

Quando a regra está bem documentada, o time ganha clareza.

Quando a regra fica implícita, o time ganha dúvida.

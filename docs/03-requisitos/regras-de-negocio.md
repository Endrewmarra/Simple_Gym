# Regras de Negócio

> Fonte: documento ERS atual. O conteúdo foi apenas padronizado em Markdown.

## RN01 — Entrada do cliente

**Descrição:** O cliente precisa estar com a mensalidade paga para ter acesso à academia.

## RN02 — Cadastro do cliente

**Descrição:** Não será permitido o cadastro de clientes menores de 14 anos.

## RN03 — Mensalidade

**Descrição:** A mensalidade não poderá ser trancada, a menos que o cliente apresente atestado médico.

## RN04 — Mensalidade

**Descrição:** Não será tolerado mais de três dias de atraso da mensalidade.

## RN05 — Mensalidade

**Descrição:** A mensalidade poderá ser paga em dinheiro, Pix, cartão de crédito ou débito.

## RN06 — Treinos

**Descrição:** Os treinos do cliente somente serão montados após a assinatura de uma Declaração de Responsabilidade e de Regras de Boa Convivência nos espaços da academia.

## RN07 — Treinos

**Descrição:** A ficha de treino deve ser gerada a partir da anamnese realizada pelo professor com o cliente.

## RN08 — Cadastro do cliente

**Descrição:** Para que o cliente tenha acesso ao aplicativo, ele deverá ter ciência dos termos da LGPD.

## RN09 — Cliente

**Descrição:** Não é permitida a entrada de menores de 14 anos no ambiente interno da academia.

## RN10 — Treinadores

**Descrição:** Treinadores externos somente serão permitidos mediante apresentação do CREF ativo.

## RN11 — Funcionário

**Descrição:** Os funcionários devem ter acesso livre à catraca para passar sempre que necessário.

## RN12 — Funcionário

**Descrição:** Diferentes funcionários possuem diferentes níveis de acesso e responsabilidades.

## RN13 — Treinadores

**Descrição:** Treinadores externos devem realizar cadastro antes de entrar na academia.

## RN14 — Acesso

**Descrição:** O aluno deve passar pela catraca para acessar o centro de treinamento.

## RN15 — Acesso ao centro de treinamento

**Referências:** RN01 e RN02

**Regra em português estruturado:**

```text
Se a idade do aluno é superior a 14 anos
    Então o aluno pode ser matriculado

Se o aluno está cadastrado e sua mensalidade está paga
    Então o aluno pode acessar o centro de treinamento
```

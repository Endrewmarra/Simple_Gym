# Convenções e Notação

Não existe uma única notação universal obrigatória para todos os documentos de requisitos. Este projeto segue a convenção solicitada no modelo da disciplina e mantém identificadores estáveis para facilitar a identificação e o versionamento dos itens.

## Regras de negócio

```text
RN01, RN02, RN03...
```

As regras descrevem políticas, condições ou restrições da academia.

A forma decimal, como `RN01.1`, pode ser usada para um detalhamento subordinado, mas somente quando a relação hierárquica for realmente necessária. Para regras independentes, deve-se criar um novo identificador sequencial.

## Requisitos funcionais

```text
RF01-E
RF02-O
RF03-D
```

- `E`: evidente, percebido diretamente pelo usuário;
- `O`: oculto, executado internamente pelo sistema;
- `D`: decorativo, ligado a elementos opcionais ou de apresentação, conforme a classificação usada na disciplina.

A numeração identifica o requisito e a letra registra sua classificação. O código não deve mudar apenas porque o texto foi revisado.

## Requisitos inversos

```text
RI01, RI02...
```

Registram comportamentos que o sistema não deve permitir.

## Requisitos não funcionais

```text
RNF01, RNF02...
```

Registram características de qualidade ou restrições, como segurança e usabilidade.

## Requisitos de interface externa

```text
RIE01-U
RIE02-H
RIE03-S
RIE04-C
```

- `U`: interface com usuário;
- `H`: interface com hardware;
- `S`: interface com software;
- `C`: comunicação.

## User stories

```text
US01, US02...
```

Os códigos foram adicionados aos textos já existentes apenas para facilitar referências e versionamento. Eles não criam novas histórias.

## Regras de versionamento

1. Cada regra ou requisito deve possuir um identificador único.
2. Um identificador não deve ser reutilizado para representar outro item.
3. A revisão do texto não altera o código do requisito.
4. Um item removido não provoca a renumeração dos itens seguintes.
5. Novos itens devem seguir a sequência numérica da respectiva categoria.
6. Alterações de sentido devem ser validadas pelo grupo ou pelo stakeholder responsável.
7. As mensagens de commit devem indicar quais itens foram alterados.

Exemplos:

```text
docs: corrigir descrição do RF03
docs: atualizar RN07 após validação do grupo
docs: adicionar RF24 validado pelo stakeholder

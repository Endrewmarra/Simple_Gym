# Convenções e Notação

Não existe uma única notação universal obrigatória para todos os documentos de requisitos. Este projeto segue a convenção solicitada no modelo da disciplina e mantém identificadores estáveis para facilitar a rastreabilidade.

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

1. Um código nunca deve ser reutilizado para outro item.
2. Um item removido deve permanecer no histórico como descontinuado, sem renumeração dos seguintes.
3. Mudanças de sentido devem ser validadas pelo grupo ou stakeholder.
4. Toda inclusão, alteração ou remoção deve atualizar o changelog.
5. Referências entre regras e requisitos devem ser atualizadas na matriz de rastreabilidade.

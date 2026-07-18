# Como Contribuir

Este fluxo foi pensado para manter os documentos fáceis de revisar e rastreáveis pelo Git.

## Antes de alterar

1. Atualize sua cópia local da branch principal.
2. Crie uma branch com nome curto e descritivo.
3. Altere somente os arquivos relacionados à mudança.

Exemplos de branch:

```text
docs/revisar-rf19
docs/adicionar-rn16
docs/atualizar-user-stories
```

## Ao criar ou alterar requisitos

1. Abra uma issue usando o modelo adequado.
2. Não reutilize códigos já usados ou removidos.
3. Mantenha um requisito ou regra por seção Markdown.
4. Atualize `docs/03-requisitos/matriz-rastreabilidade.md` quando houver referência entre itens.
5. Registre a mudança em `docs/03-requisitos/changelog.md`.
6. Abra um pull request para revisão de outro integrante.

## Identificadores

- Regra de negócio: `RN01`, `RN02`...
- Requisito funcional: `RF01-E`, `RF02-O`...
- Requisito inverso: `RI01`, `RI02`...
- Requisito não funcional: `RNF01`, `RNF02`...
- Requisito de interface externa: `RIE01-U`, `RIE02-H`...
- User story: `US01`, `US02`...

Os detalhes da notação estão em [`docs/03-requisitos/convencoes.md`](docs/03-requisitos/convencoes.md).

## Pull requests

Todo pull request deve informar:

- o que foi alterado;
- por que a alteração é necessária;
- quais identificadores foram afetados;
- quais documentos relacionados foram atualizados;
- quem revisou a mudança.

## Arquivos de entrega

Não edite diretamente um PDF já entregue. Faça a alteração nos arquivos-fonte, gere uma nova versão e registre uma cópia fechada em `entregas/` com nome claro e data ou versão.

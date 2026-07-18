# Estrutura do Repositório

```text
Simple_Gym/
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   ├── alterar-requisito.md
│   │   └── novo-requisito.md
│   └── PULL_REQUEST_TEMPLATE.md
├── .vscode/
│   ├── extensions.json
│   └── settings.json
├── assets/
│   ├── imagens/
│   └── README.md
├── docs/
│   ├── 01-contexto/
│   ├── 02-elicitacao/
│   ├── 03-requisitos/
│   ├── 04-user-stories/
│   ├── 05-ers/
│   ├── 06-seminario/
│   └── 07-fichas-de-avaliacao/
├── entregas/
├── CONTRIBUTING.md
├── ESTRUTURA.md
├── LICENSE
└── README.md
```

## Função de cada área

| Caminho | Finalidade |
|---|---|
| `.github/` | Modelos para issues e pull requests. |
| `.vscode/` | Configuração compartilhada do editor. |
| `assets/` | Imagens e outros recursos visuais. |
| `docs/01-contexto/` | Empresa, problema, objetivo, escopo e glossário. |
| `docs/02-elicitacao/` | Técnicas, stakeholders e dificuldades. |
| `docs/03-requisitos/` | Fonte principal das regras e requisitos. |
| `docs/04-user-stories/` | Histórias de usuário e sua futura rastreabilidade. |
| `docs/05-ers/` | Documento ERS atual e modelos recebidos. |
| `docs/06-seminario/` | Roteiro e arquivos da apresentação. |
| `docs/07-fichas-de-avaliacao/` | Materiais cedidos pela academia. |
| `entregas/` | Cópias fechadas das versões efetivamente entregues. |

## Migração dos arquivos antigos

| Arquivo antigo | Novo local |
|---|---|
| `Requisitos/projeto-academia .docx` | `docs/05-ers/atual/ers-simple-gym.docx` |
| `Requisitos/Regras de Negocio, Requisitos de Software.docx` | `docs/05-ers/modelos/modelo-regras-e-requisitos.docx` |
| `Requisitos/Atividade 7 de Engenharia de Software - User Stories.pdf` | `docs/04-user-stories/fontes/atividade-7-user-stories.pdf` |
| `Fichas de treino/Ficha avaliacao...docx` | `docs/07-fichas-de-avaliacao/arquivos/ficha-avaliacao.docx` |
| `Fichas de treino/Ficha avaliacao...pdf` | `docs/07-fichas-de-avaliacao/arquivos/ficha-avaliacao.pdf` |
| `Requisitos/Requisitos.md` | Substituído pelos arquivos de `docs/03-requisitos/`. |
| `Fichas de treino/treinos.md` | Substituído pelo README da pasta de fichas. |

Os documentos originais foram mantidos no pacote reorganizado, apenas com nomes e caminhos mais consistentes.

# Requisitos Funcionais

> Os códigos e conteúdos correspondem ao documento original. A escrita foi normalizada sem inclusão de novas funcionalidades.

## RF01-E

**Descrição:** O sistema deve liberar o acesso da catraca para os alunos com mensalidade em dia.

- **Ordem:** Entrada
- **Prioridade:** Essencial
- **Referências:** RN01

## RF02-E

**Descrição:** O sistema deve monitorar o pagamento da mensalidade e manter seu status — em dia, atrasado ou bloqueado — atualizado.

- **Ordem:** Entrada
- **Prioridade:** Essencial
- **Referências:** RN01

## RF03-E

**Descrição:** O sistema deve verificar a idade do aluno no início do cadastro.

- **Ordem:** Entrada
- **Prioridade:** Essencial
- **Referências:** RN02

## RF04-O

**Descrição:** O sistema deve alterar o status da mensalidade para bloqueado quando o aluno permanecer com status atrasado por mais de três dias.

- **Ordem:** Processamento
- **Prioridade:** Essencial
- **Referências:** RN04

## RF05-O

**Descrição:** O sistema deve alterar o status da matrícula para em dia mediante confirmação do pagamento.

- **Ordem:** Processamento
- **Prioridade:** Essencial
- **Referências:** RN05

## RF06-E

**Descrição:** O sistema deve solicitar a confirmação da leitura dos termos de segurança e privacidade para concluir o cadastro do aluno no aplicativo.

- **Ordem:** Entrada
- **Prioridade:** Essencial
- **Referências:** RN08

## RF07-E

**Descrição:** O sistema deve apresentar um relatório financeiro para cada sessão encerrada, considerando o login e o logout de um funcionário.

- **Ordem:** Saída
- **Prioridade:** Importante
- **Referências:** —

## RF08-E

**Descrição:** O sistema deve possibilitar a matrícula de alunos na academia.

- **Ordem:** Entrada
- **Prioridade:** Essencial
- **Referências:** —

## RF09-E

**Descrição:** O sistema deve possibilitar a visualização de todos os alunos cadastrados.

- **Ordem:** Saída
- **Prioridade:** Essencial
- **Referências:** —

## RF10-O

**Descrição:** O sistema deve registrar os horários de entrada e saída dos alunos via biometria no momento da passagem pela catraca.

- **Ordem:** Entrada
- **Prioridade:** Importante
- **Referências:** RN14

## RF11-O

**Descrição:** O sistema deve monitorar e atualizar as mensalidades e os pagamentos dos alunos.

- **Ordem:** Processamento
- **Prioridade:** Essencial
- **Referências:** RN05

## RF12-O

**Descrição:** O sistema deve armazenar as fichas de treino dos alunos.

- **Ordem:** Processamento
- **Prioridade:** Essencial
- **Referências:** —

## RF13-O

**Descrição:** O sistema deve guardar os registros de alunos com matrícula inativa.

- **Ordem:** Processamento
- **Prioridade:** Essencial
- **Referências:** —

## RF14-O

**Descrição:** O sistema deve controlar o fluxo das mercadorias e dos produtos vendidos pela academia.

- **Ordem:** Processamento
- **Prioridade:** Importante
- **Referências:** —

## RF15-E

**Descrição:** O sistema deve possibilitar o cadastro de exercícios e equipamentos para a montagem dos treinos.

- **Ordem:** Entrada
- **Prioridade:** Essencial
- **Referências:** RN07

## RF16-E

**Descrição:** O sistema deve cadastrar as avaliações antropométricas de cada aluno.

- **Ordem:** Entrada
- **Prioridade:** Essencial
- **Referências:** RN07

## RF17-E

**Descrição:** O sistema deve possibilitar salvar em PDF as fichas de treino de cada aluno.

- **Ordem:** Saída
- **Prioridade:** Importante
- **Referências:** —

## RF18-E

**Descrição:** O sistema deve possibilitar o cadastro de anamneses na matrícula do aluno.

- **Ordem:** Entrada
- **Prioridade:** Essencial
- **Referências:** RN07

## RF19-E

**Descrição:** O sistema deve gerar fichas de treino compatíveis a partir das anamneses cadastradas.

- **Ordem:** Processamento
- **Prioridade:** Desejável
- **Referências:** RN07

## RF20-E

**Descrição:** O sistema deve cadastrar contas a pagar e a receber.

- **Ordem:** Entrada
- **Prioridade:** Importante
- **Referências:** —

## RF21-E

**Descrição:** O sistema deve gerar relatórios financeiros.

- **Ordem:** Saída
- **Prioridade:** Importante
- **Referências:** —

## RF22-O

**Descrição:** O sistema deve controlar as datas e os períodos de manutenção dos equipamentos.

- **Ordem:** Processamento
- **Prioridade:** Essencial
- **Referências:** —

## RF23-E

**Descrição:** O sistema deve receber sugestões de músicas dos alunos.

- **Ordem:** Entrada
- **Prioridade:** Desejável
- **Referências:** —

## RF24-O

**Descrição:** O sistema deve monitorar a lotação da academia.

- **Ordem:** Processamento
- **Prioridade:** Importante
- **Referências:** RN14

## RF25-O

**Descrição:** O sistema deve bloquear as funcionalidades do aplicativo do aluno quando o status da matrícula for bloqueado, exceto a área de pagamento.

- **Ordem:** Processamento
- **Prioridade:** Essencial
- **Referências:** RN04

## RF26-E

**Descrição:** O sistema deve conter um catálogo de produtos vendidos pela academia.

- **Ordem:** Processamento
- **Prioridade:** Desejável
- **Referências:** —

## RF27-E

**Descrição:** O sistema deve permitir que o aluno adicione itens ao carrinho de compras no aplicativo.

- **Ordem:** Entrada
- **Prioridade:** Desejável
- **Referências:** —

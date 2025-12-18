---
agent: agent
description: Criar uma nova tarefa de programação
---

# Criar Nova Tarefa de Programação

Seu objetivo é gerar uma nova tarefa de casa para os estudantes da Mergington High School.

## Passo 1: Coletar Informações da Tarefa

Se não for já fornecido pelo usuário, pergunte sobre o que será a tarefa.

## Passo 2: Criar Estrutura da Tarefa

1. Crie um novo diretório na pasta `assignments` com um nome único baseado no tópico da tarefa
2. Crie um novo arquivo no diretório chamado `README.md` com a estrutura do arquivo [assignment-template.md](../../templates/assignment-template.md)
3. Preencha os detalhes da tarefa no arquivo README
4. (Opcional) Adicione código inicial ou anexos se a tarefa precisar deles - adicione esses arquivos à mesma pasta da tarefa

## Passo 3: Atualizar Configuração do Site

Atualize a lista de tarefas no arquivo de configuração do site [config.json](../../config.json) para incluir a nova tarefa. Para o campo `dueDate`, use a data atual mais 7 dias a menos que especificado de outra forma.

## Instruções de Uso

1. Abra o Copilot Chat no VS Code e esteja no modo `Agent`.
2. Execute este prompt digitando `/new-assignment` no input do chat. Você pode apenas executar o comando e responder às perguntas ou fornecer o tópico diretamente, por exemplo:

   `/new-assignment Construindo APIs REST com framework FastAPI`

3. Verifique se o novo diretório apareceu em `assignments/` e se `config.json` foi atualizado.

## Observações

- Siga o template de tarefas em `templates/assignment-template.md` ao gerar o `README.md`.
- Se a tarefa precisar de código inicial, adicione `starter-code.py` ou `requirements.txt` conforme necessário.

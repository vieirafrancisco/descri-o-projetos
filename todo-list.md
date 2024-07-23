# TODO List

## Descrição:
Este projeto consiste em uma lista de tarefas. O usuário irá informar quais tarefas ele deseja efetuar e ter a possibilidade de conclui-las.

Exemplo ilustrativo: https://todolist-gc94.onrender.com/
*demora aproximadamente 50s para abrir*

## Tecnologias:
- [Flask](https://flask.palletsprojects.com/en/3.0.x/) *(recomendado)*
- [Django](https://www.djangoproject.com/)

## Regras:
- Deve haver um input para que o usuário possa inserir um nome/título de tarefa
- Ao inserir a tarefa, a tafera deve ser listada na página
- A última inserida sempre no topo da lista
- Deve haver um botão/checkbox para concluir a tarefa
- Tarefas concluidas devem ser listadas em outra lista (lista de concluídas)
- A última inserida sempre no topo da lista de concluídas
- Deve haver uma botão para retornar uma tarefa concluida para a lista de tarefas disponíveis
- Ao retornar a tarefa deve ficar no topo da lista de disponíveis
- Deve haver um botão para excluir uma tarefa


## Passo 1: Modelo
O modelo principal neste caso é a Tarefa. Uma Tarefa vai ter no mínimo um nome e um status. O status é onde será controlado se a tarefa foi concluida ou não

pseudocódigo:
```
Tarefa:
  nome: str
  status: str
```

## Passo 2: View
Vão existir algumas views neste projeto. Seguem algumas sugestões listadas:
- Listagem de tarefas
- Criar tarefa
- Excluir tarefa
- Concluir tarefa
- Retornar tarefa

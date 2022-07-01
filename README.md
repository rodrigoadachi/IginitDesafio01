## Dasafio 01

---

### Requisitos

  - [X] Baixar o template https://github.com/rocketseat-education/ignite-template-conceitos-do-nodejs.git
  - [X] A rota deve receber name, e username dentro do corpo da requisição

## POST /users

  - [X] Ao cadastrar um novo usuário, ele deve ser armazenado dentro de um objeto
  - [X] Certifique-se que o ID seja um UUID
  - [X] Sempre iniciar a lista todos como um array vazio
  - [X] O objeto do usuário deve ser retornado na resposta da requisição

## GET /todos

  - [X] A rota deve receber, pelo header da requisição, uma propriedade username contendo o username do usuário e retornar uma lista com todas as tarefas desse usuário

## POST /todos

  - [X] A rota deve receber title e deadline dentro do corpo da requisição e, uma propriedade username contendo o username do usuário dentro do header da requisição
  - [X] Ao criar um novo todo, ele deve ser armazenada dentro da lista todos do usuário que está criando essa tarefa
  - [X] Cada tarefa deverá estar no seguinte formato
  - [X] iniciar a propriedade done sempre como false ao criar um todo

## PUT /todos/:id

  - [X] A rota deve receber, pelo header da requisição, uma propriedade username contendo o username do usuário e receber as propriedades title e deadline dentro do corpo
  - [X] É preciso alterar apenas o title e o deadline da tarefa que possua o id igual ao id presente nos parâmetros da rota

## PATCH /todos/:id/done

  - [X] A rota deve receber, pelo header da requisição, uma propriedade username contendo o username do usuário
  - [X] Alterar a propriedade done para true no todo que possuir um id igual ao id presente nos parâmetros da rota

## DELETE /todos/:id

  - [X] A rota deve receber, pelo header da requisição, uma propriedade username contendo o username do usuário
  - [X] excluir o todo que possuir um id igual ao id presente nos parâmetros da rota

---

## Teste de Usuários

  - [] Should be able to create a new user

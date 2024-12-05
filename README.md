Neste exercício o desafio era iniciar a construção de uma API RESTful, em Golang, para realizar operações CRUD in-memory.

Os metodos construidos foram:

- `FindAll` retorna a lista de usuários (ou array vazio).
- `FindById` recebe um id e retorna o usuário com esse id (ou null se o id não existir).
- `Insert` recebe um novo usuário {firstName, lastName, bio} e retorna o usuário recém-criado {id, firstName, LastName, FullName, bio}.
- `Update` recebe um id e um usuário existente {firstName, lastName, bio} e retorna o usuário atualizado {id, firstName, LastName, FullName, bio}. (Retorne um erro caso não exista.)
- `Delete` recebe um id e retorna o usuário deletado {id, FirstName, LastName, FullName, bio}

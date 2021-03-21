# Cadastro de Usuários - Desafios Principal 2 e Complementar 2A

Desafio com o intuito de fixar os conceitos iniciais de SOLID e também a prática de documentação da API com Swagger

## Entidades

| Entidades | Atributos |
| - | - |
| user | id, name, email, admin, created_at, updated_at |

## Requisitos

- [x] Deve ser possível cadastrar um novo usuário
- [x] Deve ser possível tornar um usuário em Admin
- [x] Deve ser possível listar um usuário por ID
- [x] Deve ser possível listar todos os usuários

## Regras de negócio

- [x] Não deve ser possível cadastrar um usuário com um email já cadastrado
- [x] Não deve ser possível tornar um usuário não cadastrado em Admin
- [x] Não deve ser possível listar um usuário não cadastrado
- [x] Não deve ser possível listar todos os usuários se o usuário da requisição não for Admin
- [x] Não deve ser possível listar todos os usuários se o usuário da requisição não existir

## Recursos

- Express
- Dados armazenados em memória
- SOLID
- Clean Archtecture
- Swagger

## Iniciando o projeto

Após clonar o projeto, é necessário atualizar as dependências

### Comandos para baixar dependências e iniciar a aplicação

```bash
yarn
yarn dev
```

### Testar a aplicação

```bash
yarn test
```

## Documentação

A rota de documentação fica em *http://localhost:3333/api-doc*

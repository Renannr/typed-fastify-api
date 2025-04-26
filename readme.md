# Typed Fastify API Example

This is an example project of an API built with **Fastify**, using **Zod** for typed validation and **Swagger** for automatic documentation.

## Technologies Used

- [Fastify](https://fastify.dev/)
- [Zod](https://zod.dev/)
- [@fastify/swagger](https://github.com/fastify/fastify-swagger)
- [@fastify/swagger-ui](https://github.com/fastify/fastify-swagger-ui)
- [@fastify/cors](https://github.com/fastify/fastify-cors)

## Features

- Fully typed API
- Automatic input (body) and output (response) validation with **Zod**
- Automatic OpenAPI documentation available at `/docs`
- Basic example of creating and listing users

## Running the project

1. Install the dependencies:

```bash
npm install
```

2. Start the server:

```bash
npm run dev
```

The server will be available at `http://localhost:3333`.

API documentation can be accessed at `http://localhost:3333/docs`.

## Available Endpoints

- `GET /users` — List all users
- `POST /users` — Create a new user
  - Expected body:
    ```json
    {
    	"name": "User Name",
    	"email": "email@example.com"
    }
    ```

## Notes

This project is an example, focused on demonstrating the integration of Fastify, Zod, and Swagger for automatic documentation.

---

# Exemplo de API Typed com Fastify

Este é um projeto de exemplo de uma API construída com **Fastify**, utilizando **Zod** para validação de tipos e **Swagger** para documentação automática.

## Tecnologias Utilizadas

- [Fastify](https://fastify.dev/)
- [Zod](https://zod.dev/)
- [@fastify/swagger](https://github.com/fastify/fastify-swagger)
- [@fastify/swagger-ui](https://github.com/fastify/fastify-swagger-ui)
- [@fastify/cors](https://github.com/fastify/fastify-cors)

## Funcionalidades

- API 100% tipada
- Validação automática de entrada (body) e saída (response) com **Zod**
- Documentação automática no padrão **OpenAPI** acessível em `/docs`
- Exemplo básico de criação e listagem de usuários

## Rodando o projeto

1. Instale as dependências:

```bash
npm install
```

2. Inicie o servidor:

```bash
npm run dev
```

O servidor ficará disponível em `http://localhost:3333`.

A documentação da API estará disponível em `http://localhost:3333/docs`.

## Endpoints Disponíveis

- `GET /users` — Lista todos os usuários
- `POST /users` — Cria um novo usuário
  - Body esperado:
    ```json
    {
    	"name": "Nome do Usuário",
    	"email": "email@exemplo.com"
    }
    ```

## Observações

Este projeto é um **exemplo**, focado em demonstrar a integraçado do Fastify, Zod e Swagger para documentação automática.

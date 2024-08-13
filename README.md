
# Task Management API

## Overview

This project is a RESTful API developed in TypeScript, using Node.js (LTS) and the Express.js framework. It allows for task management operations and user authentication, incorporating a range of advanced features for robust and secure application development.

### Key Features

- **Node.js (LTS) & TypeScript**: Built with the latest Long Term Support (LTS) version of Node.js and TypeScript for type safety and better code organization.
- **Express.js Framework**: Leveraging the Express.js framework for efficient API development.
- **CRUD Operations**: Full CRUD functionality for managing tasks:
  - **Create**: Add new tasks.
  - **Read**: Retrieve all tasks or a specific task by ID.
  - **Update**: Modify an existing task.
  - **Delete**: Remove a task by ID.
- **User Authentication**: Secure user login functionality using JWT (JSON Web Tokens) for protected API access.
- **Database Integration**: Supports various database options, either local or simulated with TypeScript classes.
- **Security Best Practices**: Includes protection against SQL injection and uses hashed passwords.
- **Documentation**: Comprehensive API documentation available via Swagger, Insomnia, or Postman.
- **Advanced Features**:
  - **Pagination & Sorting**: Efficient data retrieval with support for pagination and sorting.
  - **Input Validation**: Robust validation of user inputs using Celebrate.
  - **Automated Testing**: Includes unit and integration tests for reliable code performance.
  - **Middleware**: Custom middleware for logging, authentication, and authorization.
  - **Dockerization**: Fully Dockerized setup for easy deployment.
  - **DDD Architecture**: Structured using Domain-Driven Design (DDD) principles for modular and scalable development.

## Installation

Clone the repository and install dependencies:

\`\`\`bash
git clone <repo-url>
cd api-rest-ts
npm install
\`\`\`

### Running the Application

To start the development server:

\`\`\`bash
npm run dev
\`\`\`

### API Documentation

Access the API documentation at \`http://localhost:3000/api-docs\`.

---

# API de Gerenciamento de Tarefas

## Visão Geral

Este projeto é uma API RESTful desenvolvida em TypeScript, utilizando Node.js (LTS) e o framework Express.js. Permite operações de gerenciamento de tarefas e autenticação de usuários, incorporando uma série de funcionalidades avançadas para o desenvolvimento de aplicações robustas e seguras.

### Principais Funcionalidades

- **Node.js (LTS) e TypeScript**: Construído com a versão mais recente de Long Term Support (LTS) do Node.js e TypeScript para segurança de tipos e melhor organização do código.
- **Framework Express.js**: Utilização do framework Express.js para desenvolvimento eficiente de APIs.
- **Operações CRUD**: Funcionalidade completa de CRUD para gerenciamento de tarefas:
  - **Create**: Adicionar novas tarefas.
  - **Read**: Recuperar todas as tarefas ou uma tarefa específica por ID.
  - **Update**: Modificar uma tarefa existente.
  - **Delete**: Remover uma tarefa por ID.
- **Autenticação de Usuário**: Funcionalidade segura de login de usuário usando JWT (JSON Web Tokens) para acesso protegido à API.
- **Integração com Banco de Dados**: Suporta várias opções de banco de dados, seja local ou simulado com classes TypeScript.
- **Boas Práticas de Segurança**: Inclui proteção contra injeção de SQL e utiliza senhas com hash.
- **Documentação**: Documentação completa da API disponível via Swagger, Insomnia ou Postman.
- **Funcionalidades Avançadas**:
  - **Paginação e Ordenação**: Recuperação eficiente de dados com suporte a paginação e ordenação.
  - **Validação de Entrada**: Validação robusta de entradas de usuário utilizando Celebrate.
  - **Testes Automatizados**: Inclui testes unitários e de integração para garantir o desempenho confiável do código.
  - **Middleware**: Middleware personalizado para logging, autenticação e autorização.
  - **Dockerização**: Configuração totalmente Dockerizada para fácil implantação.
  - **Arquitetura DDD**: Estruturado utilizando princípios de Domain-Driven Design (DDD) para desenvolvimento modular e escalável.

## Instalação

Clone o repositório e instale as dependências:

\`\`\`bash
git clone <repo-url>
cd api-rest-ts
npm install
\`\`\`

### Executando a Aplicação

Para iniciar o servidor de desenvolvimento:

\`\`\`bash
npm run dev
\`\`\`

### Documentação da API

Acesse a documentação da API em \`http://localhost:3000/api-docs\`.
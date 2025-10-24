# 📘 Assignment: Construindo APIs REST com FastAPI

## 🎯 Objective

Aprender a criar uma API REST simples utilizando o framework FastAPI em Python. O estudante irá construir endpoints para manipular dados de uma lista de tarefas (to-do list).

## 📝 Tasks

### 🛠️ Criar Estrutura Básica da API

#### Description
Configure um projeto FastAPI e crie o endpoint inicial para verificar se a API está funcionando.

#### Requirements
Completed program should:
- Ter um arquivo principal `main.py` que inicia o servidor FastAPI
- Ter um endpoint GET `/` que retorna uma mensagem de boas-vindas
- Instruções para rodar o projeto

### 🛠️ Endpoints para Manipular Tarefas

#### Description
Implemente endpoints para criar, listar, atualizar e remover tarefas de uma lista em memória.

#### Requirements
Completed program should:
- Endpoint GET `/tasks` para listar todas as tarefas
- Endpoint POST `/tasks` para adicionar uma nova tarefa
- Endpoint PUT `/tasks/{id}` para atualizar uma tarefa existente
- Endpoint DELETE `/tasks/{id}` para remover uma tarefa
- Utilizar modelos Pydantic para validação dos dados

### 🛠️ Documentação Interativa

#### Description
Utilize a documentação automática do FastAPI para testar os endpoints.

#### Requirements
Completed program should:
- Acessar a documentação interativa em `/docs`
- Todos os endpoints devem estar documentados automaticamente

---

**Dica:** Consulte a [documentação oficial do FastAPI](https://fastapi.tiangolo.com/) para exemplos e instruções de instalação.

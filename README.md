# 📚 Miniguia de Estudos - Node.js e APIs REST com NotebookLM

## 📖 Contexto

Este projeto foi desenvolvido como parte do desafio da DIO utilizando o NotebookLM para organizar estudos, consultar documentação e construir um guia de referência sobre desenvolvimento de APIs REST com Node.js.

O objetivo foi utilizar a IA como ferramenta de apoio ao aprendizado, organizando informações provenientes de documentações oficiais e materiais técnicos.

---

# 🎯 Objetivos

- Aprender os fundamentos do Node.js
- Revisar conceitos de APIs REST
- Entender a arquitetura em camadas
- Consolidar boas práticas para desenvolvimento Back-end
- Criar um material de consulta para estudos futuros

---

# 📚 Fontes utilizadas

## 1. Node.js Documentation

https://nodejs.org/docs/latest/api/

---

## 2. Express.js Documentation

https://expressjs.com/

---

## 3. TypeScript Handbook

https://www.typescriptlang.org/docs/

---

## 4. MDN HTTP

https://developer.mozilla.org/en-US/docs/Web/HTTP

---

## 5. REST API Tutorial

https://restfulapi.net/

---

# 🤖 Engenharia de Prompts

## Prompt 1

> Explique como funciona o Event Loop do Node.js utilizando exemplos simples.

### Resultado

Foi apresentada uma explicação clara sobre o funcionamento do Event Loop e da fila de eventos.

---

## Prompt 2

> Qual a diferença entre PUT e PATCH em uma API REST?

### Resultado

Foi explicado que:

- PUT substitui completamente um recurso.
- PATCH altera apenas os campos enviados.

---

## Prompt 3

> Como organizar uma API utilizando Controllers, Services e Repositories?

### Resultado

Foram apresentados os papéis de cada camada e exemplos de organização.

---

## Prompt 4

> Quais são os principais Status Codes utilizados em APIs REST?

### Resultado

Foram listados os códigos:

- 200 OK
- 201 Created
- 204 No Content
- 400 Bad Request
- 404 Not Found
- 500 Internal Server Error

---

# ⚠️ Dificuldades encontradas

Durante os testes foi necessário reformular alguns prompts para obter respostas mais específicas.

Exemplo:

❌ Explique REST.

Resposta muito genérica.

Após refinamento:

✅ Explique REST focando em APIs desenvolvidas com Node.js e Express.

As respostas ficaram muito mais úteis.

---

# 📝 Miniguia de Estudos

## Node.js

- Ambiente de execução JavaScript.
- Utiliza Event Loop.
- Excelente para aplicações assíncronas.

---

## Express

- Framework para construção de APIs.
- Possui sistema de rotas.
- Suporte a Middlewares.

---

## Arquitetura em Camadas

Controller

↓

Service

↓

Repository

↓

Data

Cada camada possui apenas uma responsabilidade.

---

## Métodos HTTP

GET

Consulta recursos.

POST

Cria recursos.

PUT

Atualiza completamente.

PATCH

Atualiza parcialmente.

DELETE

Remove recursos.

---

## Principais Status HTTP

200 OK

201 Created

204 No Content

400 Bad Request

401 Unauthorized

403 Forbidden

404 Not Found

500 Internal Server Error

---

# 📖 Glossário

API

Interface responsável pela comunicação entre sistemas.

REST

Padrão arquitetural para desenvolvimento de APIs.

CRUD

Create, Read, Update e Delete.

Middleware

Função executada antes da resposta da aplicação.

Repository

Camada responsável pelo acesso aos dados.

Service

Camada que contém as regras de negócio.

Controller

Camada responsável pelas requisições HTTP.

---

# 💡 Prompts reutilizáveis

- Explique este conceito utilizando exemplos simples.
- Resuma este documento em tópicos.
- Crie um mapa mental deste conteúdo.
- Gere perguntas para revisão.
- Compare os conceitos X e Y.
- Quais são as boas práticas deste assunto?
- Explique como esse conceito é aplicado em projetos reais.

---

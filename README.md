# API Livraria

![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN)

## Resumo do projeto

Projeto de API REST para prática de JavaScript.
Livraria com sistema de cadastro e manejo de livros, autores e editoras.

## Stack utilizada

- `Node.js` v16.14.2
- `express` v4.18.1,
- `knex` v2.1.0
- `sqlite3` v5.0.8

## Roadmap

- Autenticação
- Tratamento de erros
- Validações

## Mocks

- Funcoes de simulacao do Jest (nao rodam oficialmente no banco de dados)
- Aplicado em forma de reestruturação da função 'salvar'.

## Hooks

- Funcoes (gancho) que sao executadas antes de cada teste acontecer, durante, ou depois de cada teste acontecer.
- beforeEach(), afterEach(), beforeAll(), afterAll()

## Testes de requisições

- Utilizando a biblioteca supertest

## Tabelas

- test.each() e o método jest.spyOn() para obter mais informações de um determinado método. Se ele foi requisitado, e passando mais argumentos para serem testados em um mesmo teste.

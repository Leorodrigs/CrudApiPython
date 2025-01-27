# Projeto CRUD em Python e Django

Este é um projeto de estudo pessoal desenvolvido com **Python 3.13** e **Django**, com o objetivo de explorar e aprender sobre a criação de APIs REST usando o Django REST Framework.

## Pré-requisitos

Antes de iniciar o projeto, certifique-se de que você tem o **Python 3.13** instalado no seu computador. Caso não tenha, faça o download e instalação a partir do [site oficial do Python](https://www.python.org/).

## Como executar o projeto

1. Clone o repositório ou baixe os arquivos do projeto para o seu computador.
2. No terminal, navegue até a pasta do projeto.
3. Execute o servidor de desenvolvimento com o comando:   
   python manage.py runserver

4. Após iniciar o servidor, acesse as URLs abaixo no navegador ou em ferramentas como Postman para interagir com a API.

## Endpoints da API

1. Listar todos os usuários

URL: http://127.0.0.1:8000/api/users/
Método: GET
Descrição: Retorna a listagem de todos os usuários cadastrados no banco de dados.

2. Detalhar, atualizar ou deletar um usuário específico
URL: http://127.0.0.1:8000/api/users/<ID>/
Substitua <ID> pelo ID do usuário que você deseja acessar.
Métodos:
GET: Retorna os dados de um usuário específico.
PUT: Atualiza os dados do usuário especificado.
DELETE: Remove o usuário do banco de dados.

3. Criar um novo usuário
URL: http://127.0.0.1:8000/api/users/create/
Método: POST
Descrição: Permite criar um novo cadastro de usuário no banco de dados.
Exemplo de corpo da requisição (JSON):

{
  "name": "João",
  "age": 25
}

## Tecnologias utilizadas
Python 3.13
Django
Django REST Framework

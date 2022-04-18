# Projeto ServeRest
Projeto de automação de testes utilizando o framework Postman e uma API Pública.

# Framework
Postman

# API Pública
https://serverest.dev/

# Enviroment: ServeRest
<!--ts-->
  * Arquivo:
    ServeRest.postman_environment.json
    
  * Variáveis:
    * url: variável que armazena a url da API;
    * id: variável que armaneza o id do usuário (retornado no response do POST).
    
  * Coleções:
    * Arquivo:
      ServeRest.postman_collection.json
    * Criar/cadastrar um novo usuário;
    * Listar os usuários cadastrados;
    * Listar todos os usuários cadastrados;
    * Excluir o usuário cadastrado.
    
  * Requisições:
    * POST ("create"): cadastrar usuário
    * GET ("read"): buscar usuário por ID
    * GET ("read"): listar usuários cadastrados
    * DELETE ("delete"): excluir usuário
    
  * Testes das requisições:
    * Status Code;
    * Mensagem recebida. 
<!--te-->

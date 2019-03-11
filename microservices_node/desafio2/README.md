# Trilha Microservices Node.js

## Desafio II: API para Ecommerce "Nossas Lojas"

### Atividades
Refatorar a implementação da API REST do desafio I para incluir as novas especificações: 
- além de todos os endpoints e funcionalidades anteriores:
    - alterar o método `GET` para listar todas as lojas ou filtrar (por estado/cidade)
        - deve ser possível listar todas as lojas cadastradas
        - deve ser possível filtrar por um estado
        - deve ser possível filtrar por um estado E uma cidade desse estado
        - deve ser possível filtrar por um estado E várias cidades desse estado
- utilizar classes de modelo
- utilizar arquivo de configurações para atributos parametrizaveis (como URLs de conexão e afins)
- abstrair com ORM a persistência no banco de dados
- tratar exceçoes e retornos de erro, padronizados como:
  ```json
    {
        "errorCode": "",
        "msg": ""
    }
    ```
- padronizar os retornos da API para JSON e os códigos HTTP para os indicados nessa página `https://restfulapi.net/http-status-codes/`
- escrever testes simples para a aplicação utilizando Jest7
- container com o ambiente completo (node)
- container para a base de dados
- atualizar a documentação do Swagger
- coleção do postman com os todos os endpoints e exemplos de requisição

### Ferramentas e Tecnologias:
- Git
- Docker
- Node.js
- TypeScript
- TypeORM
- Banco de Dados (Oracle, MySQL, MariaDB ou MongoDB)
- Swagger
- Jest
- Postman

### Avisos 
- Deve ser implementado apenas o back-end
- Devem ser utilizadas as técnicas vistas nos treinamentos da Alura
- Esse desafio tem duração prevista de 8 horas 
- Deve ser disponibilizado em um novo repositório público (Github, Bitbucket, etc...), seguindo as práticas de versionamento aprendidas no curso
- Devem ser utilizadas as tecnologias listadas
- No repositório devem conter instruções de execução do sistema em um README

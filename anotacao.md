# Métodos HTTP:

- GET:     Buscar uma informação do backend
- POST:    Criar uma informação no backend
- PUT:     Alterar uma informação
- DELETE:  Deletar uma informação


# Tipos de parâmetros:

* Query params: Parâmetros nomeados enviados a rota após "?" (Filtros, paginação) |req.query

- Route params: Parâmetros utilizados para identificar recursos |req.params 

- Request Body: Corpo da requisição, utilizado para criar ou alterar recursos |req.body

# Banco de dados:
- SQL: MySQL, SQLite, PostgreSQL, Oracle, Microsoft SQL Server
- NoSQL: MongoDB, CouchDB

# Configuração do banco de dados:
- Driver: SELECT * FROM users;
- Query Builder: table('users').select('*').where()

## Instalação
- Query Builder que será utilizado é o KNEX, ```npm install knex```
- Após isso, instalar o driver do banco de dados a ser utilizado, neste caso SQLITE:
```npm install sqlite3```

## Utilização
- Após a instalação do banco de dados, entre ```npx knex init``` para criar o arquivo para a configuração do banco de dados

# Modelando o banco de dados

## Entidades
- ONG
- Caso (incident)

## Funcionalidades
- Login
- Logout
- Cadastro de ONG
- Cadastrar novos casos
- Deletar casos
- Listar casos específicos de uma ONG
- Listar todos os casos
- Entrar em contato com a ONG
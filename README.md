
# API NODE

Este é um servidor desenvolvido em Node.js com Fastify que foi criado para lidar com operações CRUD em vídeos, estabelecendo conexão com um banco de dados PostgreSQL. O servidor permite adicionar, listar, atualizar e excluir vídeos por meio dos endpoints disponíveis.


## Stack utilizada

**Back-end:** Node, Fastify


## Funcionalidades

- Operações CRUD (Criar vídeos, Listar vídeos, Atualizar Vídeos e Deletar Vídeos)


## Rodando localmente

Clone o projeto

```bash
  git clone https://github.com/gabriielsl/crud-fastify
```

Entre no diretório do projeto

```bash
  cd crud-fastify
```

Instale as dependências

```bash
  npm install
  npm install fastify
  npm install postgres
  npm install dotenv -D
```

Inicie o servidor

```bash
  npm run start
```


## Variáveis de Ambiente

Para rodar esse projeto, você vai precisar adicionar as seguintes variáveis de ambiente no seu .env

`PGHOST='ep-odd-bird-a5f4mp5y.us-east-2.aws.neon.tech'`

`PGDATABASE='neondb'`

`PGUSER='neondb_owner'`

`PGPASSWORD='zpi2o9tTnkPS'`

`ENDPOINT_ID='ep-odd-bird-a5f4mp5y'`


## Rodando a Aplicação

Instalar a extensão REST CLIENT para rodar o projeto


## Demonstração

Rotas da Aplicação:

https://crud-fastify.onrender.com
https://crud-fastify.onrender.com/videos



[def]: https://github.com/gabriielsl
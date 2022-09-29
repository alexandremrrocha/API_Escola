# Escola de Inglês

Uma API para uma escola de inglês, utilizando o sequelize para fazer as manipulações no banco de dados MySQL. Projeto em andamento...


## Diagrama Relacional do projeto

<img src="Diagrama Relacional.jpg"></img>

## Stack utilizada

- Node
- Express
- MySQL
- Sequelize

## Aprendizados

- MySQL
- Sequelize

## Rodando localmente

- Clone o projeto

- Entre no diretório do projeto

- Instale as dependências

```bash
  npm install
```

- Crie e configure um arquivo config.json para a conexão com seu banco

- Rode o migrate
  
```bash
  npx sequelize-cli db:migrate
```

- Rode as seeders

```bash
  npx sequelize-cli db:seed:all
```

- Inicie o servidor node

```bash
  npm run dev
```

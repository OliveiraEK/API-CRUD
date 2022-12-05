##Criação de API simples com CRUD

* Criar frase
* Listar frase
* Atualizar frase
* Deletar frase

# Para instalar as dependências rode o comando

`npm install`

# Crie o banco de dados abaixo:

CREATE TABLE `phrases` (
    `id` int(11) NOT NULL,
    `author` varchar(100) NOT NULL,
    `txt` text NOT NULL
)

# Para rodar o projeto rode o comando

`npm run start-dev`
# API cadastro
 API de cadastro de filmes

Funcionamento:

1º - Primeiramente conectamos o projeto ao MongoDB. Para executar o projeto, vamos usar o comando "node src/index.js" no CMD ou no VSCode.

2º - Pelo Insomnia, criamos a função GET (List) que vai mostrar a lista de filmes cadastrados pelo usuário. Na barra da navegação vamos colocar "http://localhost:3000/" e em seguida clicamos em "Send" para executar a aplicação.

3º - Caso queira adicionar um filme, o usuário deve criar a opção POST (Create), responder todos os campos e clicar em "Send".

4º - Caso queira deletar, DEL (Deletar) + http://localhost:3000/ + ID do filme e clicar em "Send" para fazer deletar o filme.

5º - Caso queira mudar o nome, PUT (Update) + http://localhost:3000/ + ID do filme e clicar em "Send" para fazer alteração no título ou em outros campos.
# README

Para criar o ArticlesController e sua action index, vamos executar o controlador gerador (com a opção --skip-routes porque já temos um rota apropriada):

$ bin/rails generate controller Articles index --skip-routes

Para definir um model, utilizaremos um gerador de models:

$ bin/rails generate model Article title:string body:text

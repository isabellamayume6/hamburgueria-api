# hamburgueria-api
##EndPoints

Cadastro
POST /register
POST /signup
POST /users

Qualquer um desses 3 endpoints irá cadastrar o usuário na lista de "Users", sendo que os campos obrigatórios são os de email e password. Você pode ficar a vontade para adicionar qualquer outra propriedade no corpo do cadastro dos usuários.

Login
POST /login
POST /signin

Qualquer um desses 2 endpoints pode ser usado para realizar login com um dos usuários cadastrados na lista de "Users"

Produtos
GET / /products

Esse endpoint está disponivel apenas para leitura  é usado para renderizar as components na tela

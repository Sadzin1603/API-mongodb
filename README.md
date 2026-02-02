# API-mongodb
API em node.js com conexão no mongo db para estudo

recebe conteudo em JSON no body

{
  name:"AKO",
  email:"akonaru@gmail.com",
  age:"18"
}

npm i

para instalar as depencias e depois

npm run dev para iniciar o servidor na porta http://localhost:3000/usuarios

no delete e put passe o id do usuario a ser editado ou deletado

http://localhost:3000/usuarios/123

PORTAS
GET - retorna todos os usuarios (se passar uma query ele retorna uma lista especifica)
  http://localhost:3000/usuarios?age=18
POST - adiciona um usuario
PUT - edita um usuario
DELETE - delet um usuario



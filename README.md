# Projeto API (Collection API Restful Booker) 🏨

A API permite que os usuários interajam com reservas de hotéis, permitindo funcionalidades como criação, atualização e recuperação de reservas. Abaixo, você encontrará detalhes sobre os Endpoints da API e como utilizá-los.


### URL Base
A URL base para a API Restful-Booker é: https://restful-booker.herokuapp.com

### Autenticação
Para acessar os endpoints da API, você precisa obter um token de autenticação, o token deve ser incluído no cabeçalho Cookie para solicitações subsequentes aos endpoints protegidos.

### Endpoints Testados

###### 1. Verificar status da API
Método: GET

Descrição: Verificar o status e conectividade da API
###### 2. Obter Reservas por ID
Método: GET

Descrição: Recuperar os detalhes de uma reserva pelo ID único
###### 3. Obter Reservas por Nome
Método: GET

Descrição: Recuperar reservas pelo primeiro nome e sobrenome do hóspede
###### 4. Obter Reservas por Data
Método: GET

Descrição: Recuperar reservas pelas datas de check-in e check-out.
###### 5. Criar Reserva
Método: POST
Descrição: Criar uma nova reserva
###### 6. Atualizar Reserva
Método: PUT

Descrição: Atualizar uma reserva existente pelo ID.
###### 7. Atualizar Parcialmente uma Reserva
Método: PATCH

Descrição: Atualizar parcialmente uma reserva existente pelo ID
###### 8. Apagar Reserva
Método: DELETE

Descrição: Apagar uma reserva existente pelo ID

#### Testando a API
A API pode ser testada usando várias ferramentas, como Postman, cURL ou linguagens de programação com bibliotecas de solicitações HTTP. A coleção Postman fornecida (formato JSON) pode ser importada para o Postman para testar rapidamente os endpoints da API.





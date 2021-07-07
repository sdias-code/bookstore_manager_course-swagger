# Curso Udemy
## Comece a aprender Spring Boot agora de forma prática!
### Instrutor: Rodrigo Peleias

#### O que eu aprendi:
1 - Desenvolver uma API REST com o Spring Boot.

2 - Preparar o setup de ambiente de desenvolvimento para projetos Java de forma simples e rápida.

3 - Aprendi sobre padrões de arquitetural REST

4 - isponibilizar o projeto para uso na nuvem através do Heroku, de forma simples e gratuita!

### Como usar:
git clone https://github.com/sdias-code/digitalinnovationone.git

### No terminal:
Execute o projeto no terminal, digite o seguinte comando:
mvn spring-boot:run

### Inserindo dados:
Usar aplicativo Postman
Método Post(local)
http://localhost:8080/api/v1/books

Entrada de Dados: JASON

 `{
"name": "Investidor Inteligente",
"pages": 200,
"chapters": 20,
"isbn": "0-596-52068-9",
"publisherName": "Harper Collins",
"author": {
"name": "Benjamin Grahan",
"age": 100
}
}`

### Consulta dos dados inseridos:
consulta por id
Método GET (local)
http://localhost:8080/api/v1/books/1

### Testando app na nuvem:
Inserindo dados -- Método Post
https://meuapp-bookmanager.herokuapp.com/api/v1/books
 
Lendo dados inseridos -- Método GET
https://meuapp-bookmanager.herokuapp.com/api/v1/books/1
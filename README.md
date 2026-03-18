# Projeto Fullstack - Login (Angular + Java)

Este projeto é uma aplicação fullstack com sistema de login, composta por:
- Frontend em Angular (reutilizável)
- Backend em Java com Spring Boot

O backend em java segue um modelo geral de verificar de logi ne registro com elementos de segurança básicos e reaproveitáveis.

## Tecnologias do backend:
- Java 21
- Spring Boot
  - Spring Web
  - Dev Tools
  - Spring Security
  - Lombok
  - h2
  - JWT

## Funcionamento
O sistema roda em http://localhost:8080. Utilize o arquivo [json](https://github.com/dev-pedr0/angular-java-api/blob/master/src/test/Java%20Authenticator.postman_collection.json) na pasta test no Postman para testar o funcionamento das rotas. 

## Utilização
Requisitos:
- Java 21
- Maven

Clone o projeto:
```
git clone https://github.com/dev-pedr0/angular-java-api
```
Em [application.properties](https://github.com/dev-pedr0/angular-java-api/blob/master/src/main/resources/application.properties) configure o seu api.security.token.secret

## Frontend
O frontend pode ser encontrado [aqui](https://github.com/dev-pedr0/angular-java-login-page).

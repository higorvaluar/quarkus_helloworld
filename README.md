# Hello World com Quarkus

Este é um simples projeto de Hello World utilizando Quarkus, uma framework Java para microserviços.

## Endpoints

O projeto cria um endpoint REST simples:

- **GET** `/users`: Retorna a mensagem "Hello World!"

## Tecnologias Utilizadas

- **Quarkus**: Framework Java para microserviços
- **JAX-RS**: API para criação de serviços RESTful
- **Jakarta EE**: API de componentes para Java
- **JSON**: Formato de dados utilizado para resposta do endpoint

## Como Rodar o Projeto

1. Clone o repositório:

    ```bash
    git clone https://github.com/<seu-usuario>/<nome-do-repositorio>.git
    cd <nome-do-repositorio>
    ```

2. Compile e rode o projeto com o Maven:

    ```bash
    ./mvnw compile quarkus:dev
    ```

3. Acesse o endpoint no navegador ou Postman:

    ```bash
    http://localhost:8080/users
    ```

    A resposta será:

    ```json
    "Hello World!"
    ```

## Contribuições

Sinta-se à vontade para contribuir com melhorias ou sugestões para o projeto.

## Licença

Este projeto está sob a Licença MIT.

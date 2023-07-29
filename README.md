# Projeto de API REST com Spring Boot e JPA para um site de Filmes com MongoDB

Este é um projeto de API REST desenvolvido utilizando o framework Spring Boot e a tecnologia JPA (Java Persistence API) com o banco de dados MongoDB. A finalidade desta API é fornecer endpoints para acessar informações sobre filmes, permitindo a visualização dos filmes disponíveis e a criação de avaliações (reviews) para cada filme.

## Funcionalidades

A API possui as seguintes funcionalidades:

1. **Listar todos os filmes**: Retorna a lista completa de filmes disponíveis no sistema.

2. **Visualizar detalhes de um filme**: Permite visualizar informações detalhadas sobre um filme específico.

3. **Criar uma avaliação (review)**: Permite aos usuários criar avaliações para um filme, com pontuação e comentário.

4. **Listar avaliações de um filme**: Retorna todas as avaliações disponíveis para um filme específico.

## Endpoints

A API possui os seguintes endpoints para interação:

1. `GET /api/filmes`: Retorna todos os filmes disponíveis no sistema.

2. `GET /api/filmes/{id}`: Retorna os detalhes do filme correspondente ao ID fornecido na URL.

3. `POST /api/filmes/avaliacoes`: Cria uma nova avaliação para o filme correspondente ao ID fornecido.


## Tecnologias Utilizadas

O projeto foi desenvolvido utilizando as seguintes tecnologias:

- **Spring Boot**: Framework Java para agilizar e facilitar o desenvolvimento de aplicações.

- **JPA (Java Persistence API)**: Tecnologia que permite a integração com o banco de dados MongoDB e o mapeamento objeto-documento.

- **MongoDB**: Banco de dados orientado a documentos, utilizado para armazenar as informações dos filmes e avaliações.

## Executando o Projeto

Para executar o projeto localmente, siga os passos abaixo:

1. Certifique-se de ter o Java Development Kit (JDK) instalado em sua máquina.

2. Certifique-se de ter o MongoDB instalado e em execução em sua máquina.

3. Clone este repositório para o seu ambiente de desenvolvimento.

4. Configure as informações do banco de dados MongoDB no arquivo `application.properties`.

5. Execute a aplicação utilizando sua IDE de preferência ou através do seguinte comando no terminal:

```bash
$ ./mvnw spring-boot:run

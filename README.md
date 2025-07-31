# Projeto Spring Boot com JPA / Hibernate

Projeto desenvolvido no curso **Java COMPLETO** do [devsuperior.com.br](https://devsuperior.com.br) pelo Dr. Nelio Alves.

## Descrição

Aplicação backend em Java com Spring Boot, que implementa um web service com operações CRUD usando JPA/Hibernate para persistência de dados. O projeto possui um modelo de domínio completo e inclui tratamento de exceções, testes com banco de dados em memória (H2) e deploy opcional para Heroku.

## Funcionalidades

- Criação do projeto Spring Boot com Java 17 e Maven
- Modelo de domínio com entidades: User, Order, Product, Category, OrderItem, Payment
- Relacionamentos JPA:
  - One-to-many (User -> Orders)
  - Many-to-many com atributos extras (OrderItem)
  - One-to-one (Payment -> Order)
- Camadas separadas:
  - Resource (Controller REST)
  - Service (Regras de negócio)
  - Repository (JPA Repository)
- Banco de dados de teste H2 com seeding inicial (dados pré-carregados)
- Operações CRUD completas para usuários (Create, Retrieve, Update, Delete)
- Tratamento global de exceções (ResourceNotFoundException, DatabaseException)

## Tecnologias e Dependências

- Java 17
- Spring Boot (Spring Web, Spring Data JPA)
- Hibernate
- Banco H2 (em memória para testes)
- Maven

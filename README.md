🚀 Smart Delivery

Backend de um sistema de delivery desenvolvido com Java e Spring Boot.

O objetivo deste projeto é simular o desenvolvimento de um produto real, aplicando boas práticas de engenharia de software, arquitetura, testes automatizados e evolução incremental da aplicação.

Neste primeiro momento, o foco será exclusivamente no backend, utilizando uma arquitetura MVC bem estruturada. Conforme o projeto evoluir, a aplicação será refatorada para uma arquitetura mais desacoplada, culminando em um monólito modular e, posteriormente, em microsserviços.

Status: 🚧 Em desenvolvimento

⸻

Objetivos

* Desenvolver uma API REST utilizando Java e Spring Boot.
* Consolidar conhecimentos em desenvolvimento backend.
* Construir um projeto de portfólio com padrão corporativo.
* Demonstrar boas práticas de arquitetura e qualidade de código.
* Evoluir a arquitetura conforme o crescimento do domínio.

⸻

Stack

Linguagem

* Java 21

Framework

* Spring Boot 3.x

Persistência

* PostgreSQL
* Spring Data JPA
* Flyway

Segurança

* Spring Security
* JWT

Cache

* Redis

Documentação

* Swagger / OpenAPI

Testes

* JUnit 5
* Mockito
* Testcontainers

Build

* Maven

Infraestrutura

* Docker
* Docker Compose

⸻

Arquitetura

A evolução da arquitetura será realizada em etapas.

Fase 1

Arquitetura MVC

Controller
↓
Service
↓
Repository
↓
Database

O objetivo desta fase é construir uma base sólida, priorizando organização, boas práticas e simplicidade.

Evolução prevista

MVC
↓
MVC Modular
↓
Arquitetura Hexagonal
↓
Monólito Modular
↓
Microsserviços

Cada etapa será implementada apenas quando houver uma necessidade real, evitando complexidade desnecessária.

⸻

Funcionalidades previstas

* Autenticação com JWT
* Cadastro de clientes
* Cadastro de restaurantes
* Catálogo de produtos
* Carrinho de compras
* Checkout
* Gestão de pedidos
* Pagamentos
* Rastreamento de entregas
* Notificações

⸻

Roadmap

Foundation

* Inicialização do projeto
* Configuração do Git
* Docker Compose
* PostgreSQL
* Redis
* Flyway
* Swagger

Authentication

* Cadastro de usuários
* Login
* JWT

Customer

* CRUD de clientes

Restaurant

* CRUD de restaurantes

Catalog

* Gestão de produtos

Cart

* Carrinho de compras

Order

* Fluxo de pedidos

Payment

* Pagamentos

Delivery

* Gestão de entregas

⸻

Boas práticas

Durante o desenvolvimento serão adotadas as seguintes práticas:

* Clean Code
* SOLID
* Conventional Commits
* Versionamento de banco com Flyway
* Testes unitários e de integração
* Documentação da API com Swagger
* Histórico de commits incremental
* Evolução arquitetural orientada ao domínio

⸻

Como executar

Clone o repositório:

git clone https://github.com/caiohcordeiropereira/smart-delivery.git

Entre na pasta do projeto:

cd smart-delivery

Execute a aplicação:

./mvnw spring-boot:run

⸻

Licença

Este projeto foi desenvolvido para fins de estudo, aperfeiçoamento técnico e composição de portfólio.
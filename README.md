# Spring Boot API - Usuários

API REST desenvolvida com **Spring Boot**, com operações básicas de CRUD (Create, Read, Delete) para gerenciamento de usuários.

Projeto criado com foco em aprendizado e portfólio para vagas **Back-end Java Júnior**.

---

## Tecnologias Utilizadas

- Java 17+
- Spring Boot
- Spring Data JPA
- Hibernate
- Banco de dados H2 (em memória)
- Maven
- Postman (testes de API)

---

## Estrutura do Projeto

src/main/java/com/gabriel/springbootapi
├── controller 
│ └── UsuarioController.java 
├── model 
│ └── Usuario.java 
├── repository 
│ └── UsuarioRepository.java 
├── service 
│ └── UsuarioService.java 
└── SpringbootapiApplication.java 

---

## Como executar o projeto

### Pré-requisitos
- Java instalado
- Maven instalado
- IDE (VS Code / IntelliJ)

### Passos
```bash
git clone https://github.com/seu-usuario/springbootapi.git
cd springbootapi
mvn spring-boot:run

A aplicação iniciará em:
http://localhost:8081

 Testando a API
 Criar usuário

POST /usuarios

{
  "nome": "Gabriel",
  "email": "gabriel@email.com"
}

 Listar usuários

GET /usuarios

 Buscar usuário por ID

GET /usuarios/{id}

 Deletar usuário

DELETE /usuarios/{id}

 Banco de Dados H2

Acesse o console do H2:

http://localhost:8081/h2-console


Configuração:

JDBC URL: jdbc:h2:mem:testdb

Usuário: sa

Senha: (vazio)

 Objetivo do Projeto

Este projeto tem como objetivo praticar:

Arquitetura REST

Padrão MVC

Integração com banco de dados

Boas práticas com Spring Boot

Autor

Gabriel Azevedo de Oliveira Barros
Estudante de Ciência da Computação

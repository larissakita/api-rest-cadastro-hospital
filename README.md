# API VollMed

API REST desenvolvida com Java e Spring Boot para gerenciamento de usuários e autenticação utilizando JWT.

## Tecnologias utilizadas

* Java
* Spring Boot
* Spring Security
* JWT
* MySQL
* Maven

## Funcionalidades

* CRUD completo de usuários,médicos e pacientes
* Autenticação com JWT
* Proteção de rotas
* Validação de dados
* API REST

## Resultado

https://github.com/user-attachments/assets/eb03ae38-0981-4d30-b6f2-3effaf735aba

## Como executar o projeto

### Clone o repositório

```bash
git clone https://github.com/larissakita/api-rest-cadastro-hospital.git
```

### Configure o banco de dados

Crie um banco MySQL e configure o arquivo:

```text
application-example.properties
```

### Execute o projeto

```bash
./mvnw spring-boot:run
```

## Estrutura do projeto

* `controller` → endpoints da API
* `domain` → entidades e DTOs
* `infra/security` → autenticação e segurança JWT


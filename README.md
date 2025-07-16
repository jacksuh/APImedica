# 🏥 API Médica - Sistema de Gerenciamento de Consultas

Esta é uma API RESTful desenvolvida em Java com Spring Boot para gerenciar **consultas médicas**, pacientes e médicos. Ideal para clínicas, consultórios ou sistemas de agendamento online.

---

## 🚀 Tecnologias Utilizadas

- Java 17
- Spring Boot
- Spring Data JPA
- PostgreSQL
- Maven
- Swagger (OpenAPI)
- JUnit 5 (para testes - em progresso)
- Docker (em breve)

---

## 📦 Funcionalidades da API

- ✅ Cadastro de pacientes
- ✅ Cadastro de médicos
- ✅ Agendamento de consultas
- ✅ Cancelamento de consultas
- 🔄 Atualização de dados
- 🔍 Listagem com filtros (por data, médico, paciente) *(em progresso)*

---

## 📁 Estrutura do Projeto

```bash
src/
├── main/
│ ├── java/
│ │ └── com.api.medica/
│ │ ├── model/
│ │ ├── repository/
│ │ ├── controller/
│ │ └── service/
│ └── resources/
│ ├── application.properties
│ └── data.sql
└── test/
```


---

## ⚙️ Como Rodar Localmente

### Pré-requisitos:
- Java 17
- PostgreSQL ou Docker
- Maven

```bash
# Clone o repositório
git clone https://github.com/jacksuh/APImedica.git

# Acesse a pasta
cd APImedica

# Instale as dependências
mvn clean install

# Configure seu banco no arquivo application.properties
spring.datasource.url=jdbc:postgresql://localhost:5432/apimedica
spring.datasource.username=seu_usuario
spring.datasource.password=sua_senha

# Rode a aplicação
mvn spring-boot:run
```
📑 Documentação da API

http://localhost:8080/swagger-ui/index.html

🧪 Testes

# Em progresso: testes unitários com JUnit
mvn test

📌 Melhorias Futuras
🔒 Autenticação com JWT

💬 Mensagens de validação melhoradas

🗓️ Agenda com filtros de disponibilidade

🐳 Docker e docker-compose

🧪 Testes completos (unitário + integração)

🤝 Contribuições
Sinta-se livre para clonar, estudar e sugerir melhorias.
Pull Requests são bem-vindos! 🚀

```bash
🧑‍💻 Autor
Jackson Silva dos Santos
GitHub
E-mail: jacksonsdss@gmail.com
```
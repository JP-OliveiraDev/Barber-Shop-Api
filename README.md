# **BarberShop - Backend!** 🚀

Bem-vindo ao **BarberShop!** 🚀

Este é o repositório do backend do Barber Scheduler, um sistema desenvolvido para facilitar o agendamento de horários em barbearias. O backend foi construído utilizando Java com Spring Boot, garantindo robustez e escalabilidade na gestão de clientes, serviços e horários agendados.

## 🚀 Funcionalidades

✅ Cadastro de clientes com informações pessoais.

✅ Agendamento de horários com controle de disponibilidade.

✅ Gerenciamento de serviços oferecidos pela barbearia.

✅ Conexão com banco de dados PostgreSQL para armazenamento seguro.

✅ Migrações automáticas utilizando Flyway.


## 🛠️ Tecnologias Utilizadas

☕ Java → Linguagem de programação utilizada no backend.

🌱 Spring Boot → Framework para facilitar o desenvolvimento do backend.

🗄️ PostgreSQL → Banco de dados relacional utilizado no projeto.

📜 Flyway → Gerenciamento e versionamento do banco de dados.

🔧 Spring Data JPA → Abstração para comunicação com o banco de dados.

🔄 Spring Web → Camada para criação da API REST.

💡 Lombok → Redução de boilerplate no código Java.

📌 Validation → Validações automáticas de dados.

## 📦 Dependências principais

• Flyway Migration SQL

• Spring Data JPA

• Spring Boot DevTools

• PostgreSQL Driver

• Spring Web

• Lombok

• Validation


## ▶️ Como Executar o Projeto

### 📌 Pré-requisitos

Antes de começar, certifique-se de ter instalado:

• Java 17+

• Maven

• PostgreSQL configurado


### 🖥️ Passos para executar o Backend

**1️⃣ Clone o repositório**
```
git clone https://github.com/seu-usuario/barber-scheduler-backend.git
```
**2️⃣ Acesse o diretório do projeto**
```
cd barber-scheduler-backend
```
**3️⃣ Configure o banco de dados**

Crie um banco de dados PostgreSQL e atualize as credenciais no arquivo **application.properties**:
```
spring.datasource.url=jdbc:postgresql://localhost:5432/barberscheduler
spring.datasource.username=seu-usuario
spring.datasource.password=sua-senha
```
**4️⃣ Execute o projeto**
```
mvn spring-boot:run
```
**5️⃣ A API estará disponível em**
```
🔗 http://localhost:8080
```
### 🤝 Contribuição

Contribuições são bem-vindas! Se tiver sugestões, correções ou melhorias, sinta-se à vontade para abrir uma issue ou enviar um pull request.

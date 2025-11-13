# 🧩 Login Page - Backend (Spring Boot)

Este é o backend da aplicação **Login Page**, desenvolvido em **Spring Boot**.  
Ele é responsável por gerenciar autenticação, registro de usuários e comunicação com o banco de dados.  
O projeto está totalmente integrado ao frontend em Angular.

🔗 **Frontend do projeto:** [login-page-angular](https://github.com/IanPedr/login-page-angular)

---

## 🚀 Tecnologias utilizadas

- **Java 17+**
- **Spring Boot**
- **Spring Security**
- **JWT (JSON Web Token)**
- **Spring Data JPA**
- **Hibernate**
- **Maven**
- **Banco de dados:** H2Database (ou outro que você estiver usando)

---

## ⚙️ Como rodar o projeto localmente

### 1️⃣ Clonar o repositório
```bash
git clone https://github.com/IanPedr/login-page-backend.git
2️⃣ Entrar na pasta do projeto
bash
Copiar código
cd login-page-springboot
3️⃣ Configurar o banco de dados
No arquivo src/main/resources/application.properties, configure suas credenciais:

properties
Copiar código
spring.datasource.url=jdbc:postgresql://localhost:5432/nome_do_banco
spring.datasource.username=seu_usuario
spring.datasource.password=sua_senha
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
4️⃣ Rodar o projeto
Pelo terminal:

bash
Copiar código
mvn spring-boot:run
Ou diretamente pelo IntelliJ clicando no botão ▶️ ao lado da classe principal (Application).

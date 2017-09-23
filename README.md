# Obar API

Projeto da API do Obar

# Setup

Crie o arquivo **application.properties** no diretório: **src/main/resources/application.properties** com o seguinte:

```bash
spring.datasource.url=jdbc:mysql://localhost/db
spring.datasource.username=user
spring.datasource.password=password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.database-platform=org.hibernate.dialect.MySQL5Dialect
spring.datasource.driver-class-name=com.mysql.jdbc.Driver
```

`spring.datasource.url=jdbc:mysql://localhost/db`: url do banco de dados onde **db** deve ser o nome do seu banco de dados.

`spring.datasource.username=user`: usuário do banco de dados onde **user** deve ser o nome do seu usuário do banco de dados.

`spring.datasource.password=password`: senha do banco de dados onde **password** deve ser a senha do seu usuário do banco de dados.

`spring.jpa.hibernate.ddl-auto=update`: configuração do DDL do Hibernate.

`spring.jpa.database-platform=org.hibernate.dialect.MySQL5Dialect`: dialeto do banco de dados.

`spring.datasource.driver-class-name=com.mysql.jdbc.Driver`: local da classe JDBCDriver do banco de dados.

# Run

Importe o projeto o Spring Suite Tools (STS) e rode a aplicação no **Spring Boot Dashboard**.
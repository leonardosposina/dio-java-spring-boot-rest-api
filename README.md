# Digital Innovation One

## Desenvolvendo um sistema de gerenciamento de pessoas em API REST com Spring Boot

Esse exercício ensinou a construir do zero uma API REST com Spring Boot para cadastro e gerenciamento de pessoas, onde
também foram abordados os seguintes tópicos:

- Setup inicial do projeto com o [Spring Boot Initializr][Spring Initializr].
- Criação de modelo de dados para o mapeamento de entidades em banco de dados.
- Desenvolvimento de operações **CRUD** para o recurso **person**.
- Implantação do sistema na nuvem através do **[Heroku][Heroku]**.

### 🖱 [Clique aqui para ver online.][spring-boot-rest-api]

---

### 📑 Instruções

Para executar o projeto são necessários os seguintes pré-requisitos:

- Java 11 ou versões superiores.
- Maven 3.6.3 ou versões superiores.

Para executar o projeto, digite o seguinte comando na raiz do projeto:

```console
mvn spring-boot:run
```

Para acessar a REST API, utilize o seguinte *endpoint*:

```console
http://localhost:8080/api/v1/person
```

---

### 📚 Referências

- [Java SE Development Kit 11 Download](https://www.oracle.com/br/java/technologies/javase-jdk11-downloads.html)
- [Maven](https://maven.apache.org/)
- [Insomnia](https://insomnia.rest/download/)


- [Spring Boot](https://spring.io/projects/spring-boot)
- [Spring Initializr][Spring Initializr]


- [Documentação oficial do Lombok](https://projectlombok.org/)
- [Documentação oficial do Map Struct](https://mapstruct.org/)
- [Referência para o padrão arquitetural REST](https://restfulapi.net/)

[Heroku]:https://www.heroku.com/

[Spring Initializr]:https://start.spring.io/

[spring-boot-rest-api]:https://dio-java-spring-boot-rest-api.herokuapp.com/api/v1/person
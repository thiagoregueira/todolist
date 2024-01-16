# Projeto TodoList

Este é um projeto Java Spring Boot que implementa uma API REST para um aplicativo de lista de tarefas (TodoList).

## Características

- O projeto é baseado em Maven e usa Spring Boot versão 3.1.4.
- O código é escrito em Java 17.
- O banco de dados é H2, um banco de dados em memória.
- O projeto usa o JPA (Java Persistence API) para persistência de dados.


## Funcionalidades

- Usuários podem ser criados e gerenciados. Veja `UserModel.java` e `IUserRepository.java`.
- Tarefas podem ser criadas, atualizadas e gerenciadas. Veja `TaskModel.java` e `ITaskRepository.java`.
- As tarefas são associadas a um usuário específico.
- O projeto inclui um manipulador de exceções global. Veja `ExceptionHandlerController.java`.

## Como executar o projeto

1. Clone o repositório.
2. Navegue até o diretório do projeto.
3. Execute o comando `./mvnw spring-boot:run` para iniciar o aplicativo.
4. O aplicativo estará disponível em `http://localhost:8080`.



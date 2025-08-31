Tarefas API
API REST desenvolvida em Java com Spring Boot para gerenciamento de tarefas. Permite criar, listar, atualizar e excluir tarefas, além de consultar por responsável e data de entrega. Utiliza banco de dados H2 em memória para facilitar testes e desenvolvimento.

Funcionalidades:
Cadastro de tarefas com nome, responsável e data de entrega
Listagem de todas as tarefas
Consulta de tarefa por ID
Atualização e remoção de tarefas
Validação automática dos campos
Console H2 disponível para visualização do banco

Tecnologias:
Java 24
Spring Boot 3
Spring Data JPA
Spring Validation
H2 Database
Maven

Como executar:
Clone o repositório
Execute ./mvnw spring-boot:run
Acesse a API em http://localhost:8080/tarefas
Acesse o console H2 em http://localhost:8080/h2-console

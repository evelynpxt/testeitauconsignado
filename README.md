# testeitauconsignadoevelyn
nova plataforma do Consignado do Itaú


Para desenvolver a nova plataforma do Consignado do Itaú, vamos utilizar o Spring Framework, especificamente o Spring Boot, para facilitar a criação de uma aplicação robusta e modular, que segue os princípios de microservices. Abaixo estão os passos detalhados para o desenvolvimento do projeto.

Estrutura do Projeto
Microservices
Customer Service: Responsável por gerenciar informações dos clientes.
Simulation Service: Responsável por realizar simulações de empréstimos.
Contract Service: Responsável por armazenar contratos após a contratação do empréstimo.
Tecnologias Utilizadas
Spring Boot: Para a criação de cada microservice.
Spring Data JPA: Para interações com o banco de dados.
Spring Cloud Netflix (Eureka): Para Service Discovery.
Spring Cloud Gateway: Para o API Gateway.
H2 Database: Para o banco de dados em memória.
Docker: Para containerização dos serviços.
JUnit/Mockito: Para testes unitários.
Java 11: Linguagem de programação.
Maven: Gerenciador de dependências.
Arquitetura
Customer Service

Endpoints:
GET /customers/{cpf}: Retorna informações do cliente com base no CPF.
GET /customers: Lista todos os clientes.
Simulation Service

Endpoints:
POST /simulations: Cria uma nova simulação.
GET /simulations: Lista todas as simulações.
Contract Service

Endpoints:
POST /contracts: Armazena um novo contrato.
GET /contracts: Lista todos os contratos.
Gateway Service

Utiliza Spring Cloud Gateway para rotear chamadas de API para os microservices apropriados.

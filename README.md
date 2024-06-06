# testeitauconsignadoevelyn
nova plataforma do Consignado do Itaú

Documentação

# Plataforma de Consignado Itaú

## Introdução
Este projeto é uma plataforma de simulação de empréstimos consignados desenvolvida utilizando microservices com Spring Boot.

## Tecnologias Utilizadas
- Java 22
- Spring Boot
- Spring Cloud Netflix (Eureka, Gateway)
- Spring Data JPA
- MySQL Server
- Docker

## Estrutura do Projeto
- Customer Service
- Simulation Service
- Contract Service
- Gateway Service
- Eureka Server

## Executando o Projeto
1. Clone o repositório.
2. Navegue até o diretório de cada microserviço e execute `mvn clean install` para compilar os projetos.
3. Inicie os serviços usando Docker Compose:
   ```sh
   docker-compose up --build

   
### Conclusão
Com esses componentes, a plataforma de Consignado do Itaú estará pronta para realizar as operações básicas de identificação de clientes, simulação de empréstimos e armazenamento de contratos. A arquitetura de microservices permitirá uma fácil escalabilidade e manutenção da aplicação.



# api-produto
API RESTfull  de Produto  Usando Springboot com Postgres

![Static Badge](https://img.shields.io/badge/build-passing-brightgreen?style=for-the-badge)


API de Produtos

Este projeto é uma API RESTful desenvolvida utilizando o ecossistema Spring Framework, projetada para gerenciar informações de produtos por meio das operações CRUD (Criar, Consultar, Atualizar e Excluir).

O principal objetivo deste projeto é demonstrar a implementação de boas práticas modernas de desenvolvimento backend com Java e Spring Boot, seguindo uma arquitetura em camadas que promove organização, manutenção e escalabilidade do código. 

O projeto demonstra o fluxo completo de uma API REST, desde o recebimento das requisições até a persistência e recuperação dos dados no PostgreSQL, seguindo práticas amplamente utilizadas no mercado de desenvolvimento de software.




![image URL](https://github.com/FredCassani/api-produto/blob/main/ChatGPT%20Image%209%20de%20jun.%20de%202026,%2009_32_50.png?raw=true)

TECNOLOGIAS UTILIZADAS
SPRING WEB

Responsável por expor os endpoints REST e gerenciar as requisições e respostas HTTP. Permite que clientes interajam com a aplicação por meio das operações REST padrão.

SPRING DATA JPA

Utilizado para simplificar o acesso ao banco de dados e as operações de persistência. Fornece abstrações de repositório que reduzem código repetitivo e aumentam a produtividade ao trabalhar com bancos de dados relacionais.

POSTGRESQL DRIVER

Permite a comunicação entre a aplicação e o banco de dados PostgreSQL através do JDBC.

POSTGRESQL

Banco de dados relacional utilizado para armazenar e gerenciar os dados dos produtos de forma segura e eficiente.

VALIDATION

Utilizado para validar os dados recebidos nas requisições, garantindo a integridade das informações e impedindo que dados inválidos sejam persistidos no banco de dados.

Arquitetura

A aplicação segue uma arquitetura em camadas:

Camada Controller: Responsável por receber e responder às requisições HTTP.
Camada Service: Contém as regras de negócio e a lógica da aplicação.
Camada Repository: Responsável pelas operações de acesso ao banco de dados.
Camada Database: Persistência dos dados utilizando PostgreSQL.
Funcionalidades
Cadastro de produtos
Consulta de produtos
Consulta de produto por ID
Atualização de produtos
Exclusão de produtos
Validação de dados
Persistência em banco de dados
Arquitetura RESTful
Objetivos de Aprendizado

Este projeto foi desenvolvido para fortalecer conhecimentos em:

Java
Spring Boot
Desenvolvimento de APIs REST
Banco de Dados Relacionais
JPA e Hibernate
Arquitetura de Software
Validação de Dados
Boas Práticas de Desenvolvimento Backend




Integração Spring Boot e PostgreSQL
Este projeto utiliza o Spring Boot em conjunto com o PostgreSQL para persistência dos dados. A conexão é realizada através do driver JDBC do PostgreSQL, configurado no arquivo application.properties. O banco de dados está hospedado localmente (localhost) na porta padrão 5432, utilizando o banco api-produto. O Hibernate, por meio do Spring Data JPA, é responsável pelo mapeamento objeto-relacional (ORM), permitindo que as entidades Java sejam convertidas automaticamente em tabelas no banco de dados. A propriedade spring.jpa.hibernate.ddl-auto=update foi utilizada para que a estrutura do banco seja criada e atualizada automaticamente conforme a evolução das entidades da aplicação.

![image URL](https://github.com/FredCassani/api-produto/blob/main/Captura%20de%20tela%202026-06-09%20100101.png?raw=true)



Realização de testes da API Usando Modo DEBUG,E após isso indo para o  POSTMAN criar os produtos.

![image URL](https://github.com/FredCassani/api-produto/blob/main/controller.png?raw=true)

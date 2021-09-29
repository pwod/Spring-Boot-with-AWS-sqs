### **Prova de Conceito: aws-sqs-spring-boot-poc**

Intuito dessa Aplicação é demostrar na Prática como podemos criar
uma App que se comunica com SQS da Aws.

Requisitos:
Criação de Fila na AWS com Nome: spring-boot-poc

**Inserir AWS credentials no arquivo de Configuração .YAML**

substitua amazon.accessKey e amazon.secretKey pelas credenciais de sua conta

Para rodar aplicação executar os Seguintes comandos:

`mvn spring-boot:run`

`mvn clean package && java -jar target/aws-sqs-spring-boot-poc-0.0.1-SNAPSHOT.jar
`
~~~~~~~~Tecnologias Utilizadas:~~~~~~~~
Java: 11
Maven
Spring Boot 2.5.5
Spring Cloud AWS
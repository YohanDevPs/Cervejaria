<h1>Projeto do Bootcamp - DIO</h1>
<h2> Este projeto aborda o desenvolvimento de testes unitarios de uma API REST para o gerenciamento de estoques de cerveja.</h2>

Foram usados as seguintes tecnologias para a execução do projeto:

* Java 17.
* maven-4.0.0.
* Frameworks para testes unitários: JUnit, Mockito e Hamcrest. 
* Intellj IDEA Community Edition.
* Postman


Abordamos os seguintes tópicos:

* Testes unitarios de API REST para o gerenciamento de estoques de cerveja. 
* Testes de validação do sistema de gerencimento.
* Desenvolvimento de testes unitários para validação de funcionalides básicas: criação, listagem, consulta por nome e exclusão de cervejas.
* TDD: apresentação e exemplo prático em 2 funcionaliades importantes: incremento e decremento do número de cervejas no estoque.

Para executar o projeto no terminal, digite o seguinte comando:

```shell script
mvn spring-boot:run 
```

Para executar a suíte de testes desenvolvida durante a live coding, basta executar o seguinte comando:

```shell script
mvn clean test
```

Após executar o comando acima, basta apenas abrir o seguinte endereço e visualizar a execução do projeto:

```
http://localhost:8080/api/v1/beers
```





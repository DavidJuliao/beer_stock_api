<h2>Desenvolvimento de testes unitários para validar uma API REST de gerenciamento de estoques de cerveja.</h2>

 Projeto simples de controle de estoque de cervejas através de API aplicando a prática do TDD.

Para executar o projeto no terminal,basta abrir o diretório onde o projeto esta no terminal e digitar o seguinte comando:

```shell script
mvn spring-boot:run 
```

Para executar a suíte de testes , basta executar o seguinte comando:

```shell script
mvn clean test
```

Após executar o comando acima, basta apenas abrir o seguinte endereço e visualizar a execução do projeto:

```
http://localhost:8080/api/v1/beers
```

Tecnologias Utilizadas:

* Java 14.
* Junit.
* Hamcrest.
* Mockito.
* Swagger







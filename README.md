# JDBC CRUD - Java + SQLite

Projeto desenvolvido durante meus estudos de Java e JDBC, acompanhando o curso do professor **Arnaldo Souza**.

O objetivo do projeto foi praticar a conexão de uma aplicação Java com um banco de dados SQLite e desenvolver operações básicas de persistência de dados utilizando JDBC.

## Tecnologias utilizadas

- Java
- JDBC
- SQLite
- SQL

## Conceitos praticados

- Conexão com banco de dados
- `Connection`
- `PreparedStatement`
- `ResultSet`
- `Statement`
- Operações CRUD
- `executeQuery()` e `executeUpdate()`
- Padrão DAO
- Tratamento de exceções
- Persistência de dados

## Operações realizadas

O projeto permite realizar operações de:

- Inserção de produtos
- Consulta de produtos
- Consulta por ID
- Atualização de produtos
- Exclusão de produtos
- Listagem de produtos

## Estrutura

O projeto utiliza uma separação simples entre as responsabilidades:

```text
ConexaoDB
    ↓
ProdutoDAO
    ↓
Banco de Dados SQLite
```

O `ProdutoDAO` é responsável pelas operações de acesso aos dados, enquanto a classe `ConexaoDB` centraliza a criação da conexão com o banco.

## Sobre o projeto

Este é um **projeto de estudo**, desenvolvido acompanhando o conteúdo apresentado no curso do professor Arnaldo Souza. O projeto foi utilizado para praticar e compreender os conceitos fundamentais de JDBC e acesso a bancos de dados em Java.

O desenvolvimento também serviu como preparação para os próximos estudos em **Spring Boot, JPA/Hibernate e desenvolvimento de APIs REST**.

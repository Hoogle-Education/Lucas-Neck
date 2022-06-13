# Introdução ao SQL

## Classes:
1. atributos - o que ela tem
2. métodos - é o que ela pode fazer

## Mapeamento Objeto Relacional

modelo de diagrama UML

|Pessoa|
|:-:|
|Nome|
|Idade|
|Altura|
|Telefone|
|-------|
|fazAniversario( )|
|mudaTelefone( novoTelefone )|

## Tabela

A tabela é uma organização de dados baseadas em colunas.

|Nome|Idade|Altura|Telefone|
|:-:|:-:|:-:|:-:|
|Joao|23|1.75|123123|
|Maria|17|1.80|321321|

## Chave Primária (`Primary key`) 🔑

É a chave capaz de caracterizar um objeto na tabela de forma **única**.

|id|Nome|Idade|Altura|Telefone|
|:-:|:-:|:-:|:-:|:-:|
|1|Joao|23|1.75|123123|
|2|Maria|17|1.80|321321|

## Chave Extrangeira (`Foreign key`) 🔐

A chave extrangeira é uma forma de conexão com dados de tabelas externas.

***Seller table***
|id|Name|Email|BirthDate|BaseSalary|
|:-:|:-:|:-:|:-:|:-:|
|1|Maria|maria@gmail.com|2200.0|2|
|2|Alex|alex@gmail.com|2000.0|3|

***department table***
|id|Name|
|:-:|:-:|
|1|Food|
|2|Technology|
|3|Clothes|

## Indices (`Indexes`) 📗

Basicamente é capaz de categorizar as tabelas por um ou mais critérios que tenham uma relevância maior no processo de buscar e inserção.

## CRUD 

1. Create
2. Update
3. Retrieve
4. Delete

## Triggers 🚩

São avisos/checkpoints/flags que são lançados quando alguma determinada condição for atendida

# Esquemas

Conjuntos de tabelas organizadas e possivelmente relacionadas.

# Views

A **view** é o que pode ser generado através de consultas/requisições em uma tabela

# Functions / Procedures

É um conjunto bem definido de regras a serem repetidas.


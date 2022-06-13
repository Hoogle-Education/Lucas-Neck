# Comandos introdutórios SQL 

## **Criando** um novo banco de dados

Um banco de dados funciona de maneira similar a um esquema, basta usarmos o comendo abaixo:

```sql
CREATE DATABASE meu_banco_de_dados
```

## **Deletando** um banco de dados

```sql
DROP DATABASE meu_banco_de_dados
```

## `CREATE` e `DROP`

Os comando `CREATE` e `DROP` servem para que possamos criar não apenas tabela, mas são palavras-chaves essenciais para criação de conteúdos em uma tabela.

## Criando/Deletando uma tabela

⚠️ Para que a tabela seja criada no banco de dados correto, clicar duas vezes no nome do banco de dados até ele ficar em destaque.

De maneira similar, usaremos como base porém usamos da seguinte maneira:

Criando tabela
```sql
CREATE TABLE minha_tabela
```

Deletando uma tabela:
```sql
DROP TABLE minha_tabela
```

## Checando duplicidades (`IF NOT EXISTS`)

Podemos usar este comando nas ***query*'s** para evitar que tabelas sejam criadas de modo duplicado, ou evitar o retorno de algum erro no compilador.

```sql
CREATE TABLE IF NOT EXISTS minha_tabela
```

## **Views** - Comando `SELECT`

O comando `SELECT` possui uma extensão grande já que envolve uma grande parte das views que criamos.

Por isso iremos explorar versões mais simples e a medida que encontrarmos novos comandos criaremos views mais complexas.

```sql
SELECT * FROM minha_tabela
```

As palavras chave deste comando de modo traduzido:

1. `SELECT`: SELECIONE
2. \* : "qualquer dado"
3. `FROM`: "VINDO DA"/"EM"
4. `minha_tabela`: tabela que queremos consultar

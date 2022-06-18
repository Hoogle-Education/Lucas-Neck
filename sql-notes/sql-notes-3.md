# Filtrando Tabelas

## **Localizando** - Comando `Where` 

`Where` serve para nos apresentar um filtro aos dados da tabela, baseado em alguma condição (expressão booleana)

```sql
  SELECT *
  FROM aluno
  WHERE nota >= 7.0
```

## **Limites** - Comando `LIMIT`

```SQL
  SELECT *
  FROM aluno
  LIMIT [numero_a_ser_exibido]
```


```SQL
  SELECT *
  FROM aluno
  LIMIT [numero_a_ser_exibido] OFFSET [numero_a_ser_pulado];
```

## BUSCAR - Comando `FETCH`

```SQL
  SELECT *
  FROM aluno
  FETCH NEXT 5 ROWS ONLY;
```

## EM - Comando `IN`

```sql
  SELECT *
  FROM aluno
  WHERE 
    idade == 33 
    OR idade == 35
    OR idade == 37;
```

```sql
  SELECT *
  FROM aluno
  WHERE idade IN (33, 35, 37);
```
# Resettare l'indice di una tabella

Nel caso in cui una tabella abbia una colonna ID autoincrementale talvolta può essere opportuno resettare il suo valore di base (ad esempio in seguito ad una truncate table)

``` sql
DBCC CHECKIDENT ('tableName', RESEED, 1) 
```
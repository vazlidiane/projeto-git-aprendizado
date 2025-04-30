# Estudo Dia 02 - SQL

Hoje aprendi sobre comandos básicos em SQL:

- `SELECT`: para selecionar colunas
- `FROM`: para indicar a tabela
- `WHERE`: para aplicar filtros
- `ORDER BY`: para ordenar os resultados

Exemplo:
```sql
SELECT nome, idade
FROM clientes
WHERE idade > 30
ORDER BY nome ASC;


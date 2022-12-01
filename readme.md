# db-first

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario
Confermate lettura come al solito e buon db! 

## Table name: 
-  used_cars

## Table column: 

- id - BIGINT | AI NOTNULL UNIQUE
- brand - VARCHAR(255) | NOTNULL
- color - VARCHAR(255)  | NULL
- model - VARCHAR(255) | NOTNULL
- km - FLOAT(7,1) | NOTNULL
- price - DECIMAL(8,2) | NOTNULL
- note - TEXT | NULL
- plot - TEXT | NULL
- year - YEAR | NOTNULL
- cover - VARCHAR(255) |NULL

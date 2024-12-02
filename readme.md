## DataBase structure
Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

## table name:
- Dealer

## Table Structure:
- ID        | BIGINT - AUTO INCREMENT - PK(UNIQUE) - NO NULL
- Brand     | VARCHAR(20) - NO NULL - 
- Model     | VARCHAR(50) - NO NULL
- Fuel      | VARCHAR(15) - NO NULL
- New       | TINYINT -DEFAULT (0)
- Aveilable | TINYINT -DEFAULT (0)
- Year      | YEAR - NONULL
- Km        | INT - NULL
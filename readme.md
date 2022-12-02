# Database auto

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

## Table name: cars

## Table Columns:

- id | BIGINT PK AI NOTNULL UNIQUE INDEX
- vin | VARCHAR(20) NULL UNIQUE 
- model | VARCHAR(60) NULL NULL INDEX
- brand |  VARCHAR(60) NULL INDEX
- year | YEAR NULL 
- mileage | FLOAT (8, 2) 
- engine | VARCHAR (20)
- fuel-tipe | VARCHAR(20) INDEX
- gear | VARCHAR(10) 
- color | VARCHAR(50)
- is_new | TYNYINT DEFAULT(0)
- is_available | TYININT DEFAULT(1) INDEX
- price | DECIMAL(8, 2)
- doors | TYNYINT
- seats | TYNYINT
- horses_power | VARCHAR(4)
- description | TEXT
- owners | TYNYINT
- notes | TEXT




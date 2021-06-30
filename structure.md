# concessionario

## vendita auto usate



- id                BINGINT PRIMARY KEY UNIQUE NOTNULL INDEX
- marca             VARCHAR(100) NOTNULL
- modello           VARCHAR(100) NULL
- carrozzeria       VARCHAR(50) NULL
- prezzo            SMALLINT NOTNULL
- finanziamento     FLOAT(6,3) NULL
- valutazione       VARCHAR(100) NOTNULL
- anno              YEAR NOTNULL
- chilometraggio    MEDIUMINT NOTNULL
- potenza           VARCHAR(5) NULL
- cambio            VARCHAR(50) NULL 
- carburante        VARCHAR(50) NULL
- venditore         VARCHAR(50) NOTNULL
- stato             VARCHAR(50) NOTNULL
- porte             TINYINT NULL
- verniciatura      VARCHAR(50) NULL
- foto              VARCHAR(50) NULL

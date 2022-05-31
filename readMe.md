# database università

## dipartimenti
- ID_Dipartimento: NOT_NULL, UNIQUE, INDEX, AI
- nome: VARCHAR(30) NOT_NULL, UNIQUE, INDEX


## corsi di laurea
- ID_CorsoDiLaurea: NOT_NULL, UNIQUE, INDEX, AI
- nome: VARCHAR(30) NOT_NULL, UNIQUE, INDEX
- durata: DECIMAL (5,2) NULL

## studenti
- ID_Studente: NOT_NULL, UNIQUE, INDEX, AI
- Nome: VARCHAR(30) NOT_NULL
- Cognome: VARCHAR(30) NOT_NULL
- email: VARCHAR(50) NOT_NULL
- telefono: VARCHAR(30) NULL
- DataDiNascita: DATETIME NULL

## corsi
- ID_Corso: NOT_NULL, UNIQUE, INDEX, AI
- nome: VARCHAR(70) NOT_NULL

## appelli
- ID_Appello: NOT_NULL, UNIQUE, INDEX, AI
- data: DATETIME NOT_NULL

## insegnanti
- ID_Docente: NOT_NULL, UNIQUE, INDEX, AI
- nome: VARCHAR(30) NOT_NULL
- cognome: VARCHAR(30) NOT_NULL
- email: VARCHAR(50) NOT_NULL
- telefono: VARCHAR(30) NULL
- DataDiNascita: DATETIME NULL
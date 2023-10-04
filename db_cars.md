# esercizio di oggi: Database First

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
potete usare una tabellina markdown o un semplice file di testo se vi riesce più comodo!
Mi raccomando: quello che ci interessa sono: il nome della colonna, il tipo di dato ed eventuali attributi!

Esempio:
COLONNA | TIPO | ATTRIBUTI
-- | -- | --
marca | varchar(50) | NOT NULL
modello | varchar(50) | NOT NULL
ecc..
:top: BONUS: nomi colonne in inglese
Buon divertimento e a domani!

## svolgimento:

| cosa            | tipo        | attributi            |
| --------------- | ----------- | -------------------- |
| chassis         | bigint      | primary key          |
| brand           | Varchar(50) | notNull              |
| model           | varchar(50) | notnull              |
| displacement    | smallint    | null, unsigned       |
| anno_produzione | year        | notnull              |
| price           | mediumint   | notnull, unsigned    |
| number_owner    | tinyint     | unsigned, default(1) |
| note            | text        | null                 |
| plate           | char(7)     | notnull              |
| km              | mediumint   | unsigned, notnull    |
| fuel            | varchar(25) | notnull              |

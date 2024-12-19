# Car table

| name         | type        | attributes                          | key     | notes                                                         |
| ------------ | ----------- | ----------------------------------- | ------- | ------------------------------------------------------------- |
| id           | BIGINT      | NOT NULL - AUTOINCREMENT - UNSIGNED | PRIMARY | identifucativo di ogni veicolo nel sistema                    |
| marca        | VARCHAR(30) | NOT NULL                            |         | marca del veicolo (es. skoda, toyota, BMW, ecc...)            |
| anno_veicolo | YEAR        | NOT NULL                            |         | anno di uscitra del modello di veiolo (es. )                  |
| modello      | VARCHAR(30) | NOT NULL                            |         | modello del vicolo(es. corolla, fabia, x6, ecc... )           |
| tipo         |             |                                     |         | tipo di veicolo (es. suv, coupe, musclecar, hypercar, ecc...) |

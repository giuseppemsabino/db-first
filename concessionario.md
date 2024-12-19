# Car table

| name             | type        | attributes                          | key     | notes                                                                         |
| ---------------- | ----------- | ----------------------------------- | ------- | ----------------------------------------------------------------------------- |
| id               | BIGINT      | NOT NULL - AUTOINCREMENT - UNSIGNED | PRIMARY | identifucativo di ogni veicolo nel sistema                                    |
| marca            | VARCHAR(30) | NOT NULL                            |         | marca del veicolo (es. skoda, toyota, BMW, ecc...)                            |
| anno_veicolo     | YEAR        | NOT NULL                            |         | anno di uscitra del modello di veiolo (es. )                                  |
| data_inserimento | DATETIME    | NOT NULL                            |         | data e ora di quando il veicolo e stato inserito nel sistema                  |
| modello          | VARCHAR(30) | NOT NULL                            |         | modello del vicolo(es. corolla, fabia, x6, ecc... )                           |
| tipo             | VARCHAR(50) | NOT NULL                            |         | tipo di veicolo (es. suv, coupe, musclecar, hypercar, ecc...)                 |
| chillometraggio  | INT         | NULL                                |         |                                                                               |
| emisioni_veicolo |             | NOT NULL                            |         |                                                                               |
| alimentazione    |             | NOT NULL                            |         | tipo di alimentazione del veicolo(es. benzina, disel, gpl, elettrico, hybrid) |
| cambio           |             | NOT NULL                            |         |                                                                               |
| colore           |             | NOT NULL                            |         |                                                                               |
| owners_num       | MEDIUMINT   | NULL                                |         |                                                                               |
| disponibilita    |             | BOOLEAN                             |         |                                                                               |
| condizioni       |             |                                     |         |                                                                               |
| descrizione      |             |                                     |         |                                                                               |

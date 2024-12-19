# Car table

| name             | type        | attributes                          | key     | notes                                                                                        |
| ---------------- | ----------- | ----------------------------------- | ------- | -------------------------------------------------------------------------------------------- |
| id               | BIGINT      | NOT NULL - AUTOINCREMENT - UNSIGNED | PRIMARY | identifucativo di ogni veicolo nel sistema                                                   |
| marca            | VARCHAR(30) | NOT NULL                            |         | marca del veicolo (es. skoda, toyota, BMW, ecc...)                                           |
| anno_veicolo     | YEAR        | NOT NULL                            |         | anno di uscitra del modello di veiolo (es. )                                                 |
| data_inserimento | DATETIME    | NOT NULL                            |         | data e ora di quando il veicolo e stato inserito nel sistema                                 |
| modello          | VARCHAR(30) | NOT NULL                            |         | modello del vicolo(es. corolla, fabia, x6, ecc... )                                          |
| tipo             | VARCHAR(20) | NOT NULL                            |         | tipo di veicolo (es. suv, coupe, musclecar, hypercar, ecc...)                                |
| chillometraggio  | INT         | NOT NULL                            |         | chillometri percorsi dal veicolo                                                             |
| emisioni_veicolo |             | NOT NULL                            |         | (es. euro6,5,4,3,2,1,ecc...)                                                                 |
| alimentazione    |             | NOT NULL                            |         | tipo di alimentazione del veicolo(es. benzina, disel, gpl, elettrico, hybrid)                |
| cambio           |             | NOT NULL                            |         | (es. manuale, automatico, hybrid)                                                            |
| colore           |             | NOT NULL                            |         | colore del veicolo                                                                           |
| owners_num       | MEDIUMINT   | NULL                                |         | numeri di proprietari che ha avuto il veicolo fino oggi                                      |
| disponibilita    | BOOLEAN     |                                     |         | se il veicolo e disponibile ("SI" o "NO")                                                    |
| condizioni       | VARCHAR(30) |                                     |         | stato atuale del veicolo se e in buone condizioni o meno                                     |
| descrizione      | TEXT        |                                     |         | descrizione opzionale del venditore per fare specoìificazioni al delveicolo                  |
| prezzo           | DECIMAL     | NULL                                |         | prezzo del veicolo in vendita(null preche qualcuno puo rigalare il suo veicolo se lo deside) |

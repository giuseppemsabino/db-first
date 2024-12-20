# Car table

| name              | type        | attributes                          | key     | notes                                                                                           |
| ----------------- | ----------- | ----------------------------------- | ------- | ----------------------------------------------------------------------------------------------- |
| id                | BIGINT      | NOT NULL - AUTOINCREMENT - UNSIGNED | PRIMARY | identificativo di ogni veicolo nel sistema                                                      |
| marca             | VARCHAR(30) | NOT NULL                            |         | marca del veicolo (es. Skoda, Toyota, BMW, ecc...)                                              |
| anno_veicolo      | YEAR        | NOT NULL                            |         | anno di uscita del modello di veicolo                                                           |
| data_inserimento  | DATETIME    | NOT NULL                            |         | data e ora di quando il veicolo è stato inserito nel sistema                                    |
| modello           | VARCHAR(30) | NOT NULL                            |         | modello del veicolo (es. Corolla, Fabia, X6, ecc...)                                            |
| tipo              | VARCHAR(20) | NOT NULL                            |         | tipo di veicolo (es. SUV, coupé, muscle car, hypercar, ecc...)                                  |
| chilometraggio    | INT         | NOT NULL                            |         | chilometri percorsi dal veicolo                                                                 |
| emissioni_veicolo | CHAR(5)     | NOT NULL                            |         | emissioni del veicolo (es. Euro6, 5, 4, 3, 2, 1, ecc...)                                        |
| alimentazione     | VARCHAR(10) | NOT NULL                            |         | tipo di alimentazione del veicolo (es. benzina, diesel, GPL, elettrico, ibrido)                 |
| cambio            | VARCHAR(10) | NOT NULL                            |         | tipo di cambio (es. manuale, automatico, ibrido)                                                |
| colore            | VARCHAR(15) | NOT NULL                            |         | colore del veicolo                                                                              |
| owners_num        | MEDIUMINT   | NULL                                |         | numero di proprietari che il veicolo ha avuto fino a oggi                                       |
| disponibilita     | BOOLEAN     | NOT NULL                            |         | se il veicolo è disponibile ("SI" o "NO")                                                       |
| condizioni        | VARCHAR(30) | NOT NULL                            |         | stato attuale del veicolo (es. buone condizioni o meno)                                         |
| descrizione       | TEXT        | NULL                                |         | descrizione opzionale del venditore per fare specificazioni sul veicolo                         |
| prezzo            | DECIMAL     | NULL                                |         | prezzo del veicolo in vendita (null perché qualcuno può regalare il suo veicolo se lo desidera) |

# Logische Operatoren

### Logische Operatoren verarbeiten Wahrheitswerte

|   Operator	|  Beispiel 	|  Funktion 	|
|---	|---	|---	|
|   &	|  a & b	|  Verknüpft a und b durch ein logisches UND 	|
|  && 	|  a && b 	|  Verknüpft a und b durch ein logisches UND (nur bedingte Auswertung von b) 	|
|   │	|  a │ b	|  Verknüpft a und b durch ein logisches ODER 	|
|  ││ 	|  a ││ b	|  Verknüpft a und b durch ein logisches ODER (nur bedingte Auswertung von b) 	|
|  ! 	|  a ! b 	|  Negiert a 	|

***

+ Bei a && b: b muss nur dann ausgewertet werden, wenn die Auswertung von a den Wert **true** ergibt

+ Bei a ││ b: b muss nur dann ausgewertet werden, wenn die Auswertung von a den Wert **false** ergibt

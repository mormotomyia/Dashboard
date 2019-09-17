# Anhand des [Beispieldokumentes](Dashboard.xlsx) zur vollständigen Dokumentation

## Aufbau Lookup

```Excel
=INDEX($A$3:$J$11;MATCH(G20;A3:A11;0);MATCH(I18;A3:J3;0))
```

```Excel
=INDEX(Tabelle mit Zeilen/Spalten-Überschriften;MATCH(Nutzerfeld;Überschriften für die Spalten;0 = exakter Match);MATCH(Nutzerfeld;Überschriften für die Zeilen;0))
```



## Aufbau Nutzerfelder
___
Optional:  
```Excel
=CONCAT(G18;K18)
```

```Excel
=CONCAT(Zeit;Typ)
```
___



`Data Validation` für Zeiten  
`Data Validation` für Tpyen  
mit Legende


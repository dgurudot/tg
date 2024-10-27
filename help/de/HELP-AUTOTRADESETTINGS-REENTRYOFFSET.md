# **ReEntry Offset**

## Zweck: 

- Mit dieser Einstellung können Sie den Offset vom Briefkurs (zum Zeitpunkt des Kaufs) oder Gebotskurs (zum Zeitpunkt des Verkaufs) anpassen. 
- Der Handel wird zunächst zum im Signal empfangenen Kaufpreis getätigt. 
- Wenn er nicht innerhalb von 5 Sekunden ausgeführt wird, erfolgt ein erneuter Kaufversuch zum Briefkurs plus Offset (Standard ist 0,05). 
- Wenn ein Verkaufssignal empfangen wird, wird der Handel ebenfalls zum im Signal empfangenen Verkaufspreis getätigt, aber wenn dieses nicht ausgeführt wird, erfolgt der erneute Kaufversuch zum Gebot minus Offset (Standard ist 0,05).

## Beispiel:

- Kaufsignal 100 $ mit Gebot bei 99 $ und Briefkurs bei 101 $. Wenn die anfängliche Limitorder für den Kauf bei 100 $ nicht ausgeführt wird, erfolgt der erneute Kaufversuch bei 101 $ + 0,05 = 101,05 $.

- Verkaufssignal 200 $ mit Gebot bei 199 $ und Briefkurs bei 201 $. Wenn die anfängliche Limitorder für den Verkauf bei 200 $ nicht ausgeführt wird, erfolgt ein erneuter Versuch bei 199 $ - 0,05 = 198,95 $


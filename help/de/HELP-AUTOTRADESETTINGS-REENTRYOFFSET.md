# **Wiedereinstiegs-Offset**

## Zweck:

– Mit dieser Einstellung können Sie den Offset vom Briefkurs (zum Zeitpunkt des Kaufs) oder Geldkurs (zum Zeitpunkt des Verkaufs) anpassen.
– Der Handel wird zunächst zum im Signal empfangenen Kaufpreis platziert.
– Wird er nicht innerhalb von 5 Sekunden ausgeführt, erfolgt ein erneuter Kaufversuch zum Briefkurs plus Offset (Standard: 0,05).
– Wird ein Verkaufssignal empfangen, erfolgt der Handel zum im Signal empfangenen Verkaufspreis. Wird dieses jedoch nicht ausgeführt, erfolgt der erneute Kaufversuch zum Geldkurs minus Offset (Standard: 0,05).

## Beispiel:

– Kaufsignal 100 $ mit Geldkurs 99 $ und Briefkurs 101 $. Wird die anfängliche Limit-Order für den Kauf bei 100 $ nicht ausgeführt, erfolgt der erneute Kaufversuch bei 101 $ + 0,05 = 101,05 $.

– Verkaufssignal 200 $ mit Geldkurs 199 $ und Briefkurs 201 $. Wird die ursprüngliche Limit-Order für den Verkauf bei 200 $ nicht ausgeführt, erfolgt ein erneuter Versuch bei 199 $ - 0,05 $ = 198,95 $.


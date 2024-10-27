# **Kauf-Offset**

## Zweck: 

- Mit dieser Einstellung können Sie den Kaufpreis durch einen festen Offset anpassen. Der Kauf-Offset wird zum ausgewählten Kaufpreis hinzugefügt (könnte Ask, Bid oder Mark sein. Standard = Ask).

- Der Handel wird zunächst zum im Signal empfangenen Kaufpreis getätigt. Wenn er nicht innerhalb von 5 Sekunden ausgeführt wird, wird bei einem erneuten Versuch zum Kaufpreis (könnte Ask, Bid oder Mark sein. Standard = Ask) plus Offset (Standard ist 0,05) gekauft. 

## Beispiel:

- Kaufsignal 100 $ mit Bid bei 99 $ und Ask bei 101 $. Wenn die anfängliche Limit-Order für den Kauf bei 100 $ nicht ausgeführt wird, erfolgt ein erneuter Versuch bei 101 $ + 0,05 = 101,05 $.

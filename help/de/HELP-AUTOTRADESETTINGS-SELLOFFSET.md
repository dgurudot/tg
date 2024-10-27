# **Verkaufsoffset**

## Zweck: 

- Mit dieser Einstellung können Sie den Verkaufspreis durch einen festen Offset anpassen. 
- Der Verkaufsoffset wird vom ausgewählten Verkaufspreis abgezogen (könnte Ask, Bid oder Mark sein. Standard = Bid).

- Der Handel wird zunächst zum im Signal empfangenen Verkaufspreis getätigt. 
- Wenn er nicht innerhalb von 5 Sekunden ausgeführt wird, wird bei einem erneuten Versuch zum Verkaufspreis (könnte Ask, Bid oder Mark sein. Standard = Bid) abzüglich Offset (Standard ist 0,05) verkauft. 

## Beispiel:

- Verkaufssignal 200 $ mit Bid bei 199 $ und Ask bei 201 $. 
- Wenn die anfängliche Limitorder für den Verkauf bei 200 $ nicht ausgeführt wird, erfolgt ein erneuter Versuch bei 199 $ - 0,05 = 198,95 $

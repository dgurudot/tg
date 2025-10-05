# **Kauf-Offset**

## Zweck:

– Mit dieser Einstellung können Sie den Kaufpreis um einen festen Offset anpassen. Der Kauf-Offset wird zum gewählten Kaufpreis (Ask, Bid oder Mark, Standard: Ask) addiert.

– Der Handel wird zunächst zum im Signal empfangenen Kaufpreis platziert. Wird er nicht innerhalb von 5 Sekunden ausgeführt, erfolgt ein erneuter Kaufversuch zum Kaufpreis (Ask, Bid oder Mark, Standard: Ask) zuzüglich Offset (Standard: 0,05).

## Beispiel:

– Kaufsignal 100 $ mit Bid 99 $ und Ask 101 $. Wird die anfängliche Limit-Order für den Kauf bei 100 $ nicht ausgeführt, erfolgt ein erneuter Kaufversuch bei 101 $ + 0,05 = 101,05 $.

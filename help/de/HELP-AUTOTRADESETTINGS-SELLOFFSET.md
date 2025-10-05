# **Verkaufs-Offset**

## Zweck:

– Mit dieser Einstellung können Sie den Verkaufspreis um einen festen Offset anpassen.
– Der Verkaufs-Offset wird vom gewählten Verkaufspreis (Brief, Geld oder Marke, Standard = Geld) abgezogen.

– Der Handel wird zunächst zum im Signal empfangenen Verkaufspreis platziert.
– Wird der Verkauf nicht innerhalb von 5 Sekunden ausgeführt, erfolgt ein erneuter Versuch zum Verkaufspreis (Brief, Geld oder Marke, Standard = Geld) abzüglich Offset (Standard: 0,05).

## Beispiel:

– Verkaufssignal 200 $ mit Geldkurs 199 $ und Briefkurs 201 $.
– Wird die anfängliche Limit-Order für den Verkauf bei 200 $ nicht ausgeführt, erfolgt ein erneuter Versuch bei 199 $ – 0,05 $ = 198,95 $.

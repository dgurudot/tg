# **Anzahl der Wiederholungsversuche**

## Zweck: 

- Mit dieser Einstellung können Sie die Anzahl der Wiederholungsversuche anpassen, die wir mit einem Offset für Limit-Orders unternehmen, bevor wir die endgültige Marktorder platzieren.

## Beispiel:

- Wenn Ihre Wiederholungsanzahl 1 beträgt, versucht Signal zunächst, die Order zum im Signal erhaltenen Preis auszuführen. 
- Wenn sie nicht ausgeführt wird, gibt es nur 1 Wiederholungsversuch (basierend auf der Einstellung der Wiederholungsanzahl und kann geändert werden) und es wird der Briefkurs plus Offset für das Kaufsignal oder der Geldkurs minus Offset für das Verkaufssignal verwendet. 
- Sobald die Wiederholungsversuche erschöpft sind, wird die Marktorder platziert.

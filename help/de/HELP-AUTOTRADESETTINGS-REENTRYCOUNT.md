# **Anzahl der Wiederholungsversuche**

## Zweck:

– Mit dieser Einstellung können Sie die Anzahl der Wiederholungsversuche für Limit-Orders mit Offset festlegen, bevor eine Marktorder platziert wird.

## Beispiel:

– Wenn die Wiederholungsanzahl 1 beträgt, versucht das Signal zunächst, die Order zum im Signal erhaltenen Preis auszuführen.
– Wird die Order nicht ausgeführt, erfolgt nur ein Wiederholungsversuch (basierend auf der Einstellung für die Wiederholungsanzahl, die geändert werden kann). Dabei wird der Briefkurs plus Offset für Kauf- bzw. der Geldkurs minus Offset für Verkaufs-Signal verwendet.
– Sobald alle Wiederholungsversuche abgeschlossen sind, wird eine Marktorder platziert.

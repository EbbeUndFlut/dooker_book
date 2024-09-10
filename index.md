# Wie geht Docker?
## Inhalt
 1. [Am Anfang war die Virtuelle Maschine](#am-anfang-war-die-virtuelle-maschine)

 ## Am Anfang war die Virtuelle Maschine
 Wer über Docker redet, der redet über virtuelle Maschinen. Wenn etwas virtuell ist dann gibt es das nicht in echt, also zum anfassen.
Ein virtueller Computer existiert nur auf einen echten physischen Computer. Das heißt ich habe einen Computer in meinen Computer und davon kann ich
,theoretisch, unendlich viele haben.

Der Computer der physisch existiert und auf dem dann die virtuellen Computer laufen, wird *Host System* genannt. Auf dem Host System läuft dann die *virtualisierungs Software*. Diese ermöglicht uns das erstellen und betreiben von virtuellen Maschinen.

### Aber warum das Ganze?
Die Virtualisierung hat viele Vorteile, lasst uns mal schauen welche das sind:
![docker logo](images/Docker-Logo.png "Das Docker Logo")
# Wie geht Docker?
## Inhalt
 1. [Am Anfang war die Virtuelle Maschine](#am-anfang-war-die-virtuelle-maschine)


## Am Anfang war die Virtuelle Maschine

Wer über Docker redet, der redet über virtuelle Maschinen. Wenn etwas virtuell ist dann gibt es das nicht in echt, also zum anfassen.
Ein virtueller Computer existiert nur auf einen echten physischen Computer. Das heißt ich habe einen Computer in meinem Computer und davon kann ich
,theoretisch, unendlich viele haben.

Der Computer der physisch existiert und auf dem dann die virtuellen Computer laufen, wird *Host System* genannt. Auf dem Host System läuft dann die *virtualisierungs Software*. Diese ermöglicht uns das erstellen und betreiben von virtuellen Maschinen.

### Aber warum das Ganze?
Die Virtualisierung hat viele Vorteile, lass uns mal schauen welche das sind:
- **Isolation und Sicherheit:**  
Virtuelle Maschinen laufen in einer, vom Hostsytem, isolierten Umgebung. Das bedeutet das Probleme einer Virtuellen Maschine, normalerweise, keine Auswirkungen auf andere virtuelle Maschinen oder das Hostsystem haben.
- **Flexibilität und Skalierbarkeit:**  
Wir können Ressourcen wie RAM, CPU und Speicher dynamisch anpassen. Das ermöglicht eine Skalierung nach Bedarf
- **Ressourceneffizienz:**  
Wenn wir mehere virtuelle Maschinen auf einem Host betreiben, spart das natürlich Kosten an Hardware und Energie.
- **Portabilität:**  
Eine virtuelle Maschine ist eigentlich nichts mehr als eine Datei auf dem Host. Dateien können kopiert und verschoben werden oder als Backup gesichert werden. Wir können die virtuelle Maschine auf jeden Host starten, solange dieser die selbe Software zur virtualisierung nutzt.

Nachteile gibt es aber natürlich auch:

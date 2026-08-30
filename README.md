# Universal Monitor Avatar – tägliche Asset-Sets

Dieses Repository enthält eigenständige thematische Asset-Sets für den Universal Monitor Avatar.

## Verbindliche Struktur pro Set

```text
Assets/
├─ Avatar/
│  ├─ Idle.png
│  └─ Actions.png
├─ MonitorScene/
│  └─ MonitorScene.png
├─ Klingel/
│  └─ MonitorBell.png
└─ Sprüche/
   └─ Abschiedsspruch.json
```

Weitere Sets werden fortlaufend als `Assets 1`, `Assets 2`, `Assets 3`, … angelegt. Bestehende Sets dürfen niemals überschrieben werden.

## Inhalt eines Sets

Jedes Set verwendet genau ein neues universelles Kundenthema, zum Beispiel Fitnessstudio, Hotel, Gastronomie, Einzelhandel, Werkstatt, Schule, Bibliothek, Büro, Wellness, Friseur, Fahrradstudio oder IT-Service.

Die vier PNG-Dateien und der Abschiedsspruch müssen visuell und inhaltlich zum selben Thema passen. Der Avatar bleibt als wiedererkennbare Universal-Monitor-Figur konsistent; nur Kleidung, Requisiten, Aktionen und Szene ändern sich passend zum Thema.

## Laufregel für Actions.png

Die App spiegelt die Figur beim Zurücklaufen selbst. Deshalb müssen Idle, Gehen 1, Gehen 2 und Rennen in der oberen Reihe des Sprite-Sheets alle in dieselbe Grundrichtung nach rechts schauen. Kein Geh-Frame darf bereits nach links gespiegelt sein.

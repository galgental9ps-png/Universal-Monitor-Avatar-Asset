# Universal Monitor Avatar – tägliche Asset-Sets

Dieses Repository enthält eigenständige thematische Asset-Sets für den **Universal Monitor Avatar**.

## Verbindlicher Stammordner

Alle Asset-Sets liegen ausschließlich unter:

```text
src/
└─ UniversalMonitorAvatar/
```

`src/BeamtenMonitorAvatar/Assets` aus `galgental9ps-png/VerwaltungsQuestBayern` dient ausschließlich als technische und visuelle Referenz für Größen, Transparenz, Sprite-Raster, Figurproportionen, MonitorScene-Komposition und Klingelaufbau. Der Zielpfad dieses Repositories heißt immer `src/UniversalMonitorAvatar/`.

## Verbindliche Struktur

```text
src/
└─ UniversalMonitorAvatar/
   ├─ Assets/
   │  ├─ Avatar/
   │  │  ├─ Idle.png
   │  │  └─ Actions.png
   │  ├─ MonitorScene/
   │  │  └─ MonitorScene.png
   │  ├─ Klingel/
   │  │  └─ MonitorBell.png
   │  └─ Sprüche/
   │     ├─ Abschiedsspruch.json
   │     └─ Fallback.json
   │
   ├─ Assets 1/
   │  ├─ Avatar/
   │  │  ├─ Idle.png
   │  │  └─ Actions.png
   │  ├─ MonitorScene/
   │  │  └─ MonitorScene.png
   │  ├─ Klingel/
   │  │  └─ MonitorBell.png
   │  └─ Sprüche/
   │     └─ Abschiedsspruch.json
   │
   ├─ Assets 2/
   ├─ Assets 3/
   └─ Assets 4/
```

Weitere Sets werden fortlaufend als `Assets 1`, `Assets 2`, `Assets 3`, … angelegt. Bestehende Sets dürfen niemals überschrieben werden.

## Inhalt

Jedes Set verwendet genau ein universelles Kundenthema, z. B. Fitnessstudio, Hotel, Gastronomie, Einzelhandel, Werkstatt, Schule, Bibliothek, Büro, Wellness, Friseur, Fahrradstudio oder IT-Service.

Die vier PNG-Dateien und der Abschiedsspruch müssen visuell und inhaltlich zum selben Thema passen. Der Avatar bleibt wiedererkennbar und seriös. Für den aktuellen Grundstil: kurze braune Haare, kein Bart, keine Mütze, keine roten Haare.

## Actions.png

Die App spiegelt die Figur beim Zurücklaufen selbst. Deshalb müssen Idle, Gehen 1, Gehen 2 und Rennen in der oberen Reihe alle in dieselbe Grundrichtung nach rechts schauen. Kein Geh-Frame darf bereits nach links gespiegelt sein.

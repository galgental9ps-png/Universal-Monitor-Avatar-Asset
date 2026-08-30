# Universal Monitor Avatar – Asset-Packs

Dieses Repository enthält thematische Asset-Sets für den Universal Monitor Avatar.

## Struktur

Die Asset-Sets liegen direkt unter `src/UniversalMonitorAvatar/` als Geschwisterordner:

- `Assets`
- `Assets 1`
- `Assets 2`
- `Assets 3`
- usw.

Jedes Set enthält:

```text
Avatar/
  Idle.png
  Actions.png
MonitorScene/
  MonitorScene.png
Klingel/
  MonitorBell.png
Sprüche/
  Abschiedsspruch.json
```

Nur das Basis-Set `Assets` enthält zusätzlich `Sprüche/Fallback.json`.

Die App verwendet `AssetsRootPath = .../src/UniversalMonitorAvatar` und erkennt bei aktivem `UseRandomAssetSet` alle direkten Unterordner, deren Name mit `Assets` beginnt.

Technische und visuelle Referenz für Größen, Sprite-Raster und Szenenaufbau ist `galgental9ps-png/VerwaltungsQuestBayern/src/BeamtenMonitorAvatar/Assets`. Das Beamten-Thema selbst wird nicht übernommen.

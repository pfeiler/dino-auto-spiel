# 🦖 Dino-Auto-Abenteuer 🚒

Ein kindgerechtes Auto-Spiel für Tablet (Touch) und Browser – einfach `index.html` öffnen oder online spielen:
**https://pfeiler.github.io/dino-auto-spiel/**

## So wird gespielt
- **Gas ▶** halten zum Fahren, **Bremse ◀** zum Bremsen/Zurückrollen, **Springen ⤒** über Hindernisse
- **Wasser 💧** halten (oder einfach **aufs Feuer tippen**), um Feuer zu löschen – Wasser ist unbegrenzt
- 4 Fahrzeuge: Monstertruck, Feuerwehr (Super-Wasserkanone), Rennauto, Traktor
- Pro Level 3 Herzen ❤️❤️❤️ – Unfälle setzen zum letzten Checkpoint zurück, nach dem 3. Unfall ist die Fahrt vorbei
- 🎵 Musik oben rechts an/aus – jede Welt hat ihre eigene Melodie

## 5 Welten · 25 Level · 5 Endgegner
| Welt | Besonderheiten | Endgegner (Level 5) |
|---|---|---|
| 🌋 1 Abenteuer-Land | Wiese, Wald, Wüste, Abend-Stadt, Vulkan | 🐉 Feuer-Drache |
| ❄️ 2 Eiswelt | Rutschige Stellen, gefrorener See, Eisblöcke, Schneemänner, Eiszapfen, Pinguine | ❄️ Eis-Yeti |
| 🦍 3 Dschungelwelt | Matsch, Flüsse, Baumstämme, Schlangen, Affen, Lianen | 🦍 Matsch-Gorilla |
| 🧪 4 Chemiewelt | Säurepfützen (drüberspringen!), Kolben, Fässer, Rohre, Förderbänder | 🧪 Professor Schleim |
| ⚡ 5 Elektrowelt | Laser-Tore (warten bis AUS!), Elektrozäune, Tesla-Spulen, Batterien | ⚡ Blitz-Robo |

Jeder Endgegner wird mit **Wasser 💧** besiegt.

## Neue Welten freischalten
Die nächste Welt öffnet sich, sobald du in der Welt davor **90 % der Höchstpunkte** erreichst
(in einer Fahrt durch alle 5 Level):

| Welt | Höchstpunkte | 90 % nötig für die nächste Welt |
|---|---|---|
| 1 Abenteuer-Land | 18.500 | 16.650 |
| 2 Eiswelt | 21.400 | 19.260 |
| 3 Dschungelwelt | 23.100 | 20.790 |
| 4 Chemiewelt | 24.000 | 21.600 |
| 5 Elektrowelt | 25.000 | – |

Die Höchstpunkte entsprechen einer fehlerfreien, schnellen Fahrt (alle Hindernisse, alle Feuer gelöscht, Boss besiegt, kein Unfall).
Mit einem kleinen Fehler und etwas Zögern schafft man die 90 % trotzdem. Bestwerte je Welt werden im Browser gespeichert.

## Punkte
Strecke, geschaffte Hindernisse (+50), Sprünge (je länger in der Luft, desto mehr), gelöschte Feuer (+100),
Level-Bonus, Zeit-Bonus, „Ohne Unfall“-Bonus (+300) und Endgegner besiegt (+3.000). Ein Unfall kostet 50 Punkte.

## Bestenliste
Top 10 je Welt (Name, Punkte, Level, Fahrzeug, Datum), gespeichert im Browser (localStorage).

Tastatur (PC): Pfeiltasten / Leertaste, Wasser mit **X** oder **F**.

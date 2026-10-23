# 🦖 Dino-Auto-Abenteuer 🚒

Ein kindgerechtes Auto-Spiel für Tablet (Touch) und Browser – einfach `index.html` öffnen oder online spielen:
**https://pfeiler.github.io/dino-auto-spiel/**

## So wird gespielt
- **Gas ▶** halten zum Fahren, **Bremse ◀** zum Bremsen/Zurückrollen, **Springen ⤒** über Hindernisse
- **Saltos 🤸:** Rampen schleudern dich hoch in die Luft (gut 1 Sekunde). **In der Luft ⤒ Springen gedrückt halten** = Salto rückwärts, loslassen = der Dino richtet sich wieder aus.
  Ganze Drehung + saubere Landung (bis ca. ±28°) = **SUPER-SALTO +400**, zwei Drehungen = **DOPPEL-SALTO +550**. Schiefe Landung = lustige Wackel-Landung (kein Unfall, nur kein Bonus).
- **Wasser 💧** halten (oder einfach **aufs Feuer tippen**), um Feuer zu löschen – Wasser ist unbegrenzt
- 4 Fahrzeuge: Monstertruck, Feuerwehr (Super-Wasserkanone), Rennauto, Traktor
- Pro Level 3 Herzen ❤️❤️❤️ – Unfälle setzen zum letzten Checkpoint zurück, nach dem 3. Unfall ist die Fahrt vorbei
- **🔒 Gitter-Tore:** Ein Tor versperrt die Strecke – das Auto stößt nur sanft dagegen (kein Unfall, kein Herz weg). Ein **Rädchen ⚙️ in derselben Farbe** steht 300 px davor (mit Kette zum Tor):
  **Wasser drauf spritzen** → das Tor fährt hoch und bleibt offen. Wer früh zielt, kann sogar ohne Anhalten durchfahren.
- **❤️ Herz-Käfige:** Über der Strecke hängt ein Herz im Käfig, davor ein **Wasserrad**. Es braucht ca. 1,5–2 Sekunden Wasser – im Vorbeirasen reicht es nicht, also **langsamer fahren oder kurz anhalten**.
  Dann geht der Käfig auf, das Herz fällt herunter – einfach **drunter fahren** und fangen (großzügig). Verpasste Herzen liegen noch ein paar Sekunden auf der Strecke und verblassen dann.
  Ein gefangenes Herz gibt **+1 Leben** (höchstens 3) – sind schon alle 3 Herzen voll, gibt es stattdessen den **Herz-Bonus**.
- Geöffnete Tore und Käfige sind kleine Zwischenstopps: nach einem Unfall geht es direkt dahinter weiter.
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

Gitter-Tore und Herz-Käfige pro Level (Level 1–5; nie in der Boss-Arena, nie auf Feuern, Hindernissen, Rampen/Landezonen, Checkpoints, Laser- oder Rutsch-/Matsch-Zonen):

| Welt | 🔒 Tore | ❤️ Käfige |
|---|---|---|
| 1 | 0 / 0 / 1 / 1 / 0 (2) | 0 / 1 / 1 / 1 / 1 (4) |
| 2 | 0 / 1 / 1 / 1 / 0 (3) | 1 / 1 / 0 / 1 / 1 (4) |
| 3 | 0 / 1 / 1 / 2 / 0 (4) | 1 / 0 / 1 / 1 / 1 (4) |
| 4 | 1 / 1 / 1 / 2 / 0 (5) | 1 / 1 / 0 / 1 / 1 (4) |
| 5 | 1 / 1 / 2 / 2 / 0 (6) | 1 / 0 / 1 / 1 / 1 (4) |

Im Boss-Level liegt der Käfig vor der Arena. Die Level sind dafür etwas länger geworden.

## ⭐ Sterne & Level-Karte
Jedes der 25 Level hat **3 Sterne**:
1. ⭐ **Ziel erreicht**
2. ⭐ **Schnell:** alle Feuer gelöscht (im Boss-Level: Endgegner besiegt) und im **Zeit-Ziel** angekommen (die Zeit steht auf dem Stern; es ist dieselbe Zeit wie beim Zeit-Bonus).
   Für jedes Gitter-Tor gibt es 3 s und für jeden Herz-Käfig 4 s extra Zeit (Anhalten und Spritzen ist also kein Nachteil).
   Weil man ein brennendes Feuer nicht überholen kann, ist „alle Feuer gelöscht“ beim Ziel immer erfüllt – darum zählt hier zusätzlich die Zeit.
3. ⭐ **Ohne Unfall** (auch kein Treffer vom Endgegner)

Die besten Sterne und Punkte je Level werden gespeichert. Auf der **Level-Karte** jeder Welt kann man jedes schon erreichte Level nochmal spielen.

## Neue Welten freischalten
Die nächste Welt öffnet sich, sobald du in der Welt davor **90 % der Höchstpunkte** (in einer Fahrt) **oder 10 von 15 ⭐** schaffst:

| Welt | Höchstpunkte | 90 % nötig für die nächste Welt | oder |
|---|---|---|---|
| 1 Abenteuer-Land | 46.400 | 41.760 | 10 ⭐ in Welt 1 |
| 2 Eiswelt | 33.800 | 30.420 | 10 ⭐ in Welt 2 |
| 3 Dschungelwelt | 35.100 | 31.590 | 10 ⭐ in Welt 3 |
| 4 Chemiewelt | 37.100 | 33.390 | 10 ⭐ in Welt 4 |
| 5 Elektrowelt | 37.700 | – | – |

Die Höchstpunkte entsprechen einer fehlerfreien, schnellen Fahrt (alle Hindernisse, alle Feuer gelöscht, alle Tore und Käfige geöffnet, alle Herzen gefangen, Boss besiegt, kein Unfall, Doppel-Salto über jede Rampe).
Mit sauberen einfachen Saltos, etwas Zögern und einem Unfall schafft man die 90 % trotzdem – und die 10 Sterne gehen ganz ohne Saltos.
Eine einmal freigeschaltete Welt bleibt freigeschaltet (auch wer die früheren, niedrigeren Ziele geschafft hat – zuletzt 38.790 / 27.270 / 27.900 / 29.700 –, behält seine Welten).

## 🎨 Dino-Werkstatt
Nur zum Anschauen – keine Extra-Kräfte. Wird automatisch freigeschaltet:

| Hüte & Brillen | freigeschaltet durch | Lackierungen | freigeschaltet durch |
|---|---|---|---|
| 🧢 Basecap | immer | 🎨 Original | immer |
| 🥳 Partyhut | 3 ⭐ | 🔥 Flammen | 5 ⭐ |
| 🕶️ Sonnenbrille | 8 ⭐ | 🚓 Polizei (mit Blaulicht) | 12 ⭐ |
| ⛑️ Feuerwehrhelm | Feuer-Drache besiegt | 🌌 Sternenhimmel | erster SUPER-SALTO |
| 🛡️ Wikingerhelm | Eis-Yeti besiegt | 🌈 Regenbogen | 20 ⭐ |
| 🤠 Cowboyhut | Matsch-Gorilla besiegt | 💡 Neon | 30 ⭐ |
| 🧙 Zauberhut | Professor Schleim besiegt | 🏆 Gold | 45 ⭐ |
| 👑 Krone | Blitz-Robo besiegt | | |

Die Auswahl wird gespeichert und in allen Leveln gezeigt.

## Punkte
Strecke, geschaffte Hindernisse (+50), Sprünge (je länger in der Luft, desto mehr), Saltos (+400 / +550), gelöschte Feuer (+100), Gitter-Tor geöffnet (+100), Herz-Käfig geöffnet (+150), Herz gefangen (+250 – egal ob als Extra-Leben oder als Herz-Bonus bei vollen Herzen),
Level-Bonus, Zeit-Bonus, „Ohne Unfall“-Bonus (+300) und Endgegner besiegt (+3.000). Ein Unfall kostet 50 Punkte.

## Bestenliste
Top 10 je Welt (Name, Punkte, Level, Fahrzeug, Datum), gespeichert im Browser (localStorage).

Tastatur (PC): Pfeiltasten / Leertaste, Wasser mit **X** oder **F**.

## ⚙️ Einstellungen
Im Hauptmenü unter **⚙️ Einstellungen**: Musik an/aus (wie der 🎵-Knopf im Spiel) und **🗑 Alles zurücksetzen**.
Zurücksetzen fragt zweimal nach („Wirklich alles löschen? …“ → „Ganz sicher?“, der Ja-Knopf ist dabei kurz gesperrt und wechselt die Seite), damit es nicht aus Versehen passiert.
Gelöscht werden: Sterne, Level-Bestwerte, Level-Karte, Welt-Freischaltungen (nur Welt 1 bleibt offen), Endgegner-Siege, Werkstatt-Sachen und -Auswahl, Salto-/Tor-/Herz-Hinweise und alle Bestenlisten.
Erhalten bleiben: die Musik-Einstellung und der zuletzt eingetippte Name. Danach schaltet keine alte Umstellung (Migration) wieder etwas frei.

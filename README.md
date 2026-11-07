# Magic Football Sisters

Fußball-Quiz als Jump'n'Run – läuft direkt im Browser, am PC und auf dem Smartphone (Querformat, bildschirmfüllend).
Ein Ableger von *Magic Math Sisters*: gleiche Spielmechanik, aber Fußballfragen statt Mathematik.

## Dateien

| Datei | Inhalt |
|---|---|
| `index.html` | das komplette Spiel |
| `fragen/fussball.md` | Hauptkatalog (3 × 200 Fragen) |
| `fragen/robo.md` | schwerere Fragen für den Robo-Bonus (3 × 40) |
| `fragen/finale.md` | die schwersten Fragen für das Finale (3 × 27) |
| `README.md` | diese Anleitung |

## Die drei Welten

| Welt | Thema | Schwierigkeit | Level | Endgegner |
|---|---|---|---|---|
| 1 | Bundesliga | leichter | Bolzplatz-Wiese · Kabinen-Höhle · Burg der Meisterschale | Ballkönig |
| 2 | Europapokal (Champions League, Europa League, Conference League, EM, Nations League) | mittel | Dünen der Europa League · Oase der Conference League · Pyramide des Henkelpotts | Torwart-Skarabäus |
| 3 | Weltmeisterschaften | schwerer | Wolken-Arena · Vulkan-Stadion · Festung des Weltpokals | Pokaldrache |

## So funktionieren die Fragen

* **Fragekisten** (orange, mit Ball) von unten anstoßen → Frage. Jede Kiste hat einen Versuch.
  Richtig = grün und ein Bonus, je drei richtige Antworten = Frosch-Maskottchen mit Extraleben. Falsch = rot, sonst keine Folgen.
* **Bei jedem Start einer Welt – also auch nach jedem Game Over – werden 15 neue Fragen gezogen.**
  Bevorzugt werden Fragen, die noch nicht dran waren; erst wenn alle Fragen einer Welt gestellt wurden, beginnt die Auswahl von vorn.
* Die **Endgegner** stellen Fragen aus dem übrigen Katalog der Welt, innerhalb eines Versuchs ohne Wiederholung.
* Sind alle 15 Fragekisten einer Welt grün, wird der **Robo-Bonus** dieser Welt freigeschaltet (bleibt dauerhaft erhalten).

## Robo-Bonus (3 Spiele à 3 Stages)

Spielmechanik wie Mega Man auf dem Game Boy, Optik im Stil von Mega Man X – Helga und Emmy in Robo-Rüstung.

* B schießt (bis zu drei Schüsse), B halten = Ladeschuss, A springt (kurz drücken = kleiner Sprung).
* **Blinkende Steine** zerschießen → Frage aus `fragen/robo.md` (Welt 1 Bundesliga, Welt 2 Europapokal/EM, Welt 3 WM).
* Je **drei richtige Antworten** in Folge gibt es einen **Energy Container**; im Pausenmenü (START) füllt er mit A die Energie wieder auf.
* Am Ende jeder Stage wartet ein Robo-Meister mit eigenem Energiebalken.
* Freigeschaltete Robo-Spiele sind jederzeit über die Welt-Auswahl (Karte „ROBO“) erreichbar.

### Spezialwaffen im Robo-Bonus

Wie bei Mega Man überlässt jeder besiegte Robo-Meister seine Waffe – sie bleibt für alle Robo-Spiele erhalten:

| Besiegt | Waffe | Wirkung | Schwachstelle von |
|---|---|---|---|
| Torwart-Robo | Fallrückzieher | Ball im hohen Bogen | Schiri-Robo |
| Schiri-Robo | Pfiff-Welle | Schallwelle, geht durch Gegner | Pokal-Robo |
| Pokal-Robo | Pokal-Komet | drei goldene Kugeln im Fächer | Torwart-Robo |

* **SCHWESTER-Taste** (E) schaltet die Waffe um, ein zweiter Balken zeigt ihre Energie; sie füllt sich zu jeder Stage wieder auf.
* Ein Treffer mit der passenden Waffe zieht dem Robo-Meister viermal so viel Energie ab.
* **Energy Container**: im Pausenmenü (START) mit A benutzen.

## Finale (3 Level)

Sind **alle drei Robo-Spiele mit allen Fragen richtig** gelöst, erscheint die Karte „FINALE“: ein Side-Scrolling-Shooter im Stil von Parodius.

* Steuerkreuz fliegt, B feuert (halten = Dauerfeuer).
* **Rote Power-Kapseln abschießen** → Frage aus `fragen/finale.md`. Richtig = nächste Fähigkeit:
  SPEED → RAKETE → DOPPEL → LASER → OPTION → SCHILD.
* Level 1 Bundesliga-Himmel, Level 2 Europapokal-Nacht, Level 3 WM-Weltraum – jeweils mit Endgegner.
* **Nur Fragen:** Lernpfad mit drei Lektionen à fünf Fragen und einem Abschlusstest, ebenfalls mit neu gezogenen Fragen.

## Schwierigkeit

Im Titelbild unter „SCHWIERIGKEIT“ (mit ◀ ▶ oder A umschalten):

| Stufe | Fragekisten | Endgegner | Falsche Antwort |
|---|---|---|---|
| **Einfach** | richtig beantwortete Kisten bleiben grün – auch nach Game Over – und werden nicht nochmal gefragt | Fragen aus den bereits beantworteten Fragen der Welt | zweiter Versuch |
| **Mittel** | nach jedem Game Over 15 neue Fragen | Fragen aus dem übrigen Katalog | zweiter Versuch |
| **Schwer** | nach jedem Game Over 15 neue Fragen | Fragen aus dem übrigen Katalog | kein zweiter Versuch |

Der zweite Versuch gilt auch im Robo-Bonus und im Finale. Ist eine Welt geschafft, beginnt sie im einfachen Modus beim nächsten Mal wieder frisch.

## Spielstand zurücksetzen

Im Titelbild unter „SPIELSTAND ZURÜCKSETZEN“ gibt es zwei Möglichkeiten:

* **Nur Fragen neu mischen:** Das Spiel vergisst, welche Fragen schon gestellt wurden, und zieht für jede Welt eine neue Auswahl.
  Fortschritt, Sterne sowie Robo-Bonus- und Finale-Freischaltungen bleiben erhalten.
* **Alles zurücksetzen:** Löscht zusätzlich Fortschritt, Sterne und alle Freischaltungen.

## Fragen ändern oder ergänzen

`fragen/fussball.md` ist eine normale Markdown-Datei (auf GitHub: Datei öffnen → Stift-Symbol).

```markdown
## Welt 1 – Bundesliga

### Grundwissen
Wie viele Mannschaften spielen in der Bundesliga?

- [ ] 16
- [x] 18
- [ ] 20
- [ ] 22

> Seit 1965/66 spielen 18 Vereine in der Bundesliga.
```

Die richtige Antwort wird mit `[x]` markiert; die Antworten werden im Spiel gemischt. Pro Welt sind beliebig viele Fragen möglich.
Die Fakten entsprechen dem Stand Sommer 2025.

## Steuerung

| | Tastatur | Smartphone |
|---|---|---|
| Laufen | ← → | Steuerkreuz |
| Ducken | ↓ | Steuerkreuz unten |
| Springen / Fliegen | Leertaste oder ↑ | A |
| Rennen, Schuss | Shift oder X | B |
| Schwester wechseln | E | SCHWESTER |
| Pause-Menü | Enter | START |
| Musik / Effekte | M / N | im Pause-Menü |

Helga (Nr. 9, rot) läuft schneller und schießt mit dem Goldenen Schuh Fußbälle. Emmy (Nr. 10, grün) springt höher und kann mit dem Goldenen Schuh fliegen.

## Online stellen

Dateien ins Hauptverzeichnis eines GitHub-Repositorys legen und unter **Settings → Pages → Deploy from a branch → main / (root)** aktivieren.
Lokal geöffnet nutzt `index.html` eine eingebaute Kopie der Fragen.

Musik: ausschließlich Tschaikowskys Nussknacker-Suite (Marsch, Tanz der Zuckerfee, Chinesischer Tanz), als Chiptune arrangiert. Alle Grafiken sind eigene Pixelart.

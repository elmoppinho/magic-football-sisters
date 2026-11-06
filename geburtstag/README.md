# Happy Birthday Toni

Geburtstagsfassung von *Magic Football Sisters* – ein Quiz-Jump'n'Run im Browser (PC und Smartphone, Querformat).

## Was ist anders?

* Titelbild: **„Happy Birthday Toni“**.
* Die beiden Helden heißen **Lance** (Gelbes Trikot, läuft schneller) und **Joseba** (Bergtrikot, springt höher) –
  beide in Radtrikot mit Helm, Sonnenbrille, Radhose und Radschuhen.
* **Welt 2 ist die Tour de France:** Provence mit Lavendelfeldern, Anstieg nach Alpe d'Huez, Zielankunft in Paris –
  mit Tour-Fragen im Hauptspiel, im Robo-Bonus und im Finale.
* Welt 1 (Bundesliga) und Welt 3 (Weltmeisterschaften) bleiben Fußball.

## Dateien

| Datei | Inhalt |
|---|---|
| `index.html` | das komplette Spiel |
| `fragen/fussball.md` | Hauptkatalog: Bundesliga · Tour de France · WM |
| `fragen/robo.md` | schwerere Fragen für den Robo-Bonus |
| `fragen/finale.md` | die schwersten Fragen für das Finale |

Fragen lassen sich direkt auf GitHub bearbeiten (Datei öffnen → Stift-Symbol → Commit changes).

## Schwierigkeit

Im Titelbild unter „SCHWIERIGKEIT“ (mit ◀ ▶ oder A umschalten):

| Stufe | Fragekisten | Endgegner | Falsche Antwort |
|---|---|---|---|
| **Einfach** | richtig beantwortete Kisten bleiben grün – auch nach Game Over – und werden nicht nochmal gefragt | Fragen aus den bereits beantworteten Fragen der Welt | zweiter Versuch |
| **Mittel** | nach jedem Game Over 15 neue Fragen | Fragen aus dem übrigen Katalog | zweiter Versuch |
| **Schwer** | nach jedem Game Over 15 neue Fragen | Fragen aus dem übrigen Katalog | kein zweiter Versuch |

Der zweite Versuch gilt auch im Robo-Bonus und im Finale. Ist eine Welt geschafft, beginnt sie im einfachen Modus beim nächsten Mal wieder frisch.

## Spielablauf

* 15 Fragekisten pro Welt, nach jedem Game Over 15 neue Fragen.
* Alle 15 Kisten einer Welt grün → **Robo-Bonus** (Mega-Man-Stil): blinkende Steine zerschießen = Frage, je drei richtige Antworten = Energy Container.
* Alle drei Robo-Spiele mit allen Fragen richtig → **Finale** (Shooter im Parodius-Stil): Power-Kapseln abschießen = Frage, richtig = neue Fähigkeit.
* Musik: Tschaikowskys Nussknacker-Suite als Chiptune.

Die Spielstände sind von den anderen Fassungen getrennt.

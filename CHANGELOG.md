# POE2 Werkbank – Änderungsprotokoll / Changelog

Jeder Abschnitt unten ist so aufgebaut, dass du ihn 1:1 als Beschreibung einer GitHub-Release einfügen kannst.
Das Programm und der Discord-Post lesen die Marker `[DE]` und `[EN]`.

---

## Build 203

[DE]
### Neu
- Buildplaner (Windows-App): Neue Karte „Item vergleichen". Item aus dem Spiel kopieren (Strg+Alt+C), einen Platz wählen, einfügen, „Vergleichen": die Werkbank setzt das Item in deinen PoB-Build und zeigt Leben, Mana, Widerstände, effektive Lebenspunkte und Schaden vorher und nachher. Wahlweise mit Full DPS für eine Fertigkeit. Der Text muss auf Englisch sein.

[EN]
### New
- Build planner (Windows app): new “Compare an item” card. Copy an item in the game (Ctrl+Alt+C), choose a slot, paste, “Compare”: the workbench puts the item into your PoB build and shows life, mana, resistances, effective HP and damage before and after. Optionally with Full DPS for one skill. The text has to be in English.

---

## Build 202

[DE]
### Neu
- Buildplaner, Karte „Berechnung (Richtwert)": Automatische Neuberechnung. Nach der ersten Berechnung rechnet die Werkbank bei jeder Änderung im Passivbaum von selbst neu und zeigt, was sich ändert (zum Beispiel „Effektive Lebenspunkte +1.779", grün bei Gewinn, rot bei Verlust). Über dem Passivbaum steht dazu ein Kurzstreifen mit Leben, effektiven Lebenspunkten und Schaden. Abschaltbar in der Karte.
### Verbessert
- Buildplaner: Bei einem eingelesenen PoB-Code fließen Punkte, die du im Passivbaum änderst, jetzt in die Berechnung ein (Ausrüstung und Gems kommen weiter aus dem Code). Bereits gespeicherte Builds einmal neu einlesen.
- Die automatische Neuberechnung ist schnell (etwa 3 Sekunden); die Liste „Schaden je Fertigkeit" bleibt dabei stehen und lässt sich per Knopf neu berechnen.

[EN]
### New
- Build planner, “Calculation (estimate)” card: automatic recalculation. After the first calculation the workbench recalculates by itself whenever you change the passive tree and shows what changed (for example “Effective HP +1,779”, green for a gain, red for a loss). A short strip with life, effective HP and damage sits above the passive tree. Can be switched off in the card.
### Improved
- Build planner: with an imported PoB code, passive points you change in the tree are now included in the calculation (gear and gems still come from the code). Import already saved builds once more.
- The automatic recalculation is quick (about 3 seconds); the “damage per skill” list stays as it was and can be recalculated with a button.

---

## Build 201

[DE]
### Verbessert
- Buildplaner, Karte „Berechnung (Richtwert)": Du kannst jetzt die Hauptfertigkeit wählen, genau wie in Path of Building. Dazu gibt es eine Liste mit dem Schaden jeder einzelnen Fertigkeit, die effektiven Lebenspunkte und, wenn der Build Fertigkeiten für „Full DPS" markiert hat (oder bei einem selbst geplanten Build), den Gesamtschaden. Vorher wurde nur die erste Fertigkeit berechnet. Ein Vergleich mit einem Build von poe.ninja ergab dieselben Werte wie in Path of Building.

[EN]
### Improved
- Build planner, “Calculation (estimate)” card: you can now choose the main skill, just like in Path of Building. There is also a list with the damage of every single skill, the effective hit points and, if the build has skills marked for “Full DPS” (or for a build you planned yourself), the total damage. Before, only the first skill was calculated. A comparison with a build from poe.ninja gave the same values as Path of Building.

---

## Build 200

[DE]
### Neu
- Neues Standard-Design „Schmiede": tiefes Schwarz, Glut-Orange, Creme-Schrift und das goldene Sechseck als Zeichen in der Seitenleiste. Es passt zu den Stream-Overlays. Unter „Tabs & Look" kannst du weiterhin Hell, Dunkel, Automatisch und den bisherigen Spiel-Look wählen.
- Hintergrundbild wählbar (Geschmolzener Fels, Werkstatt mit Kerze, Werkbank mit Runen, Offene Tür oder keines), ebenfalls unter „Tabs & Look".

[EN]
### New
- New default design “Forge”: deep black, ember orange, cream type and the golden hexagon as a mark in the side bar. It matches the stream overlays. Under “Tabs & Look” you can still choose Light, Dark, Automatic and the previous game look.
- Selectable background image (molten rock, workshop with candle, workbench with runes, open door or none), also under “Tabs & Look”.

---

## Build 199

[DE]
### Neu
- Handwerk: Neuer Reiter „Rechner". Trage die Chance pro Versuch und die Kosten pro Versuch ein, auch für mehrere Schritte hintereinander. Du siehst die durchschnittlichen Versuche und Kosten, dazu die Menge, die du mit 50 bis 99 % Sicherheit einplanen solltest, und die Trefferchance bei einer festen Zahl Versuche. Mit geladenen Marktpreisen kommt eine Umrechnung in Göttliche Sphären dazu.

[EN]
### New
- Crafting: new “Calculator” tab. Enter the chance per attempt and the cost per attempt, also for several steps in a row. You see the average attempts and costs, the amount to plan for with 50 to 99% certainty, and the hit chance for a fixed number of attempts. With loaded market prices a conversion into Divine Orbs is added.

---

## Build 198

[DE]
### Neu
- Umrechner: Neuer Reiter unter „Handeln". Rechne eine Menge einer Währung in eine andere um (mit Tauschknopf) und sieh darunter den Verlauf der letzten 7 Tage mit Veränderung in Prozent und Handelsmenge. Grundlage sind die Preise aus dem Tab Marktpreise (Windows-App, Quelle poe.ninja).

[EN]
### New
- Converter: new tab under “Trade”. Convert an amount of one currency into another (with a swap button) and see the last 7 days below, with the change in percent and trade volume. It uses the prices from the Market prices tab (Windows app, source poe.ninja).

---

## Build 197

[DE]
### Neu
- Vermögen: Neuer Reiter unter „Handeln". Füge Gegenstände aus dem Spiel ein (Strg+C, dann Strg+V). Die Werkbank liest Name und Stapelgröße, bewertet alles mit den Marktpreisen und zeigt Gesamtwert in Divine und Exalted. Du kannst Anzahlen ändern, Einträge entfernen, die letzte Eingabe zurücknehmen, einen Stand speichern (mit Verlauf) und die Liste kopieren.
- Windows-App: Mit dem Sammelmodus fügt der Hotkey den Stapel unter der Maus direkt zur Vermögen-Liste hinzu.

[EN]
### New
- Net worth: new tab under “Trade”. Paste items from the game (Ctrl+C, then Ctrl+V). The workbench reads the name and stack size, values everything with the market prices and shows the total in Divine and Exalted. You can change counts, remove entries, undo the last input, save a snapshot (with history) and copy the list.
- Windows app: in collect mode the hotkey adds the stack under the mouse straight to the net worth list.

---

## Build 196

[DE]
### Verbessert
- Item-Prüfer: Das Eingabefeld sitzt jetzt in einer klar erkennbaren Einfüge-Fläche mit Hinweis und Beispiel-Knopf; die Einleitung ist kürzer.
- Buildplaner: Die lange Einleitung ist kürzer, die Hinweise zum Build Planner im Spiel stehen in einem aufklappbaren Abschnitt.

[EN]
### Improved
- Item checker: the input now sits in a clearly visible paste area with a hint and an example button; the introduction is shorter.
- Build planner: the long introduction is shorter; the notes on the in-game Build Planner are in a collapsible section.

---

## Build 195

[DE]
### Neu
- Startseite: Oben steht „Weitermachen" mit deiner zuletzt benutzten Seite, darunter „Zuletzt benutzt" und eine Karte je Bereich mit Schnellzugriff auf alle Seiten.
### Verbessert
- „Tabs & Look": Die Reiter sind nach Bereichen gruppiert (Vorbereiten, Spielen, Handeln, Wissen).

[EN]
### New
- Start page: “Continue” at the top with the page you used last, below it “Recently used” and one card per area with quick access to all pages.
### Improved
- “Tabs & Look”: tabs are grouped by area (Prepare, Play, Trade, Knowledge).

---

## Build 194

[DE]
### Neu
- Neue Navigation: Die 17 Reiter sind jetzt in 5 Bereiche gegliedert: Start, Vorbereiten, Spielen, Handeln und Wissen. Links steht eine schmale Leiste (am Handy oben), innerhalb eines Bereichs wählst du über kleine Reiter die Seite. Die Werkbank merkt sich pro Bereich, wo du zuletzt warst.
### Verbessert
- „Tabs & Look" sitzt jetzt unten in der Seitenleiste. Ausgeblendete Reiter lassen auch leere Bereiche verschwinden.

[EN]
### New
- New navigation: the 17 tabs are now grouped into 5 areas: Start, Prepare, Play, Trade and Knowledge. A slim bar on the left (on top on phones) leads to the area, and small tabs inside an area switch the page. The workbench remembers where you were last in each area.
### Improved
- “Tabs & Look” now sits at the bottom of the side bar. Hidden tabs also make empty areas disappear.

---

## Build 193

[DE]
### Neu
- Buildplaner: Neue Karte „Berechnung (Richtwert)" (nur in der Windows-App). Sie rechnet deinen Plan mit dem Berechnungskern von Path of Building Community (PoE 2, MIT-Lizenz): Passivbaum samt Waffensätzen und Attribut-Punkten, Aszendenz, Skills und Supports. Angezeigt werden Leben, Mana, Energieschild, Wille, Widerstände, Schaden pro Sekunde und eine Liste aller Werte, alles auf Deutsch. Die Rechnung läuft lokal auf deinem Rechner, ohne Internet. Wenn du den Build über „PoB-Code einfügen" geladen hast, rechnet der Kern den Original-Build mit Ausrüstung und Gems (per Schalter auf den bearbeiteten Plan umstellbar). Ohne PoB-Code fehlt die Ausrüstung, dann sind die Werte nur ein Richtwert und Angriffe ohne Waffe zeigen 0 Schaden. Das Programm wird dadurch um etwa 6 MB größer.
### Hinweis
- Der Rechenkern wird beim ersten Klick auf „Jetzt berechnen" entpackt und gestartet, das dauert ein paar Sekunden. Lizenztexte stehen in THIRD-PARTY-LICENSES.txt.
[EN]
### New
- Build planner: new “Calculation (estimate)” card (Windows app only). It calculates your plan with the calculation core of Path of Building Community (PoE 2, MIT licence): passive tree including weapon sets and attribute points, ascendancy, skills and supports. It shows life, mana, energy shield, spirit, resistances, damage per second and a list of all values. The calculation runs locally on your computer, without internet. If you loaded the build via “Paste PoB code”, the core calculates the original build with gear and gems (switchable to the edited plan). Without a PoB code, gear is missing, so the values are only an estimate and attacks without a weapon show 0 damage. The program grows by about 6 MB.
### Note
- The core is unpacked and started on the first click on “Calculate now”, which takes a few seconds. Licence texts are in THIRD-PARTY-LICENSES.txt.

---

## Build 192

[DE]
### Neu
- Statistik: Neuer Reiter „Tagebuch". Starte eine Sitzung mit deiner Farm-Art (Expedition, Delirium, Abgrund, Ritual, Riss, Sonstiges), beende sie mit dem Gewinn und sieh den Gewinn pro Stunde je Farm-Art. Karten und Tode zählt das Programm aus der Client.txt für den Zeitraum der Sitzung. Sitzungen lassen sich auch nachtragen. Gewinn in Exalted rechnet das Tagebuch mit den Kursen aus dem Tab Marktpreise in Divine um.
- Buildplaner: Ein Klick auf einen Attribut-Punkt (+5) öffnet ein Menü mit Stärke, Geschick und Intelligenz, die aktuelle Wahl ist markiert. Ein Klick auf einen belegten Attribut-Punkt öffnet dasselbe Menü, mit „Punkt entfernen" am Ende. Rechtsklick entfernt den Punkt wie bisher.
### Verbessert
- Regex-Generator: Die automatisch gewählten Wortteile beginnen nicht mehr mitten in einer kurzen Wortendung (zum Beispiel „ches veri"). Dafür sind sie im Schnitt etwa ein halbes Zeichen länger. Alle Modifikatoren aller Klassen wurden dagegen geprüft.
- Runenform-Kombinationen: Die Preisschilder erscheinen zuverlässiger. Bei Alt+R und im Automatik-Modus liest das Programm das Buch etwa alle halbe Sekunde neu, höchstens sechs Sekunden lang, bis die Preise stehen. Eine Fehlermeldung erscheint erst nach dem letzten Versuch.
[EN]
### New
- Statistics: new “Diary” tab. Start a session with your farming type (Expedition, Delirium, Abyss, Ritual, Breach, Other), end it with the profit and see the profit per hour for each type. The program counts maps and deaths from Client.txt for the time of the session. Sessions can also be added afterwards. Profit in Exalted is converted to Divine with the rates from the Market prices tab.
- Build planner: clicking an attribute point (+5) opens a menu with Strength, Dexterity and Intelligence, with the current choice marked. Clicking a taken attribute point opens the same menu, with “Remove point” at the end. Right-click still removes the point.
### Improved
- Regex generator: the automatically chosen word fragments no longer start in the middle of a short word ending (for example “ches veri”). In return they are about half a character longer on average. All modifiers of all classes were checked for this.
- Rune form combinations: the price labels appear more reliably. With Alt+R and in automatic mode the program reads the book again about every half second, for six seconds at most, until the prices are shown. An error message only appears after the last attempt.

---

## Build 191

[DE]
### Neu
- Darstellung: Unter „Tabs & Look" gibt es jetzt die Auswahl „Darstellung" mit Automatisch, Hell, Dunkel und dem neuen „Spiel-Look". Der Spiel-Look ist warm und dunkel mit Gold, Zierlinie unter dem Titel und Eckwinkeln an den Kacheln. Alle Symbole und Verzierungen sind selbst gezeichnet. Die Wahl wird gespeichert.
[EN]
### New
- Appearance: under “Tabs & Look” there is now an “Appearance” choice with Automatic, Light, Dark and the new “Game look”. The game look is warm and dark with gold, a divider line under the title and corner marks on the tiles. All symbols and decorations are drawn by us. Your choice is saved.

---

## Build 190

[DE]
### Behoben
- Kampagnenführer: Wenn du nach dem Endgame zurück in die Kampagne gewechselt bist und danach in dein Versteck gehst, zeigt das Fenster wieder „Endgame". Bei einem ganz neuen Charakter (Start in Akt 1) bleibt das Versteck in der Kampagne.
[EN]
### Fixed
- Campaign guide: if you switched back from the endgame to the campaign and then enter your hideout, the window shows “Endgame” again. With a brand new character (starting in Act 1) the hideout stays in the campaign.

---

## Build 189

[DE]
### Behoben
- Kampagnenführer: Nach dem Endgame springt das Fenster jetzt wieder in die Kampagne, sobald du eine Kampagnen-Zone betrittst (zum Beispiel mit einem neuen Charakter). Vorher blieb „Endgame" stehen, bis du das Flussufer in Akt 1 betreten hast.
[EN]
### Fixed
- Campaign guide: after the endgame the window now switches back to the campaign as soon as you enter a campaign zone (for example with a new character). Before, “Endgame” stayed until you entered the Riverbank in Act 1.

---

## Build 188

[DE]
### Neu
- Farming: Neuer Reiter „Tafeln suchen" bei Delirium, Riss und Abgrund, so wie bei Ritual. Du wählst die Mods und Mindestwerte aus den Guides, kopierst die Suchzeile für die Lagersuche oder öffnest die Handelsseite (jetzt mit Mindestwerten). Die Rangfolge der Mods kommt aus Mobalytics (Abgrund, Delirium) und timesaver.gg (Riss); wo ein Guide keinen Rang oder Wert nennt, steht das dabei.
### Hinweis
- Die deutschen Suchtexte sind aus der Übersetzungsliste von Exiled Exchange 2 abgeleitet und noch nicht im Spiel einzeln geprüft. Meldet Mods, die nicht gefunden werden.
[EN]
### New
- Farming: new “Find tablets” tab for Delirium, Breach and Abyss, like Ritual. Pick the mods and minimum values from the guides, copy the search line for the stash search or open the trade site (now with minimum values). Mod ranking comes from Mobalytics (Abyss, Delirium) and timesaver.gg (Breach); where a guide gives no rank or value, this is noted.
### Note
- The German search texts are derived from the Exiled Exchange 2 translation list and not yet checked one by one in the game. Please report mods that are not found.

---

## Build 187

[DE]
### Neu
- Buildplaner: Unter den Suchtexten gibt es pro Ausrüstungsplatz den Knopf „Im Handel suchen". Er öffnet die Handelsseite mit den Mods aus dem Build (ODER/UND und Mindestwerte wie bei den Suchtexten). Uniques werden über den Namen gesucht. Mods, die der Handel nicht kennt, werden angezeigt. Mit der Option „Handel: nur diese Basis suchen" legst du fest, ob die Basis mitgesucht wird. Die Mod-Suche gibt es in der Programm-Version.
[EN]
### New
- Build planner: below the search strings there is a “Search in trade” button for each gear slot. It opens the trade site with the mods from the build (OR/AND and minimum values as for the search strings). Uniques are searched by name. Mods the trade site does not know are listed. The option “Trade: search this base only” controls whether the base type is included. The mod search is in the app version.

---

## Build 186

[DE]
### Geändert
- Die Abfrage „Was brauchst du?" beim ersten Start ist entfernt. Es sind immer alle Reiter sichtbar. Über das Zahnrad neben den Reitern blendest du selbst aus, was du nicht brauchst.
### Behoben
- Die Abfrage erschien auch im kleinen Kampagnenführer-Fenster.
[EN]
### Changed
- The “What do you need?” question on first start is gone. All tabs are always visible. Use the gear next to the tabs to hide what you do not need.
### Fixed
- The question also appeared in the small campaign guide window.

---

## Build 185

[DE]
### Neu
- Buildplaner: PoB-Code laden. Den Code aus Path of Building 2 (zum Beispiel von Mobalytics) einfügen oder als Textdatei laden. Übernommen werden Passivbaum, Waffensätze, die Wahl bei den Attribut-Punkten, Ausrüstung und Gems.
- Buildplaner: Attribut-Punkte zeigen ihre Wahl als farbiges S, G oder I.
### Behoben
- Buildplaner: Die Symbole der Skillpunkte erscheinen jetzt rund im Rahmen statt als Quadrat mit Ecken.
[EN]
### New
- Build planner: load a PoB code. Paste the code from Path of Building 2 (for example from Mobalytics) or load it as a text file. Passive tree, weapon sets, the choice on attribute points, gear and gems are taken over.
- Build planner: attribute points show their choice as a coloured S, G or I.
### Fixed
- Build planner: node icons are now drawn round inside their frame instead of as squares with corners.

---

## Build 183

[DE]
### Neu
- Update-Hinweis: Die Werkbank prüft beim Start kurz, ob es eine neuere Version gibt, und zeigt dann oben einen Hinweis mit Download-Knopf.
- „Das ist neu": Nach einem Update zeigt die Werkbank einmalig, was sich geändert hat.
- Einstellungen → Über das Programm: „Nach Updates suchen" und „Änderungsprotokoll".
### Hinweis
- Es wird nichts automatisch installiert. Du lädst das Paket selbst herunter.
[EN]
### New
- Update notice: on start the Werkbank briefly checks for a newer version and shows a banner with a download button.
- “What’s new”: after an update the Werkbank shows once what has changed.
- Settings → About: “Check for updates” and “Changelog”.
### Note
- Nothing is installed automatically. You download the package yourself.

---

## Build 164–182 (Sammelblock / combined)

[DE]
### Neu
- Buildplaner: Die Skill-Baum-Symbole werden beim ersten Start von Grinding Gear Games nachgeladen und nur im Arbeitsspeicher gehalten.
- Buildplaner: Ausrüstung aus einer geladenen Build-Datei (z. B. Mobalytics, Maxroll) wird als Such-Regex für Truhe und Händler angezeigt. Namen von Uniques und Basistypen kommen automatisch auf Deutsch.
- Reiter ein- und ausblenden: Über das Zahnrad neben den Reitern blendest du Reiter aus und ein. Ausgeblendete Reiter rücken zusammen.
- Regex-Generator: Zusätzliche Modifikatoren (Crafting und Spezial-Mods) mit Zuordnung zur Gegenstandsklasse, soweit die Daten es hergeben.
### Verbessert
- Deutsche und englische Namen für Uniques und Basistypen vervollständigt.
- Symbolgrößen im Buildplaner angepasst.
### Behoben
- „Nur Regex" blendete den Regex-Reiter aus, wenn von einer älteren Version eine alte Auswahl gespeichert war.
- Mods, die erkannt, aber nicht in der Klasse möglich sind, wurden fälschlich als „nicht erkannt" angezeigt.
[EN]
### New
- Build planner: the skill tree icons are loaded from Grinding Gear Games on first start and kept in memory only.
- Build planner: gear from a loaded build file (e.g. Mobalytics, Maxroll) is shown as a search regex for stash and trade. Names of uniques and base types are translated automatically.
- Show or hide tabs: use the gear next to the tabs to hide and show tabs. Hidden tabs close up.
- Regex generator: additional modifiers (crafting and special mods) assigned to item classes where the data allows.
### Improved
- German and English names for uniques and base types completed.
- Icon sizes in the build planner adjusted.
### Fixed
- “Regex only” hid the regex tab when an old selection from an earlier version was stored.
- Mods that were recognised but not possible on the class were wrongly shown as “not recognised”.

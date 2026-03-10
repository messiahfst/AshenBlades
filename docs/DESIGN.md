## Grobkonzept AshenBlades (Arbeitsstand)

## 1) Welt und Fantasy
Eine Welt nach dem Untergang eines alten Koenigreichs. Nur wenige Krieger tragen noch legendaere Klingen, geschmiedet aus der Asche der alten Welt.

## 2) Einstieg und erste 10 Minuten
- Charaktererstellung beim ersten Start:
	- Geschlecht
	- Name
- Der Charakter startet ohne Ausruestung.
- In den ersten Runs erhaelt der Spieler seine ersten Items.
- Fruehphase-Ziel: erstes Build-Gefuehl durch sichtbare Stat-Verbesserung.

## 3) Detaillierter Kernablauf (eingeloggt)
1. Spieler startet Kampagne oder Event.
2. Run beginnt mit aktuellem Gear-Setup.
3. Kaempfe liefern XP und Loot-Drops.
4. Spieler prueft Loot direkt im Inventar und entscheidet:
	 - ausruesten
	 - behalten
	 - verwerfen
5. Stat-Werte veraendern den Build-Stil unmittelbar.
6. Run endet bei Abschluss des Ziels oder Tod.
7. Bei Tod: XP-Penalty, sonst kein Verlust.
8. Naechster Run startet mit aktualisiertem Build.

## 4) Idle-Fokus
Im aktuellen Konzept ist fuer Idle vor allem die Loot-Frequenz entscheidend.

## 5) Kampagne vs. Events
- Aktuell kein spielerischer Unterschied in den Regeln.
- Events unterscheiden sich ueber Themen (Gegnertypen/Boss-Themen), nicht ueber Kernmechanik.

## 6) Build-Philosophie
Builds sollen grossen Impact haben.
Jede Spieler-Statistik soll einen eigenen Build-Stil repraesentieren.

## 7) Item-System (kontrolliertes Design)
Die Itemliste wird nicht zufaellig oder wahllos generiert.

Vorgabe fuer diesen Projektschritt:
- Item-Design nur kuratiert.
- Jede neue Item-Gruppe wird vor Einbau gemeinsam reviewed.
- Du bleibst in jedem Schritt der Item-Definition als entscheidende Instanz involviert.

## 8) Gegnertypen und Encounter-Design
Noch offen. Konkrete Gegnertypen werden spaeter definiert, sobald eine klare Vision fuer das Design-Setting steht.

## 11) Kampfsystem

### Bewegung und Interaktion
- Das Spiel ist ein Point-and-Click-Adventure.
- Der Spieler bewegt sich frei durch Klicken auf Orte oder Ziele.
- Jede Interaktion (Gegner anklicken, Objekt benutzen) wird als Runde gezaehlt.

### Kampfaufloesung
- Kaempfe werden vollstaendig automatisch aufgeloest, sobald der Spieler einen Gegner anklickt.
- Waehrend dem Kampf hat der Spieler keine Eingabemoeglichkeit.
- Die entscheidenden Variablen werden vorher gesetzt: Gear, Build-Stats und Traenke-Konfiguration.
- Wer gewinnt, bestimmen die Werte zum Zeitpunkt des Klicks.

### Kampfberechnung (Hybrid)
- Grundlage ist deterministisch: Angriffskraft vs. Ruestung, Leben als Schadenpuffer.
- Zusaetzlich gibt es eine kleine Zufallsvariation (z. B. +-10% Schadensvariation pro Treffer).
- Build-Entscheidungen sind damit weiterhin klar spuerbar und planbar, aber nie 100% garantiert.
- Konkrete Prozentwerte fuer die Variation werden im Prototyp-Balancing festgelegt (noch offen).

### Rundenkonsequenz (Weltreaktion)
- Runden haben globale Auswirkungen auf die Spielwelt.
- Traenke regenerieren sich alle N Runden (Wert noch zu definieren).
- Events laufen nach X Runden ab, wenn der Spieler sie nicht abschliesst (Wert noch zu definieren).
- Weitere Weltreaktionen koennen spaeter ergaenzt werden (z. B. Gegnerrespawn, Ressourcen-Ticks).

### Tränke
- Tränke werden ausserhalb des Kampfes eingesetzt, waehrend der Spieler sich frei bewegt.
- Sie sind kein Reaktionsmittel im Kampf, sondern Vorbereitung.

### Mehrere Gegner
- Ein Raum kann mehrere Gegner enthalten.
- Der Spieler kann jeden Gegner einzeln anklicken und nacheinander bekaempfen.
- Jeder Kampf wird separat als 1v1 aufgeloest.

## 9) Tod und Penalty
Bei Tod verliert der Spieler nur XP (XP-Penalty).
Keine Item-, Loot- oder Ausruestungsverluste.

## 10) Prototyp-Ziel / Scope
Erfolg wird nicht ueber feste KPI gemessen, sondern ueber deine Entscheidung als Produktinstanz.
Scope fuer die naechste Phase: ein funktionierender Prototyp.

## 12) Progressionssystem

### Was ist ein Level?
Ein Level repraesentiert den Fortschritt des Charakters auf zwei Achsen gleichzeitig:
- Der Charakter wird intrinsisch staerker (Basiswerte steigen).
- Neue Inhalte werden freigeschaltet (Zonen, Items, Slots).

### Was passiert bei einem Level-Up?
Bei jedem Level-Up koennen folgende Dinge eintreten:
- Basiswerte steigen automatisch.
- Neue Ausruestungsslots oder Slot-Upgrades werden freigeschaltet.
- Neue Gebiete und Kampagnenabschnitte oeffnen sich.
- Neue Item-Tiers werden lootbar.
- Die genaue Kombination pro Level wird kuratiert festgelegt (kein zufaelliger Inhalt).

### XP-Quellen
XP werden verdient durch:
- Kaempfe gegen Gegner.
- Abschluss von Kampagnenabschnitten und Quests.
- Idle-Fortschritt (Figur sammelt passiv XP waehrend der Spieler ausgeloggt ist).

### Level Cap (Prototyp)
- Maximallevel im Prototyp: Level 10.
- Level 10 entspricht ca. 1 Stunde aktiver Spielzeit.
- Ab Level 10 bestimmt ausschliesslich Gear die weitere Staerke des Charakters.
- Inhalte oberhalb von Level 10 sind nicht Teil des Prototyp-Scopes.

## 13) Inventar- und Loot-System

### Inventar
- Das Inventar ist unbegrenzt gross.
- Kein Platzmangel, kein Verwerfungszwang durch volle Slots.

### Loot-Anzeige
- Loot wird nicht nach jedem einzelnen Kampf angezeigt.
- Am Ende eines Runs erhaelt der Spieler eine gesammelte Uebersicht aller erbeuteten Items.
- Dort trifft er seine Entscheidungen: ausruesten, behalten oder verwerten.

### Item-Verwertung
- Items koennen gegen Waehrung eingetauscht werden (im Prototyp verfuegbar).
- Spaeter: Items koennen zusaetzlich in Craft-Materialien zerlegt werden (Post-Prototyp).
- Kein einfaches Loeschen ohne Gegenwert vorgesehen.

### Waehrung
- Entsteht durch Item-Verwertung.
- Verwendungszweck der Waehrung noch zu definieren (z. B. Haendler, Upgrades, Crafting).

## Offene Punkte fuer naechste Iteration
- Exakte Loot-Frequenz definieren (Idle und aktiv, getrennt).
- Build-Stile pro Stat konkret benennen.
- Item-Rahmen (Anzahl Items pro Slot im Prototyp) festlegen.
- Erste Event-Themen und Boss-Themen auflisten.
- Waehrungsverwendung definieren: Wofuer kann Waehrung eingesetzt werden?


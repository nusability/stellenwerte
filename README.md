# Stellenwerte · Mehrsystemblöcke

Eine mobile-first Web-App zum Lernen des **Stellenwertsystems** (Basis 10) mit
drei verknüpften Darstellungen derselben Zahl. Wählbar **2, 3, 4 oder 5 Stellen**
(bis 99, 999, 9999 oder 99999; Standard: 2):

1. **Tally-Counter** – ein Handklicker mit mechanischem Odometer (rollende Ziffernräder),
   großem **+1**-Druckknopf, **−1** und Reset. Sein Zählwerk steht hinter einem `=`
   und ist das Ergebnis der Stellenwert-Summe (siehe 3.).
2. **Dienes-/Mehrsystemblöcke** in einer Stellenwerttabelle in isometrischer 3D-Optik.
   Echte Mehrsystemblöcke: Einer = Würfel · Zehner = Stange · Hunderter = Platte ·
   Tausender = Würfel · Zehntausender = Turm aus 10 Tausendern. Stangen, Platten und
   Würfel tragen Markierungen für jede „1". Die Einer liegen lose verstreut (nie in
   einer Reihe – eine Stange bedeutet immer genau Zehn).
3. **Stellenwert-Summe** unter der Tabelle – die Zahl als Summe ihrer Stellenwerte:
   aus 5302 wird `5000 + 300 + 00 + 2`. Jeder Term steht direkt unter „seiner"
   Blockspalte (die Ziffer in Spaltenfarbe, ihre Nullen blasser als Platzhalter)
   und ist per farbigem Kabel mit genau dem Ziffernrad im Klicker verbunden,
   zu dem er gehört. So ist sichtbar, dass die 3 in der Hunderterspalte
   **300** bedeutet – und dass der Klicker die Summe aller Stellenwerte zeigt.

Alle Ansichten sind **immer synchron und bidirektional**: Die Zahl ist die einzige Quelle
der Wahrheit. Bündeln/Entbündeln (Übertrag und Borgen) wird sichtbar gemacht – zehn Blöcke
einer Stelle wandern zusammen, fügen sich zur Form der nächsten Stelle und **verschmelzen**
(und umgekehrt beim Borgen).

## Bedienung

- **Klicker** drücken oder unter einer Spalte **+/−** tippen — gedrückt halten zum fortlaufenden Zählen.
- **Tastatur:** `↑` +1 · `↓` −1 · Zifferntasten erhöhen, `q w e r t` verringern
  (von der höchsten zur niedrigsten Stelle) — Taste halten zum Zählen.
- **Stellen:** oben 2, 3, 4 oder 5 wählen.

## Technik

Eine einzige, eigenständige `index.html` – reines HTML/CSS/JS, kein Build-Schritt.
Läuft direkt über `file://` und auf dem Smartphone (Touch, Safe-Area, responsiv).
`prefers-reduced-motion` wird respektiert.

🤖 Erstellt mit [Claude Code](https://claude.com/claude-code)

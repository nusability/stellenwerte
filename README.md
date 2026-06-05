# Stellenwerte · Mehrsystemblöcke

Eine mobile-first Web-App zum Lernen des **Stellenwertsystems** (Basis 10) mit
zwei verknüpften Darstellungen derselben Zahl. Wählbar **3, 4 oder 5 Stellen**
(bis 999, 9999 oder 99999):

1. **Tally-Counter** – ein Handklicker mit mechanischem Odometer (rollende Ziffernräder),
   großem **+1**-Druckknopf, **−1** und Reset.
2. **Dienes-/Mehrsystemblöcke** in einer Stellenwerttabelle in isometrischer 3D-Optik.
   Echte Mehrsystemblöcke: Einer = Würfel · Zehner = Stange · Hunderter = Platte ·
   Tausender = Würfel · Zehntausender = Turm aus 10 Tausendern. Stangen, Platten und
   Würfel tragen Markierungen für jede „1". Die Einer liegen lose verstreut (nie in
   einer Reihe – eine Stange bedeutet immer genau Zehn).

Beide Ansichten sind **immer synchron und bidirektional**: Die Zahl ist die einzige Quelle
der Wahrheit. Bündeln/Entbündeln (Übertrag und Borgen) wird sichtbar gemacht – zehn Blöcke
einer Stelle wandern zusammen, fügen sich zur Form der nächsten Stelle und **verschmelzen**
(und umgekehrt beim Borgen).

## Bedienung

- **Klicker** drücken oder unter einer Spalte **+/−** tippen — gedrückt halten zum fortlaufenden Zählen.
- **Tastatur:** `↑` +1 · `↓` −1 · Zifferntasten erhöhen, `q w e r t` verringern
  (von der höchsten zur niedrigsten Stelle) — Taste halten zum Zählen.
- **Stellen:** oben 3, 4 oder 5 wählen.

## Technik

Eine einzige, eigenständige `index.html` – reines HTML/CSS/JS, kein Build-Schritt.
Läuft direkt über `file://` und auf dem Smartphone (Touch, Safe-Area, responsiv).
`prefers-reduced-motion` wird respektiert.

🤖 Erstellt mit [Claude Code](https://claude.com/claude-code)

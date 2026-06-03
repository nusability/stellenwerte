# Stellenwerte · Mehrsystemblöcke

Eine mobile-first Web-App zum Lernen des **Stellenwertsystems** (Basis 10, 0–9999) mit
zwei verknüpften Darstellungen derselben Zahl:

1. **Tally-Counter** – ein Handklicker mit mechanischem Odometer (rollende Ziffernräder),
   großem **+1**-Druckknopf, **−1** und Reset.
2. **Dienes-/Mehrsystemblöcke** in einer Stellenwerttabelle
   (Tausender · Hunderter · Zehner · Einer) in isometrischer 3D-Optik.

Beide Ansichten sind **immer synchron und bidirektional**: Die Zahl ist die einzige Quelle
der Wahrheit. Bündeln/Entbündeln (Übertrag und Borgen) wird mit wandernden Blöcken
sichtbar gemacht – dieselben Würfel reisen physisch in die nächste Spalte.

## Bedienung

- **Klicker** drücken oder unter einer Spalte **+/−** tippen.
- **Tastatur:** `↑` +1 · `↓` −1 · `1 2 3 4` erhöhen, `q w e r` verringern
  (Tausender · Hunderter · Zehner · Einer).

## Technik

Eine einzige, eigenständige `index.html` – reines HTML/CSS/JS, kein Build-Schritt.
Läuft direkt über `file://` und auf dem Smartphone (Touch, Safe-Area, responsiv).
`prefers-reduced-motion` wird respektiert.

🤖 Erstellt mit [Claude Code](https://claude.com/claude-code)

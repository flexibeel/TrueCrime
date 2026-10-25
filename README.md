# TrueCrime (Arbeitstitel)

Coop-Ermittlungsspiel von Felix (flexibeel). Jeder Spieler sieht andere Hinweise, nur zusammen löst ihr den Fall.

**Stand:** Papiertest, Fall 01 „Der Abend im Hotel Möwenruh“. Nur zum Ausprobieren der Spielidee.

- Start: `index.html` (Rolle wählen)
- Ermittler A (Spurensucher, Archivar): `fall01-a.html`
- Ermittler B (Befrager, Techniker): `fall01-b.html`

Jeder öffnet nur seine eigene Seite. Die Lösung steckt nur als SHA-256-Wert in den Seiten. Notizen bleiben im eigenen Browser, online wird nichts gespeichert.

Konzept: `claude/KONZEPT.md`, Stand und nächste Schritte: `claude/FAHRPLAN.md`, Arbeitsregeln für Claude: `CLAUDE.md`. Seiten erzeugt von `tools/papiertest-build.py`.

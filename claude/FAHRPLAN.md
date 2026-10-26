# Fahrplan: Stand, Entscheidungen, Übergabe

**Jeder neue Chat liest zuerst diese Datei** (und `CLAUDE.md`). Am Ende jedes Chats wird sie aktualisiert und mitgepusht.

Stand: 26.10.2026. **Pausiert.** Felix war mit der Idee nicht zufrieden (gibt es schon, zu viel Lesen, Thema zieht nicht, kein Kribbeln). Stattdessen wird Grandline neu ausgerichtet (Repo `flexibeel/Grandline`, `claude/PLAN-NEUAUSRICHTUNG.md`). Die stärkste Idee von hier, **zeitversetzt zusammen spielen und jeder sieht etwas anderes**, wandert dorthin mit. Dieses Repo bleibt als Archiv, der Papiertest bleibt online.

## Worum es geht
Coop-Ermittlungsspiel, cozy verpackt, ernste Fälle. 2 bis 4 Spieler, jeder hat eine Rolle und sieht **nur seine Hinweise**. Der größte Aha-Moment ist **der Widerspruch** zwischen Hinweisen verschiedener Spieler. Zeitversetzt spielbar über Tage (Felix und sein Kumpel wohnen 200 km auseinander). Alles Weitere: `claude/KONZEPT.md`.

## Was schon steht
- **Konzept:** `claude/KONZEPT.md` (Idee, Ablauf, Fallgenerator mit Prüfer, Takt, Inhalts-Leitlinien, Meilensteine, Risiken).
- **Papiertest M0, Fall 01 „Der Abend im Hotel Möwenruh“ ist online:**
  - Start: https://flexibeel.github.io/TrueCrime/
  - Akte A (Felix, Spurensucher + Archivar): https://flexibeel.github.io/TrueCrime/fall01-a.html
  - Akte B (Kumpel, Befrager + Techniker): https://flexibeel.github.io/TrueCrime/fall01-b.html
  - Seiten erzeugt von `tools/papiertest-build.py` (enthält die Lösung im Klartext, Spieler nicht öffnen). Lösung nur als Hash in den Seiten, Prüf-Knopf sagt „x von 3 stimmen“. Notizen und Sterne im Browser, nichts online.
  - Texte zusätzlich als Markdown in `papiertest/`. Lösung und Beweiskette: `claude/SPOILER-FALL-01.md` (nur für Claude).
- **Marktcheck (Felix fragte „gibt's das schon?“):** Ja, der Kern existiert: *Parallel Experiment* und *Unsolved Case* (Eleven Puzzles, Noir-Comic, 2 Spieler, geteilte Hinweise, Sprachchat), *Mark & Lara: Partners in Justice*. **Unsere Lücke:** zeitversetzt über Tage statt gleichzeitig im Sprachchat, unendlich viele erzeugte Fälle statt handgemachter, echtes Ermitteln (Alibis, Widersprüche, Anklage) statt Escape-Rätsel, 2 bis 4 statt fest 2 Spieler.

## Entscheidungen von Felix (alle 25.10., per Klick)
- Grandline bleibt in der Pipeline, TrueCrime läuft nebenher in diesem eigenen Repo.
- **Ton:** True Crime, fiktive Mordfälle, nie grausam; Mischung aus düster, ernst und skurril. Cozy ist die Verpackung.
- **Spieler:** 2 bis 4, Hauptpaar Felix + Kumpel über Entfernung. Weitergehen muss es auch, wenn einer 2 Tage offline ist, aber keiner darf alles allein durchrushen (Bausteine dafür im Konzept, Abschnitt „Spannung und Takt“).
- **Spannung:** escape-room-mäßig (Rätselschlösser, Atmosphären-Wecker) ab Fall 02; Fall 01 ist nur Logiktest.
- **Wendungen:** alle vier (Alibi-Trick, geschlossener Raum, Doppelleben, Fälschung). **Fall-Längen:** gemischt (Kurz-, Tages-, Serienfall).
- **Figuren:** neu erzeugt je Fall. **Storytelling:** Verhör-Szenen (großes Porträt, Sprechblase, Mimik verrät die Lüge).
- **Plattform:** Web-App zuerst (GitHub Pages), später App in den Stores.
- **Look:** eigenständig, **nicht** Noir-Comic (zu nah an Parallel Experiment). Drei Richtungen als Entwurf, Wahl offen (siehe unten).

## Offen: Look-Wahl
Design-Fläche in Felix' Claude-Account (privat, nur Felix sieht sie): **„TrueCrime Noir-Look“**, https://claude.ai/artifact/6eTrNvC9BH6k7p8HS6HzHH. Drei Skizzen desselben Handy-Bildschirms (Fallakte, eine Verdächtige, eine Hinweiskarte, Navigation Pinnwand/Verhör/Anklage):
- **A · Riso-Akte:** zwei Druckfarben (Pink #E8337A, Petrol #2E8C8C) auf Creme #F3EEE3, Schrift Bricolage Grotesque + IBM Plex Mono, Körnung, Zine-Gefühl.
- **B · Puppenhaus-Krimi:** Hotel im Querschnitt, Räume antippbar, warme Pastelltöne auf Nachtviolett #2B2440, Schrift Fraunces + Nunito, am meisten cozy.
- **C · Thriller-Plakat:** flache Silhouetten wie ein 60er-Thriller-Plakat, Orange #EE6A1F, Schwarz, Creme, Schrift Oswald + Work Sans.
Mischungen sind erlaubt (z. B. Puppenhaus-Querschnitt im Plakat-Stil). Die Skizzen sind Richtung, keine fertige Kunst.

## Als Nächstes
1. **Look entscheiden** (Felix per Klick, A/B/C/Mischung), dann die Fläche ausbauen: Verhör-Szene mit Mimikwechsel, Pinnwand, Hinweiskarte im Detail.
2. **Papiertest Fall 01 auswerten**, sobald Felix und Kumpel gespielt haben (Lösung, Dauer, Aha-Moment, wo es zäh war). Erst wenn der Spaß da ist, geht es an M1.
3. **Weitere Planungsfragen** (mit Klick-Fragen): Wie fühlt sich jede Rolle nützlich an? Wie sehen Pinnwand und Hinweiskarten im Spiel aus? Welche Rätselarten (Codes, Zeitleisten, Räume) ab Fall 02? Wie genau funktioniert der Tagestakt (Züge pro Tag, Vertretung bei Abwesenheit)?
4. Danach M1: Fallgenerator mit Prüfer (Opus, ohne Oberfläche).

## Letzte Übergabe
- 26.10.: Pausiert, siehe Stand oben. Nicht weiterbauen, außer Felix will es ausdrücklich.
- 25.10. (1. Chat, gestartet im Grandline-Chat): Idee entwickelt, Konzept geschrieben, Papiertest Fall 01 gebaut und online gestellt, Marktcheck, drei eigenständige Looks skizziert. Nichts gebaut außer dem Papiertest. Nächstes: Look-Wahl, dann Rückmeldung zum Papiertest abwarten und weiter planen.

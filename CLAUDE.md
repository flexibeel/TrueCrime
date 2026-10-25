# TrueCrime: Arbeitsregeln für Claude

Neues Spiel von Felix (flexibeel): ein Coop-Ermittlungsspiel, jeder Spieler sieht andere Hinweise, nur zusammen löst ihr den Fall. Kostenloses Projekt, Felix bezahlt Claude selbst, deshalb gilt: sparsam und gezielt arbeiten. Grandline (`flexibeel/Grandline`) läuft parallel weiter und wird hier nicht angefasst.

## Vorgehen (wie bei Grandline)
- **Erst fragen, dann bauen.** Neue Ideen erst kurz vorschlagen (was, wo, wie groß), Zusage abwarten. Erst planen und abstimmen, dann programmieren.
- **Fragen zum Anklicken.** Entscheidungen als Auswahl-Fragen (Fragen-Werkzeug mit Antwortknöpfen), nicht als Liste im Text. Die empfohlene Antwort steht zuerst.
- **Klein anfangen.** Erst der Kern, der Spaß macht (Fall, Hinweise, Widerspruch), dann Rahmen und Politur. Das war die Lehre aus Grandline.
- **Sparsam testen.** Ein gezielter Test statt vieler Durchläufe.
- **Ehrlich bleiben.** Wenn etwas schon existiert oder eine Idee schwach ist, offen sagen.

## Neuer Chat
- Zuerst `claude/FAHRPLAN.md` lesen, dann bei Bedarf `claude/KONZEPT.md`. Code nur gezielt öffnen.
- `claude/SPOILER-*.md` nur lesen, wenn eine Lösung ausgewertet werden muss, und nie den Inhalt verraten, bevor die Spieler ihre Lösung genannt haben.
- Am Ende des Chats `claude/FAHRPLAN.md` aktualisieren (Stand, Entscheidungen, „Letzte Übergabe“) und mitpushen.
- Ist ein Thema fertig, als letzte Nachricht eine **Startnachricht für den nächsten Chat** als Codeblock, genau so:
  ```
  Arbeite im Repo flexibeel/TrueCrime, lies claude/FAHRPLAN.md.
  Nächstes Thema: <Punkt aus „Als Nächstes“>
  ```

## Git
- Dieses Repo ist öffentlich und läuft über GitHub Pages (`https://flexibeel.github.io/TrueCrime/`), Quelle `main`, Ordner root. Was auf `main` liegt, ist sofort online.
- Bauarbeiten auf eigenem Zweig (`feature/...`), nach `main` nur nach Felix' Okay. Reine Doku (Fahrplan, Konzept) darf direkt auf `main`.
- Keine Lösungen im Klartext in Spielseiten: nur als SHA-256-Wert (siehe `tools/papiertest-build.py`).

## Modellwahl
- **Sonnet:** Planen, Fragen, Fälle und Texte schreiben, Fahrplan, kleine Änderungen.
- **Opus:** Fallgenerator mit Prüfer, Oberfläche über mehrere Dateien, Online-Coop (Supabase), Kunst.
- Claude sagt von sich aus, wenn ein Wechsel sinnvoll ist.

## Stil
- Deutsch zuerst, Englisch später. Texte spannend, gern mit trockenem Witz in den Aussagen der Verdächtigen.
- Fälle sind frei erfunden. Echte Fälle liefern nur Muster (Alibi-Trick, Fälschung …), nie Namen, Opfer oder Orte. Nichts Grausames im Bild.

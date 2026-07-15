# morgenbericht-routine

Repository für die tägliche Morgenbericht-Routine.

## Struktur

- `SCHREIBREGELN.md` (Repo-Root, auf `main`): Verbindliche Stil- und Anti-KI-Schreibregeln für den Bericht. Jeder Routinelauf liest diese Datei zuerst aus `origin/main` und hält sich beim Schreiben strikt daran.
- `history/` (auf `main`): Themen-Gedächtnis, eine Datei `topics-YYYY-MM-DD.txt` pro Tag, dient nur der Doppelungs-Vermeidung, nie als Faktenquelle.

Beide leben auf `main`, weil jeder Lauf frisch von `main` abzweigt und Gedächtnis wie Schreibregeln direkt aus `origin/main` liest.

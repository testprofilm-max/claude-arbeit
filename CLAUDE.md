# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

<!-- Kurz halten. Deutsch. Ergänzt die globale ~/.claude/CLAUDE.md, die Uwes Vorgaben enthält. -->

## Worum es geht

Uwes Arbeitsordner. Kein Code-Projekt: hier entstehen Auswertungen, Berichte,
Analysen und Planungen für Label-23 / Boxing Connection und Die Textilfabrik
sowie private Auswertungen. Nichts zu bauen, zu linten oder zu testen.
Ergebnisse werden als Dateien abgelegt und per Git nach GitHub gesichert.

## Ordner

| Ordner | Zweck |
|---|---|
| `Label-23/` | Alles zu Label-23. Rohdaten (Excel, PDF, CSV-Exporte) in `Eingang/`, fertige Auswertungen daneben. |
| `Textilfabrik/` | Alles zur Textilfabrik, gleicher Aufbau. |
| `Privat/` | Finanzen, Sport, Gesundheit, Ernährung. Rein privat, steht in `.gitignore`, geht nie nach GitHub. NIE mit den Marken vermischen. |
| `tmp/` | Temp-Dateien und Zwischenstände. Steht in `.gitignore`. |
| `.claude/` | Projekteinstellungen, Regeln, Skills, Agents (noch leer). |

Neues Vorhaben: Unterordner `<Bereich>/<Vorhaben>/` mit kurzer CLAUDE.md
(Zweck, Quellen, Ergebnisform, Empfänger) anlegen.

## Git

- Branch `main`, Remote `origin` = `github.com/testprofilm-max/claude-arbeit` (Uwes Konto).
- Commits nur auf Uwes Anweisung, Commit-Nachrichten auf Deutsch.
- NIE eigenständig `git push`. Vor jedem Commit prüfen, dass nichts aus `Privat/`
  oder `tmp/` dabei ist.
- Ordner unter `*/.claude/worktrees/` sind Git-Worktrees anderer Claude-Sitzungen,
  kein Arbeitsinhalt. Nicht bearbeiten, nicht committen (stehen in `.gitignore`).

## Nicht nutzen

Die synchronisierten Skills Arthur, Eddi, Toni, Texter, Kritiker, Markant-Radar,
Instagram-Analytics, Textilfabrik-Designer und -Kritiker sind Marks Agenten mit
Pfaden auf einem anderen Rechner. Nicht auslösen, außer Uwe verlangt es ausdrücklich.

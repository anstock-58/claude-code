# CLAUDE.md – Projektdokumentation

## Repository
- **GitHub:** https://github.com/anstock-58/claude-code
- **Owner:** anstock-58
- **Haupt-Branch:** main
- **Entwicklungs-Branch:** claude/setup-github-connection-CNqL3

## GitHub-Verbindung

Dieses Projekt ist mit GitHub über das GitHub MCP-Server verbunden.
Claude Code kann direkt mit GitHub interagieren:

- Issues lesen und erstellen
- Pull Requests verwalten
- Code pushen und Branches erstellen
- Repository-Informationen abrufen

### Git-Konfiguration
- **Remote:** origin → https://github.com/anstock-58/claude-code
- **Commit-Signierung:** SSH (automatisch konfiguriert)
- **Push-Branch:** immer `git push -u origin <branch-name>`

## Arbeitsweise

### Änderungen vornehmen
1. Dateien bearbeiten
2. `git add <datei>`
3. `git commit -m "Beschreibung"`
4. `git push -u origin <branch-name>`

### Branch-Strategie
- `main` – stabiler Produktions-Branch (geschützt)
- Feature-Branches für neue Entwicklungen
- Claude arbeitet auf dem zugewiesenen Branch

## Sicherung & Backup

Code ist auf GitHub gesichert sobald er gepusht wurde.
Für lokales Backup: lokales Verzeichnis in iCloud-Ordner ablegen.

## ANDI STYLE-CORE – Verbindlicher Schreibstil

Alle Texte die für Andreas Stock geschrieben werden, folgen diesem Stil.

**Grundprinzip**
Texte sollen sich anfühlen, als hätte sie ein echter Mensch geschrieben. Klar, direkt, natürlich. Nicht geschniegelt. Nicht künstlich. Nicht wie ein Lehrbuch oder Werbetext.

**Stimme und Haltung**
- Ruhig, direkt, menschlich
- Keine künstliche Motivation, kein Predigen, kein erhobener Zeigefinger
- Der Autor muss nicht auf alles eine Antwort haben
- Darf nachdenklich sein, etwas offenlassen, auch sagen wenn etwas schwierig ist
- Haltung: Mensch mit Lebenserfahrung — nicht Opfer, nicht Guru

**Sprachstil**
- Unterschiedliche Satzlängen — kurze und lange Sätze wechseln sich ab
- Absätze bewusst einsetzen, damit Gedanken Raum bekommen
- Kleine Brüche sind erlaubt
- Natürlichkeit ist wichtiger als sprachliche Perfektion

**Verbotene Formulierungen**
- „In der heutigen Zeit", „Zudem", „Darüber hinaus", „Nicht zuletzt"
- „Abschließend lässt sich sagen", „Zusammenfassend lässt sich sagen"
- „Es ist wichtig zu verstehen", „Man darf nicht vergessen"
- Keine künstliche Business-Sprache, keine KI-Floskeln
- Keine leeren Motivationssätze, keine übertriebenen Superlative
- Keine perfekt symmetrisch aufgebauten Absätze

**Kein künstliches Ende**
- Kein automatisches Fazit oder Zusammenfassung am Ende
- Der Text darf mit einem Gedanken, einer offenen Frage oder klaren Aussage enden

**Priorität**
Wenn zwischen sprachlicher Perfektion und natürlicher Wirkung gewählt werden muss → natürliche Wirkung gewinnt immer.

---

## Wichtige Hinweise
- Niemals direkt auf `main` pushen ohne Review
- Immer committen bevor die Session endet (Stop-Hook prüft dies)
- GitHub MCP Tools für alle GitHub-Interaktionen verwenden

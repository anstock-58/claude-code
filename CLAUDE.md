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

## Wichtige Hinweise
- Niemals direkt auf `main` pushen ohne Review
- Immer committen bevor die Session endet (Stop-Hook prüft dies)
- GitHub MCP Tools für alle GitHub-Interaktionen verwenden

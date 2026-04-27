---
layout: default
title: 1. Installation der Tools
parent: Onboarding
---

# 1. Installation der Tools

[← Onboarding-Übersicht](index.md) | [Hauptseite](../index.md)

---

## 1.1 Ordner anlegen

1. **Datei-Explorer** öffnen → zu `C:\` navigieren
2. Ordner `github` erstellen (falls nicht vorhanden)
3. Pfad merken: `C:\github`

## 1.2 VS Code installieren

1. https://code.visualstudio.com → Windows-Version laden
2. Installer ausführen → immer **„Weiter"** klicken
3. VS Code starten

## 1.3 Git installieren

1. https://git-scm.com → **Git for Windows** laden
2. Installer ausführen → immer **„Weiter"** klicken
3. In PowerShell testen:
   ```terminal
   git --version
   ```
   Erwartung: z.B. `git version 2.40.0`

## 1.4 Git konfigurieren

VS Code → **Terminal > Neues Terminal** → Werte ersetzen:
```terminal
git config --global user.name "Vorname Nachname"
git config --global user.email "deine@email.com"
git config --global --list
```

Prüfe, dass `user.name` und `user.email` korrekt angezeigt werden.

---

**Nächster Schritt:** [2. Projekt einrichten →](02-projekt.md)

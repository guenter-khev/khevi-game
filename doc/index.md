---
layout: default
title: Khevi Game Dokumentation
author: 6R 2026 und Prof. Öller
---

# Projekt-MitarbeiterIn

## Installation der IDE (Entwicklungsumgebung)

1. Ordern c:/github erstellen
2. VS Code installieren ... immer "default" OK
3. Git for Windows installieren ... immer "default" OK
4. VS Code / Versionierung / Github Projekt "khevi-game" checkout
5. VS Code / Terminal / Git user.name und user.email festlegen:
```terminal
git config --global user.name "Vorname Nachname"
git config --global user.email "deine@email.com"
git config --global --list
```
Beispiel:
```terminal
git config --global user.name "Prof. Öller"
git config --global user.email "guenter.oeller@khev.at"
git config --global --list
```

Die korrekte Ausgabe ist dann: 
```terminal
core.editor="C:\Users\guent\AppData\Local\Programs\Microsoft VS Code\bin\code" --wait
user.name=Prof. Öller
user.email=guenter.oeller@khev.at
```


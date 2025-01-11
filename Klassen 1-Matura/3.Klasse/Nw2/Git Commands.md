[[3.Nwt]]
___
```c
# Repository initialisieren
git init                                // Neues lokales Git-Repository erstellen

# Dateien hinzufügen und committen
git add .                               // Alle Dateien zum Commit vorbereiten
git commit -m "Initial commit"          // Ersten Commit mit einer Nachricht erstellen

# Branch in master umbenennen (optional, falls standardmäßig main erstellt wurde)
git branch -M master                    // Aktuellen Branch in master umbenennen

# Remote-Repository verknüpfen
git remote add origin https://github.com/dein-benutzername/dein-repository.git // Remote-Repository hinzufügen

# Änderungen pushen
git push -u origin master               // Änderungen in das Remote-Repository auf Branch master pushen

# .gitignore erstellen
echo "# Ignored files" > .gitignore     // .gitignore-Datei erstellen
echo "node_modules/" >> .gitignore      // Beispiel für das Ignorieren des Ordners node_modules
echo "*.log" >> .gitignore              // Beispiel für das Ignorieren aller Log-Dateien

# README.md erstellen
echo "# Mein Repository" > README.md    // README.md-Datei mit Titel erstellen
echo "Dies ist ein Beispiel-Repository." >> README.md // Beschreibung hinzufügen

# Dateien hinzufügen und committen
git add .gitignore README.md            // .gitignore und README.md zum Commit hinzufügen
git commit -m "Add .gitignore and README.md" // Änderungen committen
git push                                // Commit ins Remote-Repository pushen

```
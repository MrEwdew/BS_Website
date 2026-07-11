# Betriebssysteme Lernpaket

Statisches Lernpaket fuer Betriebssysteme mit Zusammenfassung, Trainern,
Mini-Klausurmodus, Originalklausur-Check und Fehlerlog.

## Start

Lokal oder auf GitHub Pages einfach diese Datei oeffnen:

```text
index.html
```

Die Seite funktioniert ohne Build-Schritt und ohne Server, weil alles aus
normalen HTML-Dateien besteht.

## Enthaltene Seiten

- `index.html` - Startseite
- `cheatsheet_a4.html` - druckfertiges 2-Seiten-A4-Cheatsheet
- `Betriebssysteme_pruefungsorientierte_Zusammenfassung.html`
- `scheduling_trainer.html`
- `deadlock_trainer.html`
- `synchronisation_trainer.html`
- `speicher_trainer.html`
- `dateisystem_trainer.html`
- `mini_klausur_trainer.html`
- `kurzantwort_trainer.html`
- `originalklausur_check.html`
- `fehlerlog.html`
- `Betriebssysteme_Lernpaket.zip`

## GitHub Pages veroeffentlichen

1. Neues GitHub-Repository erstellen, zum Beispiel `betriebssysteme-lernpaket`.
2. Nur die Dateien aus dem Ordner `github_pages_site` in dieses Repository hochladen.
3. In GitHub: `Settings` -> `Pages`.
4. Bei `Build and deployment` waehlen:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Speichern und kurz warten.
6. Danach ist die Seite unter einer URL wie dieser erreichbar:

```text
https://DEINNAME.github.io/betriebssysteme-lernpaket/
```

## Wichtig

Die Vorlesungs- und Klausur-PDFs aus dem Arbeitsordner werden fuer die Website
nicht gebraucht. Falls du keine ausdrueckliche Erlaubnis zur Veroeffentlichung
hast, lade diese PDFs nicht in ein oeffentliches GitHub-Repository hoch.

Das Fehlerlog nutzt `localStorage`. Eintraege bleiben also im jeweiligen Browser
gespeichert und werden nicht an GitHub oder einen Server gesendet.

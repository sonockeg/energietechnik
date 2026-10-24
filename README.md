# Energietechnik – modularer Praxiskurs

## Inhalt
- `main.tex`: Hauptdatei
- `kapitel/`: einzelne Kapiteldateien
- `literatur/`: Platzhalter für Literaturdaten
- `tikz/`: Platzhalter für eigenständige TikZ-Abbildungen

## Kompilierung
Benötigt eine LaTeX-Distribution mit LuaLaTeX und den Paketen KOMA-Script,
fontspec, babel, siunitx, TikZ, cleveref und den weiteren in `main.tex`
genannten Paketen.

Im Projektverzeichnis ausführen:

```bash
latexmk -lualatex main.tex
```

Alternativ `lualatex main.tex` mindestens zweimal ausführen, damit
Inhaltsverzeichnis und Querverweise aktualisiert werden.

## Arbeitsweise
Kapitel werden in `main.tex` mit `\include{kapitel/dateiname}` eingebunden.
Jedes Fachkapitel soll Modell, Annahmen, Herleitung, Beispiel, typische Fehler,
Aufgaben und Lösungen enthalten.

## Fachlicher Hinweis
Das Skript ist eine Lernunterlage und keine Arbeits- oder Schaltanweisung.
Normenstände, rechtliche Anforderungen und betriebliche Vorgaben sind für
den konkreten Anwendungsfall gesondert zu prüfen.

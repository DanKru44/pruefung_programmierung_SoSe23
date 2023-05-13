# Ausarbeitung Programmierung SoSe 2023
In diesem Repo befindet sich die Ausarbeitung für die Modulprüfung Programmierung für das Sommersemester 2023. Die einzelnen Teilaufgaben werden dazu im Ordner Chapter in eizelnen .tex Dateien bearbeitet und im Hauptverzeichnis in die Datei main.tex eingefügt. In der Datei test.tex wurden einige Befehle für LaTeX ausprobiert und dient als Hilfestellung für die Erstellung der main.tex mit Beispielen.


## Kompilation
Die Datei main.tex lässt sich einfach mit dem paket texlive komilieren. Um das Literaturverzeichnis und das Inhaltsverzeichnis zu generieren müssen mehrere Kompilations-Schritte durchlaufen werden.

1. Zuerst die main.tex kompiliert werden.

2. Anschließend muss die die Datei main.aux mit dem Befehl Bibtex kompiliert erden.

3. Nun muss erneut die main.tex kompiliert werden.
	
4. Zuletzt noch einmal die main.tex kompilieren.

Beispiel:
```
pdflatex main.tex
bibtex main.aux
pdflatex main.tex
pdflatex main.tex
```
	

## Ordnerinhalte
Eine grobe Auflistung der Ordnerinhalte in diesem Repo. Weitere Informationen befinden sich in den README.md Dateien der Ordner.

### Images
Enthält alle in der Ausarbeitung verwendeten Bilder und Grafiken.

### Chapter
Enthält die .tex Dateien der einzelnen Teilaufgaben der Ausarbeitung und eine Liste mit den zu erledigenden Aufgaben und Aufgabenteilen.

### Style
Enthält Textformatierungseinstellungen der .tex Dateien.

### Literatur
Enthält die BibTeX-Datei aus der das Quellenverzeichnis erstellt wurde und Erklärung zu den genutzten Befehlen. Ebenfalls ist eine Anleitung zum zitieren enthalten.


## Aufgabenbeschreibung
Kurze Zusammenfassungen der Teilaufgaben der Ausarbeitung.
Umfangreichere Informationen zu den Teilaufgaben befinden sich in der README.md des Ordners Chapter.

### [ ] Aufgabe 1
- Erstellen des Repos, der main.tex, README.md und der Ordner für das Repo der Ausarbeitung.
- Ein Aufsatz (400 +/-25 Wörter) über Textsatzbeschreibungssprachen.

### [ ] Bonusaufgabe 
- Auswahl eines Programmes aus dem Repo [heirloom-project](https://github.com/ryanwoodsmall/heirloom-project/tree/musl/heirloom).
- Beschreiben und erklären des Programms Zeile für Zeile.

## To do´s 
Kleine Teilschritte die nicht direkt mit den Aufgaben zu tun haben, allerdings mit zur Ausarbeitung wie z.b. BibTex Quellenangaben usw. . Dieser Abschnitt dient nur als Hilfestellung für mich persönlich um einen Überblick über zu erledigende Aufgaben zu behalten.

- [x] BibTex einbindung testen
- [x] Aufgaben einbindung in die main.tex testen
- [ ] Datum in die main.tex am Ende der Bearbeitung einfügen
- [ ] Formatierung der main.tex 
	- [ ] Fußnote
	- [ ] Abbiludngsverzeichnis
	- [ ] Tabellenverzeichnis
	- [ ] Literaturverzeichnis 
	- [ ] Begriffsverzeichnis
- [ ] Vorwort
- [ ] Überblick Kapitelweise
- [ ] Zusammenfassung Kapitelweise

## Links
Hier sind einige nützliche Links enthalten zur bearbeitung von .tex Dateien , .md Datein, usw. 

### Markdown (.md)

- Formatierung von .md Dateien auf [GitHub](https://docs.github.com/de/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

### Latex (.tex)

- Hilfestellungen und Anleitungen auf [Overleaf](https://www.overleaf.com/learn)

- Skript zur Verwendung von Latex von [Daniel Hommel](https://www2.hs-esslingen.de/~dhommel/skript.pdf)

- Skript zur Verwendung von Latex von [Thorsten Nagel](http://astro.uni-tuebingen.de/~nagel/pub/Kolleg/Latex/DOKU/Latexkurs_Skript.pdf)

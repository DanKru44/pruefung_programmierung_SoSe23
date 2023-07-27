# Ausarbeitung Programmierung SoSe 2023
In diesem Repo befindet sich die Ausarbeitung für die Modulprüfung Programmierung für das Sommersemester 2023. Die einzelnen Teilaufgaben werden dazu im Ordner Chapter in einzelnen .tex Dateien bearbeitet und im Hauptverzeichnis in die Datei main.tex eingefügt. 

In der Datei test.tex wurden einige Befehle für LaTeX ausprobiert und dient als Hilfestellung für die Erstellung der main.tex mit Beispielen.


## Kompilation
Die Datei main.tex lässt sich einfach mit dem paket texlive komilieren. Um das Literaturverzeichnis und das Inhaltsverzeichnis zu generieren müssen mehrere Kompilations-Schritte durchlaufen werden.

1. Zuerst muss die main.tex mit dem Befehl pdflatex kompiliert werden.

2. Anschließend muss die die Datei main.aux mit dem Befehl Bibtex kompiliert erden.

3. Nun muss erneut die main.tex mit dem Befehl pdflatex kompiliert werden.
	
4. Zuletzt noch einmal die main.tex mit dem Befehl pdflatex kompilieren.

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

### [x] Aufgabe 1
- Erstellen des Repos, der main.tex, README.md und der Ordner für das Repo der Ausarbeitung.
- Einen Aufsatz (400 +/-25 Wörter) über Textsatzbeschreibungssprachen.

### [x] Aufgabe 2
- Einen Aufsatz schreiben über ein faszinierendes Detail aus dem Zusammenspiel von C und dem Betriebssystem (300 +/- 15 Worten)

### [x] Aufgabe 3
- Beschreibung des Konzept von Datentypen (300 +/- 15 Worten)
- Schreiben eines struct zur repräsentation einer Oszilloskopkurve
- [Repo](https://gitlab.thga.de/daniel.krueger/pruefung_sose_2023_aufgabe_3_struct)

### [x] Aufgabe 4
- Ein C Programm das über getopt ein Datum als Parameter entgegennimmt und in die Kommandozeile ausgibt um welchen Wochentag es sich handelt.
- [Repo](https://gitlab.thga.de/daniel.krueger/pruefung_sose_2023_aufgabe_4_getopt)

### [x] Aufgabe 5
- Schreiben einer Library für den Umgang mit Komplexen Zahlen
- [Repo](https://gitlab.thga.de/daniel.krueger/pruefung_sose_2023_aufgabe_5_librarys)

### [ ] Aufgabe 6
- Beschreibung des Begriffs Pointerarithmetik
- Ein Programm erstellen das die Nutzung von Pointerarithmetik exemplarishc darstellt
- [Repo](https://gitlab.thga.de/daniel.krueger/pruefung_sose_2023_aufgabe_6_pointer)

### [ ] Aufgabe 7
- Beschreibung von Streams und was diese mit Posix zu tuen haben
- Schreiben eines einfache Beispiels zum lesen und schreiben aus einem Stream
 - [Repo](https://gitlab.thga.de/daniel.krueger/pruefung_sose_2023_aufgabe_7_streams)

### [ ] Aufgabe 8
- Erstellen einer .csv,  einlesen der Daten und Ausgabe der Werte in das Terminal
- [Repo](https://gitlab.thga.de/daniel.krueger/pruefung_sose_2023_aufgabe_8_csv)#

### [ ] Aufgabe 9
- Beschreiben und Implementieren eines Algorithmus zum bestimmen der Samplingrate einer Sinusspannung
- Beschreiben und Implementieren eines Algorithmus zum bestimmen der Frequenz einer Sinusspannung 
- Beschreiben wie die Frequenz einer Rechteckspannung bestimmt werden kann
- [Repo](https://gitlab.thga.de/daniel.krueger/pruefung_sose_2023_aufgabe_9_algorithmen)

### [x] Aufgabe 10
- Beschreiben was das X11-Protokoll ist 
- Programmieren eines C-Programms dass einen Fenster öffnet 
- [Repo](https://gitlab.thga.de/daniel.krueger/pruefung_sose_2023_aufgabe_10_gui)

### [ ] Bonusaufgabe 
- Auswahl eines Programmes aus dem Repo [heirloom-project](https://github.com/ryanwoodsmall/heirloom-project/tree/musl/heirloom).
- Beschreiben und erklären des Programms Zeile für Zeile.

## To do´s 
Kleine Teilschritte die nicht direkt mit den Aufgaben zu tun haben, allerdings mit zur Ausarbeitung wie z.b. BibTex Quellenangaben usw. . Dieser Abschnitt dient nur als Hilfestellung für mich persönlich um einen Überblick über zu erledigende Aufgaben zu behalten.

- [x] BibTex einbindung testen
- [x] Aufgaben einbindung in die main.tex testen
- [x] Fehler in der Quellenangabe von Satz(Druck) beheben 
	- Der Fehler war die Angabe des Datums in .bib Datei. Alle Datums Angaben müssen in separate Felder für year, month und day eingetragen werden, damit diese richtig formatiert werden.
- [ ] Datum in die main.tex am Ende der Bearbeitung einfügen
- [ ] Formatierung der main.tex 
	- [ ] Fußzeile 
	- [ ] Kopfzeile

	Standarformat für die Fuß- und Kopfzeile verwenden?
	- [x] Abbildungsverzeichnis
	- [x] Tabellenverzeichnis
	- [x] Literaturverzeichnis 
	- [ ] Begriffsverzeichnis
- [ ] Vorwort
- [x] Stil Absätze in den Style Ordner umlagern
	- [x] Bilbliographystyle
	- [x] listingsstyle

- [ ] **README´s schreiben !!!**
## Links
Hier sind einige nützliche Links enthalten zur Bearbeitung von .tex Dateien , .md Dateien, usw. 

### Markdown (.md)

- Formatierung von .md Dateien auf [GitHub](https://docs.github.com/de/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

### Latex (.tex)

- Hilfestellungen und Anleitungen auf [Overleaf](https://www.overleaf.com/learn)

- Skript zur Verwendung von Latex von [Daniel Hommel](https://www2.hs-esslingen.de/~dhommel/skript.pdf)

- Skript zur Verwendung von Latex von [Thorsten Nagel](http://astro.uni-tuebingen.de/~nagel/pub/Kolleg/Latex/DOKU/Latexkurs_Skript.pdf)

### Makefiles
- Tutorial zu Makefiles von [C-HowTo](https://www.c-howto.de/tutorial/makefiles/)

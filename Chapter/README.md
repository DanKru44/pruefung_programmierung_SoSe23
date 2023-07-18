# Chapter
In diesem Ordner befinden sich zu allen bearbeiteten Aufgaben die zugehörigen .tex Dateien.
Diese Dateien enthalten keinen \start{document}-Befehl.

## Hinzufügen in die main.tex
Die einzelnen .tex Dateien wurden in die main.tex mit der entsprechenden Anweisung hinzugefügt.

Beispiel: `\input{Chapter/Aufgabe1.tex}`


## Aufgabenstellungen
Hier finden sich die Aufgabenstellungen der einzelnen Teilaufgaben der Ausarbeitung für das Sommersemester 2023.

### Aufgabe 1
- [x] Repo auf Gitlab der THGA anlegen
- [x] main.tex erstellen
- [x] README.md anlegen für das Hauptverzeichnis, genaue Beschreibung des Kompiliervorgangs einfügen
- [x] Ordner Images für das ablegen der Abbildungen anlegen
- [x] Ordner Chapter für die Bearbeitung der einzelnen Aufgaben anlegen
- [x] Ordner Style für Formatierungseinstellungen anlegen
- [x] Ordner Literatur für das erstellen des Quellenverzeichnisses anlegen
- [x] README.md für die Unterverzeichnisse anlegen

- [x] Schreiben eines Ausatzes von 400 +/-25 Worten.
	- [x] Beschreiben was Textsatzbeschreibungssprachen sind
	- [x] Was haben diese mit Programmiersprachen gemein
	- [x] Wie unterscheiden sie sich von Programmiersprachen
	- [x] Warum sind Textsatzbeschreibungssprachen für größere Projektdokumentationen besser geeignet als integrierte Wortprozessoren wie Word
	- [x] Begriffe die untergebracht werden sollen: 
		- [x] Ghostscript
		- [x] Groff
		- [x] Markdown
		- [x] HTML
	- [x] Abbildung für integrierte Wortprozessoren und Beispiel LaTeX vorher nachher einfügen
- [ ] Überarbeiten des Satzbaus,...

### Aufgabe 2
- [ ] Aussuchen eines Details aus Zusammenspiel von C und dem Betriebssystem (Speicherreservierung)
- [ ] Schreiben eines Aufsatzes über dieses Detail von 300 +/- 15 Worten

### Aufgabe 3
- [ ] Beschreibung des Konzeptes von Datentypen von 300 +/- 15 Worten
	- [ ] Was sind diese im Allgemeinen ?
	- [ ] Was sind diese am speziellen Beispiel von C ?
	- [ ] Welche Rolle spielen nutzerdefinierte Typen wie structs ?
	- [ ] Was macht das Keyword typedef ?

- [x] Schreiben eines structs das die Merkmale einer Oszilloskopkurve mit Metadaten, einem Kanal und einer begrenzten Länge darstellt 

[Repo](https://gitlab.thga.de/daniel.krueger/pruefung_sose_2023_aufgabe_3_struct)

### Aufgabe 4
- [x] Schreiben eines Programmes das mittels getopt ein Datum YYYY-MM-DD als Parameter entgegen nimmt und in die Kommandozeile ausgibt um welchen Wochentag es sich handelt
	- [x] Definitionsbereich YYYY-MM-DD > 2024-01-01
	- [x] Erweitern um den Definitionsbereich 1900-01-01 < YYYY-MM-DD < heute 

- [ ] Erklären wie das Programm erweiter werden müsste um all Daten bis 0000-01-01 abbilden zu können

[Repo](https://gitlab.thga.de/daniel.krueger/pruefung_sose_2023_aufgabe_4_getopt)

### Aufgabe 5
- [ ] Schreiben einer Library für den Umgang mit komplexen Zahlen
	- [ ] Die Library soll die Datentypen COMP_int und COMP_float enthalten
	- [ ] Eine Funktion die, die 2-Norm des Datenobjektes COMP_int bestimmt
	- [ ] Eine Funktion die, die 2-Norm des Datenobjektes COMP_float bestimmt
	- [ ] Eine Funktion zum addieren zweier COMP_ Elemente 
	- [ ] Eine Funktion zum printen der COMP_Elemente in Eulerform

[Repos](https://gitlab.thga.de/daniel.krueger/pruefung_sose_2023_aufgabe_5_librarys)

### Aufgabe 6
- [ ] Erklärung des Begriffs Pointerarithmetik von 300 +/- 15 Worten
	- [ ] Was ist ein Pointer?
	- [ ] Welchen Typ haben Pointer
	- [ ] Was versteht man unter dem Begriff Pointerarithmetik
	- [ ] Wie kann die Pointerarithmetik helfen Collections von Datenobjekten zu verarbeiten

- [x] Schreiben eines einfachen Programmes zur Nutzung der Pointerarithmetik 

- [ ] visualisieren des Programms mit einem Speicherdiagramm

[Repo](https://gitlab.thga.de/daniel.krueger/pruefung_sose_2023_aufgabe_6_pointer)

### Aufgabe 7 
- [ ] Erklärung zu Streams von 300 +/- 15 Wörtern
	- [ ] Was sind Streams?
	- [ ] Was haben sie mit POSIX zu tuen?

- [ ] Schreiben eines Beispiel Programms 
	- [ ] Aus einem Stream lesen
	- [ ] In einen Stream schreiben

[Repo](https://gitlab.thga.de/daniel.krueger/pruefung_sose_2023_aufgabe_7_streams)

### Aufgabe 8
- [ ] Schreiben eines Programms das eine .csv Datei verarbeitet
	- [ ] Erstellen einer .csv Datei mit beliebigem Inhalt. Drei Spalten + drei Zeilen zzgl. Kopfzeile
	- [ ] Nutzen der Library libcsv um die Datei einzulesen und in beliebigen Format in das Termial zu printen

[Repo](https://gitlab.thga.de/daniel.krueger/pruefung_sose_2023_aufgabe_8_csv)

### Aufgabe 9
In diesem [Repo](https://gitlab.thga.de/programmierung2023/example-oszi-data) befinden sich drei Oszilloskop aufnahmen von Wechselspannungen. Davon sind zwei Sinusspannungen und eine Rechteckspannung. 

- [ ] Beschreibung eines Algorithmus zum herausfinden der Samplingrate bei bekannter Frequenz
	- [ ] Implementieren des Algorithmus und herausfinden der Samplingrate der 50Hz Sinusaufnahme

- [ ] Beschreiben eines Algorithmus zum herausfinden der Frequenz bei bekannter Samplingrate
	- [ ] Implementieren des Algorithmus und herausfinden der Samplingrate der unbekannten Sinusaufnahme

- [ ] Beschreiben eines Algorithmus mit dem man die Frequenz der Aufgenommenen Rechteckspannung bestimmen kann

[Repo](https://gitlab.thga.de/daniel.krueger/pruefung_sose_2023_aufgabe_9_algorithmen)

### Aufgabe 10 
- [ ] Erklären welche Aufgabe das X11-Protokoll hat von 200 +/- 10 Worten
	- [ ] Warum spricht man hier von einem Server und einem Client?

- [x] Programmieren eines Fensters 

[Repo](https://gitlab.thga.de/daniel.krueger/pruefung_sose_2023_aufgabe_10_gui)

### Bonusaufgabe
- [x] Beschreibung des Projektes 
- [x] Anschauen des [heirloom-project](https://github.com/ryanwoodsmall/heirloom-project/tree/musl/heirloom)
- [x] Aussuchen eines der Programme: cat
- [ ] Kompilieren und Beobachtungen aufschreiben
	- [ ] Thema makefiles beschreiben
- [ ] Versuchen den Code Zeile für Zeile zu erklären 
	- [ ] Mit Abbildungen oder Diagrammen erläutern
> **Wichtig:** Die Erklärung muss nicht zu 100% korrekt sein, es geht darum zu zeigen dass man sich Mühe gibt 

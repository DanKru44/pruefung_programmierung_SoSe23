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
- [x] Überarbeiten des Satzbaus,...

### Aufgabe 2
- [x] Aussuchen eines Details aus Zusammenspiel von C und dem Betriebssystem (Speicherreservierung)
- [x] Schreiben eines Aufsatzes über dieses Detail von 300 +/- 15 Worten

### Aufgabe 3
- [x] Beschreibung des Konzeptes von Datentypen von 300 +/- 15 Worten
	- [x] Was sind diese im Allgemeinen ?
	- [x] Was sind diese am speziellen Beispiel von C ?
	- [x] Welche Rolle spielen nutzerdefinierte Typen wie structs ?
	- [x] Was macht das Keyword typedef ?

- [x] Schreiben eines structs das die Merkmale einer Oszilloskopkurve mit Metadaten, einem Kanal und einer begrenzten Länge darstellt 

[Repo](https://gitlab.thga.de/daniel.krueger/pruefung_sose_2023_aufgabe_3_struct)

### Aufgabe 4
- [x] Schreiben eines Programmes das mittels getopt ein Datum YYYY-MM-DD als Parameter entgegen nimmt und in die Kommandozeile ausgibt um welchen Wochentag es sich handelt
	- [x] Definitionsbereich YYYY-MM-DD > 2024-01-01
	- [x] Erweitern um den Definitionsbereich 1900-01-01 < YYYY-MM-DD < heute 

- [x] Erklären wie das Programm erweitert werden müsste um alle Daten bis 0000-01-01 abbilden zu können

[Repo](https://gitlab.thga.de/daniel.krueger/pruefung_sose_2023_aufgabe_4_getopt)

### Aufgabe 5
- [x] Schreiben einer Library für den Umgang mit komplexen Zahlen
	- [x] Die Library soll die Datentypen COMP_int und COMP_float enthalten
	- [x] Eine Funktion die, die 2-Norm des Datenobjektes COMP_int bestimmt
	- [x] Eine Funktion die, die 2-Norm des Datenobjektes COMP_float bestimmt
	- [x] Eine Funktion zum addieren zweier COMP_ Elemente 
	- [x] Eine Funktion zum printen der COMP_Elemente in Eulerform

optional:
- [ ] Funktion zur Ausgabe der komplexen Zahlen in kartesischer Form unter Beachtung der rechenzeichen

[Repo](https://gitlab.thga.de/daniel.krueger/pruefung_sose_2023_aufgabe_5_librarys)

### Aufgabe 6
- [x] Erklärung des Begriffs Pointerarithmetik von 300 +/- 15 Worten
	- [x] Was ist ein Pointer?
	- [x] Welchen Typ haben Pointer
	- [x] Was versteht man unter dem Begriff Pointerarithmetik
	- [x] Wie kann die Pointerarithmetik helfen Collections von Datenobjekten zu verarbeiten

- [x] Schreiben eines einfachen Programmes zur Nutzung der Pointerarithmetik 
	- [x] Zeiger auf einen einfachen Datentypen
	- [x] Zeiger im Zusammenspiel mit Arrays
	- [x] Beispiel für die Adressierung von structs einfügen

- [x] visualisieren des Programms mit einem Speicherdiagramm

[Repo](https://gitlab.thga.de/daniel.krueger/pruefung_sose_2023_aufgabe_6_pointer)

### Aufgabe 7 
- [x] Erklärung zu Streams von 300 +/- 15 Wörtern
	- [x] Was sind Streams?
	- [x] Was haben sie mit POSIX zu tuen?

- [x] Schreiben eines Beispiel Programms 
	- [x] Aus einem Stream lesen
	- [x] In einen Stream schreiben

[Repo](https://gitlab.thga.de/daniel.krueger/pruefung_sose_2023_aufgabe_7_streams)

### Aufgabe 8
- [x] Schreiben eines Programms das eine .csv Datei verarbeitet
	- [x] Erstellen einer .csv Datei mit beliebigem Inhalt. Drei Spalten + drei Zeilen zzgl. Kopfzeile
	- [x] Nutzen der Library libcsv um die Datei einzulesen und in beliebigen Format in das Termial zu printen

[Repo](https://gitlab.thga.de/daniel.krueger/pruefung_sose_2023_aufgabe_8_csv)

### Aufgabe 9
In diesem [Repo](https://gitlab.thga.de/programmierung2023/example-oszi-data) befinden sich drei Oszilloskop aufnahmen von Wechselspannungen. Davon sind zwei Sinusspannungen und eine Rechteckspannung. 

- [x] Beschreibung eines Algorithmus zum herausfinden der Samplingrate bei bekannter Frequenz
	- [x] Implementieren des Algorithmus und herausfinden der Samplingrate der 50Hz Sinusaufnahme

- [x] Beschreiben eines Algorithmus zum herausfinden der Frequenz bei bekannter Samplingrate
	- [ ] Implementieren des Algorithmus und herausfinden der Samplingrate der unbekannten Sinusaufnahme

- [x] Beschreiben eines Algorithmus mit dem man die Frequenz der Aufgenommenen Rechteckspannung bestimmen kann

[Repo](https://gitlab.thga.de/daniel.krueger/pruefung_sose_2023_aufgabe_9_algorithmen)

### Aufgabe 10 
- [x] Erklären welche Aufgabe das X11-Protokoll hat von 200 +/- 10 Worten
	- [x] Warum spricht man hier von einem Server und einem Client?

- [x] Programmieren eines Fensters 

[Repo](https://gitlab.thga.de/daniel.krueger/pruefung_sose_2023_aufgabe_10_gui)

### Bonusaufgabe
- [x] Beschreibung des Projektes 
- [x] Anschauen des [heirloom-project](https://github.com/ryanwoodsmall/heirloom-project/tree/musl/heirloom)
- [x] Aussuchen eines der Programme: cat
- [x] Kompilieren und Beobachtungen aufschreiben
	- [x] Thema makefiles beschreiben
- [x] Versuchen den Code Zeile für Zeile zu erklären 
	- [x] Mit Abbildungen oder Diagrammen erläutern
> **Wichtig:** Die Erklärung muss nicht zu 100% korrekt sein, es geht darum zu zeigen dass man sich Mühe gibt 

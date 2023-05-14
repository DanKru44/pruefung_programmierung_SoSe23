# Literatur 
In diesem Ordner befindet sich die BibTeX-Datei die für das Quellenverzeichnis der Ausarbeitung verwendet wird. In ihr sind alle Quellen genannt die für die Bearbeitung der Aufgaben genutzt wurden.  

## Einfügen in die main.tex
Dieser Anschnitt dient dazu mir persönlich die Befehle zum einbinden des Literaturverzeichnisses in die main.tex zu verdeutlichen. Ich kann somit einfach einen Überblick über die nötigen Befehle erhalten um die Einbindung und die Formatierung zu gewinnen.

- Benutztes Paket: Verwendet wurde das Paket natbib (vor \begin{document})

	Beispiel: `\usepackage{natbib}`

- Der Stil des Literaturverzeichnisses ist natdin (vor \begin{document})

	Beispiel:`\bibliographystyle{natdin}`

- Der Stil der Literaturangaben ist Autor und Jahr in Klammern (vor \begin{document})

	Beispiel: `\setcitestyle{authoryear, open={(},close={)}}`	

- Ausgabe des Literaturverzeichnisses (nach \begin{document **und direkt vor** \end{document}.

	Beispiel:`\bibliography{Literatur/literatur}` 

	Das Argument in den geschweiften Klammern ist dabei die angabe des Ordners Literatur und die darin befindliche Datei literatur.bib . Diese wird allerdings ohne die Endung .bib angegeben.

## Zitieren 
Eine Anleitung zu den Befehlen mit denen in den Aufgaben zitiert werden können. Diese dienen zur formatierung der Zitate im Text.

- Um den Autor und das Jahr in Klammern zu zitieren wird der Befehl citep genutzt.

	Beispiel: `\citep{Name der Quellenangabe in der literatur.bib}`

- Soll eine Quellenangabe mit ins Literaturverzeichnis, die nicht direkt zitiert wurde wird der Befehl nocite benutzt.	

	Beispiel: `\nocite{Name der Quellenangabe in der literatur.bib}`

## Formate in der .bib Datei
Überblick über Quellenangaben und deren Formatierung in der .bib Datei

- Webseiten
	Benötigt Angaben sind author, title, howpublished und year. Zusätzlich könne month und day angegeben werden.
	Beispiel:
	´´´
	@misc{Krüger:2023,
	author		 = {Daniel Krüger},
	title		 = {Hausarbeit Programmierung},
	howpublished = {\url{https://gitlab.thga.de/daniel.krueger/pruefung_sose_2023}},
	year		 = {2023},
	month		 = {05},
	day			 = {14}
	}
	´´´

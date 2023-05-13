# Literatur 
In diesem Ordner befindet sich die BibTeX-Datei die für das Quellenverzeichnis der Ausarbeitung verwendet wird. In ihr sind alle Quellen genannt die für die Bearbeitung der Aufgaben genutzt wurden.  

## Einfügen in die main.tex
Dieser Anschnitt dient dazu mir persönlich die Befehle zum einbinden des Literaturverzeichnisses in die main.tex zu verdeutlichen. Ich kann somit einfach einen Überblick über die nötigen Befehle erhalten um die Einbindung und die Formatierung zu gewinnen.

- Benutztes Paket: Verwendet wurde das Paket natbib (vor \begin{document})
	Beispiel: `\usepackage{natbib}

- Der Stil des Literaturverzeichnisses ist natdin (vor \begin{document})
	Beispiel:`bibliographystyle{natdin}

- Ausgabe des Literaturverzeichnisses (nach \begin{document **und direkt vor** \end{document}.
	Beispiel:`bibliography{Literatur/literatur}` 

	Das Argument in den geschweiften Klammern ist dabei die angabe des Ordners Literatur und die darin befindliche Datei literatur.bib . Diese wird allerdings ohne die Endung .bib angegeben.

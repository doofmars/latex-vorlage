## Erweitere Latex-Vorlage

Dies ist eine erweitere Latex Vorlage.
Sie basiert auf der Vorlage von Fabian Berner
und wurde im Rahmen meiner Thesis um Funktionen 
erweitert die ich für die Arbeit für sinnvoll erachtet habe.
Die original Version kann unter folgender Adresse abgerufen werden:
[LaTeX Vorlage](http://webuser.hs-furtwangen.de/~berner/wa.html)


Funktionen:

+ Quellcodeverzeichnis
+ Veränderte Verzeichnis-Struktur
+ Dateistruktur beginnend mit Zahlen zur Sortierung des Quellcodes
+ Abgeänderte Nummerierung im Inhaltsverzeichnis
+ Gitignore für Latex und TMP-Ordner
+ Vorbereitung zum Einsatz in [Texlipse](http://texlipse.sourceforge.net/)
+ Angepasste Code-Darstellung

### Verzeichnisstruktur 

├─README.MD  
├─.gitignore  
├─*document_BUILD.pdf* (generierte LaTeX Pdf von Texlipse)  
└─── src  
&ensp;├── main.tex (Hauptdatei)  
&ensp;├── preamble.tex (Konfiguration)  
&ensp;├── bibtex.bib (Quellen)  
&ensp;└── content (Beinhaltet die Kapitel)  
&ensp;&ensp;├── 0_introduction.tex  
&ensp;&ensp;├── 1_basics.tex  
&ensp;&ensp;├── 2-7_custom_chapter.tex  
&ensp;&ensp;├── 8_prospect.tex  
&ensp;&ensp;├── 9_conclusion.tex  
&ensp;&ensp;├── code  
&ensp;&ensp;|&ensp;└── example.java  
&ensp;&ensp;├── pictures  
&ensp;&ensp;|&ensp;└── hfu.jp  
&ensp;&ensp;└─── framework  
&ensp;&ensp;&ensp;├── abbreviations.tex (Abkürzungen)  
&ensp;&ensp;&ensp;├── abstract.tex (Abstract)  
&ensp;&ensp;&ensp;└── title.tex (Deckblatt)  

Über Ergänzungen in Form eines Pull-Requests freue ich mich.
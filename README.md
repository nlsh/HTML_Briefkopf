# HTML Briefköpfe

Ja, einen Briefkopf zu erstellen und diesen dann in jedem Programm nutzen zu können,
ist ein Traum. Ein wunderschöner Traum.

Man denkt sich dann, mach einen Dummy- Briefkopf in irgendeiner universellen Sprache fertig und gut.

Aber, was ist eine universelle Sprache (HTML, XHTML, LATEX, XML)? Alles Sprachen, die 
vollständig standardisiert sind, aber irgendwie doch nicht zusammenfinden.

Da jeder Internet hat, es auch wirklich jeder benutzt und gefühlt jedes Programm HTML- Lesen kann, kein Problem, nimm HTML.

Es ist aber ein Alptraum! Jedes Programm versteht nur das, was es will und nicht das, was laut [http://w3.org](http://w3.org) Standard ist.

Der erste Versuch in HTM5 überzeugt zwar in jedem Browser ein ordentliche und 
gewünschtes Ergebnis, aber in jedem Mail- Programm eine Katastrophe.
Beim Erstellen ist noch alles ok, aber beim Empfänger kommt was vollständig falsches an.

Thunderbird schmeisst den ganzen `<head>`- Tag raus, somit kann man keine Fonts nachladen, oder mittels `<styles>` dezentral per CSS die Ausgabe anpassen, `<div>``s floaten zu lassen, wird beim Empfänger komplett ignoriert (bestimmt eine Sicherheitssache, **FLOAT im CSS ist GEFÄHRLICH!!!!**).

ALso, zurück zu den Anfängen von HTM, `<table>`- Tabellen sind wohl hier die richtige Wahl, die kennt selbst der IE noch. ;-)
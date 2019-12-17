# home-codeingStandardsRefactoring-esevignani
Ausarbeitung Refactoring:

Refactoring ist, wenn man fertigen, funktionierenden Code nochmal überarbeitet damit er nicht mehr smelled. Das soll den Code verständlicher machen, damit ihn auch andere Leute verstehen können, die den Code noch nicht kennen. 

Vorteile: macht zukünftiges Überarbeiten einfacher, andere Leute können den Code verstehen

Nachteil: kostet Zeit

Prinzipien von gutem Code: 
Single-Responsibility-Prinzip: eine Klasse erfüllt nur eine Aufgabe

Open-Closed-Prinzip: das Verhalten einer Klasse darf erweitert, aber nicht verändert werden

Liskovsches Substitutionsprinzip: abgeleitete Klassen müssen immer anstelle ihrer Basisklassen einsetzbar sein

Interface-Segregation-Prinzip: ein Interface darf nur Komponenten beinhalten die eng zusammen gehören

Dependency-Inversion-Prinzip: es soll keine Abhängigkeit zwischen Klassen bestehen

KISS: keep it simple stupid

YAGNI: you aint gonna need it


Code Smell: Probleme im Code, die refactored werden müssen

Besipiele für Code Smell: 

zu lange Methode- länger als 25 Zeilen
Magic String- Zeichenfolge die nicht definiert wurde 
Magic Value - Bedeutung nicht unmittelbar erkennbar 
keine Kommentare - keine Erklärungen zum Code
duplizierter Code- derselbe Code kommt an mehreren Stellen vor
faule Klasse- Klasse ist zu klein, bringt zu wenig 
zu große Klasse- Klasse zu umfangreich, enthält duplizierten Code
Feature Envy- Methode interessiert sich mehr für eine andere Klasse als die eigene 
unnötige Lehrzeichen, Leerzeilen- verlängern den Code 
Datenklumpen: Objekte kommen immer zusammen vor

Refactoring-Schritte:

1)Testfall definieren
2)sicherstellen, dass das Programm funktioniert
3)einen einzigen Code Smell ausbessern 
4)ausprobieren ob das Programm noch funktioniert 
5)Commit
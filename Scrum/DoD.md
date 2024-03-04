# <u> Definition of Done </u>
Die Definition of Done ist eine Ansammlung von Kriterien, der definiert, wann eine Aufgabe als abgeschlossen gilt.  
Diese enthält typischerweise Aspekte wie Funktionalität, Code-Qualität, Tests, Dokumentation und Bereitstellungsvorbereitung.

# 1 Funktionalität
* alle Akzeptanzkriterien sind erfüllt
* alle funktionalen Tests wurden durchgeführt
* wurde einem anderen Team Miedglied vorgestellt

# 2 Dokumentation
Hier werden Dokumente genannt, die erstellt werden müssen.
* **Klassenbasierende Programmierung** - UML vor der Umsetzung
* **Projektdokumentation** - Anpassung/Aktualisierung der Dokumentation

# 3 Code Qualität
Hier werden standards für die Code Qualtät kurz angebrochen, welche einzuhalten sind, damit die Task als beendet bezeichnet werden darf.

## <u> 3.1 Klassenbasierte Entwicklung </u>
### Allgemein
Pro Datei eine Klasse. Die Datei ist gleichnamig nicht der Klasse.

### Sichtbarkeiten
* (Alle) Eigenschaften: **private**
* (meisten) Methoden: **public**

### Struktur
Es sind für jede Eigenschaft, falls Sinnvoll, **Getter** & **Setter** zu schreiben.

Bei Überschneidungen der Eigenschaften und Funktionen von anderen Klassen, wird eine Basisklasse entworfen, von der geerbt wird.

## <u> 3.2 Style </u>
Am Ende der Task wird der Autoformatter verwendet. Daraufhin werden, falls entstanden, Errors behoben.

## <u> 3.3 Umfang </u>
Eine Datei sollte nicht mehr als ca. einhundert Zeilen umfassen. Falls dies als notwendig angesehen wird, wird der Project Owner dazugezogen.
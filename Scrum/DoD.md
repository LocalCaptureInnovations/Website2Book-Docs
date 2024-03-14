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
Hier werden Standards für die Code Qualtät erläutert, welche einzuhalten sind, damit die Task beendet werden darf.

## <u> 3.1 Klassenbasierte Entwicklung </u>
### Allgemein
Pro Datei eine Klasse. Die Datei ist gleichnamig mit der Klasse.

### Sichtbarkeiten
* (Meisten) Eigenschaften: **private**
* (Meisten) Methoden: **public**

### Struktur
Falls das Produkt an flexibilität und er
Es sind **Getter** und **Setter** Methoden für jede Eigenschaft bereitzustellen, bei der dies den Wert des Produktes steigert. Unter anderen ist darunter zu verstehen, dass die Erweiterbarkeit und Flexibilität verbessert wird.

## <u> 3.2 Style </u>
Am Ende der Task wird der Autoformatter verwendet. Daraufhin werden, falls entstanden, Errors behoben und der Import auf entstandene Fehler überprüft.

## <u> 3.3 Umfang </u>
Eine Datei umfasst nicht mehr als eine Klasse. Diese kann ein **Handler** von übergeordneten Klassen sein, order einer dieser Klassen sein.

Eine Datei sollte nicht mehr als ca. einhundertzwanzig Zeilen umfassen. Falls dies als notwendig angesehen wird, wird der Project Owner dazugezogen.

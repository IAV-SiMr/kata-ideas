# [Ideen für Coding Katas](README.md)

## Extrem

1. **Goldbachs Vermutung**
   - Die Funktion erhält eine gerade positive ganze Zahl n als Eingabe.
   - Die Funktion gibt eine Liste von zwei Primzahlen zurück, deren Summe n ergibt.
   - Die Funktion gibt `null` zurück, wenn es keine solche Kombination von Primzahlen gibt.
   - Die Funktion muss eine effiziente Lösung implementieren.
   - Die Goldbachs Vermutung ist noch nicht bewiesen, daher gibt es keinen allgemeinen Algorithmus, um die Kombination zu finden.

2. **Fünfzehn Puzzle**
   - Die Funktion erhält ein 4x4-Schiebepuzzle als Eingabe.
   - Das Schiebepuzzle enthält Zahlen von 1 bis 15 auf einem 4x4-Gitter und ein leeres Feld.
   - Die Funktion gibt eine Sequenz von Zügen zurück, um das Puzzle zu lösen.
   - Das Puzzle muss auf eine Zielform gebracht werden, bei der die Zahlen in aufsteigender Reihenfolge angeordnet sind und das leere Feld unten rechts ist.
   - Das Fünfzehn Puzzle ist bekannt dafür, dass es in einigen Konfigurationen unlösbar ist.

3. **Collatz-Vermutung**
   - Die Funktion erhält eine positive ganze Zahl n als Eingabe.
   - Die Funktion gibt die Anzahl der Schritte zurück, die benötigt werden, um die Collatz-Folge von n zu erreichen.
   - Die Collatz-Folge für eine Zahl n ist definiert als: n -> n/2 (für gerade n) oder n -> 3n + 1 (für ungerade n).
   - Die Funktion sollte die Laufzeit- und Speicheranforderungen optimieren.
   - Die Collatz-Vermutung besagt, dass die Folge für jede positive ganze Zahl n immer bei 1 endet, jedoch wurde dies noch nicht bewiesen.

4. **Cheryl's Geburtstagsproblem**
   - Die Funktion erhält eine Liste von möglichen Geburtstagen und Informationen, die Cheryl ihren Freunden gibt.
   - Die Funktion gibt den korrekten Geburtstag von Cheryl basierend auf den gegebenen Informationen zurück.
   - Die Informationen beinhalten, dass Cheryl ihren Freunden den Monat und den Tag ihres Geburtstags in unterschiedlichen Kombinationen nennt.
   - Das Cheryl's Geburtstagsproblem wurde als Logikrätsel entworfen und erfordert logisches Denken, um die richtige Lösung zu finden.

5. **Euler-Kreis**
   - Die Funktion erhält einen ungerichteten Graphen als Eingabe.
   - Der Graph kann mehrere Komponenten haben, aber jede Komponente muss einen Euler-Kreis haben.
   - Die Funktion gibt einen Euler-Kreis für den gegebenen Graphen zurück.
   - Ein Euler-Kreis ist ein geschlossener Pfad, der jede Kante im Graphen genau einmal durchläuft.
   - Die Funktion gibt `null` zurück, wenn kein Euler-Kreis existiert oder der Graph nicht zusammenhängend ist.

6. **Perfect Hash Function**
   - Die Funktion erhält eine Liste von Schlüsseln als Eingabe.
   - Die Funktion gibt eine perfekte Hashfunktion zurück, die die Schlüssel ohne Kollisionen hashen kann.
   - Eine perfekte Hashfunktion weist jedem Schlüssel einen eindeutigen Hash-Wert zu.
   - Die Funktion sollte eine effiziente Lösung implementieren.
   - Das Finden einer perfekten Hashfunktion für eine gegebene Schlüsselliste ist ein NP-schweres Problem.

7. **NP-vollständiges Problem**
   - Die Funktion erhält eine Eingabe für ein NP-vollständiges Problem.
   - Die Funktion gibt eine Lösung für das Problem zurück.
   - NP-vollständige Probleme sind eine Klasse von Problemen, bei denen keine effiziente Lösung bekannt ist.
   - Die Funktion sollte eine exakte oder approximative Lösung implementieren.
   - Beispiele für NP-vollständige Probleme sind Rucksackproblem, TSP, Knapsack Problem, etc.

8. **Busy Beaver Problem**
   - Die Funktion erhält eine positive ganze Zahl n als Eingabe.
   - Die Funktion gibt das maximale Ergebnis zurück, das ein Busy Beaver-Programm mit n Zuständen erzielen kann.
   - Ein Busy Beaver-Programm ist ein Turing-Maschinenprogramm, das eine maximale Anzahl von Schritten ausführt, bevor es stoppt.
   - Die Funktion muss alle möglichen Programme mit n Zuständen überprüfen, um das Maximum zu finden.
   - Das Busy Beaver Problem ist unentscheidbar und es gibt keine allgemeine Lösung für beliebige n.

9. **Königsberger Brückenproblem**
   - Die Funktion erhält einen ungerichteten Graphen, der die Stadt Königsberg und ihre Brücken repräsentiert.
   - Die Funktion gibt `true` zurück, wenn es einen Rundweg durch die Stadt gibt, der jede Brücke genau einmal überquert.
   - Die Funktion gibt `false` zurück, wenn ein solcher Rundweg nicht existiert.
   - Das Königsberger Brückenproblem wurde von Euler formuliert und als erstes Beispiel für ein ungelöstes mathematisches Problem betrachtet.
   - Das Problem erfordert eine geschickte Anwendung von Graphentheorie, um die Lösung zu finden.

10. **Four Color Theorem**
    - Die Funktion erhält eine Landkarte mit Regionen als Eingabe.
    - Die Funktion gibt eine Zuordnung von Farben zu den Regionen zurück, sodass benachbarte Regionen unterschiedliche Farben haben.
    - Die Funktion muss das Four Color Theorem erfüllen, das besagt, dass vier Farben ausreichen, um jede Landkarte korrekt zu färben.
    - Die Funktion sollte eine effiziente Lösung implementieren.
    - Das Four Color Theorem wurde lange Zeit als eines der schwierigsten mathematischen Probleme angesehen und wurde erst 1976 vollständig bewiesen.

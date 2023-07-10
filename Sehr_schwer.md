# [Ideen für Coding Katas](README.md)

## Sehr schwer

1. **Optimale Matrixketten-Multiplikation**
   - Die Funktion erhält eine Liste von Matrizen mit ihren Dimensionen als Eingabe.
   - Die Funktion gibt die optimale Reihenfolge der Matrixmultiplikationen zurück.
   - Die Funktion gibt die minimale Anzahl der Skalarprodukt-Operationen zurück, um alle Matrizen zu multiplizieren.
   - Die Funktion muss den Algorithmus von Chain Matrix Multiplication verwenden.
   - Die Funktion gibt eine leere Liste zurück, wenn die Eingabeliste leer ist.

2. **Maximum Independent Set**
   - Die Funktion erhält einen ungerichteten Graphen als Eingabe.
   - Die Funktion gibt das maximale unabhängige Set des Graphen zurück.
   - Das unabhängige Set ist eine Teilmenge von Knoten, in der keine zwei Knoten direkt verbunden sind.
   - Die Funktion muss den Bron-Kerbosch-Algorithmus oder einen ähnlichen Algorithmus verwenden.
   - Die Funktion gibt eine leere Liste zurück, wenn der Graph leer ist.

3. **Langste gemeinsame Teilsequenz**
   - Die Funktion erhält zwei Strings als Eingabe.
   - Die Funktion gibt die längste gemeinsame Teilsequenz der beiden Strings zurück.
   - Die Funktion gibt eine leere Zeichenkette zurück, wenn keine gemeinsame Teilsequenz existiert.
   - Die Funktion muss eine effiziente dynamische Programmierungslösung implementieren.
   - Die Funktion sollte die Laufzeit- und Speicheranforderungen optimieren.

4. **Reisenderverkaufsproblem mit Time Windows**
   - Die Funktion erhält einen gerichteten gewichteten Graphen mit Zeitfenstern und einen Startknoten als Eingabe.
   - Die Funktion gibt den optimalen Rundreisepfad des Handlungsreisenden zurück, der alle Knoten besucht und die Zeitfenster einhält.
   - Die Funktion muss eine effiziente dynamische Programmierungslösung implementieren.
   - Die Funktion gibt `null` zurück, wenn kein Rundreisepfad existiert.
   - Die Funktion sollte die Laufzeit- und Speicheranforderungen optimieren.

5. **Steinerbaumproblem**
   - Die Funktion erhält einen ungerichteten gewichteten Graphen und eine Menge von Terminals als Eingabe.
   - Die Funktion gibt den minimalen Steinerbaum zurück, der alle Terminals verbindet.
   - Der Steinerbaum kann zusätzliche Knoten enthalten, um die Terminals zu verbinden.
   - Die Funktion muss den Algorithmus von Viterbi oder einen ähnlichen Algorithmus verwenden.
   - Die Funktion gibt `null` zurück, wenn kein Steinerbaum existiert.

6. **Maximalplanarität**
   - Die Funktion erhält einen ungerichteten Graphen als Eingabe.
   - Die Funktion gibt die maximale Anzahl von Kanten zurück, die hinzugefügt werden können, um den Graphen planar zu machen.
   - Der planare Graph enthält keine Kreuze zwischen Kanten.
   - Die Funktion muss den Algorithmus von Hopcroft und Tarjan verwenden.
   - Die Funktion gibt 0 zurück, wenn der Graph bereits planar ist.

7. **Kleinster umspannender Baum mit Knotengewichten**
   - Die Funktion erhält einen ungerichteten gewichteten Graphen mit Knotengewichten als Eingabe.
   - Die Funktion gibt den kleinsten umspannenden Baum zurück, der alle Knoten enthält.
   - Der umspannende Baum minimiert die Summe der Kanten- und Knotengewichte.
   - Die Funktion muss den Algorithmus von Boruvka oder einen ähnlichen Algorithmus verwenden.
   - Die Funktion gibt `null` zurück, wenn der Graph leer ist.

8. **3-SAT-Problem**
   - Die Funktion erhält eine aussagenlogische Formel in 3-KNF als Eingabe.
   - Die Funktion gibt `true` zurück, wenn die Formel erfüllbar ist.
   - Die Funktion gibt `false` zurück, wenn die Formel nicht erfüllbar ist.
   - Die Funktion muss den Algorithmus von Davis-Putnam-Logemann-Loveland (DPLL) verwenden.
   - Die Funktion sollte die Laufzeit- und Speicheranforderungen optimieren.

9. **Kürzeste nichttriviale Knotenüberdeckung**
   - Die Funktion erhält einen ungerichteten Graphen als Eingabe.
   - Die Funktion gibt die kürzeste nichttriviale Knotenüberdeckung des Graphen zurück.
   - Die Knotenüberdeckung ist eine Teilmenge von Knoten, die jede Kante im Graphen abdeckt.
   - Die Funktion muss den Algorithmus von König oder einen ähnlichen Algorithmus verwenden.
   - Die Funktion gibt eine leere Liste zurück, wenn der Graph leer ist.

10. **Steigungsnetzwerk**
    - Die Funktion erhält einen gerichteten Graphen mit positiven Kantengewichten als Eingabe.
    - Die Funktion gibt das maximale Steigungsnetzwerk des Graphen zurück.
    - Das Steigungsnetzwerk maximiert die Summe der Steigungen aller Pfade im Graphen.
    - Die Funktion muss den Algorithmus von Edmonds oder einen ähnlichen Algorithmus verwenden.
    - Die Funktion gibt eine leere Liste zurück, wenn der Graph leer ist.

# Projectkeuze

## Groepsleden - Klas

Arno Bruynseels - 3AONd

## Taalkeuze

Java

## Code Repository

https://github.com/miga9/sudoku-solver-java

## Beschrijving Algoritme

De sudokusolver maakt gebruik van het backtracking algoritme.

Uitleg: Het algoritme maakt begruikt van recursie (methode die zichzelf aanroept) en backtracking.

1)	Check of elke cel is opgelost, het einde van de sudoku is bereikt

Ja : einde algoritme, sudoku is opgelsot
Neen: Stap 2

2)	Check of de cell al een preset was of een waarde bevat

Ja : Ga naar voglende cell, door zichtzelf aan te roepen met de voglende celwaarde
Neen: Stap 3

3)	Maak een lijst aan met cijfers aan van 1 t.e.m. 9 en shud deze door elkaar. (Schudden niet noodzakelijk)

4)	Ga elk nummer in deze lijst af en test of het gekozen nummer niet voorkomt en de 3x3box, rij en kollom. 

Lukt : Vul dit nummer in de cel in en ga naar voglende cell door zichzelf aan te roepen met de volgende celwaarde.
Faalt: Stap 5

5)	Als er geen waarde in de lijst met nummers van 1-9 gevonden wordt dat klopt is de sudoku wordt de huidige celwaarde op 0 gezet. Vanwege recursie wordt er dan aan backtracking gedaan, wat wil zegge dat er terug naar de vorige cel wordt gegaan en een andere waarde probeert te vinden die ook klopt. (Dit kan terug gaan tot de begincel en helemaal opnieuw beginnen)



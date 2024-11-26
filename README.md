# Arrays-14---Extra-oefeningen

## Basis

### 1. **ToArray Methode**
Schrijf een methode, `ToArray(int a, int b)`, die twee integere getallen neemt als input en deze in een array van lengte twee teruggeeft als resultaat.

---

### 2. **Array van Integers naar Floats**
Schrijf een methode die een array van integere getallen converteert naar een array van floats.

**Voorbeeld:**

```
	> Input
	[1,2,3,4]
	> Output
	[1f,2f,3f,4f]
```


---

### 3. **Array van Strings naar doubles**
Schrijf een methode die een array van stringwaardes converteert naar een array van doubles. Indien er een waarde in de input zit die niet geconverteerd kan worden naar een double, geeft de methode een `FormatException`.

**Voorbeeld:**
```
	> Input
	["1","2","3","4"]
	> Output
	[1.0,2.0,3.0,4.0]
```


---

### 4. **Controleer of Alle Elementen Gelijk zijn**
Schrijf een methode, `AreAllEqual(int[] reeks)`, die controleert of alle elementen in de array gelijk zijn aan elkaar. Wanneer minstens één element verschilt, geeft deze methode `false` terug.

---

### 5. **Controleer of de Array Gesorteerd is**
Schrijf een methode, `IsSorted(int[] reeks)`, die controleert of alle elementen in de array gesorteerd zijn van klein naar groot.

---

## Advanced

### 6. **Meest Voorkomend Element**
Schrijf een methode, `MostFrequent(string[] woorden)`, die het element uit de array `woorden` teruggeeft dat het meest voorkomt en het meest vooraan staat in de array.

**Voorbeeld:**
```
	> Input
	["1","2","3","4"]
	> Output
	[1.0,2.0,3.0,4.0]
```


---

### 7. **Pseudo-Willekeurige Array**
Onze programma’s zijn nooit 100% willekeurig, maar we kunnen pseudo-random resultaten genereren. Probeer zelf een implementatie te verzinnen om een array in een willekeurige volgorde te zetten.

Schrijf een methode, `MakeRandom(int[] reeks)`, die de getallen in de input array willekeurig door elkaar mixt.

---

### 8. **Grootste verschil**
Schrijf een methode, `LargestDifference(int[] reeks)`, die het verschil teruggeeft tussen het kleinste en grootste element in de reeks.

---

## Hulpfuncties

Gebruik de array `stadiaGames` om de volgende oefeningen op te lossen. Maak vervolgens gebruik van de array-hulpfuncties om de vragen te beantwoorden.

### 9. **Vind de index**
Schrijf een programma om te achterhalen wat de index is van "Risk of Rain 2" in de array van stadiaGames. Druk de index af.

### 10. **Sorteer alfabetisch aflopend**
Schrijf een programma dat de array stadiaGames sorteert in alfabetisch aflopende volgorde. Welke positie heeft "Risk of Rain 2" dan in de array?

### 11. **Filter op tekst**
Schrijf een programma dat elk element in een kopie van de stadiaGames array verandert naar een lege string, als het element in de array niet de tekst "Assassin" bevat. Hoeveel niet lege string elementen blijven er over?

### 12. **Verwijder de eerste helft**
Schrijf een programma dat de eerste helft van de oorspronkelijke stadiaGames array verwijdert. Print vervolgens elk element van de array af.

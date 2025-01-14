## Frage 1
Welche der folgenden Aussagen beschreibt eine Precondition in "Design by Contract" korrekt?
- [ ] Sie definiert die möglichen Rückgabewerte einer Funktion.
- [ ] Sie beschreibt die Auswirkungen der Funktion auf den Zustand der Welt.
- [ ] Sie definiert die Anforderungen, die vor der Ausführung der Funktion erfüllt sein müssen.
- [ ] Sie beschreibt Invarianten, die während der Programmausführung unverändert bleiben.

---

## Frage 2
Was ist eine der Hauptaufgaben eines Interfaces?
- [ ] Sicherzustellen, dass alle Module denselben Code verwenden.
- [ ] Eine klare Trennung zwischen Nutzung und Implementierung bereitzustellen.
- [ ] Alle möglichen Rückgabewerte einer Funktion zu definieren.
- [ ] Zu verhindern, dass verschiedene Module miteinander kommunizieren.

---

## Frage 3
Was bedeutet es, eine Postcondition zu stärken?
- [ ] Die Anzahl der akzeptablen Eingaben zu erhöhen.
- [ ] Die Anforderungen an die Eingaben zu lockern.
- [ ] Den Bereich der garantierten Rückgabewerte zu verringern.
- [ ] Zusätzliche Precondition-Anforderungen hinzuzufügen.

---

## Frage 4
Welche Eigenschaft sollte ein Modul haben, um als "modular" zu gelten?
- [ ] Es sollte möglichst viele globale Variablen verwenden.
- [ ] Es sollte keine Kommunikation mit anderen Modulen erlauben.
- [ ] Es sollte keine Precondition benötigen.
- [ ] Es sollte selbstständig und durch präzise Schnittstellen verbunden sein.

---

## Frage 5
Welches Ziel wird durch die Schwächung einer Precondition erreicht?
- [ ] Weniger Implementierungen zu erlauben.
- [ ] Den garantierten Bereich von Rückgabewerten zu verringern.
- [ ] Die Anzahl der Rückgabewerte zu erhöhen.
- [ ] Eine Funktion für mehr mögliche Eingabewerte nutzbar zu machen.

---

## Frage 6
Was wird durch eine Invariante im Kontext von Design by Contract beschrieben?
- [ ] Bedingungen, die vor und nach einer Funktion erfüllt sein müssen.
- [ ] Zusicherungen über Rückgabewerte.
- [ ] Eigenschaften, die während der gesamten Programmausführung unverändert bleiben.
- [ ] Anforderungen an die Eingaben einer Funktion.

---

## Frage 7
Gegeben ist folgender Scala-Code:

```scala
def sumOverDoubledList(lst: Array[Int]): Int = {
    var result: Int = 0
    val doubledList: Array[Int] = lst.map(x => 2 * x)
    for (i <- doubledList) {
      result += i
    }
    result
  }
```

1. Beschreiben Sie einen Contract für diese Funktion als Kommentar direkt im Code. (Kein require oder ensuring nötig.)
2. Gilt hier weakest precondition/strongest postcondition?

# Quiz: Testen und Designprinzipien

---

## **Frage 1: Was ist das Hauptziel von Unit-Tests?**
-[ ] Das gesamte System integriert testen.  
-[ ] Herausfinden, wie der Benutzer mit der Schnittstelle interagiert.  
-[ ] Die Leistung unter hoher Belastung testen.  
-[ ] Einzelne Komponenten oder Funktionen isoliert testen.  

---

## **Frage 2: Worauf konzentriert sich "Black Box Testing"?**
-[ ] Testen anhand einer Spezifikation, ohne die interne Struktur zu kennen.  
-[ ] Testen der internen Strukturen oder Logik des Codes.  
-[ ] Messen der Leistung und Belastbarkeit des Systems.  
-[ ] Simulieren der Benutzeroberfläche zur Analyse des Verhaltens.  

---

## **Frage 3: Welches der folgenden Beispiele beschreibt "Grenzfalltests" (Boundary Testing)?**
-[ ] Testen mit zufällig ausgewählten Eingaben aus einem gültigen Bereich.  
-[ ] Testen an den Rändern der gültigen Eingabebereiche, z. B. 0, -1, Maximalwert.  
-[ ] Erschöpfendes Testen jeder möglichen Eingabewerte.  
-[ ] Testen mit Eingaben, die nicht mit den Spezifikationen zusammenhängen.  

---

## **Frage 4: Was ist ein Schlüsselkonzept des Single Responsibility Principle (SRP)?**
-[ ] Eine Klasse sollte mehrere Verantwortlichkeiten haben, um flexibel zu sein.  
-[ ] Eine Klasse sollte Vererbung gegenüber Komposition priorisieren.  
-[ ] Eine Klasse sollte so wenige Methoden wie möglich enthalten.  
-[ ] Eine Klasse sollte nur einen Grund für eine Änderung haben.  

---

## **Frage 5: Welches Problem entsteht, wenn das SRP verletzt wird?**
-[ ] Der Code wird zu kohäsiv.  
-[ ] Der Code hat mehrere Gründe für Änderungen.  
-[ ] Debugging wird einfacher.  
-[ ] Dependency Injection kann nicht angewendet werden.  

---

## **Frage 6: Wie beeinflusst das Open-Closed Principle die Softwarearchitektur?**
-[ ] Ein Modul sollte offen für Erweiterungen, aber geschlossen für Änderungen sein.  
-[ ] Ein Modul sollte immer bearbeitbar sein, um anpassungsfähig zu bleiben.  
-[ ] Ein Modul sollte Abstraktionen vermeiden, um die Entwicklung zu beschleunigen.  
-[ ] Ein Modul sollte Laufzeitänderungen gegenüber Kompilierungszeit-Sicherheit priorisieren.  

---

## **Frage 7: Warum sollten Module häufige Änderungen vermeiden?**
-[ ] Es behindert die Rückwärtskompatibilität.  
-[ ] Es kann neue Fehler einführen und abhängige Systeme beeinträchtigen.  
-[ ] Es erschwert das Hinzufügen neuer Funktionen.  
-[ ] Es verstößt gegen das Dependency Inversion Principle.  

---

## **Frage 8: Was ist ein Beispiel für die Einhaltung des Open-Closed Principle?**
-[ ] Schreiben eines neuen Moduls, das bestehende Funktionalität ändert.  
-[ ] Erweiterung des Verhaltens eines Moduls durch Vererbung oder Komposition.  
-[ ] Refaktorieren des Quellcodes eines Moduls, um neue Funktionen hinzuzufügen.  
-[ ] Abstrahieren potenzieller Variationen, um Erweiterungen ohne Änderungen an der Basis zu ermöglichen.  

---

## **Frage 9: Black Box Testing**
Betrachten Sie die folgende Funktion:

```scala
def concat(string1: String, string2: String): String = {
    if (string1 == null || string2 == null) return ""
    string1.concat(string2)
    string1
}
```

Identifizieren Sie Äquivalenzklassen, die verwendet werden können, um diese Funktion effektiv zu testen.
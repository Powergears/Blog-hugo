---
title: "Python Hochzähl-Maschine NONPLUSULTRA"
date: 2019-06-09T13:22:40+02:00
draft: false
---

Meine dritte Aufgabe baut im gewissen sinne auf der zweiten Aufgabe auf.den genau wie diese, musste ich ein Programm bauen das alle zahlen von eins bis einer vom Nutzer eingegebenen zahl nehmen. Aber dieses mal muss der Nutzer die Wahl dazwischen haben, ob er seine zahl addiert oder multipliziert haben will. Es war überraschend einfach, der schwerste Part war, der Additions-Part, den die variablen mit den ich gearbeitet habe hatten die ganze zeit One-off-Bugs. Aber es hat am ende gut funktioniert. Hier ist mein Endergebnis:

```python
summe = 1
max = int(input("please type in a number: "))
choice = input("multiply(m) or add(a)? ")

if choice == "a":
    for x in range(-1,max+1):
        summe = x + summe
    print (summe)

if choice == "m":
    for x in range(1, max+1):
        summe = x * summe
    print (summe)
```

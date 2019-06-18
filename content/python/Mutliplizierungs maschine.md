---
title: "Python Multiplikation"
date: 2019-06-9T13:22:40+02:00
draft: false
---

# Das Multiplikationsprogramm

### Die Aufgabe selbst.
Diese Aufgabe war die erste die ich gemacht habe.
Sie lautete wie folgt:
"Erstellen Sie ein Konsolenprogramm welches dem Benutzer auffordert 2 Zahlen einzugeben, diese sollen dann multipliziert werden."
die Aufgabe habe ich erfüllt, und bei Github hoch geladen.
Hier ist der Link dafür:
https://github.com/Powergears/Python-Repository/blob/master/erste-pythonchallenge.py .

### Problem Nummer Eins
Mein größtes Problem bei dieser Aufgabe war es, mein noch relativ neues know-how, was kein wunder war, da ich erst an dem Tag angefangen hab Python zu programmieren.



Im genaueren waren die Variablen für die vom User angegebenen zahlen ein Problem. Hier ist die Lösung die ich gefunden habe:

```python
text = input("Please write a first number: ")
text2 = input("Please write a second number: ")
```



Es fiel mir ziemlich schwer einen String zu formen, und ihn anzuwenden.
Aber auch dafür habe ich eine Lösung gefunden:

```python
text3 = text * text2
print("%s*%d=%r") % (text, text2, text3)
```

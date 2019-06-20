---
title: "Python zersetzungs-Maschine"
date: 2019-06-09T13:22:40+02:00
draft: false
---
Die zweite Aufgabe die ich gemacht habe, war weitaus komplexer. die aufgabe war, ein Programm zu bauen,das alle zahlen von null bis zu eine vom nutzer gewählten zahl zu nehmen, und zu addieren, und hier ist meine lösung:

```python

summe=0
max = input("please type in a number: ")

for x in range(max+1):
    summe = x + summe

print summe
```

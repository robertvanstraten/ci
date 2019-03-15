# cash.py

![](greedy.jpg)

In deze opdracht ga je de cash opdracht van CS50 maken in Python.

## Gebruik

	python cash.py
	O hai! How much change is owed? 0.41
	4

	python cash.py
	O hai! How much change is owed? -0.10
	O hai! How much change is owed? 0.01
	1

## Specificatie

* Schrijf een programma genaamd `cash.py` dat de gebruiker vraagt hoeveel wisselgeld er gegeven moet worden, en vervolgens het minimale aantal munten uitspuwt om dat wisselgeld te geven.
* Er zijn vier munten: quarters (0.25$), dimes (0.10$), nickels (0.05$) en pennies (0.01$).
* Als de gebruiker een negatief getal invult, dan moet je de gebruiker opnieuw vragen om invoer.
* Je mag aannemen dat de gebruiker enkel floats invult.

## Tips

* Hoewel je voor variabelen geen types hoeft op te geven, bestaan types wel degelijk in Python. Zo heb je ook nog steeds floats en de bijbehorende precissie errors. Vergeet dus niet te converteren naar integers!

## Testen

	check50 uva/progki/2018/py/cash

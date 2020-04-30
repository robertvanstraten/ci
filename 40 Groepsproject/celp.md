# Oude opdracht Groepsopdracht: Celp

### Beschrijving project
De beoogde uitkomst van het groepsproject is een onderbouwd voorstel voor een recommender system voor Yelp.

Je krijgt een dataset van Yelp bestaande uit 6.685.900 reviews en een fictieve, Yelp-achtige, website genaamd Celp (Collective yElP). Het doel is om aan de hand van de data, de gebruikers van Celp een lijst van gepersonaliseerde aanbevelingen te maken. Concreet betekent dit:

- Verkenning:
    - Analyseer de data. Bedenk hoe je de benodigde informatie uit de data kan halen.
    - Maak een prototype recommender system.
    - Evalueer het prototype.
- Voorstel:
    - Analyseer de resultaten.
    - Geef gebaseerd op de uitkomsten een voorstel voor een definietief ontwerp.

### Deliverables

Voor dit project schrijf je 4 deelverslagen (van ieder maximaal 500 woorden) en lever je de python code in van de website met het prototype recommender system.

### Download

- De volledige dataset kan je [hier downloaden](https://www.dropbox.com/s/gagjp3pxqi96gfp/Simon Pauw - yelp-all.zip?dl=1).
- Het framework voor de website vind je hier: <https://github.com/uva/celp>
    - Maak per groep een `fork` van deze repository en werk daarin vervolgens verder. Hier kun je vinden hoe dat moet: <https://help.github.com/en/articles/fork-a-repo>
    - Deze `fork` met het door jouw gebouwde recommender systeem lever je uiteindelijk in voor het code onderdeel.

### De website

Voordat je begint met programmeren, kijk eerst goed hoe de website in elkaar steekt. In principe ga je alleen aan de slag met `recommender.py`, maar wellicht wil je later `data.py` anders inrichten. Voel je vrij om aanpassingen te doen waar nodig, maar let er wel op dat de website blijft werken. Natuurlijk mag je ook nieuwe Python modules toevoegen.

Aan jou de taak om een aanbevelingssysteem te maken. Dat doe je door de functie `recommend` in `recommender.py` te implementeren. Deze functie roept de website op elke pagina aan, met verschillende parameters. Bijvoorbeeld, je weet pas wie de gebruiker is zodra zij is ingelogd. Als een gebruiker niet is ingelogd zul je dus geen `user_id` meekrijgen.


### Verslag

Het verslag bestaat uit vier delen die je afzonderlijk inlevert.

Het doel is dat je een goed onderbouwd voorstel voor een recommender system voor Yelp beschrijft. De website geeft een aantal aanbevelingen. Deze aanbevelingen moeten zo goed mogelijk worden gepersonaliseerd. Zorg ervoor dat de resultaten zo relevant en divers mogelijk zijn.

Beschrijving van het verkennen:

- Deel 1 (max 500 woorden): Bespreek in detail wat voor systeem je wil bouwen en welke informatie uit de data je hiervoor wel of niet kunt gebruiken. Welke features zijn nuttig? Hoe is de data gedistribueerd?
- Deel 2 (max 500 woorden): Bespreek welke technieken je hebt gebruikt bij het maken van een prototype recommender system en waarom deze van toepassing zijn.
- Deel 3 (max 500 woorden): Bespreek de resultaten van je experimenten met het prototype en de kwaliteit van de geleverde aanbevelingen.

Voorstel voor een ontwerp:

- Deel 4 (max 500 woorden): Geef een uitgewerkt voorstel voor een recommender system, onderbouwd met je kennis over het vakgebied en de resultaten van je experimenten uit de exploratiefase.

### Planning

| week 1 (6 - 10 mei)  | Verken en structureer de data.                                                         |
| week 2 (13 - 17 mei) | Implementeer en evalueer het prototype recommender system.                             |
| week 3 (20 - 22 mei) | Gebruik de resultaten van de afgelopen twee weken voor het uitwerken van een voorstel. |


### Deadlines

| ma 6 mei  | [Groepjes doorgeven](https://forms.gle/mA6idjm3NvAXFDxP7)                           |
| do 9 mei  | Deel 1 van het verslag inleveren                            |
| vr 10 mei | Meeting (5 minuten) met de docenten. Plan hier een slot in: |
| vr 17 mei | Deel 2 en 3 van het verslag inleveren                       |
| vr 17 mei | Meeting (5 minuten) met de docenten. Plan hier een slot in: |
| wo 22 mei | Deel 4  van het verslag en het prototype inleveren          |


**Let op** De links voor het inplannen van de meetings op vrijdag vind je hier binnenkort terug. Houd je mail in de gaten!
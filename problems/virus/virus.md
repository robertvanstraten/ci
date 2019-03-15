# Virus

## Jupyter Notebook

Om je voor te bereiden op Netwerk Analyse en verschillende andere vervolgvakken, maak je nu alvast kennis met Jupyter Notebook. Dat is een omgeving waarin je kan programmeren als wel tekst kan schrijven. Een ideale omgeving om de resultaten van jouw programma te presenteren, maar ook een ideaal formaat voor vakken (zoals dit vak) om hun opdrachten in te verspreiden.

Je runt jupyter notebook in de cs50 IDE d.m.v.

    jupyter notebook --ip=0.0.0.0 --port=8080 --no-browser

Je ziet nu een nieuwe webpagina openen. Er zijn hier drie tabjes: Files, Running, en Clusters. We hebben nu enkel de eerste nodig. Navigeer binnen Files naar een plek waar je jouw werk wilt opslaan. Dit zijn simpelweg de mappen op jouw computer, dus je kan altijd een nieuwe map aanmaken voor jouw werk. Zodra je bent aangekomen, klik je rechtsboven op het dropdown-menu `new`. Kies hier voor een Python3 notebook. Dan opent er een nieuw tabblad met daarin een nieuwe notebook.

Voor we beginnen, ga linksboven naar het dropdown-menu file en klik rename. Noem je nieuwe notebook: auto. In jouw notebook heb je zogenaamde cells. Dat zijn vakken waar je zowel code als tekst kan schrijven. Aangezien we een Python 3 notebook hebben, kunnen we Python3 code schrijven. Probeer maar eens: `print(3 * 4)`. Voer je dit in de cell, en druk je vervolgens op shift+enter (zo run je een cell), dan zie je direct onder de cell de uitkomst! Druk je enkel op enter, dan krijg je een extra regel binnen de cell.

Nieuwe cells kun je aanmaken met de knoppen bovenin het scherm, en je kan ze ook verplaatsen. Uitkomsten van cells zijn beschikbaar in andere cells, zo kun je verder werken met eerdere berekeningen. Let wel, cells updaten niet automatisch als je een andere cell runt. Je zal de cells of handmatig opnieuw moeten runnen of meerdere tegelijk via het dropdown menu Cell.

Behalve code, kunnen we ook tekst schrijven. Dit gaat in Markdown. Dat is een simpel mark-up taaltje (vandaar ook de naam). Zo kun je kopjes aanmaken met hekjes. Bijvoorbeeld # Klimaat creeërt een grote kop met de tekst Klimaat. Voeg je meer hekjes toe, dan krijg je een steeds kleiner kopje. Er zijn meer dingen die je kan doen, zoals links toevoegen, dikgedrukte tekst etc. Spiek maar even in de opdrachten straks!

## List comprehensions

Bij deze opdracht ga je onder andere oefenen met list comprehensions, een korte manier om een lijst aan te maken of te veranderen. Zie [/theory/comprehensions](/theory/comprehensions).

## What to do

Hier ga je het gedrag van virussen simuleren. Een beetje bio-informatica download je zo:

    wget https://github.com/Jelleas/virus/archive/master.zip
    unzip master.zip
    rm master.zip
    mv virus-master virus
    cd virus

De gehele opdracht vind je in de notebook!

## Testen

### check50

    check50 uva/progik/2018/virus

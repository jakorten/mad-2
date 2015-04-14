# Session 2 Android - Fragments & Storage (NOG NIET AF)

Nu we de Lynda cursus af hebben, stappen we over op het videomateriaal van een MOOC van de 
universiteit van Maryland: Programming Mobile Applications for Android Handheld Systems. 
Daarvan zijn wij vooral geïnteresseerd in de pagina met de video’s.

## Voorbereiding 1: video’s kijken

Van week 3:

* The Fragment Class – Part 1 (11:24), en
* The Fragment Class – Part 2 (16:37)

en van week 8:

* Data Management – Part 1 (15:57), en
* Data Management – Part 2 (13:43)

De docent in deze video’s, dr. Adam Porter, praat nogal sloom. Als je dat lastig vind, 
dan kun je de video versneld afspelen met knopjes linksonder de video. Smaken verschillen, 
maar zelf had ik prima ervaring met 150% snelheid, terwijl 175% net de doen was 
(terwijl de iOS video’s van Paul Hagerty voor mij niet sneller dan 125% moesten).

Let op: op de pagina met de video’s staan, bij iedere video, ook knopjes waarmee je 
niet alleen de video kunt downloaden, maar ook de sheets en de ondertitelingen. 
Die laatste zijn handig om in de video bepaalde plekken terug te vinden.
kijkvragen

We gebruiken nu de kijkvragen die verwerkt zitten in de video’s (als je ze op via coursera site bekijkt). 
Toch wil ik zien dat je ze gemaakt hebt, dus de opdracht is om je antwoorden toch in te sturen 
via het onderstaande Google Form:

[TODO](TODO)

## Voorbereiding 2: game state opslaan in n-Puzzle

In de N-puzzle hebben we de volgende requirement overgeslagen:

_The game’s state must also survive if the user quits the app or other activities appear above it. 
The end result should be that a user can return to the game and continue playing where they left 
off even if the app is quit or the device is turned off. Don’t forget to save such things as the
image selection, difficulty, number of moves taken so far, and current tile positions!_

Bedenk een antwoord op de volgende vragen:

1. Welke van de beschreven opties voor dataopslag de meest geschikte is om je N-puzzle mee af te maken?
1. Welke data moet je allemaal opslaan?
1. Waar in de code voor je huidige N-puzzle kun je het beste de code opnemen om de game-state te bewaren, en waar komt de code voor het weer inlezen ervan?
1. Wat zou een goede manier kunnen zijn om er voor te zorgen dat als je app opnieuw gestart wordt (nadat-ie echt helemaal uit het geheugen was verdwenen), je altijd terugkomt in de Activity die actief was toen de gebruiker je app verliet?

Nieuwe spelregel: voel je vrij om je te laten inspireren door StackOverflow, de Android developer
Guides of ander online materiaal. Maar geef bij je antwoord altijd aan of je het:

a. zelf verzonnen hebt,

b. zelf bedacht, maar samen met een klasgenoot (wie?),

c. van een online bron hebt (welke?),

d. of een combinatie daarvan.

Mail je antwoorden op deze vragen naar minor.mobileappdev@gmail.com,
met in de subject “Les 2.1 game state antwoorden”.

## Voorbereiding 3: bedenk een multiplayer n-Puzzle

Zoals je in de lesopzet kunt zien, gaan we van Android de volgende onderwerpen 
nog behandelen: multithreading, netwerk i/o, graphics, animatie, sensors, en location.

Het leek me leuk om een aantal van deze aspecten te toetsen door de N-puzzle verder uit 
te breiden naar een multi-player versie, waarbij location gebruikt wordt om spelers 
in de buurt te vinden.

De vraag is nu: hoe kun je van N-puzzle een spel maken dat leuk is om met z’n 2-en te spelen. 
Met elkaar, of tegen elkaar? Of nog meer spelers?

Bedenk een game-opzetje dat:

* geschikt is voor grote beeldschermen (5 inch telefoon of groter)
* een beetje leuk is maar bedenk dat het vooral een eindopdracht is, dus als we geen fantastisch game-concept hebben, dan is dat geen drama)
* in twee weken toe te voegen is aan de N-puzzle. Het moet dus niet te ingewikkeld zijn.

Mail je ideeën voor een multiplayer n-puzzle naar 

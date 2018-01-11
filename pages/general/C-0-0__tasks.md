---
layout: course
permalink: tasks/
#
title: Opdracht
---
## Opdracht 1, week 3
Voor opdracht 1 van week 3 dien je dus het volgende uit te werken:
 - Aan de hand van de input van een getal, welke het vermenigvuldigtal is, (eigen ingave via terminal) dien je de vermenigvuldigingstafel op te stellen van dat getal. 

Vooorbeeld:
  - vermenigvuldigtal: 7
  - vermenigvuldigingstafel:
0 x 7 = 0
1 x 7 = 7
2 x 7 = 14
3 x 7 = 21
4 x 7 = 28
5 x 7 = 35
6 x 7 = 42
7 x 7 = 49
8 x 7 = 56
9 x 7 = 63
10 x 7 = 70

 - Je gaat dus een loop nodig hebben voor de vermenigvuldigingstafel op te stellen.
 - Het resultaat zoals het voorbeeld zal je afdrukken in de console bij het uitvoeren van de loop.
 - Het resultaat zal je ook moeten opslaan in 3 verschillende datacollecties, je mag zelf kiezen welke je hiervoor gebruikt (voorbeeld: arrays, list, hashtable,...).
 Als alle elementen opgeslagen zijn in de datacollecties dien je elke datacollectie te overlopen en elk opgeslagen element af te drukken in de console.
 - Denk er ook aan dat je dient te werken met opsplitsing van functionaliteiten dus concreet opdelen van problemen in deelproblemen die resulteren in methodes, functies,...

 - Indienen van de oplossing:
 Maak een repository aan met de naam 1718-csse-code via je eigen account (met je login van AHS) op GitHub.
 In de folder van je repository maak je een folder opdrachtweek3 aan waarin je uw project gaat aanmaken en opslaan. Tussentijds voer je een commit en push uit naar je GitHub repo.

- Deadline: dinsdag 17/10 om 14 uur.
Codevoorbeelden van vorige les (les 3, 10/10/2017) kan je vinden op: [https://github.com/gdmgent/1718-csse-code](https://github.com/gdmgent/1718-csse-code).

## Opdracht 2, week 4

Voor opdracht 2 van week 4 dien je dus het volgende uit te werken:
 
### Oefening 1:
Aan de hand van de input van een geheel getal (tot maximum 100) ga je volgende acties ondernemen:
Alle getallen overlopen van 0 tot het gekozen getal en deze afdrukken in de console.

Voorbeeld:
Input: 12
Output:
0
1
2
3
4
5
6
7
8
9
10
11
12
 
Je gaat per geheel getal, vanaf 0 tot het gekozen getal (input), gaan kijken of het een priemgetal is.
Een priemgetal is een getal dat slechts deelbaar is door 1 en zichzelf.

Voorbeeld:
 - Input: 12
Output:
 - 0 is geen priemgetal.
 - 1 is geen priemgetal.
 - 2 is een priemgetal.
 - 3 is een priemgetal.
 - 4 is geen priemgetal.
 - 5 is een priemgetal.
 - 6 is geen priemgetal.
 - 7 is een priemgetal.
 - 8 is geen priemgetal.
 - 9 is geen priemgetal.
 - 10 is geen priemgetal.
 - 11 is een priemgetal.
 - 12 is geen priemgetal.
 
### Oefening 2:
 
Aan de hand van de input van een geheel getal ga je het aantal elementen bepalen in de rij van Fibonacci.
De elementen druk je af via de console, zie voorbeeld (output) hieronder.
De rij van Fibonacci begint met 0 en 1, vervolgens is elk volgend element in de rij steeds de som van de twee vorige elementen.

Voorbeeld:
 - Input: 8
 - Output:
  0
  1
  1
  2
  3
  5
  8
  13
 
Denk er ook aan dat je dient te werken met opsplitsing van functionaliteiten dus concreet opdelen van problemen in deelproblemen die resulteren in methodes, functies,...
 
Indienen van de oplossing:
- Maak een repository aan met de naam 1718-csse-code, indien je deze nog niet hebt aangemaakt, via je eigen account (met je login van AHS) op GitHub. In de folder van je repository maak je een folder opdrachtweek4 aan waarin je uw project gaat aanmaken en opslaan.
- Tussentijds voer je een commit en push uit naar je GitHub repo.
- Deadline: Maandag 23/10, 18 uur stipt.

## Opdracht 3, week 6
- 1a) Zet het [UML schema](https://i.stack.imgur.com/vCgMF.png) om in de nodige klasses met de nodige onderdelen (constructor(s), velden, getters, setters, methoden, access specifiers,...).
Opgelet: gender is van het type Char, dus neem volgende in acht:
  - man: m
  - vrouw: f
  - onbekend: u
- 1b) In plaats van 1 instantie van het type Author dien je de nodige aanpassing uit te voeren om meer instanties te bewaren voor een boek (type Book).
- 2) Maak een UML schema (met behulp van [StarUML](http://staruml.io), jouw oplossing in vorm van een PNG mag je plaatsen in de root van de folder opdrachtweek6) van de klasses Voertuig en Wagen, [zie code week05](https://github.com/gdmgent/1718-csse-code/tree/master/week05).
- 3) Maak een struct aan voor het bewaren van postcodes, volgende dient aanwezig te zijn:
    - Maak volgende velden: postcode, plaats, deelgemeente en provincie.
    - Kies bij de aanmaak voor de correcte datatypes.
    - Maak de nodige properties aan voor alle velden.
    - Maak een lijst aan met minimaal 5 instanties van het type Postcode.
    Gegevens om in te vullen in de datacollectie kan je vinden in de [Excelsheet](http://www.bpost2.be/zipcodes/files/zipcodes_alpha_nl.xls?_ga=2.170740832.1384631120.1510665399-1085650226.1510665399) van Bpost. 
Indienen:
- Maak een repository aan met de naam *1718-csse-code* via je eigen account (met je login van AHS) op GitHub. In de folder van je repository maak je een folder opdrachtweek6 aan waarin je uw project gaat aanmaken en opslaan. Tussentijds voer je een commit en push uit naar je GitHub repo.
- Deadline: donderdag 16/11/2017 om 14 uur.

## Opdracht 4, week 11
- 1) Maak een custom event NumberReached aan.
Dit event zal uitgevoerd worden telkens je de maximumwaarde/maximumgetal bereikt die je vooraf opgeeft.
- 2) Voorzie de nodige delegate welke zal dienen als event handler.
Deze zal de timestamp, thread en getal afdrukken in de console.
Daarna ga je de thread stoppen, voorzie erin dat je applicatie niet stopt door een exception...
- 3) Bij het starten van de applicatie dien je een maximumgetal op te geven.
- 3) Voorzie minimum 3 threads met elk volgende uitwerking:
- 3a) Thread 1: Gebruiker geeft zelf een willekeurig getal in via de console tot hij het maximumgetal heeft ingegeven.
- 3b) Thread 2: Voorzie een lus die getallen gaat overlopen van 0 tot maximumwaarde.
- 3c) Thread 3: Voorzie een lus die telkens een random getal gaat kiezen tot het maximumgetal is gekozen.

[Voor voorbeelden van events, delegates, threads,... zie code repository week11, 10, 09,...](https://github.com/gdmgent/1718-csse-code/).

Indienen:
- Maak een repository aan met de naam *1718-csse-code* via je eigen account (met je login van AHS) op GitHub. In de folder van je repository maak je een folder opdrachtweek11 aan waarin je uw project gaat aanmaken en opslaan. Tussentijds voer je een commit en push uit naar je GitHub repo.
- Deadline: zaterdag 16/12/2017 om 18 uur.
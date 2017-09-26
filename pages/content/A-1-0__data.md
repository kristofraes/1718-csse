---
layout: course
permalink: data/
#
title: Data
---
## Wat is data?

Data is een gegevensverzameling, ook wel dataset genoemd welke in de meeste gevallen gepresenteerd is in een tabelvorm.

Waarbij de rijen, ook wel records genoemd, in de tabel overeenstemt met een lid uit de gegevensverzameling.

De kolom stemt overeen met een variabele.
Elke rij bevat een waarde voor de verschillende variabelen of attributen.

Voorbeelden van variabelen: datum, tijdstip, getal, tekst,...

Een dataset heeft verschillende kenmerken welke de eigenschappen en structuur bepalen zoals onder andere het datatype van de variabelen, het aantal variabelen

Andere vormen van datasets welke geen tabelvorm zijn: XML, JSON,...

De waarden kunnen getallen zijn, maar ook gegevens van nominaal of ordinaal niveau zijn. Voor elke variable zullen normaal gesproken de waarden van hetzelfde niveau zijn, al kunnen er wel gegevens ontbreken, wat op een of andere manier dient te worden aangegeven.


# Datatypes

Een datatype of gegevenstype is een specifieke soort van data, het datatype bepaalt welke waarde de variabele kan bevatten.

De datatypes kan je verdelen in primitieve, enkelvoudige en samengestelde datatypes.

## Primitieve datatypes

Een primitief datatype is gedefinieerd door de programmeertaal zelf.

Meest voorkomende primitieve datatypes:
- Boolean
- Char
- Integer
- Double
- Decimal

Overzicht
--------

| Verkorte naam | .NET Class en type | Bereik | Grootte | Standaardwaarde |
|:---------|:--------:|:--------:|:--------:|---------:|
|Gehele getallen |  |  |  |
|----------|----------|----------|----------|----------|
| byte     | Byte, unsigned integer | 0 tot 255 | 8 | 0 |
| sbyte    | SByte, signed integer | -128 tot 127 | 8 | 0 |
| int      | Int32, signed integer | -2.147.483.648 tot 2.147.483.647 | 32 | 0 |
| uint     | UInt32, unsigned integer | -2.147.483.648 tot 2.147.483.647 | 32 | 0 |
| short    | Int16, signed integer | -32.768 tot 32.767 | 16 | 0 |
| ushort   | UInt16, unsigned integer | 0 tot 65535 | 16 | 0 |
| long     | Int64, singed integer | -9.223.372.036.854.775.808 tot 9.223.372.036.854.775.807 | 64 | 0L |
| ulong    | Int64, unsinged integer | 0 tot 18.446.744.073.709.551.615 | 64 | 0 |
| =========|==========|==========|==========|==========|
|Reële getallen |  |  |  |  |
|----------|----------|----------|----------|----------|
| float    | Single, single-precision floating point type | 32 | -3,402823e38 to 3,402823e38 | 0.0F |
| double   | Double, double-precision floating point type | 64 | -1,79769313486232e308 tot 1,79769313486232e308 | 0.0D |
| decimal  | Decimal, Precise fractional or integral type that can represent decimal numbers with 29 significant digits | 128 | ±1.0 × 10e−28 to ±7.9 × 10e28 | 0.0M |
| =========|==========|==========|==========|==========|
|Tekst     |  |  |  |  |
|----------|----------|----------|----------|----------|
| string   | String, tekenreeks |  |  |  |
| =========|==========|==========|==========|==========|
|Andere types |  |  |  |  |
|----------|----------|----------|----------|----------|
| char     | Char, 1 unicode karakter | U +0000 to U +ffff | 16 | '\0' |
| bool     | Boolean, True (1) of False (0) | True (1) of False (0) | 8 | False (0) |
| object   | Object, basis type van alle andere types |  | | 
| =========|==========|==========|==========|==========|
{:.table.table-bordered}


## Enkelvoudige datatypes

Is een primitief datatype, ook wel simpel datatype genoemd, of een datatype gedefinieerd op basis van een primitief datatype. De voorwaarde is dat een enkelvoudig datatype enkel als geheel kan worden uitgelezen en/of gemanipuleerd.

## Samengestelde datatypes

Samengestelde datatypes of complexe datatypes bestaan uit meerdere simpele types die afzonderlijk kunnen worden gemanipuleerd en uitgelezen. 

Deze structuren welke resulteren in arrays, klasse, lijsten,... die samengesteld zijn uit elementen die op zichzelf ook kunnen bestaan uit samengestelde datatypes zoals lijsten van lijsten, geneste structuren,...

### String
Is een reeks van karakters.

### Array
Een array is een collectie welke bestaat uit een vast aantal elementen van hetzelfde datatype.
Elk element in de collectie is een variabele en heeft een adres of ook wel index genoemd.
Doormiddel van de index kan je een waarde toekennen of opvragen.

Snelle toegang via een nummer. Grootte staat vooraf vast, resizen is duur. Een tweedimensionale array (toegang via twee nummers) heet een matrix.

Aanpassen van de grootte is moeilijk.

#### Een dimensionale array
Toegang via single index in een lineaire vorm.

#### Multidimensionale array
Matrix van waarden van hetzelfde type men spreekt ook wel eens van arrays van arrays.

Referentie: [https://docs.microsoft.com/nl-nl/dotnet/api/system.array?view=netframework-4.7](https://docs.microsoft.com/nl-nl/dotnet/api/system.array?view=netframework-4.7)

#### BitArray
Een BitArray is een array bestaande uit bit waarden welke bestaan uit booleans. 

Referentie: [https://docs.microsoft.com/nl-nl/dotnet/api/system.collections.bitarray?view=netframework-4.7](https://docs.microsoft.com/nl-nl/dotnet/api/system.collections.bitarray?view=netframework-4.7)

### ArrayList
Is een datacollectie van een bepaalde object die geordend is.
Opvragen van een item kan via zijn index.
Het verschil met een array is dat je items kan toevoegen en verwijderen zonder de grootte aan te passen.
Sorteren, zoeken zijn ook mogelijk via methodes.

Referentie: [https://docs.microsoft.com/nl-nl/dotnet/api/system.collections.arraylist?view=netframework-4.7](https://docs.microsoft.com/nl-nl/dotnet/api/system.collections.arraylist?view=netframework-4.7)

### Lijst
Een lijst, list in C#, is een collectie welke bestaat uit een x aantal elementen van een bepaald object.
Elk element is toegankelijk via zijn index.
Zoeken, sorteren en manipuleren is mogelijk via voorziene methodes.

Referentie: [https://docs.microsoft.com/nl-nl/dotnet/api/system.collections.generic.list-1?view=netframework-4.7](https://docs.microsoft.com/nl-nl/dotnet/api/system.collections.generic.list-1?view=netframework-4.7)

### Sortedlist
Dit is een datacollectie waarbij je gebruik kan maken van de key of de index om elementen op te vragen in de lijst.
Een SortedList is een combinatie van een hashtable (key) en een arraylist (index).
De collectie is gesorteerd via zijn key waarde.

Referentie: [https://docs.microsoft.com/nl-nl/dotnet/api/system.collections.sortedlist?view=netframework-4.7](https://docs.microsoft.com/nl-nl/dotnet/api/system.collections.sortedlist?view=netframework-4.7)

### Hashtable
Hashtable is een datacollectie die bestaat uit elementen van een bepaald datatype welke toegankelijk zijn via hun key.
Dit gebruik je best als je elementen wenst op te vragen aan de hand van een key.
Elk element in de hashtable bestaat uit een key/value paar.

Referentie: [https://docs.microsoft.com/nl-nl/dotnet/api/system.collections.hashtable?view=netframework-4.7](https://docs.microsoft.com/nl-nl/dotnet/api/system.collections.hashtable?view=netframework-4.7)

### Queue
Een queue is een FIFO collectie van een bepaald object, waarbij FIFO staat voor first-in, first-out.
Is handig als je een de items in de collectie wil raadplegen volgens het FIFO principe.
Wanneer je een item toevoegt tot de queue dan dien je enqueue uit te voeren, wanneer je een item wist van de queue dan dien je dit te doen via deque.

Referentie: [https://docs.microsoft.com/nl-nl/dotnet/api/system.collections.queue?view=netframework-4.7](https://docs.microsoft.com/nl-nl/dotnet/api/system.collections.queue?view=netframework-4.7)

### Stack
Een stack is een LIFO collectie van een bepaald object, waarbij LIFO staat voor last-in, first-out.
Wanneer je een item toevoegt tot de stack dan zal push moeten uitvoeren, wanneer je een item van de lijst wist dan zal je pop moeten uitvoeren (popping).

Referentie: [https://docs.microsoft.com/nl-nl/dotnet/api/system.collections.stack?view=netframework-4.7](https://docs.microsoft.com/nl-nl/dotnet/api/system.collections.stack?view=netframework-4.7)

### Associatieve array
Dictionary in C#; elementen in de datacollectie kan je zoeken via hun unieke key.

Referentie: [https://docs.microsoft.com/nl-nl/dotnet/api/system.collections.dictionarybase?view=netframework-4.7](https://docs.microsoft.com/nl-nl/dotnet/api/system.collections.dictionarybase?view=netframework-4.7)

### HashSet
Je kan elementen in de hashset opzoeken doormiddel van hun unieke key.

Referentie: [https://docs.microsoft.com/nl-nl/dotnet/api/system.collections.generic.hashset-1?view=netframework-4.7](https://docs.microsoft.com/nl-nl/dotnet/api/system.collections.generic.hashset-1?view=netframework-4.7)

### ConcurrentBag
Een concurrentbag is een datacollectie met waarden waar je resultaten kunt toevoegen en uitpikken.

Referentie: [https://docs.microsoft.com/nl-nl/dotnet/api/system.collections.concurrent.concurrentbag-1?view=netframework-4.7](https://docs.microsoft.com/nl-nl/dotnet/api/system.collections.concurrent.concurrentbag-1?view=netframework-4.7)

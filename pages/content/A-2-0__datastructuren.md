---
layout: course
permalink: datastructuren/
#
title: Datastructuren
---

# Datacollecties

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
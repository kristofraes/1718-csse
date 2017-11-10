---
layout: course
permalink: objecten/
#
title: Objecten en klassen
---
# Wat is een object?
Een object is een exemplaar van een bepaalde klasse en bestaat uit de waarden van alle velden of attributen waarmee we een object definieren. Objecten van dezelfde klassen beschikken steeds over dezelfde velden. De waarden van de velden kan per object verschillen.

De naam van een object start altijd met een kleine letter.

# Wat is een klasse?
Een klasse beschrijft de algemene kenmerken en een aantal algemene methodes van objecten van een bepaalde soort.
Men kan een instantie maken van een klasse welke men object noemt.

De naam start altijd met een hoofdletter.
Uit een klasse kunnen we oneindig veel objecten maken.

Een klasse bestaat uit:
- velden (instance variables)
- constructors (startwaarden voor de velden, initialisatie)
- methodes

# Overerving
Een klasse kan eigenschappen overnemen vanuit een andere klasse dit noemen we overerving.
Men spreekt dan van een basisklasse en een superklasse.

De basisklasse/superklasse is de hoogste klasse en de subklasse of afgeleide klasse bevat dan alle attributen en methodes van de superklasse.

[Referentie](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/inheritance)

# Polymorfisme
Een object kan voorkomen in meerdere gedaantes.
Het komt erop neer dat een object van subklasse kan gezien worden of als element van een superklasse en dus ook de eigenschappen en methoden van die superklasse kan gebruiken.
Polymorfisme betekent letterlijk veelvormigheid.

[Referentie](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/polymorphism)

# Inkapsulatie of inkapseling
Bij inkapseling men ervoor zorgen dat men een of meer items gaat insluiten in een fysieke of logische package.
Hierbij ga je er voor zorgen dat er geen toegang is tot de details van implementatie.

Encapsulation of inkapseling in OO ga je toepassen door gebruik te maken van access specifiers.
Een access specifier gaat definieren wat de scope en visibiliteit is van een klasse member.

Volgende access specifiers zijn van toepassing:

- public, overal
- private, enkel in dezelfde klasse
- protected, in dezelfde klasse of elke klasse die overerft van de klasse
- internal, in dezelfde assembly, maar niet van een andere assembly.
- protected internal, in de assembly waar die gedeclareerd is of van een overervende klasse in een andere assembly.

[Referentie](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/access-modifiers)
---
layout: course
permalink: methodes/
#
title: Methodes en functies
---
# Wat is een methode?
Een methode of procedure is een reeks van commando's welke in volgorde uitgevoerd worden. Een methode geeft geen returnwaarde terug.

Elk C# programma bestaat ten minste uit 1 klasse met een methode Main.

# Wat is een functie?
Hetzelfde als een methode met dat verschil dat een functie wel een waarde teruggeeft wel spreken in dat geval van een return.

# Argumenten

De argumenten van een procedure kunnen By Value of By Reference doorgegeven worden.

- By Value (ByVal): hierbij is de waarde (inhoud) van de variabele doorgegeven en niet de varibele zelf. De procedure kan de inhoud van de variabele niet wijzigen.
- By Reference (ByRef): de referentie (of verwijzing) naar de waarde is hierbij doorgegeven. De waarde van de variabele kan hierbij aangepast worden in de functie.

Standaard worden variabelen doorgegeven By Value. 
Het is uitzonderlijk om variabelen By Reference door te geven.
Voor de performantie te verhogen kunnen we wel opteren om variabelen By Reference door te geven.

# Signatuur
De signatuur van een methode of functie bestaat uit de naam, het aantal en het type van argumenten.

# Overloading
Methodes met dezelfde naam maar verschil in aantal of types argumenten.


# Waaruit bestaat een methode/functie:
- Access specifier
    Men spreekt ook wel van access modifiers.
    - public, overal
    - private, enkel in dezelfde klasse
    - protected, in dezelfde klasse of elke klasse die overerft van de klasse
    - internal, in dezelfde assembly, maar niet van een andere assembly.
    - protected internal, in de assembly waar die gedeclareerd is of van een overervende klasse in een andere assembly.
Referentie:    [https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/access-modifiers](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/access-modifiers)
- Return type
    - void => in dit geval spreken we van een methode.
    - int, string,... als returntype => in dit geval spreken we van een functie.
- Methodenaam
- Parameters
    - Tussen de (), type, volgorde, aantal.
- Inhoud van de methode
    - Volgorde van instructies om uit te voeren.
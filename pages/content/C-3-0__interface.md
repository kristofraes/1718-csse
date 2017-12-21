---
layout: course
permalink: interface/
#
title: Interface
---
Een interface bevat de definities van een groep van gerelateerde functionaliteiten die een klasse of een struct kan implementeren.

Voor een interface dien je het keyword interface te gebruiken.
De naam van de interface dient te starten met een hoofdletter I.
De interface in het voorbeeld hieronder voorziet in een definitie van een functie accountActive.

{% highlight cs linenos %}
interface IAccount
{
    bool accountActive(Account a);
}
{% endhighlight %}

Wat is het verschil tussen een interface en een abstract klasse?
Wat is het voordeel van een interface bij overerving?

[Referentie](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/interfaces/)
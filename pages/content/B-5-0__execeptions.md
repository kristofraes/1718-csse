---
layout: course
permalink: exceptions/
#
title: Exceptions
---
### Exceptions
Een exception is een fout die gegooid wordt via keyword [throw](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/throw).
De type exception hangt af van de fout die opgetreden is.

Je kan zelf een exception gooien op volgende manier:
{% highlight cs linenos %}
throw new NotImplementedException();
throw new IndexOutOfRangeException
{% endhighlight %}

### Try-catch
Je kan een exception opvangen door rond de code die je wenst uit te voeren een [try-catch](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/try-catch) te zetten.

De code dient dus in de try te komen en het opvangen van eventuele exceptions dien je in het catch blok te behandelen.
Wil je verschillende types van exceptions opvangen dan kan je opteren voor verschillende catches te schrijven ofwel geef je geen argument mee tussen de haakjes en dan vang je alle exceptions op.

{% highlight cs linenos %}
object o = null;  
try  
{  
    int i = (int)o;   // Error  
}
catch (InvalidCastException e)   
{  
    Console.WriteLine(e.);
}
{% endhighlight %}

### Try-finally

Als je bepaalde handelingen wenst uit te voeren die niet geïmpacteerd mogen geraken door een exception, dan opteer je voor een finally blok te plaatsen.

{% highlight cs linenos %}
int i = 123;
string s = "tekst";
object obj = s;

try
{
    i = (int)obj;
    Console.WriteLine("Einde van try.");
}
finally
{
    Console.WriteLine("Uitvoeren van finally blok na het optreden van een exception.");
    Console.WriteLine("i: {0}", i);
}
{% endhighlight %}

### Try-catch-finally
Als je de combinatie van alle 3 wenst dien je de 3 blokken toe te voegen.

{% highlight cs linenos %}
int i = 123;
string s = "tekst";
object obj = s;

try
{
    i = (int)obj;
    Console.WriteLine("Einde van try.");
}
catch
{
    Console.WriteLine("!EXCEPTION!");
}
finally
{
    Console.WriteLine("Uitvoeren van finally blok na het optreden van een exception.");
    Console.WriteLine("i: {0}", i);
}
{% endhighlight %}



Referenties:
[Exception handling](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/exception-handling-statements)

- Waarvoor dient een exception?
- Van welke klasse dien je over te erven om een custom Exception aan te maken?
- Hoe vang je een exception op?
- Het verschil tussen een try-catch en een try-finally?
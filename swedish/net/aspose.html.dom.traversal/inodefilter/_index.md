---
title: Interface INodeFilter
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Dom.Traversal.INodeFilter gränssnitt. Filter är objekt som vet hur man filtrerar bort noder. Om en NodeIterator eller TreeWalker ges ett NodeFilter tillämpar den filtret innan den returnerar nästa nod. Om filtret säger att man ska acceptera noden returnerar övergångslogiken it annars letar traversal efter nästa nod och låtsas att noden som avvisades inte fanns där.
type: docs
weight: 2490
url: /sv/net/aspose.html.dom.traversal/inodefilter/
---
## INodeFilter interface

Filter är objekt som vet hur man "filtrerar bort" noder. Om en NodeIterator eller TreeWalker ges ett NodeFilter, tillämpar den filtret innan den returnerar nästa nod. Om filtret säger att man ska acceptera noden, returnerar övergångslogiken it; annars letar traversal efter nästa nod och låtsas att -noden som avvisades inte fanns där.

DOM tillhandahåller inga filter. NodeFilter är bara ett -gränssnitt som användare kan implementera för att tillhandahålla sina egna filter.

NodeFilters behöver inte veta hur man korsar från nod till nod, och de behöver inte heller veta något om datastrukturen som korsas. Detta gör det väldigt enkelt att skriva filter, eftersom det enda de behöver veta hur man gör är att utvärdera en enda nod. Ett filter kan användas med ett antal olika typer av genomgångar, uppmuntrar kodåteranvändning.

Se även[Dokumentobjekt Modell (DOM) Nivå 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @sedan DOM nivå 2

```csharp
public interface INodeFilter
```

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AcceptNode](../../aspose.html.dom.traversal/inodefilter/acceptnode/)(Node) | Testa om en angiven nod är synlig i den logiska vyn för en TreeWalker eller NodeIterator. Denna funktion kommer att anropas av implementeringen av TreeWalker och NodeIterator; det anropas normalt inte direkt från användarkoden . (Även om du kunde göra det om du ville använda samma -filter för att styra din egen applikationslogik.) |

### Se även

* namnutrymme [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* hopsättning [Aspose.HTML](../../)



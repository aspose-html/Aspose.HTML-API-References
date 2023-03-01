---
title: Interface IHTMLOptionsCollection
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.IHTMLOptionsCollection gränssnitt. AnHTMLOptionsCollection är en lista över noder som representerar HTML alternativelement. En enskild nod kan nås med antingen ordinal index eller nodensnamn ellerid attribut. Samlingar i HTML DOM antas vara live vilket innebär att de uppdateras automatiskt när det underliggande dokumentet ändras.
type: docs
weight: 3680
url: /sv/net/aspose.html/ihtmloptionscollection/
---
## IHTMLOptionsCollection interface

An`HTMLOptionsCollection` är en lista över noder som representerar HTML alternativelement. En enskild nod kan nås med antingen ordinal index eller nodens`namn` eller`id` attribut. Samlingar i HTML DOM antas vara live, vilket innebär att de uppdateras automatiskt när det underliggande dokumentet ändras.

Se även[Dokumentobjektmodell (DOM) Nivå 2 HTML-specifikation](http://www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109). @sedan DOM nivå 2

```csharp
public interface IHTMLOptionsCollection : IEnumerable<Element>
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Item](../../aspose.html/ihtmloptionscollection/item/) { get; } | Returnerar indexobjektet i samlingen. Om index är större än eller lika med antalet noder i listan, returnerar detta null. (2 indexers) |
| [Length](../../aspose.html/ihtmloptionscollection/length/) { get; } | Antalet noder i listan. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [NamedItem](../../aspose.html/ihtmloptionscollection/nameditem/)(string) | Metod returnerar indexobjektet i samlingen. http://www.w3.org/TR/DOM-Level-2-HTML/html.html#HTMLOptionsCollection-namedItem |

### Se även

* class [Element](../../aspose.html.dom/element/)
* namnutrymme [Aspose.Html](../../aspose.html/)
* hopsättning [Aspose.HTML](../../)



---
title: Interface ITraversal
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Dom.Traversal.ITraversal gränssnitt. Iteratorer används för att stega igenom en uppsättning noder t.ex. uppsättningen av noder i en NodeList dokumentunderträdet som styrs av en viss Nod resultaten av en fråga eller någon annan uppsättning av noder. Uppsättningen av noder som ska itereras bestäms av implementeringen av NodeIterator. DOM Level 2 specificerar en enda NodeIteratorimplementering för dokumentorder genomgång av ett dokumentunderträd. Förekomster av dessa iteratorer skapas genom att anropa DocumentTraversal .createNodeIterator.
type: docs
weight: 2510
url: /sv/net/aspose.html.dom.traversal/itraversal/
---
## ITraversal interface

Iteratorer används för att stega igenom en uppsättning noder, t.ex. uppsättningen av noder i en NodeList, dokumentunderträdet som styrs av en viss Nod, resultaten av en fråga eller någon annan uppsättning av noder. Uppsättningen av noder som ska itereras bestäms av -implementeringen av NodeIterator. DOM Level 2 specificerar en enda NodeIterator-implementering för dokument-order genomgång av ett dokumentunderträd. Förekomster av dessa iteratorer skapas genom att anropa DocumentTraversal .createNodeIterator().

Se även[Dokumentobjekt Modell (DOM) Nivå 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @sedan DOM nivå 2

```csharp
public interface ITraversal : IDisposable
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Filter](../../aspose.html.dom.traversal/itraversal/filter/) { get; } | Nodfiltret som används för att screena noder. |
| [Root](../../aspose.html.dom.traversal/itraversal/root/) { get; } | Rotnoden för NodeIterator, som specificerades när it skapades. |
| [WhatToShow](../../aspose.html.dom.traversal/itraversal/whattoshow/) { get; } | Det här attributet bestämmer vilka nodtyper som presenteras via iteratorn . Den tillgängliga uppsättningen konstanter definieras i gränssnittet NodeFilter. Noder som inte accepteras av whatToShow kommer att hoppas över, men deras barn kan fortfarande övervägas. Observera att detta överhopp har företräde framför filtret, om något. |

### Se även

* namnutrymme [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* hopsättning [Aspose.HTML](../../)



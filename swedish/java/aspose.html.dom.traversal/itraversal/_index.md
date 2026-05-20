---
title: "ITraversal‑gränssnitt"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.traversal.ITraversal‑gränssnitt. Iterators används för att gå igenom en mängd noder, t.ex. mängden noder i en NodeList, dokumentets underträd styrt av en viss Node, resultatet av en fråga eller någon annan mängd noder. Mängden noder som ska itereras bestäms av implementationen av NodeIterator. DOM Level 2 specificerar en enda NodeIterator‑implementation för dokumentordnings‑traversering av ett dokumentunderträd. Instanser av dessa iterators skapas genom att anropa DocumentTraversal .createNodeIterator."
type: docs

url: /sv/java/com.aspose.html.dom.traversal/itraversal/
---
## ITraversal interface

Iteratorer används för att gå igenom en mängd noder, t.ex. mängden noder i en NodeList, dokumentets underträd som styrs av en viss Node, resultatet av en fråga eller någon annan mängd noder. Mängden noder som ska itereras bestäms av implementationen av NodeIterator. DOM Level 2 specificerar en enda NodeIterator‑implementation för dokumentordningstraversering av ett dokumentunderträd. Instanser av dessa iteratorer skapas genom att anropa DocumentTraversal .createNodeIterator().

Se även [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface ITraversal : IDisposable
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getFilter](../../com.aspose.html.dom.traversal/itraversal/filter/) NodeFilter som används för att filtrera noder. |
| [getRoot](../../com.aspose.html.dom.traversal/itraversal/root/) Rotnoden för NodeIterator, enligt specifikationen när den skapades. |
| [getWhatToShow](../../com.aspose.html.dom.traversal/itraversal/whattoshow/) Detta attribut bestämmer vilka nodtyper som presenteras via iteratorn. Den tillgängliga mängden konstanter definieras i NodeFilter‑gränssnittet. Noder som inte accepteras av whatToShow hoppas över, men deras barn kan fortfarande beaktas. Observera att detta hopp har företräde framför filtret, om något. |

### Se även

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)

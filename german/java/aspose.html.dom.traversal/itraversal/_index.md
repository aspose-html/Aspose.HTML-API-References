---
title: "ITraversal‑Schnittstelle"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.traversal.ITraversal‑Schnittstelle. Iteratoren werden verwendet, um durch eine Menge von Knoten zu gehen, z. b. die Menge der Knoten in einer NodeList, das Dokument-Teilbaum, das von einem bestimmten Node gesteuert wird, die Ergebnisse einer Abfrage oder jede andere Knotengruppe. Die zu iterierende Knotengruppe wird durch die Implementierung des NodeIterator bestimmt. DOM Level 2 definiert eine einzelne NodeIterator‑Implementierung für die Traversierung eines Dokument‑Teilbaums in Dokumentreihenfolge. Instanzen dieser Iteratoren werden erzeugt, indem DocumentTraversal.createNodeIterator aufgerufen wird."
type: docs

url: /de/java/com.aspose.html.dom.traversal/itraversal/
---
## ITraversal interface

Iteratoren werden verwendet, um durch eine Menge von Knoten zu gehen, z. B. die Menge von Knoten in einer NodeList, den Dokument-Teilbaum, der von einem bestimmten Node gesteuert wird, die Ergebnisse einer Abfrage oder jede andere Knotengruppe. Die zu iterierende Knotengruppe wird durch die Implementierung des NodeIterator bestimmt. DOM Level 2 spezifiziert eine einzelne NodeIterator-Implementierung für die Dokumentreihenfolge‑Durchquerung eines Dokument-Teilbaums. Instanzen dieser Iteratoren werden durch Aufruf von DocumentTraversal .createNodeIterator() erstellt.

Siehe auch das [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface ITraversal : IDisposable
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getFilter](../../com.aspose.html.dom.traversal/itraversal/filter/) Der NodeFilter, der zum Filtern von Knoten verwendet wird. |
| [getRoot](../../com.aspose.html.dom.traversal/itraversal/root/) Der Wurzelknoten des NodeIterator, wie beim Erstellen angegeben. |
| [getWhatToShow](../../com.aspose.html.dom.traversal/itraversal/whattoshow/) Dieses Attribut bestimmt, welche Knotentypen über den Iterator präsentiert werden. Die verfügbare Menge an Konstanten ist in der NodeFilter‑Schnittstelle definiert. Knoten, die von whatToShow nicht akzeptiert werden, werden übersprungen, aber ihre Kinder können weiterhin berücksichtigt werden. Beachten Sie, dass dieses Überspringen Vorrang vor dem Filter hat, falls vorhanden. |

### Siehe auch

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)

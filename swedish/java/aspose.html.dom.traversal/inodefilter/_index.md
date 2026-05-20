---
title: "INodeFilter‑gränssnitt"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.traversal.INodeFilter‑gränssnitt. Filter är objekt som vet hur man filtrerar bort noder. Om en NodeIterator eller TreeWalker får ett NodeFilter tillämpas filtret innan nästa nod returneras. Om filtret godkänner noden returneras den av traverseringslogiken, annars letar traverseringen efter nästa nod och låtsas att den avvisade noden inte finns."
type: docs

url: /sv/java/com.aspose.html.dom.traversal/inodefilter/
---
## INodeFilter interface

Filter är objekt som vet hur man \"filterar bort\" noder. Om en NodeIterator eller TreeWalker får en NodeFilter, tillämpar den filtret innan den returnerar nästa nod. Om filtret säger att noden ska accepteras returnerar traverseringslogiken den; annars letar traverseringen efter nästa nod och låtsas att den avvisade noden inte fanns.

DOM tillhandahåller inga filter. NodeFilter är bara ett gränssnitt som användare kan implementera för att tillhandahålla egna filter.

NodeFilters behöver inte veta hur man traverserar från nod till nod, och de behöver inte heller känna till datastrukturen som traverseras. Detta gör det mycket enkelt att skriva filter, eftersom det enda de måste kunna göra är att utvärdera en enskild nod. Ett filter kan användas med ett antal olika typer av traverseringar, vilket uppmuntrar återanvändning av kod.

Se även [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface INodeFilter
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [acceptNode](../../com.aspose.html.dom.traversal/inodefilter/acceptnode/)(Node) | Testa om en angiven nod är synlig i den logiska vyn av en TreeWalker eller NodeIterator. Denna funktion kommer att anropas av implementationen av TreeWalker och NodeIterator; den anropas normalt inte direkt från användarkod. (Även om du kan göra det om du vill använda samma filter för att styra din egen applikationslogik.) |

### Se även

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)

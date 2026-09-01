---
title: "INodeFilter.AcceptNode"
second_title: "Aspose.HTML för Java API-referens"
description: "INodeFilter‑metod. Testar om en angiven nod är synlig i den logiska vyn av en TreeWalker eller NodeIterator. Denna funktion kommer att anropas av implementationen av TreeWalker och NodeIterator; den anropas normalt inte direkt från användarkod. Du kan dock göra det om du vill använda samma filter för att styra din egen applikationslogik."
type: docs

url: /sv/java/com.aspose.html.dom.traversal/inodefilter/acceptnode/
---
## INodeFilter.AcceptNode method

Testa om en angiven nod är synlig i den logiska vyn av en TreeWalker eller NodeIterator. Denna funktion kommer att anropas av implementationen av TreeWalker och NodeIterator; den anropas normalt inte direkt från användarkod. (Även om du kan göra det om du vill använda samma filter för att styra din egen applikationslogik.)

```java
public short AcceptNode(Node n)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| n | Node | nod att kontrollera för att se om den passerar filtret eller inte. |

### Returvärde

en konstant för att bestämma om noden accepteras, avvisas eller hoppas över, enligt definitionen ovan.

### Se även

* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeFilter](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

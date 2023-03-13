---
title: INodeFilter.AcceptNode
second_title: Aspose.HTML för .NET API Referens
description: INodeFilter metod. Testa om en angiven nod är synlig i den logiska vyn för en TreeWalker eller NodeIterator. Denna funktion kommer att anropas av implementeringen av TreeWalker och NodeIterator det anropas normalt inte direkt från användarkoden . Även om du kunde göra det om du ville använda samma filter för att styra din egen applikationslogik.
type: docs
weight: 10
url: /sv/net/aspose.html.dom.traversal/inodefilter/acceptnode/
---
## INodeFilter.AcceptNode method

Testa om en angiven nod är synlig i den logiska vyn för en TreeWalker eller NodeIterator. Denna funktion kommer att anropas av implementeringen av TreeWalker och NodeIterator; det anropas normalt inte direkt från användarkoden . (Även om du kunde göra det om du ville använda samma -filter för att styra din egen applikationslogik.)

```csharp
public short AcceptNode(Node n)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| n | Node | nod för att kontrollera om den passerar filtret eller inte. |

### Returvärde

en konstant för att bestämma om noden är accepterad, avvisad eller överhoppad, enligt definitionen ovan.

### Se även

* class [Node](../../../aspose.html.dom/node/)
* interface [INodeFilter](../)
* namnutrymme [Aspose.Html.Dom.Traversal](../../inodefilter/)
* hopsättning [Aspose.HTML](../../../)



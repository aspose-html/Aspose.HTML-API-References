---
title: "INodeFilter.AcceptNode"
second_title: "Aspose.HTML für Java API-Referenz"
description: "INodeFilter‑Methode. Prüft, ob ein bestimmter Knoten in der logischen Ansicht eines TreeWalker oder NodeIterator sichtbar ist. Diese Funktion wird von der Implementierung von TreeWalker und NodeIterator aufgerufen; sie wird normalerweise nicht direkt vom Benutzercode aufgerufen. Sie können sie jedoch verwenden, wenn Sie denselben Filter zur Steuerung Ihrer Anwendungslogik einsetzen möchten."
type: docs

url: /de/java/com.aspose.html.dom.traversal/inodefilter/acceptnode/
---
## INodeFilter.AcceptNode method

Prüft, ob ein bestimmter Knoten in der logischen Ansicht eines TreeWalker oder NodeIterator sichtbar ist. Diese Funktion wird von der Implementierung von TreeWalker und NodeIterator aufgerufen; sie wird normalerweise nicht direkt aus dem Benutzercode heraus aufgerufen. (Obwohl Sie dies tun könnten, wenn Sie denselben Filter verwenden möchten, um Ihre Anwendungslogik zu steuern.)

```java
public short AcceptNode(Node n)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| n | Node | Knoten, der überprüft werden soll, ob er den Filter besteht oder nicht. |

### Rückgabewert

eine Konstante, um zu bestimmen, ob der Knoten akzeptiert, abgelehnt oder übersprungen wird, wie oben definiert.

### Siehe auch

* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeFilter](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---
title: "NodeFilter.AcceptNode"
second_title: "Aspose.HTML für Java API-Referenz"
description: "NodeFilter-Methode. Prüft, ob ein bestimmter Knoten in der logischen Ansicht eines TreeWalker oder NodeIterator sichtbar ist. Diese Funktion wird von der Implementierung von TreeWalker und NodeIterator aufgerufen; sie wird normalerweise nicht direkt vom Benutzercode aufgerufen. Sie können dies jedoch tun, wenn Sie denselben Filter verwenden möchten, um Ihre Anwendungslogik zu steuern."
type: docs

url: /de/java/com.aspose.html.dom.traversal.filters/nodefilter/acceptnode/
---
## NodeFilter.AcceptNode method

Prüft, ob ein bestimmter Knoten in der logischen Ansicht eines TreeWalker oder NodeIterator sichtbar ist. Diese Funktion wird von der Implementierung von TreeWalker und NodeIterator aufgerufen; sie wird normalerweise nicht direkt aus dem Benutzercode heraus aufgerufen. (Obwohl Sie dies tun könnten, wenn Sie denselben Filter verwenden möchten, um Ihre eigene Anwendungslogik zu steuern.)

```java
public abstract short AcceptNode(Node n)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| n | Node | Knoten, der überprüft werden soll, ob er den Filter besteht oder nicht. |

### Rückgabewert

Eine Konstante, die bestimmt, ob der Knoten akzeptiert, abgelehnt oder übersprungen wird, wie oben definiert.

### Siehe auch

* class [Node](../../../com.aspose.html.dom/node/)
* class [NodeFilter](../)
* package [com.aspose.html.dom.traversal.filters](../../../com.aspose.html.dom.traversal.filters/)
* package [Aspose.HTML](../../../)

---
title: "Node.RemoveChild"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Node-Methode. Die removeChild‑Methode des Node-Interfaces entfernt einen Kindknoten aus dem DOM und gibt den entfernten Knoten zurück."
type: docs

url: /de/java/com.aspose.html.dom/node/removechild/
---
## Node.RemoveChild method

Die Methode `removeChild()` des Node-Interfaces entfernt einen Kindknoten aus dem DOM und gibt den entfernten Knoten zurück.

Hinweis: Solange eine Referenz auf das entfernte Kind gehalten wird, existiert es weiterhin im Speicher, ist jedoch nicht mehr Teil des DOM. Es kann später im Code erneut verwendet werden. Wenn der Rückgabewert von removeChild() nicht gespeichert wird und keine weitere Referenz gehalten wird, wird es nach kurzer Zeit automatisch aus dem Speicher gelöscht.

```java
public Node RemoveChild(Node child)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| child | Node | Ein [`Node`](../), das der zu entfernende Kindknoten aus dem DOM ist. |

### Rückgabewert

Im Gegensatz zu [`Node.cloneNode()`](../clonenode/) bewahrt der Rückgabewert die damit verbundenen [`EventListener`](../../../com.aspose.html.dom.events/ieventlistener/)‑Objekte.

### Siehe auch

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

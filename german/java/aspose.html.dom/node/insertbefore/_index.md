---
title: "Node.InsertBefore"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Node-Methode. Die insertBefore-Methode des Node-Interfaces fügt einen Knoten vor einem Referenzknoten als Kind eines angegebenen Elternknotens ein."
type: docs

url: /de/java/com.aspose.html.dom/node/insertbefore/
---
## Node.InsertBefore method

Die insertBefore()-Methode des Node-Interface fügt einen Knoten vor einem Referenzknoten als Kind eines angegebenen Elternknotens ein.

Wenn der angegebene Knoten bereits im Dokument existiert, verschiebt insertBefore() ihn von seiner aktuellen Position zur neuen Position. (Das heißt, er wird automatisch von seinem bestehenden Elternknoten entfernt, bevor er an den angegebenen neuen Elternknoten angehängt wird.)

Das bedeutet, dass ein Knoten nicht gleichzeitig an zwei Stellen im Dokument sein kann.

```java
public Node InsertBefore(Node node, Node child)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Knoten | Node | Der einzufügende Knoten. |
| Kind | Node | Der Knoten, vor dem newNode eingefügt wird. Ist er null, wird newNode am Ende der Kindknoten von node eingefügt. |

### Rückgabewert

Gibt das hinzugefügte Kind zurück (es sei denn, newNode ist ein [`DocumentFragment`](../../documentfragment/), in diesem Fall wird das leere [`DocumentFragment`](../../documentfragment/) zurückgegeben).

### Siehe auch

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

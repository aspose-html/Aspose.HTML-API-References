---
title: "Node.AppendChild"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Node-Methode. Die appendChild-Methode des Node-Interfaces fügt einen Knoten am Ende der Kindliste eines angegebenen Elternknotens hinzu. Wenn das übergebene Kind eine Referenz zu einem bereits im Dokument vorhandenen Knoten ist, verschiebt appendChild ihn von seiner aktuellen Position zur neuen Position; es ist nicht erforderlich, den Knoten vor dem Anhängen an einen anderen Knoten aus seinem Elternknoten zu entfernen."
type: docs

url: /de/java/com.aspose.html.dom/node/appendchild/
---
## Node.AppendChild method

Die appendChild()-Methode des Node-Interface fügt einen Knoten am Ende der Kindliste eines angegebenen Elternknotens hinzu. Wenn das angegebene Kind eine Referenz zu einem bereits im Dokument vorhandenen Knoten ist, verschiebt appendChild() ihn von seiner aktuellen Position zur neuen Position (es ist nicht erforderlich, den Knoten vor dem Anhängen an einen anderen Knoten aus seinem Elternknoten zu entfernen).

Das bedeutet, dass ein Knoten nicht gleichzeitig an zwei Stellen im Dokument sein kann. Hat der Knoten bereits einen Elternknoten, wird er zuerst entfernt und dann an der neuen Position angehängt. Die [`Node.cloneNode()`](../clonenode/)-Methode kann verwendet werden, um vor dem Anhängen an den neuen Elternknoten eine Kopie des Knotens zu erstellen. Mit [`cloneNode`](../clonenode/) erstellte Kopien werden nicht automatisch synchron gehalten.

```java
public Node AppendChild(Node node)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Knoten | Node | Der Knoten, der an den angegebenen Elternknoten (häufig ein Element) angehängt wird. |

### Rückgabewert

Ein Node, der das angehängte Kind (aChild) ist, außer wenn aChild ein [`DocumentFragment`](../../documentfragment/) ist; in diesem Fall wird das leere [`DocumentFragment`](../../documentfragment/) zurückgegeben.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [dOMException](../../domexception/) | Wird ausgelöst, wenn die Einschränkungen des DOM-Baums verletzt werden. |

### Siehe auch

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

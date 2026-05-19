---
title: "Node.RemoveChild"
second_title: "Aspose.HTML voor Java API-referentie"
description: "Node methode. De removeChild‑methode van de Node-interface verwijdert een kindnode uit de DOM en retourneert de verwijderde node"
type: docs

url: /nl/java/com.aspose.html.dom/node/removechild/
---
## Node.RemoveChild method

De removeChild()-methode van de Node-interface verwijdert een kindknooppunt uit de DOM en retourneert het verwijderde knooppunt.

Opmerking: zolang er een referentie naar het verwijderde kind wordt behouden, blijft het in het geheugen bestaan, maar maakt het geen deel meer uit van de DOM. Het kan later in de code nog steeds worden hergebruikt. Als de retourwaarde van removeChild() niet wordt opgeslagen en er geen andere referentie wordt bewaard, wordt het na korte tijd automatisch uit het geheugen verwijderd.

```java
public Node RemoveChild(Node child)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| child | Node | Een [`Node`](../) die de kindnode is die uit de DOM moet worden verwijderd. |

### Retourwaarde

In tegenstelling tot [`Node.cloneNode()`](../clonenode/) behoudt de retourwaarde de gekoppelde [`EventListener`](../../../com.aspose.html.dom.events/ieventlistener/)‑objecten.

### Zie ook

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

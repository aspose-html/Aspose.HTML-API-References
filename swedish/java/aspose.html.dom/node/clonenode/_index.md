---
title: "Node.CloneNode"
second_title: "Aspose.HTML för Java API-referens"
description: "Node‑metod. cloneNode‑metoden i Node‑gränssnittet returnerar en duplikat av den nod som metoden anropades på. Dess parameter styr om underträdet som finns i en nod också klonas eller inte."
type: docs

url: /sv/java/com.aspose.html.dom/node/clonenode/
---
## CloneNode() {#clonenode}

cloneNode()-metoden i Node-gränssnittet returnerar en duplikat av den nod som metoden anropades på. Dess parameter styr om underträdet som finns i en nod också klonas eller inte.

Att klona en nod kopierar alla dess attribut och deras värden, inklusive inbyggda (inline) lyssnare. Den kopierar inte händelselyssnare som lagts till med [`addEventListener()`](../../../com.aspose.html.dom.events/ieventtarget/addeventlistener/) eller de som tilldelats elementegenskaper (t.ex. node.onclick = someFunction). Dessutom kopieras den målade bilden inte för ett [`&lt;canvas&gt;`](../../../com.aspose.html/htmlcanvaselement/)‑element.

```java
public Node CloneNode()
```

### Returvärde

Den nya [`Node`](../) klonad. Den klonade noden har ingen förälder och är inte en del av dokumentet förrän den läggs till i en annan nod som är en del av dokumentet, med hjälp av [`Node.appendChild()`](../appendchild/) eller en liknande metod.

### Se även

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CloneNode(bool) {#clonenode_1}

cloneNode()-metoden i Node-gränssnittet returnerar en duplikat av den nod som metoden anropades på. Dess parameter styr om underträdet som finns i en nod också klonas eller inte.

Att klona en nod kopierar alla dess attribut och deras värden, inklusive inbyggda (inline) lyssnare. Den kopierar inte händelselyssnare som lagts till med [addEventListener()](M:com.aspose.html.dom.events.IEventTarget.AddEventListener(System.String,com.aspose.html.dom.events.IEventListener)) eller de som tilldelats elementegenskaper (t.ex. node.onclick = someFunction). Dessutom kopieras den målade bilden inte för ett [&lt;canvas&gt;](T:Aspose.Html.HTMLCanvasElement)‑element.

```java
public Node CloneNode(bool deep)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| deep | Boolean | Om true, så kopieras noden och hela dess underträd, inklusive text som kan finnas i barnnoder av typen [`Text`](../../text/). |

### Returvärde

Den nya [Node](T:com.aspose.html.dom.Node) klonad. Den klonade noden har ingen förälder och är inte en del av dokumentet förrän den läggs till i en annan nod som är en del av dokumentet, med hjälp av [Node.appendChild()](M:com.aspose.html.dom.Node.AppendChild(com.aspose.html.dom.Node)) eller en liknande metod.

### Se även

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

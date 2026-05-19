---
title: "Node.CloneNode"
second_title: "Aspose.HTML voor Java API-referentie"
description: "Node-methode. De cloneNode‑methode van de Node‑interface retourneert een duplicaat van het knooppunt waarop deze methode is aangeroepen. De parameter bepaalt of de subboom die in een knooppunt is opgenomen ook wordt gekloond of niet."
type: docs

url: /nl/java/com.aspose.html.dom/node/clonenode/
---
## CloneNode() {#clonenode}

De cloneNode()‑methode van de Node‑interface retourneert een duplicaat van de knoop waarop deze methode is aangeroepen. De parameter bepaalt of de in een knoop aanwezige subboom ook wordt gekloond al dan niet.

Het klonen van een knooppunt kopieert al zijn attributen en hun waarden, inclusief intrinsieke (inline) listeners. Het kopieert geen event‑listeners die zijn toegevoegd met [`addEventListener()`](../../../com.aspose.html.dom.events/ieventtarget/addeventlistener/) of die zijn toegewezen aan elementeigenschappen (bijv. node.onclick = someFunction). Bovendien wordt voor een [`&lt;canvas&gt;`](../../../com.aspose.html/htmlcanvaselement/) element de geschilderde afbeelding niet gekopieerd.

```java
public Node CloneNode()
```

### Retourwaarde

De nieuwe [`Node`](../) is gekloond. Het gekloonde knooppunt heeft geen ouder en maakt geen deel uit van het document, totdat het wordt toegevoegd aan een ander knooppunt dat deel uitmaakt van het document, met behulp van [`Node.appendChild()`](../appendchild/) of een vergelijkbare methode.

### Zie ook

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CloneNode(bool) {#clonenode_1}

De cloneNode()‑methode van de Node‑interface retourneert een duplicaat van de knoop waarop deze methode is aangeroepen. De parameter bepaalt of de in een knoop aanwezige subboom ook wordt gekloond al dan niet.

Het klonen van een knooppunt kopieert al zijn attributen en hun waarden, inclusief intrinsieke (inline) listeners. Het kopieert geen event‑listeners die zijn toegevoegd met [addEventListener()](M:com.aspose.html.dom.events.IEventTarget.AddEventListener(System.String,com.aspose.html.dom.events.IEventListener)) of die zijn toegewezen aan elementeigenschappen (bijv. node.onclick = someFunction). Bovendien wordt voor een [&lt;canvas&gt;](T:Aspose.Html.HTMLCanvasElement) element de geschilderde afbeelding niet gekopieerd.

```java
public Node CloneNode(bool deep)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| deep | Boolean | Indien true, wordt het knooppunt en zijn volledige subboom, inclusief tekst die zich mogelijk in onderliggende [`Text`](../../text/) knooppunten bevindt, ook gekopieerd. |

### Retourwaarde

De nieuwe [Node](T:com.aspose.html.dom.Node) is gekloond. Het gekloonde knooppunt heeft geen ouder en maakt geen deel uit van het document, totdat het wordt toegevoegd aan een ander knooppunt dat deel uitmaakt van het document, met behulp van [Node.appendChild()](M:com.aspose.html.dom.Node.AppendChild(com.aspose.html.dom.Node)) of een vergelijkbare methode.

### Zie ook

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

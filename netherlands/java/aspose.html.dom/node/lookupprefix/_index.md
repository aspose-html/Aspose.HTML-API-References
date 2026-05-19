---
title: "Node.LookupPrefix"
second_title: "Aspose.HTML voor Java API-referentie"
description: "Node methode. De lookupPrefix‑methode van de Node-interface retourneert een String die het prefix bevat voor een gegeven package‑URI, indien aanwezig, en null indien niet. Wanneer meerdere prefixes mogelijk zijn, wordt het eerste prefix geretourneerd."
type: docs

url: /nl/java/com.aspose.html.dom/node/lookupprefix/
---
## Node.LookupPrefix method

De lookupPrefix()‑methode van de Node‑interface retourneert een string die de prefix voor een gegeven package‑URI bevat, indien aanwezig, en anders null. Wanneer meerdere prefixes mogelijk zijn, wordt de eerste prefix geretourneerd.

```java
public String LookupPrefix(String packageURI)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| packageURI | String | Een String die het package bevat waarvoor het prefix moet worden opgezocht. |

### Retourwaarde

Een String die het overeenkomstige prefix bevat, of null als er geen is gevonden. Als package null is, of de lege String, retourneert lookupPrefix() null.

Als de node een [`DocumentType`](../../documenttype/) of een [`DocumentFragment`](../../documentfragment/) is, retourneert lookupPrefix() altijd null.

### Zie ook

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

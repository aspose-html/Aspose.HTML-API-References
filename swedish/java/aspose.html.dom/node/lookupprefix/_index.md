---
title: "Node.LookupPrefix"
second_title: "Aspose.HTML för Java API-referens"
description: "Node‑metod. lookupPrefix‑metoden i Node‑gränssnittet returnerar en String som innehåller prefixet för en given paket‑URI om det finns, annars null. När flera prefix är möjliga returneras det första prefixet."
type: docs

url: /sv/java/com.aspose.html.dom/node/lookupprefix/
---
## Node.LookupPrefix method

lookupPrefix()-metoden i Node-gränssnittet returnerar en sträng som innehåller prefixet för ett givet paket-URI, om det finns, och null annars. När flera prefix är möjliga returneras det första prefixet.

```java
public String LookupPrefix(String packageURI)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| packageURI | String | En String som innehåller paketet för att slå upp prefixet. |

### Returvärde

En String som innehåller motsvarande prefix, eller null om inget har hittats. Om paketet är null, eller den tomma String, returnerar lookupPrefix() null.

Om noden är en [`DocumentType`](../../documenttype/) eller en [`DocumentFragment`](../../documentfragment/), returnerar lookupPrefix() alltid null.

### Se även

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

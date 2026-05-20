---
title: "Document.GetElementById"
second_title: "Aspose.HTML för Java API-referens"
description: "Document‑metod. Document‑metoden getElementById returnerar ett Element‑objekt som representerar elementet vars id‑egenskap matchar den angivna Strängen. Eftersom element‑ID:n måste vara unika om de anges är de ett användbart sätt att snabbt få åtkomst till ett specifikt element."
type: docs

url: /sv/java/com.aspose.html.dom/document/getelementbyid/
---
## Document.GetElementById method

Document‑metoden getElementById() returnerar ett [`Element`](../../element/)‑objekt som representerar elementet vars id‑egenskap matchar den angivna Strängen. Eftersom element‑ID:n måste vara unika om de anges är de ett användbart sätt att snabbt få åtkomst till ett specifikt element.

Om du behöver få åtkomst till ett element som inte har ett ID kan du använda querySelector() för att hitta elementet med någon selector.

```java
public Element GetElementById(String elementId)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| elementId | String | ID:t för elementet som ska lokaliseras. ID:t är en skiftlägeskänslig Sträng som är unik inom dokumentet; endast ett element kan ha ett givet ID. |

### Returvärde

Ett [`Element`](../../element/)‑objekt som beskriver DOM‑elementet som matchar det angivna ID:t, eller null om inget matchande element hittades i dokumentet.

## Anmärkningar

Se den officiella [specifikationen](https://dom.spec.whatwg.org/#dom-nonelementparentnode-getelementbyid).

Praktiskt webbutvecklingsinnehåll kan hittas på [w3schools](https://www.w3schools.com/jsref/met_document_getelementbyid.asp).

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Exempel

```java
// HTML‑innehåll
<div id="uniqueIdentifier">Container with ID - identifier</div>

// C#‑kod
import System;
import Aspose.Html;
import com.aspose.html.dom;
...
	using (var document = new HTMLDocument(inputHtmlPath))
		{
			Element element = document.GetElementById("uniqueIdentifier");
			HTMLDivElement divElement = (HTMLDivElement) element;
			Console.WriteLine(divElement.InnerHTML);

			// Användarkod placeras här
   }
```

// Konsolutdata

Behållare med ID - identifierare

*inputHtmlPath - user input html file path

### Se även

* class [Element](../../element/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

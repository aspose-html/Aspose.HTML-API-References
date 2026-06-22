---
title: "Element.GetElementsByTagName"
second_title: "Aspose.HTML voor Java API-referentie"
description: "Element-methode. Retourneert een HTMLCollection-object dat alle elementen met een opgegeven tagnaam bevat in documentvolgorde."
type: docs

url: /nl/java/com.aspose.html.dom/element/getelementsbytagname/
---
## Element.GetElementsByTagName method

Retourneert [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) object dat alle [`elements`](../) met een opgegeven tagnaam bevat, in documentvolgorde.

```java
public HTMLCollection GetElementsByTagName(String name)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | String | De tagnaam. Stringrepresentatie van de tagnaam. |

### Retourwaarde

Een [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) object is een array-achtig lijst van [`elements`](../).

## Opmerkingen

Verwijs naar de officiële [spec](https://dom.spec.whatwg.org/#dom-element-getelementsbytagname).

U bent misschien ook geïnteresseerd in de [documentatie](https://docs.aspose.com/html/net/).

Je kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Voorbeelden

```java
# Html input content
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Title</title>
</head>
<body>
<div id="divElementContainerId">
	<p class="pStyle">The paragraph styled pStyle class content...</p>
	<p>The second paragraph content...</p>
	<p>The third paragraph content...</p>
	<div class="pStyle">The div element styled pStyle class...</div>
</div>
</body>
</html>

# C# code
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	// Gebruikerscode komt hier

	HTMLCollection htmlCollection = document.GetElementsByTagName("p");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}
         
	// Gebruikerscode komt hier
}
```

*inputHtmlPath - user input html file.

# Console output

Gevonden: 3

De alinea met de stijl pStyle-klasse inhoud...

De inhoud van de tweede alinea...

De inhoud van de derde alinea...

### Zie ook

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---
title: "Element.GetElementsByTagNameNS"
second_title: "Aspose.HTML voor Java API-referentie"
description: "Element-methode. Retourneert een HTMLCollection‑object dat alle elementen met een opgegeven lokale naam en pakket‑URI‑string bevat, in documentvolgorde."
type: docs

url: /nl/java/com.aspose.html.dom/element/getelementsbytagnamens/
---
## Element.GetElementsByTagNameNS method

Retourneert een [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) object dat alle [`elements`](../) bevat met een opgegeven lokale naam en pakket‑URI‑string, in documentvolgorde.

```java
public HTMLCollection GetElementsByTagNameNS(String packageURI, String localName)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| packageURI | String | De representatie van de pakket‑URI‑string. |
| localName | String | String‑representatie van de lokale naam. |

### Retourwaarde

Een [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) object is een array-achtig overzicht van [`elements`](../).

## Opmerkingen

Zie de officiële [spec](https://dom.spec.whatwg.org/#dom-element-getelementsbytagnamens).

U bent misschien ook geïnteresseerd in de [documentatie](https://docs.aspose.com/html/net/).

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Voorbeelden

```java
# .xhtml input file content
<!DOCTYPE html>
<html lang="en"
   xmlns="http://www.w3.org/1999/xhtml"
   xmlns:custom="http://www.company.com">
<head>
	<meta charset="UTF-8"/>
	<link rel="stylesheet" href="/styles/main.css"/>
	<title>Title</title>
</head>
<body>
<custom:customtag>
	Custom package custom tag content goes here...
</custom:customtag>
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

	HTMLCollection htmlCollection = document.GetElementsByTagNameNS("http://www.company.com", "customtag");
	Console.WriteLine($"Found: {htmlCollection.Length}");
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}

	// Gebruikerscode komt hier
}
```

*inputHtmlPath - user input xhtml file path.

# Console output

Gevonden: 1

Aangepaste pakket‑aangepaste taginhoud gaat hier...

### Zie ook

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

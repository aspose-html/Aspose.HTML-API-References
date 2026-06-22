---
title: "Element.GetElementsByClassName"
second_title: "Aspose.HTML voor Java API-referentie"
description: "Element methode. Retourneert een HTMLCollection‑object dat alle elementen binnen het element bevat die alle in het argument opgegeven klassen hebben"
type: docs

url: /nl/java/com.aspose.html.dom/element/getelementsbyclassname/
---
## Element.GetElementsByClassName method

Retourneert [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) object dat alle elementen binnen [`element`](../) bevat die alle in het argument opgegeven klassen hebben.

```java
public HTMLCollection GetElementsByClassName(String classNames)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| classNames | String | De String String die een ongeordende verzameling van unieke door spaties gescheiden tokens bevat die klassen (klassenamen) vertegenwoordigen |

### Retourwaarde

Een [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) object is een array-achtig lijst van [`elements`](../).

## Opmerkingen

Verwijs naar de officiële [spec](https://dom.spec.whatwg.org/#dom-element-getelementsbyclassname).

U bent misschien ook geïnteresseerd in de [documentatie](https://docs.aspose.com/html/net/).

Je kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Voorbeelden

```java
# HTML source content
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

	Element container = document.GetElementById("divElementContainerId");
	HTMLCollection htmlCollection = container.GetElementsByClassName("pStyle");

	Console.WriteLine($"Found: {htmlCollection.Length}");
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}

	// Gebruikerscode komt hier
}
```

*inputHtmlPath - user input html file path.

# Console output

Gevonden: 2

De alinea met de stijl pStyle-klasse inhoud...

Het div-element gestyled met de pStyle-klasse...

### Zie ook

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

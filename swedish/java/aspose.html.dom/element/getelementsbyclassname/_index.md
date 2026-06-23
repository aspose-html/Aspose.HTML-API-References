---
title: "Element.GetElementsByClassName"
second_title: "Aspose.HTML för Java API-referens"
description: "Element-metod. Returnerar ett HTMLCollection‑objekt som innehåller alla element inom elementet som har alla de klasser som anges i argumentet."
type: docs

url: /sv/java/com.aspose.html.dom/element/getelementsbyclassname/
---
## Element.GetElementsByClassName method

Returnerar [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/)‑objekt som innehåller alla element inom [`element`](../) som har alla de klasser som anges i argumentet.

```java
public HTMLCollection GetElementsByClassName(String classNames)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| classNames | String | String String som innehåller en oordnad uppsättning av unika blankstegsseparerade token som representerar klasser (klassnamn) |

### Returvärde

Ett [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) objekt är en arrayliknande lista av [`elements`](../).

## Anmärkningar

Se den officiella [spec](https://dom.spec.whatwg.org/#dom-element-getelementsbyclassname).

Du kan också vara intresserad av [dokumentation](https://docs.aspose.com/html/net/).

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Exempel

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
	// Användarkod placeras här

	Element container = document.GetElementById("divElementContainerId");
	HTMLCollection htmlCollection = container.GetElementsByClassName("pStyle");

	Console.WriteLine($"Found: {htmlCollection.Length}");
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}

	// Användarkod placeras här
}
```

*inputHtmlPath - user input html file path.

# Console output

Hittad: 2

Paragraphen med pStyle-klassen stilade innehåll...

Div‑elementet med pStyle‑klassen...

### Se även

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

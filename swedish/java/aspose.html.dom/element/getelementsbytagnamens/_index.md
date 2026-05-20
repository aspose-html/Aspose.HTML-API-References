---
title: "Element.GetElementsByTagNameNS"
second_title: "Aspose.HTML för Java API-referens"
description: "Element-metod. Returnerar ett HTMLCollection-objekt som innehåller alla element med ett givet lokalt namn och paket-URI-sträng i dokumentordning."
type: docs

url: /sv/java/com.aspose.html.dom/element/getelementsbytagnamens/
---
## Element.GetElementsByTagNameNS method

Returnerar [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) objekt som innehåller alla [`elements`](../) med ett givet lokalt namn och paket-URI-sträng i dokumentordning.

```java
public HTMLCollection GetElementsByTagNameNS(String packageURI, String localName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| packageURI | String | Paket-URI-strängens representation. |
| localName | String | Strängrepresentation av lokalt namn. |

### Returvärde

Ett [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) objekt är en arrayliknande lista av [`elements`](../).

## Anmärkningar

Se den officiella [spec](https://dom.spec.whatwg.org/#dom-element-getelementsbytagnamens).

Du kan också vara intresserad av [dokumentation](https://docs.aspose.com/html/net/).

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Exempel

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
	// Användarkod placeras här

	HTMLCollection htmlCollection = document.GetElementsByTagNameNS("http://www.company.com", "customtag");
	Console.WriteLine($"Found: {htmlCollection.Length}");
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}

	// Användarkod placeras här
}
```

*inputHtmlPath - user input xhtml file path.

# Console output

Hittad: 1

Anpassat paket, anpassat tagg-innehåll placeras här...

### Se även

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

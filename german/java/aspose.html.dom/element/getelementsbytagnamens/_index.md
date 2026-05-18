---
title: "Element.GetElementsByTagNameNS"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Elementmethode. Gibt ein HTMLCollection-Objekt zurück, das alle Elemente mit einem angegebenen lokalen Namen und Paket-URI-String in Dokumentreihenfolge enthält"
type: docs

url: /de/java/com.aspose.html.dom/element/getelementsbytagnamens/
---
## Element.GetElementsByTagNameNS method

Gibt ein [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/)‑Objekt zurück, das alle [`elements`](../) mit einem angegebenen lokalen Namen und Paket‑URI‑String in Dokumentreihenfolge enthält.

```java
public HTMLCollection GetElementsByTagNameNS(String packageURI, String localName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| packageURI | String | Die Darstellung des Paket‑URI‑Strings. |
| localName | String | String‑Darstellung des lokalen Namens. |

### Rückgabewert

Ein [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/)‑Objekt ist eine array‑ähnliche Liste von [`elements`](../).

## Hinweise

Siehe die offizielle [spec](https://dom.spec.whatwg.org/#dom-element-getelementsbytagnamens).

Vielleicht sind Sie auch an der [Dokumentation](https://docs.aspose.com/html/net/) interessiert.

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) herunterladen.

## Beispiele

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
	// Benutzercode kommt hier hin

	HTMLCollection htmlCollection = document.GetElementsByTagNameNS("http://www.company.com", "customtag");
	Console.WriteLine($"Found: {htmlCollection.Length}");
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}

	// Benutzercode kommt hier hin
}
```

*inputHtmlPath - user input xhtml file path.

# Console output

Gefunden: 1

Benutzerdefinierter Paket‑Custom‑Tag‑Inhalt kommt hier hin...

### Siehe auch

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

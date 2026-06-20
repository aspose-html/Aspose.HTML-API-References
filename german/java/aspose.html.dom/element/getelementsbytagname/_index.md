---
title: "Element.GetElementsByTagName"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Element-Methode. Gibt ein HTMLCollection-Objekt zurück, das alle Elemente mit einem bestimmten Tag-Namen in Dokumentreihenfolge enthält"
type: docs

url: /de/java/com.aspose.html.dom/element/getelementsbytagname/
---
## Element.GetElementsByTagName method

Gibt ein [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/)‑Objekt zurück, das alle [`elements`](../) mit einem bestimmten Tag-Namen in Dokumentreihenfolge enthält.

```java
public HTMLCollection GetElementsByTagName(String name)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | String | Der Tag-Name. Zeichenkettenrepräsentation des Tag-Namens. |

### Rückgabewert

Ein [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/)‑Objekt ist eine array‑ähnliche Liste von [`elements`](../).

## Hinweise

Beziehen Sie sich auf die offizielle [Spezifikation](https://dom.spec.whatwg.org/#dom-element-getelementsbytagname).

Vielleicht sind Sie auch an der [Dokumentation](https://docs.aspose.com/html/net/) interessiert.

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) herunterladen.

## Beispiele

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
	// Benutzercode kommt hierher

	HTMLCollection htmlCollection = document.GetElementsByTagName("p");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}
         
	// Benutzercode kommt hierher
}
```

*inputHtmlPath - user input html file.

# Console output

Gefunden: 3

Der Absatz mit der Klasse pStyle enthält...

Der Inhalt des zweiten Absatzes...

Der Inhalt des dritten Absatzes...

### Siehe auch

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

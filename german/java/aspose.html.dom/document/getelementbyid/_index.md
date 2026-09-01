---
title: "Document.GetElementById"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Document-Methode. Die Document-Methode getElementById gibt ein Element-Objekt zurück, das das Element darstellt, dessen id-Eigenschaft mit dem angegebenen String übereinstimmt. Da Element-IDs, falls angegeben, eindeutig sein müssen, sind sie eine nützliche Möglichkeit, schnell auf ein bestimmtes Element zuzugreifen."
type: docs

url: /de/java/com.aspose.html.dom/document/getelementbyid/
---
## Document.GetElementById method

Die Document-Methode getElementById() gibt ein [`Element`](../../element/)‑Objekt zurück, das das Element darstellt, dessen id‑Eigenschaft mit dem angegebenen String übereinstimmt. Da Element-IDs, falls angegeben, eindeutig sein müssen, sind sie eine nützliche Möglichkeit, schnell auf ein bestimmtes Element zuzugreifen.

Wenn Sie Zugriff auf ein Element benötigen, das keine ID hat, können Sie querySelector() verwenden, um das Element mit einem beliebigen Selektor zu finden.

```java
public Element GetElementById(String elementId)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| elementId | String | Die ID des zu lokalisierenden Elements. Die ID ist ein case‑sensitiver String, der innerhalb des Dokuments eindeutig ist; nur ein Element kann eine bestimmte ID besitzen. |

### Rückgabewert

Ein [`Element`](../../element/)‑Objekt, das das DOM‑Element beschreibt, das der angegebenen ID entspricht, oder null, wenn kein passendes Element im Dokument gefunden wurde.

## Hinweise

Siehe die offizielle [Spezifikation](https://dom.spec.whatwg.org/#dom-nonelementparentnode-getelementbyid).

Praxisnahe Webentwicklungsinhalte finden Sie bei [w3schools](https://www.w3schools.com/jsref/met_document_getelementbyid.asp).

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) herunterladen.

## Beispiele

```java
// HTML-Inhalt
<div id="uniqueIdentifier">Container with ID - identifier</div>

// C#‑Code
import System;
import Aspose.Html;
import com.aspose.html.dom;
...
	using (var document = new HTMLDocument(inputHtmlPath))
		{
			Element element = document.GetElementById("uniqueIdentifier");
			HTMLDivElement divElement = (HTMLDivElement) element;
			Console.WriteLine(divElement.InnerHTML);

			// Benutzercode kommt hierher
   }
```

// Konsolenausgabe

Container mit ID – Bezeichner

*inputHtmlPath - user input html file path

### Siehe auch

* class [Element](../../element/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

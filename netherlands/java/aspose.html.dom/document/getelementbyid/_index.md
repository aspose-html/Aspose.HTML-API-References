---
title: "Document.GetElementById"
second_title: "Aspose.HTML voor Java API-referentie"
description: "Documentmethode. De Document-methode getElementById retourneert een Element-object dat het element vertegenwoordigt waarvan de id-eigenschap overeenkomt met de opgegeven String. Aangezien element-ID's uniek moeten zijn wanneer ze zijn opgegeven, is dit een handige manier om snel toegang te krijgen tot een specifiek element."
type: docs

url: /nl/java/com.aspose.html.dom/document/getelementbyid/
---
## Document.GetElementById method

De Document-methode getElementById() retourneert een [`Element`](../../element/) object dat het element vertegenwoordigt waarvan de id-eigenschap overeenkomt met de opgegeven String. Aangezien element-ID's uniek moeten zijn wanneer ze zijn opgegeven, is dit een handige manier om snel toegang te krijgen tot een specifiek element.

Als je toegang wilt krijgen tot een element dat geen ID heeft, kun je querySelector() gebruiken om het element te vinden met behulp van een willekeurige selector.

```java
public Element GetElementById(String elementId)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| elementId | String | De ID van het te vinden element. De ID is een hoofdlettergevoelige String die uniek is binnen het document; slechts één element kan een bepaalde ID hebben. |

### Retourwaarde

Een [`Element`](../../element/) object dat het DOM-element beschrijft dat overeenkomt met de opgegeven ID, of null als er geen overeenkomend element in het document werd gevonden.

## Opmerkingen

Zie de officiële [spec](https://dom.spec.whatwg.org/#dom-nonelementparentnode-getelementbyid).

Praktische webontwikkelingsinhoud is te vinden op [w3schools](https://www.w3schools.com/jsref/met_document_getelementbyid.asp).

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Voorbeelden

```java
// HTML-inhoud
<div id="uniqueIdentifier">Container with ID - identifier</div>

// C#-code
import System;
import Aspose.Html;
import com.aspose.html.dom;
...
	using (var document = new HTMLDocument(inputHtmlPath))
		{
			Element element = document.GetElementById("uniqueIdentifier");
			HTMLDivElement divElement = (HTMLDivElement) element;
			Console.WriteLine(divElement.InnerHTML);

			// Gebruikerscode komt hier
   }
```

// Console-uitvoer

Container met ID - identificator

*inputHtmlPath - user input html file path

### Zie ook

* class [Element](../../element/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

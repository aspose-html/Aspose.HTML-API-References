---
title: "Document.GetElementsByTagName"
second_title: "Aspose.HTML voor Java API-referentie"
description: "Document-methode. De getElementsByTagName‑methode van de Document‑interface retourneert een HTMLCollection van elementen met de opgegeven tagnaam."
type: docs

url: /nl/java/com.aspose.html.dom/document/getelementsbytagname/
---
## Document.GetElementsByTagName method

De getElementsByTagName‑methode van de [`Document`](../)‑interface retourneert een [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) van elementen met de opgegeven tagnaam.

Het volledige document wordt doorzocht, inclusief het root‑knooppunt. De geretourneerde [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) is live, wat betekent dat deze zichzelf automatisch bijwerkt om gesynchroniseerd te blijven met de DOM‑boom zonder dat document.getElementsByTagName() opnieuw hoeft te worden aangeroepen.

```java
public HTMLCollection GetElementsByTagName(String tagname)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tagnaam | String | Een String die de naam van de elementen vertegenwoordigt. De speciale String \"*\" staat voor alle elementen. |

### Retourwaarde

Een live [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) van gevonden elementen in de volgorde waarin ze in de boom verschijnen.

## Opmerkingen

Zie de officiële [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbytagname).

Praktische webontwikkelingsinhoud is te vinden op [w3schools](https://www.w3schools.com/jsref/met_document_getelementsbytagname.asp).

Je kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Voorbeelden

```java
var elements = document.GetElementsByTagName(name);
```

```java
#HTML content
<div>
	<p class="pStyle">First styled by pStyle class paragraph</p>
	<p class="pStyle">Second styled by pStyle class paragraph</p>
	<p class="pStyle">Third styled by pStyle class paragraph</p>
	<span class="pStyle">Span styled by pStyle</span>
</div>
<div id="smart class">
	<p id="p1" class="ddd kkk">Paragraph styled by class name =ddd kkk=</p>
	<p id="p2" class="ddd fff">Paragraph styled by class name =ddd fff=</p>
	<p id="p3" class="kkk fff">Paragraph styled by class name =kkk fff=</p>
</div>

# C# code
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;

import (var document = new HTMLDocument(inputHtmlPath))
{
    HTMLCollection htmlCollection = document.GetElementsByTagName("p");
    Console.WriteLine($"Found: {htmlCollection.Length}" );
    foreach (Element element in htmlCollection)
    {
      Console.WriteLine(element.InnerHTML);
    }

    // Gebruikerscode komt hier
}
```

# Console output

Gevonden: 6

Eerste gestileerd door pStyle class alinea

Tweede gestileerd door pStyle class alinea

Derde gestileerd door pStyle class alinea

Alinea gestileerd door klassenaam =ddd kkk=

Alinea gestileerd door klassenaam =ddd fff=

Alinea gestileerd door klassenaam =kkk fff=

*inputHtmlPath - user input html file path

### Zie ook

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

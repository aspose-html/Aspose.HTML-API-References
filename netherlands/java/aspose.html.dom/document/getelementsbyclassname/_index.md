---
title: "Document.GetElementsByClassName"
second_title: "Aspose.HTML voor Java API-referentie"
description: "Document‑methode. De getElementsByClassName‑methode van de Document‑interface retourneert een array‑achtig object van alle onderliggende elementen die alle opgegeven klassennamen hebben."
type: docs

url: /nl/java/com.aspose.html.dom/document/getelementsbyclassname/
---
## Document.GetElementsByClassName method

De getElementsByClassName‑methode van de [`Document`](../)‑interface retourneert een array‑achtig object van alle onderliggende elementen die alle opgegeven klassenaam(en) hebben.

Wanneer aangeroepen op het documentobject, wordt het volledige document doorzocht, inclusief de root‑knoop. Je kunt ook getElementsByClassName() aanroepen op elk element; het retourneert alleen elementen die afstammelingen zijn van het opgegeven root‑element met de opgegeven klassenaam(en).

```java
public HTMLCollection GetElementsByClassName(String classNames)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| classNames | String | De String String die een ongeordende verzameling van unieke door spaties gescheiden tokens bevat die klassen (klassenamen) vertegenwoordigen |

### Retourwaarde

Een live [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) van gevonden elementen.

## Opmerkingen

Verwijs naar de officiële [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbyclassname).

Praktijkwebontwikkelingsinhoud kan worden gevonden op [w3schools](https://www.w3schools.com/jsref/met_element_getelementsbyclassname.asp).

Je kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Voorbeelden

```java
var elements = document.GetElementsByClassName("red test");
```

```java
// HTML-inhoud
<div class="custom-class">Customized by css class container</div>

// C#-code
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLCollection htmlCollection = document.GetElementsByClassName("custom-class");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}
         
	// Gebruikerscode komt hier
}
```

// Console-uitvoer

Gevonden: 1

Aangepast door css-klasse container

*inputHtmlPath - user input html file path

```java
// CSS-styling
.ddd{
	padding: 10pt;
}

.kkk{
	background-color: chartreuse;
}

// HTML-inhoud
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
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLCollection htmlCollection = document.GetElementsByClassName("ddd");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
		Console.WriteLine($"Element type: {element.GetType()}");
	}
         
	// Gebruikerscode komt hier
}
```

# Console output

Gevonden: 2

Alinea gestileerd door klassenaam =ddd kkk=

Elementtype: Aspose.Html.HTMLParagraphElement

Alinea gestileerd door klassenaam =ddd fff=

Elementtype: Aspose.Html.HTMLParagraphElement

*inputHtmlPath - user input html file path

```java
// CSS-styling
.pStyle{
  font-
}

# HTML content
<div>
	<p class="pStyle">First styled by pStyle class paragraph</p>
	<p class="pStyle">Second styled by pStyle class paragraph</p>
	<p class="pStyle">Third styled by pStyle class paragraph</p>
	<span class="pStyle">Span styled by pStyle</span>
</div>

# C# code
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLCollection htmlCollection = document.GetElementsByClassName("pStyle");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
		Console.WriteLine($"Element type: {element.GetType()}");
	}
         
	// Gebruikerscode komt hier
}
```

# Console output

Gevonden: 4

Eerste gestileerd door pStyle class alinea

Elementtype: Aspose.Html.HTMLParagraphElement

Tweede gestileerd door pStyle class alinea

Elementtype: Aspose.Html.HTMLParagraphElement

Derde gestileerd door pStyle class alinea

Elementtype: Aspose.Html.HTMLParagraphElement

Span gestyled door pStyle

Elementtype: Aspose.Html.HTMLElement

*inputHtmlPath - user input html file path

### Zie ook

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

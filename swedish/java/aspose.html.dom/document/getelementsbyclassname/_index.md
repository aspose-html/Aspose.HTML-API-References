---
title: "Document.GetElementsByClassName"
second_title: "Aspose.HTML för Java API-referens"
description: "Document‑metod. getElementsByClassName‑metoden i Document‑gränssnittet returnerar ett array‑liknande objekt med alla barn‑element som har alla de angivna klassnamnen"
type: docs

url: /sv/java/com.aspose.html.dom/document/getelementsbyclassname/
---
## Document.GetElementsByClassName method

Den getElementsByClassName‑metoden i [`Document`](../)‑gränssnittet returnerar ett array‑liknande objekt med alla barn‑element som har alla de angivna klassnamnen.

När den anropas på dokumentobjektet söks hela dokumentet, inklusive rotnoden. Du kan också anropa getElementsByClassName() på vilket element som helst; den kommer bara att returnera element som är ättlingar till det angivna rootelementet med de givna klassnamnen.

```java
public HTMLCollection GetElementsByClassName(String classNames)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| classNames | String | Strängen String som innehåller en oordnad uppsättning av unika mellanslagsskiljda token som representerar klasser (klassnamn) |

### Returvärde

En levande [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) av hittade element.

## Anmärkningar

Se den officiella [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbyclassname).

Praktiskt webbutvecklingsinnehåll kan hittas på [w3schools](https://www.w3schools.com/jsref/met_element_getelementsbyclassname.asp).

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Exempel

```java
var elements = document.GetElementsByClassName("red test");
```

```java
// HTML‑innehåll
<div class="custom-class">Customized by css class container</div>

// C#‑kod
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
         
	// Användarkod placeras här
}
```

// Konsolutdata

Hittad: 1

Anpassad av css-klass container

*inputHtmlPath - user input html file path

```java
// CSS-styling
.ddd{
	padding: 10pt;
}

.kkk{
	background-color: chartreuse;
}

// HTML‑innehåll
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
         
	// Användarkod placeras här
}
```

# Console output

Hittad: 2

Stycke stylat av klassnamn =ddd kkk=

Elementtyp: Aspose.Html.HTMLParagraphElement

Stycke stylat av klassnamn =ddd fff=

Elementtyp: Aspose.Html.HTMLParagraphElement

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
         
	// Användarkod placeras här
}
```

# Console output

Hittad: 4

Först stylad av pStyle-klassens stycke

Elementtyp: Aspose.Html.HTMLParagraphElement

Andra stylad av pStyle-klassens stycke

Elementtyp: Aspose.Html.HTMLParagraphElement

Tredje stylad av pStyle-klassens stycke

Elementtyp: Aspose.Html.HTMLParagraphElement

Span stylad av pStyle

Elementtyp: Aspose.Html.HTMLElement

*inputHtmlPath - user input html file path

### Se även

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

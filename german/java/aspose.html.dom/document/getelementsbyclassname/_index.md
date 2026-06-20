---
title: "Document.GetElementsByClassName"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Dokumentmethode. Die getElementsByClassName-Methode des Document-Interfaces gibt ein array-ähnliches Objekt aller Kind-Elemente zurück, die alle angegebenen Klassennamen besitzen."
type: docs

url: /de/java/com.aspose.html.dom/document/getelementsbyclassname/
---
## Document.GetElementsByClassName method

Die getElementsByClassName-Methode des [`Document`](../)-Interfaces gibt ein array-ähnliches Objekt aller Kind-Elemente zurück, die alle angegebenen Klassennamen besitzen.

Wenn sie auf dem Dokumentobjekt aufgerufen wird, wird das gesamte Dokument durchsucht, einschließlich des Wurzelknotens. Sie können getElementsByClassName() auch auf jedem Element aufrufen; es gibt nur Elemente zurück, die Nachkommen des angegebenen Wurzelelements mit dem bzw. den angegebenen Klassennamen sind.

```java
public HTMLCollection GetElementsByClassName(String classNames)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| classNames | String | Der String String, der eine ungeordnete Menge eindeutiger, durch Leerzeichen getrennter Tokens darstellt, die Klassen (Klassennamen) repräsentieren |

### Rückgabewert

Eine Live-[`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) gefundener Elemente.

## Hinweise

Siehe die offizielle [Spezifikation](https://dom.spec.whatwg.org/#dom-document-getelementsbyclassname).

Praxis-Webentwicklungsinhalte können bei [w3schools](https://www.w3schools.com/jsref/met_element_getelementsbyclassname.asp) gefunden werden.

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) herunterladen.

## Beispiele

```java
var elements = document.GetElementsByClassName("red test");
```

```java
// HTML-Inhalt
<div class="custom-class">Customized by css class container</div>

// C#‑Code
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
         
	// Benutzercode kommt hierher
}
```

// Konsolenausgabe

Gefunden: 1

Angepasst durch CSS-Klasse container

*inputHtmlPath - user input html file path

```java
// CSS-Styling
.ddd{
	padding: 10pt;
}

.kkk{
	background-color: chartreuse;
}

// HTML-Inhalt
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
         
	// Benutzercode kommt hierher
}
```

# Console output

Gefunden: 2

Absatz formatiert nach Klassenname =ddd kkk=

Elementtyp: Aspose.Html.HTMLParagraphElement

Absatz formatiert nach Klassenname =ddd fff=

Elementtyp: Aspose.Html.HTMLParagraphElement

*inputHtmlPath - user input html file path

```java
// CSS-Styling
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
         
	// Benutzercode kommt hierher
}
```

# Console output

Gefunden: 4

Erster nach pStyle class formatierter Absatz

Elementtyp: Aspose.Html.HTMLParagraphElement

Zweiter nach pStyle class formatierter Absatz

Elementtyp: Aspose.Html.HTMLParagraphElement

Dritter nach pStyle class formatierter Absatz

Elementtyp: Aspose.Html.HTMLParagraphElement

Span gestylt durch pStyle

Elementtyp: Aspose.Html.HTMLElement

*inputHtmlPath - user input html file path

### Siehe auch

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---
title: "Document.GetElementsByTagName"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Document-Methode. Die getElementsByTagName-Methode des Document-Interfaces gibt eine HTMLCollection von Elementen mit dem angegebenen Tag-Namen zurück."
type: docs

url: /de/java/com.aspose.html.dom/document/getelementsbytagname/
---
## Document.GetElementsByTagName method

Die getElementsByTagName-Methode des [`Document`](../)-Interfaces gibt eine [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) von Elementen mit dem angegebenen Tag-Namen zurück.

Das gesamte Dokument wird durchsucht, einschließlich des Wurzelknotens. Die zurückgegebene [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) ist live, das heißt, sie aktualisiert sich automatisch, um mit dem DOM-Baum synchron zu bleiben, ohne dass document.getElementsByTagName() erneut aufgerufen werden muss.

```java
public HTMLCollection GetElementsByTagName(String tagname)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tagname | String | Ein String, der den Namen der Elemente darstellt. Der spezielle String "*" steht für alle Elemente. |

### Rückgabewert

Eine live [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) gefundener Elemente in der Reihenfolge, in der sie im Baum erscheinen.

## Hinweise

Siehe die offizielle [Spezifikation](https://dom.spec.whatwg.org/#dom-document-getelementsbytagname).

Praxis-Webentwicklungsinhalte finden Sie bei [w3schools](https://www.w3schools.com/jsref/met_document_getelementsbytagname.asp).

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) herunterladen.

## Beispiele

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

    // Benutzercode kommt hier hin
}
```

# Console output

Gefunden: 6

Erster nach pStyle-Klasse formatierter Absatz

Zweiter nach pStyle-Klasse formatierter Absatz

Dritter nach pStyle-Klasse formatierter Absatz

Absatz formatiert nach Klassenname =ddd kkk=

Absatz formatiert nach Klassenname =ddd fff=

Absatz formatiert nach Klassenname =kkk fff=

*inputHtmlPath - user input html file path

### Siehe auch

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

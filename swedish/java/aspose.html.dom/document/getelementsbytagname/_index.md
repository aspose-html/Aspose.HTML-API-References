---
title: "Document.GetElementsByTagName"
second_title: "Aspose.HTML för Java API-referens"
description: "Dokumentmetod. Metoden getElementsByTagName i Document‑gränssnittet returnerar en HTMLCollection av element med det angivna taggnamnet"
type: docs

url: /sv/java/com.aspose.html.dom/document/getelementsbytagname/
---
## Document.GetElementsByTagName method

Metoden getElementsByTagName i [`Document`](../)‑gränssnittet returnerar en [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) av element med det angivna taggnamnet.

Det kompletta dokumentet söks, inklusive rot‑noden. Den returnerade [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) är dynamisk, vilket betyder att den uppdateras automatiskt för att hålla sig i synk med DOM‑trädet utan att behöva anropa document.getElementsByTagName() igen.

```java
public HTMLCollection GetElementsByTagName(String tagname)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tagname | String | En String som representerar namnet på elementen. Den speciella String‑värdet "*" representerar alla element. |

### Returvärde

En dynamisk [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) av hittade element i den ordning de förekommer i trädet.

## Anmärkningar

Se den officiella [specifikationen](https://dom.spec.whatwg.org/#dom-document-getelementsbytagname).

Praktiskt webbutvecklingsinnehåll kan hittas på [w3schools](https://www.w3schools.com/jsref/met_document_getelementsbytagname.asp).

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Exempel

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

    // Användarkod placeras här
}
```

# Console output

Hittade: 6

Först stylad av pStyle-klassens stycke

Andra stylad av pStyle-klassens stycke

Tredje stylad av pStyle-klassens stycke

Stycke stylat av klassnamnet =ddd kkk=

Stycke stylat av klassnamnet =ddd fff=

Stycke stylat av klassnamnet =kkk fff=

*inputHtmlPath - user input html file path

### Se även

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---
title: Document.GetElementsByTagName
second_title: Aspose.HTML for Java API Reference
description: Document method. The getElementsByTagName method of Document interface returns an HTMLCollection of elements with the given tag name
type: docs
weight: 980
url: /java/com.aspose.html.dom/document/getelementsbytagname/
---
## Document.GetElementsByTagName method

The getElementsByTagName method of [`Document`](../) interface returns an [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) of elements with the given tag name.

The complete document is searched, including the root node. The returned [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) is live, meaning that it updates itself automatically to stay in sync with the DOM tree without having to call document.getElementsByTagName() again.

```java
public HTMLCollection GetElementsByTagName(String tagname)
```

| Parameter | Type | Description |
| --- | --- | --- |
| tagname | String | A String representing the name of the elements. The special String "*" represents all elements. |

### Return Value

A live [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) of found elements in the order they appear in the tree.

## Remarks

Refer to official [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbytagname).

Practice web development content can be founded in [w3schools](https://www.w3schools.com/jsref/met_document_getelementsbytagname.asp).

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation).

## Examples

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
import com.aspose.html;
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

    // User code goes here
}
```

# Console output

Found: 6

First styled by pStyle class paragraph

Second styled by pStyle class paragraph

Third styled by pStyle class paragraph

Paragraph styled by class name =ddd kkk=

Paragraph styled by class name =ddd fff=

Paragraph styled by class name =kkk fff=

*inputHtmlPath - user input html file path

### See Also

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../document/)
* package [Aspose.HTML](../../../)

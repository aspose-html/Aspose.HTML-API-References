---
title: Document.GetElementsByClassName
second_title: Aspose.HTML for Java API Reference
description: Document method. The getElementsByClassName method of Document interface returns an array-like object of all child elements which have all of the given class names
type: docs

url: /java/com.aspose.html.dom/document/getelementsbyclassname/
---
## Document.GetElementsByClassName method

The getElementsByClassName method of [`Document`](../) interface returns an array-like object of all child elements which have all of the given class name(s).

When called on the document object, the complete document is searched, including the root node. You may also call getElementsByClassName() on any element; it will return only elements which are descendants of the specified root element with the given class name(s).

```java
public HTMLCollection GetElementsByClassName(String classNames)
```

| Parameter | Type | Description |
| --- | --- | --- |
| classNames | String | The String String that contains an unordered set of unique space-separated tokens representing classes (class names) |

### Return Value

A live [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) of found elements.

## Remarks

Refer to official [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbyclassname).

Practice web development content can be founded in [w3schools](https://www.w3schools.com/jsref/met_element_getelementsbyclassname.asp).

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Examples

```java
var elements = document.GetElementsByClassName("red test");
```

```java
// HTML content
<div class="custom-class">Customized by css class container</div>

// C# code
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
         
	// User code goes here
}
```

// Console output

Found: 1

Customized by css class container

*inputHtmlPath - user input html file path

```java
// CSS styling
.ddd{
	padding: 10pt;
}

.kkk{
	background-color: chartreuse;
}

// HTML content
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
         
	// User code goes here
}
```

# Console output

Found: 2

Paragraph styled by class name =ddd kkk=

Element type: Aspose.Html.HTMLParagraphElement

Paragraph styled by class name =ddd fff=

Element type: Aspose.Html.HTMLParagraphElement

*inputHtmlPath - user input html file path

```java
// CSS styling
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
         
	// User code goes here
}
```

# Console output

Found: 4

First styled by pStyle class paragraph

Element type: Aspose.Html.HTMLParagraphElement

Second styled by pStyle class paragraph

Element type: Aspose.Html.HTMLParagraphElement

Third styled by pStyle class paragraph

Element type: Aspose.Html.HTMLParagraphElement

Span styled by pStyle

Element type: Aspose.Html.HTMLElement

*inputHtmlPath - user input html file path

### See Also

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

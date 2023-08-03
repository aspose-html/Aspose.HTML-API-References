---
title: Element.GetElementsByTagNameNS
second_title: Aspose.HTML for Java API Reference
description: Element method. Returns HTMLCollection object containing all elements with a given local name and package URI String in document order
type: docs
weight: 300
url: /net/com.aspose.html.dom/element/getelementsbytagnamens/
---
## Element.GetElementsByTagNameNS method

Returns [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) object containing all [`elements`](../) with a given local name and package URI String in document order.

```java
public HTMLCollection GetElementsByTagNameNS(String packageURI, String localName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| packageURI | String | The package URI String representation. |
| localName | String | String representation of local name. |

### Return Value

An [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) object is an array-like list of [`elements`](../).

## Remarks

Refer to official [spec](https://dom.spec.whatwg.org/#dom-element-getelementsbytagnamens).

You may also be interested in [documentation](https://docs.aspose.com/html/net/).

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation).

## Examples

```java
# .xhtml input file content
<!DOCTYPE html>
<html lang="en"
   xmlns="http://www.w3.org/1999/xhtml"
   xmlns:custom="http://www.company.com">
<head>
	<meta charset="UTF-8"/>
	<link rel="stylesheet" href="/styles/main.css"/>
	<title>Title</title>
</head>
<body>
<custom:customtag>
	Custom package custom tag content goes here...
</custom:customtag>
</body>
</html>

# C# code
import System;
import com.aspose.html;
import com.aspose.html.Collections;
import com.aspose.html.Dom;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	// User code goes here

	HTMLCollection htmlCollection = document.GetElementsByTagNameNS("http://www.company.com", "customtag");
	Console.WriteLine($"Found: {htmlCollection.Length}");
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}

	// User code goes here
}
```

*inputHtmlPath - user input xhtml file path.

# Console output

Found: 1

Custom package custom tag content goes here...

### See Also

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.Dom](../../element/)
* package [Aspose.HTML](../../../)

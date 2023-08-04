---
title: Element.GetElementsByClassName
second_title: Aspose.HTML for Java API Reference
description: Element method. Returns HTMLCollection object containing all the elements within element that have all the classes specified in argument
type: docs
weight: 280
url: /java/com.aspose.html.dom/element/getelementsbyclassname/
---
## Element.GetElementsByClassName method

Returns [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) object containing all the elements within [`element`](../) that have all the classes specified in argument.

```java
public HTMLCollection GetElementsByClassName(String classNames)
```

| Parameter | Type | Description |
| --- | --- | --- |
| classNames | String | The String String that contains an unordered set of unique space-separated tokens representing classes (class names) |

### Return Value

An [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) object is an array-like list of [`elements`](../).

## Remarks

Refer to official [spec](https://dom.spec.whatwg.org/#dom-element-getelementsbyclassname).

You may also be interested in [documentation](https://docs.aspose.com/html/net/).

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation).

## Examples

```java
# HTML source content
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Title</title>
</head>
<body>
<div id="divElementContainerId">
	<p class="pStyle">The paragraph styled pStyle class content...</p>
	<p>The second paragraph content...</p>
	<p>The third paragraph content...</p>
	<div class="pStyle">The div element styled pStyle class...</div>
</div>
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

	Element container = document.GetElementById("divElementContainerId");
	HTMLCollection htmlCollection = container.GetElementsByClassName("pStyle");

	Console.WriteLine($"Found: {htmlCollection.Length}");
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}

	// User code goes here
}
```

*inputHtmlPath - user input html file path.

# Console output

Found: 2

The paragraph styled pStyle class content...

The div element styled pStyle class...

### See Also

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.Dom](../../element/)
* package [Aspose.HTML](../../../)

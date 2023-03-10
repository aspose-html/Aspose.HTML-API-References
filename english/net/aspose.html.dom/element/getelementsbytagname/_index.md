---
title: Element.GetElementsByTagName
second_title: Aspose.HTML for .NET API Reference
description: Element method. Returns HTMLCollection object containing all elements with a given tag name in document order
type: docs
weight: 290
url: /net/aspose.html.dom/element/getelementsbytagname/
---
## Element.GetElementsByTagName method

Returns [`HTMLCollection`](../../../aspose.html.collections/htmlcollection/) object containing all [`elements`](../) with a given tag name, in document order.

```csharp
public HTMLCollection GetElementsByTagName(string name)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The tag name. String representation of tag name. |

### Return Value

An [`HTMLCollection`](../../../aspose.html.collections/htmlcollection/) object is an array-like list of [`elements`](../).

## Remarks

Refer to official [spec](https://dom.spec.whatwg.org/#dom-element-getelementsbytagname).

You may also be interested in [documentation](https://docs.aspose.com/html/net/).

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Examples

```csharp
# Html input content
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
using System;
using Aspose.Html;
using Aspose.Html.Collections;
using Aspose.Html.Dom;
...
using (var document = new HTMLDocument(inputHtmlPath))
{
	// User code goes here

	HTMLCollection htmlCollection = document.GetElementsByTagName("p");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}
         
	// User code goes here
}
```

*inputHtmlPath - user input html file.

# Console output

Found: 3

The paragraph styled pStyle class content...

The second paragraph content...

The third paragraph content...

### See Also

* class [HTMLCollection](../../../aspose.html.collections/htmlcollection/)
* class [Element](../)
* namespace [Aspose.Html.Dom](../../element/)
* assembly [Aspose.HTML](../../../)

---
title: Element.GetElementsByTagNameNS
second_title: Aspose.HTML for .NET API Reference
description: Element method. Returns HTMLCollection object containing all elements with a given local name and namespace URI string in document order
type: docs
weight: 300
url: /net/aspose.html.dom/element/getelementsbytagnamens/
---
## Element.GetElementsByTagNameNS method

Returns [`HTMLCollection`](../../../aspose.html.collections/htmlcollection/) object containing all [`elements`](../) with a given local name and namespace URI string in document order.

```csharp
public HTMLCollection GetElementsByTagNameNS(string namespaceURI, string localName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| namespaceURI | String | The namespace URI string representation. |
| localName | String | String representation of local name. |

### Return Value

An [`HTMLCollection`](../../../aspose.html.collections/htmlcollection/) object is an array-like list of [`elements`](../).

## Remarks

Refer to official [spec](https://dom.spec.whatwg.org/#dom-element-getelementsbytagnamens).

You may also be interested in [documentation](https://docs.aspose.com/html/net/).

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Examples

```csharp
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
	Custom namespace custom tag content goes here...
</custom:customtag>
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

Custom namespace custom tag content goes here...

### See Also

* class [HTMLCollection](../../../aspose.html.collections/htmlcollection/)
* class [Element](../)
* namespace [Aspose.Html.Dom](../../element/)
* assembly [Aspose.HTML](../../../)

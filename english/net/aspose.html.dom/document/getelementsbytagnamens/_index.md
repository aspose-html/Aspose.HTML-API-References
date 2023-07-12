---
title: Document.GetElementsByTagNameNS
second_title: Aspose.HTML for .NET API Reference
description: Document method. Returns a list of elements with the given tag name belonging to the given namespace. The complete document is searched including the root node
type: docs
weight: 990
url: /net/aspose.html.dom/document/getelementsbytagnamens/
---
## Document.GetElementsByTagNameNS method

Returns a list of elements with the given tag name belonging to the given namespace. The complete document is searched, including the root node.

```csharp
public HTMLCollection GetElementsByTagNameNS(string namespaceURI, string localName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| namespaceURI | String | The namespace URI of elements to look for. |
| localName | String | Either the local name of elements to look for or the special value *, which matches all elements. |

### Return Value

A live [`NodeList`](../../../aspose.html.collections/nodelist/) (but see the note below) of found elements in the order they appear in the tree.

## Remarks

Refer to official [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbytagnamens).

Practice web development content can be founded in [w3schools](https://www.w3schools.com/xml/met_document_getelementsbytagnamens.asp).

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Examples

```csharp
var elements = document.GetElementsByTagNameNS(@namespace, name);
```

```csharp
# HTML content. File extension - xhtml
<!DOCTYPE html>
<html lang="en"
	xmlns="http://www.w3.org/1999/xhtml"
	xmlns:xml="http://www.w3.org/XML/1998/namespace">
...
<xml:uniquetag>
  xml namespace uniquetag content goes here...
</xml:uniquetag>
...
</html>

# C# code
using System;
using Aspose.Html;
using Aspose.Html.Collections;
using Aspose.Html.Dom;
...
using (var document = new HTMLDocument(inputHtmlPath))
{
    HTMLCollection htmlCollection = document.GetElementsByTagNameNS("http://www.w3.org/XML/1998/namespace","uniquetag");
    Console.WriteLine($"Found: {htmlCollection.Length}" );
    foreach (Element element in htmlCollection)
    {
      Console.WriteLine(element.InnerHTML);
    }  
    // User code goes here
}





# Console output

Found: 1

xml namespace uniquetag content goes here...




```

*inputHtmlPath - user input xhtml file path

```csharp
# HTML content. File extension - xhtml
<!DOCTYPE html>
<html lang="en"
   xmlns="http://www.w3.org/1999/xhtml"
   xmlns:custom="http://www.company.com"
   xmlns:xml="http://www.w3.org/XML/1998/namespace">
...
<xml:CATALOG>
	<xml:CD>
    <xml:TITLE>Empire Burlesque</xml:TITLE>
    <xml:ARTIST>Bob Dylan</xml:ARTIST>
    <xml:COUNTRY>USA</xml:COUNTRY>
    <xml:COMPANY>Columbia</xml:COMPANY>
    <xml:PRICE>10.90</xml:PRICE>
    <xml:YEAR>1985</xml:YEAR>
  </xml:CD>
...

# C# code
using System;
using Aspose.Html;
using Aspose.Html.Collections;
using Aspose.Html.Dom;
...
using (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLCollection htmlCollection = 
          document.GetElementsByTagNameNS("http://www.w3.org/XML/1998/namespace", "ARTIST");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}
         
	// User code goes here
}
```

# Console output

Found: 3

Bob Dylan

Bonnie Tyler

Dolly Parton

*inputHtmlPath - user input xhtml file path

### See Also

* class [HTMLCollection](../../../aspose.html.collections/htmlcollection/)
* class [Document](../)
* namespace [Aspose.Html.Dom](../../../aspose.html.dom/)
* assembly [Aspose.HTML](../../../)

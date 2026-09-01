---
title: "Document.GetElementsByTagNameNS"
second_title: "Aspose.HTML for Java API 参考"
description: "Document 方法。返回属于给定包的、具有指定标签名的元素列表。搜索整个文档，包括根节点。"
type: docs

url: /zh/java/com.aspose.html.dom/document/getelementsbytagnamens/
---
## Document.GetElementsByTagNameNS method

返回属于给定包的、具有指定标签名的元素列表。搜索范围包括整个文档，包括根节点。

```java
public HTMLCollection GetElementsByTagNameNS(String packageURI, String localName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| packageURI | String | 要查找的元素的包 URI。 |
| localName | String | 可以是要查找的元素的本地名称，或特殊值 *，它匹配所有元素。 |

### 返回值

一个实时的[`NodeList`](../../../com.aspose.html.collections/nodelist/)（但请参阅下面的说明），按它们在树中出现的顺序列出找到的元素。

## 备注

请参阅官方[spec](https://dom.spec.whatwg.org/#dom-document-getelementsbytagnamens)。

实践网页开发内容可在[w3schools](https://www.w3schools.com/xml/met_document_getelementsbytagnamens.asp)中找到。

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) 下载完整的示例和数据文件。

## 示例

```java
var elements = document.GetElementsByTagNameNS(@package, name);
```

```java
# HTML content. File extension - xhtml
<!DOCTYPE html>
<html lang="en"
	xmlns="http://www.w3.org/1999/xhtml"
	xmlns:xml="http://www.w3.org/XML/1998/package">
...
<xml:uniquetag>
  xml package uniquetag content goes here...
</xml:uniquetag>
...
</html>

# C# code
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
    HTMLCollection htmlCollection = document.GetElementsByTagNameNS("http://www.w3.org/XML/1998/package","uniquetag");
    Console.WriteLine($"Found: {htmlCollection.Length}" );
    foreach (Element element in htmlCollection)
    {
      Console.WriteLine(element.InnerHTML);
    }  
    // 用户代码放在此处
}





# Console output

Found: 1

xml package uniquetag content goes here...




```

*inputHtmlPath - user input xhtml file path

```java
# HTML content. File extension - xhtml
<!DOCTYPE html>
<html lang="en"
   xmlns="http://www.w3.org/1999/xhtml"
   xmlns:custom="http://www.company.com"
   xmlns:xml="http://www.w3.org/XML/1998/package">
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
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLCollection htmlCollection = 
          document.GetElementsByTagNameNS("http://www.w3.org/XML/1998/package", "ARTIST");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}
         
	// 用户代码放在此处
}
```

# Console output

找到：3

Bob Dylan

Bonnie Tyler

Dolly Parton

*inputHtmlPath - user input xhtml file path

### 另请参见

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

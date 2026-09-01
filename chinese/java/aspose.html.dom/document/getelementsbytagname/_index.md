---
title: "Document.GetElementsByTagName"
second_title: "Aspose.HTML for Java API 参考"
description: "Document 方法。Document 接口的 getElementsByTagName 方法返回具有给定标签名的元素的 HTMLCollection。"
type: docs

url: /zh/java/com.aspose.html.dom/document/getelementsbytagname/
---
## Document.GetElementsByTagName method

[`Document`](../) 接口的 getElementsByTagName 方法返回具有给定标签名的元素的 [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/)。

会搜索完整的文档，包括根节点。返回的 [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) 是实时的，这意味着它会自动更新自身，以保持与 DOM 树同步，而无需再次调用 document.getElementsByTagName()。

```java
public HTMLCollection GetElementsByTagName(String tagname)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 标签名 | String | 一个表示元素名称的字符串。特殊字符串 "*" 代表所有元素。 |

### 返回值

一个实时的 [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) ，按它们在树中出现的顺序列出找到的元素。

## 备注

请参阅官方 [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbytagname)。

实践网页开发内容可在 [w3schools](https://www.w3schools.com/jsref/met_document_getelementsbytagname.asp) 中找到。

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) 下载完整的示例和数据文件。

## 示例

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

    // 用户代码放在此处
}
```

# Console output

找到：6

首个使用 pStyle 类的段落

第二个使用 pStyle 类的段落

第三个使用 pStyle 类的段落

段落使用类名 =ddd kkk= 样式

段落使用类名 =ddd fff= 样式

段落使用类名 =kkk fff= 样式

*inputHtmlPath - user input html file path

### 另请参见

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

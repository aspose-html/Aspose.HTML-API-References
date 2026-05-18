---
title: "Document.GetElementsByClassName"
second_title: "Aspose.HTML for Java API 参考"
description: "Document 方法。Document 接口的 getElementsByClassName 方法返回一个类数组对象，包含所有具有给定所有类名的子元素。"
type: docs

url: /zh/java/com.aspose.html.dom/document/getelementsbyclassname/
---
## Document.GetElementsByClassName method

该 [`Document`](../) 接口的 getElementsByClassName 方法返回一个类数组对象，包含所有具有给定类名的子元素。

当在 document 对象上调用时，会搜索完整文档，包括根节点。您也可以在任何元素上调用 getElementsByClassName()；它将仅返回具有给定类名的、指定根元素的后代元素。

```java
public HTMLCollection GetElementsByClassName(String classNames)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| classNames | String | String String 包含一组无序唯一的以空格分隔的标记，表示类（类名） |

### 返回值

一个实时的[`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/)，包含找到的元素。

## 备注

请参阅官方[spec](https://dom.spec.whatwg.org/#dom-document-getelementsbyclassname)。

实践网页开发内容可在[w3schools](https://www.w3schools.com/jsref/met_element_getelementsbyclassname.asp)中找到。

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) 下载完整的示例和数据文件。

## 示例

```java
var elements = document.GetElementsByClassName("red test");
```

```java
// HTML 内容
<div class="custom-class">Customized by css class container</div>

// C# 代码
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
         
	// 用户代码放在此处
}
```

// 控制台输出

找到：1

由 css 类容器自定义

*inputHtmlPath - user input html file path

```java
// CSS 样式
.ddd{
	padding: 10pt;
}

.kkk{
	background-color: chartreuse;
}

// HTML 内容
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
         
	// 用户代码放在此处
}
```

# Console output

找到：2

段落使用类名 =ddd kkk= 样式

元素类型：Aspose.Html.HTMLParagraphElement

段落使用类名 =ddd fff= 样式

元素类型：Aspose.Html.HTMLParagraphElement

*inputHtmlPath - user input html file path

```java
// CSS 样式
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
         
	// 用户代码放在此处
}
```

# Console output

找到：4

第一个使用 pStyle 类的段落

元素类型：Aspose.Html.HTMLParagraphElement

第二个使用 pStyle 类的段落

元素类型：Aspose.Html.HTMLParagraphElement

第三个使用 pStyle 类的段落

元素类型：Aspose.Html.HTMLParagraphElement

Span 由 pStyle 样式化

元素类型：Aspose.Html.HTMLElement

*inputHtmlPath - user input html file path

### 另请参阅

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---
title: "Document.GetElementsByClassName"
second_title: "Aspose.HTML for Java API 参考"
description: "Document 方法。Document 接口的 getElementsByClassName 方法返回一个类似数组的对象，包含所有具有给定类名的子元素。"
type: docs

url: /zh/java/com.aspose.html.dom/document/getelementsbyclassname/
---
## Document.GetElementsByClassName method

该 `getElementsByClassName` 方法的 [`Document`](../) 接口返回一个类似数组的对象，包含所有具有给定类名的子元素。

当在 document 对象上调用时，会搜索整个文档，包括根节点。您也可以在任意元素上调用 getElementsByClassName()；它只会返回具有给定类名的、指定根元素的后代元素。

```java
public HTMLCollection GetElementsByClassName(String classNames)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| classNames | String | String String 包含一组无序唯一的以空格分隔的标记，表示类（类名） |

### 返回值

实时的 [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) 用于已找到的元素。

## 备注

请参阅官方 [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbyclassname)。

实践 Web 开发内容可在 [w3schools](https://www.w3schools.com/jsref/met_element_getelementsbyclassname.asp) 中找到。

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

已找到：1

通过 css 类 container 定制

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

已找到：2

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

已找到：4

首个使用 pStyle 类的段落

元素类型：Aspose.Html.HTMLParagraphElement

第二个使用 pStyle 类的段落

元素类型：Aspose.Html.HTMLParagraphElement

第三个使用 pStyle 类的段落

元素类型：Aspose.Html.HTMLParagraphElement

Span 已通过 pStyle 样式化

元素类型：Aspose.Html.HTMLElement

*inputHtmlPath - user input html file path

### 另请参见

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

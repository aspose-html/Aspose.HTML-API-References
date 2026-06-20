---
title: "Document.GetElementById"
second_title: "Aspose.HTML for Java API 参考"
description: "Document 方法。Document 方法 getElementById 返回一个 Element 对象，表示其 id 属性与指定 String 匹配的元素。由于元素 ID（如果指定）必须唯一，它们是快速访问特定元素的有用方式。"
type: docs

url: /zh/java/com.aspose.html.dom/document/getelementbyid/
---
## Document.GetElementById method

Document 方法 getElementById() 返回一个 [`Element`](../../element/) 对象，表示其 id 属性与指定 String 匹配的元素。由于元素 ID（如果指定）必须唯一，它们是快速访问特定元素的有用方式。

如果需要访问没有 ID 的元素，可以使用 querySelector() 通过任意选择器查找该元素。

```java
public Element GetElementById(String elementId)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| elementId | String | 要定位的元素的 ID。ID 是区分大小写的 String，在文档中唯一；同一 ID 只能对应一个元素。 |

### 返回值

一个描述匹配指定 ID 的 DOM 元素对象的 [`Element`](../../element/) 对象，如果在文档中未找到匹配的元素，则为 null。

## 备注

请参阅官方 [spec](https://dom.spec.whatwg.org/#dom-nonelementparentnode-getelementbyid)。

实践网页开发内容可在 [w3schools](https://www.w3schools.com/jsref/met_document_getelementbyid.asp) 找到。

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) 下载完整的示例和数据文件。

## 示例

```java
// HTML 内容
<div id="uniqueIdentifier">Container with ID - identifier</div>

// C# 代码
import System;
import Aspose.Html;
import com.aspose.html.dom;
...
	using (var document = new HTMLDocument(inputHtmlPath))
		{
			Element element = document.GetElementById("uniqueIdentifier");
			HTMLDivElement divElement = (HTMLDivElement) element;
			Console.WriteLine(divElement.InnerHTML);

			// 用户代码放在此处
   }
```

// 控制台输出

带有 ID 的容器 - 标识符

*inputHtmlPath - user input html file path

### 另请参见

* class [Element](../../element/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

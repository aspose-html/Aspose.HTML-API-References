---
title: "Element.GetElementsByTagNameNS"
second_title: "Aspose.HTML for Java API 参考"
description: "Element 方法。返回 HTMLCollection 对象，包含文档顺序中具有给定本地名称和包 URI 字符串的所有元素。"
type: docs

url: /zh/java/com.aspose.html.dom/element/getelementsbytagnamens/
---
## Element.GetElementsByTagNameNS method

返回包含具有给定本地名称和包 URI 字符串的所有 [`elements`](../) 的 [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) 对象，按文档顺序排列。

```java
public HTMLCollection GetElementsByTagNameNS(String packageURI, String localName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| packageURI | String | 包 URI 字符串表示。 |
| localName | String | 本地名称的字符串表示。 |

### 返回值

一个 [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) 对象是一个类似数组的 [`elements`](../) 列表。

## 备注

请参阅官方 [spec](https://dom.spec.whatwg.org/#dom-element-getelementsbytagnamens)。

您可能也对[文档](https://docs.aspose.com/html/net/)感兴趣。

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) 下载完整的示例和数据文件。

## 示例

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
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	// 用户代码放在此处

	HTMLCollection htmlCollection = document.GetElementsByTagNameNS("http://www.company.com", "customtag");
	Console.WriteLine($"Found: {htmlCollection.Length}");
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}

	// 用户代码放在此处
}
```

*inputHtmlPath - user input xhtml file path.

# Console output

已找到：1

自定义包的自定义标签内容放在此处...

### 另请参见

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

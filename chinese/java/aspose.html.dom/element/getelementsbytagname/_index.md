---
title: "Element.GetElementsByTagName"
second_title: "Aspose.HTML for Java API 参考"
description: "Element 方法。返回包含所有具有给定标签名的元素的 HTMLCollection 对象，按文档顺序排列"
type: docs

url: /zh/java/com.aspose.html.dom/element/getelementsbytagname/
---
## Element.GetElementsByTagName method

返回 [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) 对象，包含所有具有给定标签名的 [`elements`](../)，按文档顺序。

```java
public HTMLCollection GetElementsByTagName(String name)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | String | 标签名。标签名的字符串表示。 |

### 返回值

一个 [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) 对象是一个类似数组的 [`elements`](../) 列表。

## 备注

请参阅官方[规范](https://dom.spec.whatwg.org/#dom-element-getelementsbytagname)。

您可能也对[文档](https://docs.aspose.com/html/net/)感兴趣。

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) 下载完整的示例和数据文件。

## 示例

```java
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
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	// 用户代码放在此处

	HTMLCollection htmlCollection = document.GetElementsByTagName("p");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}
         
	// 用户代码放在此处
}
```

*inputHtmlPath - user input html file.

# Console output

找到：3

段落使用 pStyle 类样式的内容...

第二段内容...

第三段内容...

### 另请参见

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

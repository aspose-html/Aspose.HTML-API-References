---
title: "Element.GetElementsByClassName"
second_title: "Aspose.HTML for Java API 参考"
description: "Element 方法。返回包含在 element 中具有参数中指定的所有类的所有元素的 HTMLCollection 对象。"
type: docs

url: /zh/java/com.aspose.html.dom/element/getelementsbyclassname/
---
## Element.GetElementsByClassName method

返回包含在 [`element`](../) 中具有参数中指定的所有类的所有元素的 [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) 对象。

```java
public HTMLCollection GetElementsByClassName(String classNames)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| classNames | String | String String 包含一组无序唯一的以空格分隔的标记，表示类（类名） |

### 返回值

一个 [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) 对象是一个类似数组的 [`elements`](../) 列表。

## 备注

请参阅官方[规范](https://dom.spec.whatwg.org/#dom-element-getelementsbyclassname)。

您可能也对[文档](https://docs.aspose.com/html/net/)感兴趣。

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) 下载完整的示例和数据文件。

## 示例

```java
# HTML source content
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

	Element container = document.GetElementById("divElementContainerId");
	HTMLCollection htmlCollection = container.GetElementsByClassName("pStyle");

	Console.WriteLine($"Found: {htmlCollection.Length}");
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}

	// 用户代码放在此处
}
```

*inputHtmlPath - user input html file path.

# Console output

已找到：2

段落使用 pStyle 类样式的内容...

div 元素使用 pStyle 类进行样式化...

### 另请参见

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

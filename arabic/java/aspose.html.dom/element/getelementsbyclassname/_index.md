---
title: "Element.GetElementsByClassName"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة Element. تُرجِع كائن HTMLCollection يحتوي على جميع العناصر داخل العنصر التي لديها جميع الفئات المحددة في الوسيط."
type: docs

url: /ar/java/com.aspose.html.dom/element/getelementsbyclassname/
---
## Element.GetElementsByClassName method

تُرجِع كائن [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) يحتوي على جميع العناصر داخل [`element`](../) التي لديها جميع الفئات المحددة في الوسيط.

```java
public HTMLCollection GetElementsByClassName(String classNames)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| classNames | String | سلسلة String String التي تحتوي على مجموعة غير مرتبة من الرموز الفريدة المفصولة بمسافات تمثل الفئات (أسماء الفئات) |

### قيمة الإرجاع

كائن [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) هو قائمة شبيهة بالمصفوفة من [`elements`](../).

## ملاحظات

ارجع إلى المواصفة الرسمية [spec](https://dom.spec.whatwg.org/#dom-element-getelementsbyclassname).

قد تكون مهتمًا أيضًا بـ [documentation](https://docs.aspose.com/html/net/).

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## الأمثلة

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
	// يذهب كود المستخدم هنا

	Element container = document.GetElementById("divElementContainerId");
	HTMLCollection htmlCollection = container.GetElementsByClassName("pStyle");

	Console.WriteLine($"Found: {htmlCollection.Length}");
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}

	// يذهب كود المستخدم هنا
}
```

*inputHtmlPath - user input html file path.

# Console output

تم العثور على: 2

الفقرة ذات الفئة pStyle المحتوى...

العنصر div المصمم بفئة pStyle...

### انظر أيضًا

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

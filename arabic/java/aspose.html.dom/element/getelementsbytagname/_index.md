---
title: "Element.GetElementsByTagName"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة Element. تُعيد كائن HTMLCollection يحتوي على جميع العناصر ذات الاسم الوسمي المحدد بترتيب المستند"
type: docs

url: /ar/java/com.aspose.html.dom/element/getelementsbytagname/
---
## Element.GetElementsByTagName method

تُعيد كائن [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) يحتوي على جميع [`elements`](../) ذات الاسم الوسمي المحدد، بترتيب المستند.

```java
public HTMLCollection GetElementsByTagName(String name)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | String | اسم الوسم. تمثيل السلسلة لاسم الوسم. |

### قيمة الإرجاع

كائن [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) هو قائمة شبيهة بالمصفوفة من [`elements`](../).

## ملاحظات

ارجع إلى المواصفة الرسمية [spec](https://dom.spec.whatwg.org/#dom-element-getelementsbytagname).

قد تكون مهتمًا أيضًا بـ [documentation](https://docs.aspose.com/html/net/).

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## الأمثلة

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
	// يذهب كود المستخدم هنا

	HTMLCollection htmlCollection = document.GetElementsByTagName("p");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}
         
	// يذهب كود المستخدم هنا
}
```

*inputHtmlPath - user input html file.

# Console output

تم العثور على: 3

الفقرة ذات الفئة pStyle المحتوى...

محتوى الفقرة الثانية...

محتوى الفقرة الثالثة...

### انظر أيضًا

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

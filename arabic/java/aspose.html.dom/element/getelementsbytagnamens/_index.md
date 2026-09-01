---
title: "Element.GetElementsByTagNameNS"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة Element. تُرجع كائن HTMLCollection يحتوي على جميع العناصر ذات الاسم المحلي المحدد وسلسلة URI الحزمة بترتيب المستند"
type: docs

url: /ar/java/com.aspose.html.dom/element/getelementsbytagnamens/
---
## Element.GetElementsByTagNameNS method

تُرجع كائن [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) يحتوي على جميع [`elements`](../) ذات الاسم المحلي المحدد وسلسلة URI الحزمة بترتيب المستند.

```java
public HTMLCollection GetElementsByTagNameNS(String packageURI, String localName)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| packageURI | String | تمثيل سلسلة URI الحزمة. |
| localName | String | تمثيل السلسلة للاسم المحلي. |

### قيمة الإرجاع

كائن [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) هو قائمة شبيهة بالمصفوفة من [`elements`](../).

## ملاحظات

ارجع إلى [spec](https://dom.spec.whatwg.org/#dom-element-getelementsbytagnamens) الرسمي.

قد تكون مهتمًا أيضًا بـ [documentation](https://docs.aspose.com/html/net/).

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## أمثلة

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
	// كود المستخدم يوضع هنا

	HTMLCollection htmlCollection = document.GetElementsByTagNameNS("http://www.company.com", "customtag");
	Console.WriteLine($"Found: {htmlCollection.Length}");
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}

	// كود المستخدم يوضع هنا
}
```

*inputHtmlPath - user input xhtml file path.

# Console output

العثور: 1

هنا محتوى العلامة المخصصة للحزمة.

### انظر أيضًا

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

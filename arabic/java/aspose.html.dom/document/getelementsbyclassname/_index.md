---
title: "Document.GetElementsByClassName"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة Document. تُرجع طريقة getElementsByClassName في واجهة Document كائنًا شبيهًا بالمصفوفة يحتوي على جميع العناصر الفرعية التي لديها جميع أسماء الفئات المحددة"
type: docs

url: /ar/java/com.aspose.html.dom/document/getelementsbyclassname/
---
## Document.GetElementsByClassName method

طريقة getElementsByClassName في واجهة [`Document`](../) تُرجع كائنًا شبيهًا بالمصفوفة يحتوي على جميع العناصر الفرعية التي لديها جميع أسماء الفئات المحددة.

عند استدعائه على كائن المستند، يتم البحث في المستند بالكامل، بما في ذلك عقدة الجذر. يمكنك أيضًا استدعاء getElementsByClassName() على أي عنصر؛ سيُرجع فقط العناصر التي هي من نسل العنصر الجذري المحدد والتي تحمل أسماء الفئات المعطاة.

```java
public HTMLCollection GetElementsByClassName(String classNames)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| classNames | String | سلسلة String String التي تحتوي على مجموعة غير مرتبة من الرموز الفريدة المفصولة بمسافات تمثل الفئات (أسماء الفئات) |

### قيمة الإرجاع

مجموعة حية [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) من العناصر التي تم العثور عليها.

## ملاحظات

ارجع إلى [المواصفة](https://dom.spec.whatwg.org/#dom-document-getelementsbyclassname) الرسمية.

يمكن العثور على محتوى ممارسة تطوير الويب في [w3schools](https://www.w3schools.com/jsref/met_element_getelementsbyclassname.asp).

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## الأمثلة

```java
var elements = document.GetElementsByClassName("red test");
```

```java
// محتوى HTML
<div class="custom-class">Customized by css class container</div>

// كود C#
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
         
	// يذهب كود المستخدم هنا
}
```

// إخراج وحدة التحكم

تم العثور على: 1

مُخصص بواسطة حاوية فئة css

*inputHtmlPath - user input html file path

```java
// تنسيق CSS
.ddd{
	padding: 10pt;
}

.kkk{
	background-color: chartreuse;
}

// محتوى HTML
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
         
	// يذهب كود المستخدم هنا
}
```

# Console output

تم العثور على: 2

الفقرة تم تنسيقها بواسطة اسم الفئة =ddd kkk=

نوع العنصر: Aspose.Html.HTMLParagraphElement

الفقرة تم تنسيقها بواسطة اسم الفئة =ddd fff=

نوع العنصر: Aspose.Html.HTMLParagraphElement

*inputHtmlPath - user input html file path

```java
// تنسيق CSS
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
         
	// يذهب كود المستخدم هنا
}
```

# Console output

تم العثور على: 4

الأول تم تنسيقه بواسطة الفئة pStyle للفقرة

نوع العنصر: Aspose.Html.HTMLParagraphElement

الثاني تم تنسيقه بواسطة الفئة pStyle للفقرة

نوع العنصر: Aspose.Html.HTMLParagraphElement

الثالث تم تنسيقه بواسطة الفئة pStyle للفقرة

نوع العنصر: Aspose.Html.HTMLParagraphElement

عنصر Span مُنسق بواسطة pStyle

نوع العنصر: Aspose.Html.HTMLElement

*inputHtmlPath - user input html file path

### انظر أيضًا

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

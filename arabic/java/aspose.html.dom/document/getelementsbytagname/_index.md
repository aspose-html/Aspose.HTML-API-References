---
title: "Document.GetElementsByTagName"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة Document. طريقة getElementsByTagName في واجهة Document تُرجع مجموعة HTMLCollection من العناصر التي تحمل الاسم الوسمي المحدد."
type: docs

url: /ar/java/com.aspose.html.dom/document/getelementsbytagname/
---
## Document.GetElementsByTagName method

طريقة getElementsByTagName في واجهة [`Document`](../) تُرجع [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) من العناصر التي تحمل الاسم الوسمي المحدد.

يتم البحث في كامل المستند، بما في ذلك العقدة الجذرية. الـ [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) المُرجعة حية، أي أنها تُحدّث نفسها تلقائيًا لتظل متزامنة مع شجرة DOM دون الحاجة إلى استدعاء document.getElementsByTagName() مرة أخرى.

```java
public HTMLCollection GetElementsByTagName(String tagname)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| اسم الوسم | String | سلسلة `String` تمثل اسم العناصر. السلسلة الخاصة "*" تمثل جميع العناصر. |

### قيمة الإرجاع

مجموعة حية [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) من العناصر التي تم العثور عليها بترتيب ظهورها في الشجرة.

## ملاحظات

ارجع إلى [المواصفة](https://dom.spec.whatwg.org/#dom-document-getelementsbytagname) الرسمية.

يمكن العثور على محتوى تطوير الويب العملي في [w3schools](https://www.w3schools.com/jsref/met_document_getelementsbytagname.asp).

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## أمثلة

```java
var elements = document.GetElementsByTagName(name);
```

```java
#HTML content
<div>
	<p class="pStyle">First styled by pStyle class paragraph</p>
	<p class="pStyle">Second styled by pStyle class paragraph</p>
	<p class="pStyle">Third styled by pStyle class paragraph</p>
	<span class="pStyle">Span styled by pStyle</span>
</div>
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

import (var document = new HTMLDocument(inputHtmlPath))
{
    HTMLCollection htmlCollection = document.GetElementsByTagName("p");
    Console.WriteLine($"Found: {htmlCollection.Length}" );
    foreach (Element element in htmlCollection)
    {
      Console.WriteLine(element.InnerHTML);
    }

    // كود المستخدم يوضع هنا
}
```

# Console output

تم العثور على: 6

الأول مُنسق بواسطة فئة pStyle

الثاني مُنسق بواسطة فئة pStyle

الثالث مُنسق بواسطة فئة pStyle

فقرة مُنسقة بواسطة اسم الفئة =ddd kkk=

فقرة مُنسقة بواسطة اسم الفئة =ddd fff=

فقرة مُنسقة بواسطة اسم الفئة =kkk fff=

*inputHtmlPath - user input html file path

### انظر أيضًا

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

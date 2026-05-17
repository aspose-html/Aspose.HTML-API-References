---
title: "Document.GetElementsByTagName"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة Document. طريقة getElementsByTagName لواجهة Document تُعيد مجموعة HTMLCollection من العناصر التي تحمل الاسم المحدد للوسم."
type: docs

url: /ar/java/com.aspose.html.dom/document/getelementsbytagname/
---
## Document.GetElementsByTagName method

طريقة getElementsByTagName لواجهة [`Document`](../) تُعيد [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) من العناصر التي تحمل الاسم المحدد للوسم.

يتم البحث في المستند الكامل، بما في ذلك العقدة الجذرية. الـ [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) المُرجعة حية، أي أنها تُحدّث نفسها تلقائيًا لتظل متزامنة مع شجرة DOM دون الحاجة إلى استدعاء document.getElementsByTagName() مرة أخرى.

```java
public HTMLCollection GetElementsByTagName(String tagname)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| tagname | String | سلسلة تمثل اسم العناصر. السلسلة الخاصة "*" تمثل جميع العناصر. |

### قيمة الإرجاع

مجموعة حية [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) من العناصر التي تم العثور عليها بترتيب ظهورها في الشجرة.

## ملاحظات

راجع المواصفة الرسمية [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbytagname).

يمكن العثور على محتوى تطوير الويب العملي في [w3schools](https://www.w3schools.com/jsref/met_document_getelementsbytagname.asp).

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## الأمثلة

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

    // يذهب كود المستخدم هنا
}
```

# Console output

تم العثور على: 6

الأول تم تنسيقه بواسطة الفئة pStyle للفقرة

الثاني تم تنسيقه بواسطة الفئة pStyle للفقرة

الثالث تم تنسيقه بواسطة الفئة pStyle للفقرة

الفقرة تم تنسيقها بواسطة اسم الفئة =ddd kkk=

الفقرة تم تنسيقها بواسطة اسم الفئة =ddd fff=

الفقرة تم تنسيقها بواسطة اسم الفئة =kkk fff=

*inputHtmlPath - user input html file path

### انظر أيضًا

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

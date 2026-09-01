---
title: "Document.GetElementById"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة المستند. طريقة المستند getElementById تُعيد كائن Element يمثل العنصر الذي تتطابق خاصية id الخاصة به مع السلسلة المحددة. بما أن معرفات العناصر يجب أن تكون فريدة إذا تم تحديدها، فهي طريقة مفيدة للوصول إلى عنصر معين بسرعة"
type: docs

url: /ar/java/com.aspose.html.dom/document/getelementbyid/
---
## Document.GetElementById method

طريقة المستند getElementById() تُعيد كائن [`Element`](../../element/) يمثل العنصر الذي تتطابق خاصية id الخاصة به مع السلسلة المحددة. بما أن معرفات العناصر يجب أن تكون فريدة إذا تم تحديدها، فهي طريقة مفيدة للوصول إلى عنصر معين بسرعة.

إذا كنت بحاجة للوصول إلى عنصر لا يملك معرفًا، يمكنك استخدام querySelector() للعثور على العنصر باستخدام أي محدد.

```java
public Element GetElementById(String elementId)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| elementId | String | معرف العنصر المراد تحديده. المعرف هو سلسلة حساسة لحالة الأحرف وتكون فريدة داخل المستند؛ لا يمكن أن يكون هناك أكثر من عنصر يحمل نفس المعرف. |

### قيمة الإرجاع

كائن [`Element`](../../element/) يصف كائن عنصر DOM المتطابق مع المعرف المحدد، أو null إذا لم يتم العثور على عنصر متطابق في المستند.

## ملاحظات

ارجع إلى [المواصفة](https://dom.spec.whatwg.org/#dom-nonelementparentnode-getelementbyid) الرسمية.

يمكن العثور على محتوى تطوير الويب العملي في [w3schools](https://www.w3schools.com/jsref/met_document_getelementbyid.asp).

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## أمثلة

```java
// محتوى HTML
<div id="uniqueIdentifier">Container with ID - identifier</div>

// كود C#
import System;
import Aspose.Html;
import com.aspose.html.dom;
...
	using (var document = new HTMLDocument(inputHtmlPath))
		{
			Element element = document.GetElementById("uniqueIdentifier");
			HTMLDivElement divElement = (HTMLDivElement) element;
			Console.WriteLine(divElement.InnerHTML);

			// كود المستخدم يوضع هنا
   }
```

// مخرجات وحدة التحكم

حاوية مع معرف - identifier

*inputHtmlPath - user input html file path

### انظر أيضًا

* class [Element](../../element/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

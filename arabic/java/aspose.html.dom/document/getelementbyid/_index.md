---
title: "Document.GetElementById"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة المستند. طريقة Document getElementById تُرجع كائن Element يمثل العنصر الذي تتطابق خاصية id الخاصة به مع السلسلة المحددة. بما أن معرفات العناصر يجب أن تكون فريدة إذا تم تحديدها، فهي طريقة مفيدة للوصول إلى عنصر محدد بسرعة"
type: docs

url: /ar/java/com.aspose.html.dom/document/getelementbyid/
---
## Document.GetElementById method

تُرجع طريقة Document getElementById() كائن [`Element`](../../element/) يمثل العنصر الذي تتطابق خاصية id الخاصة به مع السلسلة المحددة. بما أن معرفات العناصر يجب أن تكون فريدة إذا تم تحديدها، فهي طريقة مفيدة للوصول إلى عنصر محدد بسرعة.

إذا كنت بحاجة للوصول إلى عنصر لا يمتلك معرف ID، يمكنك استخدام querySelector() للعثور على العنصر باستخدام أي محدد.

```java
public Element GetElementById(String elementId)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| elementId | String | معرف العنصر المراد تحديده. المعرف هو سلسلة حساسة لحالة الأحرف فريدة داخل المستند؛ لا يمكن أن يكون هناك أكثر من عنصر واحد يحمل نفس المعرف. |

### قيمة الإرجاع

كائن [`Element`](../../element/) يصف كائن عنصر DOM الذي يطابق المعرف المحدد، أو null إذا لم يتم العثور على عنصر مطابق في المستند.

## ملاحظات

ارجع إلى [المواصفة](https://dom.spec.whatwg.org/#dom-nonelementparentnode-getelementbyid) الرسمية.

يمكن العثور على محتوى تطوير الويب العملي في [w3schools](https://www.w3schools.com/jsref/met_document_getelementbyid.asp).

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## الأمثلة

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

			// يذهب كود المستخدم هنا
   }
```

// إخراج وحدة التحكم

حاوية بمعرف ID - معرف

*inputHtmlPath - user input html file path

### انظر أيضًا

* class [Element](../../element/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

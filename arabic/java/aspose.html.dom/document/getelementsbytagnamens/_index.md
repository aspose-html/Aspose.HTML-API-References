---
title: "Document.GetElementsByTagNameNS"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة Document. تُرجع قائمة بالعناصر التي لها اسم الوسم المحدد وتخص الحزمة المحددة. يتم البحث في المستند بالكامل بما في ذلك عقدة الجذر"
type: docs

url: /ar/java/com.aspose.html.dom/document/getelementsbytagnamens/
---
## Document.GetElementsByTagNameNS method

يعيد قائمة بالعناصر التي تحمل الاسم الوسمي المحدد وتخص الحزمة المحددة. يتم البحث في المستند بالكامل، بما في ذلك عقدة الجذر.

```java
public HTMLCollection GetElementsByTagNameNS(String packageURI, String localName)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| packageURI | String | عنوان URI الخاص بالحزمة للعناصر المراد البحث عنها. |
| localName | String | إما اسم العنصر المحلي للبحث عنه أو القيمة الخاصة *, التي تطابق جميع العناصر. |

### قيمة الإرجاع

قائمة حية [`NodeList`](../../../com.aspose.html.collections/nodelist/) (لكن راجع الملاحظة أدناه) للعناصر التي تم العثور عليها بالترتيب الذي تظهر به في الشجرة.

## ملاحظات

ارجع إلى [المواصفة](https://dom.spec.whatwg.org/#dom-document-getelementsbytagnamens) الرسمية.

يمكن العثور على محتوى ممارسات تطوير الويب في [w3schools](https://www.w3schools.com/xml/met_document_getelementsbytagnamens.asp).

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## الأمثلة

```java
var elements = document.GetElementsByTagNameNS(@package, name);
```

```java
# HTML content. File extension - xhtml
<!DOCTYPE html>
<html lang="en"
	xmlns="http://www.w3.org/1999/xhtml"
	xmlns:xml="http://www.w3.org/XML/1998/package">
...
<xml:uniquetag>
  xml package uniquetag content goes here...
</xml:uniquetag>
...
</html>

# C# code
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
    HTMLCollection htmlCollection = document.GetElementsByTagNameNS("http://www.w3.org/XML/1998/package","uniquetag");
    Console.WriteLine($"Found: {htmlCollection.Length}" );
    foreach (Element element in htmlCollection)
    {
      Console.WriteLine(element.InnerHTML);
    }  
    // يذهب كود المستخدم هنا
}





# Console output

Found: 1

xml package uniquetag content goes here...




```

*inputHtmlPath - user input xhtml file path

```java
# HTML content. File extension - xhtml
<!DOCTYPE html>
<html lang="en"
   xmlns="http://www.w3.org/1999/xhtml"
   xmlns:custom="http://www.company.com"
   xmlns:xml="http://www.w3.org/XML/1998/package">
...
<xml:CATALOG>
	<xml:CD>
    <xml:TITLE>Empire Burlesque</xml:TITLE>
    <xml:ARTIST>Bob Dylan</xml:ARTIST>
    <xml:COUNTRY>USA</xml:COUNTRY>
    <xml:COMPANY>Columbia</xml:COMPANY>
    <xml:PRICE>10.90</xml:PRICE>
    <xml:YEAR>1985</xml:YEAR>
  </xml:CD>
...

# C# code
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLCollection htmlCollection = 
          document.GetElementsByTagNameNS("http://www.w3.org/XML/1998/package", "ARTIST");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}
         
	// يذهب كود المستخدم هنا
}
```

# Console output

تم العثور على: 3

بوب ديلان

بوني تايلر

دولي بارتون

*inputHtmlPath - user input xhtml file path

### انظر أيضًا

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---
title: "Document.GetElementsByTagNameNS"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "Document मेथड। दिए गए टैग नाम वाले तत्वों की सूची लौटाता है जो दिए गए पैकेज से संबंधित हैं। पूर्ण दस्तावेज़ को रूट नोड सहित खोजा जाता है।"
type: docs

url: /hi/java/com.aspose.html.dom/document/getelementsbytagnamens/
---
## Document.GetElementsByTagNameNS method

दिए गए पैकेज से संबंधित दिए गए टैग नाम वाले तत्वों की सूची लौटाता है। पूरी दस्तावेज़ की खोज की जाती है, जिसमें रूट नोड भी शामिल है।

```java
public HTMLCollection GetElementsByTagNameNS(String packageURI, String localName)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| packageURI | String | खोजे जाने वाले तत्वों का पैकेज URI। |
| localName | String | या तो खोजे जाने वाले तत्वों का स्थानीय नाम या विशेष मान *, जो सभी तत्वों से मेल खाता है। |

### रिटर्न वैल्यू

एक लाइव [`NodeList`](../../../com.aspose.html.collections/nodelist/) (नीचे नोट देखें) खोजे गए तत्वों का, जो पेड़ में उनके प्रकट होने के क्रम में है।

## Remarks

आधिकारिक [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbytagnamens) देखें।

वेब विकास सामग्री का अभ्यास [w3schools](https://www.w3schools.com/xml/met_document_getelementsbytagnamens.asp) में पाया जा सकता है।

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) से डाउनलोड कर सकते हैं।

## उदाहरण

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
    // उपयोगकर्ता कोड यहाँ जाएँगा
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
         
	// उपयोगकर्ता कोड यहाँ जाएँगा
}
```

# Console output

पाया गया: 3

Bob Dylan

Bonnie Tyler

Dolly Parton

*inputHtmlPath - user input xhtml file path

### संबंधित देखें

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

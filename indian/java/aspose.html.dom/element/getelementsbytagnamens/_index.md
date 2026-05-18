---
title: "Element.GetElementsByTagNameNS"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "Element method. दस्तावेज़ क्रम में दिए गए स्थानीय नाम और पैकेज URI स्ट्रिंग वाले सभी तत्वों को सम्मिलित करने वाला HTMLCollection ऑब्जेक्ट लौटाता है।"
type: docs

url: /hi/java/com.aspose.html.dom/element/getelementsbytagnamens/
---
## Element.GetElementsByTagNameNS method

दिए गए स्थानीय नाम और पैकेज URI स्ट्रिंग वाले सभी [`elements`](../) को सम्मिलित करने वाला [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) ऑब्जेक्ट लौटाता है।

```java
public HTMLCollection GetElementsByTagNameNS(String packageURI, String localName)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| packageURI | String | पैकेज URI स्ट्रिंग प्रतिनिधित्व। |
| localName | String | स्थानीय नाम का स्ट्रिंग प्रतिनिधित्व। |

### रिटर्न वैल्यू

एक [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) ऑब्जेक्ट एक एरे-समतुल्य सूची है जिसमें [`elements`](../) होते हैं।

## टिप्पणियाँ

आधिकारिक [spec](https://dom.spec.whatwg.org/#dom-element-getelementsbytagnamens) देखें।

आपको [documentation](https://docs.aspose.com/html/net/) में भी रुचि हो सकती है।

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) से डाउनलोड कर सकते हैं।

## उदाहरण

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
	// उपयोगकर्ता कोड यहाँ जाएँ

	HTMLCollection htmlCollection = document.GetElementsByTagNameNS("http://www.company.com", "customtag");
	Console.WriteLine($"Found: {htmlCollection.Length}");
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}

	// उपयोगकर्ता कोड यहाँ जाएँ
}
```

*inputHtmlPath - user input xhtml file path.

# Console output

पाया गया: 1

कस्टम पैकेज कस्टम टैग सामग्री यहाँ आती है...

### संबंधित देखें

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

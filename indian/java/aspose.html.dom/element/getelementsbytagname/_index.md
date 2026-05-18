---
title: "Element.GetElementsByTagName"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "Element method. दिए गए टैग नाम वाले सभी तत्वों को दस्तावेज़ क्रम में शामिल करने वाला HTMLCollection ऑब्जेक्ट लौटाता है"
type: docs

url: /hi/java/com.aspose.html.dom/element/getelementsbytagname/
---
## Element.GetElementsByTagName method

दिए गए टैग नाम वाले सभी [`elements`](../) को शामिल करने वाला [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) ऑब्जेक्ट लौटाता है, दस्तावेज़ क्रम में।

```java
public HTMLCollection GetElementsByTagName(String name)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| नाम | String | टैग नाम। टैग नाम का स्ट्रिंग प्रतिनिधित्व। |

### रिटर्न वैल्यू

एक [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) ऑब्जेक्ट एक एरे-समतुल्य सूची है जिसमें [`elements`](../) होते हैं।

## टिप्पणियाँ

आधिकारिक [spec](https://dom.spec.whatwg.org/#dom-element-getelementsbytagname) देखें।

आपको [documentation](https://docs.aspose.com/html/net/) में भी रुचि हो सकती है।

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) से डाउनलोड कर सकते हैं।

## उदाहरण

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
	// उपयोगकर्ता कोड यहाँ जाएँ

	HTMLCollection htmlCollection = document.GetElementsByTagName("p");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}
         
	// उपयोगकर्ता कोड यहाँ जाएँ
}
```

*inputHtmlPath - user input html file.

# Console output

पाया गया: 3

pStyle क्लास द्वारा शैलीबद्ध पैराग्राफ की सामग्री...

दूसरे पैराग्राफ की सामग्री...

तीसरे पैराग्राफ की सामग्री...

### संबंधित देखें

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

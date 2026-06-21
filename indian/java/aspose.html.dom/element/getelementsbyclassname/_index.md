---
title: "Element.GetElementsByClassName"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "Element method. एक HTMLCollection ऑब्जेक्ट लौटाता है जिसमें उन सभी एलिमेंट्स को शामिल किया गया है जो तर्क में निर्दिष्ट सभी क्लासेज़ वाले होते हैं।"
type: docs

url: /hi/java/com.aspose.html.dom/element/getelementsbyclassname/
---
## Element.GetElementsByClassName method

एक [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) ऑब्जेक्ट लौटाता है जिसमें उन सभी एलिमेंट्स को शामिल किया गया है जो [`element`](../) के भीतर हैं और तर्क में निर्दिष्ट सभी क्लासेज़ वाले हैं।

```java
public HTMLCollection GetElementsByClassName(String classNames)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| classNames | String | String String जो वर्गों (क्लास नाम) का प्रतिनिधित्व करने वाले अद्वितीय स्पेस-सेपरेटेड टोकनों का अनऑर्डर्ड सेट रखता है |

### रिटर्न वैल्यू

एक [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) ऑब्जेक्ट एक एरे-समतुल्य सूची है जिसमें [`elements`](../) होते हैं।

## Remarks

आधिकारिक [spec](https://dom.spec.whatwg.org/#dom-element-getelementsbyclassname) देखें।

आपको भी [documentation](https://docs.aspose.com/html/net/) में रुचि हो सकती है।

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
# HTML source content
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
	// उपयोगकर्ता कोड यहाँ जाएँगा

	Element container = document.GetElementById("divElementContainerId");
	HTMLCollection htmlCollection = container.GetElementsByClassName("pStyle");

	Console.WriteLine($"Found: {htmlCollection.Length}");
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}

	// उपयोगकर्ता कोड यहाँ जाएँगा
}
```

*inputHtmlPath - user input html file path.

# Console output

पाया गया: 2

pStyle क्लास से स्टाइल किया गया पैराग्राफ सामग्री...

div तत्व को pStyle वर्ग से स्टाइल किया गया...

### संबंधित देखें

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

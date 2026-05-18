---
title: "Element.GetElementsByClassName"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "Element method. उन सभी एलिमेंट्स को शामिल करने वाला HTMLCollection ऑब्जेक्ट लौटाता है जो तत्व के भीतर हैं और जिनके पास तर्क में निर्दिष्ट सभी क्लासेज़ हैं।"
type: docs

url: /hi/java/com.aspose.html.dom/element/getelementsbyclassname/
---
## Element.GetElementsByClassName method

उन सभी एलिमेंट्स को शामिल करने वाला [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) ऑब्जेक्ट लौटाता है जो [`element`](../) के भीतर हैं और तर्क में निर्दिष्ट सभी क्लासेज़ हैं।

```java
public HTMLCollection GetElementsByClassName(String classNames)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| classNames | String | String String जो वर्गों (क्लास नाम) का प्रतिनिधित्व करने वाले अनियमित क्रम में अद्वितीय स्पेस-सेपरेटेड टोकन का सेट रखता है |

### रिटर्न वैल्यू

एक [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) ऑब्जेक्ट एक एरे-समतुल्य सूची है जिसमें [`elements`](../) होते हैं।

## टिप्पणियाँ

आधिकारिक [spec](https://dom.spec.whatwg.org/#dom-element-getelementsbyclassname) देखें।

आपको [documentation](https://docs.aspose.com/html/net/) में भी रुचि हो सकती है।

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
	// उपयोगकर्ता कोड यहाँ जाएँ

	Element container = document.GetElementById("divElementContainerId");
	HTMLCollection htmlCollection = container.GetElementsByClassName("pStyle");

	Console.WriteLine($"Found: {htmlCollection.Length}");
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}

	// उपयोगकर्ता कोड यहाँ जाएँ
}
```

*inputHtmlPath - user input html file path.

# Console output

पाया गया: 2

pStyle क्लास द्वारा शैलीबद्ध पैराग्राफ की सामग्री...

pStyle वर्ग द्वारा शैलीबद्ध div तत्व...

### संबंधित देखें

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---
title: "Document.GetElementsByTagName"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "Document मेथड। Document इंटरफ़ेस की getElementsByTagName मेथड दिए गए टैग नाम वाले तत्वों की एक HTMLCollection लौटाती है"
type: docs

url: /hi/java/com.aspose.html.dom/document/getelementsbytagname/
---
## Document.GetElementsByTagName method

[`Document`](../) इंटरफ़ेस की getElementsByTagName मेथड दिए गए टैग नाम वाले तत्वों की एक [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) लौटाती है।

पूरा दस्तावेज़, जिसमें रूट नोड शामिल है, खोजा जाता है। लौटाई गई [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) लाइव होती है, अर्थात यह स्वतः अपडेट होती है ताकि DOM ट्री के साथ सिंक में रहे बिना फिर से document.getElementsByTagName() कॉल किए।

```java
public HTMLCollection GetElementsByTagName(String tagname)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| टैगनाम | String | एक String जो तत्वों के नाम का प्रतिनिधित्व करता है। विशेष String "*" सभी तत्वों का प्रतिनिधित्व करता है। |

### रिटर्न वैल्यू

एक लाइव [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) जिसमें पाए गए तत्वों को वृक्ष में उनकी उपस्थिति क्रम में दिखाया गया है।

## टिप्पणियाँ

आधिकारिक [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbytagname) देखें।

वेब विकास सामग्री का अभ्यास [w3schools](https://www.w3schools.com/jsref/met_document_getelementsbytagname.asp) में पाया जा सकता है।

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) से डाउनलोड कर सकते हैं।

## उदाहरण

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

    // उपयोगकर्ता कोड यहाँ जाएँ
}
```

# Console output

पाया गया: 6

पहला pStyle क्लास पैराग्राफ द्वारा स्टाइल किया गया

दूसरा pStyle क्लास पैराग्राफ द्वारा स्टाइल किया गया

तीसरा pStyle क्लास पैराग्राफ द्वारा स्टाइल किया गया

पैराग्राफ को क्लास नाम =ddd kkk= द्वारा स्टाइल किया गया

पैराग्राफ को क्लास नाम =ddd fff= द्वारा स्टाइल किया गया

पैराग्राफ को क्लास नाम =kkk fff= द्वारा स्टाइल किया गया

*inputHtmlPath - user input html file path

### संबंधित देखें

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---
title: "Document.GetElementsByClassName"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "Document मेथड। Document इंटरफ़ेस का getElementsByClassName मेथड सभी चाइल्ड एलिमेंट्स का एक एरे-समतुल्य ऑब्जेक्ट लौटाता है जिनके पास सभी दिए गए क्लास नाम हैं।"
type: docs

url: /hi/java/com.aspose.html.dom/document/getelementsbyclassname/
---
## Document.GetElementsByClassName method

यह [`Document`](../) इंटरफ़ेस का getElementsByClassName मेथड सभी चाइल्ड एलिमेंट्स का एक एरे-समतुल्य ऑब्जेक्ट लौटाता है जिनके पास सभी दिए गए क्लास नाम (नाम) हैं।

जब इसे document ऑब्जेक्ट पर कॉल किया जाता है, तो पूरी दस्तावेज़ खोजी जाती है, जिसमें रूट नोड भी शामिल है। आप किसी भी एलिमेंट पर भी getElementsByClassName() कॉल कर सकते हैं; यह केवल उन एलिमेंट्स को लौटाएगा जो निर्दिष्ट रूट एलिमेंट के वंशज हैं और जिनके पास दिए गए क्लास नाम (नाम) हैं।

```java
public HTMLCollection GetElementsByClassName(String classNames)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| classNames | String | String String जो वर्गों (क्लास नाम) का प्रतिनिधित्व करने वाले अनियमित क्रम में अद्वितीय स्पेस-सेपरेटेड टोकन का सेट रखता है |

### रिटर्न वैल्यू

पाए गए तत्वों का एक लाइव [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/)

## टिप्पणियाँ

आधिकारिक [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbyclassname) देखें।

वेब विकास सामग्री का अभ्यास [w3schools](https://www.w3schools.com/jsref/met_element_getelementsbyclassname.asp) में पाया जा सकता है।

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
var elements = document.GetElementsByClassName("red test");
```

```java
// HTML सामग्री
<div class="custom-class">Customized by css class container</div>

// C# कोड
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLCollection htmlCollection = document.GetElementsByClassName("custom-class");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}
         
	// उपयोगकर्ता कोड यहाँ जाएँ
}
```

// कंसोल आउटपुट

पाया गया: 1

css क्लास कंटेनर द्वारा अनुकूलित

*inputHtmlPath - user input html file path

```java
// CSS स्टाइलिंग
.ddd{
	padding: 10pt;
}

.kkk{
	background-color: chartreuse;
}

// HTML सामग्री
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
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLCollection htmlCollection = document.GetElementsByClassName("ddd");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
		Console.WriteLine($"Element type: {element.GetType()}");
	}
         
	// उपयोगकर्ता कोड यहाँ जाएँ
}
```

# Console output

पाया गया: 2

पैराग्राफ को क्लास नाम =ddd kkk= द्वारा स्टाइल किया गया

एलिमेंट प्रकार: Aspose.Html.HTMLParagraphElement

पैराग्राफ को क्लास नाम =ddd fff= द्वारा स्टाइल किया गया

एलिमेंट प्रकार: Aspose.Html.HTMLParagraphElement

*inputHtmlPath - user input html file path

```java
// CSS स्टाइलिंग
.pStyle{
  font-
}

# HTML content
<div>
	<p class="pStyle">First styled by pStyle class paragraph</p>
	<p class="pStyle">Second styled by pStyle class paragraph</p>
	<p class="pStyle">Third styled by pStyle class paragraph</p>
	<span class="pStyle">Span styled by pStyle</span>
</div>

# C# code
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLCollection htmlCollection = document.GetElementsByClassName("pStyle");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
		Console.WriteLine($"Element type: {element.GetType()}");
	}
         
	// उपयोगकर्ता कोड यहाँ जाएँ
}
```

# Console output

पाया गया: 4

पहला pStyle क्लास पैराग्राफ द्वारा स्टाइल किया गया

एलिमेंट प्रकार: Aspose.Html.HTMLParagraphElement

दूसरा pStyle क्लास पैराग्राफ द्वारा स्टाइल किया गया

एलिमेंट प्रकार: Aspose.Html.HTMLParagraphElement

तीसरा pStyle क्लास पैराग्राफ द्वारा स्टाइल किया गया

एलिमेंट प्रकार: Aspose.Html.HTMLParagraphElement

pStyle द्वारा स्टाइल किया गया स्पैन

एलिमेंट प्रकार: Aspose.Html.HTMLElement

*inputHtmlPath - user input html file path

### संबंधित देखें

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

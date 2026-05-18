---
title: "Document.GetElementById"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "Document मेथड। The Document मेथड getElementById एक Element ऑब्जेक्ट लौटाता है जो उस तत्व का प्रतिनिधित्व करता है जिसकी id प्रॉपर्टी निर्दिष्ट String से मेल खाती है। चूँकि तत्व IDs को विशिष्ट होना आवश्यक है, यदि निर्दिष्ट किया गया हो तो वे एक विशिष्ट तत्व तक जल्दी पहुँचने का उपयोगी तरीका हैं।"
type: docs

url: /hi/java/com.aspose.html.dom/document/getelementbyid/
---
## Document.GetElementById method

Document मेथड getElementById() एक [`Element`](../../element/) ऑब्जेक्ट लौटाता है जो उस तत्व का प्रतिनिधित्व करता है जिसकी id प्रॉपर्टी निर्दिष्ट String से मेल खाती है। चूँकि तत्व IDs को विशिष्ट होना आवश्यक है, यदि निर्दिष्ट किया गया हो तो वे एक विशिष्ट तत्व तक जल्दी पहुँचने का उपयोगी तरीका हैं।

यदि आपको ऐसे तत्व तक पहुँच चाहिए जिसका ID नहीं है, तो आप querySelector() का उपयोग करके किसी भी selector से वह तत्व खोज सकते हैं।

```java
public Element GetElementById(String elementId)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| elementId | String | खोजे जाने वाले तत्व का ID। ID एक case-sensitive String है जो दस्तावेज़ के भीतर अद्वितीय है; केवल एक ही तत्व को दिया गया कोई भी ID मिल सकता है। |

### रिटर्न वैल्यू

एक [`Element`](../../element/) ऑब्जेक्ट जो निर्दिष्ट ID से मेल खाने वाले DOM तत्व ऑब्जेक्ट का वर्णन करता है, या null यदि दस्तावेज़ में कोई मेल खाने वाला तत्व नहीं मिला।

## टिप्पणियाँ

आधिकारिक [spec](https://dom.spec.whatwg.org/#dom-nonelementparentnode-getelementbyid) देखें।

वेब विकास सामग्री का अभ्यास [w3schools](https://www.w3schools.com/jsref/met_document_getelementbyid.asp) में पाया जा सकता है।

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
// HTML सामग्री
<div id="uniqueIdentifier">Container with ID - identifier</div>

// C# कोड
import System;
import Aspose.Html;
import com.aspose.html.dom;
...
	using (var document = new HTMLDocument(inputHtmlPath))
		{
			Element element = document.GetElementById("uniqueIdentifier");
			HTMLDivElement divElement = (HTMLDivElement) element;
			Console.WriteLine(divElement.InnerHTML);

			// उपयोगकर्ता कोड यहाँ जाएँ
   }
```

// कंसोल आउटपुट

ID - पहचानकर्ता वाला कंटेनर

*inputHtmlPath - user input html file path

### संबंधित देखें

* class [Element](../../element/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

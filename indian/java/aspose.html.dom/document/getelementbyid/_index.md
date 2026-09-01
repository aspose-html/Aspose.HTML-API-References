---
title: "Document.GetElementById"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "Document विधि। Document विधि getElementById एक Element ऑब्जेक्ट लौटाती है जो उस तत्व का प्रतिनिधित्व करता है जिसकी id प्रॉपर्टी निर्दिष्ट स्ट्रिंग से मेल खाती है। चूँकि तत्व IDs को विशिष्ट होना आवश्यक है, यदि निर्दिष्ट किया गया हो तो यह किसी विशिष्ट तत्व तक शीघ्र पहुँच प्राप्त करने का उपयोगी तरीका है।"
type: docs

url: /hi/java/com.aspose.html.dom/document/getelementbyid/
---
## Document.GetElementById method

Document विधि getElementById() एक [`Element`](../../element/) ऑब्जेक्ट लौटाती है जो उस तत्व का प्रतिनिधित्व करता है जिसकी id प्रॉपर्टी निर्दिष्ट स्ट्रिंग से मेल खाती है। चूँकि तत्व IDs को विशिष्ट होना आवश्यक है, यदि निर्दिष्ट किया गया हो तो यह किसी विशिष्ट तत्व तक शीघ्र पहुँच प्राप्त करने का उपयोगी तरीका है।

यदि आपको किसी ऐसे तत्व तक पहुँच चाहिए जिसका ID नहीं है, तो आप querySelector() का उपयोग करके किसी भी चयनकर्ता से तत्व खोज सकते हैं।

```java
public Element GetElementById(String elementId)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| elementId | String | खोजे जाने वाले तत्व का ID। ID एक केस-सेंसिटिव स्ट्रिंग है जो दस्तावेज़ के भीतर अद्वितीय होती है; केवल एक ही तत्व को दिया गया कोई भी ID मिल सकता है। |

### रिटर्न वैल्यू

एक [`Element`](../../element/) ऑब्जेक्ट जो निर्दिष्ट ID से मेल खाने वाले DOM तत्व को वर्णित करता है, या null यदि दस्तावेज़ में कोई मेल खाने वाला तत्व नहीं मिला।

## Remarks

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

			// उपयोगकर्ता कोड यहाँ जाएँगा
   }
```

// Console आउटपुट

ID के साथ कंटेनर - पहचानकर्ता

*inputHtmlPath - user input html file path

### संबंधित देखें

* class [Element](../../element/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

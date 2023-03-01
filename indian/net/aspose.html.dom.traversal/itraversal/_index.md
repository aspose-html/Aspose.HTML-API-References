---
title: Interface ITraversal
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Aspose.Html.Dom.Traversal.ITraversal इंटरफेस. Iterators क उपयग नड्स के एक सेट के मध्यम से कदम उठने के लए कय जत है उदहरण के लए नडलस्ट में नड्स क सेट द्वर नयंत्रत दस्तवेज़ सबट्र एक वशेष नड एक क्वेर के परणम य कस अन्य सेट नड्स क पुनरवृत्त कए जने वले नड्स क सेट NodeIterator के कर्यन्वयन द्वर नर्धरत कय जत है DOM लेवल 2 दस्तवेज़ सबट्र के दस्तवेज़ऑर्डर ट्रैवर्सल के लए एक संगल नडइटरेटर कर्यन्वयन नर्दष्ट करत है DocumentTraversal .createNodeIterator. क कल करके इन पुनरवृत्तयं के उदहरण बनए जते हैं
type: docs
weight: 2510
url: /hi/net/aspose.html.dom.traversal/itraversal/
---
## ITraversal interface

Iterators का उपयोग नोड्स के एक सेट के माध्यम से कदम उठाने के लिए किया जाता है, उदाहरण के लिए नोडलिस्ट में नोड्स का सेट, द्वारा नियंत्रित दस्तावेज़ सबट्री एक विशेष नोड, एक क्वेरी के परिणाम, या किसी अन्य सेट नोड्स का। पुनरावृत्त किए जाने वाले नोड्स का सेट NodeIterator के कार्यान्वयन द्वारा निर्धारित किया जाता है। DOM लेवल 2 दस्तावेज़ सबट्री के दस्तावेज़-ऑर्डर ट्रैवर्सल के लिए एक सिंगल नोडइटरेटर कार्यान्वयन निर्दिष्ट करता है। DocumentTraversal .createNodeIterator(). को कॉल करके इन पुनरावृत्तियों के उदाहरण बनाए जाते हैं

यह भी देखें[दस्तावेज़ ऑब्जेक्ट मॉडल (DOM) स्तर 2 ट्रैवर्सल और रेंज विशिष्टता](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @DOM लेवल 2 के बाद से

```csharp
public interface ITraversal : IDisposable
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Filter](../../aspose.html.dom.traversal/itraversal/filter/) { get; } | नोडफ़िल्टर नोड्स को स्क्रीन करने के लिए उपयोग किया जाता है। |
| [Root](../../aspose.html.dom.traversal/itraversal/root/) { get; } | NodeIterator का रूट नोड, जैसा कि निर्दिष्ट किया गया है जब it बनाया गया था। |
| [WhatToShow](../../aspose.html.dom.traversal/itraversal/whattoshow/) { get; } | यह विशेषता निर्धारित करती है कि पुनरावर्तक के माध्यम से कौन से नोड प्रकार प्रस्तुत किए जाते हैं। स्थिरांक के उपलब्ध सेट को NodeFilter इंटरफ़ेस में परिभाषित किया गया है। द्वारा स्वीकार नहीं किए गए नोड्स को छोड़ दिया जाएगा, लेकिन उनके बच्चों को अभी भी माना जा सकता है। ध्यान दें कि इस स्किप को फ़िल्टर पर प्राथमिकता मिलती है, यदि कोई है. |

### यह सभी देखें

* नाम स्थान [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* सभा [Aspose.HTML](../../)



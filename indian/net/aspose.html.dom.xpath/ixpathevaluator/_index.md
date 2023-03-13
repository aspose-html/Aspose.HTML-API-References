---
title: Interface IXPathEvaluator
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Aspose.Html.Dom.XPath.IXPathEvaluator इंटरफेस. XPath एक्सप्रेशन क मूल्यंकन इसके द्वर प्रदन कय जत हैIXPathEvaluator .
type: docs
weight: 2560
url: /hi/net/aspose.html.dom.xpath/ixpathevaluator/
---
## IXPathEvaluator interface

XPath एक्सप्रेशन का मूल्यांकन इसके द्वारा प्रदान किया जाता है`IXPathEvaluator` .

```csharp
public interface IXPathEvaluator
```

## तरीकों

| नाम | विवरण |
| --- | --- |
| [CreateExpression](../../aspose.html.dom.xpath/ixpathevaluator/createexpression/)(string, IXPathNSResolver) | पार्स किए गए XPath व्यंजक को हल किए गए नामस्थानों के साथ बनाता है. यह उपयोगी है जब किसी एप्लिकेशन में एक अभिव्यक्ति का पुन: उपयोग किया जाएगा क्योंकि यह अभिव्यक्ति स्ट्रिंग को एक अधिक कुशल आंतरिक रूप में संकलित करने के लिए को संभव बनाता है और अभिव्यक्ति के भीतर होने वाले सभी नामस्थान उपसर्गों को पूर्व-समाधान करता है। |
| [CreateNSResolver](../../aspose.html.dom.xpath/ixpathevaluator/creatensresolver/)(Node) | नामस्थानों को हल करने के लिए किसी भी DOM नोड को अनुकूलित करता है ताकि XPath एक्सप्रेशन का आसानी से मूल्यांकन किया जा सके उस नोड के संदर्भ के सापेक्ष जहां वह दस्तावेज़ में दिखाई दिया था। यह एडॉप्टर DOM लेवल 3 विधि की तरह काम करता है`lookupNamespaceURI` नोड के पदानुक्रम में time lookupNamespaceURI पर उपलब्ध वर्तमान जानकारी का उपयोग करके दिए गए उपसर्ग से namespaceURI को हल करने में नोड्स पर, अंतर्निहित xml उपसर्ग को भी सही ढंग से हल करना। |
| [Evaluate](../../aspose.html.dom.xpath/ixpathevaluator/evaluate/)(string, Node, IXPathNSResolver, XPathResultType, object) | एक XPath अभिव्यक्ति स्ट्रिंग का मूल्यांकन करता है और यदि संभव हो तो निर्दिष्ट प्रकार का परिणाम देता है। |

### यह सभी देखें

* नाम स्थान [Aspose.Html.Dom.XPath](../../aspose.html.dom.xpath/)
* सभा [Aspose.HTML](../../)



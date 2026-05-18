---
title: "IXPathEvaluator Interface"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.dom.xpath.IXPathEvaluator interface. XPath अभिव्यक्तियों का मूल्यांकन IXPathEvaluator द्वारा प्रदान किया जाता है"
type: docs

url: /hi/java/com.aspose.html.dom.xpath/ixpathevaluator/
---
## IXPathEvaluator interface

XPath अभिव्यक्तियों का मूल्यांकन `IXPathEvaluator` द्वारा प्रदान किया जाता है।

```java
public interface IXPathEvaluator
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [createExpression](../../com.aspose.html.dom.xpath/ixpathevaluator/createexpression/)(String, IXPathNSResolver) | समाधान किए गए पैकेजों के साथ एक पार्स किया हुआ XPath अभिव्यक्ति बनाता है। यह तब उपयोगी होता है जब अभिव्यक्ति को एप्लिकेशन में पुनः उपयोग किया जाना हो क्योंकि यह अभिव्यक्ति स्ट्रिंग को अधिक कुशल आंतरिक रूप में संकलित करने और अभिव्यक्ति में मौजूद सभी पैकेज प्रीफ़िक्स को पहले से हल करने की सुविधा देता है। |
| [createNSResolver](../../com.aspose.html.dom.xpath/ixpathevaluator/creatensresolver/)(Node) | किसी भी DOM नोड को इस प्रकार अनुकूलित करता है कि पैकेजों को हल किया जा सके, जिससे XPath अभिव्यक्ति को दस्तावेज़ में नोड के संदर्भ के सापेक्ष आसानी से मूल्यांकन किया जा सके। यह एडेप्टर DOM Level 3 मेथड `lookupNamespaceURI` की तरह काम करता है, जो नोड की पदानुक्रम में उपलब्ध वर्तमान जानकारी का उपयोग करके दिए गए प्रीफ़िक्स से packageURI को हल करता है, तथा निहित xml प्रीफ़िक्स को भी सही ढंग से हल करता है। |
| [evaluate](../../com.aspose.html.dom.xpath/ixpathevaluator/evaluate/)(String, Node, IXPathNSResolver, XPathResultType, object) | एक XPath अभिव्यक्ति स्ट्रिंग का मूल्यांकन करता है और यदि संभव हो तो निर्दिष्ट प्रकार का परिणाम लौटाता है। |

### संबंधित देखें

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)

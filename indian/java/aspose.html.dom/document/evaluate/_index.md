---
title: "Document.Evaluate"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "Document मेथड। एक XPath एक्सप्रेशन स्ट्रिंग का मूल्यांकन करता है और यदि संभव हो तो निर्दिष्ट प्रकार का परिणाम लौटाता है।"
type: docs

url: /hi/java/com.aspose.html.dom/document/evaluate/
---
## Document.Evaluate method

एक XPath अभिव्यक्ति स्ट्रिंग का मूल्यांकन करता है और यदि संभव हो तो निर्दिष्ट प्रकार का परिणाम लौटाता है।

```java
public IXPathResult Evaluate(String expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| अभिव्यक्ति | String | पार्स और मूल्यांकन किए जाने वाली XPath अभिव्यक्ति स्ट्रिंग। |
| contextNode | Node | संदर्भ इस XPath एक्सप्रेशन के मूल्यांकन के लिए कंटेक्स्ट नोड है। |
| resolver | IXPathNSResolver | रेज़ॉल्वर XPath एक्सप्रेशन के भीतर सभी प्रीफ़िक्स, जिसमें xml पैकेज प्रीफ़िक्स शामिल है, को उपयुक्त पैकेज URI में अनुवाद की अनुमति देता है। |
| प्रकार | XPathResultType | यदि कोई विशिष्ट प्रकार निर्दिष्ट किया गया है, तो परिणाम को संबंधित प्रकार के रूप में लौटाया जाएगा। |
| result | ऑब्जेक्ट | परिणाम एक विशिष्ट परिणाम ऑब्जेक्ट को निर्दिष्ट करता है जिसे इस मेथड द्वारा पुन: उपयोग किया जा सकता है और लौटाया जा सकता है। |

### रिटर्न वैल्यू

XPath एक्सप्रेशन के मूल्यांकन का परिणाम।

### संबंधित देखें

* interface [IXPathResult](../../../com.aspose.html.dom.xpath/ixpathresult/)
* class [Node](../../node/)
* interface [IXPathNSResolver](../../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* enum [XPathResultType](../../../com.aspose.html.dom.xpath/xpathresulttype/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

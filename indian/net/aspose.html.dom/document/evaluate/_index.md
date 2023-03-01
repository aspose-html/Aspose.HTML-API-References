---
title: Document.Evaluate
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Document तरक. एक XPath अभव्यक्त स्ट्रंग क मूल्यंकन करत है और यद संभव ह त नर्दष्ट प्रकर क परणम देत है
type: docs
weight: 950
url: /hi/net/aspose.html.dom/document/evaluate/
---
## Document.Evaluate method

एक XPath अभिव्यक्ति स्ट्रिंग का मूल्यांकन करता है और यदि संभव हो तो निर्दिष्ट प्रकार का परिणाम देता है।

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| expression | String | पार्स और मूल्यांकित की जाने वाली XPath व्यंजक स्ट्रिंग. |
| contextNode | Node | संदर्भ इस XPath अभिव्यक्ति के मूल्यांकन के लिए संदर्भ नोड है। |
| resolver | IXPathNSResolver | रिज़ॉल्वर XPath व्यंजक के अंतर्गत xml नामस्थान उपसर्ग सहित सभी उपसर्गों के उपयुक्त नामस्थान URI में अनुवाद की अनुमति देता है। |
| type | XPathResultType | यदि एक विशिष्ट प्रकार निर्दिष्ट किया गया है, तो परिणाम संबंधित प्रकार के रूप में लौटाया जाएगा। |
| result | Object | परिणाम एक विशिष्ट परिणाम वस्तु को निर्दिष्ट करता है जिसका पुन: उपयोग किया जा सकता है और इस विधि द्वारा वापस किया जा सकता है। |

### प्रतिलाभ की मात्रा

XPath व्यंजक के मूल्यांकन का परिणाम.

### यह सभी देखें

* interface [IXPathResult](../../../aspose.html.dom.xpath/ixpathresult/)
* class [Node](../../node/)
* interface [IXPathNSResolver](../../../aspose.html.dom.xpath/ixpathnsresolver/)
* enum [XPathResultType](../../../aspose.html.dom.xpath/xpathresulttype/)
* class [Document](../)
* नाम स्थान [Aspose.Html.Dom](../../document/)
* सभा [Aspose.HTML](../../../)



---
title: IXPathEvaluator.CreateExpression
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: IXPathEvaluator तरक. पर्स कए गए XPath व्यंजक क हल कए गए नमस्थनं के सथ बनत है. यह उपयग है जब कस एप्लकेशन में एक अभव्यक्त क पुन उपयग कय जएग क्यंक यह अभव्यक्त स्ट्रंग क एक अधक कुशल आंतरक रूप में संकलत करने के लए क संभव बनत है और अभव्यक्त के भतर हने वले सभ नमस्थन उपसर्गं क पूर्वसमधन करत है
type: docs
weight: 10
url: /hi/net/aspose.html.dom.xpath/ixpathevaluator/createexpression/
---
## IXPathEvaluator.CreateExpression method

पार्स किए गए XPath व्यंजक को हल किए गए नामस्थानों के साथ बनाता है. यह उपयोगी है जब किसी एप्लिकेशन में एक अभिव्यक्ति का पुन: उपयोग किया जाएगा क्योंकि यह अभिव्यक्ति स्ट्रिंग को एक अधिक कुशल आंतरिक रूप में संकलित करने के लिए को संभव बनाता है और अभिव्यक्ति के भीतर होने वाले सभी नामस्थान उपसर्गों को पूर्व-समाधान करता है।

```csharp
public IXPathExpression CreateExpression(string expression, IXPathNSResolver resolver)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| expression | String | पार्स की जाने वाली XPath व्यंजक स्ट्रिंग. |
| resolver | IXPathNSResolver | `रिज़ॉल्वर` सहित सभी उपसर्गों के अनुवाद की अनुमति देता है`एक्सएमएल` नामस्थान उपसर्ग, XPath अभिव्यक्ति के भीतर उपयुक्त नामस्थान URI में। यदि यह निर्दिष्ट किया गया है`व्यर्थ` , किसी भी नामस्थान उपसर्ग के भीतर अभिव्यक्ति का परिणाम होगा[`DOMException`](../../../aspose.html.dom/domexception/) कोड के साथ फेंका जा रहा है`NAMESPACE_ERR`. |

### प्रतिलाभ की मात्रा

XPath एक्सप्रेशन का संकलित रूप।

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: यदि व्यंजक के नियमों के अनुसार वैधानिक नहीं है तो उठाया जाता है[`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | NAMESPACE_ERR: यदि व्यंजक में नाम स्थान उपसर्ग है जिसे निर्दिष्ट द्वारा हल नहीं किया जा सकता है, तो उठाया जाता है[`IXPathNSResolver`](../../ixpathnsresolver/). |

### यह सभी देखें

* interface [IXPathExpression](../../ixpathexpression/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* interface [IXPathEvaluator](../)
* नाम स्थान [Aspose.Html.Dom.XPath](../../ixpathevaluator/)
* सभा [Aspose.HTML](../../../)



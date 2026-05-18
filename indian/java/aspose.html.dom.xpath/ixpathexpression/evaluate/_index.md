---
title: "IXPathExpression.Evaluate"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "IXPathExpression मेथड। इस XPath अभिव्यक्ति का मूल्यांकन करता है और एक परिणाम लौटाता है।"
type: docs

url: /hi/java/com.aspose.html.dom.xpath/ixpathexpression/evaluate/
---
## IXPathExpression.Evaluate method

इस XPath अभिव्यक्ति का मूल्यांकन करता है और एक परिणाम लौटाता है।

```java
public IXPathResult Evaluate(Node contextNode, XPathResultType type, object result)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| contextNode | Node | `context` वह कॉन्टेक्स्ट नोड है इस XPath अभिव्यक्ति के मूल्यांकन के लिए। यदि [`IXPathEvaluator`](../../ixpathevaluator/) को [`Document`](../../../com.aspose.html.dom/document/) को कास्ट करके प्राप्त किया गया है तो यह उसी दस्तावेज़ द्वारा स्वामित्व में होना चाहिए और यह एक [`Document`](../../../com.aspose.html.dom/document/), [`Element`](../../../com.aspose.html.dom/element/), [`Attr`](../../../com.aspose.html.dom/attr/), [`Text`](../../../com.aspose.html.dom/text/), [`CDATASection`](../../../com.aspose.html.dom/cdatasection/), [`Comment`](../../../com.aspose.html.dom/comment/), [`ProcessingInstruction`](../../../com.aspose.html.dom/processinginstruction/) या XPathNamespace नोड होना चाहिए। यदि कॉन्टेक्स्ट नोड एक [`Text`](../../../com.aspose.html.dom/text/) या एक [`CDATASection`](../../../com.aspose.html.dom/cdatasection/) है, तो कॉन्टेक्स्ट को XPath द्वारा देखे गए पूरे लॉजिकल टेक्स्ट नोड के रूप में व्याख्यायित किया जाता है, जब तक नोड खाली न हो, ऐसे में यह XPath कॉन्टेक्स्ट के रूप में कार्य नहीं कर सकता। |
| type | XPathResultType | यदि कोई विशिष्ट `type` निर्दिष्ट किया गया है, तो परिणाम को निर्दिष्ट प्रकार लौटाने के लिए XPath रूपांतरणों पर निर्भर करते हुए रूपांतरित किया जाएगा और यदि वांछित रूपांतरण संभव नहीं है तो यह विफल होगा। यह [`XPathResultType`](../../xpathresulttype/) के मानों में से एक होना चाहिए। |
| result | Object | `result` एक विशिष्ट परिणाम ऑब्जेक्ट निर्दिष्ट करता है जिसे इस मेथड द्वारा पुन: उपयोग किया जा सकता है और लौटाया जा सकता है। यदि इसे `null` के रूप में निर्दिष्ट किया जाता है या कार्यान्वयन निर्दिष्ट परिणाम को पुन: उपयोग नहीं करता, तो एक नया परिणाम ऑब्जेक्ट बनाया जाएगा और लौटाया जाएगा। XPath 1.0 परिणामों के लिए, यह ऑब्जेक्ट प्रकार [`IXPathResult`](../../ixpathresult/) का होगा। |

### रिटर्न वैल्यू

XPath अभिव्यक्ति के मूल्यांकन का परिणाम। XPath 1.0 परिणामों के लिए, यह ऑब्जेक्ट प्रकार [`IXPathResult`](../../ixpathresult/) का होगा।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: यदि परिणाम को निर्दिष्ट प्रकार में परिवर्तित नहीं किया जा सकता तो उत्पन्न होता है। |
| [dOMException](../../../com.aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: नोड उस दस्तावेज़ से है जो उस [`IXPathEvaluator`](../../ixpathevaluator/) द्वारा समर्थित नहीं है जिसने यह [`IXPathExpression`](../) बनाया। |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: नोड वह प्रकार नहीं है जो XPath कॉन्टेक्स्ट नोड के रूप में अनुमति प्राप्त है या अनुरोध प्रकार इस [`IXPathExpression`](../) द्वारा अनुमति प्राप्त नहीं है। |

### संबंधित देखें

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../com.aspose.html.dom/node/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathExpression](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)

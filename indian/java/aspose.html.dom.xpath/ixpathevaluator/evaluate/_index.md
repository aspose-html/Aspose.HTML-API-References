---
title: "IXPathEvaluator.Evaluate"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "IXPathEvaluator मेथड। एक XPath अभिव्यक्ति स्ट्रिंग का मूल्यांकन करता है और यदि संभव हो तो निर्दिष्ट प्रकार का परिणाम लौटाता है।"
type: docs

url: /hi/java/com.aspose.html.dom.xpath/ixpathevaluator/evaluate/
---
## IXPathEvaluator.Evaluate method

एक XPath अभिव्यक्ति स्ट्रिंग का मूल्यांकन करता है और यदि संभव हो तो निर्दिष्ट प्रकार का परिणाम लौटाता है।

```java
public IXPathResult Evaluate(String expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| अभिव्यक्ति | String | पार्स और मूल्यांकन करने के लिए XPath अभिव्यक्ति स्ट्रिंग। |
| contextNode | Node | `context` इस XPath अभिव्यक्ति के मूल्यांकन के लिए संदर्भ नोड है। यदि [`IXPathEvaluator`](../) को [`Document`](../../../com.aspose.html.dom/document/) को कास्ट करके प्राप्त किया गया है, तो यह उसी दस्तावेज़ का स्वामित्व होना चाहिए और यह एक [`Document`](../../../com.aspose.html.dom/document/), [`Element`](../../../com.aspose.html.dom/element/), [`Attr`](../../../com.aspose.html.dom/attr/), [`Text`](../../../com.aspose.html.dom/text/), [`CDATASection`](../../../com.aspose.html.dom/cdatasection/), [`Comment`](../../../com.aspose.html.dom/comment/), [`ProcessingInstruction`](../../../com.aspose.html.dom/processinginstruction/) या XPathNamespace नोड होना चाहिए। यदि संदर्भ नोड एक [`Text`](../../../com.aspose.html.dom/text/) या एक [`CDATASection`](../../../com.aspose.html.dom/cdatasection/) है, तो संदर्भ को XPath द्वारा देखे जाने वाले पूरे तार्किक टेक्स्ट नोड के रूप में व्याख्यायित किया जाता है, जब तक कि नोड खाली न हो, ऐसी स्थिति में यह XPath संदर्भ के रूप में कार्य नहीं कर सकता। |
| resolver | IXPathNSResolver | `resolver` सभी प्रीफ़िक्स, जिसमें `xml` पैकेज प्रीफ़िक्स भी शामिल है, को XPath अभिव्यक्ति के भीतर उपयुक्त पैकेज URI में अनुवाद करने की अनुमति देता है। यदि इसे `null` के रूप में निर्दिष्ट किया जाता है, तो अभिव्यक्ति के भीतर कोई भी पैकेज प्रीफ़िक्स [`DOMException`](../../../com.aspose.html.dom/domexception/) को कोड `NAMESPACE_ERR` के साथ थ्रो करने का कारण बनेगा। |
| type | XPathResultType | यदि कोई विशिष्ट `type` निर्दिष्ट किया गया है, तो परिणाम संबंधित प्रकार के रूप में लौटाया जाएगा। XPath 1.0 परिणामों के लिए, यह [`XPathResultType`](../../xpathresulttype/) enum के मानों में से एक होना चाहिए। |
| result | Object | `result` एक विशिष्ट परिणाम ऑब्जेक्ट निर्दिष्ट करता है जिसे इस मेथड द्वारा पुन: उपयोग किया जा सकता है और लौटाया जा सकता है। यदि इसे `null` के रूप में निर्दिष्ट किया गया है या कार्यान्वयन निर्दिष्ट परिणाम को पुन: उपयोग नहीं करता, तो एक नया परिणाम ऑब्जेक्ट बनाया जाएगा और लौटाया जाएगा। XPath 1.0 परिणामों के लिए, यह ऑब्जेक्ट प्रकार [`IXPathResult`](../../ixpathresult/) का होगा। |

### रिटर्न वैल्यू

XPath अभिव्यक्ति के मूल्यांकन का परिणाम। XPath 1.0 परिणामों के लिए, यह ऑब्जेक्ट प्रकार [`IXPathResult`](../../ixpathresult/) का होगा।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: यदि अभिव्यक्ति [`IXPathEvaluator`](../) के नियमों के अनुसार वैध नहीं है तो उत्पन्न होता है। |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: यदि परिणाम को निर्दिष्ट प्रकार में परिवर्तित नहीं किया जा सकता तो उत्पन्न होता है। |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NAMESPACE_ERR: यदि अभिव्यक्ति में ऐसे पैकेज प्रीफ़िक्स हैं जिन्हें निर्दिष्ट [`IXPathNSResolver`](../../ixpathnsresolver/) द्वारा हल नहीं किया जा सकता, तो उत्पन्न होता है। |
| [dOMException](../../../com.aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: नोड ऐसे दस्तावेज़ से है जो इस [`IXPathEvaluator`](../) द्वारा समर्थित नहीं है। |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: नोड वह प्रकार नहीं है जो XPath संदर्भ नोड के रूप में अनुमति प्राप्त है या अनुरोधित प्रकार इस [`IXPathEvaluator`](../) द्वारा अनुमति नहीं है। |

### संबंधित देखें

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathEvaluator](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)

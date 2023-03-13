---
title: IXPathEvaluator.Evaluate
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: IXPathEvaluator तरक. एक XPath अभव्यक्त स्ट्रंग क मूल्यंकन करत है और यद संभव ह त नर्दष्ट प्रकर क परणम देत है
type: docs
weight: 30
url: /hi/net/aspose.html.dom.xpath/ixpathevaluator/evaluate/
---
## IXPathEvaluator.Evaluate method

एक XPath अभिव्यक्ति स्ट्रिंग का मूल्यांकन करता है और यदि संभव हो तो निर्दिष्ट प्रकार का परिणाम देता है।

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| expression | String | पार्स और मूल्यांकित की जाने वाली XPath व्यंजक स्ट्रिंग. |
| contextNode | Node | `प्रसंग` इस XPath व्यंजक के मूल्यांकन के लिए संदर्भ नोड है। अगर[`IXPathEvaluator`](../) कास्ट करके प्राप्त किया गया था[`Document`](../../../aspose.html.dom/document/) तो यह उसी दस्तावेज़ के स्वामित्व में होना चाहिए और एक होना चाहिए[`Document`](../../../aspose.html.dom/document/) ,[`Element`](../../../aspose.html.dom/element/) ,[`Attr`](../../../aspose.html.dom/attr/) ,[`Text`](../../../aspose.html.dom/text/) , [`CDATASection`](../../../aspose.html.dom/cdatasection/) ,[`Comment`](../../../aspose.html.dom/comment/) ,[`ProcessingInstruction`](../../../aspose.html.dom/processinginstruction/) , याXPathNamespace नोड। यदि संदर्भ नोड a[`Text`](../../../aspose.html.dom/text/) या एक [`CDATASection`](../../../aspose.html.dom/cdatasection/)तब संदर्भ को संपूर्ण तार्किक पाठ नोड के रूप में समझा जाता है जैसा कि XPath द्वारा देखा जाता है, जब तक कि नोड खाली न हो, जिस स्थिति में यह XPath संदर्भ के रूप में कार्य नहीं कर सकता है। |
| resolver | IXPathNSResolver | `रिज़ॉल्वर` सहित सभी उपसर्गों के अनुवाद की अनुमति देता है`एक्सएमएल` नेमस्पेस प्रीफ़िक्स, XPath एक्सप्रेशन के भीतर उपयुक्त नेमस्पेस URI में। यदि इसे निर्दिष्ट किया गया है`व्यर्थ` , व्यंजक के भीतर किसी भी नाम स्थान के उपसर्ग का परिणाम होगा[`DOMException`](../../../aspose.html.dom/domexception/) कोड के साथ फेंका जा रहा है`NAMESPACE_ERR`. |
| type | XPathResultType | यदि कोई विशिष्ट`प्रकार` निर्दिष्ट किया गया है, तो परिणाम संबंधित प्रकार के रूप में लौटाया जाएगा। XPath 1.0 परिणामों के लिए, यह के मानों में से एक होना चाहिए[`XPathResultType`](../../xpathresulttype/) एनुम। |
| result | Object | `परिणाम` एक विशिष्ट परिणाम ऑब्जेक्ट निर्दिष्ट करता है जिसका पुन: उपयोग किया जा सकता है और इस विधि द्वारा लौटाया जा सकता है। यदि यह निर्दिष्ट किया गया है`व्यर्थ`या कार्यान्वयन निर्दिष्ट परिणाम का पुन: उपयोग नहीं करता है, एक नया परिणाम ऑब्जेक्ट बनाया जाएगा और लौटाया जाएगा। XPath 1.0 परिणामों के लिए, यह ऑब्जेक्ट प्रकार का होगा[`IXPathResult`](../../ixpathresult/). |

### प्रतिलाभ की मात्रा

XPath व्यंजक के मूल्यांकन का परिणाम. XPath 1.0 परिणामों के लिए, यह ऑब्जेक्ट प्रकार का होगा[`IXPathResult`](../../ixpathresult/).

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: यदि व्यंजक के नियमों के अनुसार कानूनी नहीं है तो उठाया गया[`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | TYPE_ERR: यदि परिणाम निर्दिष्ट प्रकार को वापस करने के लिए परिवर्तित नहीं किया जा सकता है तो उठाया गया। |
| [DOMException](../../../aspose.html.dom/domexception/) | NAMESPACE_ERR: यदि व्यंजक में नामस्थान उपसर्ग है जिसे निर्दिष्ट द्वारा हल नहीं किया जा सकता है तो उठाया जाता है[`IXPathNSResolver`](../../ixpathnsresolver/). |
| [DOMException](../../../aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: नोड एक ऐसे दस्तावेज़ से है जो इसके द्वारा समर्थित नहीं है[`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: नोड XPath संदर्भ नोड के रूप में अनुमत प्रकार नहीं है या इसके द्वारा अनुरोध प्रकार की अनुमति नहीं है[`IXPathEvaluator`](../). |

### यह सभी देखें

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathEvaluator](../)
* नाम स्थान [Aspose.Html.Dom.XPath](../../ixpathevaluator/)
* सभा [Aspose.HTML](../../../)



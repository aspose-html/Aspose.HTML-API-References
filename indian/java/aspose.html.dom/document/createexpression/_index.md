---
title: "Document.CreateExpression"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "Document मेथड। हल किए गए पैकेजों के साथ एक पार्स किया गया XPath अभिव्यक्ति बनाता है। यह तब उपयोगी है जब किसी अभिव्यक्ति को एप्लिकेशन में पुन: उपयोग किया जाएगा क्योंकि यह अभिव्यक्ति स्ट्रिंग को अधिक कुशल आंतरिक रूप में संकलित करने और अभिव्यक्ति में उपस्थित सभी पैकेज प्रीफ़िक्स को पहले से हल करने की अनुमति देता है।"
type: docs

url: /hi/java/com.aspose.html.dom/document/createexpression/
---
## Document.CreateExpression method

समाधान किए गए पैकेजों के साथ एक पार्स किया हुआ XPath अभिव्यक्ति बनाता है। यह तब उपयोगी होता है जब अभिव्यक्ति को एप्लिकेशन में पुनः उपयोग किया जाना हो क्योंकि यह अभिव्यक्ति स्ट्रिंग को अधिक कुशल आंतरिक रूप में संकलित करने और अभिव्यक्ति में मौजूद सभी पैकेज प्रीफ़िक्स को पहले से हल करने की सुविधा देता है।

```java
public IXPathExpression CreateExpression(String expression, IXPathNSResolver resolver)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| अभिव्यक्ति | String | पार्स किए जाने वाली XPath अभिव्यक्ति स्ट्रिंग। |
| resolver | IXPathNSResolver | `resolver` सभी प्रीफ़िक्स, जिसमें `xml` पैकेज प्रीफ़िक्स शामिल है, को XPath अभिव्यक्ति के भीतर उपयुक्त पैकेज URI में अनुवाद करने की अनुमति देता है। यदि इसे `null` के रूप में निर्दिष्ट किया जाता है, तो अभिव्यक्ति के भीतर कोई भी पैकेज प्रीफ़िक्स [`DOMException`](../../domexception/) को कोड `NAMESPACE_ERR` के साथ थ्रो करेगा। |

### रिटर्न वैल्यू

XPath अभिव्यक्ति का संकलित रूप।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [dOMException](../../domexception/) | INVALID_EXPRESSION_ERR: यदि अभिव्यक्ति [`IXPathEvaluator`](../../../com.aspose.html.dom.xpath/ixpathevaluator/) के नियमों के अनुसार वैध नहीं है तो उत्पन्न होता है। |
| [dOMException](../../domexception/) | NAMESPACE_ERR: यदि अभिव्यक्ति में ऐसे पैकेज प्रीफ़िक्स हैं जिन्हें निर्दिष्ट [`IXPathNSResolver`](../../../com.aspose.html.dom.xpath/ixpathnsresolver/) द्वारा हल नहीं किया जा सकता है तो उत्पन्न होता है। |

### संबंधित देखें

* interface [IXPathExpression](../../../com.aspose.html.dom.xpath/ixpathexpression/)
* interface [IXPathNSResolver](../../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

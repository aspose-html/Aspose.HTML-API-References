---
title: "IXPathResult.IterateNext"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "IXPathResult मेथड। नोड सेट से अगला नोड इटरेट करता है और लौटाता है या यदि और नोड नहीं हैं तो null लौटाता है।"
type: docs

url: /hi/java/com.aspose.html.dom.xpath/ixpathresult/iteratenext/
---
## IXPathResult.IterateNext method

नोड सेट से अगला नोड इटररेट करता है और लौटाता है, या यदि और नोड नहीं हैं तो `null`।

```java
public Node IterateNext()
```

### रिटर्न वैल्यू

अगला नोड लौटाता है।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: यदि `resultType` `UnorderedNodeIterator` प्रकार या `OrderedNodeIterator` प्रकार नहीं है तो उत्पन्न होता है। |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_STATE_ERR: परिणाम लौटाए जाने के बाद दस्तावेज़ में परिवर्तन किया गया है। |

### संबंधित देखें

* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathResult](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)

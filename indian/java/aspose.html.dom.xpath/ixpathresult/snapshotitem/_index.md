---
title: "IXPathResult.SnapshotItem"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "IXPathResult मेथड। स्नैपशॉट संग्रह में indexवाँ आइटम लौटाता है। यदि index सूची में नोड्स की संख्या से बड़ा या बराबर है तो यह मेथड null लौटाता है। इटररेटर परिणाम के विपरीत, स्नैपशॉट अमान्य नहीं होता लेकिन यदि दस्तावेज़ में परिवर्तन किया गया है तो यह वर्तमान दस्तावेज़ से मेल नहीं खा सकता।"
type: docs

url: /hi/java/com.aspose.html.dom.xpath/ixpathresult/snapshotitem/
---
## IXPathResult.SnapshotItem method

स्नैपशॉट संग्रह में `index`वें आइटम को लौटाता है। यदि `index` सूची में नोड्स की संख्या से बड़ा या बराबर है, तो यह मेथड `null` लौटाता है। इटररेटर परिणाम के विपरीत, स्नैपशॉट अमान्य नहीं होता, लेकिन यदि दस्तावेज़ बदलता है तो यह वर्तमान दस्तावेज़ से मेल नहीं खा सकता।

```java
public Node SnapshotItem(int index)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| index | Int32 | स्नैपशॉट संग्रह में इंडेक्स। |

### रिटर्न वैल्यू

`NodeList` में `index`वाँ स्थिति पर नोड, या यदि वह वैध इंडेक्स नहीं है तो `null`।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: यदि `resultType` `UnorderedNodeSnapshot` प्रकार या `OrderedNodeSnapshot` प्रकार नहीं है तो उत्पन्न होता है। |

### संबंधित देखें

* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathResult](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)

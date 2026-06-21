---
title: "IXPathResult.SnapshotItem"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "IXPathResult method. स्नैपशॉट संग्रह में indexवां आइटम लौटाता है। यदि index सूची में नोड्स की संख्या के बराबर या उससे अधिक है तो यह विधि null लौटाती है। इटररेटर परिणाम के विपरीत, स्नैपशॉट अमान्य नहीं होता लेकिन यदि दस्तावेज़ में परिवर्तन किया गया हो तो यह वर्तमान दस्तावेज़ से मेल नहीं खा सकता।"
type: docs

url: /hi/java/com.aspose.html.dom.xpath/ixpathresult/snapshotitem/
---
## IXPathResult.SnapshotItem method

`index`वें आइटम को स्नैपशॉट संग्रह में लौटाता है। यदि `index` सूची में नोड्स की संख्या से बड़ा या बराबर है, तो यह मेथड `null` लौटाता है। इटररेटर परिणाम के विपरीत, स्नैपशॉट अमान्य नहीं होता, लेकिन यदि दस्तावेज़ बदल दिया गया हो तो यह वर्तमान दस्तावेज़ से मेल नहीं खा सकता।

```java
public Node SnapshotItem(int index)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | Int32 | स्नैपशॉट संग्रह में इंडेक्स। |

### रिटर्न वैल्यू

`NodeList` में `index`वां स्थिति पर नोड, या यदि वह मान्य इंडेक्स नहीं है तो `null`।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: यदि `resultType` `UnorderedNodeSnapshot` प्रकार या `OrderedNodeSnapshot` प्रकार नहीं है तो उत्पन्न होता है। |

### संबंधित देखें

* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathResult](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)

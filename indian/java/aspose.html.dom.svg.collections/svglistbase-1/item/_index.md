---
title: "SVGListBase-1.Item"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "SVGListBase प्रॉपर्टी। सूची में इंडेक्सवाँ आइटम लौटाता है"
type: docs

url: /hi/java/com.aspose.html.dom.svg.collections/svglistbase-1/item/
---
## SVGListBase&lt;T&gt; indexer

सूची में इंडेक्सवाँ आइटम लौटाता है।

```java
public T this[ulong index] { get; set; }
```

| पैरामीटर | विवरण |
| --- | --- |
| index | सूची में इंडेक्स। |

### रिटर्न वैल्यू

सूची में इंडेक्सवाँ स्थिति पर संग्रहीत ऑब्जेक्ट।

### Property Value

सूची में संग्रहीत आइटम का प्रकार।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | कोड [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). जब सूची को संशोधित नहीं किया जा सकता तब उत्पन्न होता है। |
| [dOMException](../../../com.aspose.html.dom/domexception/) | कोड [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). यदि सूचकांक संख्या numberOfItems से बड़ी या बराबर हो तो उत्पन्न होता है। |

### संबंधित देखें

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)

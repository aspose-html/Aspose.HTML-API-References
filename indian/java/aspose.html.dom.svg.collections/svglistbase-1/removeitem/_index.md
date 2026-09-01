---
title: "SVGListBase-1.RemoveItem"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "SVGListBase मेथड। सूची से मौजूदा आइटम को हटाता है"
type: docs

url: /hi/java/com.aspose.html.dom.svg.collections/svglistbase-1/removeitem/
---
## SVGListBase&lt;T&gt;.RemoveItem method

सूची से एक मौजूदा आइटम हटाता है।

```java
public T RemoveItem(ulong index)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | UInt64 | हटाए जाने वाले आइटम का इंडेक्स। पहला आइटम संख्या 0 है। |

### रिटर्न वैल्यू

हटाया गया आइटम।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | कोड [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). जब सूची को संशोधित नहीं किया जा सकता तब उत्पन्न होता है। |
| [dOMException](../../../com.aspose.html.dom/domexception/) | कोड [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). यदि सूचकांक संख्या numberOfItems से बड़ी या बराबर हो तो उत्पन्न होता है। |

### संबंधित देखें

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)

---
title: "SVGListBase-1.ReplaceItem"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "SVGListBase मेथड। सूची में मौजूदा आइटम को एक नए आइटम से बदलता है।"
type: docs

url: /hi/java/com.aspose.html.dom.svg.collections/svglistbase-1/replaceitem/
---
## SVGListBase&lt;T&gt;.ReplaceItem method

सूची में मौजूदा आइटम को एक नए आइटम से बदलता है।

```java
public T ReplaceItem(T newItem, ulong index)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| newItem | T | सूची में सम्मिलित किया जाने वाला आइटम। |
| index | UInt64 | जिस आइटम को बदलना है उसका सूचकांक। पहला आइटम संख्या 0 है। |

### रिटर्न वैल्यू

डाला गया आइटम।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | कोड [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). जब सूची को संशोधित नहीं किया जा सकता तब उत्पन्न होता है। |
| [dOMException](../../../com.aspose.html.dom/domexception/) | कोड [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). यदि सूचकांक संख्या numberOfItems से बड़ी या बराबर हो तो उत्पन्न होता है। |

### संबंधित देखें

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)

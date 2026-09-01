---
title: "SVGListBase-1.InsertItemBefore"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "SVGListBase मेथड। निर्दिष्ट स्थिति पर सूची में नया आइटम सम्मिलित करता है। पहला आइटम संख्या 0 है।"
type: docs

url: /hi/java/com.aspose.html.dom.svg.collections/svglistbase-1/insertitembefore/
---
## SVGListBase&lt;T&gt;.InsertItemBefore method

निर्दिष्ट स्थिति पर सूची में एक नया आइटम सम्मिलित करता है। पहला आइटम संख्या 0 है।

```java
public T InsertItemBefore(T newItem, ulong index)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| newItem | T | सूची में सम्मिलित किया जाने वाला आइटम। |
| index | UInt64 | नए आइटम को सम्मिलित करने से पहले वाले आइटम का सूचकांक। पहला आइटम संख्या 0 है। यदि सूचकांक 0 के बराबर है, तो नया आइटम सूची की शुरुआत में सम्मिलित होता है। यदि सूचकांक numberOfItems से बड़ा या बराबर है, तो नया आइटम सूची के अंत में जोड़ा जाता है। |

### रिटर्न वैल्यू

डाला गया आइटम।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | कोड [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). जब सूची को संशोधित नहीं किया जा सकता तब उत्पन्न होता है। |

### संबंधित देखें

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)

---
title: "Element.AttachShadow"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "Element विधि. शैडो रूट बनाता है और इसे वर्तमान तत्व से संलग्न करता है"
type: docs

url: /hi/java/com.aspose.html.dom/element/attachshadow/
---
## Element.AttachShadow method

एक शैडो रूट बनाता है और उसे वर्तमान तत्व से जोड़ता है।

```java
public ShadowRoot AttachShadow(ShadowRootMode mode)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| मोड | ShadowRootMode | शैडो रूट जिस मोड में बनाया जाएगा। |

### रिटर्न वैल्यू

बनाया गया [`ShadowRoot`](../../shadowroot/).

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| Error | NotSupportedError: Element शैडो ट्री का समर्थन नहीं करता है। |
| Error | InvalidStateError: Element के पास पहले से ही शैडो ट्री है। |

### संबंधित देखें

* class [ShadowRoot](../../shadowroot/)
* enum [ShadowRootMode](../../shadowrootmode/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

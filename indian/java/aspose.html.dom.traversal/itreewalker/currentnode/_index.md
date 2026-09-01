---
title: "ITreeWalker.CurrentNode"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "ITreeWalker प्रॉपर्टी। वह नोड जहाँ TreeWalker वर्तमान में स्थित है। DOM ट्री में परिवर्तन के कारण वर्तमान नोड TreeWalker के संबंधित फ़िल्टर द्वारा अब स्वीकार नहीं किया जा सकता है। currentNode को स्पष्ट रूप से किसी भी नोड पर सेट किया जा सकता है, चाहे वह रूट नोड द्वारा निर्दिष्ट उपवृक्ष के भीतर हो या नहीं, या फ़िल्टर और whatToShow फ़्लैग्स द्वारा स्वीकार किया जाएगा। आगे का ट्रैवर्सल currentNode के सापेक्ष होता है, भले ही वह वर्तमान दृश्य का हिस्सा न हो, अनुरोधित दिशा में फ़िल्टर लागू करके; यदि कोई ट्रैवर्सल संभव नहीं है तो currentNode नहीं बदला जाता।"
type: docs

url: /hi/java/com.aspose.html.dom.traversal/itreewalker/currentnode/
---
## ITreeWalker.CurrentNode property

TreeWalker जिस नोड पर वर्तमान में स्थित है वह नोड। DOM ट्री में परिवर्तन के कारण वर्तमान नोड TreeWalker के संबंधित फ़िल्टर द्वारा अब स्वीकार नहीं किया जा सकता है। currentNode को स्पष्ट रूप से किसी भी नोड पर सेट किया जा सकता है, चाहे वह रूट नोड द्वारा निर्दिष्ट उपवृक्ष के भीतर हो या नहीं, या फ़िल्टर और whatToShow फ़्लैग्स द्वारा स्वीकार किया जाएगा। आगे का ट्रैवर्सल currentNode के सापेक्ष होता है, भले ही वह वर्तमान दृश्य का हिस्सा न हो, अनुरोधित दिशा में फ़िल्टर लागू करके; यदि कोई ट्रैवर्सल संभव नहीं है, तो currentNode नहीं बदला जाता।

```java
public Node CurrentNode { get; set; }
```

### Property Value

वर्तमान नोड।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: यदि currentNode को null पर सेट करने का प्रयास किया जाता है तो उत्पन्न होता है। |

### संबंधित देखें

* class [Node](../../../com.aspose.html.dom/node/)
* interface [ITreeWalker](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

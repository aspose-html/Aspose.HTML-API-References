---
title: "INodeIterator.NextNode"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "INodeIterator विधि। सेट में अगला नोड लौटाता है और सेट में इटरिटर की स्थिति को आगे बढ़ाता है। एक NodeIterator बनाने के बाद nextNode को पहली बार कॉल करने पर सेट का पहला नोड लौटाया जाता है।"
type: docs

url: /hi/java/com.aspose.html.dom.traversal/inodeiterator/nextnode/
---
## INodeIterator.NextNode method

सेट में अगला नोड लौटाता है और इटररेटर की स्थिति को सेट में आगे बढ़ाता है। एक NodeIterator बनाने के बाद, nextNode() का पहला कॉल सेट में पहला नोड लौटाता है।

```java
public Node NextNode()
```

### रिटर्न वैल्यू

सेट में इटरिट किया जा रहा अगला नोड, या यदि उस सेट में और सदस्य नहीं हैं तो null।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_STATE_ERR: यदि इस विधि को डिटैच विधि को बुलाने के बाद कॉल किया जाता है तो उत्पन्न होता है। |

### संबंधित देखें

* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeIterator](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

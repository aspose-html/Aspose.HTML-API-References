---
title: "Node.CloneNode"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "Node विधि। Node इंटरफ़ेस की cloneNode विधि उस नोड की एक प्रतिलिपि लौटाती है जिस पर यह विधि कॉल की गई थी। इसका पैरामीटर नियंत्रित करता है कि नोड में मौजूद उपवृक्ष भी क्लोन किया जाए या नहीं।"
type: docs

url: /hi/java/com.aspose.html.dom/node/clonenode/
---
## CloneNode() {#clonenode}

cloneNode() मेथड Node इंटरफ़ेस का उस नोड की प्रतिलिपि लौटाता है जिस पर यह मेथड कॉल किया गया था। इसका पैरामीटर नियंत्रित करता है कि नोड में शामिल सबट्री भी क्लोन किया जाए या नहीं।

एक नोड को क्लोन करने से उसके सभी गुण और उनके मान कॉपी हो जाते हैं, जिसमें अंतर्निहित (इनलाइन) लिस्नर भी शामिल हैं। यह उन इवेंट लिस्नरों को कॉपी नहीं करता जो [`addEventListener()`](../../../com.aspose.html.dom.events/ieventtarget/addeventlistener/) का उपयोग करके जोड़े गए हैं या जो तत्व गुणों (जैसे, node.onclick = someFunction) को सौंपे गए हैं। अतिरिक्त रूप से, एक [`&lt;canvas&gt;`](../../../com.aspose.html/htmlcanvaselement/) तत्व के लिए, पेंट की गई छवि कॉपी नहीं होती।

```java
public Node CloneNode()
```

### रिटर्न वैल्यू

नया क्लोन किया गया [`Node`](../)। क्लोन किया गया नोड का कोई पैरेंट नहीं होता और यह दस्तावेज़ का हिस्सा नहीं होता, जब तक कि इसे दस्तावेज़ का हिस्सा किसी अन्य नोड में [`Node.appendChild()`](../appendchild/) या समान विधि का उपयोग करके जोड़ा न जाए।

### संबंधित देखें

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CloneNode(bool) {#clonenode_1}

cloneNode() मेथड Node इंटरफ़ेस का उस नोड की प्रतिलिपि लौटाता है जिस पर यह मेथड कॉल किया गया था। इसका पैरामीटर नियंत्रित करता है कि नोड में शामिल सबट्री भी क्लोन किया जाए या नहीं।

एक नोड को क्लोन करने से उसके सभी गुण और उनके मान कॉपी हो जाते हैं, जिसमें अंतर्निहित (इनलाइन) लिस्नर भी शामिल हैं। यह उन इवेंट लिस्नरों को कॉपी नहीं करता जो [addEventListener()](M:com.aspose.html.dom.events.IEventTarget.AddEventListener(System.String,com.aspose.html.dom.events.IEventListener)) का उपयोग करके जोड़े गए हैं या जो तत्व गुणों (जैसे, node.onclick = someFunction) को सौंपे गए हैं। अतिरिक्त रूप से, एक [&lt;canvas&gt;](T:Aspose.Html.HTMLCanvasElement) तत्व के लिए, पेंट की गई छवि कॉपी नहीं होती।

```java
public Node CloneNode(bool deep)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| deep | Boolean | यदि true है, तो नोड और उसकी पूरी उपवृक्ष, जिसमें चाइल्ड [`Text`](../../text/) नोड्स में हो सकता टेक्स्ट भी शामिल है, भी कॉपी हो जाता है। |

### रिटर्न वैल्यू

नया क्लोन किया गया [Node](T:com.aspose.html.dom.Node)। क्लोन किया गया नोड का कोई पैरेंट नहीं होता और यह दस्तावेज़ का हिस्सा नहीं होता, जब तक कि इसे दस्तावेज़ का हिस्सा किसी अन्य नोड में [Node.appendChild()](M:com.aspose.html.dom.Node.AppendChild(com.aspose.html.dom.Node)) या समान विधि का उपयोग करके जोड़ा न जाए।

### संबंधित देखें

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

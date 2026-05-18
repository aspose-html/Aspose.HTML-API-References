---
title: "Node.CloneNode"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "Node मेथड। Node इंटरफ़ेस का cloneNode मेथड उस नोड की एक प्रतिलिपि लौटाता है जिस पर यह मेथड कॉल किया गया था। इसका पैरामीटर नियंत्रित करता है कि नोड में मौजूद सबट्री भी क्लोन किया जाए या नहीं।"
type: docs

url: /hi/java/com.aspose.html.dom/node/clonenode/
---
## CloneNode() {#clonenode}

cloneNode() मेथड Node इंटरफ़ेस का यह उस नोड की एक प्रतिलिपि लौटाता है जिस पर यह मेथड बुलाया गया था। इसका पैरामीटर नियंत्रित करता है कि नोड में निहित सबट्री भी क्लोन किया जाए या नहीं।

एक नोड को क्लोन करने से उसके सभी एट्रिब्यूट और उनके मान कॉपी हो जाते हैं, जिसमें अंतर्निहित (इनलाइन) लिस्नर भी शामिल हैं। यह उन इवेंट लिस्नरों को कॉपी नहीं करता जो [`addEventListener()`](../../../com.aspose.html.dom.events/ieventtarget/addeventlistener/) का उपयोग करके जोड़े गए हैं या जो एलिमेंट प्रॉपर्टीज़ (जैसे, node.onclick = someFunction) को असाइन किए गए हैं। अतिरिक्त रूप से, एक [`&lt;canvas&gt;`](../../../com.aspose.html/htmlcanvaselement/) एलिमेंट के लिए, पेंटेड इमेज कॉपी नहीं होती।

```java
public Node CloneNode()
```

### रिटर्न वैल्यू

नया क्लोन किया गया [`Node`](../)। क्लोन किया गया नोड का कोई पैरेंट नहीं होता और यह दस्तावेज़ का हिस्सा नहीं रहता, जब तक कि इसे दस्तावेज़ का हिस्सा किसी अन्य नोड में जोड़ नहीं दिया जाता, जैसे कि [`Node.appendChild()`](../appendchild/) या समान किसी मेथड का उपयोग करके।

### संबंधित देखें

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CloneNode(bool) {#clonenode_1}

cloneNode() मेथड Node इंटरफ़ेस का यह उस नोड की एक प्रतिलिपि लौटाता है जिस पर यह मेथड बुलाया गया था। इसका पैरामीटर नियंत्रित करता है कि नोड में निहित सबट्री भी क्लोन किया जाए या नहीं।

एक नोड को क्लोन करने से उसके सभी एट्रिब्यूट और उनके मान कॉपी हो जाते हैं, जिसमें अंतर्निहित (इनलाइन) लिस्नर भी शामिल हैं। यह उन इवेंट लिस्नरों को कॉपी नहीं करता जो [addEventListener()](M:com.aspose.html.dom.events.IEventTarget.AddEventListener(System.String,com.aspose.html.dom.events.IEventListener)) का उपयोग करके जोड़े गए हैं या जो एलिमेंट प्रॉपर्टीज़ (जैसे, node.onclick = someFunction) को असाइन किए गए हैं। अतिरिक्त रूप से, एक [&lt;canvas&gt;](T:Aspose.Html.HTMLCanvasElement) एलिमेंट के लिए, पेंटेड इमेज कॉपी नहीं होती।

```java
public Node CloneNode(bool deep)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| deep | Boolean | यदि true है, तो नोड और उसका पूरा सबट्री, जिसमें चाइल्ड [`Text`](../../text/) नोड्स में हो सकता टेक्स्ट भी शामिल है, कॉपी हो जाता है। |

### रिटर्न वैल्यू

नया क्लोन किया गया [Node](T:com.aspose.html.dom.Node)। क्लोन किया गया नोड का कोई पैरेंट नहीं होता और यह दस्तावेज़ का हिस्सा नहीं रहता, जब तक कि इसे दस्तावेज़ का हिस्सा किसी अन्य नोड में नहीं जोड़ा जाता, जैसे कि [Node.appendChild()](M:com.aspose.html.dom.Node.AppendChild(com.aspose.html.dom.Node)) या समान किसी मेथड का उपयोग करके।

### संबंधित देखें

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

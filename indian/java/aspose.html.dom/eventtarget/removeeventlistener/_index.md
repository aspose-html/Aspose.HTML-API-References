---
title: "EventTarget.RemoveEventListener"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "EventTarget मेथड। यह मेथड इवेंट टार्गेट से इवेंट लिस्नर्स को हटाने की अनुमति देता है। यदि किसी को इवेंट प्रोसेसिंग के दौरान हटाया जाता है तो वह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा। इवेंट लिस्नर्स को हटाए जाने के बाद कभी भी बुलाया नहीं जा सकता।"
type: docs

url: /hi/java/com.aspose.html.dom/eventtarget/removeeventlistener/
---
## RemoveEventListener(String, DOMEventHandler, bool) {#removeeventlistener}

यह विधि इवेंट लक्ष्य से इवेंट लिस्नर को हटाने की अनुमति देती है। यदि इवेंट प्रोसेस हो रहा हो तो इवेंट लिस्नर को हटाया जाता है, तो वह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा। Event Listeners को हटाए जाने के बाद कभी भी बुलाया नहीं जा सकता।

```java
public void RemoveEventListener(String type, DOMEventHandler handler, bool useCapture)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| प्रकार | String | हटाए जा रहे इवेंट प्रकार को निर्दिष्ट करता है। |
| हैंडलर | DOMEventHandler | पैरामीटर यह दर्शाता है कि क्या हटाया जाना है। |
| useCapture | Boolean | निर्दिष्ट करता है कि हटाए जा रहे EventListener को कैप्चरिंग लिस्नर के रूप में पंजीकृत किया गया था या नहीं। यदि कोई लिस्नर दो बार पंजीकृत किया गया था, एक कैप्चर के साथ और एक बिना, तो प्रत्येक को अलग‑अलग हटाना होगा। कैप्चरिंग लिस्नर को हटाने से उसी लिस्नर के गैर‑कैप्चरिंग संस्करण पर प्रभाव नहीं पड़ता, और इसके विपरीत भी यही सत्य है। |

### संबंधित देखें

* delegate [DOMEventHandler](../../../com.aspose.html.dom.events/domeventhandler/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## RemoveEventListener(String, IEventListener) {#removeeventlistener_1}

यह विधि इवेंट लक्ष्य से इवेंट लिस्नर को हटाने की अनुमति देती है। यदि इवेंट प्रोसेस हो रहा हो तो इवेंट लिस्नर को हटाया जाता है, तो वह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा। Event Listeners को हटाए जाने के बाद कभी भी बुलाया नहीं जा सकता।

```java
public void RemoveEventListener(String type, IEventListener listener)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| प्रकार | String | हटाए जा रहे इवेंट प्रकार को निर्दिष्ट करता है। |
| लिस्नर | IEventListener | पैरामीटर यह दर्शाता है कि क्या हटाया जाना है। |

### संबंधित देखें

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## RemoveEventListener(String, IEventListener, bool) {#removeeventlistener_2}

यह विधि इवेंट लक्ष्य से इवेंट लिस्नर को हटाने की अनुमति देती है। यदि इवेंट प्रोसेस हो रहा हो तो इवेंट लिस्नर को हटाया जाता है, तो वह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा। Event Listeners को हटाए जाने के बाद कभी भी बुलाया नहीं जा सकता।

```java
public void RemoveEventListener(String type, IEventListener listener, bool useCapture)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| प्रकार | String | हटाए जा रहे इवेंट प्रकार को निर्दिष्ट करता है। |
| लिस्नर | IEventListener | पैरामीटर यह दर्शाता है कि क्या हटाया जाना है। |
| useCapture | Boolean | निर्दिष्ट करता है कि हटाए जा रहे EventListener को कैप्चरिंग लिस्नर के रूप में पंजीकृत किया गया था या नहीं। यदि कोई लिस्नर दो बार पंजीकृत किया गया था, एक कैप्चर के साथ और एक बिना, तो प्रत्येक को अलग‑अलग हटाना होगा। कैप्चरिंग लिस्नर को हटाने से उसी लिस्नर के गैर‑कैप्चरिंग संस्करण पर प्रभाव नहीं पड़ता, और इसके विपरीत भी यही सत्य है। |

### संबंधित देखें

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

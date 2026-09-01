---
title: "EventTarget.AddEventListener"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "EventTarget मेथड। EventTarget इंटरफ़ेस का addEventListener मेथड एक फ़ंक्शन सेट करता है जिसे तब कॉल किया जाएगा जब भी निर्दिष्ट इवेंट टार्गेट को डिलीवर किया जाएगा।"
type: docs

url: /hi/java/com.aspose.html.dom/eventtarget/addeventlistener/
---
## AddEventListener(String, DOMEventHandler, bool) {#addeventlistener}

addEventListener() मेथड [EventTarget ](T:com.aspose.html.dom.EventTarget) इंटरफ़ेस एक फ़ंक्शन सेट करता है जो तब बुलाया जाएगा जब निर्दिष्ट इवेंट लक्ष्य को पहुँचाया जाता है।

यह काम करता है एक फ़ंक्शन या एक ऑब्जेक्ट जो [EventListener](T:com.aspose.html.dom.events.IEventListener) को इम्प्लीमेंट करता है, को निर्दिष्ट इवेंट प्रकार के इवेंट लिस्नर्स की सूची में EventTarget पर जोड़कर, जिस पर इसे कॉल किया गया है। यदि फ़ंक्शन या ऑब्जेक्ट पहले से ही इस टार्गेट के इवेंट लिस्नर्स की सूची में मौजूद है, तो उन्हें दूसरी बार नहीं जोड़ा जाता।

```java
public void AddEventListener(String type, DOMEventHandler handler, bool useCapture)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| प्रकार | String | इवेंट प्रकार जिसके लिए उपयोगकर्ता पंजीकरण कर रहा है |
| हैंडलर | DOMEventHandler | इवेंट होने पर कॉल किए जाने के लिए एक लेता है। |
| useCapture | Boolean | यदि true है, तो useCapture दर्शाता है कि उपयोगकर्ता कैप्चर शुरू करना चाहता है। कैप्चर शुरू करने के बाद, निर्दिष्ट प्रकार के सभी इवेंट्स को पहले पंजीकृत ऑब्जेक्ट को डिस्पैच किया जाएगा, उसके बाद ट्री में उनके नीचे स्थित किसी भी Event Targets को। ट्री के माध्यम से ऊपर की ओर बबलिंग करने वाले इवेंट्स designated को कैप्चर उपयोग करने के लिए ट्रिगर नहीं करेंगे। |

## Remarks

यदि कोई is को an में जोड़ा जाता है जबकि वह इवेंट प्रोसेस कर रहा है, तो यह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा लेकिन इवेंट फ्लो के बाद के चरण, जैसे बबलिंग चरण में ट्रिगर हो सकता है। यदि समान पैरामीटरों के साथ एक ही ऑब्जेक्ट पर कई समान Event Listeners पंजीकृत किए गए हैं, तो डुप्लिकेट इंस्टेंसेज़ को त्याग दिया जाता है। वे दो बार कॉल नहीं होते और क्योंकि उन्हें त्याग दिया गया है, उन्हें मेथड के साथ हटाने की आवश्यकता नहीं है।

### संबंधित देखें

* delegate [DOMEventHandler](../../../com.aspose.html.dom.events/domeventhandler/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener) {#addeventlistener_1}

[`EventTarget `](../) इंटरफ़ेस का addEventListener() मेथड एक फ़ंक्शन सेट करता है जिसे तब कॉल किया जाएगा जब भी निर्दिष्ट इवेंट टार्गेट को डिलीवर किया जाएगा।

यह काम करता है एक फ़ंक्शन या एक ऑब्जेक्ट जो [`EventListener`](../../../com.aspose.html.dom.events/ieventlistener/) को इम्प्लीमेंट करता है, को निर्दिष्ट इवेंट प्रकार के इवेंट लिस्नर्स की सूची में EventTarget पर जोड़कर, जिस पर इसे कॉल किया गया है। यदि फ़ंक्शन या ऑब्जेक्ट पहले से ही इस टार्गेट के इवेंट लिस्नर्स की सूची में मौजूद है, तो उन्हें दूसरी बार नहीं जोड़ा जाता।

```java
public void AddEventListener(String type, IEventListener listener)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| प्रकार | String | इवेंट प्रकार जिसके लिए उपयोगकर्ता पंजीकरण कर रहा है |
| लिस्नर | IEventListener | उपयोगकर्ता द्वारा लागू किए गए इंटरफ़ेस को लेता है जिसमें इवेंट होने पर कॉल किए जाने वाले मेथड्स होते हैं। |

## Remarks

यदि कोई is को an में जोड़ा जाता है जबकि वह इवेंट प्रोसेस कर रहा है, तो यह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा लेकिन इवेंट फ्लो के बाद के चरण, जैसे बबलिंग चरण में ट्रिगर हो सकता है। यदि समान पैरामीटरों के साथ एक ही ऑब्जेक्ट पर कई समान Event Listeners पंजीकृत किए गए हैं, तो डुप्लिकेट इंस्टेंसेज़ को त्याग दिया जाता है। वे दो बार कॉल नहीं होते और क्योंकि उन्हें त्याग दिया गया है, उन्हें मेथड के साथ हटाने की आवश्यकता नहीं है।

### संबंधित देखें

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener, bool) {#addeventlistener_2}

addEventListener() मेथड [EventTarget ](T:com.aspose.html.dom.EventTarget) इंटरफ़ेस एक फ़ंक्शन सेट करता है जो तब बुलाया जाएगा जब निर्दिष्ट इवेंट लक्ष्य को पहुँचाया जाता है।

यह काम करता है एक फ़ंक्शन या एक ऑब्जेक्ट जो [EventListener](T:com.aspose.html.dom.events.IEventListener) को इम्प्लीमेंट करता है, को निर्दिष्ट इवेंट प्रकार के इवेंट लिस्नर्स की सूची में EventTarget पर जोड़कर, जिस पर इसे कॉल किया गया है। यदि फ़ंक्शन या ऑब्जेक्ट पहले से ही इस टार्गेट के इवेंट लिस्नर्स की सूची में मौजूद है, तो उन्हें दूसरी बार नहीं जोड़ा जाता।

```java
public void AddEventListener(String type, IEventListener listener, bool useCapture)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| प्रकार | String | इवेंट प्रकार जिसके लिए उपयोगकर्ता पंजीकरण कर रहा है |
| लिस्नर | IEventListener | उपयोगकर्ता द्वारा लागू किए गए इंटरफ़ेस को लेता है जिसमें इवेंट होने पर कॉल किए जाने वाले मेथड्स होते हैं। |
| useCapture | Boolean | यदि true है, तो useCapture दर्शाता है कि उपयोगकर्ता कैप्चर शुरू करना चाहता है। कैप्चर शुरू करने के बाद, निर्दिष्ट प्रकार के सभी इवेंट्स को पहले पंजीकृत ऑब्जेक्ट को डिस्पैच किया जाएगा, उसके बाद ट्री में उनके नीचे स्थित किसी भी Event Targets को। ट्री के माध्यम से ऊपर की ओर बबलिंग करने वाले इवेंट्स designated को कैप्चर उपयोग करने के लिए ट्रिगर नहीं करेंगे। |

## Remarks

यदि कोई is को an में जोड़ा जाता है जबकि वह इवेंट प्रोसेस कर रहा है, तो यह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा लेकिन इवेंट फ्लो के बाद के चरण, जैसे बबलिंग चरण में ट्रिगर हो सकता है। यदि समान पैरामीटरों के साथ एक ही ऑब्जेक्ट पर कई समान Event Listeners पंजीकृत किए गए हैं, तो डुप्लिकेट इंस्टेंसेज़ को त्याग दिया जाता है। वे दो बार कॉल नहीं होते और क्योंकि उन्हें त्याग दिया गया है, उन्हें मेथड के साथ हटाने की आवश्यकता नहीं है।

### संबंधित देखें

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

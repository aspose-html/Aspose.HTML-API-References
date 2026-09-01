---
title: "IEventTarget.AddEventListener"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "IEventTarget मेथड। EventTarget मेथड addEventListener एक फ़ंक्शन सेट करता है जो निर्दिष्ट इवेंट के लक्ष्य पर पहुँचने पर कॉल किया जाएगा।"
type: docs

url: /hi/java/com.aspose.html.dom.events/ieventtarget/addeventlistener/
---
## AddEventListener(String, IEventListener) {#addeventlistener}

EventTarget मेथड addEventListener() एक फ़ंक्शन सेट करता है जिसे तब बुलाया जाएगा जब भी निर्दिष्ट इवेंट लक्ष्य पर पहुँचाया जाता है।

सामान्य टार्गेट्स में Element, Document, और Window शामिल हैं, लेकिन टार्गेट कोई भी ऑब्जेक्ट हो सकता है जो इवेंट्स को सपोर्ट करता हो (जैसे XMLHttpRequest)।

```java
public void AddEventListener(String type, IEventListener listener)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| प्रकार | String | इवेंट प्रकार को सुनने के लिए केस‑सेंसिटिव स्ट्रिंग। |
| लिस्नर | IEventListener | उपयोगकर्ता द्वारा लागू किए गए इंटरफ़ेस को लेता है जिसमें इवेंट होने पर कॉल किए जाने वाले मेथड्स होते हैं। |

## Remarks

यदि कोई is को an में जोड़ा जाता है जबकि वह इवेंट प्रोसेस कर रहा है, तो यह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा लेकिन इवेंट फ्लो के बाद के चरण, जैसे बबलिंग चरण में ट्रिगर हो सकता है। यदि समान पैरामीटरों के साथ एक ही ऑब्जेक्ट पर कई समान Event Listeners पंजीकृत किए गए हैं, तो डुप्लिकेट इंस्टेंसेज़ को त्याग दिया जाता है। वे दो बार कॉल नहीं होते और क्योंकि उन्हें त्याग दिया गया है, उन्हें मेथड के साथ हटाने की आवश्यकता नहीं है।

### संबंधित देखें

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener, bool) {#addeventlistener_1}

EventTarget मेथड addEventListener() एक फ़ंक्शन सेट करता है जिसे तब बुलाया जाएगा जब भी निर्दिष्ट इवेंट लक्ष्य पर पहुँचाया जाता है।

सामान्य टार्गेट्स में Element, Document, और Window शामिल हैं, लेकिन टार्गेट कोई भी ऑब्जेक्ट हो सकता है जो इवेंट्स को सपोर्ट करता हो (जैसे XMLHttpRequest)।

```java
public void AddEventListener(String type, IEventListener listener, bool useCapture)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| प्रकार | String | इवेंट प्रकार को सुनने के लिए केस‑सेंसिटिव स्ट्रिंग। |
| लिस्नर | IEventListener | उपयोगकर्ता द्वारा लागू किए गए इंटरफ़ेस को लेता है जिसमें इवेंट होने पर कॉल किए जाने वाले मेथड्स होते हैं। |
| useCapture | Boolean | यदि true है, तो useCapture दर्शाता है कि उपयोगकर्ता कैप्चर शुरू करना चाहता है। कैप्चर शुरू करने के बाद, निर्दिष्ट प्रकार के सभी इवेंट्स को पहले पंजीकृत ऑब्जेक्ट को डिस्पैच किया जाएगा, उसके बाद ट्री में उनके नीचे स्थित किसी भी Event Targets को। ट्री के माध्यम से ऊपर की ओर बबलिंग करने वाले इवेंट्स designated को कैप्चर उपयोग करने के लिए ट्रिगर नहीं करेंगे। |

## Remarks

यदि कोई is को an में जोड़ा जाता है जबकि वह इवेंट प्रोसेस कर रहा है, तो यह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा लेकिन इवेंट फ्लो के बाद के चरण, जैसे बबलिंग चरण में ट्रिगर हो सकता है। यदि समान पैरामीटरों के साथ एक ही ऑब्जेक्ट पर कई समान Event Listeners पंजीकृत किए गए हैं, तो डुप्लिकेट इंस्टेंसेज़ को त्याग दिया जाता है। वे दो बार कॉल नहीं होते और क्योंकि उन्हें त्याग दिया गया है, उन्हें मेथड के साथ हटाने की आवश्यकता नहीं है।

### संबंधित देखें

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)

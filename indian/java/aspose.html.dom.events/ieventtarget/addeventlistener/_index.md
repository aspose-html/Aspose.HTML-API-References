---
title: "IEventTarget.AddEventListener"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "IEventTarget मेथड। EventTarget मेथड addEventListener एक फ़ंक्शन सेट करता है जिसे तब बुलाया जाएगा जब निर्दिष्ट इवेंट टार्गेट को डिलीवर किया जाएगा।"
type: docs

url: /hi/java/com.aspose.html.dom.events/ieventtarget/addeventlistener/
---
## AddEventListener(String, IEventListener) {#addeventlistener}

EventTarget मेथड addEventListener() एक फ़ंक्शन सेट करता है जो निर्दिष्ट इवेंट लक्ष्य पर पहुँचने पर कॉल किया जाएगा।

सामान्य टार्गेट्स में Element, Document, और Window शामिल हैं, लेकिन टार्गेट कोई भी ऑब्जेक्ट हो सकता है जो इवेंट्स को सपोर्ट करता हो (जैसे XMLHttpRequest)।

```java
public void AddEventListener(String type, IEventListener listener)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| प्रकार | String | एक केस‑सेंसिटिव स्ट्रिंग जो सुनने के लिए इवेंट प्रकार को दर्शाती है। |
| लिस्नर | IEventListener | एक इंटरफ़ेस लेता है जिसे उपयोगकर्ता ने लागू किया है, जिसमें वे मेथड्स होते हैं जो इवेंट होने पर कॉल किए जाएंगे। |

## टिप्पणियाँ

यदि किसी इवेंट को प्रोसेस करते समय किसी लिस्नर को जोड़ा जाता है, तो वह वर्तमान कार्रवाई द्वारा ट्रिगर नहीं होगा लेकिन इवेंट फ्लो के बाद के चरण में, जैसे बबलिंग चरण में ट्रिगर हो सकता है। यदि समान पैरामीटरों के साथ एक ही ऑब्जेक्ट पर कई समान Event Listeners पंजीकृत किए गए हैं, तो डुप्लिकेट इंस्टेंस को त्याग दिया जाता है। वे दो बार कॉल नहीं होते और क्योंकि उन्हें त्याग दिया गया है, उन्हें मेथड के साथ हटाने की आवश्यकता नहीं होती।

### संबंधित देखें

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener, bool) {#addeventlistener_1}

EventTarget मेथड addEventListener() एक फ़ंक्शन सेट करता है जो निर्दिष्ट इवेंट लक्ष्य पर पहुँचने पर कॉल किया जाएगा।

सामान्य टार्गेट्स में Element, Document, और Window शामिल हैं, लेकिन टार्गेट कोई भी ऑब्जेक्ट हो सकता है जो इवेंट्स को सपोर्ट करता हो (जैसे XMLHttpRequest)।

```java
public void AddEventListener(String type, IEventListener listener, bool useCapture)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| प्रकार | String | एक केस‑सेंसिटिव स्ट्रिंग जो सुनने के लिए इवेंट प्रकार को दर्शाती है। |
| लिस्नर | IEventListener | एक इंटरफ़ेस लेता है जिसे उपयोगकर्ता ने लागू किया है, जिसमें वे मेथड्स होते हैं जो इवेंट होने पर कॉल किए जाएंगे। |
| useCapture | Boolean | यदि true है, तो useCapture संकेत देता है कि उपयोगकर्ता कैप्चर शुरू करना चाहता है। कैप्चर शुरू करने के बाद, निर्दिष्ट प्रकार के सभी इवेंट्स पहले पंजीकृत लिस्नर्स को डिस्पैच किए जाएंगे, फिर ट्री में उनके नीचे स्थित किसी भी Event Targets को। ट्री में ऊपर की ओर बबलिंग करने वाले इवेंट्स designated को कैप्चर उपयोग करने के लिए ट्रिगर नहीं करेंगे। |

## टिप्पणियाँ

यदि किसी इवेंट को प्रोसेस करते समय किसी लिस्नर को जोड़ा जाता है, तो वह वर्तमान कार्रवाई द्वारा ट्रिगर नहीं होगा लेकिन इवेंट फ्लो के बाद के चरण में, जैसे बबलिंग चरण में ट्रिगर हो सकता है। यदि समान पैरामीटरों के साथ एक ही ऑब्जेक्ट पर कई समान Event Listeners पंजीकृत किए गए हैं, तो डुप्लिकेट इंस्टेंस को त्याग दिया जाता है। वे दो बार कॉल नहीं होते और क्योंकि उन्हें त्याग दिया गया है, उन्हें मेथड के साथ हटाने की आवश्यकता नहीं होती।

### संबंधित देखें

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)

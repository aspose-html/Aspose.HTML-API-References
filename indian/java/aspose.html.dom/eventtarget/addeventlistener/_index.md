---
title: "EventTarget.AddEventListener"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "EventTarget मेथड। EventTarget इंटरफ़ेस की addEventListener मेथड एक फ़ंक्शन सेट करती है जो निर्दिष्ट इवेंट टार्गेट पर पहुँचने पर कॉल किया जाएगा।"
type: docs

url: /hi/java/com.aspose.html.dom/eventtarget/addeventlistener/
---
## AddEventListener(String, DOMEventHandler, bool) {#addeventlistener}

addEventListener() मेथड [EventTarget ](T:com.aspose.html.dom.EventTarget) इंटरफ़ेस का यह सेट करता है कि एक फ़ंक्शन को कॉल किया जाए जब भी निर्दिष्ट इवेंट लक्ष्य तक पहुँचाया जाता है।

यह काम करता है फ़ंक्शन या ऐसे ऑब्जेक्ट को जोड़कर जो [EventListener](T:com.aspose.html.dom.events.IEventListener) को इम्प्लीमेंट करता है, निर्दिष्ट इवेंट प्रकार के इवेंट लिस्नर्स की सूची में, उस EventTarget पर जिस पर इसे कॉल किया गया है। यदि फ़ंक्शन या ऑब्जेक्ट पहले से ही इस टार्गेट की इवेंट लिस्नर्स सूची में मौजूद है, तो उन्हें दूसरी बार नहीं जोड़ा जाता।

```java
public void AddEventListener(String type, DOMEventHandler handler, bool useCapture)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| प्रकार | String | इवेंट प्रकार जिसके लिए उपयोगकर्ता पंजीकरण कर रहा है |
| हैंडलर | DOMEventHandler | इवेंट के होने पर कॉल किया जाने वाला एक फ़ंक्शन लेता है। |
| useCapture | Boolean | यदि true है, तो useCapture संकेत देता है कि उपयोगकर्ता कैप्चर शुरू करना चाहता है। कैप्चर शुरू करने के बाद, निर्दिष्ट प्रकार के सभी इवेंट्स पहले पंजीकृत लिस्नर्स को डिस्पैच किए जाएंगे, फिर ट्री में उनके नीचे स्थित किसी भी Event Targets को। ट्री में ऊपर की ओर बबलिंग करने वाले इवेंट्स designated को कैप्चर उपयोग करने के लिए ट्रिगर नहीं करेंगे। |

## टिप्पणियाँ

यदि किसी इवेंट को प्रोसेस करते समय किसी लिस्नर को जोड़ा जाता है, तो वह वर्तमान कार्रवाई द्वारा ट्रिगर नहीं होगा लेकिन इवेंट फ्लो के बाद के चरण में, जैसे बबलिंग चरण में ट्रिगर हो सकता है। यदि समान पैरामीटरों के साथ एक ही ऑब्जेक्ट पर कई समान Event Listeners पंजीकृत किए गए हैं, तो डुप्लिकेट इंस्टेंस को त्याग दिया जाता है। वे दो बार कॉल नहीं होते और क्योंकि उन्हें त्याग दिया गया है, उन्हें मेथड के साथ हटाने की आवश्यकता नहीं होती।

### संबंधित देखें

* delegate [DOMEventHandler](../../../com.aspose.html.dom.events/domeventhandler/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener) {#addeventlistener_1}

[`EventTarget `](../) इंटरफ़ेस की addEventListener() मेथड एक फ़ंक्शन सेट करती है जो निर्दिष्ट इवेंट टार्गेट पर पहुँचने पर कॉल किया जाएगा।

यह काम करता है फ़ंक्शन या ऐसे ऑब्जेक्ट को जोड़कर जो [`EventListener`](../../../com.aspose.html.dom.events/ieventlistener/) को इम्प्लीमेंट करता है, निर्दिष्ट इवेंट प्रकार के इवेंट लिस्नर्स की सूची में, उस EventTarget पर जिस पर इसे कॉल किया गया है। यदि फ़ंक्शन या ऑब्जेक्ट पहले से ही इस टार्गेट की इवेंट लिस्नर्स सूची में मौजूद है, तो उन्हें दूसरी बार नहीं जोड़ा जाता।

```java
public void AddEventListener(String type, IEventListener listener)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| प्रकार | String | इवेंट प्रकार जिसके लिए उपयोगकर्ता पंजीकरण कर रहा है |
| लिस्नर | IEventListener | एक इंटरफ़ेस लेता है जिसे उपयोगकर्ता ने लागू किया है, जिसमें वे मेथड्स होते हैं जो इवेंट होने पर कॉल किए जाएंगे। |

## टिप्पणियाँ

यदि किसी इवेंट को प्रोसेस करते समय किसी लिस्नर को जोड़ा जाता है, तो वह वर्तमान कार्रवाई द्वारा ट्रिगर नहीं होगा लेकिन इवेंट फ्लो के बाद के चरण में, जैसे बबलिंग चरण में ट्रिगर हो सकता है। यदि समान पैरामीटरों के साथ एक ही ऑब्जेक्ट पर कई समान Event Listeners पंजीकृत किए गए हैं, तो डुप्लिकेट इंस्टेंस को त्याग दिया जाता है। वे दो बार कॉल नहीं होते और क्योंकि उन्हें त्याग दिया गया है, उन्हें मेथड के साथ हटाने की आवश्यकता नहीं होती।

### संबंधित देखें

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener, bool) {#addeventlistener_2}

addEventListener() मेथड [EventTarget ](T:com.aspose.html.dom.EventTarget) इंटरफ़ेस का यह सेट करता है कि एक फ़ंक्शन को कॉल किया जाए जब भी निर्दिष्ट इवेंट लक्ष्य तक पहुँचाया जाता है।

यह काम करता है फ़ंक्शन या ऐसे ऑब्जेक्ट को जोड़कर जो [EventListener](T:com.aspose.html.dom.events.IEventListener) को इम्प्लीमेंट करता है, निर्दिष्ट इवेंट प्रकार के इवेंट लिस्नर्स की सूची में, उस EventTarget पर जिस पर इसे कॉल किया गया है। यदि फ़ंक्शन या ऑब्जेक्ट पहले से ही इस टार्गेट की इवेंट लिस्नर्स सूची में मौजूद है, तो उन्हें दूसरी बार नहीं जोड़ा जाता।

```java
public void AddEventListener(String type, IEventListener listener, bool useCapture)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| प्रकार | String | इवेंट प्रकार जिसके लिए उपयोगकर्ता पंजीकरण कर रहा है |
| लिस्नर | IEventListener | एक इंटरफ़ेस लेता है जिसे उपयोगकर्ता ने लागू किया है, जिसमें वे मेथड्स होते हैं जो इवेंट होने पर कॉल किए जाएंगे। |
| useCapture | Boolean | यदि true है, तो useCapture संकेत देता है कि उपयोगकर्ता कैप्चर शुरू करना चाहता है। कैप्चर शुरू करने के बाद, निर्दिष्ट प्रकार के सभी इवेंट्स पहले पंजीकृत लिस्नर्स को डिस्पैच किए जाएंगे, फिर ट्री में उनके नीचे स्थित किसी भी Event Targets को। ट्री में ऊपर की ओर बबलिंग करने वाले इवेंट्स designated को कैप्चर उपयोग करने के लिए ट्रिगर नहीं करेंगे। |

## टिप्पणियाँ

यदि किसी इवेंट को प्रोसेस करते समय किसी लिस्नर को जोड़ा जाता है, तो वह वर्तमान कार्रवाई द्वारा ट्रिगर नहीं होगा लेकिन इवेंट फ्लो के बाद के चरण में, जैसे बबलिंग चरण में ट्रिगर हो सकता है। यदि समान पैरामीटरों के साथ एक ही ऑब्जेक्ट पर कई समान Event Listeners पंजीकृत किए गए हैं, तो डुप्लिकेट इंस्टेंस को त्याग दिया जाता है। वे दो बार कॉल नहीं होते और क्योंकि उन्हें त्याग दिया गया है, उन्हें मेथड के साथ हटाने की आवश्यकता नहीं होती।

### संबंधित देखें

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

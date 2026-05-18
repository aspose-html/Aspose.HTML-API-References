---
title: "EventTarget क्लास"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.dom.EventTarget क्लास। EventTarget इंटरफ़ेस उन वस्तुओं द्वारा लागू किया जाता है जो इवेंट प्राप्त कर सकती हैं और उनके लिए लिस्नर हो सकते हैं। दूसरे शब्दों में, इवेंट के किसी भी लक्ष्य में इस इंटरफ़ेस से जुड़े तीन मेथड लागू होते हैं।"
type: docs

url: /hi/java/com.aspose.html.dom/eventtarget/
---
## EventTarget class

EventTarget इंटरफ़ेस उन वस्तुओं द्वारा लागू किया जाता है जो घटनाएँ प्राप्त कर सकती हैं और उनके लिए लिस्नर रख सकती हैं। दूसरे शब्दों में, घटनाओं का कोई भी लक्ष्य इस इंटरफ़ेस से जुड़े तीन मेथड्स को लागू करता है।

[`Element`](../element/), and its children, as well as [`Document`](../document/) and Window, are the most common event targets, but other objects can be event targets, too.

```java
public class EventTarget : DOMObject, IDisposable, IEventTarget
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [EventTarget](eventtarget/)() | EventTarget वस्तु का एक नया उदाहरण आरंभ करता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_1)(String, IEventListener) | `addEventListener()` मेथड `EventTarget `इंटरफ़ेस का वह फ़ंक्शन सेट करता है जो निर्दिष्ट इवेंट लक्ष्य को पहुँचाए जाने पर कॉल किया जाएगा। |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/#addeventlistener)(String, DOMEventHandler, bool) | addEventListener() मेथड [EventTarget ](T:com.aspose.html.dom.EventTarget) इंटरफ़ेस का यह सेट करता है कि एक फ़ंक्शन को कॉल किया जाए जब भी निर्दिष्ट इवेंट लक्ष्य तक पहुँचाया जाता है। |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_2)(String, IEventListener, bool) | addEventListener() मेथड [EventTarget ](T:com.aspose.html.dom.EventTarget) इंटरफ़ेस का यह सेट करता है कि एक फ़ंक्शन को कॉल किया जाए जब भी निर्दिष्ट इवेंट लक्ष्य तक पहुँचाया जाता है। |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | निर्दिष्ट [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) पर एक इवेंट डिस्पैच करता है, (सिंक्रोनस रूप से) प्रभावित EventListeners को उचित क्रम में बुलाता है। सामान्य इवेंट प्रोसेसिंग नियम (कैप्चरिंग और वैकल्पिक बबलिंग चरण सहित) उन इवेंट्स पर भी लागू होते हैं जिन्हें मैन्युअली [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) से डिस्पैच किया जाता है। |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | ऐप्लिकेशन-परिभाषित कार्यों को निष्पादित करता है जो अनमैनेज्ड संसाधनों को मुक्त करने, रिलीज़ करने या रीसेट करने से संबंधित होते हैं। |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | यह मेथड ECMAScript ऑब्जेक्ट को पुनः प्राप्त करने के लिए उपयोग किया जाता है। |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_1)(String, IEventListener) | यह मेथड इवेंट टार्गेट से इवेंट लिस्नर्स को हटाने की अनुमति देता है। यदि कोई इवेंट लिस्नर इवेंट प्रोसेस हो रहा हो तो उसे हटाया जाता है, तो वह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा। हटाए जाने के बाद इवेंट लिस्नर्स कभी भी कॉल नहीं किए जा सकते। |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener)(String, DOMEventHandler, bool) | यह मेथड इवेंट टार्गेट से इवेंट लिस्नर्स को हटाने की अनुमति देता है। यदि कोई इवेंट लिस्नर इवेंट प्रोसेस हो रहा हो तो उसे हटाया जाता है, तो वह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा। हटाए जाने के बाद इवेंट लिस्नर्स कभी भी कॉल नहीं किए जा सकते। |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_2)(String, IEventListener, bool) | यह मेथड इवेंट टार्गेट से इवेंट लिस्नर्स को हटाने की अनुमति देता है। यदि कोई इवेंट लिस्नर इवेंट प्रोसेस हो रहा हो तो उसे हटाया जाता है, तो वह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा। हटाए जाने के बाद इवेंट लिस्नर्स कभी भी कॉल नहीं किए जा सकते। |

### संबंधित देखें

* class [DOMObject](../domobject/)
* interface [IEventTarget](../../com.aspose.html.dom.events/ieventtarget/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)

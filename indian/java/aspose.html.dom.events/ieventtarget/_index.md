---
title: "IEventTarget इंटरफ़ेस"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.dom.events.IEventTarget इंटरफ़ेस। EventTarget इंटरफ़ेस सभी नोड्स द्वारा लागू किया जाता है उन कार्यान्वयनों में जो DOM इवेंट मॉडल का समर्थन करते हैं। इसलिए इस इंटरफ़ेस को Node इंटरफ़ेस के एक उदाहरण पर बाइंडिंग-विशिष्ट कास्टिंग विधियों का उपयोग करके प्राप्त किया जा सकता है। यह इंटरफ़ेस Event Listeners को पंजीकृत और हटाने तथा उन पर इवेंट्स को डिस्पैच करने की अनुमति देता है।"
type: docs

url: /hi/java/com.aspose.html.dom.events/ieventtarget/
---
## IEventTarget interface

EventTarget इंटरफ़ेस उन सभी नोड्स द्वारा लागू किया जाता है जो DOM इवेंट मॉडल का समर्थन करने वाले कार्यान्वयन में होते हैं। इसलिए, इस इंटरफ़ेस को Node इंटरफ़ेस के एक इंस्टेंस पर बाइंडिंग-विशिष्ट कास्टिंग विधियों का उपयोग करके प्राप्त किया जा सकता है। यह इंटरफ़ेस इवेंट लिस्नर्स की पंजीकरण और हटाने तथा उन पर इवेंट्स को डिस्पैच करने की अनुमति देता है।

```java
public interface IEventTarget
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener)(String, IEventListener) | EventTarget मेथड addEventListener() एक फ़ंक्शन सेट करता है जिसे तब बुलाया जाएगा जब भी निर्दिष्ट इवेंट लक्ष्य पर पहुँचाया जाता है। |
| [addEventListener](../../com.aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(String, IEventListener, bool) | EventTarget मेथड addEventListener() एक फ़ंक्शन सेट करता है जिसे तब बुलाया जाएगा जब भी निर्दिष्ट इवेंट लक्ष्य पर पहुँचाया जाता है। |
| [dispatchEvent](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/)(Event) | निर्दिष्ट EventTarget पर एक इवेंट डिस्पैच करता है, (सिंक्रोनस रूप से) प्रभावित EventListeners को उचित क्रम में बुलाता है। सामान्य इवेंट प्रोसेसिंग नियम (कैप्चरिंग और वैकल्पिक बबलिंग चरण सहित) भी उन इवेंट्स पर लागू होते हैं जो dispatchEvent() के साथ मैन्युअल रूप से डिस्पैच किए जाते हैं। |
| [removeEventListener](../../com.aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(String, IEventListener) | यह विधि इवेंट लक्ष्य से इवेंट लिस्नर को हटाने की अनुमति देती है। यदि इवेंट प्रोसेस हो रहा हो तो इवेंट लिस्नर को हटाया जाता है, तो वह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा। Event Listeners को हटाए जाने के बाद कभी भी बुलाया नहीं जा सकता। |
| [removeEventListener](../../com.aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(String, IEventListener, bool) | यह विधि इवेंट लक्ष्य से इवेंट लिस्नर को हटाने की अनुमति देती है। यदि इवेंट प्रोसेस हो रहा हो तो इवेंट लिस्नर को हटाया जाता है, तो वह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा। Event Listeners को हटाए जाने के बाद कभी भी बुलाया नहीं जा सकता। |

### संबंधित देखें

* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)

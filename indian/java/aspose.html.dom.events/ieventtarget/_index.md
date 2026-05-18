---
title: "IEventTarget इंटरफ़ेस"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.dom.events.IEventTarget इंटरफ़ेस। EventTarget इंटरफ़ेस को उन सभी नोड्स द्वारा लागू किया जाता है जो DOM इवेंट मॉडल को समर्थन देने वाले कार्यान्वयन में होते हैं। इसलिए इस इंटरफ़ेस को Node इंटरफ़ेस के किसी उदाहरण पर बाइंडिंग-विशिष्ट कास्टिंग विधियों का उपयोग करके प्राप्त किया जा सकता है। यह इंटरफ़ेस Event Listeners की पंजीकरण और हटाने तथा उन पर इवेंट्स को डिस्पैच करने की अनुमति देता है।"
type: docs

url: /hi/java/com.aspose.html.dom.events/ieventtarget/
---
## IEventTarget interface

EventTarget इंटरफ़ेस उन सभी नोड्स द्वारा लागू किया जाता है जो DOM इवेंट मॉडल का समर्थन करने वाले कार्यान्वयन में होते हैं। इसलिए, इस इंटरफ़ेस को Node इंटरफ़ेस के एक इंस्टेंस पर बाइंडिंग-विशिष्ट कास्टिंग विधियों का उपयोग करके प्राप्त किया जा सकता है। यह इंटरफ़ेस इवेंट लिस्नर्स की पंजीकरण और हटाने तथा इवेंट्स को उस पर डिस्पैच करने की अनुमति देता है।

```java
public interface IEventTarget
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener)(String, IEventListener) | EventTarget मेथड addEventListener() एक फ़ंक्शन सेट करता है जो निर्दिष्ट इवेंट लक्ष्य पर पहुँचने पर कॉल किया जाएगा। |
| [addEventListener](../../com.aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(String, IEventListener, bool) | EventTarget मेथड addEventListener() एक फ़ंक्शन सेट करता है जो निर्दिष्ट इवेंट लक्ष्य पर पहुँचने पर कॉल किया जाएगा। |
| [dispatchEvent](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/)(Event) | निर्दिष्ट EventTarget पर एक इवेंट डिस्पैच करता है, (सिंक्रोनस रूप से) प्रभावित EventListeners को उचित क्रम में बुलाता है। सामान्य इवेंट प्रोसेसिंग नियम (कैप्चरिंग और वैकल्पिक बबलींग चरण सहित) उन इवेंट्स पर भी लागू होते हैं जिन्हें dispatchEvent() के साथ मैन्युअली डिस्पैच किया जाता है। |
| [removeEventListener](../../com.aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(String, IEventListener) | यह मेथड इवेंट टार्गेट से इवेंट लिस्नर्स को हटाने की अनुमति देता है। यदि कोई इवेंट लिस्नर इवेंट प्रोसेस हो रहा हो तो उसे हटाया जाता है, तो वह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा। हटाए जाने के बाद इवेंट लिस्नर्स कभी भी कॉल नहीं किए जा सकते। |
| [removeEventListener](../../com.aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(String, IEventListener, bool) | यह मेथड इवेंट टार्गेट से इवेंट लिस्नर्स को हटाने की अनुमति देता है। यदि कोई इवेंट लिस्नर इवेंट प्रोसेस हो रहा हो तो उसे हटाया जाता है, तो वह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा। हटाए जाने के बाद इवेंट लिस्नर्स कभी भी कॉल नहीं किए जा सकते। |

### संबंधित देखें

* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)

---
title: "EventTarget.DispatchEvent"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "EventTarget मेथड। निर्दिष्ट EventTarget पर इवेंट को सिंक्रोनस रूप से डिस्पैच करता है, जिससे प्रभावित इवेंट लिस्नर्स उचित क्रम में बुलाए जाते हैं। सामान्य इवेंट प्रोसेसिंग नियम, जिसमें कैप्चरिंग और वैकल्पिक बबलिंग फेज़ शामिल हैं, मैन्युअली dispatchEvent के साथ डिस्पैच किए गए इवेंट्स पर भी लागू होते हैं।"
type: docs

url: /hi/java/com.aspose.html.dom/eventtarget/dispatchevent/
---
## EventTarget.DispatchEvent method

निर्दिष्ट [`EventTarget`](../../../com.aspose.html.dom.events/ieventtarget/) पर एक इवेंट को (सिंक्रोनस रूप से) डिस्पैच करता है, जिससे प्रभावित इवेंट लिस्नर्स उचित क्रम में बुलाए जाते हैं। सामान्य इवेंट प्रोसेसिंग नियम (जिसमें कैप्चरिंग और वैकल्पिक बबलिंग फेज़ शामिल हैं) मैन्युअली [`dispatchEvent()`](../../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) के साथ डिस्पैच किए गए इवेंट्स पर भी लागू होते हैं।

```java
public bool DispatchEvent(Event @event)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| इवेंट | इवेंट | इवेंट प्रकार, व्यवहार, और प्रसंस्करण के दौरान उपयोग की जाने वाली संदर्भात्मक जानकारी निर्दिष्ट करता है। |

### रिटर्न वैल्यू

रिटर्न वैल्यू यह दर्शाता है कि इवेंट को संभालने वाले किसी भी लिस्नर ने कॉल किया या नहीं। यदि कॉल किया गया तो मान false होता है, अन्यथा मान true होता है।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [dOMException](../../domexception/) |  |

## Remarks

इस प्रकार डिस्पैच किए गए इवेंट्स में वही कैप्चरिंग और बबलिंग व्यवहार होगा जैसा कि इम्प्लीमेंटेशन द्वारा सीधे डिस्पैच किए गए इवेंट्स में होता है। इवेंट का लक्ष्य वह on है जिस पर इसे कॉल किया जाता है।

### संबंधित देखें

* class [Event](../../../com.aspose.html.dom.events/event/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

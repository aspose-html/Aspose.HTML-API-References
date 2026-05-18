---
title: "EventTarget.DispatchEvent"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "EventTarget मेथड। निर्दिष्ट EventTarget पर इवेंट को सिंक्रोनस रूप से डिस्पैच करता है, जिससे प्रभावित EventListeners उचित क्रम में कॉल होते हैं। सामान्य इवेंट प्रोसेसिंग नियम, जिसमें कैप्चरिंग और वैकल्पिक बबलिंग फेज़ शामिल हैं, मैन्युअली dispatchEvent के साथ डिस्पैच किए गए इवेंट्स पर भी लागू होते हैं।"
type: docs

url: /hi/java/com.aspose.html.dom/eventtarget/dispatchevent/
---
## EventTarget.DispatchEvent method

निर्दिष्ट [`EventTarget`](../../../com.aspose.html.dom.events/ieventtarget/) पर एक इवेंट डिस्पैच करता है, (सिंक्रोनस रूप से) जिससे प्रभावित EventListeners उचित क्रम में कॉल होते हैं। सामान्य इवेंट प्रोसेसिंग नियम (जिसमें कैप्चरिंग और वैकल्पिक बबलिंग फेज़ शामिल हैं) मैन्युअली [`dispatchEvent()`](../../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) के साथ डिस्पैच किए गए इवेंट्स पर भी लागू होते हैं।

```java
public bool DispatchEvent(Event @event)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| इवेंट | इवेंट | इवेंट प्रकार, व्यवहार, और प्रसंग संबंधी जानकारी को निर्दिष्ट करता है जो इवेंट प्रोसेसिंग में उपयोग की जाएगी। |

### रिटर्न वैल्यू

रिटर्न वैल्यू यह दर्शाती है कि इवेंट को संभालने वाले किसी भी लिस्नर ने कॉल किया या नहीं। यदि कॉल किया गया तो मान false होता है, अन्यथा मान true होता है।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [dOMException](../../domexception/) |  |

## टिप्पणियाँ

इस प्रकार डिस्पैच किए गए इवेंट्स में वही कैप्चरिंग और बबलिंग व्यवहार होगा जैसा कि इम्प्लीमेंटेशन द्वारा सीधे डिस्पैच किए गए इवेंट्स में होता है। इवेंट का टार्गेट वह ऑब्जेक्ट है जिस पर इसे कॉल किया जाता है।

### संबंधित देखें

* class [Event](../../../com.aspose.html.dom.events/event/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---
title: "IDocumentEvent.CreateEvent"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "IDocumentEvent मेथड। createEvent मेथड का उपयोग तब इवेंट्स बनाने के लिए किया जाता है जब उपयोगकर्ता के लिए स्वयं इवेंट बनाना असुविधाजनक या अनावश्यक हो।"
type: docs

url: /hi/java/com.aspose.html.dom.events/idocumentevent/createevent/
---
## IDocumentEvent.CreateEvent method

createEvent मेथड का उपयोग तब इवेंट बनाने के लिए किया जाता है जब उपयोगकर्ता के लिए स्वयं इवेंट बनाना असुविधाजनक या अनावश्यक हो।

```java
public Event CreateEvent(String eventType)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| eventType | String | eventType पैरामीटर यह निर्दिष्ट करता है कि किस प्रकार का interface बनाया जाना है। यदि निर्दिष्ट interface इम्प्लीमेंटेशन द्वारा समर्थित है, तो यह मेथड अनुरोधित interface प्रकार का नया ऑब्जेक्ट लौटाएगा। यदि इसे मेथड के माध्यम से डिस्पैच किया जाना है, तो निर्माण के बाद उपयुक्त मेथड को कॉल करके मानों को इनिशियलाइज़ करना आवश्यक है। यह मेथड उन मामलों में s बनाने के लिए उपयोग किया जाता है जब उपयोगकर्ता के लिए स्वयं उन्हें बनाना असुविधाजनक या अनावश्यक हो। उन स्थितियों में जहाँ प्रदान किया गया इम्प्लीमेंटेशन अपर्याप्त है, उपयोगकर्ता अपने स्वयं के इम्प्लीमेंटेशन प्रदान कर सकते हैं ताकि इस मेथड के साथ उपयोग किया जा सके। |

### रिटर्न वैल्यू

निर्धारित इवेंट प्रकार के नए बनाए गए इवेंट को लौटाता है।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: यदि इम्प्लीमेंटेशन अनुरोधित interface प्रकार को सपोर्ट नहीं करता तो यह त्रुटि उठती है। |

### संबंधित देखें

* class [Event](../../event/)
* interface [IDocumentEvent](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)

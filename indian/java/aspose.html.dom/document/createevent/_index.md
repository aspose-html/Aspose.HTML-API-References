---
title: "Document.CreateEvent"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "Document मेथड। कार्यान्वयन द्वारा समर्थित प्रकार का एक इवेंट बनाता है"
type: docs

url: /hi/java/com.aspose.html.dom/document/createevent/
---
## Document.CreateEvent method

एक [`Event`](../../../com.aspose.html.dom.events/event/) बनाता है जो कार्यान्वयन द्वारा समर्थित प्रकार का है।

```java
public Event CreateEvent(String eventType)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| eventType | String | eventType पैरामीटर उस [`Event`](../../../com.aspose.html.dom.events/event/) इंटरफ़ेस के प्रकार को निर्दिष्ट करता है जिसे बनाया जाना है। यदि निर्दिष्ट किया गया [`Event`](../../../com.aspose.html.dom.events/event/) इंटरफ़ेस कार्यान्वयन द्वारा समर्थित है, तो यह मेथड अनुरोधित इंटरफ़ेस प्रकार का नया [`Event`](../../../com.aspose.html.dom.events/event/) लौटाएगा। यदि [`Event`](../../../com.aspose.html.dom.events/event/) को [`DispatchEvent`](../../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) मेथड के माध्यम से डिस्पैच किया जाना है, तो निर्माण के बाद उपयुक्त [`InitEvent`](../../../com.aspose.html.dom.events/event/initevent/) मेथड को कॉल करना आवश्यक है ताकि [`Event`](../../../com.aspose.html.dom.events/event/) के मानों को प्रारंभ किया जा सके। |

### रिटर्न वैल्यू

नया बनाया गया [`Event`](../../../com.aspose.html.dom.events/event/)

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: यदि कार्यान्वयन अनुरोधित [`Event`](../../../com.aspose.html.dom.events/event/) इंटरफ़ेस प्रकार का समर्थन नहीं करता है तो उत्पन्न होता है |

### संबंधित देखें

* class [Event](../../../com.aspose.html.dom.events/event/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

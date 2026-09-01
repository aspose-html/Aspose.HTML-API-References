---
title: "SVGSVGElement.CreateEvent"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "SVGSVGElement विधि। कार्यान्वयन द्वारा समर्थित प्रकार का एक इवेंट बनाती है।"
type: docs

url: /hi/java/com.aspose.html.dom.svg/svgsvgelement/createevent/
---
## SVGSVGElement.CreateEvent method

कार्यान्वयन द्वारा समर्थित प्रकार का एक [`Event`](../../../com.aspose.html.dom.events/event/) बनाती है।

```java
public Event CreateEvent(String eventType)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| eventType | String | eventType पैरामीटर यह निर्दिष्ट करता है कि किस प्रकार का [`Event`](../../../com.aspose.html.dom.events/event/) इंटरफ़ेस बनाया जाना है। यदि निर्दिष्ट किया गया [`Event`](../../../com.aspose.html.dom.events/event/) इंटरफ़ेस कार्यान्वयन द्वारा समर्थित है तो यह मेथड अनुरोधित इंटरफ़ेस प्रकार का नया [`Event`](../../../com.aspose.html.dom.events/event/) लौटाएगा। यदि [`Event`](../../../com.aspose.html.dom.events/event/) को [`DispatchEvent`](../../../com.aspose.html.dom/eventtarget/dispatchevent/) मेथड के माध्यम से डिस्पैच किया जाना है तो निर्माण के बाद उपयुक्त [`InitEvent`](../../../com.aspose.html.dom.events/event/initevent/) मेथड को कॉल करना आवश्यक है ताकि [`Event`](../../../com.aspose.html.dom.events/event/) के मानों को प्रारंभ किया जा सके। |

### रिटर्न वैल्यू

नया बनाया गया [`Event`](../../../com.aspose.html.dom.events/event/)

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: यदि कार्यान्वयन अनुरोधित [`Event`](../../../com.aspose.html.dom.events/event/) इंटरफ़ेस प्रकार का समर्थन नहीं करता है तो उत्पन्न होता है |

### संबंधित देखें

* class [Event](../../../com.aspose.html.dom.events/event/)
* class [SVGSVGElement](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

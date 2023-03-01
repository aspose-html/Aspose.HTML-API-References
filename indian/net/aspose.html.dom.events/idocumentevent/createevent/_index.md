---
title: IDocumentEvent.CreateEvent
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: IDocumentEvent तरक. एक बनत हैEvent कर्यन्वयन द्वर समर्थत एक प्रकर क
type: docs
weight: 10
url: /hi/net/aspose.html.dom.events/idocumentevent/createevent/
---
## IDocumentEvent.CreateEvent method

एक बनाता है[`Event`](../../event/) कार्यान्वयन द्वारा समर्थित एक प्रकार का।

```csharp
public Event CreateEvent(string eventType)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| eventType | String | इवेंट टाइप पैरामीटर के प्रकार को निर्दिष्ट करता है[`Event`](../../event/) बनाया जाने वाला इंटरफ़ेस.  यदि[`Event`](../../event/)निर्दिष्ट इंटरफ़ेस कार्यान्वयन द्वारा समर्थित है, यह विधि एक new वापस कर देगी[`Event`](../../event/) अनुरोधित इंटरफ़ेस प्रकार का। यदि[`Event`](../../event/)के माध्यम से भेजा जाना है[`DispatchEvent`](../../../aspose.html.dom/eventtarget/dispatchevent/) विधि उपयुक्त [`InitEvent`](../../event/initevent/) आरंभ करने के लिए निर्माण के बाद विधि को बुलाया जाना चाहिए[`Event`](../../event/) s मान. |

### प्रतिलाभ की मात्रा

नव निर्मित[`Event`](../../event/)

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: यदि कार्यान्वयन के प्रकार का समर्थन नहीं करता है तो उठाया गया[`Event`](../../event/) इंटरफ़ेस अनुरोधित |

### यह सभी देखें

* class [Event](../../event/)
* interface [IDocumentEvent](../)
* नाम स्थान [Aspose.Html.Dom.Events](../../idocumentevent/)
* सभा [Aspose.HTML](../../../)



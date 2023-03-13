---
title: Interface IEventTarget
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Aspose.Html.Dom.Events.IEventTarget इंटरफेस. दEventTarget इंटरफ़ेस सभ नड्स द्वर एक कर्यन्वयन में कर्यन्वत कय जत है ज DOM इवेंट मडल क समर्थन करत है एकEventTarget और उस पर घटनओं क प्रेषणIEventTarget .
type: docs
weight: 810
url: /hi/net/aspose.html.dom.events/ieventtarget/
---
## IEventTarget interface

द[`EventTarget`](../../aspose.html.dom/eventtarget/) इंटरफ़ेस सभी नोड्स द्वारा एक कार्यान्वयन में कार्यान्वित किया जाता है जो DOM इवेंट मॉडल का समर्थन करता है। एक[`EventTarget`](../../aspose.html.dom/eventtarget/) और उस पर घटनाओं का प्रेषण`IEventTarget` .

```csharp
public interface IEventTarget
```

## तरीकों

| नाम | विवरण |
| --- | --- |
| [AddEventListener](../../aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener)(string, IEventListener) | यह विधि ईवेंट लक्ष्य पर ईवेंट श्रोताओं के पंजीकरण की अनुमति देती है। |
| [AddEventListener](../../aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(string, IEventListener, bool) | यह विधि ईवेंट लक्ष्य पर ईवेंट श्रोताओं के पंजीकरण की अनुमति देती है। |
| [DispatchEvent](../../aspose.html.dom.events/ieventtarget/dispatchevent/)(Event) | यह विधि इवेंट को कार्यान्वयन इवेंट मॉडल में भेजने की अनुमति देती है. |
| [RemoveEventListener](../../aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(string, IEventListener) | यह विधि ईवेंट श्रोताओं को ईवेंट लक्ष्य से हटाने की अनुमति देती है। यदि कोई[`IEventListener`](../ieventlistener/) एक से हटा दिया जाता है[`EventTarget`](../../aspose.html.dom/eventtarget/) जबकि यह किसी घटना को संसाधित कर रहा है, यह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं किया जाएगा। इवेंट श्रोताओं को हटाए जाने के बाद कभी नहीं बुलाया जा सकता है। |
| [RemoveEventListener](../../aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(string, IEventListener, bool) | यह विधि ईवेंट श्रोताओं को ईवेंट लक्ष्य से हटाने की अनुमति देती है। यदि कोई[`IEventListener`](../ieventlistener/) एक से हटा दिया जाता है[`EventTarget`](../../aspose.html.dom/eventtarget/) जबकि यह किसी घटना को संसाधित कर रहा है, यह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं किया जाएगा। इवेंट श्रोताओं को हटाए जाने के बाद कभी नहीं बुलाया जा सकता है। |

### यह सभी देखें

* नाम स्थान [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* सभा [Aspose.HTML](../../)



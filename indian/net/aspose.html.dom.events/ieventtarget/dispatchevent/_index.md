---
title: IEventTarget.DispatchEvent
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: IEventTarget तरक. यह वध इवेंट क कर्यन्वयन इवेंट मडल में भेजने क अनुमत देत है.
type: docs
weight: 20
url: /hi/net/aspose.html.dom.events/ieventtarget/dispatchevent/
---
## IEventTarget.DispatchEvent method

यह विधि इवेंट को कार्यान्वयन इवेंट मॉडल में भेजने की अनुमति देती है.

```csharp
public bool DispatchEvent(Event @event)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| event | Event | ईवेंट को संसाधित करने में उपयोग किए जाने वाले ईवेंट प्रकार, व्यवहार और प्रासंगिक जानकारी को निर्दिष्ट करता है। |

### प्रतिलाभ की मात्रा

का वापसी मान[`DispatchEvent`](../../../aspose.html.dom/eventtarget/dispatchevent/) इंगित करता है कि क्या श्रोताओं में से कोई भी जिसने घटना को संभाला है[`PreventDefault`](../../event/preventdefault/) . अगर[`PreventDefault`](../../event/preventdefault/) कहा जाता था मान असत्य है, अन्यथा मान सत्य है।

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) |  |

### टिप्पणियों

इस तरह से भेजे गए इवेंट में कैप्चरिंग और बुदबुदाहट का व्यवहार वैसा ही होगा जैसा सीधे कार्यान्वयन द्वारा भेजे गए इवेंट का होता है। इवेंट का लक्ष्य है[`EventTarget`](../../../aspose.html.dom/eventtarget/) जिस पर[`DispatchEvent`](../../../aspose.html.dom/eventtarget/dispatchevent/) कहा जाता है

### यह सभी देखें

* class [Event](../../event/)
* interface [IEventTarget](../)
* नाम स्थान [Aspose.Html.Dom.Events](../../ieventtarget/)
* सभा [Aspose.HTML](../../../)



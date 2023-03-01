---
title: Interface IEventListener
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Aspose.Html.Dom.Events.IEventListener इंटरफेस. दIEventListenerइंटरफ़ेस घटनओं क संभलने के लए प्रथमक तरक है उपयगकर्त इसे लगू करते हैंIEventListener इंटरफ़ेस और उनके श्रत क एक पर पंजकृत करेंEventTarget क उपयगAddEventListener वध. उपयगकर्तओं क भ हट देन चहएIEventListener उसमें सेEventTarget श्रत क उपयग पूर करने के बद
type: docs
weight: 800
url: /hi/net/aspose.html.dom.events/ieventlistener/
---
## IEventListener interface

द`IEventListener`इंटरफ़ेस घटनाओं को संभालने के लिए प्राथमिक तरीका है। उपयोगकर्ता इसे लागू करते हैं`IEventListener` इंटरफ़ेस और उनके श्रोता को एक पर पंजीकृत करें[`EventTarget`](../../aspose.html.dom/eventtarget/) का उपयोग[`AddEventListener`](../../aspose.html.dom/eventtarget/addeventlistener/) विधि. उपयोगकर्ताओं को भी हटा देना चाहिए`IEventListener` उसमें से[`EventTarget`](../../aspose.html.dom/eventtarget/) श्रोता का उपयोग पूरा करने के बाद।

```csharp
public interface IEventListener
```

## तरीकों

| नाम | विवरण |
| --- | --- |
| [HandleEvent](../../aspose.html.dom.events/ieventlistener/handleevent/)(Event) | इस विधि को तब कहा जाता है जब कोई घटना उस प्रकार की होती है जिसके लिए`IEventListener` इंटरफ़ेस पंजीकृत किया गया था। |

### टिप्पणियों

जब एक नोड को क्लोननोड पद्धति का उपयोग करके कॉपी किया जाता है, तो स्रोत नोड से जुड़े इवेंट श्रोता कॉपी किए गए नोड से जुड़े नहीं होते हैं। यदि उपयोगकर्ता समान ईवेंट श्रोताओं को नई बनाई गई कॉपी में जोड़ना चाहता है, तो उपयोगकर्ता को उन्हें मैन्युअल रूप से जोड़ना होगा।

### यह सभी देखें

* नाम स्थान [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* सभा [Aspose.HTML](../../)



---
title: EventTarget.RemoveEventListener
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: EventTarget तरक. यह वध ईवेंट श्रतओं क ईवेंट लक्ष्य से हटने क अनुमत देत है यद कईIEventListener एक से हट दय जत हैEventTarget जबक यह कस घटन क संसधत कर रह है यह वर्तमन क्रयओं द्वर ट्रगर नहं कय जएग इवेंट श्रतओं क हटए जने के बद कभ नहं बुलय ज सकत है
type: docs
weight: 40
url: /hi/net/aspose.html.dom/eventtarget/removeeventlistener/
---
## RemoveEventListener(string, DOMEventHandler, bool) {#removeeventlistener}

यह विधि ईवेंट श्रोताओं को ईवेंट लक्ष्य से हटाने की अनुमति देती है। यदि कोई[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) एक से हटा दिया जाता है[`EventTarget`](../) जबकि यह किसी घटना को संसाधित कर रहा है, यह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं किया जाएगा। इवेंट श्रोताओं को हटाए जाने के बाद कभी नहीं बुलाया जा सकता है।

```csharp
public void RemoveEventListener(string type, DOMEventHandler handler, bool useCapture)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | String | के ईवेंट प्रकार को निर्दिष्ट करता है[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) निकाला जा रहा है। |
| handler | DOMEventHandler | [`DOMEventHandler`](../../../aspose.html.dom.events/domeventhandler/) पैरामीटर इंगित करता है[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) निकाले जाने के लिए। |
| useCapture | Boolean | निर्दिष्ट करता है कि हटाया जा रहा इवेंट लिस्टनर एक कैप्चरिंग श्रोता के रूप में पंजीकृत था या नहीं। एक ही श्रोता की, और इसके विपरीत। |

### यह सभी देखें

* delegate [DOMEventHandler](../../../aspose.html.dom.events/domeventhandler/)
* class [EventTarget](../)
* नाम स्थान [Aspose.Html.Dom](../../eventtarget/)
* सभा [Aspose.HTML](../../../)

---

## RemoveEventListener(string, IEventListener) {#removeeventlistener_1}

यह विधि ईवेंट श्रोताओं को ईवेंट लक्ष्य से हटाने की अनुमति देती है। यदि कोई[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) एक से हटा दिया जाता है[`EventTarget`](../) जबकि यह किसी घटना को संसाधित कर रहा है, यह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं किया जाएगा। इवेंट श्रोताओं को हटाए जाने के बाद कभी नहीं बुलाया जा सकता है।

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | String | के ईवेंट प्रकार को निर्दिष्ट करता है[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) निकाला जा रहा है। |
| listener | IEventListener | [`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) पैरामीटर इंगित करता है[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) निकाले जाने के लिए। |

### यह सभी देखें

* interface [IEventListener](../../../aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* नाम स्थान [Aspose.Html.Dom](../../eventtarget/)
* सभा [Aspose.HTML](../../../)

---

## RemoveEventListener(string, IEventListener, bool) {#removeeventlistener_2}

यह विधि ईवेंट श्रोताओं को ईवेंट लक्ष्य से हटाने की अनुमति देती है। यदि कोई[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) एक से हटा दिया जाता है[`EventTarget`](../) जबकि यह किसी घटना को संसाधित कर रहा है, यह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं किया जाएगा। इवेंट श्रोताओं को हटाए जाने के बाद कभी नहीं बुलाया जा सकता है।

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | String | के ईवेंट प्रकार को निर्दिष्ट करता है[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) निकाला जा रहा है। |
| listener | IEventListener | [`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) पैरामीटर इंगित करता है[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) निकाले जाने के लिए। |
| useCapture | Boolean | निर्दिष्ट करता है कि हटाया जा रहा इवेंट लिस्टनर एक कैप्चरिंग श्रोता के रूप में पंजीकृत था या नहीं। एक ही श्रोता की, और इसके विपरीत। |

### यह सभी देखें

* interface [IEventListener](../../../aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* नाम स्थान [Aspose.Html.Dom](../../eventtarget/)
* सभा [Aspose.HTML](../../../)



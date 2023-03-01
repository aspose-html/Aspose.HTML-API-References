---
title: EventTarget.AddEventListener
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: EventTarget तरक. यह वध ईवेंट लक्ष्य पर ईवेंट श्रतओं के पंजकरण क अनुमत देत है
type: docs
weight: 10
url: /hi/net/aspose.html.dom/eventtarget/addeventlistener/
---
## AddEventListener(string, DOMEventHandler, bool) {#addeventlistener}

यह विधि ईवेंट लक्ष्य पर ईवेंट श्रोताओं के पंजीकरण की अनुमति देती है।

```csharp
public void AddEventListener(string type, DOMEventHandler handler, bool useCapture)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | String | घटना प्रकार जिसके लिए उपयोगकर्ता पंजीकरण कर रहा है |
| handler | DOMEventHandler | एक लेता है[`DOMEventHandler`](../../../aspose.html.dom.events/domeventhandler/) घटना होने पर बुलाया जाना है। |
| useCapture | Boolean | अगर सही है, तो यूजकैप्चर इंगित करता है कि उपयोगकर्ता कैप्चर शुरू करना चाहता है। कैप्चर शुरू करने के बाद, निर्दिष्ट प्रकार की सभी घटनाओं को पंजीकृत [`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) ट्री में उनके नीचे किसी भी ईवेंट लक्ष्य को भेजे जाने से पहले. ईवेंट जो ट्री के माध्यम से ऊपर की ओर बुदबुदा रहे हैं, ट्रिगर नहीं करेंगे[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) कैप्चर का उपयोग करने के लिए नामित। |

### टिप्पणियों

यदि कोई[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) एक में जोड़ा जाता है[`EventTarget`](../) जब यह किसी घटना को संसाधित कर रहा होता है, तो यह वर्तमान क्रियाओं द्वारा को ट्रिगर नहीं किया जाएगा, लेकिन ईवेंट प्रवाह के बाद के चरण के दौरान ट्रिगर किया जा सकता है, जैसे बुबलिंग चरण।

यदि एकाधिक समान ईवेंट श्रोता एक ही पर पंजीकृत हैं[`EventTarget`](../)उसी पैरामीटर के साथ डुप्लिकेट इंस्टेंसेस को छोड़ दिया जाता है। वे इसका कारण नहीं बनते हैं[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) दो बार बुलाए जाने के लिए और चूंकि उन्हें खारिज कर दिया गया है इसलिए उन्हें हटाने की आवश्यकता नहीं है the [`RemoveEventListener`](../removeeventlistener/) विधि।

### यह सभी देखें

* delegate [DOMEventHandler](../../../aspose.html.dom.events/domeventhandler/)
* class [EventTarget](../)
* नाम स्थान [Aspose.Html.Dom](../../eventtarget/)
* सभा [Aspose.HTML](../../../)

---

## AddEventListener(string, IEventListener) {#addeventlistener_1}

यह विधि ईवेंट लक्ष्य पर ईवेंट श्रोताओं के पंजीकरण की अनुमति देती है।

```csharp
public void AddEventListener(string type, IEventListener listener)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | String | घटना प्रकार जिसके लिए उपयोगकर्ता पंजीकरण कर रहा है |
| listener | IEventListener | उपयोगकर्ता द्वारा कार्यान्वित एक इंटरफ़ेस लेता है जिसमें ईवेंट होने पर कॉल करने के तरीके शामिल होते हैं। |

### टिप्पणियों

यदि कोई[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) एक में जोड़ा जाता है[`EventTarget`](../) जब यह किसी घटना को संसाधित कर रहा होता है, तो यह वर्तमान क्रियाओं द्वारा को ट्रिगर नहीं किया जाएगा, लेकिन ईवेंट प्रवाह के बाद के चरण के दौरान ट्रिगर किया जा सकता है, जैसे बुबलिंग चरण।

यदि एकाधिक समान ईवेंट श्रोता एक ही पर पंजीकृत हैं[`EventTarget`](../)उसी पैरामीटर के साथ डुप्लिकेट इंस्टेंसेस को छोड़ दिया जाता है। वे इसका कारण नहीं बनते हैं[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) दो बार बुलाए जाने के लिए और चूंकि उन्हें खारिज कर दिया गया है इसलिए उन्हें हटाने की आवश्यकता नहीं है the [`RemoveEventListener`](../removeeventlistener/) विधि।

### यह सभी देखें

* interface [IEventListener](../../../aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* नाम स्थान [Aspose.Html.Dom](../../eventtarget/)
* सभा [Aspose.HTML](../../../)

---

## AddEventListener(string, IEventListener, bool) {#addeventlistener_2}

यह विधि ईवेंट लक्ष्य पर ईवेंट श्रोताओं के पंजीकरण की अनुमति देती है।

```csharp
public void AddEventListener(string type, IEventListener listener, bool useCapture)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | String | घटना प्रकार जिसके लिए उपयोगकर्ता पंजीकरण कर रहा है |
| listener | IEventListener | उपयोगकर्ता द्वारा कार्यान्वित एक इंटरफ़ेस लेता है जिसमें ईवेंट होने पर कॉल करने के तरीके शामिल होते हैं। |
| useCapture | Boolean | अगर सही है, तो यूजकैप्चर इंगित करता है कि उपयोगकर्ता कैप्चर शुरू करना चाहता है। कैप्चर शुरू करने के बाद, निर्दिष्ट प्रकार की सभी घटनाओं को पंजीकृत [`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) ट्री में उनके नीचे किसी भी ईवेंट लक्ष्य को भेजे जाने से पहले. ईवेंट जो ट्री के माध्यम से ऊपर की ओर बुदबुदा रहे हैं, ट्रिगर नहीं करेंगे[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) कैप्चर का उपयोग करने के लिए नामित। |

### टिप्पणियों

यदि कोई[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) एक में जोड़ा जाता है[`EventTarget`](../) जब यह किसी घटना को संसाधित कर रहा होता है, तो यह वर्तमान क्रियाओं द्वारा को ट्रिगर नहीं किया जाएगा, लेकिन ईवेंट प्रवाह के बाद के चरण के दौरान ट्रिगर किया जा सकता है, जैसे बुबलिंग चरण।

यदि एकाधिक समान ईवेंट श्रोता एक ही पर पंजीकृत हैं[`EventTarget`](../)उसी पैरामीटर के साथ डुप्लिकेट इंस्टेंसेस को छोड़ दिया जाता है। वे इसका कारण नहीं बनते हैं[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) दो बार बुलाए जाने के लिए और चूंकि उन्हें खारिज कर दिया गया है इसलिए उन्हें हटाने की आवश्यकता नहीं है the [`RemoveEventListener`](../removeeventlistener/) विधि।

### यह सभी देखें

* interface [IEventListener](../../../aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* नाम स्थान [Aspose.Html.Dom](../../eventtarget/)
* सभा [Aspose.HTML](../../../)



---
title: Class Event
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Aspose.Html.Dom.Events.Event कक्ष. दEvent ईवेंट क संसधत करने वले हैंडलर क ईवेंट के बरे में प्रसंगक जनकर प्रदन करने के लए उपयग कय जत है
type: docs
weight: 770
url: /hi/net/aspose.html.dom.events/event/
---
## Event class

द`Event` ईवेंट को संसाधित करने वाले हैंडलर को ईवेंट के बारे में प्रासंगिक जानकारी प्रदान करने के लिए उपयोग किया जाता है।

```csharp
public class Event : DOMObject
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Event](event/#constructor)(string) | का एक नया उदाहरण प्रारंभ करता है`Event` वर्ग. |
| [Event](event/#constructor_1)(string, IDictionary&lt;string, object&gt;) | का एक नया उदाहरण प्रारंभ करता है`Event` वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | यह इंगित करने के लिए प्रयोग किया जाता है कि कोई ईवेंट बबलिंग ईवेंट है या नहीं। यदि ईवेंट बबल कर सकता है तो मान सही है, अन्यथा मान गलत है. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | यह इंगित करने के लिए प्रयोग किया जाता है कि क्या किसी ईवेंट की डिफ़ॉल्ट क्रिया को रोका जा सकता है या नहीं। यदि डिफ़ॉल्ट क्रिया को रोका जा सकता है तो मान सही है, अन्यथा मान गलत है। |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | इंगित करने के लिए प्रयोग किया जाता है[`IEventTarget`](../ieventtarget/) किसका[`IEventListener`](../ieventlistener/) s वर्तमान में संसाधित किए जा रहे हैं। यह कैप्चरिंग और बबलिंग के दौरान विशेष रूप से उपयोगी है। |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | सही रिटर्न देता है अगर preventDefault () लागू किया गया था, जबकि रद्द करने योग्य विशेषता मान सही है, और गलत अन्यथा। |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | यह इंगित करने के लिए प्रयोग किया जाता है कि वर्तमान में ईवेंट प्रवाह के किस चरण का मूल्यांकन किया जा रहा है। |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | isTrusted विशेषता को वह मान वापस करना चाहिए जिसके लिए इसे प्रारंभ किया गया था। जब कोई ईवेंट बनाया जाता है तो एट्रिब्यूट को गलत. पर इनिशियलाइज़ किया जाना चाहिए |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | इंगित करने के लिए प्रयोग किया जाता है[`IEventTarget`](../ieventtarget/) जिसके लिए घटना को मूल रूप से भेजा गया था। |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | उस समय को निर्दिष्ट करने के लिए उपयोग किया जाता है (युग के सापेक्ष मिलीसेकंड में) जिस पर ईवेंट बनाया गया था। इस तथ्य के कारण कि कुछ सिस्टम यह जानकारी प्रदान नहीं कर सकते हैं, टाइमस्टैम्प का मान सभी घटनाओं के लिए उपलब्ध नहीं हो सकता है। उपलब्ध नहीं होने पर , 0 का मान लौटाया जाएगा. एपोच समय के उदाहरण हैं सिस्टम के प्रारंभ होने का समय या 0:0:0 UTC 1 जनवरी 1970. |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | इवेंट का नाम (केस-इनसेंसिटिव)। नाम एक XML नाम होना चाहिए. |

## तरीकों

| नाम | विवरण |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | इस विधि का उपयोग ECMAScript ऑब्जेक्ट को पुनः प्राप्त करने के लिए किया जाता हैType . |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | द[`InitEvent`](./initevent/) विधि का उपयोग किसी के मान को प्रारंभ करने के लिए किया जाता है`Event` the द्वारा बनाया गया[`IDocumentEvent`](../idocumentevent/) इंटरफ़ेस. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | यदि कोई ईवेंट रद्द करने योग्य है, तो[`PreventDefault`](./preventdefault/) विधि का उपयोग यह दर्शाने के लिए किया जाता है कि ईवेंट को रद्द किया जाना है, जिसका अर्थ है कि ईवेंट के परिणामस्वरूप कार्यान्वयन द्वारा सामान्य रूप से की जाने वाली कोई भी डिफ़ॉल्ट कार्रवाई नहीं होगी। |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | इस विधि को लागू करने से ईवेंट को वर्तमान के बाद पंजीकृत किसी भी ईवेंट श्रोताओं तक पहुंचने से रोकता है और जब पेड़ में भेजा जाता है तो ईवेंट को किसी भी अन्य ऑब्जेक्ट तक पहुंचने से रोकता है। |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | द[`StopPropagation`](./stoppropagation/) विधि का उपयोग घटना प्रवाह के दौरान किसी घटना के आगे प्रसार को रोकने के लिए किया जाता है। |

## खेत

| नाम | विवरण |
| --- | --- |
| const [AtTargetPhase](../../aspose.html.dom.events/event/attargetphase/) | वर्तमान ईवेंट चरण कैप्चरिंग चरण है। |
| const [BubblingPhase](../../aspose.html.dom.events/event/bubblingphase/) | वर्तमान ईवेंट चरण बबलिंग चरण है। |
| const [CapturingPhase](../../aspose.html.dom.events/event/capturingphase/) | इवेंट का वर्तमान में लक्ष्य पर मूल्यांकन किया जा रहा है[`IEventTarget`](../ieventtarget/) . |
| const [NonePhase](../../aspose.html.dom.events/event/nonephase/) | वर्तमान में नहीं भेजे गए ईवेंट इस चरण में हैं। |

### टिप्पणियों

एक वस्तु जो लागू करती है`Event` आम तौर पर एक ईवेंट हैंडलर के लिए पहले पैरामीटर के रूप में पास किया जाता है। अतिरिक्त इंटरफेस प्राप्त करके इवेंट हैंडलर को अधिक विशिष्ट संदर्भ जानकारी दी जाती है`Event` जिसमें उनके साथ होने वाले ईवेंट के प्रकार से सीधे संबंधित जानकारी होती है। ये व्युत्पन्न इंटरफेस भी इवेंट श्रोता को दिए गए ऑब्जेक्ट द्वारा कार्यान्वित किए जाते हैं।

### यह सभी देखें

* class [DOMObject](../../aspose.html.dom/domobject/)
* नाम स्थान [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* सभा [Aspose.HTML](../../)



---
title: Class TimeEvent
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Aspose.Html.Dom.Svg.Events.TimeEvent कक्ष. TimeEvent इंटरफ़ेस समय क घटनओं से जुड़ वशष्ट प्रसंगक जनकर प्रदन करत है वभन्न प्रकर के इवेंट ज ह सकते हैं वे हैं startEvent endEvent और repeatEvent.
type: docs
weight: 1340
url: /hi/net/aspose.html.dom.svg.events/timeevent/
---
## TimeEvent class

TimeEvent इंटरफ़ेस समय की घटनाओं से जुड़ी विशिष्ट प्रासंगिक जानकारी प्रदान करता है। विभिन्न प्रकार के इवेंट जो हो सकते हैं वे हैं: startEvent, endEvent और repeatEvent.

```csharp
public class TimeEvent : Event
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | यह इंगित करने के लिए प्रयोग किया जाता है कि कोई ईवेंट बबलिंग ईवेंट है या नहीं। यदि ईवेंट बबल कर सकता है तो मान सही है, अन्यथा मान गलत है. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | यह इंगित करने के लिए प्रयोग किया जाता है कि क्या किसी ईवेंट की डिफ़ॉल्ट क्रिया को रोका जा सकता है या नहीं। यदि डिफ़ॉल्ट क्रिया को रोका जा सकता है तो मान सही है, अन्यथा मान गलत है। |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | इंगित करने के लिए प्रयोग किया जाता है[`IEventTarget`](../../aspose.html.dom.events/ieventtarget/) किसका[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) s वर्तमान में संसाधित किए जा रहे हैं। यह कैप्चरिंग और बबलिंग के दौरान विशेष रूप से उपयोगी है। |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | सही रिटर्न देता है अगर preventDefault () लागू किया गया था, जबकि रद्द करने योग्य विशेषता मान सही है, और गलत अन्यथा। |
| [Detail](../../aspose.html.dom.svg.events/timeevent/detail/) { get; } | इवेंट के प्रकार के आधार पर, इवेंट के बारे में कुछ विवरण जानकारी निर्दिष्ट करता है। इस ईवेंट प्रकार के लिए, एनिमेशन के लिए रिपीट संख्या इंगित करता है. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | यह इंगित करने के लिए प्रयोग किया जाता है कि वर्तमान में ईवेंट प्रवाह के किस चरण का मूल्यांकन किया जा रहा है। |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | isTrusted विशेषता को वह मान वापस करना चाहिए जिसके लिए इसे प्रारंभ किया गया था। जब कोई ईवेंट बनाया जाता है तो एट्रिब्यूट को गलत. पर इनिशियलाइज़ किया जाना चाहिए |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | इंगित करने के लिए प्रयोग किया जाता है[`IEventTarget`](../../aspose.html.dom.events/ieventtarget/) जिसके लिए घटना को मूल रूप से भेजा गया था। |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | उस समय को निर्दिष्ट करने के लिए उपयोग किया जाता है (युग के सापेक्ष मिलीसेकंड में) जिस पर ईवेंट बनाया गया था। इस तथ्य के कारण कि कुछ सिस्टम यह जानकारी प्रदान नहीं कर सकते हैं, टाइमस्टैम्प का मान सभी घटनाओं के लिए उपलब्ध नहीं हो सकता है। उपलब्ध नहीं होने पर , 0 का मान लौटाया जाएगा. एपोच समय के उदाहरण हैं सिस्टम के प्रारंभ होने का समय या 0:0:0 UTC 1 जनवरी 1970. |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | इवेंट का नाम (केस-इनसेंसिटिव)। नाम एक XML नाम होना चाहिए. |
| [View](../../aspose.html.dom.svg.events/timeevent/view/) { get; } | दृश्य विशेषता सार दृश्य [DOM2VIEWS] की पहचान करती है जिससे घटना उत्पन्न हुई थी। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | इस विधि का उपयोग ECMAScript ऑब्जेक्ट को पुनः प्राप्त करने के लिए किया जाता हैType . |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | द[`InitEvent`](../../aspose.html.dom.events/event/initevent/) विधि का उपयोग किसी के मान को प्रारंभ करने के लिए किया जाता है[`Event`](../../aspose.html.dom.events/event/) the द्वारा बनाया गया[`IDocumentEvent`](../../aspose.html.dom.events/idocumentevent/) इंटरफ़ेस. |
| [InitTimeEvent](../../aspose.html.dom.svg.events/timeevent/inittimeevent/)(string, IAbstractView, long) | initTimeEvent विधि का उपयोग DocumentEvent इंटरफ़ेस के माध्यम से बनाए गए TimeEvent के मान को प्रारंभ करने के लिए किया जाता है। इस विधि को केवल TimeEvent को डिस्पैचइवेंट विधि के माध्यम से भेजे जाने से पहले ही कॉल किया जा सकता है, हालाँकि यदि आवश्यक हो तो उस चरण के दौरान इसे कई बार कॉल किया जा सकता है। यदि एक से अधिक बार कॉल किया जाता है, तो अंतिम मंगलाचरण को प्राथमिकता दी जाती है. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | यदि कोई ईवेंट रद्द करने योग्य है, तो[`PreventDefault`](../../aspose.html.dom.events/event/preventdefault/) विधि का उपयोग यह दर्शाने के लिए किया जाता है कि ईवेंट को रद्द किया जाना है, जिसका अर्थ है कि ईवेंट के परिणामस्वरूप कार्यान्वयन द्वारा सामान्य रूप से की जाने वाली कोई भी डिफ़ॉल्ट कार्रवाई नहीं होगी। |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | इस विधि को लागू करने से ईवेंट को वर्तमान के बाद पंजीकृत किसी भी ईवेंट श्रोताओं तक पहुंचने से रोकता है और जब पेड़ में भेजा जाता है तो ईवेंट को किसी भी अन्य ऑब्जेक्ट तक पहुंचने से रोकता है। |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | द[`StopPropagation`](../../aspose.html.dom.events/event/stoppropagation/) विधि का उपयोग घटना प्रवाह के दौरान किसी घटना के आगे प्रसार को रोकने के लिए किया जाता है। |

### यह सभी देखें

* class [Event](../../aspose.html.dom.events/event/)
* नाम स्थान [Aspose.Html.Dom.Svg.Events](../../aspose.html.dom.svg.events/)
* सभा [Aspose.HTML](../../)



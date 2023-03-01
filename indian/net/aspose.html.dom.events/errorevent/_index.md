---
title: Class ErrorEvent
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Aspose.Html.Dom.Events.ErrorEvent कक्ष. दErrorEvent रनटइम के दरन हुई त्रुटयं के बरे में प्रसंगक जनकर प्रदन करत है
type: docs
weight: 760
url: /hi/net/aspose.html.dom.events/errorevent/
---
## ErrorEvent class

द`ErrorEvent` रनटाइम के दौरान हुई त्रुटियों के बारे में प्रासंगिक जानकारी प्रदान करता है।

```csharp
public class ErrorEvent : Event
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [ErrorEvent](errorevent/#constructor_1)(Exception) | का एक नया उदाहरण प्रारंभ करता है`ErrorEvent` वर्ग. |
| [ErrorEvent](errorevent/#constructor)(IDictionary&lt;string, object&gt;) | का एक नया उदाहरण प्रारंभ करता है`ErrorEvent` वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | यह इंगित करने के लिए प्रयोग किया जाता है कि कोई ईवेंट बबलिंग ईवेंट है या नहीं। यदि ईवेंट बबल कर सकता है तो मान सही है, अन्यथा मान गलत है. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | यह इंगित करने के लिए प्रयोग किया जाता है कि क्या किसी ईवेंट की डिफ़ॉल्ट क्रिया को रोका जा सकता है या नहीं। यदि डिफ़ॉल्ट क्रिया को रोका जा सकता है तो मान सही है, अन्यथा मान गलत है। |
| [ColNo](../../aspose.html.dom.events/errorevent/colno/) { get; } | कॉलनो विशेषता को वह मान वापस करना चाहिए जिसके लिए इसे प्रारंभ किया गया था। जब ऑब्जेक्ट बनाया जाता है, तो इस विशेषता को शून्य से प्रारंभ किया जाना चाहिए। यह उस कॉलम संख्या का प्रतिनिधित्व करता है जहां स्क्रिप्ट में त्रुटि हुई थी। |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | इंगित करने के लिए प्रयोग किया जाता है[`IEventTarget`](../ieventtarget/) किसका[`IEventListener`](../ieventlistener/) s वर्तमान में संसाधित किए जा रहे हैं। यह कैप्चरिंग और बबलिंग के दौरान विशेष रूप से उपयोगी है। |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | सही रिटर्न देता है अगर preventDefault () लागू किया गया था, जबकि रद्द करने योग्य विशेषता मान सही है, और गलत अन्यथा। |
| [Error](../../aspose.html.dom.events/errorevent/error/) { get; } | एरर एट्रिब्यूट को वह वैल्यू लौटानी चाहिए जिस पर इसे इनिशियलाइज़ किया गया था। जब ऑब्जेक्ट बनाया जाता है, तो इस विशेषता को शून्य में प्रारंभ किया जाना चाहिए। जहां उपयुक्त हो, यह त्रुटि का प्रतिनिधित्व करने वाली वस्तु पर सेट है (उदाहरण के लिए एक बेजोड़ DOM अपवाद के मामले में अपवाद वस्तु)। |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | यह इंगित करने के लिए प्रयोग किया जाता है कि वर्तमान में ईवेंट प्रवाह के किस चरण का मूल्यांकन किया जा रहा है। |
| [FileName](../../aspose.html.dom.events/errorevent/filename/) { get; } | फ़ाइल नाम विशेषता को वह मान वापस करना चाहिए जिसके लिए इसे प्रारंभ किया गया था। जब ऑब्जेक्ट बनाया जाता है, तो इस विशेषता को खाली स्ट्रिंग में प्रारंभ किया जाना चाहिए। यह उस स्क्रिप्ट के निरपेक्ष URL का प्रतिनिधित्व करता है जिसमें त्रुटि मूल रूप से हुई थी। |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | isTrusted विशेषता को वह मान वापस करना चाहिए जिसके लिए इसे प्रारंभ किया गया था। जब कोई ईवेंट बनाया जाता है तो एट्रिब्यूट को गलत. पर इनिशियलाइज़ किया जाना चाहिए |
| [LineNo](../../aspose.html.dom.events/errorevent/lineno/) { get; } | लिनोनो विशेषता को वह मान वापस करना चाहिए जिसके लिए इसे प्रारंभ किया गया था। जब ऑब्जेक्ट बनाया जाता है, तो इस विशेषता को शून्य से प्रारंभ किया जाना चाहिए। यह उस लाइन नंबर का प्रतिनिधित्व करता है जहां स्क्रिप्ट में त्रुटि हुई थी। |
| [Message](../../aspose.html.dom.events/errorevent/message/) { get; } | संदेश विशेषता को वह मान वापस करना चाहिए जिसके लिए इसे प्रारंभ किया गया था। जब ऑब्जेक्ट बनाया जाता है, तो इस विशेषता को खाली स्ट्रिंग में प्रारंभ किया जाना चाहिए। यह त्रुटि संदेश का प्रतिनिधित्व करता है। |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | इंगित करने के लिए प्रयोग किया जाता है[`IEventTarget`](../ieventtarget/) जिसके लिए घटना को मूल रूप से भेजा गया था। |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | उस समय को निर्दिष्ट करने के लिए उपयोग किया जाता है (युग के सापेक्ष मिलीसेकंड में) जिस पर ईवेंट बनाया गया था। इस तथ्य के कारण कि कुछ सिस्टम यह जानकारी प्रदान नहीं कर सकते हैं, टाइमस्टैम्प का मान सभी घटनाओं के लिए उपलब्ध नहीं हो सकता है। उपलब्ध नहीं होने पर , 0 का मान लौटाया जाएगा. एपोच समय के उदाहरण हैं सिस्टम के प्रारंभ होने का समय या 0:0:0 UTC 1 जनवरी 1970. |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | इवेंट का नाम (केस-इनसेंसिटिव)। नाम एक XML नाम होना चाहिए. |

## तरीकों

| नाम | विवरण |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | इस विधि का उपयोग ECMAScript ऑब्जेक्ट को पुनः प्राप्त करने के लिए किया जाता हैType . |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | द[`InitEvent`](../event/initevent/) विधि का उपयोग किसी के मान को प्रारंभ करने के लिए किया जाता है[`Event`](../event/) the द्वारा बनाया गया[`IDocumentEvent`](../idocumentevent/) इंटरफ़ेस. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | यदि कोई ईवेंट रद्द करने योग्य है, तो[`PreventDefault`](../event/preventdefault/) विधि का उपयोग यह दर्शाने के लिए किया जाता है कि ईवेंट को रद्द किया जाना है, जिसका अर्थ है कि ईवेंट के परिणामस्वरूप कार्यान्वयन द्वारा सामान्य रूप से की जाने वाली कोई भी डिफ़ॉल्ट कार्रवाई नहीं होगी। |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | इस विधि को लागू करने से ईवेंट को वर्तमान के बाद पंजीकृत किसी भी ईवेंट श्रोताओं तक पहुंचने से रोकता है और जब पेड़ में भेजा जाता है तो ईवेंट को किसी भी अन्य ऑब्जेक्ट तक पहुंचने से रोकता है। |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | द[`StopPropagation`](../event/stoppropagation/) विधि का उपयोग घटना प्रवाह के दौरान किसी घटना के आगे प्रसार को रोकने के लिए किया जाता है। |

### यह सभी देखें

* class [Event](../event/)
* नाम स्थान [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* सभा [Aspose.HTML](../../)



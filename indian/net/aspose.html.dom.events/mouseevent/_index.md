---
title: Class MouseEvent
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Aspose.Html.Dom.Events.MouseEvent कक्ष. मउसइवेंट इंटरफ़ेस मउस इवेंट्स से संबंधत वशष्ट प्रसंगक जनकर प्रदन करत है
type: docs
weight: 840
url: /hi/net/aspose.html.dom.events/mouseevent/
---
## MouseEvent class

माउसइवेंट इंटरफ़ेस माउस इवेंट्स से संबंधित विशिष्ट प्रासंगिक जानकारी प्रदान करता है।

```csharp
public class MouseEvent : UIEvent
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [MouseEvent](mouseevent/#constructor)(string) | का एक नया उदाहरण प्रारंभ करता है`MouseEvent` वर्ग. |
| [MouseEvent](mouseevent/#constructor_1)(string, IDictionary&lt;string, object&gt;) | का एक नया उदाहरण प्रारंभ करता है`MouseEvent` वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [AltKey](../../aspose.html.dom.events/mouseevent/altkey/) { get; } | altKey विशेषता का संदर्भ लें। |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | यह इंगित करने के लिए प्रयोग किया जाता है कि कोई ईवेंट बबलिंग ईवेंट है या नहीं। यदि ईवेंट बबल कर सकता है तो मान सही है, अन्यथा मान गलत है. |
| [Button](../../aspose.html.dom.events/mouseevent/button/) { get; } | माउस बटन के दबाव या रिलीज के कारण होने वाली माउस घटनाओं के दौरान, बटन का उपयोग यह इंगित करने के लिए किया जाना चाहिए कि किस पॉइंटर डिवाइस बटन ने स्थिति बदल दी है। |
| [Buttons](../../aspose.html.dom.events/mouseevent/buttons/) { get; } | किसी भी माउस इवेंट के दौरान, बटन का उपयोग यह इंगित करने के लिए किया जाना चाहिए कि माउस बटन का कौन सा संयोजन वर्तमान में दबाया जा रहा है, जिसे बिटमास्क के रूप में व्यक्त किया गया है। |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | यह इंगित करने के लिए प्रयोग किया जाता है कि क्या किसी ईवेंट की डिफ़ॉल्ट क्रिया को रोका जा सकता है या नहीं। यदि डिफ़ॉल्ट क्रिया को रोका जा सकता है तो मान सही है, अन्यथा मान गलत है। |
| [ClientX](../../aspose.html.dom.events/mouseevent/clientx/) { get; } | वह क्षैतिज निर्देशांक जिस पर इवेंट से जुड़े व्यूपोर्ट के सापेक्ष इवेंट हुआ। |
| [ClientY](../../aspose.html.dom.events/mouseevent/clienty/) { get; } | वर्टिकल कोऑर्डिनेट जिस पर इवेंट से जुड़े व्यूपोर्ट के सापेक्ष इवेंट हुआ। |
| [CtrlKey](../../aspose.html.dom.events/mouseevent/ctrlkey/) { get; } | ctrlKey विशेषता का संदर्भ लें। |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | इंगित करने के लिए प्रयोग किया जाता है[`IEventTarget`](../ieventtarget/) किसका[`IEventListener`](../ieventlistener/) s वर्तमान में संसाधित किए जा रहे हैं। यह कैप्चरिंग और बबलिंग के दौरान विशेष रूप से उपयोगी है। |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | सही रिटर्न देता है अगर preventDefault () लागू किया गया था, जबकि रद्द करने योग्य विशेषता मान सही है, और गलत अन्यथा। |
| [Detail](../../aspose.html.dom.events/uievent/detail/) { get; } | इवेंट के प्रकार के आधार पर, इवेंट के बारे में कुछ विवरण जानकारी निर्दिष्ट करता है. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | यह इंगित करने के लिए प्रयोग किया जाता है कि वर्तमान में ईवेंट प्रवाह के किस चरण का मूल्यांकन किया जा रहा है। |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | isTrusted विशेषता को वह मान वापस करना चाहिए जिसके लिए इसे प्रारंभ किया गया था। जब कोई ईवेंट बनाया जाता है तो एट्रिब्यूट को गलत. पर इनिशियलाइज़ किया जाना चाहिए |
| [MetaKey](../../aspose.html.dom.events/mouseevent/metakey/) { get; } | मेटाकी विशेषता का संदर्भ लें। |
| [RelatedTarget](../../aspose.html.dom.events/mouseevent/relatedtarget/) { get; } | इवेंट के प्रकार के आधार पर यूआई इवेंट से संबंधित द्वितीयक ईवेंट लक्ष्य की पहचान करने के लिए उपयोग किया जाता है। |
| [ScreenX](../../aspose.html.dom.events/mouseevent/screenx/) { get; } | क्षैतिज समन्वय जिस पर स्क्रीन समन्वय प्रणाली की उत्पत्ति के सापेक्ष घटना हुई। |
| [ScreenY](../../aspose.html.dom.events/mouseevent/screeny/) { get; } | वह लंबवत निर्देशांक जिस पर स्क्रीन समन्वय प्रणाली की उत्पत्ति के सापेक्ष घटना घटित हुई। |
| [ShiftKey](../../aspose.html.dom.events/mouseevent/shiftkey/) { get; } | शिफ्टकी विशेषता का संदर्भ लें। |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | इंगित करने के लिए प्रयोग किया जाता है[`IEventTarget`](../ieventtarget/) जिसके लिए घटना को मूल रूप से भेजा गया था। |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | उस समय को निर्दिष्ट करने के लिए उपयोग किया जाता है (युग के सापेक्ष मिलीसेकंड में) जिस पर ईवेंट बनाया गया था। इस तथ्य के कारण कि कुछ सिस्टम यह जानकारी प्रदान नहीं कर सकते हैं, टाइमस्टैम्प का मान सभी घटनाओं के लिए उपलब्ध नहीं हो सकता है। उपलब्ध नहीं होने पर , 0 का मान लौटाया जाएगा. एपोच समय के उदाहरण हैं सिस्टम के प्रारंभ होने का समय या 0:0:0 UTC 1 जनवरी 1970. |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | इवेंट का नाम (केस-इनसेंसिटिव)। नाम एक XML नाम होना चाहिए. |
| [View](../../aspose.html.dom.events/uievent/view/) { get; } | दृश्य विशेषता उस विंडो की पहचान करती है जिससे ईवेंट उत्पन्न किया गया था। इस विशेषता का गैर-प्रारंभिक मान शून्य होना चाहिए। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | इस विधि का उपयोग ECMAScript ऑब्जेक्ट को पुनः प्राप्त करने के लिए किया जाता हैType . |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | द[`InitEvent`](../event/initevent/) विधि का उपयोग किसी के मान को प्रारंभ करने के लिए किया जाता है[`Event`](../event/) the द्वारा बनाया गया[`IDocumentEvent`](../idocumentevent/) इंटरफ़ेस. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | यदि कोई ईवेंट रद्द करने योग्य है, तो[`PreventDefault`](../event/preventdefault/) विधि का उपयोग यह दर्शाने के लिए किया जाता है कि ईवेंट को रद्द किया जाना है, जिसका अर्थ है कि ईवेंट के परिणामस्वरूप कार्यान्वयन द्वारा सामान्य रूप से की जाने वाली कोई भी डिफ़ॉल्ट कार्रवाई नहीं होगी। |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | इस विधि को लागू करने से ईवेंट को वर्तमान के बाद पंजीकृत किसी भी ईवेंट श्रोताओं तक पहुंचने से रोकता है और जब पेड़ में भेजा जाता है तो ईवेंट को किसी भी अन्य ऑब्जेक्ट तक पहुंचने से रोकता है। |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | द[`StopPropagation`](../event/stoppropagation/) विधि का उपयोग घटना प्रवाह के दौरान किसी घटना के आगे प्रसार को रोकने के लिए किया जाता है। |

### यह सभी देखें

* class [UIEvent](../uievent/)
* नाम स्थान [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* सभा [Aspose.HTML](../../)



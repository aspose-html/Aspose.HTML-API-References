---
title: Class KeyboardEvent
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Aspose.Html.Dom.Events.KeyboardEvent कक्ष. कबर्डइवेंट इंटरफ़ेस कबर्ड उपकरणं से संबंधत वशष्ट प्रसंगक जनकर प्रदन करत है प्रत्येक कबर्ड ईवेंट एक मन क उपयग करके एक कुंज क संदर्भ देत है कुंजपटल घटनओं क समन्यत उस तत्व पर नर्देशत कय जत है जसमें फकस हत है
type: docs
weight: 830
url: /hi/net/aspose.html.dom.events/keyboardevent/
---
## KeyboardEvent class

कीबोर्डइवेंट इंटरफ़ेस कीबोर्ड उपकरणों से संबंधित विशिष्ट प्रासंगिक जानकारी प्रदान करता है। प्रत्येक कीबोर्ड ईवेंट एक मान का उपयोग करके एक कुंजी का संदर्भ देता है। कुंजीपटल घटनाओं को सामान्यतः उस तत्व पर निर्देशित किया जाता है जिसमें फोकस होता है।

```csharp
public class KeyboardEvent : UIEvent
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [KeyboardEvent](keyboardevent/#constructor)(string) | का एक नया उदाहरण प्रारंभ करता है`KeyboardEvent` वर्ग. |
| [KeyboardEvent](keyboardevent/#constructor_1)(string, IDictionary&lt;string, object&gt;) | का एक नया उदाहरण प्रारंभ करता है`KeyboardEvent` वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [AltKey](../../aspose.html.dom.events/keyboardevent/altkey/) { get; } | सच है अगर Alt (वैकल्पिक) (या "विकल्प") कुंजी संशोधक सक्रिय था। इस विशेषता का गैर-प्रारंभिक मान गलत होना चाहिए। |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | यह इंगित करने के लिए प्रयोग किया जाता है कि कोई ईवेंट बबलिंग ईवेंट है या नहीं। यदि ईवेंट बबल कर सकता है तो मान सही है, अन्यथा मान गलत है. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | यह इंगित करने के लिए प्रयोग किया जाता है कि क्या किसी ईवेंट की डिफ़ॉल्ट क्रिया को रोका जा सकता है या नहीं। यदि डिफ़ॉल्ट क्रिया को रोका जा सकता है तो मान सही है, अन्यथा मान गलत है। |
| [Code](../../aspose.html.dom.events/keyboardevent/code/) { get; } | कोड में एक स्ट्रिंग होती है जो दबाए जाने वाली भौतिक कुंजी की पहचान करती है। मूल्य वर्तमान कीबोर्ड लेआउट या संशोधक स्थिति से प्रभावित नहीं होता है, इसलिए एक विशेष कुंजी हमेशा समान मान लौटाती है। |
| [CtrlKey](../../aspose.html.dom.events/keyboardevent/ctrlkey/) { get; } | सच है अगर नियंत्रण (नियंत्रण) कुंजी संशोधक सक्रिय था। इस विशेषता का गैर-प्रारंभिक मान गलत होना चाहिए। |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | इंगित करने के लिए प्रयोग किया जाता है[`IEventTarget`](../ieventtarget/) किसका[`IEventListener`](../ieventlistener/) s वर्तमान में संसाधित किए जा रहे हैं। यह कैप्चरिंग और बबलिंग के दौरान विशेष रूप से उपयोगी है। |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | सही रिटर्न देता है अगर preventDefault () लागू किया गया था, जबकि रद्द करने योग्य विशेषता मान सही है, और गलत अन्यथा। |
| [Detail](../../aspose.html.dom.events/uievent/detail/) { get; } | इवेंट के प्रकार के आधार पर, इवेंट के बारे में कुछ विवरण जानकारी निर्दिष्ट करता है. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | यह इंगित करने के लिए प्रयोग किया जाता है कि वर्तमान में ईवेंट प्रवाह के किस चरण का मूल्यांकन किया जा रहा है। |
| [IsComposing](../../aspose.html.dom.events/keyboardevent/iscomposing/) { get; } | सच है अगर कुंजी घटना एक संरचना सत्र के भाग के रूप में होती है, यानी, रचना प्रारंभ घटना के बाद और संबंधित संरचना अंत घटना से पहले। इस विशेषता का गैर-प्रारंभिक मान गलत होना चाहिए। |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | isTrusted विशेषता को वह मान वापस करना चाहिए जिसके लिए इसे प्रारंभ किया गया था। जब कोई ईवेंट बनाया जाता है तो एट्रिब्यूट को गलत. पर इनिशियलाइज़ किया जाना चाहिए |
| [Key](../../aspose.html.dom.events/keyboardevent/key/) { get; } | कुंजी दबाए गए कुंजी का कुंजी मान रखती है। यदि मान में एक मुद्रित प्रतिनिधित्व है, तो यह एक गैर-रिक्त यूनिकोड वर्ण स्ट्रिंग होना चाहिए, जो इस विनिर्देश में परिभाषित कुंजी मान निर्धारित करने के लिए एल्गोरिथम के अनुरूप हो। यदि मान एक नियंत्रण कुंजी है जिसका कोई मुद्रित प्रतिनिधित्व नहीं है, तो यह कुंजी मान सेट में परिभाषित प्रमुख मानों में से एक होना चाहिए, जैसा कि कुंजी मान निर्धारित करने के लिए एल्गोरिथम द्वारा निर्धारित किया गया है। कार्यान्वयन जो एक कुंजी की पहचान करने में असमर्थ हैं, उन्हें अज्ञात कुंजी मान का उपयोग करना चाहिए। |
| [Location](../../aspose.html.dom.events/keyboardevent/location/) { get; } | स्थान विशेषता में डिवाइस पर कुंजी के तार्किक स्थान का संकेत होता है। |
| [MetaKey](../../aspose.html.dom.events/keyboardevent/metakey/) { get; } | सच है अगर मेटा (मेटा) कुंजी संशोधक सक्रिय था। |
| [Repeat](../../aspose.html.dom.events/keyboardevent/repeat/) { get; } | सच है अगर कुंजी को निरंतर तरीके से दबाया गया है। एक कुंजी को दबाए रखने से सिस्टम कॉन्फ़िगरेशन द्वारा निर्धारित दर पर, इनपुट से पहले, इनपुट से पहले, इस क्रम में इनपुट की घटनाओं को दोहराने में परिणाम होना चाहिए। उन मोबाइल उपकरणों के लिए जिनमें लॉन्ग-की-प्रेस व्यवहार होता है, ट्रू मस्ट के रिपीट एट्रिब्यूट वैल्यू वाला पहला महत्वपूर्ण ईवेंट लॉन्ग-की-प्रेस के संकेत के रूप में काम करता है। दोहराना शुरू करने के लिए कुंजी को दबाए जाने की अवधि कॉन्फ़िगरेशन-निर्भर है। |
| [ShiftKey](../../aspose.html.dom.events/keyboardevent/shiftkey/) { get; } | सच है अगर शिफ्ट (शिफ्ट) कुंजी संशोधक सक्रिय था। |
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

## खेत

| नाम | विवरण |
| --- | --- |
| const [DOM_KEY_LOCATION_LEFT](../../aspose.html.dom.events/keyboardevent/dom_key_location_left/) | सक्रिय कुंजी बाएं कुंजी स्थान से उत्पन्न होती है (जब इस कुंजी के लिए एक से अधिक संभावित स्थान होते हैं)। |
| const [DOM_KEY_LOCATION_NUMPAD](../../aspose.html.dom.events/keyboardevent/dom_key_location_numpad/) | कुंजी सक्रियण संख्यात्मक कीपैड पर या संख्यात्मक कीपैड के अनुरूप वर्चुअल कुंजी के साथ उत्पन्न होता है (जब इस कुंजी के लिए एक से अधिक संभावित स्थान होते हैं)। ध्यान दें कि NumLock कुंजी को हमेशा DOM_KEY_LOCATION_STANDARD के स्थान के साथ एन्कोड किया जाना चाहिए। |
| const [DOM_KEY_LOCATION_RIGHT](../../aspose.html.dom.events/keyboardevent/dom_key_location_right/) | कुंजी सक्रियण सही कुंजी स्थान से उत्पन्न हुआ (जब इस कुंजी के लिए एक से अधिक संभावित स्थान हों)। |
| const [DOM_KEY_LOCATION_STANDARD](../../aspose.html.dom.events/keyboardevent/dom_key_location_standard/) | कुंजी सक्रियण को कुंजी के बाएँ या दाएँ संस्करण के रूप में प्रतिष्ठित नहीं किया जाना चाहिए, और (NumLock कुंजी के अलावा) संख्यात्मक कीपैड से उत्पन्न नहीं हुआ (या संख्यात्मक कीपैड के अनुरूप वर्चुअल कुंजी से उत्पन्न नहीं हुआ)। |

### यह सभी देखें

* class [UIEvent](../uievent/)
* नाम स्थान [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* सभा [Aspose.HTML](../../)



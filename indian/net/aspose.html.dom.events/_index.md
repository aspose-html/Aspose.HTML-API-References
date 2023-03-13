---
title: Aspose.Html.Dom.Events
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: द Aspose.Html.Dom.Events नेमस्पेस DOM अपडेटंग से संबंधत कस भ इवेंट के लए ऑब्जेक्ट प्रदन करत है इसमें वशेष प्रसंगक जनकर अवलकन क सदस्यत शमल है ज घटन के सथसथ कस्टम इवेंट नर्मण से जुड़ है
type: docs
weight: 80
url: /hi/net/aspose.html.dom.events/
---
द **Aspose.Html.Dom.Events** नेमस्पेस DOM अपडेटिंग से संबंधित किसी भी इवेंट के लिए ऑब्जेक्ट प्रदान करता है। इसमें विशेष प्रासंगिक जानकारी अवलोकन की सदस्यता शामिल है जो घटना के साथ-साथ कस्टम इवेंट निर्माण से जुड़ी है।

## कक्षाओं

| कक्षा | विवरण |
| --- | --- |
| [CustomEvent](./customevent/) | कस्टमइवेंट इंटरफ़ेस का उपयोग करने वाले ईवेंट का उपयोग कस्टम डेटा ले जाने के लिए किया जा सकता है. |
| [DocumentLoadErrorEvent](./documentloaderrorevent/) | द[`DocumentLoadErrorEvent`](../aspose.html.dom.events/documentloaderrorevent/) तब होता है जब अनुरोधित संसाधन उपलब्ध नहीं होता है। |
| [DOMEventHandler](./domeventhandler/) | इवेंट हैंडलिंग के लिए कॉलबैक का प्रतिनिधित्व करता है। |
| [ErrorEvent](./errorevent/) | द[`ErrorEvent`](../aspose.html.dom.events/errorevent/) रनटाइम के दौरान हुई त्रुटियों के बारे में प्रासंगिक जानकारी प्रदान करता है। |
| [Event](./event/) | द[`Event`](../aspose.html.dom.events/event/) ईवेंट को संसाधित करने वाले हैंडलर को ईवेंट के बारे में प्रासंगिक जानकारी प्रदान करने के लिए उपयोग किया जाता है। |
| [FocusEvent](./focusevent/) | फोकसइवेंट इंटरफ़ेस फोकस इवेंट्स से जुड़ी विशिष्ट प्रासंगिक जानकारी प्रदान करता है। |
| [InputEvent](./inputevent/) | जब भी DOM को अपडेट किया जा रहा होता है तो इनपुट इवेंट नोटिफिकेशन के रूप में भेजे जाते हैं। |
| [KeyboardEvent](./keyboardevent/) | कीबोर्डइवेंट इंटरफ़ेस कीबोर्ड उपकरणों से संबंधित विशिष्ट प्रासंगिक जानकारी प्रदान करता है। प्रत्येक कीबोर्ड ईवेंट एक मान का उपयोग करके एक कुंजी का संदर्भ देता है। कुंजीपटल घटनाओं को सामान्यतः उस तत्व पर निर्देशित किया जाता है जिसमें फोकस होता है। |
| [MouseEvent](./mouseevent/) | माउसइवेंट इंटरफ़ेस माउस इवेंट्स से संबंधित विशिष्ट प्रासंगिक जानकारी प्रदान करता है। |
| [UIEvent](./uievent/) | UIEvent इंटरफ़ेस उपयोगकर्ता इंटरफ़ेस ईवेंट से संबंधित विशिष्ट प्रासंगिक जानकारी प्रदान करता है। |
| [WheelEvent](./wheelevent/) | WheelEvent इंटरफ़ेस व्हील ईवेंट से संबंधित विशिष्ट प्रासंगिक जानकारी प्रदान करता है। WheelEvent इंटरफ़ेस का उदाहरण बनाने के लिए, WheelEvent कंस्ट्रक्टर का उपयोग करें, एक वैकल्पिक WheelEventInit डिक्शनरी पास करें. |
## इंटरफेस

| इंटरफेस | विवरण |
| --- | --- |
| [IDocumentEvent](./idocumentevent/) | द[`IDocumentEvent`](../aspose.html.dom.events/idocumentevent/) इंटरफ़ेस एक तंत्र प्रदान करता है जिसके द्वारा उपयोगकर्ता एक बना सकता है[`Event`](../aspose.html.dom.events/event/) कार्यान्वयन द्वारा समर्थित एक प्रकार का। |
| [IEventListener](./ieventlistener/) | द[`IEventListener`](../aspose.html.dom.events/ieventlistener/)इंटरफ़ेस घटनाओं को संभालने के लिए प्राथमिक तरीका है। उपयोगकर्ता इसे लागू करते हैं[`IEventListener`](../aspose.html.dom.events/ieventlistener/) इंटरफ़ेस और उनके श्रोता को एक पर पंजीकृत करें[`EventTarget`](../aspose.html.dom/eventtarget/) का उपयोग[`AddEventListener`](../aspose.html.dom/eventtarget/addeventlistener/) विधि. उपयोगकर्ताओं को भी हटा देना चाहिए[`IEventListener`](../aspose.html.dom.events/ieventlistener/) उसमें से[`EventTarget`](../aspose.html.dom/eventtarget/) श्रोता का उपयोग पूरा करने के बाद। |
| [IEventTarget](./ieventtarget/) | द[`EventTarget`](../aspose.html.dom/eventtarget/) इंटरफ़ेस सभी नोड्स द्वारा एक कार्यान्वयन में कार्यान्वित किया जाता है जो DOM इवेंट मॉडल का समर्थन करता है। एक[`EventTarget`](../aspose.html.dom/eventtarget/) और उस पर घटनाओं का प्रेषण[`IEventTarget`](../aspose.html.dom.events/ieventtarget/) . |



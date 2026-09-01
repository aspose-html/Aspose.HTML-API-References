---
title: "TimeEvent क्लास"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.dom.svg.events.TimeEvent क्लास। TimeEvent इंटरफ़ेस टाइम इवेंट्स से संबंधित विशिष्ट संदर्भात्मक जानकारी प्रदान करता है। विभिन्न प्रकार के इवेंट्स जो हो सकते हैं वे beginEvent, endEvent और repeatEvent हैं।"
type: docs

url: /hi/java/com.aspose.html.dom.svg.events/timeevent/
---
## TimeEvent class

TimeEvent इंटरफ़ेस टाइम इवेंट्स से संबंधित विशिष्ट संदर्भात्मक जानकारी प्रदान करता है। उत्पन्न हो सकने वाले विभिन्न प्रकार के इवेंट्स हैं: beginEvent, endEvent और repeatEvent।

```java
public class TimeEvent : Event
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) यह संकेत देने के लिए उपयोग किया जाता है कि कोई इवेंट बबलिंग इवेंट है या नहीं। यदि इवेंट बबल कर सकता है तो मान true है, अन्यथा मान false है। |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) यह संकेत देने के लिए उपयोग किया जाता है कि कोई इवेंट अपनी डिफ़ॉल्ट कार्रवाई को रोक सकता है या नहीं। यदि डिफ़ॉल्ट कार्रवाई को रोका जा सकता है तो मान true है, अन्यथा मान false है। |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) का उपयोग यह संकेत करने के लिए किया जाता है कि कौन सा [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/) जिसका [`IEventListener`](../../com.aspose.html.dom.events/ieventlistener/) वर्तमान में प्रोसेस हो रहा है। यह विशेष रूप से कैप्चरिंग और बबbling के दौरान उपयोगी है। |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) यदि preventDefault() को तब बुलाया गया जब cancelable एट्रिब्यूट का मान true हो, तो true लौटाता है, अन्यथा false। |
| [getDetail](../../com.aspose.html.dom.svg.events/timeevent/detail/) इवेंट के बारे में कुछ विस्तृत जानकारी निर्दिष्ट करता है, इवेंट के प्रकार पर निर्भर करता है। इस इवेंट प्रकार के लिए, एनीमेशन की पुनरावृत्ति संख्या दर्शाता है। |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) यह संकेत देने के लिए उपयोग किया जाता है कि इवेंट फ्लो का कौन सा चरण वर्तमान में मूल्यांकन किया जा रहा है। |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) isTrusted विशेषता को वह मान लौटाना चाहिए जो इसे आरंभ किया गया था। जब कोई इवेंट बनाया जाता है तो इस विशेषता को false पर आरंभ किया जाना चाहिए। |
| [getTarget](../../com.aspose.html.dom.events/event/target/) का उपयोग यह संकेत करने के लिए किया जाता है कि इवेंट मूल रूप से किस [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/) को डिस्पैच किया गया था। |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) इवेंट के निर्माण के समय (एपोक से मिलीसेकंड में) को निर्दिष्ट करने के लिए उपयोग किया जाता है। कुछ सिस्टम इस जानकारी प्रदान नहीं कर सकते, इसलिए timeStamp का मान सभी इवेंट्स के लिए उपलब्ध नहीं हो सकता। जब उपलब्ध नहीं हो, तो 0 मान लौटाया जाएगा। एपोक समय के उदाहरण हैं सिस्टम शुरू होने का समय या 0:0:0 UTC 1 जनवरी 1970। |
| [getType](../../com.aspose.html.dom.events/event/type/) इवेंट का नाम (केस-इंसेंसिटिव)। नाम एक XML नाम होना चाहिए। |
| [getView](../../com.aspose.html.dom.svg.events/timeevent/view/) view एट्रिब्यूट यह पहचानता है कि इवेंट किस AbstractView [DOM2VIEWS] से उत्पन्न हुआ था। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | यह मेथड ECMAScript ऑब्जेक्ट को प्राप्त करने के लिए उपयोग किया जाता है। |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | यह [`InitEvent`](../../com.aspose.html.dom.events/event/initevent/) मेथड का उपयोग एक [`Event`](../../com.aspose.html.dom.events/event/) को प्रारंभ करने के लिए किया जाता है जो [`IDocumentEvent`](../../com.aspose.html.dom.events/idocumentevent/) इंटरफ़ेस के माध्यम से बनाया गया है। |
| [initTimeEvent](../../com.aspose.html.dom.svg.events/timeevent/inittimeevent/)(String, IAbstractView, long) | initTimeEvent मेथड का उपयोग DocumentEvent इंटरफ़ेस के माध्यम से बनाए गए TimeEvent के मान को प्रारंभ करने के लिए किया जाता है। यह मेथड केवल तब कॉल किया जा सकता है जब TimeEvent को dispatchEvent मेथड के द्वारा डिस्पैच किया जाना बाकी हो, हालांकि आवश्यक होने पर इस चरण के दौरान इसे कई बार कॉल किया जा सकता है। यदि कई बार कॉल किया जाता है, तो अंतिम कॉल को प्राथमिकता दी जाती है। |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | यदि कोई इवेंट रद्द करने योग्य है, तो [`PreventDefault`](../../com.aspose.html.dom.events/event/preventdefault/) मेथड का उपयोग यह दर्शाने के लिए किया जाता है कि इवेंट को रद्द किया जाना है, अर्थात इवेंट के परिणामस्वरूप लागू द्वारा सामान्यतः ली जाने वाली कोई भी डिफ़ॉल्ट कार्रवाई नहीं होगी। |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Invoking this method prevents event from reaching any event listeners registered after the current one and when dispatched in a tree also prevents event from reaching any other objects. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | यह [`StopPropagation`](../../com.aspose.html.dom.events/event/stoppropagation/) मेथड का उपयोग इवेंट फ्लो के दौरान इवेंट के आगे प्रसार को रोकने के लिए किया जाता है। |

### संबंधित देखें

* class [Event](../../com.aspose.html.dom.events/event/)
* package [com.aspose.html.dom.svg.events](../../com.aspose.html.dom.svg.events/)
* package [Aspose.HTML](../../)

---
title: "UIEvent Class"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.dom.events.UIEvent class. The UIEvent interface provides specific contextual information associated with User Interface events"
type: docs

url: /hi/java/com.aspose.html.dom.events/uievent/
---
## UIEvent class

UIEvent इंटरफ़ेस उपयोगकर्ता इंटरफ़ेस इवेंट्स से संबंधित विशिष्ट संदर्भात्मक जानकारी प्रदान करता है।

```java
public class UIEvent : Event
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [UIEvent](uievent/#constructor)(String) | Initializes a new instance of the `UIEvent` class. |
| [UIEvent](uievent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) यह संकेत देने के लिए उपयोग किया जाता है कि कोई इवेंट बबलिंग इवेंट है या नहीं। यदि इवेंट बबल कर सकता है तो मान true है, अन्यथा मान false है। |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) यह संकेत देने के लिए उपयोग किया जाता है कि कोई इवेंट अपनी डिफ़ॉल्ट कार्रवाई को रोक सकता है या नहीं। यदि डिफ़ॉल्ट कार्रवाई को रोका जा सकता है तो मान true है, अन्यथा मान false है। |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) यह संकेत देने के लिए उपयोग किया जाता है कि कौन सा [`IEventTarget`](../ieventtarget/) है, जिसके [`IEventListener`](../ieventlistener/) वर्तमान में प्रोसेस हो रहे हैं। यह कैप्चरिंग और बबलिंग के दौरान विशेष रूप से उपयोगी है। |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) यदि preventDefault() को तब बुलाया गया जब cancelable एट्रिब्यूट का मान true हो, तो true लौटाता है, अन्यथा false। |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) इवेंट के प्रकार के आधार पर इवेंट के बारे में कुछ विस्तृत जानकारी निर्दिष्ट करता है। |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) यह संकेत देने के लिए उपयोग किया जाता है कि इवेंट फ्लो का कौन सा चरण वर्तमान में मूल्यांकन किया जा रहा है। |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) isTrusted विशेषता को वह मान लौटाना चाहिए जो इसे आरंभ किया गया था। जब कोई इवेंट बनाया जाता है तो इस विशेषता को false पर आरंभ किया जाना चाहिए। |
| [getTarget](../../com.aspose.html.dom.events/event/target/) `IEventTarget` को संकेत करने के लिए उपयोग किया जाता है, जिससे इवेंट मूल रूप से प्रेषित किया गया था। |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) इवेंट के निर्माण के समय (एपोक से मिलीसेकंड में) को निर्दिष्ट करने के लिए उपयोग किया जाता है। कुछ सिस्टम इस जानकारी प्रदान नहीं कर सकते, इसलिए timeStamp का मान सभी इवेंट्स के लिए उपलब्ध नहीं हो सकता। जब उपलब्ध नहीं हो, तो 0 मान लौटाया जाएगा। एपोक समय के उदाहरण हैं सिस्टम शुरू होने का समय या 0:0:0 UTC 1 जनवरी 1970। |
| [getType](../../com.aspose.html.dom.events/event/type/) इवेंट का नाम (केस-इंसेंसिटिव)। नाम एक XML नाम होना चाहिए। |
| [getView](../../com.aspose.html.dom.events/uievent/view/) view विशेषता उस विंडो को पहचानती है जिससे इवेंट उत्पन्न हुआ था। इस विशेषता का अनआरंभित मान null होना चाहिए। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | यह मेथड ECMAScript ऑब्जेक्ट को प्राप्त करने के लिए उपयोग किया जाता है। |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | The [`InitEvent`](../event/initevent/) मेथड का उपयोग उन [`Event`](../event/) के मान को आरंभ करने के लिए किया जाता है जो [`IDocumentEvent`](../idocumentevent/) इंटरफ़ेस के माध्यम से बनाए गए हैं। |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | If an event is cancelable, the [`PreventDefault`](../event/preventdefault/) method is used to signify that the event is to be canceled, meaning any default action normally taken by the implementation as a result of the event will not occur. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Invoking this method prevents event from reaching any event listeners registered after the current one and when dispatched in a tree also prevents event from reaching any other objects. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | The [`StopPropagation`](../event/stoppropagation/) method is used prevent further propagation of an event during event flow. |

### संबंधित देखें

* class [Event](../event/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)

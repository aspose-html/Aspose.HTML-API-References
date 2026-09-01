---
title: "इवेंट क्लास"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.dom.events.Event क्लास। यह इवेंट के बारे में संदर्भात्मक जानकारी प्रदान करने के लिए उपयोग किया जाता है, जिसे इवेंट प्रोसेस करने वाला हैंडलर प्राप्त करता है।"
type: docs

url: /hi/java/com.aspose.html.dom.events/event/
---
## Event class

इसे इवेंट को प्रोसेस करने वाले हैंडलर को इवेंट के बारे में संदर्भात्मक जानकारी प्रदान करने के लिए उपयोग किया जाता है।

```java
public class Event : DOMObject
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Event](event/#constructor)(String) | `Event` क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Event](event/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) यह संकेत देने के लिए उपयोग किया जाता है कि कोई इवेंट बबलिंग इवेंट है या नहीं। यदि इवेंट बबल कर सकता है तो मान true है, अन्यथा मान false है। |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) यह संकेत देने के लिए उपयोग किया जाता है कि कोई इवेंट अपनी डिफ़ॉल्ट कार्रवाई को रोक सकता है या नहीं। यदि डिफ़ॉल्ट कार्रवाई को रोका जा सकता है तो मान true है, अन्यथा मान false है। |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) यह संकेत देने के लिए उपयोग किया जाता है कि कौन सा [`IEventTarget`](../ieventtarget/) है, जिसके [`IEventListener`](../ieventlistener/) वर्तमान में प्रोसेस हो रहे हैं। यह कैप्चरिंग और बबलिंग के दौरान विशेष रूप से उपयोगी है। |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) यदि preventDefault() को तब बुलाया गया जब cancelable एट्रिब्यूट का मान true हो, तो true लौटाता है, अन्यथा false। |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) यह संकेत देने के लिए उपयोग किया जाता है कि इवेंट फ्लो का कौन सा चरण वर्तमान में मूल्यांकन किया जा रहा है। |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) isTrusted विशेषता को वह मान लौटाना चाहिए जो इसे आरंभ किया गया था। जब कोई इवेंट बनाया जाता है तो इस विशेषता को false पर आरंभ किया जाना चाहिए। |
| [getTarget](../../com.aspose.html.dom.events/event/target/) `IEventTarget` को संकेत करने के लिए उपयोग किया जाता है, जिससे इवेंट मूल रूप से प्रेषित किया गया था। |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) इवेंट के निर्माण के समय (एपोक से मिलीसेकंड में) को निर्दिष्ट करने के लिए उपयोग किया जाता है। कुछ सिस्टम इस जानकारी प्रदान नहीं कर सकते, इसलिए timeStamp का मान सभी इवेंट्स के लिए उपलब्ध नहीं हो सकता। जब उपलब्ध नहीं हो, तो 0 मान लौटाया जाएगा। एपोक समय के उदाहरण हैं सिस्टम शुरू होने का समय या 0:0:0 UTC 1 जनवरी 1970। |
| [getType](../../com.aspose.html.dom.events/event/type/) इवेंट का नाम (केस-इंसेंसिटिव)। नाम एक XML नाम होना चाहिए। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | यह मेथड ECMAScript ऑब्जेक्ट को प्राप्त करने के लिए उपयोग किया जाता है। |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | [`InitEvent`](./initevent/) मेथड का उपयोग `[`IDocumentEvent`](../idocumentevent/)` इंटरफ़ेस के माध्यम से बनाए गए `Event` के मान को इनिशियलाइज़ करने के लिए किया जाता है। |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | यदि कोई इवेंट रद्द करने योग्य है, तो [`PreventDefault`](./preventdefault/) मेथड का उपयोग यह संकेत देने के लिए किया जाता है कि इवेंट को रद्द किया जाना है, अर्थात् इवेंट के परिणामस्वरूप इम्प्लीमेंटेशन द्वारा सामान्यतः ली जाने वाली कोई भी डिफ़ॉल्ट कार्रवाई नहीं होगी। |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Invoking this method prevents event from reaching any event listeners registered after the current one and when dispatched in a tree also prevents event from reaching any other objects. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | [`StopPropagation`](./stoppropagation/) मेथड का उपयोग इवेंट फ्लो के दौरान इवेंट के आगे के प्रसार को रोकने के लिए किया जाता है। |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| const [AtTargetPhase](../../com.aspose.html.dom.events/event/attargetphase/) | वर्तमान इवेंट चरण कैप्चरिंग चरण है। |
| const [BubblingPhase](../../com.aspose.html.dom.events/event/bubblingphase/) | वर्तमान इवेंट चरण बबलिंग चरण है। |
| const [CapturingPhase](../../com.aspose.html.dom.events/event/capturingphase/) | इवेंट वर्तमान में लक्ष्य [`IEventTarget`](../ieventtarget/) पर मूल्यांकित किया जा रहा है। |
| const [NonePhase](../../com.aspose.html.dom.events/event/nonephase/) | जो इवेंट्स अभी तक डिस्पैच नहीं हुए हैं, वे इस चरण में होते हैं। |

## Remarks

एक ऑब्जेक्ट जो इसे लागू करता है, आमतौर पर इवेंट हैंडलर को पहला पैरामीटर के रूप में पास किया जाता है। अधिक विशिष्ट संदर्भ जानकारी इवेंट हैंडलरों को अतिरिक्त इंटरफ़ेस को डेराइव करके पास की जाती है, जो सीधे इवेंट के प्रकार से संबंधित जानकारी रखती हैं। ये डेराइव्ड इंटरफ़ेस भी उस ऑब्जेक्ट द्वारा लागू किए जाते हैं जो इवेंट लिस्नर को पास किया जाता है।

### संबंधित देखें

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)

---
title: "InputEvent क्लास"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.dom.events.InputEvent क्लास। इनपुट इवेंट्स को सूचनाओं के रूप में भेजा जाता है जब भी DOM अपडेट हो रहा होता है।"
type: docs

url: /hi/java/com.aspose.html.dom.events/inputevent/
---
## InputEvent class

जब भी DOM अपडेट किया जाता है, इनपुट इवेंट्स को सूचनाओं के रूप में भेजा जाता है।

```java
public class InputEvent : UIEvent
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [InputEvent](inputevent/#constructor)(String) | एक नया `InputEvent` क्लास का उदाहरण प्रारंभ करता है। |
| [InputEvent](inputevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## गुण

| नाम | विवरण |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) यह दर्शाने के लिए उपयोग किया जाता है कि कोई इवेंट बबलिंग इवेंट है या नहीं। यदि इवेंट बबल कर सकता है तो मान true है, अन्यथा मान false है। |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) यह दर्शाने के लिए उपयोग किया जाता है कि कोई इवेंट अपनी डिफ़ॉल्ट कार्रवाई को रोका जा सकता है या नहीं। यदि डिफ़ॉल्ट कार्रवाई को रोका जा सकता है तो मान true है, अन्यथा मान false है। |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) यह दर्शाने के लिए उपयोग किया जाता है कि कौन सा [`IEventTarget`](../ieventtarget/) है, जिसके [`IEventListener`](../ieventlistener/) वर्तमान में प्रोसेस हो रहे हैं। यह कैप्चरिंग और बबलिंग के दौरान विशेष रूप से उपयोगी है। |
| [getData](../../com.aspose.html.dom.events/inputevent/data/) डेटा इनपुट मेथड द्वारा उत्पन्न अक्षरों का मान रखता है। यह एक एकल यूनिकोड अक्षर या यूनिकोड अक्षरों की गैर-खाली श्रृंखला हो सकता है [Unicode]। अक्षरों को यूनिकोड नॉर्मलाइज़ेशन फॉर्म NFC के अनुसार सामान्यीकृत किया जाना चाहिए, जैसा कि [UAX15] में परिभाषित है। यह विशेषता खाली स्ट्रिंग भी रख सकती है। |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) यदि cancelable एट्रिब्यूट का मान true हो और preventDefault() को बुलाया गया हो तो true लौटाता है, अन्यथा false। |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) इवेंट के प्रकार के आधार पर इवेंट के बारे में कुछ विस्तृत जानकारी निर्दिष्ट करता है। |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) यह दर्शाने के लिए उपयोग किया जाता है कि इवेंट फ्लो का कौन सा चरण वर्तमान में मूल्यांकन किया जा रहा है। |
| [getIsComposing](../../com.aspose.html.dom.events/inputevent/iscomposing/) यदि इनपुट इवेंट एक कंपोज़िशन सत्र का हिस्सा है, अर्थात् compositionstart इवेंट के बाद और संबंधित compositionend इवेंट से पहले, तो यह true होगा। इस विशेषता का अनइनिशियलाइज़्ड मान अवश्य false होना चाहिए। |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) isTrusted एट्रिब्यूट को वह मान लौटाना चाहिए जिससे इसे प्रारंभ किया गया था। जब कोई इवेंट बनाया जाता है तो एट्रिब्यूट को false पर प्रारंभ किया जाना चाहिए। |
| [getTarget](../../com.aspose.html.dom.events/event/target/) इसका उपयोग उस [`IEventTarget`](../ieventtarget/) को इंगित करने के लिए किया जाता है, जिससे इवेंट मूल रूप से डिस्पैच किया गया था। |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) इसका उपयोग उस समय (epoch के सापेक्ष मिलीसेकंड में) को निर्दिष्ट करने के लिए किया जाता है, जिस समय इवेंट बनाया गया था। चूँकि कुछ सिस्टम यह जानकारी प्रदान नहीं कर सकते, सभी इवेंट्स के लिए timeStamp का मान उपलब्ध नहीं हो सकता। जब उपलब्ध नहीं हो, तो 0 का मान लौटाया जाएगा। epoch समय के उदाहरण हैं सिस्टम की शुरुआत का समय या 0:0:0 UTC 1 जनवरी 1970। |
| [getType](../../com.aspose.html.dom.events/event/type/) इवेंट का नाम (case-insensitive) है। नाम एक XML नाम होना चाहिए। |
| [getView](../../com.aspose.html.dom.events/uievent/view/) view एट्रिब्यूट उस विंडो को पहचानता है जिससे इवेंट उत्पन्न हुआ था। इस एट्रिब्यूट का अनप्रारंभित मान हमेशा null होना चाहिए। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | यह मेथड ECMAScript ऑब्जेक्ट को पुनः प्राप्त करने के लिए उपयोग किया जाता है। |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | The [`InitEvent`](../event/initevent/) मेथड का उपयोग उस [`Event`](../event/) के मान को प्रारंभ करने के लिए किया जाता है, जो [`IDocumentEvent`](../idocumentevent/) इंटरफ़ेस के माध्यम से बनाया गया हो। |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | यदि इवेंट रद्द करने योग्य है, तो [`PreventDefault`](../event/preventdefault/) मेथड का उपयोग यह संकेत देने के लिए किया जाता है कि इवेंट को रद्द किया जाना है, अर्थात् इवेंट के परिणामस्वरूप लागू होने वाली कोई भी डिफ़ॉल्ट कार्रवाई नहीं होगी। |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | इस मेथड को कॉल करने से इवेंट वर्तमान लिस्नर के बाद पंजीकृत किसी भी इवेंट लिस्नर तक नहीं पहुँच पाएगा और ट्री में डिस्पैच होने पर इवेंट किसी अन्य ऑब्जेक्ट तक नहीं पहुँचेगा। |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | The [`StopPropagation`](../event/stoppropagation/) मेथड का उपयोग इवेंट फ्लो के दौरान इवेंट के आगे प्रसार को रोकने के लिए किया जाता है। |

### संबंधित देखें

* class [UIEvent](../uievent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)

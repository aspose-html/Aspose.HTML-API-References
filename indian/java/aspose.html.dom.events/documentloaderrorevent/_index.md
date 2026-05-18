---
title: "DocumentLoadErrorEvent क्लास"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.dom.events.DocumentLoadErrorEvent क्लास। DocumentLoadErrorEvent तब उत्पन्न होता है जब अनुरोधित संसाधन उपलब्ध नहीं होता।"
type: docs

url: /hi/java/com.aspose.html.dom.events/documentloaderrorevent/
---
## DocumentLoadErrorEvent class

DocumentLoadErrorEvent तब उत्पन्न होता है जब अनुरोधित संसाधन उपलब्ध नहीं होता।

```java
public class DocumentLoadErrorEvent : ErrorEvent
```

## गुण

| नाम | विवरण |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) यह दर्शाने के लिए उपयोग किया जाता है कि कोई इवेंट बबलिंग इवेंट है या नहीं। यदि इवेंट बबल कर सकता है तो मान true है, अन्यथा मान false है। |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) यह दर्शाने के लिए उपयोग किया जाता है कि कोई इवेंट अपनी डिफ़ॉल्ट कार्रवाई को रोका जा सकता है या नहीं। यदि डिफ़ॉल्ट कार्रवाई को रोका जा सकता है तो मान true है, अन्यथा मान false है। |
| [getColNo](../../com.aspose.html.dom.events/errorevent/colno/) colno एट्रिब्यूट को उस मान को लौटाना चाहिए जिससे यह प्रारंभ किया गया था। जब ऑब्जेक्ट बनाया जाता है, तो इस एट्रिब्यूट को शून्य पर प्रारंभ किया जाना चाहिए। यह स्क्रिप्ट में जहाँ त्रुटि हुई, उस कॉलम नंबर को दर्शाता है। |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) यह दर्शाने के लिए उपयोग किया जाता है कि कौन सा [`IEventTarget`](../ieventtarget/) है, जिसके [`IEventListener`](../ieventlistener/) वर्तमान में प्रोसेस हो रहे हैं। यह कैप्चरिंग और बबलिंग के दौरान विशेष रूप से उपयोगी है। |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) यदि cancelable एट्रिब्यूट का मान true हो और preventDefault() को बुलाया गया हो तो true लौटाता है, अन्यथा false। |
| [getError](../../com.aspose.html.dom.events/errorevent/error/) error एट्रिब्यूट को उस मान को लौटाना चाहिए जिससे यह प्रारंभ किया गया था। जब ऑब्जेक्ट बनाया जाता है, तो इस एट्रिब्यूट को null पर प्रारंभ किया जाना चाहिए। जहाँ उपयुक्त हो, इसे त्रुटि का प्रतिनिधित्व करने वाले ऑब्जेक्ट पर सेट किया जाता है (जैसे अनकैच्ड DOM एक्सेप्शन के मामले में एक्सेप्शन ऑब्जेक्ट)। |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) यह दर्शाने के लिए उपयोग किया जाता है कि इवेंट फ्लो का कौन सा चरण वर्तमान में मूल्यांकन किया जा रहा है। |
| [getFileName](../../com.aspose.html.dom.events/errorevent/filename/) filename एट्रिब्यूट को उस मान को लौटाना चाहिए जिससे यह प्रारंभ किया गया था। जब ऑब्जेक्ट बनाया जाता है, तो इस एट्रिब्यूट को खाली स्ट्रिंग पर प्रारंभ किया जाना चाहिए। यह उस स्क्रिप्ट का पूर्ण URL दर्शाता है जिसमें त्रुटि मूल रूप से हुई थी। |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) isTrusted एट्रिब्यूट को वह मान लौटाना चाहिए जिससे इसे प्रारंभ किया गया था। जब कोई इवेंट बनाया जाता है तो एट्रिब्यूट को false पर प्रारंभ किया जाना चाहिए। |
| [getLineNo](../../com.aspose.html.dom.events/errorevent/lineno/) lineno एट्रिब्यूट को वह मान लौटाना चाहिए जिससे इसे प्रारंभ किया गया था। जब ऑब्जेक्ट बनाया जाता है, तो इस एट्रिब्यूट को शून्य (zero) पर प्रारंभ किया जाना चाहिए। यह स्क्रिप्ट में त्रुटि हुई लाइन नंबर को दर्शाता है। |
| [getMessage](../../com.aspose.html.dom.events/errorevent/message/) message एट्रिब्यूट को वह मान लौटाना चाहिए जिससे इसे प्रारंभ किया गया था। जब ऑब्जेक्ट बनाया जाता है, तो इस एट्रिब्यूट को खाली स्ट्रिंग से प्रारंभ किया जाना चाहिए। यह त्रुटि संदेश को दर्शाता है। |
| [getTarget](../../com.aspose.html.dom.events/event/target/) इसका उपयोग उस [`IEventTarget`](../ieventtarget/) को इंगित करने के लिए किया जाता है, जिससे इवेंट मूल रूप से डिस्पैच किया गया था। |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) इसका उपयोग उस समय (epoch के सापेक्ष मिलीसेकंड में) को निर्दिष्ट करने के लिए किया जाता है, जिस समय इवेंट बनाया गया था। चूँकि कुछ सिस्टम यह जानकारी प्रदान नहीं कर सकते, सभी इवेंट्स के लिए timeStamp का मान उपलब्ध नहीं हो सकता। जब उपलब्ध नहीं हो, तो 0 का मान लौटाया जाएगा। epoch समय के उदाहरण हैं सिस्टम की शुरुआत का समय या 0:0:0 UTC 1 जनवरी 1970। |
| [getType](../../com.aspose.html.dom.events/event/type/) इवेंट का नाम (case-insensitive) है। नाम एक XML नाम होना चाहिए। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | यह मेथड ECMAScript ऑब्जेक्ट को पुनः प्राप्त करने के लिए उपयोग किया जाता है। |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | The [`InitEvent`](../event/initevent/) मेथड का उपयोग उस [`Event`](../event/) के मान को प्रारंभ करने के लिए किया जाता है, जो [`IDocumentEvent`](../idocumentevent/) इंटरफ़ेस के माध्यम से बनाया गया हो। |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | यदि इवेंट रद्द करने योग्य है, तो [`PreventDefault`](../event/preventdefault/) मेथड का उपयोग यह संकेत देने के लिए किया जाता है कि इवेंट को रद्द किया जाना है, अर्थात् इवेंट के परिणामस्वरूप लागू होने वाली कोई भी डिफ़ॉल्ट कार्रवाई नहीं होगी। |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | इस मेथड को कॉल करने से इवेंट वर्तमान लिस्नर के बाद पंजीकृत किसी भी इवेंट लिस्नर तक नहीं पहुँच पाएगा और ट्री में डिस्पैच होने पर इवेंट किसी अन्य ऑब्जेक्ट तक नहीं पहुँचेगा। |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | The [`StopPropagation`](../event/stoppropagation/) मेथड का उपयोग इवेंट फ्लो के दौरान इवेंट के आगे प्रसार को रोकने के लिए किया जाता है। |

### संबंधित देखें

* class [ErrorEvent](../errorevent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)

---
title: "WheelEvent क्लास"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.dom.events.WheelEvent क्लास। WheelEvent इंटरफ़ेस व्हील इवेंट्स से संबंधित विशिष्ट संदर्भात्मक जानकारी प्रदान करता है। WheelEvent इंटरफ़ेस का एक उदाहरण बनाने के लिए WheelEvent कन्स्ट्रक्टर का उपयोग करें और एक वैकल्पिक WheelEventInit शब्दकोश पास करें।"
type: docs

url: /hi/java/com.aspose.html.dom.events/wheelevent/
---
## WheelEvent class

WheelEvent इंटरफ़ेस व्हील इवेंट्स से संबंधित विशिष्ट संदर्भात्मक जानकारी प्रदान करता है। WheelEvent इंटरफ़ेस का एक इंस्टेंस बनाने के लिए, WheelEvent कंस्ट्रक्टर का उपयोग करें और वैकल्पिक WheelEventInit डिक्शनरी पास करें।

```java
public class WheelEvent : MouseEvent
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [WheelEvent](wheelevent/#constructor)(String) | `WheelEvent` क्लास का नया उदाहरण प्रारंभ करता है। |
| [WheelEvent](wheelevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## गुण

| नाम | विवरण |
| --- | --- |
| [getAltKey](../../com.aspose.html.dom.events/mouseevent/altkey/) altKey विशेषता को देखें। |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) यह दर्शाने के लिए उपयोग किया जाता है कि कोई इवेंट बबलिंग इवेंट है या नहीं। यदि इवेंट बबल कर सकता है तो मान true है, अन्यथा मान false है। |
| [getButton](../../com.aspose.html.dom.events/mouseevent/button/) माउस बटन के दबाने या रिलीज़ होने से उत्पन्न माउस इवेंट्स के दौरान, बटन का उपयोग यह संकेत देने के लिए अनिवार्य है कि कौन सा पॉइंटर डिवाइस बटन स्थिति बदल गया। |
| [getButtons](../../com.aspose.html.dom.events/mouseevent/buttons/) किसी भी माउस इवेंट के दौरान, बटन्स का उपयोग यह संकेत देने के लिए अनिवार्य है कि वर्तमान में कौन सा माउस बटनों का संयोजन दबा हुआ है, जिसे बिटमास्क के रूप में व्यक्त किया जाता है। |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) यह दर्शाने के लिए उपयोग किया जाता है कि कोई इवेंट अपनी डिफ़ॉल्ट कार्रवाई को रोका जा सकता है या नहीं। यदि डिफ़ॉल्ट कार्रवाई को रोका जा सकता है तो मान true है, अन्यथा मान false है। |
| [getClientX](../../com.aspose.html.dom.events/mouseevent/clientx/) इवेंट के घटित होने पर क्षैतिज निर्देशांक, जो इवेंट से जुड़े व्यूपोर्ट के सापेक्ष होता है। |
| [getClientY](../../com.aspose.html.dom.events/mouseevent/clienty/) इवेंट के घटित होने पर लंबवत निर्देशांक, जो इवेंट से जुड़े व्यूपोर्ट के सापेक्ष होता है। |
| [getCtrlKey](../../com.aspose.html.dom.events/mouseevent/ctrlkey/) ctrlKey विशेषता को देखें। |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) यह दर्शाने के लिए उपयोग किया जाता है कि कौन सा [`IEventTarget`](../ieventtarget/) है, जिसके [`IEventListener`](../ieventlistener/) वर्तमान में प्रोसेस हो रहे हैं। यह कैप्चरिंग और बबलिंग के दौरान विशेष रूप से उपयोगी है। |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) यदि cancelable एट्रिब्यूट का मान true हो और preventDefault() को बुलाया गया हो तो true लौटाता है, अन्यथा false। |
| [getDeltaMode](../../com.aspose.html.dom.events/wheelevent/deltamode/) deltaMode गुण डेल्टा मानों की माप इकाइयों का संकेत रखता है। डिफ़ॉल्ट मान DOM_DELTA_PIXEL (पिक्सेल) है। |
| [getDeltaX](../../com.aspose.html.dom.events/wheelevent/deltax/) उन उपयोगकर्ता एजेंट्स में जहाँ व्हील इवेंट की डिफ़ॉल्ट क्रिया स्क्रॉल करना है, मान को x-अक्ष (पिक्सेल, लाइनों, या पृष्ठों में) के माप के रूप में होना चाहिए जिसे इवेंट रद्द न होने पर स्क्रॉल किया जाएगा। अन्यथा, यह कार्यान्वयन-विशिष्ट माप (पिक्सेल, लाइनों, या पृष्ठों में) है जो व्हील डिवाइस की x-अक्ष के चारों ओर गति को दर्शाता है। |
| [getDeltaY](../../com.aspose.html.dom.events/wheelevent/deltay/) उन उपयोगकर्ता एजेंट्स में जहाँ व्हील इवेंट की डिफ़ॉल्ट क्रिया स्क्रॉल करना है, मान को y-अक्ष (पिक्सेल, लाइनों, या पृष्ठों में) के माप के रूप में होना चाहिए जिसे इवेंट रद्द न होने पर स्क्रॉल किया जाएगा। अन्यथा, यह कार्यान्वयन-विशिष्ट माप (पिक्सेल, लाइनों, या पृष्ठों में) है जो व्हील डिवाइस की y-अक्ष के चारों ओर गति को दर्शाता है। |
| [getDeltaZ](../../com.aspose.html.dom.events/wheelevent/deltaz/) उन उपयोगकर्ता एजेंट्स में जहाँ व्हील इवेंट की डिफ़ॉल्ट क्रिया स्क्रॉल करना है, मान को z-अक्ष (पिक्सेल, लाइनों, या पृष्ठों में) के माप के रूप में होना चाहिए जिसे इवेंट रद्द न होने पर स्क्रॉल किया जाएगा। अन्यथा, यह कार्यान्वयन-विशिष्ट माप (पिक्सेल, लाइनों, या पृष्ठों में) है जो व्हील डिवाइस की z-अक्ष के चारों ओर गति को दर्शाता है। |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) इवेंट के प्रकार के आधार पर इवेंट के बारे में कुछ विस्तृत जानकारी निर्दिष्ट करता है। |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) यह दर्शाने के लिए उपयोग किया जाता है कि इवेंट फ्लो का कौन सा चरण वर्तमान में मूल्यांकन किया जा रहा है। |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) isTrusted एट्रिब्यूट को वह मान लौटाना चाहिए जिससे इसे प्रारंभ किया गया था। जब कोई इवेंट बनाया जाता है तो एट्रिब्यूट को false पर प्रारंभ किया जाना चाहिए। |
| [getMetaKey](../../com.aspose.html.dom.events/mouseevent/metakey/) metaKey विशेषता को देखें। |
| [getRelatedTarget](../../com.aspose.html.dom.events/mouseevent/relatedtarget/) किसी UI इवेंट से संबंधित द्वितीयक EventTarget की पहचान करने के लिए उपयोग किया जाता है, इवेंट के प्रकार के आधार पर। |
| [getScreenX](../../com.aspose.html.dom.events/mouseevent/screenx/) वह क्षैतिज निर्देशांक जहाँ इवेंट स्क्रीन निर्देशांक प्रणाली की मूल बिंदु के सापेक्ष हुआ। |
| [getScreenY](../../com.aspose.html.dom.events/mouseevent/screeny/) वह लंबवत निर्देशांक जहाँ इवेंट स्क्रीन निर्देशांक प्रणाली की मूल बिंदु के सापेक्ष हुआ। |
| [getShiftKey](../../com.aspose.html.dom.events/mouseevent/shiftkey/) shiftKey गुण का संदर्भ लें। |
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

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| const [DOM_DELTA_LINE](../../com.aspose.html.dom.events/wheelevent/dom_delta_line/) | डेल्टा की माप इकाइयाँ अवश्य व्यक्तिगत टेक्स्ट लाइनों की होनी चाहिए। यह कई फ़ॉर्म नियंत्रणों के लिए लागू होता है। |
| const [DOM_DELTA_PAGE](../../com.aspose.html.dom.events/wheelevent/dom_delta_page/) | डेल्टा की माप इकाइयाँ अवश्य पृष्ठों की होनी चाहिए, चाहे वह एकल स्क्रीन के रूप में परिभाषित हो या एक सीमित पृष्ठ के रूप में। |
| const [DOM_DELTA_PIXEL](../../com.aspose.html.dom.events/wheelevent/dom_delta_pixel/) | डेल्टा की माप इकाइयाँ अवश्य पिक्सेल की होनी चाहिए। यह अधिकांश ऑपरेटिंग सिस्टम और कार्यान्वयन कॉन्फ़िगरेशन में सबसे सामान्य मामला है। |

### संबंधित देखें

* class [MouseEvent](../mouseevent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)

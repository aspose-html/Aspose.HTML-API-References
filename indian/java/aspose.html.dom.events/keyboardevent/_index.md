---
title: "KeyboardEvent क्लास"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.dom.events.KeyboardEvent क्लास। KeyboardEvent इंटरफ़ेस कीबोर्ड डिवाइसों से संबंधित विशिष्ट संदर्भात्मक जानकारी प्रदान करता है। प्रत्येक कीबोर्ड इवेंट एक मान का उपयोग करके कुंजी को संदर्भित करता है। कीबोर्ड इवेंट आमतौर पर उस तत्व की ओर निर्देशित होते हैं जिसके पास फोकस है।"
type: docs

url: /hi/java/com.aspose.html.dom.events/keyboardevent/
---
## KeyboardEvent class

KeyboardEvent इंटरफ़ेस कीबोर्ड डिवाइसों से संबंधित विशिष्ट संदर्भात्मक जानकारी प्रदान करता है। प्रत्येक कीबोर्ड इवेंट एक मान का उपयोग करके कुंजी को संदर्भित करता है। कीबोर्ड इवेंट्स आमतौर पर उस तत्व की ओर निर्देशित होते हैं जिसका फोकस सक्रिय है।

```java
public class KeyboardEvent : UIEvent
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [KeyboardEvent](keyboardevent/#constructor)(String) | `KeyboardEvent` क्लास का नया इंस्टेंस आरंभ करता है। |
| [KeyboardEvent](keyboardevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [getAltKey](../../com.aspose.html.dom.events/keyboardevent/altkey/) यदि Alt (वैकल्पिक) (या "Option") कुंजी मॉडिफ़ायर सक्रिय था तो true। इस विशेषता का अनआरंभित मान false होना चाहिए। |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) यह संकेत देने के लिए उपयोग किया जाता है कि कोई इवेंट बबलिंग इवेंट है या नहीं। यदि इवेंट बबल कर सकता है तो मान true है, अन्यथा मान false है। |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) यह संकेत देने के लिए उपयोग किया जाता है कि कोई इवेंट अपनी डिफ़ॉल्ट कार्रवाई को रोक सकता है या नहीं। यदि डिफ़ॉल्ट कार्रवाई को रोका जा सकता है तो मान true है, अन्यथा मान false है। |
| [getCode](../../com.aspose.html.dom.events/keyboardevent/code/) कोड एक स्ट्रिंग रखता है जो दबाई जा रही भौतिक कुंजी की पहचान करता है। यह मान वर्तमान कीबोर्ड लेआउट या मॉडिफ़ायर स्थिति से प्रभावित नहीं होता, इसलिए किसी विशेष कुंजी का मान हमेशा समान रहेगा। |
| [getCtrlKey](../../com.aspose.html.dom.events/keyboardevent/ctrlkey/) यदि Control (कंट्रोल) कुंजी मॉडिफ़ायर सक्रिय था तो true। इस विशेषता का अनआरंभित मान false होना चाहिए। |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) यह संकेत देने के लिए उपयोग किया जाता है कि कौन सा [`IEventTarget`](../ieventtarget/) है, जिसके [`IEventListener`](../ieventlistener/) वर्तमान में प्रोसेस हो रहे हैं। यह कैप्चरिंग और बबलिंग के दौरान विशेष रूप से उपयोगी है। |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) यदि preventDefault() को तब बुलाया गया जब cancelable एट्रिब्यूट का मान true हो, तो true लौटाता है, अन्यथा false। |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) इवेंट के प्रकार के आधार पर इवेंट के बारे में कुछ विस्तृत जानकारी निर्दिष्ट करता है। |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) यह संकेत देने के लिए उपयोग किया जाता है कि इवेंट फ्लो का कौन सा चरण वर्तमान में मूल्यांकन किया जा रहा है। |
| [getIsComposing](../../com.aspose.html.dom.events/keyboardevent/iscomposing/) यदि कुंजी इवेंट एक संयोजन सत्र का हिस्सा है, अर्थात compositionstart इवेंट के बाद और संबंधित compositionend इवेंट से पहले, तो true। इस विशेषता का अनआरंभित मान false होना चाहिए। |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) isTrusted विशेषता को वह मान लौटाना चाहिए जो इसे आरंभ किया गया था। जब कोई इवेंट बनाया जाता है तो इस विशेषता को false पर आरंभ किया जाना चाहिए। |
| [getKey](../../com.aspose.html.dom.events/keyboardevent/key/) key दबाई गई कुंजी का मान रखता है। यदि मान का मुद्रित प्रतिनिधित्व है, तो यह एक गैर-खाली यूनिकोड अक्षर स्ट्रिंग होना चाहिए, जो इस विनिर्देशन में परिभाषित एल्गोरिदम के अनुसार हो। यदि मान एक नियंत्रण कुंजी है जिसका कोई मुद्रित प्रतिनिधित्व नहीं है, तो यह कुंजी मान सेट में परिभाषित कुंजी मानों में से एक होना चाहिए, जैसा कि एल्गोरिदम द्वारा निर्धारित है। जिन कार्यान्वयनों को कुंजी पहचानने में असमर्थता है, उन्हें कुंजी मान Unidentified का उपयोग करना चाहिए। |
| [getLocation](../../com.aspose.html.dom.events/keyboardevent/location/) location विशेषता डिवाइस पर कुंजी के तार्किक स्थान का संकेत रखती है। |
| [getMetaKey](../../com.aspose.html.dom.events/keyboardevent/metakey/) यदि meta (Meta) कुंजी मॉडिफ़ायर सक्रिय था तो true। |
| [getRepeat](../../com.aspose.html.dom.events/keyboardevent/repeat/) यदि कुंजी निरंतर दबाई गई है तो true। कुंजी को दबाए रखने से क्रम में keydown, beforeinput, input इवेंट्स दोहराए जाने चाहिए, जिसकी दर सिस्टम कॉन्फ़िगरेशन द्वारा निर्धारित होती है। मोबाइल डिवाइसों में जहाँ लंबी कुंजी दबाने का व्यवहार होता है, repeat विशेषता का मान true वाला पहला कुंजी इवेंट लंबी कुंजी दबाने का संकेत होना चाहिए। दोहराव शुरू करने के लिए कुंजी को दबाए रखने का समय कॉन्फ़िगरेशन पर निर्भर करता है। |
| [getShiftKey](../../com.aspose.html.dom.events/keyboardevent/shiftkey/) यदि Shift (Shift) कुंजी मॉडिफ़ायर सक्रिय था तो true। |
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

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| const [DOM_KEY_LOCATION_LEFT](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_left/) | The key activated originated from the left key location (when there is more than one possible location for this key). |
| const [DOM_KEY_LOCATION_NUMPAD](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_numpad/) | The key activation originated on the numeric keypad or with a virtual key corresponding to the numeric keypad (when there is more than one possible location for this key). Note that the NumLock key should always be encoded with a location of DOM_KEY_LOCATION_STANDARD. |
| const [DOM_KEY_LOCATION_RIGHT](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_right/) | The key activation originated from the right key location (when there is more than one possible location for this key). |
| const [DOM_KEY_LOCATION_STANDARD](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_standard/) | The key activation MUST NOT be distinguished as the left or right version of the key, and (other than the NumLock key) did not originate from the numeric keypad (or did not originate with a virtual key corresponding to the numeric keypad). |

### संबंधित देखें

* class [UIEvent](../uievent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)

---
title: "KeyboardEvent क्लास"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.dom.events.KeyboardEvent क्लास। KeyboardEvent इंटरफ़ेस कीबोर्ड डिवाइसों से संबंधित विशिष्ट संदर्भात्मक जानकारी प्रदान करता है। प्रत्येक कीबोर्ड इवेंट एक मान का उपयोग करके कुंजी को संदर्भित करता है। कीबोर्ड इवेंट आमतौर पर उस एलिमेंट पर लक्षित होते हैं जिसका फोकस है।"
type: docs

url: /hi/java/com.aspose.html.dom.events/keyboardevent/
---
## KeyboardEvent class

KeyboardEvent इंटरफ़ेस कीबोर्ड डिवाइसों से संबंधित विशिष्ट संदर्भात्मक जानकारी प्रदान करता है। प्रत्येक कीबोर्ड इवेंट एक मान का उपयोग करके कुंजी को संदर्भित करता है। कीबोर्ड इवेंट्स आमतौर पर उस तत्व की ओर निर्देशित होते हैं जिसमें फोकस होता है।

```java
public class KeyboardEvent : UIEvent
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [KeyboardEvent](keyboardevent/#constructor)(String) | `KeyboardEvent` क्लास का नया इंस्टेंस प्रारंभ करता है। |
| [KeyboardEvent](keyboardevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## गुण

| नाम | विवरण |
| --- | --- |
| [getAltKey](../../com.aspose.html.dom.events/keyboardevent/altkey/) true यदि Alt (वैकल्पिक) (या \"Option\") कुंजी मोडिफ़ायर सक्रिय था। इस एट्रिब्यूट का अनप्रारंभित मान हमेशा false होना चाहिए। |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) यह दर्शाने के लिए उपयोग किया जाता है कि कोई इवेंट बबलिंग इवेंट है या नहीं। यदि इवेंट बबल कर सकता है तो मान true है, अन्यथा मान false है। |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) यह दर्शाने के लिए उपयोग किया जाता है कि कोई इवेंट अपनी डिफ़ॉल्ट कार्रवाई को रोका जा सकता है या नहीं। यदि डिफ़ॉल्ट कार्रवाई को रोका जा सकता है तो मान true है, अन्यथा मान false है। |
| [getCode](../../com.aspose.html.dom.events/keyboardevent/code/) कोड एक स्ट्रिंग रखता है जो दबाई गई भौतिक कुंजी की पहचान करता है। यह मान वर्तमान कीबोर्ड लेआउट या मोडिफ़ायर स्थिति से प्रभावित नहीं होता, इसलिए किसी विशेष कुंजी का मान हमेशा समान रहेगा। |
| [getCtrlKey](../../com.aspose.html.dom.events/keyboardevent/ctrlkey/) true यदि Control (कंट्रोल) कुंजी मोडिफ़ायर सक्रिय था। इस एट्रिब्यूट का अनप्रारंभित मान हमेशा false होना चाहिए। |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) यह दर्शाने के लिए उपयोग किया जाता है कि कौन सा [`IEventTarget`](../ieventtarget/) है, जिसके [`IEventListener`](../ieventlistener/) वर्तमान में प्रोसेस हो रहे हैं। यह कैप्चरिंग और बबलिंग के दौरान विशेष रूप से उपयोगी है। |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) यदि cancelable एट्रिब्यूट का मान true हो और preventDefault() को बुलाया गया हो तो true लौटाता है, अन्यथा false। |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) इवेंट के प्रकार के आधार पर इवेंट के बारे में कुछ विस्तृत जानकारी निर्दिष्ट करता है। |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) यह दर्शाने के लिए उपयोग किया जाता है कि इवेंट फ्लो का कौन सा चरण वर्तमान में मूल्यांकन किया जा रहा है। |
| [getIsComposing](../../com.aspose.html.dom.events/keyboardevent/iscomposing/) true यदि कुंजी इवेंट एक कंपोज़िशन सत्र का हिस्सा है, अर्थात् compositionstart इवेंट के बाद और संबंधित compositionend इवेंट से पहले। इस एट्रिब्यूट का अनप्रारंभित मान हमेशा false होना चाहिए। |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) isTrusted एट्रिब्यूट को वह मान लौटाना चाहिए जिससे इसे प्रारंभ किया गया था। जब कोई इवेंट बनाया जाता है तो एट्रिब्यूट को false पर प्रारंभ किया जाना चाहिए। |
| [getKey](../../com.aspose.html.dom.events/keyboardevent/key/) कुंजी दबाए गए कुंजी का मान रखती है। यदि इस मान का मुद्रित प्रतिनिधित्व है, तो यह एक गैर-खाली यूनिकोड कैरेक्टर स्ट्रिंग होना चाहिए, जो इस विशिष्टता में परिभाषित कुंजी मान निर्धारित करने के एल्गोरिदम के अनुरूप हो। यदि यह एक नियंत्रण कुंजी है जिसका कोई मुद्रित प्रतिनिधित्व नहीं है, तो यह कुंजी मान सेट में परिभाषित कुंजी मानों में से एक होना चाहिए, जैसा कि कुंजी मान निर्धारित करने के एल्गोरिदम द्वारा निर्धारित है। ऐसी कार्यान्वयन जो कुंजी की पहचान नहीं कर सकते, उन्हें कुंजी मान Unidentified का उपयोग करना चाहिए। |
| [getLocation](../../com.aspose.html.dom.events/keyboardevent/location/) location एट्रिब्यूट डिवाइस पर कुंजी के तार्किक स्थान का संकेत रखता है। |
| [getMetaKey](../../com.aspose.html.dom.events/keyboardevent/metakey/) true यदि meta (Meta) कुंजी मोडिफ़ायर सक्रिय था। |
| [getRepeat](../../com.aspose.html.dom.events/keyboardevent/repeat/) true यदि कुंजी निरंतर रूप से दबाई गई है। कुंजी को दबाए रखने से keydown, beforeinput, input इवेंट क्रमशः पुनरावृत्ति में उत्पन्न होने चाहिए, जिसकी दर सिस्टम कॉन्फ़िगरेशन द्वारा निर्धारित होती है। मोबाइल डिवाइसों में जहाँ लंबी कुंजी दबाव व्यवहार होता है, repeat एट्रिब्यूट true वाले पहले कुंजी इवेंट को लंबी कुंजी दबाव का संकेत माना जाना चाहिए। कुंजी को दोहराने के लिए आवश्यक दबाव अवधि कॉन्फ़िगरेशन-निर्भर होती है। |
| [getShiftKey](../../com.aspose.html.dom.events/keyboardevent/shiftkey/) true यदि shift (Shift) कुंजी मोडिफ़ायर सक्रिय था। |
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
| const [DOM_KEY_LOCATION_LEFT](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_left/) | कुंजी सक्रिय बाएँ कुंजी स्थान से उत्पन्न हुई (जब इस कुंजी के लिए एक से अधिक संभावित स्थान हों)। |
| const [DOM_KEY_LOCATION_NUMPAD](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_numpad/) | की सक्रियता संख्यात्मक कीपैड पर या संख्यात्मक कीपैड के अनुरूप एक वर्चुअल कुंजी के साथ उत्पन्न हुई (जब इस कुंजी के लिए एक से अधिक संभावित स्थान हों)। ध्यान दें कि NumLock कुंजी को हमेशा DOM_KEY_LOCATION_STANDARD स्थान के साथ एन्कोड किया जाना चाहिए। |
| const [DOM_KEY_LOCATION_RIGHT](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_right/) | की सक्रियता दाएँ कुंजी स्थान से उत्पन्न हुई (जब इस कुंजी के लिए एक से अधिक संभावित स्थान हों)। |
| const [DOM_KEY_LOCATION_STANDARD](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_standard/) | की सक्रियता को बाएँ या दाएँ संस्करण के रूप में अलग नहीं किया जाना चाहिए, और (NumLock कुंजी को छोड़कर) यह संख्यात्मक कीपैड से उत्पन्न नहीं हुई (या संख्यात्मक कीपैड के अनुरूप वर्चुअल कुंजी से उत्पन्न नहीं हुई)। |

### संबंधित देखें

* class [UIEvent](../uievent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)

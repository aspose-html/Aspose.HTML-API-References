---
title: "MediaQueryList क्लास"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.window.MediaQueryList class. MediaQueryList ऑब्जेक्ट दस्तावेज़ पर लागू मीडिया क्वेरी की जानकारी संग्रहीत करता है, जो दस्तावेज़ की स्थिति के विरुद्ध तत्काल और इवेंट‑ड्रिवेन मिलान दोनों का समर्थन करता है। CSSOM View Module विनिर्देशन देखें https//www.w3.org/TR/cssom-view/the-mediaquerylist-interface"
type: docs

url: /hi/java/com.aspose.html.window/mediaquerylist/
---
## MediaQueryList class

एक MediaQueryList ऑब्जेक्ट दस्तावेज़ पर लागू मीडिया क्वेरी की जानकारी संग्रहीत करता है, जिसमें दस्तावेज़ की स्थिति के विरुद्ध तत्काल और इवेंट-ड्रिवेन मिलान दोनों का समर्थन होता है। देखें CSSOM View Module विनिर्देशन: [https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface](https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface)

```java
public class MediaQueryList : EventTarget
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [getDocument](../../com.aspose.html.window/mediaquerylist/document/) कॉन्टेक्स्ट ऑब्जेक्ट का संबंधित दस्तावेज़। |
| [getMatches](../../com.aspose.html.window/mediaquerylist/matches/) एक बूलियन मान जो true लौटाता है यदि दस्तावेज़ वर्तमान में मीडिया क्वेरी सूची से मेल खाता है, अन्यथा false। |
| [getMedia](../../com.aspose.html.window/mediaquerylist/media/) एक स्ट्रिंग जो सीरियलाइज़्ड मीडिया क्वेरी को दर्शाती है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | The addEventListener() method of the [`EventTarget `](../../com.aspose.html.dom/eventtarget/)interface sets up a function that will be called whenever the specified event is delivered to the target. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | addEventListener() मेथड [EventTarget ](T:com.aspose.html.dom.EventTarget) इंटरफ़ेस एक फ़ंक्शन सेट करता है जो तब बुलाया जाएगा जब निर्दिष्ट इवेंट लक्ष्य को पहुँचाया जाता है। |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | addEventListener() मेथड [EventTarget ](T:com.aspose.html.dom.EventTarget) इंटरफ़ेस एक फ़ंक्शन सेट करता है जो तब बुलाया जाएगा जब निर्दिष्ट इवेंट लक्ष्य को पहुँचाया जाता है। |
| [addListener](../../com.aspose.html.window/mediaquerylist/addlistener/)(IEventListener) | MediaQueryList मैच स्थिति परिवर्तन इवेंट लिस्नर जोड़ें। |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | `EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) पर निर्दिष्ट इवेंट को डिस्पैच करता है, (सिंक्रोनस रूप से) प्रभावित EventListeners को उचित क्रम में बुलाता है। सामान्य इवेंट प्रोसेसिंग नियम (कैप्चरिंग और वैकल्पिक बबलिंग चरण सहित) मैन्युअल रूप से [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) के साथ डिस्पैच किए गए इवेंट्स पर भी लागू होते हैं। |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | अनमैनेज्ड संसाधनों को मुक्त करने, रिलीज़ करने या रीसेट करने से जुड़े एप्लिकेशन-परिभाषित कार्यों को निष्पादित करता है। |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | यह मेथड ECMAScript ऑब्जेक्ट को प्राप्त करने के लिए उपयोग किया जाता है। |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | यह विधि इवेंट लक्ष्य से इवेंट लिस्नर को हटाने की अनुमति देती है। यदि इवेंट प्रोसेस हो रहा हो तो इवेंट लिस्नर को हटाया जाता है, तो वह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा। Event Listeners को हटाए जाने के बाद कभी भी बुलाया नहीं जा सकता। |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | यह विधि इवेंट लक्ष्य से इवेंट लिस्नर को हटाने की अनुमति देती है। यदि इवेंट प्रोसेस हो रहा हो तो इवेंट लिस्नर को हटाया जाता है, तो वह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा। Event Listeners को हटाए जाने के बाद कभी भी बुलाया नहीं जा सकता। |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | यह विधि इवेंट लक्ष्य से इवेंट लिस्नर को हटाने की अनुमति देती है। यदि इवेंट प्रोसेस हो रहा हो तो इवेंट लिस्नर को हटाया जाता है, तो वह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा। Event Listeners को हटाए जाने के बाद कभी भी बुलाया नहीं जा सकता। |
| [removeListener](../../com.aspose.html.window/mediaquerylist/removelistener/)(IEventListener) | MediaQueryList मैच स्थिति परिवर्तन इवेंट लिस्नर हटाएँ। |

## इवेंट्स

| नाम | विवरण |
| --- | --- |
| event [OnChange](../../com.aspose.html.window/mediaquerylist/onchange/) | जब मैच स्थिति बदलती है तो MediaQueryList पर फायर किया जाने वाला इवेंट। |

### संबंधित देखें

* class [EventTarget](../../com.aspose.html.dom/eventtarget/)
* package [com.aspose.html.window](../../com.aspose.html.window/)
* package [Aspose.HTML](../../)

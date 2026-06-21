---
title: "IWindow इंटरफ़ेस"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.window.IWindow इंटरफ़ेस। विंडो ऑब्जेक्ट एक DOM दस्तावेज़ वाली विंडो का प्रतिनिधित्व करता है।"
type: docs

url: /hi/java/com.aspose.html.window/iwindow/
---
## IWindow interface

विंडो ऑब्जेक्ट एक ऐसी विंडो को दर्शाता है जिसमें एक DOM दस्तावेज़ होता है।

```java
public interface IWindow : IDisposable, IDocumentView, IEventTarget, IGlobalEventHandlers, 
    IWindowEventHandlers, IWindowTimers
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [getDocument](../../com.aspose.html.window/iwindow/document/) document एट्रिब्यूट को विंडो ऑब्जेक्ट का नवीनतम Document ऑब्जेक्ट लौटाना चाहिए। |
| [getFrameElement](../../com.aspose.html.window/iwindow/frameelement/) एक Document का frameElement ऑब्जेक्ट। |
| [getLocalStorage](../../com.aspose.html.window/iwindow/localstorage/) एक Storage ऑब्जेक्ट लौटाता है जो आपको उपयोगकर्ता एजेंट में कुंजी/मान युग्म सहेजने की अनुमति देता है। |
| [getLocation](../../com.aspose.html.window/iwindow/location/) Window इंटरफ़ेस का location एट्रिब्यूट उस विंडो ऑब्जेक्ट के Document के लिए Location ऑब्जेक्ट लौटाना चाहिए। |
[getName]
[setName] The name attribute of the Window object must, on getting, return the current name of the browsing context, and, on setting, set the name of the browsing context to the new value. |
| [getOpener](../../com.aspose.html.window/iwindow/opener/) Window ऑब्जेक्ट पर opener IDL एट्रिब्यूट, प्राप्त करने पर, यदि मौजूद हो, अभी भी उपलब्ध हो, और वर्तमान browsing context ने अपना opener नहीं छोड़ा है, तो उस browsing context का WindowProxy ऑब्जेक्ट लौटाना चाहिए जिससे वर्तमान browsing context बनाया गया था (उसका opener browsing context); अन्यथा null लौटाना चाहिए। सेट करने पर, यदि नया मान null है तो वर्तमान browsing context को अपना opener छोड़ देना चाहिए; यदि नया मान कुछ और है तो उपयोगकर्ता एजेंट को Window ऑब्जेक्ट की आंतरिक विधि [[DefineOwnProperty]] को कॉल करना चाहिए, प्रॉपर्टी नाम \"opener\" को प्रॉपर्टी कुंजी के रूप में पास करते हुए, और प्रॉपर्टी डिस्क्रिप्टर { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } को प्रॉपर्टी डिस्क्रिप्टर के रूप में, जहाँ value नया मान है। |
| [getParent](../../com.aspose.html.window/iwindow/parent/) एक Document के Window ऑब्जेक्ट पर parent IDL एट्रिब्यूट, browsing context b में, यदि कोई parent browsing context मौजूद है (अर्थात b एक child browsing context है) तो उस parent browsing context का WindowProxy ऑब्जेक्ट लौटाना चाहिए, अन्यथा (यदि यह top‑level browsing context या detached nested browsing context है) browsing context b स्वयं का WindowProxy ऑब्जेक्ट लौटाना चाहिए। |
| [getSelf](../../com.aspose.html.window/iwindow/self/) Window ऑब्जेक्ट के browsing context का WindowProxy ऑब्जेक्ट लौटाता है। |
| [getTop](../../com.aspose.html.window/iwindow/top/) एक Document के Window ऑब्जेक्ट पर top IDL एट्रिब्यूट, browsing context b में, यदि उसका कोई top‑level browsing context है तो उस top‑level browsing context का WindowProxy ऑब्जेक्ट लौटाना चाहिए (यदि वह स्वयं एक top‑level browsing context है तो उसका अपना WindowProxy ऑब्जेक्ट होगा), अन्यथा उसका अपना WindowProxy ऑब्जेक्ट लौटाना चाहिए (जैसे यदि वह एक detached nested browsing context था)। |
| [getWindow](../../com.aspose.html.window/iwindow/window/) Window ऑब्जेक्ट के browsing context का WindowProxy ऑब्जेक्ट लौटाता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [alert](../../com.aspose.html.window/iwindow/alert/)(String) | दिए गए संदेश के साथ एक मोडल अलर्ट प्रदर्शित करता है, और उपयोगकर्ता के इसे बंद करने की प्रतीक्षा करता है। |
| [atob](../../com.aspose.html.window/iwindow/atob/)(String) | इनपुट डेटा को लेता है, जो base64‑एन्कोडेड बाइनरी डेटा वाली Unicode स्ट्रिंग के रूप में होता है, उसे डिकोड करता है, और एक स्ट्रिंग लौटाता है जिसमें U+0000 से U+00FF तक के अक्षर होते हैं, प्रत्येक बाइनरी बाइट (0x00 से 0xFF) का प्रतिनिधित्व करता है, जो उस बाइनरी डेटा के अनुरूप होते हैं। |
| [btoa](../../com.aspose.html.window/iwindow/btoa/)(String) | इनपुट डेटा को लेता है, जो केवल U+0000 से U+00FF तक के अक्षर वाली Unicode स्ट्रिंग के रूप में होता है, प्रत्येक बाइनरी बाइट (0x00 से 0xFF) का प्रतिनिधित्व करता है, और इसे उसके base64 प्रतिनिधित्व में परिवर्तित करता है, जिसे वह लौटाता है। |
| [confirm](../../com.aspose.html.window/iwindow/confirm/)(String) | दिए गए संदेश के साथ एक मोडल OK/Cancel प्रॉम्प्ट प्रदर्शित करता है, उपयोगकर्ता के इसे बंद करने की प्रतीक्षा करता है, और यदि उपयोगकर्ता OK क्लिक करता है तो true और यदि Cancel क्लिक करता है तो false लौटाता है। |
| [matchMedia](../../com.aspose.html.window/iwindow/matchmedia/)(String) | एक नया MediaQueryList ऑब्जेक्ट लौटाता है जिसे फिर दस्तावेज़ यह निर्धारित करने के लिए उपयोग किया जा सकता है कि वह मीडिया क्वेरी स्ट्रिंग से मेल खाता है या नहीं, साथ ही दस्तावेज़ की निगरानी करने के लिए ताकि पता चल सके कि वह कब मेल खाता है (या मेल नहीं खाता)। देखें CSSOM View Module विनिर्देशन: [https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface](https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface) |
| [prompt](../../com.aspose.html.window/iwindow/prompt/)(String, String) | दिए गए संदेश के साथ एक मोडल टेक्स्ट फ़ील्ड प्रॉम्प्ट प्रदर्शित करता है, उपयोगकर्ता के इसे बंद करने की प्रतीक्षा करता है, और उपयोगकर्ता द्वारा दर्ज किया गया मान लौटाता है। यदि उपयोगकर्ता प्रॉम्प्ट को रद्द करता है तो null लौटाता है। यदि दूसरा तर्क मौजूद है, तो दिया गया मान डिफ़ॉल्ट के रूप में उपयोग किया जाता है। |

### संबंधित देखें

* interface [IDocumentView](../../com.aspose.html.dom.views/idocumentview/)
* interface [IEventTarget](../../com.aspose.html.dom.events/ieventtarget/)
* interface [IGlobalEventHandlers](../../com.aspose.html.dom/iglobaleventhandlers/)
* interface [IWindowEventHandlers](../iwindoweventhandlers/)
* interface [IWindowTimers](../iwindowtimers/)
* package [com.aspose.html.window](../../com.aspose.html.window/)
* package [Aspose.HTML](../../)

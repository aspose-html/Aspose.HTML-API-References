---
title: "IWindow.Btoa"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "IWindow विधि। इनपुट डेटा को Unicode स्ट्रिंग के रूप में लेती है जिसमें केवल U0000 से U00FF रेंज के अक्षर होते हैं, प्रत्येक बाइनरी बाइट को 0x00 से 0xFF मान के साथ दर्शाते हैं, और इसे base64 प्रतिनिधित्व में परिवर्तित करती है जिसे यह लौटाती है।"
type: docs

url: /hi/java/com.aspose.html.window/iwindow/btoa/
---
## IWindow.Btoa method

इनपुट डेटा को लेता है, जो केवल U+0000 से U+00FF तक के अक्षर वाली Unicode स्ट्रिंग के रूप में होता है, प्रत्येक बाइनरी बाइट (0x00 से 0xFF) का प्रतिनिधित्व करता है, और इसे उसके base64 प्रतिनिधित्व में परिवर्तित करता है, जिसे वह लौटाता है।

```java
public String Btoa(String data)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| डेटा | String | U+0000 से U+00FF रेंज में केवल अक्षरों वाली Unicode स्ट्रिंग। |

### रिटर्न वैल्यू

base64 स्ट्रिंग।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | यदि इनपुट स्ट्रिंग में कोई भी रेंज से बाहर का अक्षर हो तो "InvalidCharacterError" DOMException अपवाद फेंकता है। |

### संबंधित देखें

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)

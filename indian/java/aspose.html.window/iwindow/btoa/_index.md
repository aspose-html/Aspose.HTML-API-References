---
title: "IWindow.Btoa"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "IWindow विधि. इनपुट डेटा को Unicode स्ट्रिंग के रूप में लेता है जिसमें केवल U0000 से U00FF की सीमा के अक्षर होते हैं, प्रत्येक बाइनरी बाइट को 0x00 से 0xFF मान के साथ दर्शाते हैं, और इसे उसके base64 प्रतिनिधित्व में परिवर्तित करता है जिसे वह लौटाता है"
type: docs

url: /hi/java/com.aspose.html.window/iwindow/btoa/
---
## IWindow.Btoa method

इनपुट डेटा लेता है, जो केवल U+0000 से U+00FF तक के अक्षर वाली यूनिकोड स्ट्रिंग के रूप में होता है, प्रत्येक बाइनरी बाइट को 0x00 से 0xFF तक के मान के साथ दर्शाता है, और इसे उसके बेस64 प्रतिनिधित्व में परिवर्तित करता है, जिसे वह लौटाता है।

```java
public String Btoa(String data)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| डेटा | String | यह Unicode स्ट्रिंग केवल U+0000 से U+00FF की सीमा के अक्षरों को शामिल करती है। |

### रिटर्न वैल्यू

यह base64 स्ट्रिंग।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | यदि इनपुट स्ट्रिंग में कोई सीमा से बाहर का अक्षर हो तो "InvalidCharacterError" DOMException अपवाद फेंकता है। |

### संबंधित देखें

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)

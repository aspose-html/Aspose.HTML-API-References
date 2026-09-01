---
title: "IWindow.Atob"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "IWindow विधि। इनपुट डेटा को Unicode स्ट्रिंग के रूप में लेती है जिसमें base64-एन्कोडेड बाइनरी डेटा होता है, इसे डिकोड करती है और एक स्ट्रिंग लौटाती है जिसमें अक्षर U0000 से U00FF रेंज में होते हैं, प्रत्येक बाइनरी बाइट को 0x00 से 0xFF मान के साथ दर्शाते हैं, जो उस बाइनरी डेटा के अनुरूप होते हैं।"
type: docs

url: /hi/java/com.aspose.html.window/iwindow/atob/
---
## IWindow.Atob method

इनपुट डेटा को लेता है, जो base64‑एन्कोडेड बाइनरी डेटा वाली Unicode स्ट्रिंग के रूप में होता है, उसे डिकोड करता है, और एक स्ट्रिंग लौटाता है जिसमें U+0000 से U+00FF तक के अक्षर होते हैं, प्रत्येक बाइनरी बाइट (0x00 से 0xFF) का प्रतिनिधित्व करता है, जो उस बाइनरी डेटा के अनुरूप होते हैं।

```java
public String Atob(String data)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| डेटा | String | base64-एन्कोडेड बाइनरी डेटा वाली Unicode स्ट्रिंग। |

### रिटर्न वैल्यू

U+0000 से U+00FF रेंज में अक्षरों वाली स्ट्रिंग।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | यदि इनपुट स्ट्रिंग वैध base64 डेटा नहीं है तो "InvalidCharacterError" DOMException फेंकता है। |

### संबंधित देखें

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)

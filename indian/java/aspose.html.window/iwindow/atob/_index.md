---
title: "IWindow.Atob"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "IWindow विधि. इनपुट डेटा को Unicode स्ट्रिंग के रूप में लेता है जिसमें base64-एन्कोडेड बाइनरी डेटा होता है, उसे डिकोड करता है और एक स्ट्रिंग लौटाता है जिसमें U0000 से U00FF की सीमा के अक्षर होते हैं, प्रत्येक बाइनरी बाइट को 0x00 से 0xFF मान के साथ दर्शाते हैं, जो उस बाइनरी डेटा के अनुरूप होते हैं।"
type: docs

url: /hi/java/com.aspose.html.window/iwindow/atob/
---
## IWindow.Atob method

इनपुट डेटा लेता है, जो बेस64-एन्कोडेड बाइनरी डेटा वाली यूनिकोड स्ट्रिंग के रूप में होता है, उसे डिकोड करता है, और एक स्ट्रिंग लौटाता है जिसमें U+0000 से U+00FF तक के अक्षर होते हैं, प्रत्येक बाइनरी बाइट को 0x00 से 0xFF तक के मान के साथ दर्शाता है, जो उस बाइनरी डेटा के अनुरूप होते हैं।

```java
public String Atob(String data)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| डेटा | String | यह Unicode स्ट्रिंग base64-एन्कोडेड बाइनरी डेटा को शामिल करती है। |

### रिटर्न वैल्यू

यह स्ट्रिंग U+0000 से U+00FF की सीमा के अक्षरों से बनी है।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | यदि इनपुट स्ट्रिंग वैध base64 डेटा नहीं है तो "InvalidCharacterError" DOMException फेंकता है। |

### संबंधित देखें

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)

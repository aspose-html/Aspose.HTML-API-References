---
title: "Resource क्लास"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.saving.Resource क्लास। यह क्लास एक रिसोर्स का वर्णन करती है और इसे प्रोसेस करने के लिए मेथड्स प्रदान करती है।"
type: docs

url: /hi/java/com.aspose.html.saving/resource/
---
## Resource class

यह क्लास एक संसाधन का वर्णन करती है और उसे प्रोसेस करने के लिए मेथड्स प्रदान करती है।

```java
public class Resource
```

## गुण

| नाम | विवरण |
| --- | --- |
| [getMimeType](../../com.aspose.html.saving/resource/mimetype/) इस रिसोर्स का [`MimeType`](../../com.aspose.html/mimetype/) लौटाता है। यदि रिसोर्स नहीं मिला तो यह `null` हो सकता है। |
| [getOriginalReference](../../com.aspose.html.saving/resource/originalreference/) इस रिसोर्स के मूल रेफ़रेंस को शामिल करने वाली स्ट्रिंग लौटाता है। |
| [getOriginalUrl](../../com.aspose.html.saving/resource/originalurl/) एक URL लौटाता है जो दर्शाता है कि यह रिसोर्स कहाँ स्थित था। |
[getOutputUrl]
[setOutputUrl] Gets or sets the URL indicating where the resource will be located after processing. |
| [getStatus](../../com.aspose.html.saving/resource/status/) वर्तमान संसाधन की स्थिति लौटाता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [embed](../../com.aspose.html.saving/resource/embed/)(ResourceHandlingContext) | इस संसाधन को उसके पैरेंट में Base64 के रूप में एन्कोड करके एम्बेड करता है। एन्कोडिंग परिणाम [`OutputUrl`](./outputurl/) में लिखा जाएगा। |
| [save](../../com.aspose.html.saving/resource/save/)(Stream, ResourceHandlingContext) | संसाधन को प्रदान किए गए स्ट्रीम में सहेजता है। |
| [withOutputUrl](../../com.aspose.html.saving/resource/withoutputurl/)(Url) | नया URL निर्दिष्ट करता है जो दर्शाता है कि प्रोसेसिंग के बाद संसाधन कहाँ स्थित होगा। |

### संबंधित देखें

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)

---
title: "ResourceHandler क्लास"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.saving.ResourceHandlers.ResourceHandler क्लास। यह क्लास संसाधनों को संभालने के लिए जिम्मेदार है। यह ऐसे मेथड प्रदान करता है जो आपको यह नियंत्रित करने की अनुमति देते हैं कि Resource के साथ क्या किया जाएगा और कौन सा संदर्भ पैरेंट Resource में लिखा जाएगा।"
type: docs

url: /hi/java/com.aspose.html.saving.resourcehandlers/resourcehandler/
---
## ResourceHandler class

यह क्लास संसाधनों को संभालने के लिए ज़िम्मेदार है। यह ऐसे मेथड प्रदान करती है जो आपको यह नियंत्रित करने की अनुमति देते हैं कि [`Resource`](../../com.aspose.html.saving/resource/) के साथ क्या किया जाएगा, साथ ही कौन सा रेफ़रेंस पैरेंट [`Resource`](../../com.aspose.html.saving/resource/) में लिखा जाएगा।

```java
public abstract class ResourceHandler
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| abstract [HandleResource](../../com.aspose.html.saving.resourcehandlers/resourcehandler/handleresource/)(Resource, ResourceHandlingContext) | यह मेथड संसाधन को संभालने के लिए जिम्मेदार है। इसमें आप [`Resource`](../../com.aspose.html.saving/resource/) को स्ट्रीम में सहेज सकते हैं या इसे पैरेंट संसाधन में एम्बेड कर सकते हैं। |
| [handleResourceReference](../../com.aspose.html.saving.resourcehandlers/resourcehandler/handleresourcereference/)(Resource, ResourceHandlingContext) | यह मेथड संसाधन संदर्भ को संभालने के लिए जिम्मेदार है। इस मेथड में, आप निर्धारित कर सकते हैं कि संभाले जा रहे संसाधन का संदर्भ कैसे दिखेगा। |

### संबंधित देखें

* package [com.aspose.html.saving.ResourceHandlers](../../com.aspose.html.saving.resourcehandlers/)
* package [Aspose.HTML](../../)

---
title: "ResourceHandler.HandleResourceReference"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "ResourceHandler मेथड। यह मेथड संसाधन रेफ़रेंस को संभालने के लिए जिम्मेदार है। इस मेथड में आप यह सेट कर सकते हैं कि संभाले जा रहे संसाधन का रेफ़रेंस कैसा दिखेगा।"
type: docs

url: /hi/java/com.aspose.html.saving.resourcehandlers/resourcehandler/handleresourcereference/
---
## ResourceHandler.HandleResourceReference method

यह मेथड संसाधन रेफ़रेंस को संभालने के लिए ज़िम्मेदार है। इस मेथड में आप निर्धारित कर सकते हैं कि संभाले जा रहे संसाधन का रेफ़रेंस कैसा दिखेगा।

```java
public String HandleResourceReference(Resource resource, ResourceHandlingContext context)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| resource | Resource | वह [`Resource`](../../../com.aspose.html.saving/resource/) जिसे संभाला जाएगा। |
| संदर्भ | ResourceHandlingContext | संसाधन हैंडलिंग संदर्भ। |

### रिटर्न वैल्यू

एक स्ट्रिंग जो पैरेंट रिसोर्स में लिखी जाएगी और वर्तमान में संभाले जा रहे संसाधन का रेफ़रेंस दर्शाती है।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| InvalidOperationException | यदि [`OutputUrl`](../../../com.aspose.html.saving/resource/outputurl/) `null` है और [`Status`](../../../com.aspose.html.saving/resource/status/) Saved है तो यह उठाया जाता है। सहेजे गए रिसोर्स के लिए [`OutputUrl`](../../../com.aspose.html.saving/resource/outputurl/) निर्दिष्ट किया जाना चाहिए क्योंकि अन्यथा इस रिसोर्स को संदर्भित करने वाले रिसोर्सेज़ में सही रेफ़रेंस निर्दिष्ट करना असंभव है। |

### संबंधित देखें

* class [Resource](../../../com.aspose.html.saving/resource/)
* class [ResourceHandlingContext](../../../com.aspose.html.saving/resourcehandlingcontext/)
* class [ResourceHandler](../)
* package [com.aspose.html.saving.ResourceHandlers](../../../com.aspose.html.saving.resourcehandlers/)
* package [Aspose.HTML](../../../)

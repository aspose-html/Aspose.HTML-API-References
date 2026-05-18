---
title: "ResourceHandler.HandleResourceReference"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "ResourceHandler मेथड। यह मेथड संसाधन रेफ़रेंस को संभालने के लिए ज़िम्मेदार है। इस मेथड में आप यह सेट कर सकते हैं कि संभाले जा रहे संसाधन का रेफ़रेंस कैसे दिखेगा"
type: docs

url: /hi/java/com.aspose.html.saving.resourcehandlers/resourcehandler/handleresourcereference/
---
## ResourceHandler.HandleResourceReference method

यह मेथड संसाधन संदर्भ को संभालने के लिए जिम्मेदार है। इस मेथड में, आप निर्धारित कर सकते हैं कि संभाले जा रहे संसाधन का संदर्भ कैसे दिखेगा।

```java
public String HandleResourceReference(Resource resource, ResourceHandlingContext context)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| resource | Resource | पैरेंट [`Resource`](../../../com.aspose.html.saving/resource/) जिसे संभाला जाएगा। |
| संदर्भ | ResourceHandlingContext | संसाधन हैंडलिंग संदर्भ। |

### रिटर्न वैल्यू

एक स्ट्रिंग जो पैरेंट संसाधन में लिखी जाएगी और वर्तमान में संभाले जा रहे संसाधन के रेफ़रेंस का प्रतिनिधित्व करती है।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| InvalidOperationException | यदि [`OutputUrl`](../../../com.aspose.html.saving/resource/outputurl/) `null` है और [`Status`](../../../com.aspose.html.saving/resource/status/) Saved है तो यह त्रुटि उठती है। Saved संसाधन के लिए [`OutputUrl`](../../../com.aspose.html.saving/resource/outputurl/) निर्दिष्ट किया जाना चाहिए क्योंकि अन्यथा इस संसाधन को रेफ़र करने वाले संसाधनों में सही रेफ़रेंस निर्दिष्ट करना असंभव है। |

### संबंधित देखें

* class [Resource](../../../com.aspose.html.saving/resource/)
* class [ResourceHandlingContext](../../../com.aspose.html.saving/resourcehandlingcontext/)
* class [ResourceHandler](../)
* package [com.aspose.html.saving.ResourceHandlers](../../../com.aspose.html.saving.resourcehandlers/)
* package [Aspose.HTML](../../../)

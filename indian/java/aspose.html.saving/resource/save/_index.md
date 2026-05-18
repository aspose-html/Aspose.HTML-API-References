---
title: "Resource.Save"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "Resource मेथड। प्रदान किए गए स्ट्रीम में संसाधन को सहेजता है"
type: docs

url: /hi/java/com.aspose.html.saving/resource/save/
---
## Resource.Save method

संसाधन को प्रदान किए गए स्ट्रीम में सहेजता है।

```java
public Resource Save(Stream stream, ResourceHandlingContext context)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | स्ट्रीम जिसमें संसाधन सहेजा जाएगा। |
| संदर्भ | ResourceHandlingContext | संसाधन हैंडलिंग संदर्भ। |

### रिटर्न वैल्यू

यह संसाधन ताकि आप कॉल्स को चेन कर सकें।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| InvalidOperationException | उठाया जाता है यदि [`OutputUrl`](../outputurl/) `null` है। संसाधन को सहेजने से पहले [`OutputUrl`](../outputurl/) निर्दिष्ट किया जाना चाहिए क्योंकि अन्यथा इस संसाधन को संदर्भित करने वाले संसाधनों में सही रेफ़रेंस निर्दिष्ट करना असंभव है। |

### संबंधित देखें

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* package [com.aspose.html.saving](../../../com.aspose.html.saving/)
* package [Aspose.HTML](../../../)

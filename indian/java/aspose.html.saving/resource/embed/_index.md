---
title: "Resource.Embed"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "Resource मेथड। इस संसाधन को Base64 के रूप में एन्कोड करके उसके पैरेंट में एम्बेड करता है। एन्कोडिंग परिणाम OutputUrl में लिखा जाएगा।"
type: docs

url: /hi/java/com.aspose.html.saving/resource/embed/
---
## Resource.Embed method

इस संसाधन को Base64 के रूप में एन्कोड करके उसके पैरेंट में एम्बेड करता है। एन्कोडिंग परिणाम [`OutputUrl`](../outputurl/) में लिखा जाएगा।

```java
public Resource Embed(ResourceHandlingContext context)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| संदर्भ | ResourceHandlingContext | संसाधन हैंडलिंग संदर्भ। |

### रिटर्न वैल्यू

यह संसाधन ताकि आप कॉल्स को चेन कर सकें।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| InvalidOperationException | उठाया जाता है यदि कोई [`ParentResource`](../../resourcehandlingcontext/parentresource/) नहीं है क्योंकि परिणाम को एम्बेड करने की कोई जगह नहीं है। |

### संबंधित देखें

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* package [com.aspose.html.saving](../../../com.aspose.html.saving/)
* package [Aspose.HTML](../../../)

---
title: "IEventListener इंटरफ़ेस"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.dom.events.IEventListener इंटरफ़ेस। यह इंटरफ़ेस इवेंट्स को संभालने की मुख्य विधि है। उपयोगकर्ता इंटरफ़ेस को लागू करते हैं और विधि का उपयोग करके अपना लिस्नर पंजीकृत करते हैं। उपयोगकर्ताओं को अपने लिस्नर को उसके उपयोग को समाप्त करने के बाद भी हटाना चाहिए।"
type: docs

url: /hi/java/com.aspose.html.dom.events/ieventlistener/
---
## IEventListener interface

इंटरफ़ेस इवेंट्स को संभालने की प्राथमिक विधि है। उपयोगकर्ता इंटरफ़ेस को लागू करते हैं और उस विधि का उपयोग करके अपना लिस्नर पंजीकृत करते हैं। उपयोगकर्ताओं को लिस्नर के उपयोग के बाद इसे हटाना भी चाहिए।

```java
public interface IEventListener
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [handleEvent](../../com.aspose.html.dom.events/ieventlistener/handleevent/)(Event) | यह विधि तब कॉल की जाती है जब भी उस प्रकार का इवेंट होता है जिसके लिए इंटरफ़ेस पंजीकृत किया गया था। |

## टिप्पणियाँ

जब cloneNode विधि का उपयोग करके किसी Node की प्रतिलिपि बनाई जाती है, तो स्रोत Node से जुड़े Event Listeners प्रतिलिपि Node में नहीं जुड़ते। यदि उपयोगकर्ता चाहता है कि वही Event Listeners नई बनाई गई प्रतिलिपि में जोड़े जाएँ, तो उपयोगकर्ता को उन्हें मैन्युअल रूप से जोड़ना होगा।

### संबंधित देखें

* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)

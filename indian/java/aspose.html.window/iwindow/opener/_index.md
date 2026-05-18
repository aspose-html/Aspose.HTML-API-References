---
title: "IWindow.Opener"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "IWindow property. Window ऑब्जेक्ट पर opener IDL एट्रिब्यूट को प्राप्त करने पर वर्तमान ब्राउज़िंग कॉन्टेक्स्ट के निर्माण के स्रोत ब्राउज़िंग कॉन्टेक्स्ट (उसका opener ब्राउज़िंग कॉन्टेक्स्ट) का WindowProxy ऑब्जेक्ट लौटाना चाहिए, यदि वह मौजूद है, यदि वह अभी भी उपलब्ध है, और यदि वर्तमान ब्राउज़िंग कॉन्टेक्स्ट ने अपना opener नहीं छोड़ा है; अन्यथा इसे null लौटाना चाहिए। सेट करने पर, यदि नया मान null है तो वर्तमान ब्राउज़िंग कॉन्टेक्स्ट को अपना opener छोड़ना चाहिए; यदि नया मान कुछ और है तो यूज़र एजेंट को Window ऑब्जेक्ट की DefineOwnProperty आंतरिक विधि को कॉल करना चाहिए, प्रॉपर्टी नाम \\\"opener\\\" को प्रॉपर्टी कुंजी के रूप में पास करते हुए और Property Descriptor { Value: value, Writable: true, Enumerable: true, Configurable: true } को प्रॉपर्टी डिस्क्रिप्टर के रूप में, जहाँ value नया मान है।"
type: docs

url: /hi/java/com.aspose.html.window/iwindow/opener/
---
## IWindow.Opener property

Window ऑब्जेक्ट पर opener IDL एट्रिब्यूट, प्राप्त करने पर, उस ब्राउज़िंग कॉन्टेक्स्ट का WindowProxy ऑब्जेक्ट लौटाना चाहिए जिससे वर्तमान ब्राउज़िंग कॉन्टेक्स्ट बनाया गया था (उसका opener ब्राउज़िंग कॉन्टेक्स्ट), यदि वह मौजूद है, यदि वह अभी भी उपलब्ध है, और यदि वर्तमान ब्राउज़िंग कॉन्टेक्स्ट ने अपना opener नहीं छोड़ा है; अन्यथा इसे null लौटाना चाहिए। सेट करने पर, यदि नया मान null है तो वर्तमान ब्राउज़िंग कॉन्टेक्स्ट को अपना opener छोड़ना चाहिए; यदि नया मान कुछ और है तो यूज़र एजेंट को Window ऑब्जेक्ट की [[DefineOwnProperty]] आंतरिक विधि को कॉल करना चाहिए, प्रॉपर्टी नाम \"opener\" को प्रॉपर्टी कुंजी के रूप में पास करते हुए, और Property Descriptor { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } को प्रॉपर्टी डिस्क्रिप्टर के रूप में, जहाँ value नया मान है।

```java
public IWindow Opener { get; }
```

### Property Value

opener।

### संबंधित देखें

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)

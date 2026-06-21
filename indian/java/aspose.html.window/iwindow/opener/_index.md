---
title: "IWindow.Opener"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "IWindow property. Window वस्तु पर opener IDL attribute को प्राप्त करने पर वर्तमान browsing context को बनाने वाले browsing context (उसका opener browsing context) का WindowProxy object लौटाना चाहिए, यदि वह मौजूद है, यदि वह अभी भी उपलब्ध है, और यदि वर्तमान browsing context ने अपना opener नहीं त्यागा है; अन्यथा null लौटाना चाहिए। सेट करने पर, यदि नया मान null है तो वर्तमान browsing context को अपना opener त्यागना चाहिए; यदि नया मान कुछ और है तो user agent को Window वस्तु की DefineOwnProperty आंतरिक विधि को कॉल करना चाहिए, जिसमें प्रॉपर्टी नाम \"opener\" को प्रॉपर्टी कुंजी के रूप में पास किया जाए और Property Descriptor { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } को प्रॉपर्टी डिस्क्रिप्टर के रूप में पास किया जाए, जहाँ value नया मान है।"
type: docs

url: /hi/java/com.aspose.html.window/iwindow/opener/
---
## IWindow.Opener property

Window वस्तु पर opener IDL attribute, प्राप्त करने पर, उस browsing context का WindowProxy object लौटाना चाहिए जिससे वर्तमान browsing context बनाया गया था (उसका opener browsing context), यदि वह मौजूद है, यदि वह अभी भी उपलब्ध है, और यदि वर्तमान browsing context ने अपना opener नहीं त्यागा है; अन्यथा null लौटाना चाहिए। सेट करने पर, यदि नया मान null है तो वर्तमान browsing context को अपना opener त्यागना चाहिए; यदि नया मान कुछ और है तो user agent को Window वस्तु की [[DefineOwnProperty]] आंतरिक विधि को कॉल करना चाहिए, जिसमें प्रॉपर्टी नाम "opener" को प्रॉपर्टी कुंजी के रूप में पास किया जाए, और Property Descriptor { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } को प्रॉपर्टी डिस्क्रिप्टर के रूप में पास किया जाए, जहाँ value नया मान है।

```java
public IWindow Opener { get; }
```

### Property Value

opener।

### संबंधित देखें

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)

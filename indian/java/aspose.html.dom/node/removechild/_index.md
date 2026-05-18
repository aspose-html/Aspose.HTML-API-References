---
title: "Node.RemoveChild"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "Node मेथड। Node इंटरफ़ेस का removeChild मेथड DOM से एक चाइल्ड नोड हटाता है और हटाए गए नोड को लौटाता है।"
type: docs

url: /hi/java/com.aspose.html.dom/node/removechild/
---
## Node.RemoveChild method

Node इंटरफ़ेस की removeChild() मेथड DOM से एक child node हटाती है और हटाए गए node को लौटाती है।

नोट: जब तक हटाए गए चाइल्ड पर एक रेफ़रेंस रखा जाता है, वह मेमोरी में मौजूद रहता है, लेकिन अब DOM का हिस्सा नहीं रहता। इसे बाद में कोड में फिर से उपयोग किया जा सकता है। यदि removeChild() का रिटर्न वैल्यू संग्रहीत नहीं किया जाता और कोई अन्य रेफ़रेंस नहीं रखा जाता, तो यह थोड़े समय के बाद स्वचालित रूप से मेमोरी से हटा दिया जाएगा।

```java
public Node RemoveChild(Node child)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| child | Node | एक [`Node`](../) जो DOM से हटाए जाने वाला चाइल्ड नोड है। |

### रिटर्न वैल्यू

[`Node.cloneNode()`](../clonenode/) के विपरीत, रिटर्न वैल्यू उन [`EventListener`](../../../com.aspose.html.dom.events/ieventlistener/) ऑब्जेक्ट्स को संरक्षित रखती है जो इसके साथ जुड़े हैं।

### संबंधित देखें

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---
title: "Node.InsertBefore"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "Node विधि। Node इंटरफ़ेस की insertBefore विधि एक नोड को एक रेफ़रेंस नोड से पहले निर्दिष्ट पैरेंट नोड के बच्चे के रूप में सम्मिलित करती है।"
type: docs

url: /hi/java/com.aspose.html.dom/node/insertbefore/
---
## Node.InsertBefore method

insertBefore() मेथड Node इंटरफ़ेस का एक नोड को रेफ़रेंस नोड से पहले निर्दिष्ट पैरेंट नोड के चाइल्ड के रूप में सम्मिलित करता है।

यदि दिया गया नोड पहले से ही दस्तावेज़ में मौजूद है, तो insertBefore() उसे उसकी वर्तमान स्थिति से नई स्थिति में ले जाता है। (अर्थात, यह स्वचालित रूप से निर्दिष्ट नए पैरेंट में जोड़ने से पहले उसके मौजूदा पैरेंट से हटा दिया जाएगा।)

इसका मतलब है कि एक नोड एक साथ दस्तावेज़ में दो स्थानों पर नहीं हो सकता।

```java
public Node InsertBefore(Node node, Node child)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| नोड | Node | सम्मिलित किया जाने वाला नोड। |
| चाइल्ड | Node | वह नोड जिसके पहले newNode सम्मिलित किया जाता है। यदि यह null है, तो newNode नोड के चाइल्ड नोड्स के अंत में सम्मिलित किया जाता है। |

### रिटर्न वैल्यू

जोड़े गए चाइल्ड को लौटाता है (जब तक newNode एक [`DocumentFragment`](../../documentfragment/) न हो, इस स्थिति में खाली [`DocumentFragment`](../../documentfragment/) लौटाया जाता है)।

### संबंधित देखें

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

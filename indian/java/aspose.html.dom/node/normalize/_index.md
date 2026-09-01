---
title: "Node.Normalize"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "Node मेथड। इस Node के नीचे स्थित उप‑ट्री की पूरी गहराई में सभी Text नोड्स को, एट्रिब्यूट नोड्स सहित, एक सामान्य रूप में रखता है जहाँ केवल संरचना जैसे तत्व, टिप्पणी, प्रोसेसिंग इंस्ट्रक्शन, CDATA सेक्शन और एंटिटी रेफ़रेंसेज़ Text नोड्स को अलग करती हैं, अर्थात् कोई सटे हुए Text नोड्स या खाली Text नोड्स नहीं होते। इसका उपयोग यह सुनिश्चित करने के लिए किया जा सकता है कि किसी दस्तावेज़ का DOM दृश्य उसी तरह हो जैसा कि इसे सहेजा और पुनः‑लोड किया गया हो, और यह उन ऑपरेशनों के लिए उपयोगी है जैसे XPointer लुकअप्स जो किसी विशिष्ट दस्तावेज़ ट्री संरचना पर निर्भर होते हैं। यदि Node.ownerDocument से जुड़े DOMConfiguration ऑब्जेक्ट का normalize-characters पैरामीटर true है, तो यह मेथड Text नोड्स के अक्षरों को भी पूरी तरह से सामान्यीकृत करेगा।"
type: docs

url: /hi/java/com.aspose.html.dom/node/normalize/
---
## Node.Normalize method

`[`Text`](../../text/)` नोड्स को इस Node के नीचे स्थित उप‑ट्री की पूरी गहराई में, एट्रिब्यूट नोड्स सहित, एक "सामान्य" रूप में रखा जाता है जहाँ केवल संरचना (जैसे [`elements`](../../element/), [`comments`](../../comment/), [`processing instructions`](../../processinginstruction/), [`CDATA sections`](../../cdatasection/), और [`entity references`](../../entityreference/)) [`Text`](../../text/) नोड्स को अलग करती है, अर्थात् कोई सटे हुए Text नोड्स या खाली Text नोड्स नहीं होते। इसका उपयोग यह सुनिश्चित करने के लिए किया जा सकता है कि किसी दस्तावेज़ का DOM दृश्य उसी तरह हो जैसा कि इसे सहेजा और पुनः‑लोड किया गया हो, और यह उन ऑपरेशनों के लिए उपयोगी है (जैसे XPointer [XPointer] लुकअप्स) जो किसी विशिष्ट दस्तावेज़ ट्री संरचना पर निर्भर होते हैं। यदि [`DOMConfiguration`](../../../com.aspose.html/configuration/) ऑब्जेक्ट का "normalize-characters" पैरामीटर, जो [`Node.ownerDocument`](../ownerdocument/) से जुड़ा है, true है, तो यह मेथड Text नोड्स के अक्षरों को भी पूरी तरह से सामान्यीकृत करेगा।

```java
public void Normalize()
```

### संबंधित देखें

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

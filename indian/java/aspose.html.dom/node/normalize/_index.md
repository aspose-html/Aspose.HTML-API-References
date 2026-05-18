---
title: "Node.Normalize"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "Node मेथड। यह इस Node के नीचे सब-ट्री की पूरी गहराई में सभी Text नोड्स को, एट्रिब्यूट नोड्स सहित, एक सामान्य रूप में रखता है जहाँ केवल संरचना (जैसे elements, comments, processing instructions, CDATA sections, और entity references) Text नोड्स को अलग करती है, अर्थात कोई आसन्न Text नोड्स या खाली Text नोड्स नहीं होते। यह सुनिश्चित करने के लिए उपयोग किया जा सकता है कि किसी दस्तावेज़ का DOM दृश्य उसी तरह हो जैसा कि इसे सहेजा और पुनः लोड किया गया हो, और यह उन ऑपरेशनों के लिए उपयोगी है जैसे XPointer लुकअप्स जो किसी विशिष्ट दस्तावेज़ ट्री संरचना पर निर्भर होते हैं। यदि Node.ownerDocument से जुड़े DOMConfiguration ऑब्जेक्ट का normalize-characters पैरामीटर true है, तो यह मेथड Text नोड्स के अक्षरों को भी पूरी तरह से सामान्य करेगा।"
type: docs

url: /hi/java/com.aspose.html.dom/node/normalize/
---
## Node.Normalize method

सभी [`Text`](../../text/) नोड्स को इस Node के नीचे सब-ट्री की पूरी गहराई में, एट्रिब्यूट नोड्स सहित, एक "सामान्य" रूप में रखा जाता है जहाँ केवल संरचना (जैसे [`elements`](../../element/), [`comments`](../../comment/), [`processing instructions`](../../processinginstruction/), [`CDATA sections`](../../cdatasection/), और [`entity references`](../../entityreference/)) [`Text`](../../text/) नोड्स को अलग करती है, अर्थात कोई आसन्न Text नोड्स या खाली Text नोड्स नहीं होते। यह सुनिश्चित करने के लिए उपयोग किया जा सकता है कि किसी दस्तावेज़ का DOM दृश्य उसी तरह हो जैसा कि इसे सहेजा और पुनः लोड किया गया हो, और यह उन ऑपरेशनों के लिए उपयोगी है (जैसे XPointer [XPointer] लुकअप्स) जो किसी विशिष्ट दस्तावेज़ ट्री संरचना पर निर्भर होते हैं। यदि [`DOMConfiguration`](../../../com.aspose.html/configuration/) ऑब्जेक्ट के "normalize-characters" पैरामीटर का मान true है, जो [`Node.ownerDocument`](../ownerdocument/) से जुड़ा है, तो यह मेथड Text नोड्स के अक्षरों को भी पूरी तरह से सामान्य करेगा।

```java
public void Normalize()
```

### संबंधित देखें

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

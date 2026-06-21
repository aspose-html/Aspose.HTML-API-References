---
title: "ICSS2Properties.Position"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "ICSS2Properties प्रॉपर्टी। इस प्रॉपर्टी के मानों के निम्नलिखित अर्थ हैं"
type: docs

url: /hi/java/com.aspose.html.dom.css/icss2properties/position/
---
## ICSS2Properties.Position property

इस प्रॉपर्टी के मानों के निम्नलिखित अर्थ हैं:

static - बॉक्स एक सामान्य बॉक्स है, जो [normal flow](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#normal-flow) के अनुसार व्यवस्थित किया गया है। ['left'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-left) और ['top'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-top) प्रॉपर्टीज़ लागू नहीं होतीं. relative - बॉक्स की स्थिति [normal flow](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#normal-flow) (इसे normal flow में स्थिति कहा जाता है) के अनुसार गणना की जाती है। फिर बॉक्स को उसकी सामान्य स्थिति से [relative](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#relative-positioning) के अनुसार ऑफ़सेट किया जाता है। जब बॉक्स B को सापेक्ष रूप से स्थित किया जाता है, तो अगले बॉक्स की स्थिति इस तरह गणना की जाती है जैसे B ऑफ़सेट न किया गया हो। absolute - बॉक्स की स्थिति (और संभवतः आकार) ['left'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-left), ['right'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-right), ['top'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-top), और ['bottom'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-bottom) प्रॉपर्टीज़ के साथ निर्दिष्ट की जाती है। ये प्रॉपर्टीज़ बॉक्स के [containing block](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#containing-block) के सापेक्ष ऑफ़सेट निर्धारित करती हैं। पूर्णतः स्थित बॉक्स सामान्य प्रवाह से बाहर ले लिए जाते हैं। इसका मतलब है कि उनका बाद के भाई-बहनों के लेआउट पर कोई प्रभाव नहीं पड़ता। साथ ही, हालांकि [absolutely positioned](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#absolutely-positioned) बॉक्स के मार्जिन होते हैं, वे किसी अन्य मार्जिन के साथ [collapse](https://www.w3.org/TR/1998/REC-CSS2-19980512/box.html#collapsing-margins) नहीं होते। fixed - बॉक्स की स्थिति 'absolute' मॉडल के अनुसार गणना की जाती है, लेकिन अतिरिक्त रूप से बॉक्स को कुछ संदर्भ के सापेक्ष [fixed](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#fixed-positioning) किया जाता है। निरंतर मीडिया के मामले में, बॉक्स को [viewport](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#viewport) के सापेक्ष फिक्स किया जाता है (और स्क्रॉल करने पर नहीं चलता)। पेज़्ड मीडिया के मामले में, बॉक्स को पेज के सापेक्ष फिक्स किया जाता है, भले ही वह पेज [viewport](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#viewport) के माध्यम से देखा जाए (उदाहरण के लिए प्रिंट-प्रिव्यू में)। लेखक 'fixed' को मीडिया-निर्भर तरीके से निर्दिष्ट करना चाह सकते हैं.

```java
public String Position { get; set; }
```

### रिटर्न वैल्यू

पोज़िशन प्रॉपर्टी

### संबंधित देखें

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

---
title: "ICSS2Properties.UnicodeBidi"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "ICSS2Properties प्रॉपर्टी। इस प्रॉपर्टी के मानों के निम्नलिखित अर्थ हैं।"
type: docs

url: /hi/java/com.aspose.html.dom.css/icss2properties/unicodebidi/
---
## ICSS2Properties.UnicodeBidi property

इस प्रॉपर्टी के मानों के निम्नलिखित अर्थ हैं:

normal - तत्व bidirectional algorithm के संदर्भ में अतिरिक्त एम्बेडिंग स्तर नहीं खोलता। inline-level तत्वों के लिए, implicit reordering तत्व सीमाओं के पार काम करता है। embed - यदि तत्व inline-level है, तो यह मान bidirectional algorithm के संदर्भ में अतिरिक्त एम्बेडिंग स्तर खोलता है। इस एम्बेडिंग स्तर की दिशा ['direction'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-direction) प्रॉपर्टी द्वारा दी जाती है। तत्व के भीतर, पुनः क्रमबद्धता implicit रूप से की जाती है। यह तत्व की शुरुआत में LRE (U+202A; 'direction: ltr' के लिए) या RLE (U+202B; 'direction: rtl' के लिए) जोड़ने और अंत में PDF (U+202C) जोड़ने के बराबर है। bidi-override - यदि तत्व inline-level है या ऐसा block-level तत्व है जिसमें केवल inline-level तत्व हैं, तो यह एक ओवरराइड बनाता है। इसका मतलब है कि तत्व के भीतर, पुनः क्रमबद्धता पूरी तरह से ['direction'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-direction) प्रॉपर्टी के अनुसार क्रम में होती है; bidirectional algorithm का implicit भाग अनदेखा किया जाता है। यह तत्व की शुरुआत में LRO (U+202D; 'direction: ltr' के लिए) या RLO (U+202E; 'direction: rtl' के लिए) जोड़ने और अंत में PDF (U+202C) जोड़ने के बराबर है।

```java
public String UnicodeBidi { get; set; }
```

### रिटर्न वैल्यू

unicode-bidi प्रॉपर्टी

### संबंधित देखें

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

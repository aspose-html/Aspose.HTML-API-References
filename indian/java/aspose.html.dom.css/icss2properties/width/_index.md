---
title: "ICSS2Properties.Width"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "ICSS2Properties प्रॉपर्टी। यह प्रॉपर्टी ब्लॉक-लेवल और रिप्लेस्ड तत्वों द्वारा उत्पन्न बॉक्सों की सामग्री चौड़ाई को निर्दिष्ट करती है।"
type: docs

url: /hi/java/com.aspose.html.dom.css/icss2properties/width/
---
## ICSS2Properties.Width property

यह प्रॉपर्टी ब्लॉक-लेवल और [replaced](https://www.w3.org/TR/1998/REC-CSS2-19980512/conform.html#replaced-element) तत्वों द्वारा उत्पन्न बॉक्सों की [content width](https://www.w3.org/TR/1998/REC-CSS2-19980512/box.html#content-width) को निर्दिष्ट करती है।

यह गुण गैर-प्रतिस्थापित [inline-level](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#inline-level) तत्वों पर लागू नहीं होता है। एक गैर-प्रतिस्थापित इनलाइन तत्व के बॉक्स की चौड़ाई उनके भीतर रेंडर की गई सामग्री की ही होती है (बच्चों के किसी भी सापेक्ष ऑफ़सेट से पहले)। याद रखें कि इनलाइन बॉक्स [line boxes](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#line-box) में प्रवाहित होते हैं। लाइन बॉक्स की चौड़ाई उनके [containing block](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#containing-block) द्वारा निर्धारित होती है, लेकिन [floats](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#floats) की उपस्थिति से कम हो सकती है।

प्रतिस्थापित तत्व के बॉक्स की चौड़ाई [intrinsic](https://www.w3.org/TR/1998/REC-CSS2-19980512/conform.html#intrinsic) होती है और यदि इस गुण का मान 'auto' से अलग है तो उपयोगकर्ता एजेंट द्वारा स्केल की जा सकती है।

मानों के निम्नलिखित अर्थ हैं:

'[length](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-length)' - एक निश्चित चौड़ाई निर्दिष्ट करता है।'[percentage](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-percentage)' - एक प्रतिशत चौड़ाई निर्दिष्ट करता है। प्रतिशत उत्पन्न बॉक्स के [containing block](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#containing-block) की चौड़ाई के सापेक्ष गणना की जाती है।auto - चौड़ाई अन्य गुणों के मानों पर निर्भर करती है। नीचे दिए गए अनुभाग देखें।ध्यान दें: ['width'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visudet.html#propdef-width) के नकारात्मक मान अवैध हैं।

```java
public String Width { get; set; }
```

### रिटर्न वैल्यू

चौड़ाई गुण

### संबंधित देखें

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

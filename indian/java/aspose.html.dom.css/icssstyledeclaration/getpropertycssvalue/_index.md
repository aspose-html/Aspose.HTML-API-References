---
title: "ICSSStyleDeclaration.GetPropertyCSSValue"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "ICSSStyleDeclaration मेथड। इसका उपयोग CSS प्रॉपर्टी के मान का ऑब्जेक्ट प्रतिनिधित्व प्राप्त करने के लिए किया जाता है यदि वह इस घोषणा ब्लॉक के भीतर स्पष्ट रूप से सेट किया गया हो। यह मेथड null लौटाता है यदि प्रॉपर्टी एक शॉर्टहैंड प्रॉपर्टी है। शॉर्टहैंड प्रॉपर्टी मानों को केवल Strings के रूप में getPropertyValue और setProperty मेथड्स का उपयोग करके एक्सेस और मॉडिफाई किया जा सकता है।"
type: docs

url: /hi/java/com.aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/
---
## ICSSStyleDeclaration.GetPropertyCSSValue method

इस घोषणा ब्लॉक के भीतर यदि कोई CSS प्रॉपर्टी स्पष्ट रूप से सेट की गई हो, तो उसकी मान की ऑब्जेक्ट प्रतिनिधित्व को पुनः प्राप्त करने के लिए उपयोग किया जाता है। यदि प्रॉपर्टी शॉर्टहैंड प्रॉपर्टी है तो यह मेथड null लौटाता है। शॉर्टहैंड प्रॉपर्टी मानों को केवल स्ट्रिंग्स के रूप में ही एक्सेस और संशोधित किया जा सकता है, getPropertyValue और setProperty मेथड्स का उपयोग करके।

```java
public CSSValue GetPropertyCSSValue(String propertyName)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| propertyName | String | propertyName एक String है जो प्राप्त की जाने वाली प्रॉपर्टी का नाम दर्शाता है। |

### रिटर्न वैल्यू

value एक CSSValue है जिसमें प्रॉपर्टी के लिए CSS मान होता है। यदि कोई मान नहीं है, तो null लौटाता है।

### संबंधित देखें

* class [CSSValue](../../cssvalue/)
* interface [ICSSStyleDeclaration](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

---
title: "ICSSStyleDeclaration.GetPropertyCSSValue"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "ICSSStyleDeclaration मेथड। इसका उपयोग इस घोषणा ब्लॉक के भीतर यदि कोई CSS प्रॉपर्टी स्पष्ट रूप से सेट की गई हो तो उसकी वैल्यू का ऑब्जेक्ट प्रतिनिधित्व प्राप्त करने के लिए किया जाता है। यह मेथड null लौटाता है यदि प्रॉपर्टी एक शॉर्टहैंड प्रॉपर्टी है। शॉर्टहैंड प्रॉपर्टी वैल्यूज़ को केवल Strings के रूप में getPropertyValue और setProperty मेथड्स का उपयोग करके एक्सेस और मॉडिफ़ाई किया जा सकता है।"
type: docs

url: /hi/java/com.aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/
---
## ICSSStyleDeclaration.GetPropertyCSSValue method

यदि इस घोषणा ब्लॉक में कोई CSS प्रॉपर्टी स्पष्ट रूप से सेट की गई है तो उसकी वैल्यू के ऑब्जेक्ट प्रतिनिधित्व को पुनः प्राप्त करने के लिए उपयोग किया जाता है। यदि प्रॉपर्टी शॉर्टहैंड प्रॉपर्टी है तो यह मेथड null लौटाता है। शॉर्टहैंड प्रॉपर्टी वैल्यूज़ को केवल स्ट्रिंग्स के रूप में एक्सेस और संशोधित किया जा सकता है, getPropertyValue और setProperty मेथड्स का उपयोग करके।

```java
public CSSValue GetPropertyCSSValue(String propertyName)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| propertyName | String | propertyName वह String है जो प्राप्त किए जाने वाले प्रॉपर्टी नाम का प्रतिनिधित्व करता है। |

### रिटर्न वैल्यू

value एक CSSValue है जिसमें किसी प्रॉपर्टी के लिए CSS वैल्यू शामिल है। यदि कोई नहीं है, तो null लौटाता है।

### संबंधित देखें

* class [CSSValue](../../cssvalue/)
* interface [ICSSStyleDeclaration](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

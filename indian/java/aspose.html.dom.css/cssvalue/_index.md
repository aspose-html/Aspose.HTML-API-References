---
title: "CSSValue क्लास"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.dom.css.CSSValue क्लास। एक सरल या जटिल मान का प्रतिनिधित्व करता है। एक CSSValue ऑब्जेक्ट केवल CSS प्रॉपर्टी के संदर्भ में ही उपस्थित होता है।"
type: docs

url: /hi/java/com.aspose.html.dom.css/cssvalue/
---
## CSSValue class

एक सरल या जटिल मान का प्रतिनिधित्व करता है। CSSValue ऑब्जेक्ट केवल CSS प्रॉपर्टी के संदर्भ में ही उपस्थित होता है।

```java
public abstract class CSSValue : DOMObject
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| abstract [CSSText](../../com.aspose.html.dom.css/cssvalue/csstext/) { get; set; } | `CSSValue` इंटरफ़ेस की cssText प्रॉपर्टी वर्तमान गणना किए गए CSS प्रॉपर्टी मान को दर्शाती है। |
| [getCSSValueType](../../com.aspose.html.dom.css/cssvalue/cssvaluetype/) मान के प्रकार को परिभाषित करने वाला कोड। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [equals](../../com.aspose.html.dom.css/cssvalue/equals/)(object) | निर्धारित करता है कि निर्दिष्ट ऑब्जेक्ट इस इंस्टेंस के बराबर है या नहीं। |
| [getHashCode](../../com.aspose.html.dom.css/cssvalue/gethashcode/)() | इस उदाहरण के लिए एक हैश कोड लौटाता है। |
| [getPlatformType](../../com.aspose.html.dom.css/cssvalue/getplatformtype/)() | यह मेथड ECMAScript ऑब्जेक्ट टाइप प्राप्त करने के लिए उपयोग किया जाता है। |
| [toString](../../com.aspose.html.dom.css/cssvalue/toString/)() | इस उदाहरण का प्रतिनिधित्व करने वाली स्ट्रिंग लौटाता है। |
| [operator ==](../../com.aspose.html.dom.css/cssvalue/op_equality/) |  |
| [operator !=](../../com.aspose.html.dom.css/cssvalue/op_inequality/) |  |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| const [CSS_CUSTOM](../../com.aspose.html.dom.css/cssvalue/css_custom/) | मान एक कस्टम मान है। |
| const [CSS_INHERIT](../../com.aspose.html.dom.css/cssvalue/css_inherit/) | मान विरासत में मिला है और cssText में "inherit" शामिल है। |
| const [CSS_PRIMITIVE_VALUE](../../com.aspose.html.dom.css/cssvalue/css_primitive_value/) | मान एक प्रिमिटिव मान है और इस CSSValue इंटरफ़ेस के उदाहरण पर बाइंडिंग-विशिष्ट कास्टिंग विधियों का उपयोग करके CSSPrimitiveValue इंटरफ़ेस का एक इंस्टेंस प्राप्त किया जा सकता है। |
| const [CSS_VALUE_LIST](../../com.aspose.html.dom.css/cssvalue/css_value_list/) | मान एक CSSValue सूची है और CSSValueList इंटरफ़ेस का एक उदाहरण इस CSSValue इंटरफ़ेस के इस उदाहरण पर बाइंडिंग-विशिष्ट कास्टिंग विधियों का उपयोग करके प्राप्त किया जा सकता है। |

### संबंधित देखें

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)

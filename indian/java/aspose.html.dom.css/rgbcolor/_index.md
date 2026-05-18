---
title: "RGBColor क्लास"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.dom.css.RGBColor क्लास। The RGBColor इंटरफ़ेस का उपयोग किसी भी RGB रंग मान को दर्शाने के लिए किया जाता है। यह इंटरफ़ेस अंतर्निहित स्टाइल प्रॉपर्टी में मानों को प्रतिबिंबित करता है। इसलिए CSSPrimitiveValue ऑब्जेक्ट्स में किए गए संशोधन स्टाइल प्रॉपर्टी को बदलते हैं।"
type: docs

url: /hi/java/com.aspose.html.dom.css/rgbcolor/
---
## RGBColor class

RGBColor इंटरफ़ेस का उपयोग किसी भी RGB रंग मान को दर्शाने के लिए किया जाता है। यह इंटरफ़ेस अंतर्निहित स्टाइल प्रॉपर्टी में मानों को प्रतिबिंबित करता है। इसलिए, CSSPrimitiveValue ऑब्जेक्ट्स में किए गए परिवर्तन स्टाइल प्रॉपर्टी को संशोधित करते हैं।

निर्दिष्ट RGB रंग को क्लिप नहीं किया जाता (भले ही संख्या 0-255 या 0%-100% की सीमा से बाहर हो)। एक गणना किया गया RGB रंग डिवाइस के अनुसार क्लिप किया जाता है।

भले ही स्टाइल शीट में रंग मान के लिए केवल पूर्णांक ही हो, इस पूर्णांक का आंतरिक संग्रहण फ्लोट होता है, और इसे निर्दिष्ट या गणना किए गए स्टाइल में फ्लोट के रूप में उपयोग किया जा सकता है।

रंग प्रतिशत मान को हमेशा संख्या में और इसके विपरीत बदला जा सकता है।

```java
public class RGBColor : DOMObject
```

## गुण

| नाम | विवरण |
| --- | --- |
| [getAlpha](../../com.aspose.html.dom.css/rgbcolor/alpha/) इस Color संरचना के अल्फा घटक मान को प्राप्त करता है। |
| [getBlue](../../com.aspose.html.dom.css/rgbcolor/blue/) इस Color संरचना के नीले घटक मान को प्राप्त करता है। |
| [getGreen](../../com.aspose.html.dom.css/rgbcolor/green/) इस Color संरचना के हरे घटक मान को प्राप्त करता है। |
| [getRed](../../com.aspose.html.dom.css/rgbcolor/red/) इस Color संरचना के लाल घटक मान को प्राप्त करता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | यह मेथड ECMAScript ऑब्जेक्ट को पुनः प्राप्त करने के लिए उपयोग किया जाता है। |
| [toNative](../../com.aspose.html.dom.css/rgbcolor/tonative/)() | मूल रंग ऑब्जेक्ट में परिवर्तित करता है। |

## टिप्पणियाँ

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

संदर्भ

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

### संबंधित देखें

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)

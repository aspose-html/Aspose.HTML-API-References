---
title: "SVGTransform.Matrix"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "SVGTransform प्रॉपर्टी। वह मैट्रिक्स जो इस रूपांतरण का प्रतिनिधित्व करता है। मैट्रिक्स ऑब्जेक्ट लाइव है, जिसका अर्थ है कि SVGTransform ऑब्जेक्ट में किए गए कोई भी परिवर्तन तुरंत मैट्रिक्स ऑब्जेक्ट में परिलक्षित होते हैं और इसके विपरीत भी। यदि मैट्रिक्स ऑब्जेक्ट को सीधे बदल दिया जाता है, अर्थात् SVGTransform इंटरफ़ेस की विधियों का उपयोग किए बिना, तो SVGTransform का प्रकार SVG_TRANSFORM_MATRIX में बदल जाता है। SVG_TRANSFORM_MATRIX के लिए मैट्रिक्स में उपयोगकर्ता द्वारा प्रदान किए गए a, b, c, d, e, f मान होते हैं। SVG_TRANSFORM_TRANSLATE के लिए e और f अनुवाद मात्रा का प्रतिनिधित्व करते हैं (a=1, b=0, c=0 और d=1)। SVG_TRANSFORM_SCALE के लिए a और d स्केल मात्रा का प्रतिनिधित्व करते हैं (b=0, c=0, e=0 और f=0)। SVG_TRANSFORM_SKEWX और SVG_TRANSFORM_SKEWY के लिए a, b, c और d वह मैट्रिक्स दर्शाते हैं जो दिए गए स्क्यू का परिणाम देगा (e=0 और f=0)। SVG_TRANSFORM_ROTATE के लिए a, b, c, d, e और f मिलकर वह मैट्रिक्स बनाते हैं जो दिए गए घूर्णन का परिणाम देगा। जब घूर्णन केंद्र बिंदु (0, 0) के आसपास होता है, तो e और f शून्य होंगे।"
type: docs

url: /hi/java/com.aspose.html.dom.svg.datatypes/svgtransform/matrix/
---
## SVGTransform.Matrix property

यह रूपांतरण का प्रतिनिधित्व करने वाला मैट्रिक्स। मैट्रिक्स ऑब्जेक्ट लाइव है, जिसका अर्थ है कि SVGTransform ऑब्जेक्ट में किए गए कोई भी परिवर्तन तुरंत मैट्रिक्स ऑब्जेक्ट में परिलक्षित होते हैं और इसके विपरीत भी। यदि मैट्रिक्स ऑब्जेक्ट को सीधे बदल दिया जाता है (अर्थात् SVGTransform इंटरफ़ेस की विधियों का उपयोग किए बिना), तो SVGTransform का प्रकार SVG_TRANSFORM_MATRIX में बदल जाता है। SVG_TRANSFORM_MATRIX के लिए मैट्रिक्स में उपयोगकर्ता द्वारा प्रदान किए गए a, b, c, d, e, f मान होते हैं। SVG_TRANSFORM_TRANSLATE के लिए e और f अनुवाद मात्रा का प्रतिनिधित्व करते हैं (a=1, b=0, c=0 और d=1)। SVG_TRANSFORM_SCALE के लिए a और d स्केल मात्रा का प्रतिनिधित्व करते हैं (b=0, c=0, e=0 और f=0)। SVG_TRANSFORM_SKEWX और SVG_TRANSFORM_SKEWY के लिए a, b, c और d वह मैट्रिक्स दर्शाते हैं जो दिए गए स्क्यू का परिणाम देगा (e=0 और f=0)। SVG_TRANSFORM_ROTATE के लिए a, b, c, d, e और f मिलकर वह मैट्रिक्स बनाते हैं जो दिए गए घूर्णन का परिणाम देगा। जब घूर्णन केंद्र बिंदु (0, 0) के आसपास होता है, तो e और f शून्य होंगे।

```java
public SVGMatrix Matrix { get; }
```

### Property Value

यह रूपांतरण का प्रतिनिधित्व करने वाला मैट्रिक्स।

### संबंधित देखें

* class [SVGMatrix](../../svgmatrix/)
* class [SVGTransform](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)

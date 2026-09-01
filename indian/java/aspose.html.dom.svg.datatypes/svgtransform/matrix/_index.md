---
title: "SVGTransform.Matrix"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "SVGTransform प्रॉपर्टी। वह मैट्रिक्स जो इस रूपांतरण का प्रतिनिधित्व करता है। मैट्रिक्स ऑब्जेक्ट लाइव है, अर्थात SVGTransform ऑब्जेक्ट में किए गए किसी भी परिवर्तन को तुरंत मैट्रिक्स ऑब्जेक्ट में परिलक्षित किया जाता है और इसके विपरीत भी। यदि मैट्रिक्स ऑब्जेक्ट को सीधे (यानी SVGTransform इंटरफ़ेस की विधियों का उपयोग किए बिना) बदल दिया जाता है, तो SVGTransform का प्रकार SVG_TRANSFORM_MATRIX में बदल जाता है। SVG_TRANSFORM_MATRIX के लिए, मैट्रिक्स में उपयोगकर्ता द्वारा प्रदान किए गए a, b, c, d, e, f मान होते हैं। SVG_TRANSFORM_TRANSLATE के लिए, e और f अनुवाद मात्रा का प्रतिनिधित्व करते हैं (a=1, b=0, c=0 और d=1)। SVG_TRANSFORM_SCALE के लिए, a और d स्केल मात्रा का प्रतिनिधित्व करते हैं (b=0, c=0, e=0 और f=0)। SVG_TRANSFORM_SKEWX और SVG_TRANSFORM_SKEWY के लिए, a, b, c और d वह मैट्रिक्स दर्शाते हैं जो दिए गए स्क्यू (e=0 और f=0) का परिणाम देगा। SVG_TRANSFORM_ROTATE के लिए, a, b, c, d, e और f मिलकर वह मैट्रिक्स बनाते हैं जो दिए गए घूर्णन का परिणाम देगा। जब घूर्णन केंद्र बिंदु (0, 0) के चारों ओर होता है, तो e और f शून्य होंगे।"
type: docs

url: /hi/java/com.aspose.html.dom.svg.datatypes/svgtransform/matrix/
---
## SVGTransform.Matrix property

यह मैट्रिक्स इस रूपांतरण का प्रतिनिधित्व करता है। मैट्रिक्स ऑब्जेक्ट लाइव है, अर्थात SVGTransform ऑब्जेक्ट में किए गए किसी भी परिवर्तन को तुरंत मैट्रिक्स ऑब्जेक्ट में परिलक्षित किया जाता है और इसके विपरीत भी। यदि मैट्रिक्स ऑब्जेक्ट को सीधे (यानी SVGTransform इंटरफ़ेस की विधियों का उपयोग किए बिना) बदल दिया जाता है, तो SVGTransform का प्रकार SVG_TRANSFORM_MATRIX में बदल जाता है। SVG_TRANSFORM_MATRIX के लिए, मैट्रिक्स में उपयोगकर्ता द्वारा प्रदान किए गए a, b, c, d, e, f मान होते हैं। SVG_TRANSFORM_TRANSLATE के लिए, e और f अनुवाद मात्रा का प्रतिनिधित्व करते हैं (a=1, b=0, c=0 और d=1)। SVG_TRANSFORM_SCALE के लिए, a और d स्केल मात्रा का प्रतिनिधित्व करते हैं (b=0, c=0, e=0 और f=0)। SVG_TRANSFORM_SKEWX और SVG_TRANSFORM_SKEWY के लिए, a, b, c और d वह मैट्रिक्स दर्शाते हैं जो दिए गए स्क्यू (e=0 और f=0) का परिणाम देगा। SVG_TRANSFORM_ROTATE के लिए, a, b, c, d, e और f मिलकर वह मैट्रिक्स बनाते हैं जो दिए गए घूर्णन का परिणाम देगा। जब घूर्णन केंद्र बिंदु (0, 0) के चारों ओर होता है, तो e और f शून्य होंगे।

```java
public SVGMatrix Matrix { get; }
```

### Property Value

यह मैट्रिक्स इस रूपांतरण का प्रतिनिधित्व करता है।

### संबंधित देखें

* class [SVGMatrix](../../svgmatrix/)
* class [SVGTransform](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)

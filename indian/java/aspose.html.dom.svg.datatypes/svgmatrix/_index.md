---
title: "SVGMatrix क्लास"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.dom.svg.datatypes.SVGMatrix क्लास। कई SVG ग्राफ़िक्स ऑपरेशन्स 2x3 मैट्रिसेज़ का उपयोग करते हैं जो रूप a c e b d f होते हैं, जिन्हें मैट्रिक्स अंकगणित के लिए 3x3 मैट्रिक्स में विस्तारित करने पर a c e b d f 0 0 1 बन जाता है।"
type: docs

url: /hi/java/com.aspose.html.dom.svg.datatypes/svgmatrix/
---
## SVGMatrix class

SVG के कई ग्राफ़िक्स ऑपरेशनों में [a c e] [b d f] रूप के 2x3 मैट्रिक्स का उपयोग किया जाता है, जो जब मैट्रिक्स अंकगणित के लिए 3x3 मैट्रिक्स में विस्तारित होते हैं, तो बनते हैं: [a c e] [b d f] [0 0 1]

```java
public class SVGMatrix : SVGValueType
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [A](../../com.aspose.html.dom.svg.datatypes/svgmatrix/a/) { get; set; } | मैट्रिक्स का A घटक। |
| [B](../../com.aspose.html.dom.svg.datatypes/svgmatrix/b/) { get; set; } | मैट्रिक्स का B घटक। |
| [C](../../com.aspose.html.dom.svg.datatypes/svgmatrix/c/) { get; set; } | मैट्रिक्स का C घटक। |
| [D](../../com.aspose.html.dom.svg.datatypes/svgmatrix/d/) { get; set; } | मैट्रिक्स का D घटक। |
| [E](../../com.aspose.html.dom.svg.datatypes/svgmatrix/e/) { get; set; } | मैट्रिक्स का E घटक। |
| [F](../../com.aspose.html.dom.svg.datatypes/svgmatrix/f/) { get; set; } | मैट्रिक्स का F घटक। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | अनमैनेज्ड और - वैकल्पिक रूप से - मैनेज्ड रिसोर्सेज़ को रिलीज़ करता है। |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | यह मेथड ECMAScript ऑब्जेक्ट को प्राप्त करने के लिए उपयोग किया जाता है। |
| [multiply](../../com.aspose.html.dom.svg.datatypes/svgmatrix/multiply/)(SVGMatrix) | मैट्रिक्स गुणा करता है। यह मैट्रिक्स दूसरे मैट्रिक्स द्वारा पोस्ट-गुणा किया जाता है, जिससे परिणामस्वरूप नया मैट्रिक्स प्राप्त होता है। |
| [rotate](../../com.aspose.html.dom.svg.datatypes/svgmatrix/rotate/)(float) | वर्तमान मैट्रिक्स पर रोटेशन ट्रांसफ़ॉर्मेशन को पोस्ट-गुणा करता है और परिणामस्वरूप मैट्रिक्स लौटाता है। |
| [scale](../../com.aspose.html.dom.svg.datatypes/svgmatrix/scale/)(float) | वर्तमान मैट्रिक्स पर यूनिफ़ॉर्म स्केल ट्रांसफ़ॉर्मेशन को पोस्ट-गुणा करता है और परिणामस्वरूप मैट्रिक्स लौटाता है। |
| [scaleNonUniform](../../com.aspose.html.dom.svg.datatypes/svgmatrix/scalenonuniform/)(float, float) | वर्तमान मैट्रिक्स पर नॉन-यूनिफ़ॉर्म स्केल ट्रांसफ़ॉर्मेशन को पोस्ट-गुणा करता है और परिणामस्वरूप मैट्रिक्स लौटाता है। |
| [skewX](../../com.aspose.html.dom.svg.datatypes/svgmatrix/skewx/)(float) | वर्तमान मैट्रिक्स पर एक skewX परिवर्तन को पोस्ट-गुणा करता है और परिणामी मैट्रिक्स लौटाता है। |
| [skewY](../../com.aspose.html.dom.svg.datatypes/svgmatrix/skewy/)(float) | वर्तमान मैट्रिक्स पर एक skewY परिवर्तन को पोस्ट-गुणा करता है और परिणामी मैट्रिक्स लौटाता है। |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgmatrix/toString/)() | इस उदाहरण का प्रतिनिधित्व करने वाली स्ट्रिंग लौटाता है। |
| [translate](../../com.aspose.html.dom.svg.datatypes/svgmatrix/translate/)(float, float) | वर्तमान मैट्रिक्स पर एक translation परिवर्तन को पोस्ट-गुणा करता है और परिणामी मैट्रिक्स लौटाता है। |

### संबंधित देखें

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)

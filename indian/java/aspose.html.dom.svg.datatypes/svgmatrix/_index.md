---
title: "SVGMatrix क्लास"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.dom.svg.datatypes.SVGMatrix क्लास। कई SVG ग्राफ़िक्स ऑपरेशन्स a c e b d f के रूप में 2x3 मैट्रिसेज़ का उपयोग करती हैं, जो मैट्रिक्स अंकगणित के उद्देश्यों के लिए 3x3 मैट्रिक्स में विस्तारित होने पर a c e b d f 0 0 1 बन जाती हैं।"
type: docs

url: /hi/java/com.aspose.html.dom.svg.datatypes/svgmatrix/
---
## SVGMatrix class

SVG के कई ग्राफ़िक्स ऑपरेशन निम्न रूप के 2x3 मैट्रिसेज़ का उपयोग करते हैं: [a c e] [b d f] जो, मैट्रिक्स अंकगणित के उद्देश्य से 3x3 मैट्रिक्स में विस्तारित होने पर बनते हैं: [a c e] [b d f] [0 0 1]

```java
public class SVGMatrix : SVGValueType
```

## गुण

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
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | अप्रबंधित और - वैकल्पिक रूप से - प्रबंधित संसाधनों को रिलीज़ करता है। |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | यह मेथड ECMAScript ऑब्जेक्ट को पुनः प्राप्त करने के लिए उपयोग किया जाता है। |
| [multiply](../../com.aspose.html.dom.svg.datatypes/svgmatrix/multiply/)(SVGMatrix) | मैट्रिक्स गुणन करता है। यह मैट्रिक्स किसी अन्य मैट्रिक्स द्वारा पोस्ट-गुणा किया जाता है, जिससे परिणामी नया मैट्रिक्स प्राप्त होता है। |
| [rotate](../../com.aspose.html.dom.svg.datatypes/svgmatrix/rotate/)(float) | वर्तमान मैट्रिक्स पर एक रोटेशन ट्रांसफ़ॉर्मेशन को पोस्ट-गुणा करता है और परिणामी मैट्रिक्स लौटाता है। |
| [scale](../../com.aspose.html.dom.svg.datatypes/svgmatrix/scale/)(float) | वर्तमान मैट्रिक्स पर एक समान स्केल ट्रांसफ़ॉर्मेशन को पोस्ट-गुणा करता है और परिणामी मैट्रिक्स लौटाता है। |
| [scaleNonUniform](../../com.aspose.html.dom.svg.datatypes/svgmatrix/scalenonuniform/)(float, float) | वर्तमान मैट्रिक्स पर एक असमान स्केल ट्रांसफ़ॉर्मेशन को पोस्ट-गुणा करता है और परिणामी मैट्रिक्स लौटाता है। |
| [skewX](../../com.aspose.html.dom.svg.datatypes/svgmatrix/skewx/)(float) | वर्तमान मैट्रिक्स पर एक skewX ट्रांसफ़ॉर्मेशन को पोस्ट-गुणा करता है और परिणामी मैट्रिक्स लौटाता है। |
| [skewY](../../com.aspose.html.dom.svg.datatypes/svgmatrix/skewy/)(float) | वर्तमान मैट्रिक्स पर एक skewY ट्रांसफ़ॉर्मेशन को पोस्ट-गुणा करता है और परिणामी मैट्रिक्स लौटाता है। |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgmatrix/toString/)() | इस उदाहरण का प्रतिनिधित्व करने वाली स्ट्रिंग लौटाता है। |
| [translate](../../com.aspose.html.dom.svg.datatypes/svgmatrix/translate/)(float, float) | वर्तमान मैट्रिक्स पर एक ट्रांसलेशन ट्रांसफ़ॉर्मेशन को पोस्ट-गुणा करता है और परिणामी मैट्रिक्स लौटाता है। |

### संबंधित देखें

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)

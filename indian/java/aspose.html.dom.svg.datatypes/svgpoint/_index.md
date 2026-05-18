---
title: "SVGPoint क्लास"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.dom.svg.datatypes.SVGPoint class. कई SVG DOM इंटरफ़ेस वर्ग SVGPoint की वस्तुओं का उल्लेख करते हैं। एक SVGPoint x y निर्देशांक युग्म है। मैट्रिक्स संचालन में उपयोग किए जाने पर SVGPoint को x y 1 के रूप में एक वेक्टर माना जाता है। यदि किसी SVGRect वस्तु को केवल-पढ़ने योग्य निर्धारित किया जाता है तो उसके किसी गुण को असाइन करने का प्रयास करने पर एक अपवाद फेंका जाएगा।"
type: docs

url: /hi/java/com.aspose.html.dom.svg.datatypes/svgpoint/
---
## SVGPoint class

SVG DOM के कई इंटरफ़ेस क्लास SVGPoint के ऑब्जेक्ट्स का संदर्भ देते हैं। एक SVGPoint (x, y) निर्देशांक जोड़ी है। मैट्रिक्स ऑपरेशनों में उपयोग होने पर, SVGPoint को इस रूप के वेक्टर के रूप में माना जाता है: [x] [y] [1] यदि एक SVGRect ऑब्जेक्ट को केवल-पढ़ने योग्य निर्धारित किया जाता है, तो उसके किसी एट्रिब्यूट को असाइन करने का प्रयास करने पर एक अपवाद उत्पन्न होगा।

```java
public class SVGPoint : SVGValueType
```

## गुण

| नाम | विवरण |
| --- | --- |
| [X](../../com.aspose.html.dom.svg.datatypes/svgpoint/x/) { get; set; } | X निर्देशांक। |
| [Y](../../com.aspose.html.dom.svg.datatypes/svgpoint/y/) { get; set; } | Y निर्देशांक। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | अप्रबंधित और - वैकल्पिक रूप से - प्रबंधित संसाधनों को रिलीज़ करता है। |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | यह मेथड ECMAScript ऑब्जेक्ट को पुनः प्राप्त करने के लिए उपयोग किया जाता है। |
| [matrixTransform](../../com.aspose.html.dom.svg.datatypes/svgpoint/matrixtransform/)(SVGMatrix) | इस SVGPoint वस्तु पर 2x3 मैट्रिक्स रूपांतरण लागू करता है और एक नया, परिवर्तित SVGPoint वस्तु लौटाता है: newpoint = matrix * thispoint |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgpoint/toString/)() | इस उदाहरण का प्रतिनिधित्व करने वाली स्ट्रिंग लौटाता है। |

### संबंधित देखें

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)

---
title: "ICanvasPathMethods इंटरफ़ेस"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.dom.canvas.ICanvasPathMethods interface. ICanvasPathMethods इंटरफ़ेस का उपयोग वस्तुओं के पथ को संशोधित करने के लिए किया जाता है।"
type: docs

url: /hi/java/com.aspose.html.dom.canvas/icanvaspathmethods/
---
## ICanvasPathMethods interface

ICanvasPathMethods इंटरफ़ेस ऑब्जेक्ट्स के पाथ को संशोधित करने के लिए उपयोग किया जाता है।

```java
public interface ICanvasPathMethods
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [arc](../../com.aspose.html.dom.canvas/icanvaspathmethods/arc/#arc)(double, double, double, double, double) | पथ में एक चाप जोड़ता है जो (x, y) स्थित पर केंद्रित है, त्रिज्या r के साथ, startAngle से शुरू होकर endAngle पर समाप्त होता है, और दिए गए दिशा में प्रतिक्लॉकवाइज़ (डिफ़ॉल्ट रूप से क्लॉकवाइज़) चलता है। |
| [arc](../../com.aspose.html.dom.canvas/icanvaspathmethods/arc/#arc_1)(double, double, double, double, double, bool) | पथ में एक चाप जोड़ता है जो (x, y) स्थित पर केंद्रित है, त्रिज्या r के साथ, startAngle से शुरू होकर endAngle पर समाप्त होता है, और दिए गए दिशा में प्रतिक्लॉकवाइज़ (डिफ़ॉल्ट रूप से क्लॉकवाइज़) चलता है। |
| [arcTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/arcto/)(double, double, double, double, double) | दिए गए नियंत्रण बिंदुओं और त्रिज्या के साथ पथ में एक चाप जोड़ता है, जो पिछले बिंदु से सीधी रेखा द्वारा जुड़ा होता है। |
| [bezierCurveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/beziercurveto/)(double, double, double, double, double, double) | पथ में एक क्यूबिक Bézier वक्र जोड़ता है। इसके लिए तीन बिंदुओं की आवश्यकता होती है। पहले दो बिंदु नियंत्रण बिंदु होते हैं और तीसरा अंत बिंदु। प्रारंभिक बिंदु वर्तमान पथ का अंतिम बिंदु होता है, जिसे Bézier वक्र बनाने से पहले moveTo() का उपयोग करके बदला जा सकता है। |
| [closePath](../../com.aspose.html.dom.canvas/icanvaspathmethods/closepath/)() | पेन के बिंदु को वर्तमान उप-पथ की शुरुआत में वापस ले जाता है। यह वर्तमान बिंदु से शुरुआत तक सीधी रेखा खींचने का प्रयास करता है। यदि आकार पहले ही बंद हो चुका है या केवल एक बिंदु है, तो यह फ़ंक्शन कुछ नहीं करता। |
| [ellipse](../../com.aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse)(double, double, double, double, double, double, double) | पथ में एक दीर्घवृत्त जोड़ता है जो (x, y) स्थित पर केंद्रित है, radiusX और radiusY त्रिज्याओं के साथ, startAngle से शुरू होकर endAngle पर समाप्त होता है, और दिए गए दिशा में प्रतिक्लॉकवाइज़ (डिफ़ॉल्ट रूप से क्लॉकवाइज़) चलता है। |
| [ellipse](../../com.aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | पथ में एक दीर्घवृत्त जोड़ता है जो (x, y) स्थित पर केंद्रित है, radiusX और radiusY त्रिज्याओं के साथ, startAngle से शुरू होकर endAngle पर समाप्त होता है, और दिए गए दिशा में प्रतिक्लॉकवाइज़ (डिफ़ॉल्ट रूप से क्लॉकवाइज़) चलता है। |
| [lineTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/lineto/)(double, double) | उप-पथ के अंतिम बिंदु को x, y निर्देशांक से सीधी रेखा द्वारा जोड़ता है। |
| [moveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/moveto/)(double, double) | एक नए उप-पथ का प्रारंभिक बिंदु (x, y) निर्देशांक पर ले जाता है। |
| [quadraticCurveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/quadraticcurveto/)(double, double, double, double) | वर्तमान पथ में एक द्विघात Bézier वक्र जोड़ता है। |
| [rect](../../com.aspose.html.dom.canvas/icanvaspathmethods/rect/)(double, double, double, double) | स्थिति (x, y) पर एक आयत के लिए पथ बनाता है, जिसका आकार चौड़ाई और ऊँचाई द्वारा निर्धारित होता है। |

### संबंधित देखें

* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)

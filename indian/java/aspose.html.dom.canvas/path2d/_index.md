---
title: "Path2D क्लास"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.dom.canvas.Path2D क्लास। Canvas 2D API का Path2D इंटरफ़ेस पाथ को घोषित करने के लिए उपयोग किया जाता है, जिन्हें बाद में CanvasRenderingContext2D ऑब्जेक्ट्स पर उपयोग किया जाता है। CanvasRenderingContext2D इंटरफ़ेस की पाथ मेथड्स भी इस इंटरफ़ेस पर उपलब्ध हैं और आपको आवश्यकतानुसार कैनवास पर पाथ को बनाए रखने और पुनः चलाने की अनुमति देती हैं।"
type: docs

url: /hi/java/com.aspose.html.dom.canvas/path2d/
---
## Path2D class

Canvas 2D API का Path2D इंटरफ़ेस पाथ घोषित करने के लिए उपयोग किया जाता है, जिन्हें बाद में CanvasRenderingContext2D वस्तुओं पर उपयोग किया जाता है। CanvasRenderingContext2D इंटरफ़ेस की पाथ मेथड्स भी इस इंटरफ़ेस पर मौजूद हैं और आपको पाथ बनाने की अनुमति देती हैं जिन्हें आप आवश्यकतानुसार कैनवास पर बनाए रख सकते हैं और पुनः चला सकते हैं।

```java
public class Path2D : DOMObject, ICanvasPathMethods, IDisposable
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Path2D](path2d/#constructor)() | नया निर्मित Path2D ऑब्जेक्ट लौटाता है |
| [Path2D](path2d/#constructor_1)(Path2D) | एक अन्य पाथ को तर्क के रूप में लेकर नया निर्मित Path2D ऑब्जेक्ट लौटाता है (एक कॉपी बनाता है) |
| [Path2D](path2d/#constructor_2)(String) | SVG पाथ डेटा वाली स्ट्रिंग के साथ नया निर्मित Path2D ऑब्जेक्ट लौटाता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [addPath](../../com.aspose.html.dom.canvas/path2d/addpath/#addpath)(Path2D) | तर्क द्वारा दिया गया पाथ को मौजूदा पाथ में जोड़ता है। |
| [addPath](../../com.aspose.html.dom.canvas/path2d/addpath/#addpath_1)(Path2D, SVGMatrix) | तर्क द्वारा दिया गया पाथ को मौजूदा पाथ में जोड़ता है। |
| [arc](../../com.aspose.html.dom.canvas/path2d/arc/#arc)(double, double, double, double, double) | पथ में एक चाप जोड़ता है जो (x, y) स्थिति पर केंद्रित है, त्रिज्या r के साथ, startAngle से शुरू होकर endAngle पर समाप्त होता है, और निर्दिष्ट दिशा में anticlockwise (डिफ़ॉल्ट रूप से clockwise) चलता है। |
| [arc](../../com.aspose.html.dom.canvas/path2d/arc/#arc_1)(double, double, double, double, double, bool) | पथ में एक चाप जोड़ता है जो (x, y) स्थिति पर केंद्रित है, त्रिज्या r के साथ, startAngle से शुरू होकर endAngle पर समाप्त होता है, और निर्दिष्ट दिशा में anticlockwise (डिफ़ॉल्ट रूप से clockwise) चलता है। |
| [arcTo](../../com.aspose.html.dom.canvas/path2d/arcto/)(double, double, double, double, double) | दिए गए नियंत्रण बिंदुओं और त्रिज्या के साथ पथ में एक चाप जोड़ता है, जो पिछले बिंदु से सीधी रेखा द्वारा जुड़ा होता है। |
| [bezierCurveTo](../../com.aspose.html.dom.canvas/path2d/beziercurveto/)(double, double, double, double, double, double) | पथ में एक क्यूबिक Bézier वक्र जोड़ता है। इसके लिए तीन बिंदुओं की आवश्यकता होती है। पहले दो बिंदु नियंत्रण बिंदु होते हैं और तीसरा अंत बिंदु। प्रारंभिक बिंदु वर्तमान पथ का अंतिम बिंदु होता है, जिसे Bézier वक्र बनाने से पहले moveTo() का उपयोग करके बदला जा सकता है। |
| [closePath](../../com.aspose.html.dom.canvas/path2d/closepath/)() | पेन के बिंदु को वर्तमान उप-पथ की शुरुआत में वापस ले जाता है। यह वर्तमान बिंदु से शुरुआत तक सीधी रेखा खींचने का प्रयास करता है। यदि आकार पहले ही बंद हो चुका है या केवल एक बिंदु है, तो यह फ़ंक्शन कुछ नहीं करता। |
| [dispose](../../com.aspose.html.dom.canvas/path2d/dispose/)() | ऑब्जेक्ट को डिस्पोज़ करता है। |
| [ellipse](../../com.aspose.html.dom.canvas/path2d/ellipse/#ellipse)(double, double, double, double, double, double, double) | पथ में एक दीर्घवृत्त जोड़ता है जो (x, y) स्थिति पर केंद्रित है, radiusX और radiusY त्रिज्याओं के साथ, startAngle से शुरू होकर endAngle पर समाप्त होता है, और निर्दिष्ट दिशा में anticlockwise (डिफ़ॉल्ट रूप से clockwise) चलता है। |
| [ellipse](../../com.aspose.html.dom.canvas/path2d/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | पथ में एक दीर्घवृत्त जोड़ता है जो (x, y) स्थिति पर केंद्रित है, radiusX और radiusY त्रिज्याओं के साथ, startAngle से शुरू होकर endAngle पर समाप्त होता है, और निर्दिष्ट दिशा में anticlockwise (डिफ़ॉल्ट रूप से clockwise) चलता है। |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | यह मेथड ECMAScript ऑब्जेक्ट को प्राप्त करने के लिए उपयोग किया जाता है। |
| [lineTo](../../com.aspose.html.dom.canvas/path2d/lineto/)(double, double) | उप-पथ के अंतिम बिंदु को x, y निर्देशांक से सीधी रेखा द्वारा जोड़ता है। |
| [moveTo](../../com.aspose.html.dom.canvas/path2d/moveto/)(double, double) | नए उप-पथ के प्रारंभ बिंदु को (x, y) निर्देशांक पर ले जाता है। |
| [quadraticCurveTo](../../com.aspose.html.dom.canvas/path2d/quadraticcurveto/)(double, double, double, double) | वर्तमान पथ में एक द्विघात Bézier वक्र जोड़ता है। |
| [rect](../../com.aspose.html.dom.canvas/path2d/rect/)(double, double, double, double) | स्थिति (x, y) पर एक आयत के लिए पथ बनाता है, जिसका आकार चौड़ाई और ऊँचाई द्वारा निर्धारित होता है। |

### संबंधित देखें

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)

---
title: Class Path2D
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Aspose.Html.Dom.Canvas.Path2D कक्ष. कैनवस 2ड एपआई के पथ2ड इंटरफेस क उपयग उन रस्तं क घषत करने के लए कय जत है ज बद में कैनवसरेंडरंग कन्टेक्स्ट2ड ऑब्जेक्ट्स पर उपयग कए जते हैं CanvasRenderingContext2D इंटरफ़ेस क पथ वधयँ इस इंटरफ़ेस पर भ मजूद हैं और आपक पथ बनने क अनुमत दे रह हैं जन्हें आप बनए रख सकते हैं और कैनवस पर आवश्यकतनुसर पुन चल सकते हैं
type: docs
weight: 290
url: /hi/net/aspose.html.dom.canvas/path2d/
---
## Path2D class

कैनवास 2डी एपीआई के पाथ2डी इंटरफेस का उपयोग उन रास्तों को घोषित करने के लिए किया जाता है जो बाद में कैनवसरेंडरिंग कॉन्टेक्स्ट2डी ऑब्जेक्ट्स पर उपयोग किए जाते हैं। CanvasRenderingContext2D इंटरफ़ेस की पथ विधियाँ इस इंटरफ़ेस पर भी मौजूद हैं और आपको पथ बनाने की अनुमति दे रही हैं जिन्हें आप बनाए रख सकते हैं और कैनवास पर आवश्यकतानुसार पुनः चला सकते हैं।

```csharp
public class Path2D : DOMObject, ICanvasPathMethods, IDisposable
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Path2D](path2d/#constructor)() | एक नया तात्कालिक पथ2D ऑब्जेक्ट लौटाता है |
| [Path2D](path2d/#constructor_1)(Path2D) | एक तर्क के रूप में दूसरे पथ के साथ एक नया तत्काल पथ2D ऑब्जेक्ट लौटाता है (एक प्रति बनाता है) |
| [Path2D](path2d/#constructor_2)(string) | एसवीजी पथ डेटा से युक्त एक स्ट्रिंग के साथ एक नया तत्काल पथ2डी ऑब्जेक्ट लौटाता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [AddPath](../../aspose.html.dom.canvas/path2d/addpath/#addpath)(Path2D) | तर्क द्वारा दिए गए पथ में जोड़ता है। |
| [AddPath](../../aspose.html.dom.canvas/path2d/addpath/#addpath_1)(Path2D, SVGMatrix) | तर्क द्वारा दिए गए पथ में जोड़ता है। |
| [Arc](../../aspose.html.dom.canvas/path2d/arc/#arc)(double, double, double, double, double) | उस पथ पर एक चाप जोड़ता है जो (x, y) स्थिति पर केंद्रित होता है, त्रिज्या r के साथ startAngle से शुरू होता है और endAngle पर समाप्त होता है जो दी गई दिशा में वामावर्त (घड़ी की दिशा में डिफ़ॉल्ट) होता है। |
| [Arc](../../aspose.html.dom.canvas/path2d/arc/#arc_1)(double, double, double, double, double, bool) | उस पथ पर एक चाप जोड़ता है जो (x, y) स्थिति पर केंद्रित होता है, त्रिज्या r के साथ startAngle से शुरू होता है और endAngle पर समाप्त होता है जो दी गई दिशा में वामावर्त (घड़ी की दिशा में डिफ़ॉल्ट) होता है। |
| [ArcTo](../../aspose.html.dom.canvas/path2d/arcto/)(double, double, double, double, double) | दिए गए नियंत्रण बिंदुओं और त्रिज्या के साथ पथ में एक चाप जोड़ता है, जो पिछले बिंदु से एक सीधी रेखा से जुड़ा होता है। |
| [BezierCurveTo](../../aspose.html.dom.canvas/path2d/beziercurveto/)(double, double, double, double, double, double) | पथ में घन बेज़ियर वक्र जोड़ता है। इसके लिए तीन बिंदुओं की आवश्यकता है। पहले दो बिंदु नियंत्रण बिंदु हैं और तीसरा अंतिम बिंदु है। प्रारंभिक बिंदु वर्तमान पथ में अंतिम बिंदु है, जिसे बेजियर वक्र बनाने से पहले मूव टू () का उपयोग करके बदला जा सकता है। |
| [ClosePath](../../aspose.html.dom.canvas/path2d/closepath/)() | पेन के बिंदु को वर्तमान उप-पथ की शुरुआत में वापस ले जाने का कारण बनता है। यह वर्तमान बिंदु से प्रारंभ तक एक सीधी रेखा खींचने का प्रयास करता है। यदि आकृति पहले ही बंद हो चुकी है या केवल एक बिंदु है, तो यह फ़ंक्शन कुछ नहीं करता है। |
| [Dispose](../../aspose.html.dom.canvas/path2d/dispose/)() | वस्तु का निपटान करता है। |
| [Ellipse](../../aspose.html.dom.canvas/path2d/ellipse/#ellipse)(double, double, double, double, double, double, double) | उस पथ में एक दीर्घवृत्त जोड़ता है जो (x, y) स्थिति पर केंद्रित है, त्रिज्या त्रिज्या X और त्रिज्या Y के साथ startAngle पर शुरू होता है और एंटीक्लॉकवाइज़ (घड़ी की दिशा में डिफ़ॉल्ट) द्वारा दी गई दिशा में अंतकोण पर समाप्त होता है। |
| [Ellipse](../../aspose.html.dom.canvas/path2d/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | उस पथ में एक दीर्घवृत्त जोड़ता है जो (x, y) स्थिति पर केंद्रित है, त्रिज्या त्रिज्या X और त्रिज्या Y के साथ startAngle पर शुरू होता है और एंटीक्लॉकवाइज़ (घड़ी की दिशा में डिफ़ॉल्ट) द्वारा दी गई दिशा में अंतकोण पर समाप्त होता है। |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | इस विधि का उपयोग ECMAScript ऑब्जेक्ट को पुनः प्राप्त करने के लिए किया जाता हैType . |
| [LineTo](../../aspose.html.dom.canvas/path2d/lineto/)(double, double) | उपपथ में अंतिम बिंदु को x से जोड़ता है, y एक सीधी रेखा के साथ समन्वय करता है। |
| [MoveTo](../../aspose.html.dom.canvas/path2d/moveto/)(double, double) | एक नए उप-पथ के शुरुआती बिंदु को (x, y) निर्देशांक पर ले जाता है। |
| [QuadraticCurveTo](../../aspose.html.dom.canvas/path2d/quadraticcurveto/)(double, double, double, double) | वर्तमान पथ में द्विघात बेजियर वक्र जोड़ता है. |
| [Rect](../../aspose.html.dom.canvas/path2d/rect/)(double, double, double, double) | चौड़ाई और ऊंचाई द्वारा निर्धारित आकार के साथ स्थिति (x, y) पर एक आयत के लिए पथ बनाता है। |

### यह सभी देखें

* class [DOMObject](../../aspose.html.dom/domobject/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* नाम स्थान [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas/)
* सभा [Aspose.HTML](../../)



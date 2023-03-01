---
title: Interface ICanvasPathMethods
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Aspose.Html.Dom.Canvas.ICanvasPathMethods इंटरफेस. ICanvasPathMethods इंटरफ़ेस क उपयग वस्तुओं के पथ में हेरफेर करने के लए कय जत है
type: docs
weight: 240
url: /hi/net/aspose.html.dom.canvas/icanvaspathmethods/
---
## ICanvasPathMethods interface

ICanvasPathMethods इंटरफ़ेस का उपयोग वस्तुओं के पथ में हेरफेर करने के लिए किया जाता है।

```csharp
public interface ICanvasPathMethods
```

## तरीकों

| नाम | विवरण |
| --- | --- |
| [Arc](../../aspose.html.dom.canvas/icanvaspathmethods/arc/#arc)(double, double, double, double, double) | उस पथ पर एक चाप जोड़ता है जो (x, y) स्थिति पर केंद्रित होता है, त्रिज्या r के साथ startAngle से शुरू होता है और endAngle पर समाप्त होता है जो दी गई दिशा में वामावर्त (घड़ी की दिशा में डिफ़ॉल्ट) होता है। |
| [Arc](../../aspose.html.dom.canvas/icanvaspathmethods/arc/#arc_1)(double, double, double, double, double, bool) | उस पथ पर एक चाप जोड़ता है जो (x, y) स्थिति पर केंद्रित होता है, त्रिज्या r के साथ startAngle से शुरू होता है और endAngle पर समाप्त होता है जो दी गई दिशा में वामावर्त (घड़ी की दिशा में डिफ़ॉल्ट) होता है। |
| [ArcTo](../../aspose.html.dom.canvas/icanvaspathmethods/arcto/)(double, double, double, double, double) | दिए गए नियंत्रण बिंदुओं और त्रिज्या के साथ पथ में एक चाप जोड़ता है, जो पिछले बिंदु से एक सीधी रेखा से जुड़ा होता है। |
| [BezierCurveTo](../../aspose.html.dom.canvas/icanvaspathmethods/beziercurveto/)(double, double, double, double, double, double) | पथ में घन बेज़ियर वक्र जोड़ता है। इसके लिए तीन बिंदुओं की आवश्यकता है। पहले दो बिंदु नियंत्रण बिंदु हैं और तीसरा अंतिम बिंदु है। प्रारंभिक बिंदु वर्तमान पथ में अंतिम बिंदु है, जिसे बेजियर वक्र बनाने से पहले मूव टू () का उपयोग करके बदला जा सकता है। |
| [ClosePath](../../aspose.html.dom.canvas/icanvaspathmethods/closepath/)() | पेन के बिंदु को वर्तमान उप-पथ की शुरुआत में वापस ले जाने का कारण बनता है। यह वर्तमान बिंदु से प्रारंभ तक एक सीधी रेखा खींचने का प्रयास करता है। यदि आकृति पहले ही बंद हो चुकी है या केवल एक बिंदु है, तो यह फ़ंक्शन कुछ नहीं करता है। |
| [Ellipse](../../aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse)(double, double, double, double, double, double, double) | उस पथ में एक दीर्घवृत्त जोड़ता है जो (x, y) स्थिति पर केंद्रित है, त्रिज्या त्रिज्या X और त्रिज्या Y के साथ startAngle पर शुरू होता है और एंटीक्लॉकवाइज़ (घड़ी की दिशा में डिफ़ॉल्ट) द्वारा दी गई दिशा में अंतकोण पर समाप्त होता है। |
| [Ellipse](../../aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | उस पथ में एक दीर्घवृत्त जोड़ता है जो (x, y) स्थिति पर केंद्रित है, त्रिज्या त्रिज्या X और त्रिज्या Y के साथ startAngle पर शुरू होता है और एंटीक्लॉकवाइज़ (घड़ी की दिशा में डिफ़ॉल्ट) द्वारा दी गई दिशा में अंतकोण पर समाप्त होता है। |
| [LineTo](../../aspose.html.dom.canvas/icanvaspathmethods/lineto/)(double, double) | उपपथ में अंतिम बिंदु को x से जोड़ता है, y एक सीधी रेखा के साथ समन्वय करता है। |
| [MoveTo](../../aspose.html.dom.canvas/icanvaspathmethods/moveto/)(double, double) | एक नए उप-पथ के शुरुआती बिंदु को (x, y) निर्देशांक पर ले जाता है। |
| [QuadraticCurveTo](../../aspose.html.dom.canvas/icanvaspathmethods/quadraticcurveto/)(double, double, double, double) | वर्तमान पथ में द्विघात बेजियर वक्र जोड़ता है. |
| [Rect](../../aspose.html.dom.canvas/icanvaspathmethods/rect/)(double, double, double, double) | चौड़ाई और ऊंचाई द्वारा निर्धारित आकार के साथ स्थिति (x, y) पर एक आयत के लिए पथ बनाता है। |

### यह सभी देखें

* नाम स्थान [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas/)
* सभा [Aspose.HTML](../../)



---
title: Interface ICanvasRenderingContext2D
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Aspose.Html.Dom.Canvas.ICanvasRenderingContext2D इंटरफेस. ICanvasRenderingContext2D इंटरफ़ेस क उपयग आयतं पठ छवयं और अन्य वस्तुओं क कैनवस तत्व पर खंचने के लए कय जत है यह एक कैनवस तत्व क आरेखण सतह के लए 2D रेंडरंग संदर्भ प्रदन करत है
type: docs
weight: 260
url: /hi/net/aspose.html.dom.canvas/icanvasrenderingcontext2d/
---
## ICanvasRenderingContext2D interface

ICanvasRenderingContext2D इंटरफ़ेस का उपयोग आयतों, पाठ, छवियों और अन्य वस्तुओं को कैनवास तत्व पर खींचने के लिए किया जाता है। यह एक कैनवास तत्व की आरेखण सतह के लिए 2D रेंडरिंग संदर्भ प्रदान करता है।

```csharp
public interface ICanvasRenderingContext2D : ICanvasDrawingStyles, ICanvasPathMethods
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Canvas](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/canvas/) { get; } | HTMLCanvasElement का केवल-पढ़ने के लिए बैक-रेफरेंस। अगर यह कैनवास तत्व से संबद्ध नहीं है तो शून्य हो सकता है। |
| [FillStyle](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fillstyle/) { get; set; } | अंदर की आकृतियों का उपयोग करने के लिए रंग या शैली। डिफ़ॉल्ट: (काला). |
| [GlobalAlpha](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/globalalpha/) { get; set; } | अल्फ़ा मान जो आकृतियों और छवियों को कैनवास पर संयोजित करने से पहले उन पर लागू किया जाता है। डिफ़ॉल्ट 1.0 (अपारदर्शी). |
| [GlobalCompositeOperation](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/globalcompositeoperation/) { get; set; } | GlobalAlpha के साथ यह सेट करता है कि मौजूदा बिटमैप पर आकृतियाँ और चित्र कैसे बनाए जाते हैं। डिफ़ॉल्ट: (स्रोत-ओवर) |
| [ImageSmoothingEnabled](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/imagesmoothingenabled/) { get; set; } | इमेज स्मूथिंग मोड; अक्षम होने पर, स्केल किए जाने पर छवियों को चिकना नहीं किया जाएगा. |
| [ShadowBlur](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowblur/) { get; set; } | धुंधले प्रभाव को निर्दिष्ट करता है। डिफ़ॉल्ट 0 |
| [ShadowColor](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowcolor/) { get; set; } | छाया का रंग। डिफ़ॉल्ट पूरी तरह से पारदर्शी काला. |
| [ShadowOffsetX](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowoffsetx/) { get; set; } | क्षैतिज दूरी छाया ऑफसेट होगी। डिफ़ॉल्ट 0. |
| [ShadowOffsetY](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowoffsety/) { get; set; } | ऊर्ध्वाधर दूरी छाया को ऑफसेट किया जाएगा। डिफ़ॉल्ट 0. |
| [StrokeStyle](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/strokestyle/) { get; set; } | आकृतियों के चारों ओर की रेखाओं के लिए उपयोग किया जाने वाला रंग या शैली। डिफ़ॉल्ट: (काला). |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [AddHitRegion](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/addhitregion/)(Dictionary&lt;string, string&gt;) | कैनवास में एक हिट क्षेत्र जोड़ता है। यह आपको हिट का पता लगाने को आसान बनाने की अनुमति देता है, आपको घटनाओं को DOM तत्वों, पर रूट करने देता है और उपयोगकर्ताओं के लिए कैनवास को देखे बिना एक्सप्लोर करना संभव बनाता है। |
| [BeginPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/beginpath/)() | उप-पथों की सूची को खाली करके एक नया पथ प्रारंभ करता है। जब आप एक नया पथ बनाना चाहते हैं तो इस विधि को कॉल करें। |
| [ClearHitRegions](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clearhitregions/)() | कैनवास से सभी हिट क्षेत्रों को निकालता है. |
| [ClearRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clearrect/)(double, double, double, double) | प्रारंभिक बिंदु (x, y) और आकार (चौड़ाई, ऊंचाई) द्वारा परिभाषित आयत में सभी पिक्सेल को पारदर्शी काले रंग में सेट करता है, पहले से खींची गई किसी भी सामग्री को मिटा देता है। |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip)() | गैर-शून्य वाइंडिंग संख्या नियम का उपयोग करते हुए, वर्तमान क्लिपिंग क्षेत्र और पथ द्वारा वर्णित क्षेत्र के प्रतिच्छेदन की गणना करके एक नया क्लिपिंग क्षेत्र बनाता है। वास्तविक उपपथों को प्रभावित किए बिना, क्लिपिंग क्षेत्र की गणना करते समय खुले उपपथों को निहित रूप से बंद किया जाना चाहिए . नया क्लिपिंग क्षेत्र वर्तमान क्लिपिंग क्षेत्र को बदल देता है। |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_1)(CanvasFillRule) | गैर-शून्य घुमावदार संख्या नियम का उपयोग करके वर्तमान क्लिपिंग क्षेत्र और पथ द्वारा वर्णित क्षेत्र के चौराहे की गणना करके एक नया क्लिपिंग क्षेत्र बनाता है। वास्तविक उपपथों को प्रभावित किए बिना, क्लिपिंग क्षेत्र की गणना करते समय खुले उपपथों को निहित रूप से बंद किया जाना चाहिए। नया क्लिपिंग क्षेत्र वर्तमान क्लिपिंग क्षेत्र को बदल देता है। |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_2)(Path2D, CanvasFillRule) | गैर-शून्य घुमावदार संख्या नियम का उपयोग करके वर्तमान क्लिपिंग क्षेत्र और पथ द्वारा वर्णित क्षेत्र के चौराहे की गणना करके एक नया क्लिपिंग क्षेत्र बनाता है। वास्तविक उपपथों को प्रभावित किए बिना, क्लिपिंग क्षेत्र की गणना करते समय खुले उपपथों को निहित रूप से बंद किया जाना चाहिए। नया क्लिपिंग क्षेत्र वर्तमान क्लिपिंग क्षेत्र को बदल देता है। |
| [CreateImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata)(IImageData) | निर्दिष्ट आयामों के साथ एक नया, रिक्त ImageData ऑब्जेक्ट बनाता है। नई वस्तु में सभी पिक्सेल पारदर्शी काले हैं। |
| [CreateImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata_1)(double, double) | निर्दिष्ट आयामों के साथ एक नया, रिक्त ImageData ऑब्जेक्ट बनाता है। नई वस्तु में सभी पिक्सेल पारदर्शी काले हैं। |
| [CreateLinearGradient](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createlineargradient/)(double, double, double, double) | मापदंडों द्वारा दर्शाए गए निर्देशांक द्वारा दी गई रेखा के साथ एक रेखीय ढाल बनाता है। |
| [CreatePattern](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern)(HTMLCanvasElement, string) | निर्दिष्ट छवि (एक कैनवास इमेज स्रोत) का उपयोग करके एक पैटर्न बनाता है। यह पुनरावृत्ति तर्क द्वारा निर्दिष्ट दिशाओं में स्रोत को दोहराता है। |
| [CreatePattern](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern_1)(HTMLImageElement, string) | निर्दिष्ट छवि (एक कैनवास इमेज स्रोत) का उपयोग करके एक पैटर्न बनाता है। यह पुनरावृत्ति तर्क द्वारा निर्दिष्ट दिशाओं में स्रोत को दोहराता है। |
| [CreateRadialGradient](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createradialgradient/)(double, double, double, double, double, double) | मापदंडों द्वारा दर्शाए गए दो मंडलियों के निर्देशांक द्वारा दिया गया एक रेडियल ग्रेडिएंट बनाता है। |
| [DrawFocusIfNeeded](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawfocusifneeded/)(Element) | यदि किसी दिए गए तत्व पर ध्यान केंद्रित किया जाता है, तो यह विधि वर्तमान पथ के चारों ओर एक फ़ोकस रिंग खींचती है। |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage)(HTMLCanvasElement, double, double) | निर्दिष्ट छवि बनाता है। |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_3)(HTMLImageElement, double, double) | निर्दिष्ट छवि बनाता है। |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_1)(HTMLCanvasElement, double, double, double, double) | निर्दिष्ट छवि बनाता है। |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_4)(HTMLImageElement, double, double, double, double) | निर्दिष्ट छवि बनाता है। |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_2)(HTMLCanvasElement, double, double, double, double, double, double, double, double) | निर्दिष्ट छवि बनाता है। |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_5)(HTMLImageElement, double, double, double, double, double, double, double, double) | निर्दिष्ट छवि बनाता है। |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill)() | उपपथ को वर्तमान भरण शैली और डिफ़ॉल्ट एल्गोरिदम CanvasFillRule.Nozero. से भरता है |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_1)(CanvasFillRule) | उपपथ को वर्तमान भरण शैली से भरता है. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_2)(Path2D) | उपपथ को वर्तमान भरण शैली और डिफ़ॉल्ट एल्गोरिदम CanvasFillRule.Nozero. से भरता है |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_3)(Path2D, CanvasFillRule) | उपपथ को वर्तमान भरण शैली से भरता है. |
| [FillRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fillrect/)(double, double, double, double) | (x, y) स्थिति पर एक भरा हुआ आयत बनाता है जिसका आकार चौड़ाई और ऊंचाई से निर्धारित होता है। |
| [FillText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext)(string, double, double) | दिए गए पाठ को दिए गए (x, y) स्थान पर ड्रा (भरता है) करता है। |
| [FillText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext_1)(string, double, double, double) | दिए गए पाठ को दिए गए (x, y) स्थान पर ड्रा (भरता है) करता है। |
| [GetImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/getimagedata/)(double, double, double, double) | आयत द्वारा दर्शाए गए कैनवास के क्षेत्र के लिए अंतर्निहित पिक्सेल डेटा का प्रतिनिधित्व करने वाला एक इमेजडेटा ऑब्जेक्ट देता है जो (sx, sy) से शुरू होता है और इसकी चौड़ाई और sh ऊंचाई होती है। यह विधि कैनवास रूपांतरण मैट्रिक्स से प्रभावित नहीं होती है। |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_2)(double, double) | रिपोर्ट करता है कि निर्दिष्ट बिंदु वर्तमान पथ में शामिल है या नहीं। |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_3)(double, double, CanvasFillRule) | रिपोर्ट करता है कि निर्दिष्ट बिंदु वर्तमान पथ में शामिल है या नहीं। |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath)(Path2D, double, double) | रिपोर्ट करता है कि निर्दिष्ट बिंदु वर्तमान पथ में शामिल है या नहीं। |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_1)(Path2D, double, double, CanvasFillRule) | रिपोर्ट करता है कि निर्दिष्ट बिंदु वर्तमान पथ में शामिल है या नहीं। |
| [IsPointInStroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke_1)(double, double) | रिपोर्ट करता है कि निर्दिष्ट बिंदु पथ के स्ट्रोकिंग द्वारा निहित क्षेत्र के अंदर है या नहीं। |
| [IsPointInStroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke)(Path2D, double, double) | रिपोर्ट करता है कि निर्दिष्ट बिंदु पथ के स्ट्रोकिंग द्वारा निहित क्षेत्र के अंदर है या नहीं। |
| [MeasureText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/measuretext/)(string) | टेक्स्टमेट्रिक्स ऑब्जेक्ट लौटाता है। |
| [PutImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata)(IImageData, double, double) | दिए गए ImageData ऑब्जेक्ट से डेटा को बिटमैप पर पेंट करता है। यदि एक गंदा आयत प्रदान किया जाता है, तो उस आयत के केवल पिक्सेल ही पेंट किए जाते हैं। यह विधि कैनवास परिवर्तन मैट्रिक्स से प्रभावित नहीं है। |
| [PutImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata_1)(IImageData, double, double, double, double, double, double) | दिए गए ImageData ऑब्जेक्ट से डेटा को बिटमैप पर पेंट करता है। यदि एक गंदा आयत प्रदान किया जाता है, तो उस आयत के केवल पिक्सेल ही पेंट किए जाते हैं। यह विधि कैनवास परिवर्तन मैट्रिक्स से प्रभावित नहीं है। |
| [RemoveHitRegion](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/removehitregion/)(string) | निर्दिष्ट आईडी वाले हिट क्षेत्र को कैनवास से निकालता है. |
| [ResetTransform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/resettransform/)() | पहचान मैट्रिक्स द्वारा वर्तमान परिवर्तन को रीसेट करता है। |
| [Restore](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/restore/)() | सेव () द्वारा सहेजे गए 'स्टेट स्टैक' पर अंतिम तत्व के लिए ड्राइंग शैली की स्थिति को पुनर्स्थापित करता है। |
| [Rotate](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/rotate/)(double) | रूपांतरण मैट्रिक्स में एक घुमाव जोड़ता है। कोण तर्क दक्षिणावर्त रोटेशन कोण का प्रतिनिधित्व करता है और रेडियन में व्यक्त किया जाता है। |
| [Save](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/save/)() | स्टैक का उपयोग करके वर्तमान आरेखण शैली स्थिति को सहेजता है ताकि आप पुनर्स्थापना () का उपयोग करके इसमें किए गए किसी भी परिवर्तन को वापस कर सकें। |
| [Scale](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/scale/)(double, double) | कैनवास इकाइयों में x क्षैतिज रूप से और y लंबवत रूप से स्केलिंग परिवर्तन जोड़ता है। |
| [SetTransform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/settransform/)(double, double, double, double, double, double) | वर्तमान परिवर्तन को पहचान मैट्रिक्स में रीसेट करता है, और फिर समान तर्कों के साथ परिवर्तन () विधि को आमंत्रित करता है। |
| [Stroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke)() | वर्तमान स्ट्रोक शैली के साथ उपपथों को स्ट्रोक करता है। |
| [Stroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke_1)(Path2D) | वर्तमान स्ट्रोक शैली के साथ उपपथों को स्ट्रोक करता है। |
| [StrokeRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/strokerect/)(double, double, double, double) | एक आयत को पेंट करता है जिसका प्रारंभिक बिंदु (x, y) पर है और वर्तमान स्ट्रोक शैली का उपयोग करके कैनवास पर aw चौड़ाई और h ऊंचाई है। |
| [StrokeText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext)(string, double, double) | दिए गए पाठ को दिए गए (x, y) स्थान पर ड्रा (स्ट्रोक) करता है। |
| [StrokeText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext_1)(string, double, double, double?) | दिए गए पाठ को दिए गए (x, y) स्थान पर ड्रा (स्ट्रोक) करता है। |
| [Transform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/transform/)(double, double, double, double, double, double) | वर्तमान परिवर्तन मैट्रिक्स को इसके तर्कों द्वारा वर्णित मैट्रिक्स से गुणा करता है। |
| [Translate](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/translate/)(double, double) | कैनवास और उसके मूल x क्षैतिज रूप से और y लंबवत रूप से ग्रिड पर स्थानांतरित करके एक अनुवाद परिवर्तन जोड़ता है। |

### यह सभी देखें

* interface [ICanvasDrawingStyles](../icanvasdrawingstyles/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* नाम स्थान [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas/)
* सभा [Aspose.HTML](../../)



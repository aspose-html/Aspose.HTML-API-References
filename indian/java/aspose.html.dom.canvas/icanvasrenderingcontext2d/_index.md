---
title: "ICanvasRenderingContext2D इंटरफ़ेस"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.dom.canvas.ICanvasRenderingContext2D इंटरफ़ेस। ICanvasRenderingContext2D इंटरफ़ेस का उपयोग कैनवास एलिमेंट पर आयतें, टेक्स्ट, इमेज और अन्य ऑब्जेक्ट्स ड्रॉ करने के लिए किया जाता है। यह कैनवास एलिमेंट की ड्रॉइंग सतह के लिए 2D रेंडरिंग कॉन्टेक्स्ट प्रदान करता है।"
type: docs

url: /hi/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/
---
## ICanvasRenderingContext2D interface

ICanvasRenderingContext2D इंटरफ़ेस आयत, पाठ, छवियों और अन्य वस्तुओं को कैनवास तत्व पर ड्रॉ करने के लिए उपयोग किया जाता है। यह कैनवास तत्व की ड्रॉइंग सतह के लिए 2D रेंडरिंग कॉन्टेक्स्ट प्रदान करता है।

```java
public interface ICanvasRenderingContext2D : ICanvasDrawingStyles, ICanvasPathMethods
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [getCanvas](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/canvas/) HTMLCanvasElement के लिए एक रीड‑ओनली बैक‑रेफ़रेंस। यदि यह किसी कैनवास एलिमेंट से संबद्ध नहीं है तो यह null हो सकता है। |
[getFillStyle]
[setFillStyle] Color or style to use inside shapes. Default: (black). |
[getGlobalAlpha]
[setGlobalAlpha] Alpha value that is applied to shapes and images before they are composited onto the canvas. Default 1.0 (opaque). |
[getGlobalCompositeOperation]
[setGlobalCompositeOperation] With globalAlpha applied this sets how shapes and images are drawn onto the existing bitmap. Default: (source-over) |
[getImageSmoothingEnabled]
[setImageSmoothingEnabled] Image smoothing mode; if disabled, images will not be smoothed if scaled. |
[getShadowBlur]
[setShadowBlur] Specifies the blurring effect. Default 0 |
[getShadowColor]
[setShadowColor] Color of the shadow. Default fully-transparent black. |
[getShadowOffsetX]
[setShadowOffsetX] Horizontal distance the shadow will be offset. Default 0. |
[getShadowOffsetY]
[setShadowOffsetY] Vertical distance the shadow will be offset. Default 0. |
[getStrokeStyle]
[setStrokeStyle] Color or style to use for the lines around shapes. Default: (black). |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [addHitRegion](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/addhitregion/)(Dictionary&lt;String, String&gt;) |  |
| [beginPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/beginpath/)() | सब‑पाथ की सूची को खाली करके एक नया पाथ शुरू करता है। जब आप नया पाथ बनाना चाहते हैं तो इस मेथड को कॉल करें। |
| [clearHitRegions](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clearhitregions/)() | कैनवास से सभी हिट रीजन हटाता है। |
| [clearRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clearrect/)(double, double, double, double) | शुरुआती बिंदु (x, y) और आकार (width, height) द्वारा परिभाषित आयत में सभी पिक्सेल को पारदर्शी काले रंग में सेट करता है, जिससे पहले से ड्रॉ किया गया कोई भी कंटेंट मिट जाता है। |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip)() | वर्तमान क्लिपिंग रीजन और पाथ द्वारा वर्णित क्षेत्र के इंटरसेक्शन की गणना करके एक नया क्लिपिंग रीजन बनाता है, गैर‑शून्य विंडिंग नंबर नियम का उपयोग करते हुए। क्लिपिंग रीजन की गणना करते समय खुले सब‑पाथ को अप्रत्यक्ष रूप से बंद किया जाना चाहिए, बिना वास्तविक सब‑पाथ को प्रभावित किए। नया क्लिपिंग रीजन वर्तमान क्लिपिंग रीजन को प्रतिस्थापित करता है। |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_1)(CanvasFillRule) | वर्तमान क्लिपिंग रीजन और पाथ द्वारा वर्णित क्षेत्र के इंटरसेक्शन की गणना करके एक नया क्लिपिंग रीजन बनाता है, गैर‑शून्य विंडिंग नंबर नियम का उपयोग करते हुए। क्लिपिंग रीजन की गणना करते समय खुले सब‑पाथ को अप्रत्यक्ष रूप से बंद किया जाना चाहिए, बिना वास्तविक सब‑पाथ को प्रभावित किए। नया क्लिपिंग रीजन वर्तमान क्लिपिंग रीजन को प्रतिस्थापित करता है। |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_2)(Path2D, CanvasFillRule) | वर्तमान क्लिपिंग रीजन और पाथ द्वारा वर्णित क्षेत्र के इंटरसेक्शन की गणना करके एक नया क्लिपिंग रीजन बनाता है, गैर‑शून्य विंडिंग नंबर नियम का उपयोग करते हुए। क्लिपिंग रीजन की गणना करते समय खुले सब‑पाथ को अप्रत्यक्ष रूप से बंद किया जाना चाहिए, बिना वास्तविक सब‑पाथ को प्रभावित किए। नया क्लिपिंग रीजन वर्तमान क्लिपिंग रीजन को प्रतिस्थापित करता है। |
| [createImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata)(IImageData) | निर्दिष्ट आयामों के साथ एक नया, खाली ImageData ऑब्जेक्ट बनाता है। नए ऑब्जेक्ट के सभी पिक्सेल पारदर्शी काले होते हैं। |
| [createImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata_1)(double, double) | निर्दिष्ट आयामों के साथ एक नया, खाली ImageData ऑब्जेक्ट बनाता है। नए ऑब्जेक्ट के सभी पिक्सेल पारदर्शी काले होते हैं। |
| [createLinearGradient](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createlineargradient/)(double, double, double, double) | पैरामीटर्स द्वारा प्रतिनिधित्व किए गए निर्देशांक द्वारा दी गई रेखा के साथ एक लीनियर ग्रेडिएंट बनाता है। |
| [createPattern](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern)(HTMLCanvasElement, String) | निर्दिष्ट इमेज (एक CanvasImageSource) का उपयोग करके एक पैटर्न बनाता है। यह स्रोत को दोहराव आर्ग्यूमेंट द्वारा निर्दिष्ट दिशाओं में दोहराता है। |
| [createPattern](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern_1)(HTMLImageElement, String) | निर्दिष्ट इमेज (एक CanvasImageSource) का उपयोग करके एक पैटर्न बनाता है। यह स्रोत को दोहराव आर्ग्यूमेंट द्वारा निर्दिष्ट दिशाओं में दोहराता है। |
| [createRadialGradient](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createradialgradient/)(double, double, double, double, double, double) | पैरामीटर्स द्वारा प्रतिनिधित्व किए गए दो वृत्तों के निर्देशांक द्वारा दिया गया एक रेडियल ग्रेडिएंट बनाता है। |
| [drawFocusIfNeeded](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawfocusifneeded/)(Element) | यदि कोई दिया गया तत्व फोकस्ड है, तो यह मेथड वर्तमान पथ के चारों ओर फोकस रिंग बनाता है। |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage)(HTMLCanvasElement, double, double) | निर्दिष्ट छवि को ड्रॉ करता है। |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_3)(HTMLImageElement, double, double) | निर्दिष्ट छवि को ड्रॉ करता है। |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_1)(HTMLCanvasElement, double, double, double, double) | निर्दिष्ट छवि को ड्रॉ करता है। |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_4)(HTMLImageElement, double, double, double, double) | निर्दिष्ट छवि को ड्रॉ करता है। |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_2)(HTMLCanvasElement, double, double, double, double, double, double, double, double) | निर्दिष्ट छवि को ड्रॉ करता है। |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_5)(HTMLImageElement, double, double, double, double, double, double, double, double) | निर्दिष्ट छवि को ड्रॉ करता है। |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill)() | उपपथों को वर्तमान फ़िल स्टाइल और डिफ़ॉल्ट एल्गोरिद्म CanvasFillRule.Nonzero के साथ भरता है। |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_1)(CanvasFillRule) | उपपथों को वर्तमान फ़िल स्टाइल के साथ भरता है। |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_2)(Path2D) | उपपथों को वर्तमान फ़िल स्टाइल और डिफ़ॉल्ट एल्गोरिद्म CanvasFillRule.Nonzero के साथ भरता है। |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_3)(Path2D, CanvasFillRule) | उपपथों को वर्तमान फ़िल स्टाइल के साथ भरता है। |
| [fillRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fillrect/)(double, double, double, double) | (x, y) स्थिति पर एक भरा हुआ आयत ड्रॉ करता है जिसका आकार चौड़ाई और ऊँचाई द्वारा निर्धारित होता है। |
| [fillText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext)(String, double, double) | दिए गए (x,y) स्थिति पर दिया गया टेक्स्ट ड्रॉ (भरे) करता है। |
| [fillText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext_1)(String, double, double, double) | दिए गए (x,y) स्थिति पर दिया गया टेक्स्ट ड्रॉ (भरे) करता है। |
| [getImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/getimagedata/)(double, double, double, double) | एक ImageData ऑब्जेक्ट लौटाता है जो कैनवास के उस क्षेत्र के अंतर्निहित पिक्सेल डेटा को दर्शाता है, जिसे आयत द्वारा दर्शाया गया है जो (sx, sy) से शुरू होती है और जिसकी चौड़ाई sw और ऊँचाई sh है। यह मेथड कैनवास ट्रांसफ़ॉर्मेशन मैट्रिक्स से प्रभावित नहीं होता। |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_2)(double, double) | रिपोर्ट करता है कि निर्दिष्ट बिंदु वर्तमान पथ में शामिल है या नहीं। |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_3)(double, double, CanvasFillRule) | रिपोर्ट करता है कि निर्दिष्ट बिंदु वर्तमान पथ में शामिल है या नहीं। |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath)(Path2D, double, double) | रिपोर्ट करता है कि निर्दिष्ट बिंदु वर्तमान पथ में शामिल है या नहीं। |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_1)(Path2D, double, double, CanvasFillRule) | रिपोर्ट करता है कि निर्दिष्ट बिंदु वर्तमान पथ में शामिल है या नहीं। |
| [isPointInStroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke_1)(double, double) | रिपोर्ट करता है कि निर्दिष्ट बिंदु पथ के स्ट्रोकिंग द्वारा घिरे क्षेत्र के भीतर है या नहीं। |
| [isPointInStroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke)(Path2D, double, double) | रिपोर्ट करता है कि निर्दिष्ट बिंदु पथ के स्ट्रोकिंग द्वारा घिरे क्षेत्र के भीतर है या नहीं। |
| [measureText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/measuretext/)(String) | एक TextMetrics ऑब्जेक्ट लौटाता है। |
| [putImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata)(IImageData, double, double) | दिए गए ImageData ऑब्जेक्ट से डेटा को बिटमैप पर पेंट करता है। यदि एक डर्टी आयत प्रदान की गई है, तो केवल उस आयत के पिक्सेल पेंट होते हैं। यह मेथड कैनवास ट्रांसफ़ॉर्मेशन मैट्रिक्स से प्रभावित नहीं होता। |
| [putImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata_1)(IImageData, double, double, double, double, double, double) | दिए गए ImageData ऑब्जेक्ट से डेटा को बिटमैप पर पेंट करता है। यदि एक डर्टी आयत प्रदान की गई है, तो केवल उस आयत के पिक्सेल पेंट होते हैं। यह मेथड कैनवास ट्रांसफ़ॉर्मेशन मैट्रिक्स से प्रभावित नहीं होता। |
| [removeHitRegion](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/removehitregion/)(String) | निर्दिष्ट id वाले हिट रीजन को कैनवास से हटा देता है। |
| [resetTransform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/resettransform/)() | पहचान मैट्रिक्स द्वारा वर्तमान ट्रांसफ़ॉर्म को रीसेट करता है। |
| [restore](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/restore/)() | ड्रॉइंग स्टाइल की स्थिति को 'state stack' के अंतिम तत्व पर पुनर्स्थापित करता है, जिसे save() द्वारा सहेजा गया था। |
| [rotate](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/rotate/)(double) | ट्रांसफ़ॉर्मेशन मैट्रिक्स में एक रोटेशन जोड़ता है। एंगल आर्ग्यूमेंट घड़ी की दिशा में रोटेशन एंगल को दर्शाता है और रेडियन में व्यक्त किया जाता है। |
| [save](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/save/)() | स्टैक का उपयोग करके वर्तमान ड्रॉइंग स्टाइल की स्थिति को सहेजता है ताकि आप restore() द्वारा किए गए किसी भी परिवर्तन को वापस ले सकें। |
| [scale](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/scale/)(double, double) | कैनवास यूनिट्स में x क्षैतिज और y लंबवत स्केलिंग ट्रांसफ़ॉर्मेशन जोड़ता है। |
| [setTransform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/settransform/)(double, double, double, double, double, double) | वर्तमान ट्रांसफ़ॉर्म को पहचान मैट्रिक्स पर रीसेट करता है, और फिर समान आर्ग्यूमेंट्स के साथ transform() मेथड को कॉल करता है। |
| [stroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke)() | उपपथों को वर्तमान स्ट्रोक स्टाइल के साथ स्ट्रोक करता है। |
| [stroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke_1)(Path2D) | उपपथों को वर्तमान स्ट्रोक स्टाइल के साथ स्ट्रोक करता है। |
| [strokeRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/strokerect/)(double, double, double, double) | (x, y) पर प्रारंभ बिंदु वाला और w चौड़ाई तथा h ऊँचाई वाला आयत को कैनवास पर पेंट करता है, वर्तमान स्ट्रोक स्टाइल का उपयोग करके। |
| [strokeText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext)(String, double, double) | दिए गए (x, y) स्थिति पर दिया गया टेक्स्ट ड्रॉ (स्ट्रोक) करता है। |
| [strokeText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext_1)(String, double, double, double?) | दिए गए (x, y) स्थिति पर दिया गया टेक्स्ट ड्रॉ (स्ट्रोक) करता है। |
| [transform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/transform/)(double, double, double, double, double, double) | वर्तमान ट्रांसफ़ॉर्मेशन मैट्रिक्स को उसके आर्ग्यूमेंट्स द्वारा वर्णित मैट्रिक्स से गुणा करता है। |
| [translate](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/translate/)(double, double) | कैनवास और उसकी मूल बिंदु को x क्षैतिज और y लंबवत ग्रिड पर ले जाकर एक ट्रांसलेशन ट्रांसफ़ॉर्मेशन जोड़ता है। |

### संबंधित देखें

* interface [ICanvasDrawingStyles](../icanvasdrawingstyles/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)

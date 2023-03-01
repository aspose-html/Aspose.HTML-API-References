---
title: Class XpsDevice
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Aspose.Html.Rendering.Xps.XpsDevice कक्ष. एक xps दस्तवेज़ के प्रतपदन क प्रतनधत्व करत है
type: docs
weight: 4530
url: /hi/net/aspose.html.rendering.xps/xpsdevice/
---
## XpsDevice class

एक xps दस्तावेज़ के प्रतिपादन का प्रतिनिधित्व करता है।

```csharp
public class XpsDevice : Device<XpsGraphicContext, XpsRenderingOptions>
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [XpsDevice](xpsdevice/#constructor)(ICreateStreamProvider) | का एक नया उदाहरण प्रारंभ करता है`XpsDevice` वर्ग. |
| [XpsDevice](xpsdevice/#constructor_4)(Stream) | का एक नया उदाहरण प्रारंभ करता है`XpsDevice` वर्ग. |
| [XpsDevice](xpsdevice/#constructor_5)(string) | का एक नया उदाहरण प्रारंभ करता है`XpsDevice` वर्ग. |
| [XpsDevice](xpsdevice/#constructor_1)(XpsRenderingOptions, ICreateStreamProvider) | का एक नया उदाहरण प्रारंभ करता है`XpsDevice` रेंडरिंग विकल्प और स्ट्रीम प्रदाता द्वारा वर्ग। |
| [XpsDevice](xpsdevice/#constructor_2)(XpsRenderingOptions, Stream) | का एक नया उदाहरण प्रारंभ करता है`XpsDevice`विकल्प और आउटपुट स्ट्रीम प्रदान करके वर्ग। |
| [XpsDevice](xpsdevice/#constructor_3)(XpsRenderingOptions, string) | का एक नया उदाहरण प्रारंभ करता है`XpsDevice` विकल्प और आउटपुट फ़ाइल नाम प्रदान करके वर्ग। |

## गुण

| नाम | विवरण |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } |  |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } |  |

## तरीकों

| नाम | विवरण |
| --- | --- |
| override [AddRect](../../aspose.html.rendering.xps/xpsdevice/addrect/)(RectangleF) | एक पूर्ण उपपथ के रूप में वर्तमान पथ में एक आयत जोड़ता है। |
| override [BeginDocument](../../aspose.html.rendering.xps/xpsdevice/begindocument/)(Document) | दस्तावेज़ का प्रतिपादन शुरू करता है। |
| override [BeginElement](../../aspose.html.rendering.xps/xpsdevice/beginelement/)(Element, RectangleF) | तत्व का प्रतिपादन शुरू करता है। |
| override [BeginPage](../../aspose.html.rendering.xps/xpsdevice/beginpage/)(SizeF) | नए पेज की रेंडरिंग शुरू करता है। |
| override [Clip](../../aspose.html.rendering.xps/xpsdevice/clip/)(FillMode) | भरने के क्षेत्र को निर्धारित करने के लिए फिलमोड नियम का उपयोग करके वर्तमान क्लिपिंग पथ को वर्तमान पथ से काटकर संशोधित करता है। यह विधि वर्तमान पथ को समाप्त करती है। |
| override [ClosePath](../../aspose.html.rendering.xps/xpsdevice/closepath/)() | वर्तमान बिंदु से उपपथ के प्रारंभिक बिंदु तक एक सीधी रेखा खंड जोड़कर वर्तमान उपपथ को बंद करता है। यदि वर्तमान उपपथ पहले से ही बंद है, तो "ClosePath" कुछ नहीं करता है। यह ऑपरेटर वर्तमान उपपथ को समाप्त कर देता है। वर्तमान पथ में एक और खंड जोड़ने से एक नया उपपथ शुरू होता है, भले ही नया खंड "क्लोजपाथ" विधि द्वारा पहुंचे समापन बिंदु पर शुरू होता है। |
| override [CubicBezierTo](../../aspose.html.rendering.xps/xpsdevice/cubicbezierto/)(PointF, PointF, PointF) | एक घन बेज़ियर वक्र को वर्तमान पथ में जोड़ता है। वक्र वर्तमान बिंदु से बिंदु pt2, तक pt1 और pt2 को बेज़ियर नियंत्रण बिंदुओं के रूप में उपयोग करता है। नया वर्तमान बिंदु pt3. है |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() |  |
| override [DrawImage](../../aspose.html.rendering.xps/xpsdevice/drawimage/)(byte[], ImageType, RectangleF) | निर्दिष्ट छवि बनाता है। |
| virtual [EndDocument](../../aspose.html.rendering/device-2/enddocument/)() |  |
| override [EndElement](../../aspose.html.rendering.xps/xpsdevice/endelement/)(Element) | तत्व का प्रतिपादन समाप्त करता है। |
| override [EndPage](../../aspose.html.rendering.xps/xpsdevice/endpage/)() | वर्तमान पृष्ठ का प्रतिपादन समाप्त करता है। |
| override [Fill](../../aspose.html.rendering.xps/xpsdevice/fill/)(FillMode) | वर्तमान पथ से घिरे पूरे क्षेत्र को भरता है। यदि पथ में कई डिस्कनेक्ट किए गए उपपथ होते हैं, तो यह सभी उपपथों के अंदर भरता है, को एक साथ माना जाता है। यह विधि वर्तमान पथ को समाप्त करती है। |
| override [FillText](../../aspose.html.rendering.xps/xpsdevice/filltext/)(string, PointF) | निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट स्थान पर भरता है। |
| override [Flush](../../aspose.html.rendering.xps/xpsdevice/flush/)() | सभी डेटा को आउटपुट स्ट्रीम में फ़्लश करता है. |
| override [LineTo](../../aspose.html.rendering.xps/xpsdevice/lineto/)(PointF) | वर्तमान बिंदु से बिंदु (पीटी) तक एक सीधी रेखा खंड जोड़ता है। नया वर्तमान बिंदु pt. है |
| override [MoveTo](../../aspose.html.rendering.xps/xpsdevice/moveto/)(PointF) | किसी भी कनेक्टिंग लाइन सेगमेंट को छोड़ते हुए, वर्तमान बिंदु को पैरामीटर pt के निर्देशांक में ले जाकर एक नया उपपथ शुरू करता है। यदि वर्तमान पथ में पिछली पथ निर्माण विधि भी "MoveTo" थी, तो नई "MoveTo" इसे ओवरराइड कर देती है; पिछले "मूव टू" ऑपरेशन का कोई अवशेष पथ में नहीं रहता है। |
| override [RestoreGraphicContext](../../aspose.html.rendering.xps/xpsdevice/restoregraphiccontext/)() | पूरे ग्राफिक्स संदर्भ को स्टैक से पॉप करके उसके पूर्व मान पर पुनर्स्थापित करता है। |
| virtual [SaveGraphicContext](../../aspose.html.rendering/device-2/savegraphiccontext/)() |  |
| override [Stroke](../../aspose.html.rendering.xps/xpsdevice/stroke/)() | वर्तमान पथ के साथ एक रेखा को स्ट्रोक करता है। स्ट्रोक की गई रेखा पथ में प्रत्येक सीधे या घुमावदार खंड का अनुसरण करती है, इसके समानांतर भुजाओं वाले खंड पर केंद्रित होती है। पथ के प्रत्येक उपपथ को अलग से व्यवहार किया जाता है। यह विधि वर्तमान पथ को समाप्त करती है। |
| override [StrokeAndFill](../../aspose.html.rendering.xps/xpsdevice/strokeandfill/)(FillMode) | स्ट्रोक और वर्तमान पथ भरें। यह विधि वर्तमान पथ को समाप्त करती है। |
| override [StrokeText](../../aspose.html.rendering.xps/xpsdevice/stroketext/)(string, PointF) | निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट स्थान पर स्ट्रोक करता है। |

## अन्य सदस्य

| नाम | विवरण |
| --- | --- |
| class [XpsGraphicContext](xpsdevice.xpsgraphiccontext/) | XpsDevice के लिए वर्तमान ग्राफ़िक्स नियंत्रण पैरामीटर रखता है. ये पैरामीटर वैश्विक ढांचे को परिभाषित करते हैं जिसके भीतर ग्राफ़िक्स ऑपरेटर निष्पादित करते हैं. |

### यह सभी देखें

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2/)
* class [XpsGraphicContext](../xpsdevice.xpsgraphiccontext/)
* class [XpsRenderingOptions](../xpsrenderingoptions/)
* नाम स्थान [Aspose.Html.Rendering.Xps](../../aspose.html.rendering.xps/)
* सभा [Aspose.HTML](../../)



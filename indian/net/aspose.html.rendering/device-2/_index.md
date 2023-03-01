---
title: Class DeviceTGraphicContextTRenderingOptions
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Aspose.Html.Rendering.Device2TGraphicContextTRenderingOptions कक्ष. कर्यन्वयन वशेष रेंडरंग उपकरणं के लए आधर वर्ग क प्रतनधत्व करत है
type: docs
weight: 4140
url: /hi/net/aspose.html.rendering/device-2/
---
## Device&lt;TGraphicContext,TRenderingOptions&gt; class

कार्यान्वयन विशेष रेंडरिंग उपकरणों के लिए आधार वर्ग का प्रतिनिधित्व करता है।

```csharp
public abstract class Device<TGraphicContext, TRenderingOptions> : IDevice
    where TGraphicContext : GraphicContext, new()
    where TRenderingOptions : RenderingOptions
```

| पैरामीटर | विवरण |
| --- | --- |
| TGraphicContext | ग्राफिक संदर्भ जो वर्तमान ग्राफिक्स नियंत्रण पैरामीटर रखता है |
| TRenderingOptions | प्रतिपादन विकल्प |

## गुण

| नाम | विवरण |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } | ग्राफिक संदर्भ प्राप्त करता है |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } | रेंडरिंग विकल्प प्राप्त करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| abstract [AddRect](../../aspose.html.rendering/device-2/addrect/)(RectangleF) | एक पूर्ण उपपथ के रूप में वर्तमान पथ में एक आयत जोड़ता है। |
| virtual [BeginDocument](../../aspose.html.rendering/device-2/begindocument/)(Document) | दस्तावेज़ का प्रतिपादन शुरू करता है। |
| abstract [BeginElement](../../aspose.html.rendering/device-2/beginelement/)(Element, RectangleF) | नोड का प्रतिपादन शुरू करता है। |
| virtual [BeginPage](../../aspose.html.rendering/device-2/beginpage/)(SizeF) | नए पेज की रेंडरिंग शुरू करता है। |
| abstract [Clip](../../aspose.html.rendering/device-2/clip/)(FillMode) | भरने के क्षेत्र को निर्धारित करने के लिए फिलमोड नियम का उपयोग करके वर्तमान क्लिपिंग पथ को वर्तमान पथ से काटकर संशोधित करता है। यह विधि वर्तमान पथ को समाप्त करती है। |
| abstract [ClosePath](../../aspose.html.rendering/device-2/closepath/)() | वर्तमान बिंदु से उपपथ के प्रारंभिक बिंदु तक एक सीधी रेखा खंड जोड़कर वर्तमान उपपथ को बंद करता है। यदि वर्तमान उपपथ पहले से ही बंद है, तो "ClosePath" कुछ नहीं करता है। यह ऑपरेटर वर्तमान उपपथ को समाप्त कर देता है। वर्तमान पथ में एक और खंड जोड़ने से एक नया उपपथ शुरू होता है, भले ही नया खंड "क्लोजपाथ" विधि द्वारा पहुंचे समापन बिंदु पर शुरू होता है। |
| abstract [CubicBezierTo](../../aspose.html.rendering/device-2/cubicbezierto/)(PointF, PointF, PointF) | एक घन बेज़ियर वक्र को वर्तमान पथ में जोड़ता है। वक्र वर्तमान बिंदु से बिंदु pt2, तक pt1 और pt2 को बेज़ियर नियंत्रण बिंदुओं के रूप में उपयोग करता है। नया वर्तमान बिंदु pt3. है |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() | अप्रबंधित संसाधनों को मुक्त करने, जारी करने या रीसेट करने से संबंधित एप्लिकेशन-परिभाषित कार्य करता है। |
| abstract [DrawImage](../../aspose.html.rendering/device-2/drawimage/)(byte[], ImageType, RectangleF) | निर्दिष्ट छवि बनाता है। |
| virtual [EndDocument](../../aspose.html.rendering/device-2/enddocument/)() | दस्तावेज़ का प्रतिपादन समाप्त करता है। |
| abstract [EndElement](../../aspose.html.rendering/device-2/endelement/)(Element) | नोड का प्रतिपादन समाप्त करता है। |
| virtual [EndPage](../../aspose.html.rendering/device-2/endpage/)() | वर्तमान पृष्ठ का प्रतिपादन समाप्त करता है। |
| abstract [Fill](../../aspose.html.rendering/device-2/fill/)(FillMode) | वर्तमान पथ से घिरे पूरे क्षेत्र को भरता है। यदि पथ में कई डिस्कनेक्ट किए गए उपपथ होते हैं, तो यह सभी उपपथों के अंदर भरता है, को एक साथ माना जाता है। यह विधि वर्तमान पथ को समाप्त करती है। |
| abstract [FillText](../../aspose.html.rendering/device-2/filltext/)(string, PointF) | निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट स्थान पर भरता है। |
| virtual [Flush](../../aspose.html.rendering/device-2/flush/)() | सभी डेटा को आउटपुट स्ट्रीम में फ़्लश करता है. |
| abstract [LineTo](../../aspose.html.rendering/device-2/lineto/)(PointF) | वर्तमान बिंदु से बिंदु (पीटी) तक एक सीधी रेखा खंड जोड़ता है। नया वर्तमान बिंदु pt. है |
| abstract [MoveTo](../../aspose.html.rendering/device-2/moveto/)(PointF) | किसी भी कनेक्टिंग लाइन सेगमेंट को छोड़ते हुए, वर्तमान बिंदु को पैरामीटर pt के निर्देशांक में ले जाकर एक नया उपपथ शुरू करता है। यदि वर्तमान पथ में पिछली पथ निर्माण विधि भी "MoveTo" थी, तो नई "MoveTo" इसे ओवरराइड कर देती है; पिछले "मूव टू" ऑपरेशन का कोई अवशेष पथ में नहीं रहता है। |
| virtual [RestoreGraphicContext](../../aspose.html.rendering/device-2/restoregraphiccontext/)() | पूरे ग्राफिक्स संदर्भ को स्टैक से पॉप करके उसके पूर्व मान पर पुनर्स्थापित करता है। |
| virtual [SaveGraphicContext](../../aspose.html.rendering/device-2/savegraphiccontext/)() | स्टैक पर संपूर्ण ग्राफ़िक्स संदर्भ की एक प्रति पुश करता है. |
| abstract [Stroke](../../aspose.html.rendering/device-2/stroke/)() | वर्तमान पथ के साथ एक रेखा को स्ट्रोक करता है। स्ट्रोक की गई रेखा पथ में प्रत्येक सीधे या घुमावदार खंड का अनुसरण करती है, इसके समानांतर भुजाओं वाले खंड पर केंद्रित होती है। पथ के प्रत्येक उपपथ को अलग से व्यवहार किया जाता है। यह विधि वर्तमान पथ को समाप्त करती है। |
| abstract [StrokeAndFill](../../aspose.html.rendering/device-2/strokeandfill/)(FillMode) | स्ट्रोक और वर्तमान पथ भरें। यह विधि वर्तमान पथ को समाप्त करती है। |
| abstract [StrokeText](../../aspose.html.rendering/device-2/stroketext/)(string, PointF) | निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट स्थान पर स्ट्रोक करता है। |

## अन्य सदस्य

| नाम | विवरण |
| --- | --- |
| class [DeviceConfiguration&lt;TGraphicContext,TRenderingOptions&gt;](device-2.deviceconfiguration-2/) | उपकरणों के लिए कॉन्फ़िगरेशन ऑब्जेक्ट का प्रतिनिधित्व करता है। |
| enum [PageWritingStrategy&lt;TGraphicContext,TRenderingOptions&gt;](device-2.pagewritingstrategy-2/) | आउटपुट स्ट्रीम\स्ट्रीम में पेज लिखने के लिए रणनीतियों के प्रकार निर्दिष्ट करता है। |

### यह सभी देखें

* interface [IDevice](../idevice/)
* class [GraphicContext](../graphiccontext/)
* class [RenderingOptions](../renderingoptions/)
* नाम स्थान [Aspose.Html.Rendering](../../aspose.html.rendering/)
* सभा [Aspose.HTML](../../)



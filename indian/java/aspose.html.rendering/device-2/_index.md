---
title: "DeviceTGraphicContextTRenderingOptions क्लास"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.rendering.Device2TGraphicContextTRenderingOptions क्लास। विशिष्ट रेंडरिंग डिवाइसों के कार्यान्वयन के लिए बेस क्लास का प्रतिनिधित्व करता है।"
type: docs

url: /hi/java/com.aspose.html.rendering/device-2/
---
## Device&lt;TGraphicContext,TRenderingOptions&gt; class

विशिष्ट रेंडरिंग डिवाइसों के कार्यान्वयन के लिए बेस क्लास का प्रतिनिधित्व करता है।

```java
public abstract class Device<TGraphicContext, TRenderingOptions> : Device, IDevice
    where TGraphicContext : GraphicContext, new()
    where TRenderingOptions : RenderingOptions
```

| Parameter | विवरण |
| --- | --- |
| TGraphicContext | ग्राफिक कॉन्टेक्स्ट जो वर्तमान ग्राफिक्स नियंत्रण पैरामीटर रखता है |
| TRenderingOptions | रेंडरिंग विकल्प |

## गुण

| नाम | विवरण |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) ग्राफिक कॉन्टेक्स्ट प्राप्त करता है |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) रेंडरिंग विकल्प प्राप्त करता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [addRect](../../com.aspose.html.rendering/device-2/addrect/)(RectangleF) | वर्तमान पाथ में एक आयत को पूर्ण सबपाथ के रूप में जोड़ता है। |
| [beginDocument](../../com.aspose.html.rendering/device-2/begindocument/)(Document) | दस्तावेज़ की रेंडरिंग शुरू करता है। |
| [beginElement](../../com.aspose.html.rendering/device-2/beginelement/)(Element, RectangleF) | नोड का रेंडरिंग शुरू करता है। |
| [beginPage](../../com.aspose.html.rendering/device-2/beginpage/)(SizeF) | नए पृष्ठ की रेंडरिंग शुरू करता है। |
| [clip](../../com.aspose.html.rendering/device-2/clip/)(FillRule) | वर्तमान क्लिपिंग पाथ को वर्तमान पाथ के साथ प्रतिच्छेद करके संशोधित करता है, FillRule का उपयोग करके भरने के क्षेत्र को निर्धारित करता है। यह मेथड वर्तमान पाथ को समाप्त करता है। |
| [closePath](../../com.aspose.html.rendering/device-2/closepath/)() | वर्तमान बिंदु से सबपाथ के प्रारंभिक बिंदु तक एक सीधी रेखा खंड जोड़कर वर्तमान सबपाथ को बंद करता है। यदि वर्तमान सबपाथ पहले से बंद है, तो "ClosePath" कुछ नहीं करता। यह ऑपरेटर वर्तमान सबपाथ को समाप्त करता है। वर्तमान पाथ में एक और खंड जोड़ने से नया सबपाथ शुरू होता है, भले ही नया खंड "ClosePath" मेथड द्वारा पहुँचे अंतिम बिंदु से शुरू हो। |
| [cubicBezierTo](../../com.aspose.html.rendering/device-2/cubicbezierto/)(PointF, PointF, PointF) | वर्तमान पाथ में एक क्यूबिक Bézier कर्व जोड़ता है। कर्व वर्तमान बिंदु से बिंदु pt2 तक विस्तारित होता है, जहाँ pt1 और pt2 को Bézier नियंत्रण बिंदु के रूप में उपयोग किया जाता है। नया वर्तमान बिंदु pt3 है। |
| [dispose](../../com.aspose.html.rendering/device-2/dispose/)() | ऐप्लिकेशन-परिभाषित कार्यों को निष्पादित करता है जो अनमैनेज्ड संसाधनों को मुक्त करने, रिलीज़ करने या रीसेट करने से संबंधित होते हैं। |
| [drawImage](../../com.aspose.html.rendering/device-2/drawimage/)(byte[], WebImageFormat, RectangleF) | निर्दिष्ट छवि को ड्रॉ करता है। |
| [endDocument](../../com.aspose.html.rendering/device-2/enddocument/)() | दस्तावेज़ की रेंडरिंग समाप्त करता है। |
| [endElement](../../com.aspose.html.rendering/device-2/endelement/)(Element) | नोड का रेंडरिंग समाप्त करता है। |
| [endPage](../../com.aspose.html.rendering/device-2/endpage/)() | वर्तमान पृष्ठ का रेंडरिंग समाप्त करता है। |
| [fill](../../com.aspose.html.rendering/device-2/fill/)(FillRule) | वर्तमान पथ द्वारा घिरे पूरे क्षेत्र को भरता है। यदि पथ में कई असंबद्ध उपपथ शामिल हों, तो यह सभी उपपथों के अंदरूनी हिस्सों को साथ में भरता है। यह विधि वर्तमान पथ को समाप्त करती है। |
| [fillText](../../com.aspose.html.rendering/device-2/filltext/)(String, PointF) | निर्दिष्ट स्थान पर निर्दिष्ट पाठ स्ट्रिंग को भरता है। |
| [flush](../../com.aspose.html.rendering/device-2/flush/)() | सभी डेटा को आउटपुट स्ट्रीम में फ्लश करता है। |
| [lineTo](../../com.aspose.html.rendering/device-2/lineto/)(PointF) | वर्तमान बिंदु से बिंदु (pt) तक एक सीधी रेखा खंड जोड़ता है। नया वर्तमान बिंदु pt है। |
| [moveTo](../../com.aspose.html.rendering/device-2/moveto/)(PointF) | वर्तमान बिंदु को पैरामीटर pt के निर्देशांक पर ले जाकर एक नया उपपथ शुरू करता है, किसी भी जोड़ने वाली रेखा खंड को छोड़ते हुए। यदि वर्तमान पथ में पिछली पथ निर्माण विधि भी "MoveTo" थी, तो नया "MoveTo" उसे अधिलेखित कर देता है; पथ में पिछले "MoveTo" ऑपरेशन का कोई अंश नहीं रहता। |
| [restoreGraphicContext](../../com.aspose.html.rendering/device-2/restoregraphiccontext/)() | स्टैक से पॉप करके पूरे ग्राफ़िक्स कॉन्टेक्स्ट को उसके पूर्व मान में पुनर्स्थापित करता है। |
| [saveGraphicContext](../../com.aspose.html.rendering/device-2/savegraphiccontext/)() | पूरे ग्राफ़िक्स कॉन्टेक्स्ट की एक प्रति स्टैक पर पुश करता है। |
| [stroke](../../com.aspose.html.rendering/device-2/stroke/)() | वर्तमान पथ के साथ एक रेखा स्ट्रोक करता है। स्ट्रोक की गई रेखा पथ के प्रत्येक सीधी या वक्र खंड का अनुसरण करती है, खंड के केंद्र में स्थित और उसके दोनों ओर समानांतर पक्षों के साथ। पथ के प्रत्येक उपपथ को अलग-अलग माना जाता है। यह विधि वर्तमान पथ को समाप्त करती है। |
| [strokeAndFill](../../com.aspose.html.rendering/device-2/strokeandfill/)(FillRule) | वर्तमान पथ को स्ट्रोक और भरता है। यह विधि वर्तमान पथ को समाप्त करती है। |
| [strokeText](../../com.aspose.html.rendering/device-2/stroketext/)(String, PointF) | निर्दिष्ट स्थान पर निर्दिष्ट पाठ स्ट्रिंग को स्ट्रोक करता है। |

## अन्य सदस्य

| नाम | विवरण |
| --- | --- |
| class [DeviceConfiguration&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2.deviceconfiguration-2) |  |
| enum [PageWritingStrategy&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2.pagewritingstrategy-2) | आउटपुट stream\streams में पृष्ठ लिखने की रणनीतियों के प्रकार निर्दिष्ट करता है। |

### संबंधित देखें

* class [Device](../device/)
* interface [IDevice](../idevice/)
* class [GraphicContext](../graphiccontext/)
* class [RenderingOptions](../renderingoptions/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)

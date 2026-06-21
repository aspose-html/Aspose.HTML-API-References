---
title: "XpsDevice क्लास"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.rendering.xps.XpsDevice क्लास। Xps दस्तावेज़ में रेंडरिंग को दर्शाता है।"
type: docs

url: /hi/java/com.aspose.html.rendering.xps/xpsdevice/
---
## XpsDevice class

एक XPS दस्तावेज़ में रेंडरिंग का प्रतिनिधित्व करता है।

```java
public class XpsDevice : Device<XpsGraphicContext, XpsRenderingOptions>
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [XpsDevice](xpsdevice/#constructor)(ICreateStreamProvider) | `XpsDevice` क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
| [XpsDevice](xpsdevice/#constructor_4)(Stream) | `XpsDevice` क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
| [XpsDevice](xpsdevice/#constructor_5)(String) | `XpsDevice` क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
| [XpsDevice](xpsdevice/#constructor_1)(XpsRenderingOptions, ICreateStreamProvider) | रेंडरिंग विकल्पों और स्ट्रीम प्रोवाइडर द्वारा `XpsDevice` क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
| [XpsDevice](xpsdevice/#constructor_2)(XpsRenderingOptions, Stream) | रेंडरिंग विकल्पों और आउटपुट स्ट्रीम द्वारा `XpsDevice` क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
| [XpsDevice](xpsdevice/#constructor_3)(XpsRenderingOptions, String) | रेंडरिंग विकल्पों और आउटपुट फ़ाइल नाम द्वारा `XpsDevice` क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [addRect](../../com.aspose.html.rendering/device-2/addrect/)(RectangleF) |  |
| [beginDocument](../../com.aspose.html.rendering/device-2/begindocument/)(Document) |  |
| [beginElement](../../com.aspose.html.rendering/device-2/beginelement/)(Element, RectangleF) |  |
| [beginPage](../../com.aspose.html.rendering/device-2/beginpage/)(SizeF) |  |
| [clip](../../com.aspose.html.rendering/device-2/clip/)(FillRule) |  |
| [closePath](../../com.aspose.html.rendering/device-2/closepath/)() |  |
| [cubicBezierTo](../../com.aspose.html.rendering/device-2/cubicbezierto/)(PointF, PointF, PointF) |  |
| [dispose](../../com.aspose.html.rendering/device-2/dispose/)() |  |
| [drawImage](../../com.aspose.html.rendering/device-2/drawimage/)(byte[], WebImageFormat, RectangleF) |  |
| [endDocument](../../com.aspose.html.rendering/device-2/enddocument/)() |  |
| [endElement](../../com.aspose.html.rendering/device-2/endelement/)(Element) |  |
| [endPage](../../com.aspose.html.rendering/device-2/endpage/)() |  |
| [fill](../../com.aspose.html.rendering/device-2/fill/)(FillRule) |  |
| [fillText](../../com.aspose.html.rendering/device-2/filltext/)(String, PointF) |  |
| [flush](../../com.aspose.html.rendering/device-2/flush/)() |  |
| [lineTo](../../com.aspose.html.rendering/device-2/lineto/)(PointF) |  |
| [moveTo](../../com.aspose.html.rendering/device-2/moveto/)(PointF) |  |
| [restoreGraphicContext](../../com.aspose.html.rendering/device-2/restoregraphiccontext/)() |  |
| [saveGraphicContext](../../com.aspose.html.rendering/device-2/savegraphiccontext/)() |  |
| [stroke](../../com.aspose.html.rendering/device-2/stroke/)() |  |
| [strokeAndFill](../../com.aspose.html.rendering/device-2/strokeandfill/)(FillRule) |  |
| [strokeText](../../com.aspose.html.rendering/device-2/stroketext/)(String, PointF) |  |

## अन्य सदस्य

| नाम | विवरण |
| --- | --- |
| class [XpsGraphicContext](../../com.aspose.html.rendering.xps/xpsdevice.xpsgraphiccontext) | XpsDevice के लिए वर्तमान ग्राफ़िक्स नियंत्रण पैरामीटर रखता है। ये पैरामीटर उस वैश्विक फ्रेमवर्क को परिभाषित करते हैं जिसमें ग्राफ़िक्स ऑपरेटर निष्पादित होते हैं। |

### संबंधित देखें

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [XpsGraphicContext](../xpsdevice.xpsgraphiccontext/)
* class [XpsRenderingOptions](../xpsrenderingoptions/)
* package [com.aspose.html.rendering.xps](../../com.aspose.html.rendering.xps/)
* package [Aspose.HTML](../../)

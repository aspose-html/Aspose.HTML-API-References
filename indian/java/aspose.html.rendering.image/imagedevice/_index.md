---
title: "ImageDevice क्लास"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.rendering.image.ImageDevice क्लास। jpeg png bmp gif tiff रास्टर फ़ॉर्मेट्स में रेंडरिंग का प्रतिनिधित्व करता है।"
type: docs

url: /hi/java/com.aspose.html.rendering.image/imagedevice/
---
## ImageDevice class

रास्टर फ़ॉर्मैट्स: jpeg, png, bmp, gif, tiff में रेंडरिंग का प्रतिनिधित्व करता है।

```java
public class ImageDevice : Device<ImageGraphicContext, ImageRenderingOptions>
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [ImageDevice](imagedevice/#constructor)(ICreateStreamProvider) | `ImageDevice` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [ImageDevice](imagedevice/#constructor_4)(Stream) | `ImageDevice` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [ImageDevice](imagedevice/#constructor_5)(String) | `ImageDevice` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [ImageDevice](imagedevice/#constructor_1)(ImageRenderingOptions, ICreateStreamProvider) | `ImageDevice` क्लास का नया उदाहरण रेंडरिंग विकल्पों और स्ट्रीम प्रोवाइडर द्वारा इनिशियलाइज़ करता है। |
| [ImageDevice](imagedevice/#constructor_2)(ImageRenderingOptions, Stream) | `ImageDevice` क्लास का नया उदाहरण रेंडरिंग विकल्पों और आउटपुट स्ट्रीम द्वारा इनिशियलाइज़ करता है। |
| [ImageDevice](imagedevice/#constructor_3)(ImageRenderingOptions, String) | `ImageDevice` क्लास का नया उदाहरण रेंडरिंग विकल्पों और आउटपुट फ़ाइल नाम द्वारा इनिशियलाइज़ करता है। |

## गुण

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
| class [ImageGraphicContext](../../com.aspose.html.rendering.image/imagedevice.imagegraphiccontext) | `ImageDevice` के लिए वर्तमान ग्राफ़िक्स नियंत्रण पैरामीटर रखता है। ये पैरामीटर वह वैश्विक फ्रेमवर्क परिभाषित करते हैं जिसमें ग्राफ़िक्स ऑपरेटर निष्पादित होते हैं। |

### संबंधित देखें

* class [ImageGraphicContext](../imagedevice.imagegraphiccontext/)
* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [ImageRenderingOptions](../imagerenderingoptions/)
* package [com.aspose.html.rendering.image](../../com.aspose.html.rendering.image/)
* package [Aspose.HTML](../../)

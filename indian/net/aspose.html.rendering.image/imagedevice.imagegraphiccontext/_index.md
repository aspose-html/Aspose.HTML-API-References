---
title: Class ImageDevice.ImageGraphicContext
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Aspose.Html.Rendering.Image.ImageDeviceImageGraphicContext कक्ष. के लए वर्तमन ग्रफक्स नयंत्रण पैरमटर रखत हैImageDevice . ये पैरमटर वैश्वक ढंचे क परभषत करते हैं जसके भतर ग्रफक्स ऑपरेटर नष्पदत करते हैं
type: docs
weight: 4310
url: /hi/net/aspose.html.rendering.image/imagedevice.imagegraphiccontext/
---
## ImageDevice.ImageGraphicContext class

के लिए वर्तमान ग्राफिक्स नियंत्रण पैरामीटर रखता है[`ImageDevice`](../imagedevice/) . ये पैरामीटर वैश्विक ढांचे को परिभाषित करते हैं जिसके भीतर ग्राफिक्स ऑपरेटर निष्पादित करते हैं।

```csharp
public class ImageGraphicContext : GraphicContext
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [ImageGraphicContext](imagegraphiccontext/)() | डिफ़ॉल्ट कंस्ट्रक्टर। |

## गुण

| नाम | विवरण |
| --- | --- |
| virtual [CharacterSpacing](../../aspose.html.rendering/graphiccontext/characterspacing/) { get; set; } | कैरेक्टर स्पेसिंग सेट करता है या प्राप्त करता है। |
| virtual [FillBrush](../../aspose.html.rendering/graphiccontext/fillbrush/) { get; set; } | ब्रश ऑब्जेक्ट को सेट या प्राप्त करता है जिसका उपयोग पथों के अंदरूनी हिस्सों को भरने के लिए किया जाता है। |
| virtual [Font](../../aspose.html.rendering/graphiccontext/font/) { get; set; } | ट्रू टाइप फॉन्ट ऑब्जेक्ट को सेट या प्राप्त करता है जिसका उपयोग टेक्स्ट को रेंडर करने के लिए किया जाता है। |
| virtual [FontSize](../../aspose.html.rendering/graphiccontext/fontsize/) { get; set; } | टेक्स्ट फ़ॉन्ट आकार सेट करता है या प्राप्त करता है। |
| virtual [FontStyle](../../aspose.html.rendering/graphiccontext/fontstyle/) { get; set; } | टेक्स्ट फ़ॉन्ट शैली सेट करता है या प्राप्त करता है। |
| virtual [LineCap](../../aspose.html.rendering/graphiccontext/linecap/) { get; set; } | स्ट्रोक किए गए किसी भी खुले पथ के लिए एंडपॉइंट के आकार को निर्दिष्ट करने वाला कोड सेट या प्राप्त करता है। |
| virtual [LineDashOffset](../../aspose.html.rendering/graphiccontext/linedashoffset/) { get; set; } | वर्तमान लाइन डैश पैटर्न का चरण ऑफ़सेट सेट या प्राप्त करता है। |
| virtual [LineDashPattern](../../aspose.html.rendering/graphiccontext/linedashpattern/) { get; set; } | पथ स्ट्रोक होने पर उपयोग किए जाने वाले डैश पैटर्न का विवरण सेट या प्राप्त करता है। |
| virtual [LineDashStyle](../../aspose.html.rendering/graphiccontext/linedashstyle/) { get; set; } | स्ट्रोक किए गए पथ की धराशायी रेखाओं की शैली प्राप्त करने के सेट. |
| virtual [LineJoin](../../aspose.html.rendering/graphiccontext/linejoin/) { get; set; } | स्ट्रोक पथ के जुड़े खंडों के बीच जोड़ों के आकार को निर्दिष्ट करने वाला कोड सेट या प्राप्त करता है। |
| virtual [LineWidth](../../aspose.html.rendering/graphiccontext/linewidth/) { get; set; } | स्ट्रोक किए जाने वाले रास्तों की मोटाई सेट करता है या प्राप्त करता है. |
| virtual [MiterLimit](../../aspose.html.rendering/graphiccontext/miterlimit/) { get; set; } | स्ट्रोक किए गए पथों के लिए माइटर्ड लाइन की अधिकतम लंबाई सेट करता है या प्राप्त करता है। यह पैरामीटर "स्पाइक्स" की लंबाई को सीमित करता है जब लाइन सेगमेंट तेज कोणों पर जुड़ते हैं। |
| virtual [StrokeBrush](../../aspose.html.rendering/graphiccontext/strokebrush/) { get; set; } | स्ट्रोक पथ के लिए उपयोग की जाने वाली ब्रश ऑब्जेक्ट को सेट या प्राप्त करता है। |
| virtual [TextInfo](../../aspose.html.rendering/graphiccontext/textinfo/) { get; } | हो जाता है[`TextInfo`](../../aspose.html.rendering/textinfo/) ऑब्जेक्ट जिसमें रेंडर किए गए टेक्स्ट के बारे में जानकारी है. |
| override [TransformationMatrix](../../aspose.html.rendering.image/imagegraphiccontext/transformationmatrix/) { get; set; } | परिवर्तन मैट्रिक्स सेट या प्राप्त करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| override [Clone](../../aspose.html.rendering.image/imagegraphiccontext/clone/)() | एक GdiGraphicContext वर्ग का एक नया उदाहरण बनाता है जिसमें मौजूदा उदाहरण के समान गुण मान होते हैं। |
| override [Transform](../../aspose.html.rendering.image/imagegraphiccontext/transform/)(Matrix) | निर्दिष्ट मैट्रिक्स को गुणा करके वर्तमान परिवर्तन मैट्रिक्स को संशोधित करें। |

### यह सभी देखें

* class [GraphicContext](../../aspose.html.rendering/graphiccontext/)
* class [ImageDevice](../imagedevice/)
* नाम स्थान [Aspose.Html.Rendering.Image](../../aspose.html.rendering.image/)
* सभा [Aspose.HTML](../../)



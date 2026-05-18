---
title: "DocDevice.DocGraphicContext क्लास"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.rendering.doc.DocDeviceDocGraphicContext क्लास। DocDevice के लिए वर्तमान ग्राफ़िक्स नियंत्रण पैरामीटर रखता है। ये पैरामीटर वह वैश्विक ढांचा परिभाषित करते हैं जिसमें ग्राफ़िक्स ऑपरेटर निष्पादित होते हैं।"
type: docs

url: /hi/java/com.aspose.html.rendering.doc/docdevice.docgraphiccontext/
---
## DocDevice.DocGraphicContext class

DocDevice के लिए वर्तमान ग्राफ़िक्स नियंत्रण पैरामीटर रखता है। ये पैरामीटर वह वैश्विक ढांचा परिभाषित करते हैं जिसमें ग्राफ़िक्स ऑपरेटर निष्पादित होते हैं।

```java
public class DocGraphicContext : GraphicContext
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [docGraphicContext](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext/.ctor)() | डिफ़ॉल्ट कंस्ट्रक्टर। |

## गुण

| नाम | विवरण |
| --- | --- |
| [characterSpacing](../../com.aspose.html.rendering/graphiccontext/characterspacing/) { get; set; } | अक्षर अंतराल सेट करता है या प्राप्त करता है। |
| [fillBrush](../../com.aspose.html.rendering/graphiccontext/fillbrush/) { get; set; } | पाथ के अंदरूनी हिस्सों को भरने के लिए उपयोग किए जाने वाले ब्रश ऑब्जेक्ट को सेट करता है या प्राप्त करता है। |
| [font](../../com.aspose.html.rendering/graphiccontext/font/) { get; set; } | पाठ रेंडर करने के लिए उपयोग किए जाने वाले ट्रू टाइप फ़ॉन्ट ऑब्जेक्ट को सेट करता है या प्राप्त करता है। |
| [fontSize](../../com.aspose.html.rendering/graphiccontext/fontsize/) { get; set; } | पाठ फ़ॉन्ट आकार सेट करता है या प्राप्त करता है। |
| [fontStyle](../../com.aspose.html.rendering/graphiccontext/fontstyle/) { get; set; } | पाठ फ़ॉन्ट शैली सेट करता है या प्राप्त करता है। |
| [lineCap](../../com.aspose.html.rendering/graphiccontext/linecap/) { get; set; } | किसी भी खुले पाथ के अंत बिंदुओं के आकार को निर्दिष्ट करने वाले कोड को सेट करता है या प्राप्त करता है। |
| [lineDashOffset](../../com.aspose.html.rendering/graphiccontext/linedashoffset/) { get; set; } | वर्तमान लाइन डैश पैटर्न के फेज़ ऑफ़सेट को सेट करता है या प्राप्त करता है। |
| [lineDashPattern](../../com.aspose.html.rendering/graphiccontext/linedashpattern/) { get; set; } | पाथ स्ट्रोक किए जाने पर उपयोग होने वाले डैश पैटर्न का विवरण सेट करता है या प्राप्त करता है। |
| [lineJoin](../../com.aspose.html.rendering/graphiccontext/linejoin/) { get; set; } | स्ट्रोक किए गए पाथ के जुड़े खंडों के बीच जॉइंट के आकार को निर्दिष्ट करने वाले कोड को सेट करता है या प्राप्त करता है। |
| [lineWidth](../../com.aspose.html.rendering/graphiccontext/linewidth/) { get; set; } | स्ट्रोक किए जाने वाले पाथ की मोटाई सेट करता है या प्राप्त करता है। |
| [miterLimit](../../com.aspose.html.rendering/graphiccontext/miterlimit/) { get; set; } | स्ट्रोक किए गए पाथ के लिए मिटर लाइन जॉइंट की अधिकतम लंबाई सेट करता है या प्राप्त करता है। यह पैरामीटर तीखे कोणों पर लाइन खंडों के जुड़ने से उत्पन्न \"स्पाइक्स\" की लंबाई को सीमित करता है। |
| [strokeBrush](../../com.aspose.html.rendering/graphiccontext/strokebrush/) { get; set; } | स्ट्रोक किए गए पाथ के लिए उपयोग किए जाने वाले ब्रश ऑब्जेक्ट को सेट करता है या प्राप्त करता है। |
| [getTextInfo](../../com.aspose.html.rendering/graphiccontext/textinfo/) रेंडर किए गए पाठ के बारे में जानकारी रखने वाला एक [`TextInfo`](../../com.aspose.html.rendering/textinfo/) ऑब्जेक्ट प्राप्त करता है। |
| [transformationMatrix](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext/transformationmatrix) { get; set; } | ट्रांसफ़ॉर्मेशन मैट्रिक्स सेट करता है या प्राप्त करता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [clone](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext/clone)() | [`GraphicContext`](../../com.aspose.html.rendering/graphiccontext/) क्लास का एक नया उदाहरण बनाता है जिसमें मौजूदा उदाहरण के समान प्रॉपर्टी मान होते हैं। |
| [transform](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext/transform)(IMatrix) | निर्दिष्ट मैट्रिक्स को गुणा करके वर्तमान ट्रांसफ़ॉर्मेशन मैट्रिक्स को संशोधित करता है। |

### संबंधित देखें

* class [GraphicContext](../../com.aspose.html.rendering/graphiccontext/)
* class [DocDevice](../docdevice/)
* package [com.aspose.html.rendering.doc](../../com.aspose.html.rendering.doc/)
* package [Aspose.HTML](../../)

---
title: "DocDevice.DocGraphicContext क्लास"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.rendering.doc.DocDeviceDocGraphicContext क्लास। DocDevice के लिए वर्तमान ग्राफिक्स नियंत्रण पैरामीटर रखता है। ये पैरामीटर उस वैश्विक फ्रेमवर्क को परिभाषित करते हैं जिसमें ग्राफिक्स ऑपरेटर कार्यान्वित होते हैं।"
type: docs

url: /hi/java/com.aspose.html.rendering.doc/docdevice.docgraphiccontext/
---
## DocDevice.DocGraphicContext class

DocDevice के लिए वर्तमान ग्राफिक्स नियंत्रण पैरामीटर रखता है। ये पैरामीटर उस वैश्विक फ्रेमवर्क को परिभाषित करते हैं जिसमें ग्राफिक्स ऑपरेटर कार्यान्वित होते हैं।

```java
public class DocGraphicContext : GraphicContext
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [docGraphicContext](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext/.ctor)() | डिफ़ॉल्ट कंस्ट्रक्टर। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [characterSpacing](../../com.aspose.html.rendering/graphiccontext/characterspacing/) { get; set; } | कैरेक्टर स्पेसिंग सेट या प्राप्त करता है। |
| [fillBrush](../../com.aspose.html.rendering/graphiccontext/fillbrush/) { get; set; } | पाथ के अंदरूनी भाग को भरने के लिए उपयोग किए जाने वाले ब्रश ऑब्जेक्ट को सेट या प्राप्त करता है। |
| [font](../../com.aspose.html.rendering/graphiccontext/font/) { get; set; } | टेक्स्ट रेंडरिंग के लिए उपयोग किए जाने वाले ट्रू टाइप फ़ॉन्ट ऑब्जेक्ट को सेट या प्राप्त करता है। |
| [fontSize](../../com.aspose.html.rendering/graphiccontext/fontsize/) { get; set; } | टेक्स्ट फ़ॉन्ट आकार सेट या प्राप्त करता है। |
| [fontStyle](../../com.aspose.html.rendering/graphiccontext/fontstyle/) { get; set; } | टेक्स्ट फ़ॉन्ट शैली सेट या प्राप्त करता है। |
| [lineCap](../../com.aspose.html.rendering/graphiccontext/linecap/) { get; set; } | किसी भी खुले पाथ के स्ट्रोक किए गए अंत बिंदुओं के आकार को निर्दिष्ट करने वाले कोड को सेट या प्राप्त करता है। |
| [lineDashOffset](../../com.aspose.html.rendering/graphiccontext/linedashoffset/) { get; set; } | वर्तमान लाइन डैश पैटर्न के फेज़ ऑफ़सेट को सेट या प्राप्त करता है। |
| [lineDashPattern](../../com.aspose.html.rendering/graphiccontext/linedashpattern/) { get; set; } | पाथ स्ट्रोक किए जाने पर उपयोग किए जाने वाले डैश पैटर्न का विवरण सेट या प्राप्त करता है। |
| [lineJoin](../../com.aspose.html.rendering/graphiccontext/linejoin/) { get; set; } | स्ट्रोक किए गए पाथ के जुड़े सेगमेंट्स के बीच जॉइंट्स के आकार को निर्दिष्ट करने वाले कोड को सेट या प्राप्त करता है। |
| [lineWidth](../../com.aspose.html.rendering/graphiccontext/linewidth/) { get; set; } | स्ट्रोक किए जाने वाले पाथ की मोटाई सेट या प्राप्त करता है। |
| [miterLimit](../../com.aspose.html.rendering/graphiccontext/miterlimit/) { get; set; } | स्ट्रोक किए गए पाथ के लिए मिटरड लाइन जॉइंट्स की अधिकतम लंबाई सेट या प्राप्त करता है। यह पैरामीटर तीखे कोणों पर लाइन सेगमेंट्स के जुड़ने पर उत्पन्न "स्पाइक्स" की लंबाई को सीमित करता है। |
| [strokeBrush](../../com.aspose.html.rendering/graphiccontext/strokebrush/) { get; set; } | स्ट्रोक किए गए पाथ के लिए उपयोग किए जाने वाले ब्रश ऑब्जेक्ट को सेट या प्राप्त करता है। |
| [getTextInfo](../../com.aspose.html.rendering/graphiccontext/textinfo/) रेंडर किए गए टेक्स्ट के बारे में जानकारी रखने वाला एक [`TextInfo`](../../com.aspose.html.rendering/textinfo/) ऑब्जेक्ट प्राप्त करता है। |
| [transformationMatrix](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext/transformationmatrix) { get; set; } | ट्रांसफ़ॉर्मेशन मैट्रिक्स सेट या प्राप्त करता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [clone](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext/clone)() | एक नया इंस्टेंस बनाता है एक [`GraphicContext`](../../com.aspose.html.rendering/graphiccontext/) क्लास का, जिसमें मौजूदा इंस्टेंस के समान प्रॉपर्टी मान होते हैं। |
| [transform](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext/transform)(IMatrix) | निर्दिष्ट मैट्रिक्स को गुणा करके वर्तमान ट्रांसफ़ॉर्मेशन मैट्रिक्स को संशोधित करता है। |

### संबंधित देखें

* class [GraphicContext](../../com.aspose.html.rendering/graphiccontext/)
* class [DocDevice](../docdevice/)
* package [com.aspose.html.rendering.doc](../../com.aspose.html.rendering.doc/)
* package [Aspose.HTML](../../)

---
title: "ITextureBrush इंटरफ़ेस"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.drawing.ITextureBrush इंटरफ़ेस। एक ब्रश इंटरफ़ेस को परिभाषित करता है जो किसी आकार के अंदरूनी भाग को भरने के लिए छवि का उपयोग करता है।"
type: docs

url: /hi/java/com.aspose.html.drawing/itexturebrush/
---
## ITextureBrush interface

एक छवि का उपयोग करके आकार के अंदरूनी भाग को भरने वाले ब्रश इंटरफ़ेस को परिभाषित करता है।

```java
public interface ITextureBrush : ITransformableBrush
```

## गुण

| नाम | विवरण |
| --- | --- |
| [getColorMap](../../com.aspose.html.drawing/itexturebrush/colormap/) तत्वों की संख्या सम होनी चाहिए। प्रत्येक सम तत्व पुराना रंग है। प्रत्येक विषम तत्व नया रंग है। |
| [getImage](../../com.aspose.html.drawing/itexturebrush/image/) ब्रश द्वारा उपयोग की जाने वाली छवि को प्राप्त करता है या सेट करता है। |
| [getImageArea](../../com.aspose.html.drawing/itexturebrush/imagearea/) ब्रश द्वारा उपयोग की जाने वाली छवि के भाग को निर्दिष्ट करता है। यदि यह RectangleF.Empty के बराबर है तो पूरी छवि उपयोग की जाएगी। निर्देशांक पिक्सेल में हैं। |
[getOpacity]
[setOpacity] Get opacity value in a color transform matrix. |

### संबंधित देखें

* interface [ITransformableBrush](../itransformablebrush/)
* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)

---
title: "ImageRenderingOptions क्लास"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.rendering.image.ImageRenderingOptions क्लास। ImageDevice के लिए रेंडरिंग विकल्पों का प्रतिनिधित्व करता है। यह विकल्प आउटपुट इमेज फ़ॉर्मेट, संपीड़न, रिज़ॉल्यूशन आदि निर्दिष्ट करने के लिए उपयोग किया जाता है।"
type: docs

url: /hi/java/com.aspose.html.rendering.image/imagerenderingoptions/
---
## ImageRenderingOptions class

[`ImageDevice`](../imagedevice/) के लिए रेंडरिंग विकल्पों का प्रतिनिधित्व करता है। यह विकल्प आउटपुट इमेज फ़ॉर्मेट, संपीड़न, रिज़ॉल्यूशन आदि निर्दिष्ट करने के लिए उपयोग किया जाता है।

```java
public class ImageRenderingOptions : RenderingOptions
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [ImageRenderingOptions](imagerenderingoptions/#constructor)() | `ImageRenderingOptions` क्लास का नया इंस्टेंस प्रारंभ करता है; डिफ़ॉल्ट इमेज फ़ॉर्मेट के रूप में Png उपयोग किया जाएगा। |
| [ImageRenderingOptions](imagerenderingoptions/#constructor_1)(ImageFormat) | निर्दिष्ट इमेज फ़ॉर्मेट के साथ `ImageRenderingOptions` क्लास का नया इंस्टेंस प्रारंभ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
[getCompression]
[setCompression] Sets or gets Tagged Image File Format (TIFF) [`Compression`](../compression/). By default this property is LZW. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) एक [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) ऑब्जेक्ट प्राप्त करता है जो css प्रॉपर्टी प्रोसेसिंग के कॉन्फ़िगरेशन के लिए उपयोग किया जाता है। |
[getFormat]
[setFormat] Sets or gets [`ImageFormat`](../imageformat/). By default this property is Png. |
| [horizontalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | आउटपुट और आंतरिक (जो फ़िल्टर प्रोसेसिंग के दौरान उपयोग होते हैं) इमेजों के लिए क्षैतिज रिज़ॉल्यूशन को सेट या प्राप्त करता है, पिक्सेल प्रति इंच में। डिफ़ॉल्ट रूप से यह प्रॉपर्टी 300 dpi है। |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) एक पेज सेटअप ऑब्जेक्ट प्राप्त करता है जो आउटपुट पेज-सेट के कॉन्फ़िगरेशन के लिए उपयोग किया जाता है। |
| [getText](../../com.aspose.html.rendering.image/imagerenderingoptions/text/) एक [`TextOptions`](../textoptions/) ऑब्जेक्ट प्राप्त करता है जिसका उपयोग टेक्स्ट रेंडरिंग के कॉन्फ़िगरेशन के लिए किया जाता है। |
[getUseAntialiasing]
[setUseAntialiasing] Specifies whether to use antialiasing. By default, antialiasing is enabled. |
| [verticalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | आउटपुट और आंतरिक (जो फ़िल्टर प्रोसेसिंग के दौरान उपयोग होते हैं) इमेजों के लिए ऊर्ध्वाधर रिज़ॉल्यूशन को सेट या प्राप्त करता है, पिक्सेल प्रति इंच में। डिफ़ॉल्ट रूप से यह प्रॉपर्टी 300 dpi है। |

### संबंधित देखें

* class [RenderingOptions](../../com.aspose.html.rendering/renderingoptions/)
* package [com.aspose.html.rendering.image](../../com.aspose.html.rendering.image/)
* package [Aspose.HTML](../../)

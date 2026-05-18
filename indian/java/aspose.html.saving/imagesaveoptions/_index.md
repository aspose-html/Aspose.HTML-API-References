---
title: "ImageSaveOptions क्लास"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.saving.ImageSaveOptions क्लास। विशिष्ट विकल्प डेटा क्लास। यह इमेज परिणाम रिज़ॉल्यूशन, स्मूदिंग, क्वालिटी, फॉर्मेट तथा पेज सेटिंग्स आदि को प्रबंधित करने के लिए प्रॉपर्टीज़ प्रदान करता है। अधिक जानकारी आप दस्तावेज़ लेख में प्राप्त कर सकते हैं।"
type: docs

url: /hi/java/com.aspose.html.saving/imagesaveoptions/
---
## ImageSaveOptions class

विशिष्ट विकल्पों की डेटा क्लास। यह छवि परिणाम रिज़ॉल्यूशन, स्मूदिंग गुणवत्ता, फ़ॉर्मेट तथा पेज सेटिंग्स आदि को प्रबंधित करने के लिए गुण प्रदान करती है। अधिक जानकारी आप दस्तावेज़ में प्राप्त कर सकते हैं [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#save-options).

```java
public class ImageSaveOptions : ImageRenderingOptions
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [ImageSaveOptions](imagesaveoptions/#constructor)() | `ImageSaveOptions` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है; डिफ़ॉल्ट इमेज फॉर्मेट के रूप में Png उपयोग किया जाएगा। |
| [ImageSaveOptions](imagesaveoptions/#constructor_1)(ImageFormat) | इमेज फॉर्मेट [`ImageFormat`](../../com.aspose.html.rendering.image/imageformat/) इनिशियलाइज़ेशन पर आधारित |

## गुण

| नाम | विवरण |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
[getCompression]
[setCompression] Sets or gets Tagged Image File Format (TIFF) [`Compression`](../../com.aspose.html.rendering.image/compression/). By default this property is LZW. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) एक [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) ऑब्जेक्ट प्राप्त करता है जिसका उपयोग CSS प्रॉपर्टीज़ प्रोसेसिंग की कॉन्फ़िगरेशन के लिए किया जाता है। |
[getFormat]
[setFormat] Sets or gets [`ImageFormat`](../../com.aspose.html.rendering.image/imageformat/). By default this property is Png. |
| [horizontalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | आउटपुट और इंटरनल (जो फ़िल्टर प्रोसेसिंग के दौरान उपयोग होते हैं) इमेजेज़ के लिए क्षैतिज रिज़ॉल्यूशन सेट या प्राप्त करता है, पिक्सेल प्रति इंच में। डिफ़ॉल्ट रूप से यह प्रॉपर्टी 300 dpi है। |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) एक पेज सेटअप ऑब्जेक्ट प्राप्त करता है जिसका उपयोग आउटपुट पेज-सेट की कॉन्फ़िगरेशन के लिए किया जाता है। |
| [getText](../../com.aspose.html.rendering.image/imagerenderingoptions/text/) एक [`TextOptions`](../../com.aspose.html.rendering.image/textoptions/) ऑब्जेक्ट प्राप्त करता है जिसका उपयोग टेक्स्ट रेंडरिंग की कॉन्फ़िगरेशन के लिए किया जाता है। |
[getUseAntialiasing]
[setUseAntialiasing] Specifies whether to use antialiasing. By default, antialiasing is enabled. |
| [verticalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | आउटपुट और इंटरनल (जो फ़िल्टर प्रोसेसिंग के दौरान उपयोग होते हैं) इमेजेज़ के लिए लंबवत रिज़ॉल्यूशन सेट या प्राप्त करता है, पिक्सेल प्रति इंच में। डिफ़ॉल्ट रूप से यह प्रॉपर्टी 300 dpi है। |

## टिप्पणियाँ

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.drawing;
import com.aspose.html.rendering.image;
import com.aspose.html.saving;
...
      // एक स्रोत HTML फ़ाइल का पथ तैयार करें
      String documentPath = Path.Combine(DataDir, "nature.html");

      // परिवर्तित फ़ाइल को सहेजने के लिए पथ तैयार करें 
      String savePath = Path.Combine(OutputDir, "nature-output-options.png");

      // फ़ाइल से एक HTML दस्तावेज़ प्रारंभ करें
      using var document = new HTMLDocument(documentPath);

      // ImageSaveOptions को इनिशियलाइज़ करें       
      var options = new ImageSaveOptions()
      {
        SmoothingMode = SmoothingMode.Default,
        HorizontalResolution = 100,
        VerticalResolution = 100,
        BackgroundColor = Color.Beige
      };

      // HTML को PNG में कनवर्ट करें
      Converter.ConvertHTML(document, options, savePath);
```

### संबंधित देखें

* class [ImageRenderingOptions](../../com.aspose.html.rendering.image/imagerenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)

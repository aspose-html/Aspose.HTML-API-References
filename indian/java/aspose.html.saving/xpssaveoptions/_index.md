---
title: "XpsSaveOptions क्लास"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.saving.XpsSaveOptions क्लास। विशिष्ट विकल्प डेटा क्लास कुछ गुण प्रदान करती है जिससे रूपांतरण परिणाम को प्रबंधित किया जा सके। उदाहरण के लिए PageSetup पृष्ठ की विशेषताओं को निर्दिष्ट करता है। दस्तावेज़ लेख देखें।"
type: docs

url: /hi/java/com.aspose.html.saving/xpssaveoptions/
---
## XpsSaveOptions class

विशिष्ट विकल्प डेटा क्लास कुछ गुण प्रदान करती है जिससे रूपांतरण परिणाम को प्रबंधित किया जा सके। उदाहरण के लिए [`PageSetup`](../../com.aspose.html.rendering/pagesetup/) पृष्ठ की विशेषताओं को निर्दिष्ट करता है। दस्तावेज़ [लेख](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#save-options) देखें।

```java
public class XpsSaveOptions : XpsRenderingOptions
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [XpsSaveOptions](xpssaveoptions/)() | डिफ़ॉल्ट कंस्ट्रक्टर। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) एक [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) ऑब्जेक्ट प्राप्त करता है जो css प्रॉपर्टी प्रोसेसिंग के कॉन्फ़िगरेशन के लिए उपयोग किया जाता है। |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | आंतरिक (जो फ़िल्टर प्रोसेसिंग के दौरान उपयोग होते हैं) छवियों के लिए क्षैतिज रिज़ॉल्यूशन को सेट या प्राप्त करता है, पिक्सेल प्रति इंच में। डिफ़ॉल्ट रूप से यह प्रॉपर्टी 300 dpi है। |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) एक पेज सेटअप ऑब्जेक्ट प्राप्त करता है जो आउटपुट पेज-सेट के कॉन्फ़िगरेशन के लिए उपयोग किया जाता है। |
| [verticalResolution](../../com.aspose.html.rendering/renderingoptions/verticalresolution/) { get; set; } | आंतरिक (जो फ़िल्टर प्रोसेसिंग के दौरान उपयोग होते हैं) छवियों के लिए ऊर्ध्वाधर रिज़ॉल्यूशन को सेट या प्राप्त करता है, पिक्सेल प्रति इंच में। डिफ़ॉल्ट रूप से यह प्रॉपर्टी 300 dpi है। |

## Remarks

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) पर पूर्ण उदाहरण और डेटा फ़ाइलें पा सकते हैं।

## उदाहरण

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
...
	  String documentPath = Path.Combine(OutputDir, "save-options.html");
      String savePath = Path.Combine(OutputDir, "save-options-output.xps");

      // HTML कोड तैयार करें और इसे फ़ाइल में सहेजें
      var code = "<h1> XpsSaveOptions Class</h1>\r\n" +
            "<p>Using XpsSaveOptions Class, you can programmatically apply a wide range of conversion parameters such as BackgroundColor, PageSetup, etc.</p>\r\n";

      File.WriteAllText(documentPath, code);

      // HTML फ़ाइल से एक HTML दस्तावेज़ प्रारंभ करें
      using var document = new HTMLDocument(documentPath);
       
      // पृष्ठ‑आकार, मार्जिन सेट करें और पृष्ठभूमि रंग को AntiqueWhite में बदलें
      var options = new XpsSaveOptions()
      {
        BackgroundColor = Color.AntiqueWhite
      };
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(Length.FromInches(4.9f), Length.FromInches(3.5f)), new Margin(30, 20, 10, 10));

      // HTML को XPS में परिवर्तित करें
      Converter.ConvertHTML(document, options, savePath); 
```

### संबंधित देखें

* class [XpsRenderingOptions](../../com.aspose.html.rendering.xps/xpsrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)

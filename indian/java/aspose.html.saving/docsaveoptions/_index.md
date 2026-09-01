---
title: "DocSaveOptions क्लास"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.saving.DocSaveOptions क्लास। विशिष्ट विकल्प डेटा क्लास। गुणों को असाइन करके आप रेंडरिंग विशेषताओं जैसे रिज़ॉल्यूशन, पृष्ठ आकार, पृष्ठभूमि रंग तथा दस्तावेज़‑विशिष्ट विकल्प जैसे फ़ॉन्ट एम्बेडिंग को प्रबंधित कर सकते हैं। अधिक जानकारी के लिए दस्तावेज़ लेख देखें।"
type: docs

url: /hi/java/com.aspose.html.saving/docsaveoptions/
---
## DocSaveOptions class

विशिष्ट विकल्पों की डेटा क्लास। गुणों को असाइन करके आप रिज़ॉल्यूशन, पेज आकार, बैकग्राउंड रंग जैसी रेंडरिंग विशेषताओं तथा फ़ॉन्ट एम्बेडिंग जैसे दस्तावेज़-विशिष्ट विकल्पों को प्रबंधित कर सकते हैं। अधिक जानकारी के लिए दस्तावेज़ देखें [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#save-options).

```java
public class DocSaveOptions : DocRenderingOptions
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [DocSaveOptions](docsaveoptions/)() | डिफ़ॉल्ट कंस्ट्रक्टर। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) एक [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) ऑब्जेक्ट प्राप्त करता है जो css प्रॉपर्टी प्रोसेसिंग के कॉन्फ़िगरेशन के लिए उपयोग किया जाता है। |
[getDocumentFormat]
[setDocumentFormat] Gets or sets the file format of the output document. The default value is DOCX. |
[getFontEmbeddingRule]
[setFontEmbeddingRule] Gets or sets the font embedding rule. The default value is None. |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | आंतरिक (जो फ़िल्टर प्रोसेसिंग के दौरान उपयोग होते हैं) छवियों के लिए क्षैतिज रिज़ॉल्यूशन को सेट या प्राप्त करता है, पिक्सेल प्रति इंच में। डिफ़ॉल्ट रूप से यह प्रॉपर्टी 300 dpi है। |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) एक पेज सेटअप ऑब्जेक्ट प्राप्त करता है जो आउटपुट पेज-सेट के कॉन्फ़िगरेशन के लिए उपयोग किया जाता है। |
| [verticalResolution](../../com.aspose.html.rendering/renderingoptions/verticalresolution/) { get; set; } | आंतरिक (जो फ़िल्टर प्रोसेसिंग के दौरान उपयोग होते हैं) छवियों के लिए ऊर्ध्वाधर रिज़ॉल्यूशन को सेट या प्राप्त करता है, पिक्सेल प्रति इंच में। डिफ़ॉल्ट रूप से यह प्रॉपर्टी 300 dpi है। |

## Remarks

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.drawing;
import com.aspose.html.saving;
import System;
...
 // एक स्रोत HTML फ़ाइल का पथ तैयार करें
      String documentPath = Path.Combine(DataDir, "canvas.html");

      // परिवर्तित फ़ाइल को सहेजने के लिए पथ तैयार करें 
      String savePath = Path.Combine(OutputDir, "canvas-output-options.docx");

      // फ़ाइल से एक HTML दस्तावेज़ प्रारंभ करें
      using var document = new HTMLDocument(documentPath);

      // DocSaveOptions को प्रारंभ करें। पृष्ठ‑आकार 600x400 पिक्सेल और मार्जिन सेट करें
      var options = new DocSaveOptions();
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(600, 400), new Margin(10, 10, 10, 10));

      // HTML को DOCX में परिवर्तित करें
      Converter.ConvertHTML(document, options, savePath);
```

*OutputDir - custom output folder path.

### संबंधित देखें

* class [DocRenderingOptions](../../com.aspose.html.rendering.doc/docrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)

---
title: "PdfSaveOptions क्लास"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.saving.PdfSaveOptions क्लास। विशिष्ट डेटा क्लास कुछ प्रॉपर्टीज़ प्रदान करता है जो रूपांतरण परिणाम को प्रबंधित करती हैं। उदाहरण के लिए PageSetup पृष्ठ की विशेषताओं को निर्दिष्ट करता है। दस्तावेज़ लेख देखें।"
type: docs

url: /hi/java/com.aspose.html.saving/pdfsaveoptions/
---
## PdfSaveOptions class

विशिष्ट डेटा क्लास कुछ प्रॉपर्टीज़ प्रदान करता है जो रूपांतरण परिणाम को प्रबंधित करती हैं। उदाहरण के लिए [`PageSetup`](../../com.aspose.html.rendering/pagesetup/) पृष्ठ की विशेषताओं को निर्दिष्ट करता है। दस्तावेज़ [लेख](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions) देखें।

```java
public class PdfSaveOptions : PdfRenderingOptions
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | डिफ़ॉल्ट कंस्ट्रक्टर। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) एक [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) ऑब्जेक्ट प्राप्त करता है जो css प्रॉपर्टी प्रोसेसिंग के कॉन्फ़िगरेशन के लिए उपयोग किया जाता है। |
| [getDocumentInfo](../../com.aspose.html.rendering.pdf/pdfrenderingoptions/documentinfo/) आउटपुट PDF दस्तावेज़ के बारे में जानकारी रखता है। |
[getEncryption]
[setEncryption] Gets or sets a encryption details. If not set, then no encryption will be performed. |
[getFormFieldBehaviour]
[setFormFieldBehaviour] Specifies the behavior of form fields in the output PDF document. |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | आंतरिक (जो फ़िल्टर प्रोसेसिंग के दौरान उपयोग होते हैं) छवियों के लिए क्षैतिज रिज़ॉल्यूशन को सेट या प्राप्त करता है, पिक्सेल प्रति इंच में। डिफ़ॉल्ट रूप से यह प्रॉपर्टी 300 dpi है। |
[getIsTaggedPdf]
[setIsTaggedPdf] Creates a tag structure if `true`. |
[getJpegQuality]
[setJpegQuality] Specifies the quality of JPEG compression for images (if JPEG compression is used). Default is 95. |
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
 	 // एक स्रोत HTML फ़ाइल का पथ तैयार करें
      String documentPath = Path.Combine(DataDir, "drawing.html");

      // परिवर्तित फ़ाइल को सहेजने के लिए पथ तैयार करें 
      String savePath = Path.Combine(OutputDir, "drawing-options.pdf");

      // फ़ाइल से एक HTML दस्तावेज़ प्रारंभ करें
      using var document = new HTMLDocument(documentPath);

      // PdfSaveOptions को प्रारंभ करें। पृष्ठ आकार 600x300 पिक्सेल, मार्जिन सेट करें, 
      // रिज़ॉल्यूशन और पृष्ठभूमि रंग को AliceBlue में बदलें 
      var options = new PdfSaveOptions()
      {         
        HorizontalResolution = 200,
        VerticalResolution = 200,
        BackgroundColor = Color.AliceBlue,
        JpegQuality = 100
      };
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(600, 300), new Margin(20, 10, 10, 10));      

      // HTML को PDF में परिवर्तित करें
      Converter.ConvertHTML(document, options, savePath);
```

### संबंधित देखें

* class [PdfRenderingOptions](../../com.aspose.html.rendering.pdf/pdfrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)

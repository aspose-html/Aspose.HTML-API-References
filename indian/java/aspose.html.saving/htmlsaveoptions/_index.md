---
title: "HTMLSaveOptions Class"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.saving.HTMLSaveOptions class. HTML सहेजने के विकल्पों का प्रतिनिधित्व करता है। विशिष्ट प्रॉपर्टी असाइन करके आप संसाधन प्रोसेसिंग को प्रबंधित कर सकते हैं जैसे अधिकतम हैंडलिंग गहराई आदि। अधिक जानकारी के लिए दस्तावेज़ लेख देखें।"
type: docs

url: /hi/java/com.aspose.html.saving/htmlsaveoptions/
---
## HTMLSaveOptions class

HTML सहेजने के विकल्पों का प्रतिनिधित्व करता है। विशिष्ट गुणों को असाइन करके आप अधिकतम हैंडलिंग गहराई आदि जैसे संसाधन प्रोसेसिंग को प्रबंधित कर सकते हैं। अधिक जानकारी के लिए दस्तावेज़ देखें [article](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/).

```java
public class HTMLSaveOptions : SaveOptions
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [HTMLSaveOptions](htmlsaveoptions/)() | डिफ़ॉल्ट कंस्ट्रक्टर। |

## गुण

| नाम | विवरण |
| --- | --- |
[getDocumentType]
[setDocumentType] Gets or sets the output document type. |
| [getResourceHandlingOptions](../../com.aspose.html.saving/saveoptions/resourcehandlingoptions/) एक [`ResourceHandlingOptions`](../resourcehandlingoptions/) ऑब्जेक्ट प्राप्त करता है जिसका उपयोग रिसोर्स हैंडलिंग की कॉन्फ़िगरेशन के लिए किया जाता है। |
[getSerializeInputValue]
[setSerializeInputValue] This option controls whether to serialize the value of the [`HTMLInputElement`](../../com.aspose.html/htmlinputelement/)'s or the [`HTMLTextAreaElement`](../../com.aspose.html/htmltextareaelement/)'s "value" property into the "value" attribute. |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| const [AUTO](../../com.aspose.html.saving/htmlsaveoptions/auto/) | आउटपुट दस्तावेज़ प्रकार स्वचालित रूप से चुना जाएगा। |
| const [HTML](../../com.aspose.html.saving/htmlsaveoptions/html/) | दस्तावेज़ को HTML के रूप में सहेजा जाएगा। |
| const [XHTML](../../com.aspose.html.saving/htmlsaveoptions/xhtml/) | दस्तावेज़ को XHTML के रूप में सहेजा जाएगा। |

## टिप्पणियाँ

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import Aspose.Html;
import com.aspose.html.dom.svg;
import com.aspose.html.saving;
import System;
...
     // HTML दस्तावेज़ के लिए आउटपुट पाथ तैयार करें 
      String documentPath = Path.Combine(OutputDir, "save-with-linked-file.html");

      // लिंक्ड दस्तावेज़ के साथ एक साधारण HTML फ़ाइल तैयार करें
      File.WriteAllText(documentPath, "<p>Hello World!</p>" +
                      "<a href='linked.html'>linked file</a>");

      // एक साधारण लिंक्ड HTML फ़ाइल तैयार करें
      File.WriteAllText(Path.Combine(OutputDir, "linked.html"), "<p>Hello linked file!</p>");

      // "save-with-linked-file.html" को मेमोरी में लोड करें
      using (var document = new HTMLDocument(documentPath))
      {
        // एक सहेजने विकल्प का इंस्टेंस बनाएं
        var options = new HTMLSaveOptions();

        // The मान '0' वाली निम्न पंक्ति इस उदाहरण को सहेजते समय सभी अन्य जुड़े HTML‑फ़ाइलों को काट देती है
        // यदि आप इस पंक्ति को हटाते हैं या मान को '1' में बदलते हैं, तो 'linked.html' फ़ाइल भी आउटपुट फ़ोल्डर में सहेजी जाएगी
        options.ResourceHandlingOptions.MaxHandlingDepth = 1;

        // दस्तावेज़ को सहेजने के विकल्पों के साथ सहेजें
        document.Save(Path.Combine(OutputDir, "save-with-linked-file_out.html"), options);
      }
```

*OutputDir - user output folder.

### संबंधित देखें

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)

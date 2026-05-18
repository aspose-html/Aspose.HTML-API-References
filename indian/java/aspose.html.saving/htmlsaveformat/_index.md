---
title: "HTMLSaveFormat एनम"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.saving.HTMLSaveFormat एनम। वह प्रारूप निर्दिष्ट करता है जिसमें दस्तावेज़ सहेजा जाता है। आप लेख में HTMLDocument को सहेजने के बारे में अधिक जानकारी पा सकते हैं"
type: docs

url: /hi/java/com.aspose.html.saving/htmlsaveformat/
---
## HTMLSaveFormat enumeration

दस्तावेज़ के सहेजे जाने वाले प्रारूप को निर्दिष्ट करता है। आप [`HTMLDocument`](../../com.aspose.html/htmldocument/) को सहेजने के बारे में अधिक जानकारी [लेख](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) में पा सकते हैं।

```java
public enum HTMLSaveFormat
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| Original | `0` | दस्तावेज़ को उसके मूल प्रारूप में सहेजा जाएगा। |
| Markdown | `1` | दस्तावेज़ को मार्कडाउन के रूप में सहेजा जाएगा। |
| MHTML | `2` | दस्तावेज़ को MHTML के रूप में सहेजा जाएगा। |

## टिप्पणियाँ

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
  // दस्तावेज़ सहेजने के लिए आउटपुट पथ तैयार करें
  String documentPath = Path.Combine(OutputDir, "save-to-MD.md");

  // HTML कोड तैयार करें
  var html_code = "<H2>Hello World!</H2>";
   
  // String वेरिएबल से एक दस्तावेज़ प्रारंभ करें
  using (var document = new HTMLDocument(html_code, "."))
  {
    // दस्तावेज़ को मार्कडाउन फ़ाइल के रूप में सहेजें
    document.Save(documentPath, HTMLSaveFormat.Markdown);
  }
```

*OutputDir - user output folder path.

### संबंधित देखें

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)

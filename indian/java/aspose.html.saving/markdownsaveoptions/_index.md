---
title: "MarkdownSaveOptions क्लास"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.saving.MarkdownSaveOptions क्लास। Markdown सहेजने के विकल्पों का प्रतिनिधित्व करता है। उदाहरण के लिए आप markdown फ़ॉर्मेटिंग शैली सेट कर सकते हैं, पूर्वनिर्धारित GitLab Flavored Markdown संगत विकल्पों का उपयोग कर सकते हैं और संसाधन हैंडलिंग को कॉन्फ़िगर कर सकते हैं। अधिक जानकारी के लिए लेख देखें।"
type: docs

url: /hi/java/com.aspose.html.saving/markdownsaveoptions/
---
## MarkdownSaveOptions class

Markdown सहेजने के विकल्पों का प्रतिनिधित्व करता है। उदाहरण के लिए, आप markdown फ़ॉर्मेटिंग शैली सेट कर सकते हैं, पूर्वनिर्धारित GitLab Flavored Markdown संगत विकल्पों का उपयोग कर सकते हैं और संसाधन हैंडलिंग को कॉन्फ़िगर कर सकते हैं। अधिक जानकारी के लिए देखें [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options).

```java
public class MarkdownSaveOptions : SaveOptions
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions/)() | `MarkdownSaveOptions` क्लास की एक नई इंस्टेंस को प्रारंभ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| static [getDefault](../../com.aspose.html.saving/markdownsaveoptions/default/) डिफ़ॉल्ट Markdown दस्तावेज़ीकरण के साथ संगत विकल्पों का सेट लौटाता है। |
| static [getGit](../../com.aspose.html.saving/markdownsaveoptions/git/) GitLab Flavored Markdown के साथ संगत विकल्पों का सेट लौटाता है। |
[getFeatures]
[setFeatures] Flag set that controls which elements are converted to markdown. |
[getFormatter]
[setFormatter] Gets or sets the markdown formatting style. |
| [getResourceHandlingOptions](../../com.aspose.html.saving/saveoptions/resourcehandlingoptions/) संसाधन हैंडलिंग कॉन्फ़िगरेशन के लिए उपयोग किए जाने वाले एक [`ResourceHandlingOptions`](../resourcehandlingoptions/) ऑब्जेक्ट को प्राप्त करता है। |

## Remarks

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) पर पूर्ण उदाहरण और डेटा फ़ाइलें पा सकते हैं।

## उदाहरण

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
import System.IO;
...
	 // परिवर्तित फ़ाइल को सहेजने के लिए पथ तैयार करें 
      String savePath = Path.Combine(OutputDir, "options-output.md");

      // HTML कोड तैयार करें और इसे फ़ाइल में सहेजें
      var code = "<h1>Header 1</h1>" +
            "<h2>Header 2</h2>" +
            "<p>Hello, World!!</p>" +
            "<a href='aspose.com'>aspose</a>";
      File.WriteAllText(Path.Combine(OutputDir, "options.html"), code);

      // SaveOptions की एक इंस्टेंस बनाएं और नियम सेट करें: 
      // - केवल <a> और <p> तत्वों को Markdown में परिवर्तित किया जाएगा
      var options = new MarkdownSaveOptions();
      options.Features = MarkdownFeatures.Link | MarkdownFeatures.AutomaticParagraph;

      // HTML को Markdown में परिवर्तित करने के लिए ConvertHTML मेथड को कॉल करें।
      Converter.ConvertHTML(Path.Combine(OutputDir, "options.html"), options, savePath);
```

### संबंधित देखें

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)

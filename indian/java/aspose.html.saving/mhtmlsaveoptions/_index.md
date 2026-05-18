---
title: "MHTMLSaveOptions क्लास"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.saving.MHTMLSaveOptions क्लास। MHTML सहेजने के विकल्पों का प्रतिनिधित्व करता है। विशिष्ट प्रॉपर्टीज़ असाइन करके आप रिसोर्स प्रोसेसिंग को प्रबंधित कर सकते हैं जैसे अधिकतम हैंडलिंग डेप्थ आदि। अधिक जानकारी के लिए दस्तावेज़ लेख देखें।"
type: docs

url: /hi/java/com.aspose.html.saving/mhtmlsaveoptions/
---
## MHTMLSaveOptions class

MHTML सहेजने के विकल्पों का प्रतिनिधित्व करता है। विशिष्ट गुणों को असाइन करके आप अधिकतम हैंडलिंग गहराई आदि जैसे संसाधन प्रोसेसिंग को प्रबंधित कर सकते हैं। अधिक जानकारी के लिए दस्तावेज़ देखें [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options).

```java
public class MHTMLSaveOptions : SaveOptions
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [MHTMLSaveOptions](mhtmlsaveoptions/)() | डिफ़ॉल्ट कंस्ट्रक्टर। |

## गुण

| नाम | विवरण |
| --- | --- |
| [getResourceHandlingOptions](../../com.aspose.html.saving/saveoptions/resourcehandlingoptions/) एक [`ResourceHandlingOptions`](../resourcehandlingoptions/) ऑब्जेक्ट प्राप्त करता है जिसका उपयोग रिसोर्स हैंडलिंग की कॉन्फ़िगरेशन के लिए किया जाता है। |

## टिप्पणियाँ

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) पर पा सकते हैं।

## उदाहरण

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
import System.IO;
...
	 // HTML कोड को दूसरे फ़ाइल के लिंक के साथ तैयार करें और इसे 'document.html' नाम की फ़ाइल में सहेजें
      var code = "<span>Hello, World!!</span> " +
            "<a href='document2.html'>click</a>";
      File.WriteAllText("document.html", code);

      // HTML कोड तैयार करें और इसे 'document2.html' नाम की फ़ाइल में सहेजें
      code = @"<span>Hello, World!!</span>";
      File.WriteAllText("document2.html", code);
       
      String savePath = Path.Combine(OutputDir, "output-options.mht");

      // डॉक्यूमेंट को सीधे लिंक किए गए रिसोर्सेज़ के साथ बदलने के लिए रिसोर्स लिंकिंग डेप्थ का मान 1 पर बदलें
      var options = new MHTMLSaveOptions()
      {
        ResourceHandlingOptions =
        {
          MaxHandlingDepth = 1
        }
      };

      // HTML को MHTML में बदलें
      Converter.ConvertHTML("document.html", options, savePath);  
```

### संबंधित देखें

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)

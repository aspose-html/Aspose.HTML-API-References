---
title: "MHTMLSaveOptions क्लास"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.saving.MHTMLSaveOptions क्लास। MHTML सहेजने के विकल्पों का प्रतिनिधित्व करता है। विशिष्ट प्रॉपर्टीज़ असाइन करके आप संसाधन प्रोसेसिंग को प्रबंधित कर सकते हैं जैसे अधिकतम हैंडलिंग गहराई आदि। अधिक जानकारी के लिए दस्तावेज़ लेख देखें।"
type: docs

url: /hi/java/com.aspose.html.saving/mhtmlsaveoptions/
---
## MHTMLSaveOptions class

MHTML सहेजने के विकल्पों का प्रतिनिधित्व करता है। विशिष्ट गुणों को असाइन करके आप अधिकतम हैंडलिंग गहराई आदि जैसी संसाधन प्रोसेसिंग को प्रबंधित कर सकते हैं। अधिक जानकारी के लिए दस्तावेज़ देखें [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options).

```java
public class MHTMLSaveOptions : SaveOptions
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [MHTMLSaveOptions](mhtmlsaveoptions/)() | डिफ़ॉल्ट कंस्ट्रक्टर। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
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
	 // HTML कोड को दूसरे फ़ाइल के लिंक के साथ तैयार करें और इसे फ़ाइल में 'document.html' के रूप में सहेजें
      var code = "<span>Hello, World!!</span> " +
            "<a href='document2.html'>click</a>";
      File.WriteAllText("document.html", code);

      // HTML कोड तैयार करें और इसे फ़ाइल में 'document2.html' के रूप में सहेजें
      code = @"<span>Hello, World!!</span>";
      File.WriteAllText("document2.html", code);
       
      String savePath = Path.Combine(OutputDir, "output-options.mht");

      // सीधे जुड़े संसाधनों वाले दस्तावेज़ को परिवर्तित करने के लिए संसाधन लिंकिंग गहराई का मान 1 करें
      var options = new MHTMLSaveOptions()
      {
        ResourceHandlingOptions =
        {
          MaxHandlingDepth = 1
        }
      };

      // HTML को MHTML में परिवर्तित करें
      Converter.ConvertHTML("document.html", options, savePath);  
```

### संबंधित देखें

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)

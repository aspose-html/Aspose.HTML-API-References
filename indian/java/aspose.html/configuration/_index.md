---
title: "Configuration क्लास"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.Configuration क्लास। एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने हेतु उपयोग किए जाने वाले कॉन्फ़िगरेशन कॉन्टेक्स्ट ऑब्जेक्ट का प्रतिनिधित्व करता है। कॉन्फ़िगरेशन प्रबंधन में आप कस्टम यूज़र स्टाइलशीट लागू करके दस्तावेज़ शैली को ओवरराइड कर सकते हैं या एप्लिकेशन से किसी भी वेब अनुरोध को संभाल सकते हैं तथा स्क्रिप्ट नीति को कॉन्फ़िगर कर सकते हैं। विवरण Environment Configuration गाइड में हैं।"
type: docs

url: /hi/java/com.aspose.html/configuration/
---
## Configuration class

यह कॉन्फ़िगरेशन कॉन्टेक्स्ट ऑब्जेक्ट को दर्शाता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। कॉन्फ़िगरेशन प्रबंधन में आप कस्टम यूज़र स्टाइलशीट लागू करके दस्तावेज़ शैली को ओवरराइड कर सकते हैं, या एप्लिकेशन से आने वाले वेब अनुरोधों को संभाल सकते हैं तथा स्क्रिप्ट नीति को कॉन्फ़िगर कर सकते हैं। विवरण [Environment Configuration guide](https://docs.aspose.com/html/net/working-with-documents/environment-configuration/) में उपलब्ध है।

```java
public class Configuration : IDisposable, IServiceProvider
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Configuration](configuration/)() | `class` का नया इंस्टेंस इनिशियलाइज़ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
[getSecurity]
[setSecurity] Gets or sets the sandboxing flag of the configuration. Refer to article about [sandboxing](https://docs.aspose.com/html/net/working-with-documents/environment-configuration/#sandboxing). |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| static [Create](../../com.aspose.html/configuration/create/#create)() | Configuration ऑब्जेक्ट का इंस्टेंस बनाएं और कॉन्फ़िगर करें। |
| static [Create](../../com.aspose.html/configuration/create/#create_1)(Action&lt;IConfigurationBuilder&gt;) | Configuration ऑब्जेक्ट का इंस्टेंस बनाएं और कॉन्फ़िगर करें। |
| [dispose](../../com.aspose.html/configuration/dispose/)() | अनमैनेज्ड संसाधनों को मुक्त करने, रिलीज़ करने या रीसेट करने से जुड़े एप्लिकेशन-परिभाषित कार्यों को निष्पादित करता है। |
| [getService](../../com.aspose.html/configuration/getservice/#getservice)(Type) | अनुरोधित सर्विस प्राप्त करता है। |
| [GetService&lt;T&gt;](../../com.aspose.html/configuration/getservice/#getservice_1)() | अनुरोधित सर्विस प्राप्त करता है। |

## Remarks

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System;
import System.Diagnostics;
import System.IO;
import Aspose.Html;
import com.aspose.html.net;
import com.aspose.html.services;

    // यह संदेश हैंडलर अनुरोध की प्रोसेसिंग की शुरुआत और समाप्ति के बारे में एक संदेश प्रिंट करता है।
    public class LogMessageHandler : MessageHandler
    {
      // Invoke() मेथड को ओवरराइड करें
      public void Invoke(INetworkOperationContext context)
      {
        Debug.WriteLine("Start processing request: " + context.Request.RequestUri);

        // चेन में अगले संदेश हैंडलर को Invoke करें
        Next(context);

        Debug.WriteLine("Finish processing request: " + context.Request.RequestUri);
      }
    }
```

```java
    public void CreateACustomMessageHandlerTest()
    {
      // Configuration क्लास का एक उदाहरण बनाएं
      using var configuration = new Configuration();

      // LogMessageHandler को मौजूदा संदेश हैंडलरों की श्रृंखला में जोड़ें
      var service = configuration.GetService<INetworkService>();
      var handlers = service.MessageHandlers;
           
      handlers.Insert(0, new LogMessageHandler());

      // स्रोत दस्तावेज़ फ़ाइल का पथ तैयार करें
      String documentPath = Path.Combine(DataDir, "input.htm");

      // निर्दिष्ट कॉन्फ़िगरेशन के साथ एक HTML दस्तावेज़ प्रारंभ करें
      using var document = new HTMLDocument(documentPath, configuration);
    }
```

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.net;
import com.aspose.html.saving;
import com.aspose.html.services;
import System;
import System.Collections.Generic;
import System.IO;
import System.Net;
import System.Text;

public void SandboxingSample()
    {
      // HTML कोड तैयार करें और इसे फ़ाइल में सहेजें
      var code = "<span>Hello World!!</span> " +
            "<script>document.write('Have a nice day!');</script>";

      File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

      // Configuration का एक उदाहरण बनाएं
      using (var configuration = new Configuration())
      {
        // 'scripts' को एक अविश्वसनीय संसाधन के रूप में चिह्नित करें
        configuration.Security |= Sandbox.Scripts;

        // निर्दिष्ट कॉन्फ़िगरेशन के साथ एक HTML दस्तावेज़ प्रारंभ करें
        using (var document = new HTMLDocument(Path.Combine(OutputDir, "sandboxing.html"), configuration))
        {
          // HTML को PDF में परिवर्तित करें
          Converter.ConvertHTML(document, new PdfSaveOptions(), Path.Combine(OutputDir, "sandboxing_out.pdf"));
        }
      }       
    }
```

*OutputDir - user output folder path.

### संबंधित देखें

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)

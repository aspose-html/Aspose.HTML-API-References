---
title: "Converter.ConvertMHTML"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "Converter मेथड। इनपुट स्ट्रीम द्वारा प्रस्तुत MHTML स्रोत को बदलें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित xps फ़ाइल है।"
type: docs

url: /hi/java/com.aspose.html.converters/converter/convertmhtml/
---
## ConvertMHTML(Stream, XpsSaveOptions, String) {#convertmhtml_31}

इनपुट [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) द्वारा प्रस्तुत MHTML स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित xps फ़ाइल है।

```java
public static void ConvertMHTML(Stream stream, XpsSaveOptions options, String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | इनपुट mhtml (.mht) डेटा स्ट्रीम। |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट का उपयोग आपको रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण xps फ़ाइल पथ। |

## Remarks

MHTML कनवर्टर

MHTML से [XPS](https://docs.fileformat.com/page-description-language/xps/) में रूपांतरण अक्सर विशिष्ट कार्यों के लिए XPS फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। एक XPS फ़ाइल पेज लेआउट फ़ाइलों को दर्शाती है जो XML Paper Specifications पर आधारित हैं, माइक्रोसॉफ्ट द्वारा बनाई गई।

इस [लेख](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) को देखें जहाँ आपको ConvertHTML() मेथड्स का उपयोग करके MHTML को XPS में बदलने की जानकारी मिलती है, जो कि [`Converter`](../) क्लास के हैं, तथा कैसे [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें।

MHTML को XPS में बदलें

Converter क्लास कुछ MHTML‑विशिष्ट रूपांतरण XPS में प्रदान करती है। MHTML को XPS में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय MHTML (.mht) फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप मानक या कस्टम विशिष्ट स्ट्रीम को भी रूपांतरण स्रोत के रूप में उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन का उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट बनाएं। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। Converter क्लास की ConvertMHTML() मेथड का उपयोग करके MHTML को XPS परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के अनुसार तीन या अधिक पैरामीटर होते हैं। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से MHTML को XPS में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // डिफ़ॉल्ट XpsSaveOptions ऑब्जेक्ट परिभाषित करें
      var options = new XpsSaveOptions();

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, XpsSaveOptions, String) {#convertmhtml_47}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत MHTML स्रोत को XPS में परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित XPS फ़ाइल है।

```java
public static void ConvertMHTML(String sourcePath, XpsSaveOptions options, String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourcePath | String | MHTML स्रोत का पूर्ण फ़ाइल पथ। |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट का उपयोग आपको रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण xps फ़ाइल पथ। |

## Remarks

MHTML कनवर्टर

MHTML से [XPS](https://docs.fileformat.com/page-description-language/xps/) में रूपांतरण अक्सर विशिष्ट कार्यों के लिए XPS फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। एक XPS फ़ाइल पेज लेआउट फ़ाइलों को दर्शाती है जो XML Paper Specifications पर आधारित हैं, माइक्रोसॉफ्ट द्वारा बनाई गई।

इस [लेख](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) को देखें जहाँ आपको ConvertHTML() मेथड्स का उपयोग करके MHTML को XPS में बदलने की जानकारी मिलती है, जो कि [`Converter`](../) क्लास के हैं, तथा कैसे [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें।

MHTML को XPS में बदलें

Converter क्लास कुछ MHTML‑विशिष्ट रूपांतरण XPS में प्रदान करती है। MHTML को XPS में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय MHTML (.mht) फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप मानक या कस्टम विशिष्ट स्ट्रीम को भी रूपांतरण स्रोत के रूप में उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन का उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट बनाएं। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। Converter क्लास की ConvertMHTML() मेथड का उपयोग करके MHTML को XPS परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के अनुसार तीन या अधिक पैरामीटर होते हैं। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से MHTML को XPS में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// फ़ॉर्म स्रोत फ़ाइल पथ
	var sourcePath = Path.Combine(InputFolder, "sample.mht");

	// फ़ॉर्म परिणाम फ़ाइल पथ
	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// डिफ़ॉल्ट XpsSaveOptions ऑब्जेक्ट परिभाषित करें
	var options = new XpsSaveOptions();

	// रूपांतरण प्रक्रिया शुरू करें
	Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, XpsSaveOptions, String) {#convertmhtml_15}

URL द्वारा प्रस्तुत MHTML स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित XPS फ़ाइल है।

```java
public static void ConvertMHTML(Url sourceUrl, XpsSaveOptions options, String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceUrl | Url | MHTML स्रोत दस्तावेज़ URL - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट का उपयोग आपको रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण xps फ़ाइल पथ। |

## Remarks

MHTML कनवर्टर

MHTML से [XPS](https://docs.fileformat.com/page-description-language/xps/) में रूपांतरण अक्सर विशिष्ट कार्यों के लिए XPS फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। एक XPS फ़ाइल पेज लेआउट फ़ाइलों को दर्शाती है जो XML Paper Specifications पर आधारित हैं, माइक्रोसॉफ्ट द्वारा बनाई गई।

इस [लेख](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) को देखें जहाँ आपको ConvertHTML() मेथड्स का उपयोग करके MHTML को XPS में बदलने की जानकारी मिलती है, जो कि [`Converter`](../) क्लास के हैं, तथा कैसे [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें।

MHTML को XPS में बदलें

Converter क्लास कुछ MHTML‑विशिष्ट रूपांतरण XPS में प्रदान करती है। MHTML को XPS में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय MHTML (.mht) फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप मानक या कस्टम विशिष्ट स्ट्रीम को भी रूपांतरण स्रोत के रूप में उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन का उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट बनाएं। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। Converter क्लास की ConvertMHTML() मेथड का उपयोग करके MHTML को XPS परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के अनुसार तीन या अधिक पैरामीटर होते हैं। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से MHTML को XPS में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// फ़ॉर्म स्रोत फ़ाइल पथ
	var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

	// फ़ॉर्म परिणाम फ़ाइल पथ
	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// डिफ़ॉल्ट XpsSaveOptions ऑब्जेक्ट परिभाषित करें
	var options = new XpsSaveOptions();

	// रूपांतरण प्रक्रिया शुरू करें
	Converter.ConvertMHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, XpsSaveOptions, String) {#convertmhtml_23}

इनपुट [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) द्वारा प्रस्तुत MHTML स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित XPS फ़ाइल है।

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | रूपांतरण स्रोत mhtml (.mht) डेटा स्ट्रीम। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट का उपयोग आपको रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण xps फ़ाइल पथ। |

## Remarks

MHTML कनवर्टर

MHTML से [XPS](https://docs.fileformat.com/page-description-language/xps/) में रूपांतरण अक्सर विशिष्ट कार्यों के लिए XPS फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। एक XPS फ़ाइल पेज लेआउट फ़ाइलों को दर्शाती है जो XML Paper Specifications पर आधारित हैं, माइक्रोसॉफ्ट द्वारा बनाई गई।

इस [लेख](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) को देखें जहाँ आपको ConvertHTML() मेथड्स का उपयोग करके MHTML को XPS में बदलने की जानकारी मिलती है, जो कि [`Converter`](../) क्लास के हैं, तथा कैसे [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें।

MHTML को XPS में बदलें

Converter क्लास कुछ MHTML‑विशिष्ट रूपांतरण XPS में प्रदान करती है। MHTML को XPS में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय MHTML (.mht) फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप मानक या कस्टम विशिष्ट स्ट्रीम को भी रूपांतरण स्रोत के रूप में उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन का उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट बनाएं। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। Converter क्लास की ConvertMHTML() मेथड का उपयोग करके MHTML को XPS परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के अनुसार तीन या अधिक पैरामीटर होते हैं। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से MHTML को XPS में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // डिफ़ॉल्ट XpsSaveOptions ऑब्जेक्ट परिभाषित करें
      var options = new XpsSaveOptions();

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(File.OpenRead(sourcePath), new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### संबंधित देखें

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, XpsSaveOptions, String) {#convertmhtml_39}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत MHTML स्रोत को XPS में परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित XPS फ़ाइल है।

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourcePath | String | MHTML स्रोत का पूर्ण फ़ाइल पथ। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट का उपयोग आपको रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण xps फ़ाइल पथ। |

## Remarks

MHTML कनवर्टर

MHTML से [XPS](https://docs.fileformat.com/page-description-language/xps/) में रूपांतरण अक्सर विशिष्ट कार्यों के लिए XPS फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। एक XPS फ़ाइल पेज लेआउट फ़ाइलों को दर्शाती है जो XML Paper Specifications पर आधारित हैं, माइक्रोसॉफ्ट द्वारा बनाई गई।

इस [लेख](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) को देखें जहाँ आपको ConvertHTML() मेथड्स का उपयोग करके MHTML को XPS में बदलने की जानकारी मिलती है, जो कि [`Converter`](../) क्लास के हैं, तथा कैसे [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें।

MHTML को XPS में बदलें

Converter क्लास कुछ MHTML‑विशिष्ट रूपांतरण XPS में प्रदान करती है। MHTML को XPS में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय MHTML (.mht) फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप मानक या कस्टम विशिष्ट स्ट्रीम को भी रूपांतरण स्रोत के रूप में उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन का उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट बनाएं। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। Converter क्लास की ConvertMHTML() मेथड का उपयोग करके MHTML को XPS परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के अनुसार तीन या अधिक पैरामीटर होते हैं। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से MHTML को XPS में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // डिफ़ॉल्ट XpsSaveOptions ऑब्जेक्ट परिभाषित करें
      var options = new XpsSaveOptions();

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, XpsSaveOptions, String) {#convertmhtml_7}

URL द्वारा प्रस्तुत MHTML स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित XPS फ़ाइल है।

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceUrl | Url | MHTML स्रोत दस्तावेज़ URL - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट का उपयोग आपको रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण xps फ़ाइल पथ। |

## Remarks

MHTML कनवर्टर

MHTML से [XPS](https://docs.fileformat.com/page-description-language/xps/) में रूपांतरण अक्सर विशिष्ट कार्यों के लिए XPS फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। एक XPS फ़ाइल पेज लेआउट फ़ाइलों को दर्शाती है जो XML Paper Specifications पर आधारित हैं, माइक्रोसॉफ्ट द्वारा बनाई गई।

इस [लेख](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) को देखें जहाँ आपको ConvertHTML() मेथड्स का उपयोग करके MHTML को XPS में बदलने की जानकारी मिलती है, जो कि [`Converter`](../) क्लास के हैं, तथा कैसे [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें।

MHTML को XPS में बदलें

Converter क्लास कुछ MHTML‑विशिष्ट रूपांतरण XPS में प्रदान करती है। MHTML को XPS में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय MHTML (.mht) फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप मानक या कस्टम विशिष्ट स्ट्रीम को भी रूपांतरण स्रोत के रूप में उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन का उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट बनाएं। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। Converter क्लास की ConvertMHTML() मेथड का उपयोग करके MHTML को XPS परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के अनुसार तीन या अधिक पैरामीटर होते हैं। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से MHTML को XPS में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // डिफ़ॉल्ट XpsSaveOptions ऑब्जेक्ट परिभाषित करें
      var options = new XpsSaveOptions();

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_30}

इनपुट स्ट्रीम द्वारा प्रस्तुत MHTML स्रोत को परिवर्तित करें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित होता है।

```java
public static void ConvertMHTML(Stream stream, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | रूपांतरण स्रोत mhtml (.mht) डेटा स्ट्रीम। |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट का उपयोग आपको रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। |

## Remarks

MHTML कनवर्टर

MHTML से [XPS](https://docs.fileformat.com/page-description-language/xps/) में रूपांतरण अक्सर विशिष्ट कार्यों के लिए XPS फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। एक XPS फ़ाइल पेज लेआउट फ़ाइलों को दर्शाती है जो XML Paper Specifications पर आधारित हैं, माइक्रोसॉफ्ट द्वारा बनाई गई।

इस [लेख](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) को देखें जहाँ आपको ConvertHTML() मेथड्स का उपयोग करके MHTML को XPS में बदलने की जानकारी मिलती है, जो कि [`Converter`](../) क्लास के हैं, तथा कैसे [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें।

MHTML को XPS में बदलें

Converter क्लास कुछ MHTML‑विशिष्ट रूपांतरण XPS में प्रदान करती है। MHTML को XPS में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय MHTML (.mht) फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप मानक या कस्टम विशिष्ट स्ट्रीम को भी रूपांतरण स्रोत के रूप में उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन का उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट बनाएं। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। Converter क्लास की ConvertMHTML() मेथड का उपयोग करके MHTML को XPS परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के अनुसार तीन या अधिक पैरामीटर होते हैं। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से MHTML को XPS में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;
import com.aspose.html.io;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // डिफ़ॉल्ट XpsSaveOptions ऑब्जेक्ट परिभाषित करें
      var options = new XpsSaveOptions();

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### संबंधित देखें

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_46}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत MHTML स्रोत को XPS में परिवर्तित करें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित होता है।

```java
public static void ConvertMHTML(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourcePath | String | MHTML स्रोत का पूर्ण फ़ाइल पथ। |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट का उपयोग आपको रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | ज्ञात (देखें [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन। |

## Remarks

MHTML कनवर्टर

MHTML से [XPS](https://docs.fileformat.com/page-description-language/xps/) में रूपांतरण अक्सर विशिष्ट कार्यों के लिए XPS फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। एक XPS फ़ाइल पेज लेआउट फ़ाइलों को दर्शाती है जो XML Paper Specifications पर आधारित हैं, माइक्रोसॉफ्ट द्वारा बनाई गई।

इस [लेख](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) को देखें जहाँ आपको ConvertHTML() मेथड्स का उपयोग करके MHTML को XPS में बदलने की जानकारी मिलती है, जो कि [`Converter`](../) क्लास के हैं, तथा कैसे [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें।

MHTML को XPS में बदलें

Converter क्लास कुछ MHTML‑विशिष्ट रूपांतरण XPS में प्रदान करती है। MHTML को XPS में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय MHTML (.mht) फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप मानक या कस्टम विशिष्ट स्ट्रीम को भी रूपांतरण स्रोत के रूप में उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन का उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट बनाएं। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। Converter क्लास की ConvertMHTML() मेथड का उपयोग करके MHTML को XPS परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के अनुसार तीन या अधिक पैरामीटर होते हैं। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से MHTML को XPS में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;
import com.aspose.html.io;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // डिफ़ॉल्ट XpsSaveOptions ऑब्जेक्ट परिभाषित करें
      var options = new XpsSaveOptions();

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(sourcePath, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### संबंधित देखें

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_14}

[`URL`](../../../com.aspose.html/url/) द्वारा प्रस्तुत MHTML स्रोत को परिवर्तित करें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित होता है।

```java
public static void ConvertMHTML(Url sourceUrl, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceUrl | Url | MHTML स्रोत दस्तावेज़ URL - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट का उपयोग आपको रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। |

## Remarks

MHTML कनवर्टर

MHTML से [XPS](https://docs.fileformat.com/page-description-language/xps/) में रूपांतरण अक्सर विशिष्ट कार्यों के लिए XPS फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। एक XPS फ़ाइल पेज लेआउट फ़ाइलों को दर्शाती है जो XML Paper Specifications पर आधारित हैं, माइक्रोसॉफ्ट द्वारा बनाई गई।

इस [लेख](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) को देखें जहाँ आपको ConvertHTML() मेथड्स का उपयोग करके MHTML को XPS में बदलने की जानकारी मिलती है, जो कि [`Converter`](../) क्लास के हैं, तथा कैसे [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें।

MHTML को XPS में बदलें

Converter क्लास कुछ MHTML‑विशिष्ट रूपांतरण XPS में प्रदान करती है। MHTML को XPS में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय MHTML (.mht) फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप मानक या कस्टम विशिष्ट स्ट्रीम को भी रूपांतरण स्रोत के रूप में उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन का उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट बनाएं। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। Converter क्लास की ConvertMHTML() मेथड का उपयोग करके MHTML को XPS परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के अनुसार तीन या अधिक पैरामीटर होते हैं। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से MHTML को XPS में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;
import com.aspose.html.io; 
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // डिफ़ॉल्ट XpsSaveOptions ऑब्जेक्ट परिभाषित करें
      var options = new XpsSaveOptions();

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(sourceUrl, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### संबंधित देखें

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_22}

इनपुट स्ट्रीम द्वारा प्रस्तुत MHTML स्रोत को परिवर्तित करें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित होता है।

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | रूपांतरण स्रोत mhtml (.mht) डेटा स्ट्रीम। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट का उपयोग आपको रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। |

## Remarks

MHTML कनवर्टर

MHTML से [XPS](https://docs.fileformat.com/page-description-language/xps/) में रूपांतरण अक्सर विशिष्ट कार्यों के लिए XPS फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। एक XPS फ़ाइल पेज लेआउट फ़ाइलों को दर्शाती है जो XML Paper Specifications पर आधारित हैं, माइक्रोसॉफ्ट द्वारा बनाई गई।

इस [लेख](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) को देखें जहाँ आपको ConvertHTML() मेथड्स का उपयोग करके MHTML को XPS में बदलने की जानकारी मिलती है, जो कि [`Converter`](../) क्लास के हैं, तथा कैसे [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें।

MHTML को XPS में बदलें

Converter क्लास कुछ MHTML‑विशिष्ट रूपांतरण XPS में प्रदान करती है। MHTML को XPS में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय MHTML (.mht) फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप मानक या कस्टम विशिष्ट स्ट्रीम को भी रूपांतरण स्रोत के रूप में उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन का उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट बनाएं। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। Converter क्लास की ConvertMHTML() मेथड का उपयोग करके MHTML को XPS परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के अनुसार तीन या अधिक पैरामीटर होते हैं। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से MHTML को XPS में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;
import com.aspose.html.io;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // डिफ़ॉल्ट XpsSaveOptions ऑब्जेक्ट परिभाषित करें
      var options = new XpsSaveOptions();

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### संबंधित देखें

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_38}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत MHTML स्रोत को XPS में परिवर्तित करें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित होता है।

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourcePath | String | MHTML स्रोत का पूर्ण फ़ाइल पथ। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट का उपयोग आपको रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | ज्ञात (देखें [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन। |

## Remarks

MHTML कनवर्टर

MHTML से [XPS](https://docs.fileformat.com/page-description-language/xps/) में रूपांतरण अक्सर विशिष्ट कार्यों के लिए XPS फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। एक XPS फ़ाइल पेज लेआउट फ़ाइलों को दर्शाती है जो XML Paper Specifications पर आधारित हैं, माइक्रोसॉफ्ट द्वारा बनाई गई।

इस [लेख](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) को देखें जहाँ आपको ConvertHTML() मेथड्स का उपयोग करके MHTML को XPS में बदलने की जानकारी मिलती है, जो कि [`Converter`](../) क्लास के हैं, तथा कैसे [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें।

MHTML को XPS में बदलें

Converter क्लास कुछ MHTML‑विशिष्ट रूपांतरण XPS में प्रदान करती है। MHTML को XPS में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय MHTML (.mht) फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप मानक या कस्टम विशिष्ट स्ट्रीम को भी रूपांतरण स्रोत के रूप में उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन का उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट बनाएं। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। Converter क्लास की ConvertMHTML() मेथड का उपयोग करके MHTML को XPS परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के अनुसार तीन या अधिक पैरामीटर होते हैं। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से MHTML को XPS में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // डिफ़ॉल्ट XpsSaveOptions ऑब्जेक्ट परिभाषित करें
      var options = new XpsSaveOptions();

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_6}

URL द्वारा प्रस्तुत MHTML स्रोत को परिवर्तित करें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित होता है।

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceUrl | Url | MHTML स्रोत दस्तावेज़ URL - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट का उपयोग आपको रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | ज्ञात (देखें [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन। |

## Remarks

MHTML कनवर्टर

MHTML से [XPS](https://docs.fileformat.com/page-description-language/xps/) में रूपांतरण अक्सर विशिष्ट कार्यों के लिए XPS फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। एक XPS फ़ाइल पेज लेआउट फ़ाइलों को दर्शाती है जो XML Paper Specifications पर आधारित हैं, माइक्रोसॉफ्ट द्वारा बनाई गई।

इस [लेख](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) को देखें जहाँ आपको ConvertHTML() मेथड्स का उपयोग करके MHTML को XPS में बदलने की जानकारी मिलती है, जो कि [`Converter`](../) क्लास के हैं, तथा कैसे [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें।

MHTML को XPS में बदलें

Converter क्लास कुछ MHTML‑विशिष्ट रूपांतरण XPS में प्रदान करती है। MHTML को XPS में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय MHTML (.mht) फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप मानक या कस्टम विशिष्ट स्ट्रीम को भी रूपांतरण स्रोत के रूप में उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन का उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट बनाएं। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। Converter क्लास की ConvertMHTML() मेथड का उपयोग करके MHTML को XPS परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के अनुसार तीन या अधिक पैरामीटर होते हैं। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से MHTML को XPS में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // डिफ़ॉल्ट XpsSaveOptions ऑब्जेक्ट परिभाषित करें
      var options = new XpsSaveOptions();

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, DocSaveOptions, String) {#convertmhtml_25}

इनपुट स्ट्रीम द्वारा प्रस्तुत MHTML स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित docx फ़ाइल है।

```java
public static void ConvertMHTML(Stream stream, DocSaveOptions options, String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | MHTML रूपांतरण इनपुट डेटा स्ट्रीम। |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण docx फ़ाइल पाथ। |

## Remarks

MHTML कनवर्टर

MHTML से DOCX रूपांतरण अक्सर विशिष्ट कार्यों के लिए [DOCX](https://docs.fileformat.com/word-processing/docx/) फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। DOCX माइक्रोसॉफ्ट वर्ड दस्तावेज़ों के लिए एक प्रसिद्ध फ़ॉर्मेट है। इसमें पाठ, तालिकाएँ, रास्टर और वेक्टर ग्राफ़िक्स, वीडियो, ध्वनि और आरेख सहित विभिन्न प्रकार का डेटा हो सकता है। यह फ़ॉर्मेट लोकप्रिय है क्योंकि यह जटिल फ़ॉर्मेटिंग सुविधाओं का समर्थन करता है और उपयोगकर्ताओं को किसी भी प्रकार का दस्तावेज़ लिखने के लिए विभिन्न विकल्प प्रदान करता है।

देखें [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) जहाँ आप ConvertMHTML() मेथड्स का उपयोग करके [`Converter`](../) क्लास के माध्यम से MHTML को DOCX में कैसे परिवर्तित करें और [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) तथा [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को कैसे लागू करें, इस बारे में जानकारी पा सकते हैं।

MHTML को DOCX में परिवर्तित करें

Converter क्लास कुछ MHTML-विशिष्ट रूपांतरण DOCX में प्रदान करती है। MHTML को DOCX में परिवर्तित करने के लिए, आपको कुछ सरल चरणों वाले परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय MHTML (.mht) फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप मानक या कस्टम विशिष्ट स्ट्रीम को भी रूपांतरण स्रोत के रूप में उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट बनाएँ। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। Converter क्लास की ConvertMHTML() मेथड का उपयोग करके MHTML को DOCX परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के अनुसार तीन या अधिक पैरामीटर हो सकते हैं। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से MHTML को DOCX में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // डिफ़ॉल्ट DocSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new DocSaveOptions();

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### संबंधित देखें

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, DocSaveOptions, String) {#convertmhtml_41}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत MHTML स्रोत को DOCX में परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित docx फ़ाइल है।

```java
public static void ConvertMHTML(String sourcePath, DocSaveOptions options, String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourcePath | String | MHTML स्रोत फ़ाइल पथ। इसे वर्तमान डायरेक्टरी पथ के साथ मिलाकर एक पूर्ण URL बनाया जाएगा। |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण docx फ़ाइल पाथ। |

## Remarks

MHTML कनवर्टर

MHTML से DOCX रूपांतरण अक्सर विशिष्ट कार्यों के लिए [DOCX](https://docs.fileformat.com/word-processing/docx/) फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। DOCX माइक्रोसॉफ्ट वर्ड दस्तावेज़ों के लिए एक प्रसिद्ध फ़ॉर्मेट है। इसमें पाठ, तालिकाएँ, रास्टर और वेक्टर ग्राफ़िक्स, वीडियो, ध्वनि और आरेख सहित विभिन्न प्रकार का डेटा हो सकता है। यह फ़ॉर्मेट लोकप्रिय है क्योंकि यह जटिल फ़ॉर्मेटिंग सुविधाओं का समर्थन करता है और उपयोगकर्ताओं को किसी भी प्रकार का दस्तावेज़ लिखने के लिए विभिन्न विकल्प प्रदान करता है।

देखें [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) जहाँ आप ConvertMHTML() मेथड्स का उपयोग करके [`Converter`](../) क्लास के माध्यम से MHTML को DOCX में कैसे परिवर्तित करें और [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) तथा [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को कैसे लागू करें, इस बारे में जानकारी पा सकते हैं।

MHTML को DOCX में परिवर्तित करें

Converter क्लास कुछ MHTML-विशिष्ट रूपांतरण DOCX में प्रदान करती है। MHTML को DOCX में परिवर्तित करने के लिए, आपको कुछ सरल चरणों वाले परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय MHTML (.mht) फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप मानक या कस्टम विशिष्ट स्ट्रीम को भी रूपांतरण स्रोत के रूप में उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट बनाएँ। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। Converter क्लास की ConvertMHTML() मेथड का उपयोग करके MHTML को DOCX परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के अनुसार तीन या अधिक पैरामीटर हो सकते हैं। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से MHTML को DOCX में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // डिफ़ॉल्ट DocSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new DocSaveOptions();

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, DocSaveOptions, String) {#convertmhtml_9}

URL द्वारा प्रस्तुत MHTML स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित DOCX फ़ाइल है।

```java
public static void ConvertMHTML(Url sourceUrl, DocSaveOptions options, String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceUrl | Url | MHTML स्रोत दस्तावेज़ URL - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण docx फ़ाइल पाथ। |

## Remarks

MHTML कनवर्टर

MHTML से DOCX रूपांतरण अक्सर विशिष्ट कार्यों के लिए [DOCX](https://docs.fileformat.com/word-processing/docx/) फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। DOCX माइक्रोसॉफ्ट वर्ड दस्तावेज़ों के लिए एक प्रसिद्ध फ़ॉर्मेट है। इसमें पाठ, तालिकाएँ, रास्टर और वेक्टर ग्राफ़िक्स, वीडियो, ध्वनि और आरेख सहित विभिन्न प्रकार का डेटा हो सकता है। यह फ़ॉर्मेट लोकप्रिय है क्योंकि यह जटिल फ़ॉर्मेटिंग सुविधाओं का समर्थन करता है और उपयोगकर्ताओं को किसी भी प्रकार का दस्तावेज़ लिखने के लिए विभिन्न विकल्प प्रदान करता है।

देखें [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) जहाँ आप ConvertMHTML() मेथड्स का उपयोग करके [`Converter`](../) क्लास के माध्यम से MHTML को DOCX में कैसे परिवर्तित करें और [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) तथा [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को कैसे लागू करें, इस बारे में जानकारी पा सकते हैं।

MHTML को DOCX में परिवर्तित करें

Converter क्लास कुछ MHTML-विशिष्ट रूपांतरण DOCX में प्रदान करती है। MHTML को DOCX में परिवर्तित करने के लिए, आपको कुछ सरल चरणों वाले परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय MHTML (.mht) फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप मानक या कस्टम विशिष्ट स्ट्रीम को भी रूपांतरण स्रोत के रूप में उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट बनाएँ। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। Converter क्लास की ConvertMHTML() मेथड का उपयोग करके MHTML को DOCX परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के अनुसार तीन या अधिक पैरामीटर हो सकते हैं। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से MHTML को DOCX में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // इनपुट फ़ाइल पथ के आधार पर URL बनाएं
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // डिफ़ॉल्ट DocSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new DocSaveOptions();

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(sourceUrl, options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### संबंधित देखें

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, DocSaveOptions, String) {#convertmhtml_17}

इनपुट स्ट्रीम द्वारा प्रस्तुत MHTML स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित docx फ़ाइल है।

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | MHTML रूपांतरण इनपुट डेटा स्ट्रीम। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण docx फ़ाइल पाथ। |

## Remarks

MHTML कनवर्टर

MHTML से DOCX रूपांतरण अक्सर विशिष्ट कार्यों के लिए [DOCX](https://docs.fileformat.com/word-processing/docx/) फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। DOCX माइक्रोसॉफ्ट वर्ड दस्तावेज़ों के लिए एक प्रसिद्ध फ़ॉर्मेट है। इसमें पाठ, तालिकाएँ, रास्टर और वेक्टर ग्राफ़िक्स, वीडियो, ध्वनि और आरेख सहित विभिन्न प्रकार का डेटा हो सकता है। यह फ़ॉर्मेट लोकप्रिय है क्योंकि यह जटिल फ़ॉर्मेटिंग सुविधाओं का समर्थन करता है और उपयोगकर्ताओं को किसी भी प्रकार का दस्तावेज़ लिखने के लिए विभिन्न विकल्प प्रदान करता है।

देखें [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) जहाँ आप ConvertMHTML() मेथड्स का उपयोग करके [`Converter`](../) क्लास के माध्यम से MHTML को DOCX में कैसे परिवर्तित करें और [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) तथा [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को कैसे लागू करें, इस बारे में जानकारी पा सकते हैं।

MHTML को DOCX में परिवर्तित करें

Converter क्लास कुछ MHTML-विशिष्ट रूपांतरण DOCX में प्रदान करती है। MHTML को DOCX में परिवर्तित करने के लिए, आपको कुछ सरल चरणों वाले परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय MHTML (.mht) फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप मानक या कस्टम विशिष्ट स्ट्रीम को भी रूपांतरण स्रोत के रूप में उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट बनाएँ। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। Converter क्लास की ConvertMHTML() मेथड का उपयोग करके MHTML को DOCX परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के अनुसार तीन या अधिक पैरामीटर हो सकते हैं। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से MHTML को DOCX में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // डिफ़ॉल्ट DocSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new DocSaveOptions();

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, DocSaveOptions, String) {#convertmhtml_33}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत MHTML स्रोत को DOCX में परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित docx फ़ाइल है।

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourcePath | String | MHTML स्रोत का पूर्ण फ़ाइल पथ। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण docx फ़ाइल पाथ। |

## Remarks

MHTML कनवर्टर

MHTML से DOCX रूपांतरण अक्सर विशिष्ट कार्यों के लिए [DOCX](https://docs.fileformat.com/word-processing/docx/) फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। DOCX माइक्रोसॉफ्ट वर्ड दस्तावेज़ों के लिए एक प्रसिद्ध फ़ॉर्मेट है। इसमें पाठ, तालिकाएँ, रास्टर और वेक्टर ग्राफ़िक्स, वीडियो, ध्वनि और आरेख सहित विभिन्न प्रकार का डेटा हो सकता है। यह फ़ॉर्मेट लोकप्रिय है क्योंकि यह जटिल फ़ॉर्मेटिंग सुविधाओं का समर्थन करता है और उपयोगकर्ताओं को किसी भी प्रकार का दस्तावेज़ लिखने के लिए विभिन्न विकल्प प्रदान करता है।

देखें [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) जहाँ आप ConvertMHTML() मेथड्स का उपयोग करके [`Converter`](../) क्लास के माध्यम से MHTML को DOCX में कैसे परिवर्तित करें और [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) तथा [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को कैसे लागू करें, इस बारे में जानकारी पा सकते हैं।

MHTML को DOCX में परिवर्तित करें

Converter क्लास कुछ MHTML-विशिष्ट रूपांतरण DOCX में प्रदान करती है। MHTML को DOCX में परिवर्तित करने के लिए, आपको कुछ सरल चरणों वाले परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय MHTML (.mht) फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप मानक या कस्टम विशिष्ट स्ट्रीम को भी रूपांतरण स्रोत के रूप में उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट बनाएँ। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। Converter क्लास की ConvertMHTML() मेथड का उपयोग करके MHTML को DOCX परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के अनुसार तीन या अधिक पैरामीटर हो सकते हैं। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से MHTML को DOCX में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // डिफ़ॉल्ट DocSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new DocSaveOptions();

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, DocSaveOptions, String) {#convertmhtml_1}

[`URL`](../../../com.aspose.html/url/) द्वारा प्रस्तुत MHTML स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित docx फ़ाइल है।

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceUrl | Url | MHTML स्रोत दस्तावेज़ [`URL`](../../../com.aspose.html/url/) - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण docx फ़ाइल पाथ। |

## Remarks

MHTML कनवर्टर

MHTML से DOCX रूपांतरण अक्सर विशिष्ट कार्यों के लिए [DOCX](https://docs.fileformat.com/word-processing/docx/) फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। DOCX माइक्रोसॉफ्ट वर्ड दस्तावेज़ों के लिए एक प्रसिद्ध फ़ॉर्मेट है। इसमें पाठ, तालिकाएँ, रास्टर और वेक्टर ग्राफ़िक्स, वीडियो, ध्वनि और आरेख सहित विभिन्न प्रकार का डेटा हो सकता है। यह फ़ॉर्मेट लोकप्रिय है क्योंकि यह जटिल फ़ॉर्मेटिंग सुविधाओं का समर्थन करता है और उपयोगकर्ताओं को किसी भी प्रकार का दस्तावेज़ लिखने के लिए विभिन्न विकल्प प्रदान करता है।

देखें [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) जहाँ आप ConvertMHTML() मेथड्स का उपयोग करके [`Converter`](../) क्लास के माध्यम से MHTML को DOCX में कैसे परिवर्तित करें और [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) तथा [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को कैसे लागू करें, इस बारे में जानकारी पा सकते हैं।

MHTML को DOCX में परिवर्तित करें

Converter क्लास कुछ MHTML-विशिष्ट रूपांतरण DOCX में प्रदान करती है। MHTML को DOCX में परिवर्तित करने के लिए, आपको कुछ सरल चरणों वाले परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय MHTML (.mht) फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप मानक या कस्टम विशिष्ट स्ट्रीम को भी रूपांतरण स्रोत के रूप में उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट बनाएँ। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। Converter क्लास की ConvertMHTML() मेथड का उपयोग करके MHTML को DOCX परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के अनुसार तीन या अधिक पैरामीटर हो सकते हैं। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से MHTML को DOCX में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // इनपुट फ़ाइल पथ के आधार पर URL बनाएं
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // डिफ़ॉल्ट DocSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new DocSaveOptions();

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_24}

इनपुट स्ट्रीम द्वारा प्रस्तुत MHTML स्रोत को परिवर्तित करें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित होता है।

```java
public static void ConvertMHTML(Stream stream, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | MHTML रूपांतरण इनपुट डेटा स्ट्रीम। |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। |

## Remarks

MHTML कनवर्टर

MHTML से DOCX रूपांतरण अक्सर विशिष्ट कार्यों के लिए [DOCX](https://docs.fileformat.com/word-processing/docx/) फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। DOCX माइक्रोसॉफ्ट वर्ड दस्तावेज़ों के लिए एक प्रसिद्ध फ़ॉर्मेट है। इसमें पाठ, तालिकाएँ, रास्टर और वेक्टर ग्राफ़िक्स, वीडियो, ध्वनि और आरेख सहित विभिन्न प्रकार का डेटा हो सकता है। यह फ़ॉर्मेट लोकप्रिय है क्योंकि यह जटिल फ़ॉर्मेटिंग सुविधाओं का समर्थन करता है और उपयोगकर्ताओं को किसी भी प्रकार का दस्तावेज़ लिखने के लिए विभिन्न विकल्प प्रदान करता है।

देखें [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) जहाँ आप ConvertMHTML() मेथड्स का उपयोग करके [`Converter`](../) क्लास के माध्यम से MHTML को DOCX में कैसे परिवर्तित करें और [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) तथा [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को कैसे लागू करें, इस बारे में जानकारी पा सकते हैं।

MHTML को DOCX में परिवर्तित करें

Converter क्लास कुछ MHTML-विशिष्ट रूपांतरण DOCX में प्रदान करती है। MHTML को DOCX में परिवर्तित करने के लिए, आपको कुछ सरल चरणों वाले परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय MHTML (.mht) फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप मानक या कस्टम विशिष्ट स्ट्रीम को भी रूपांतरण स्रोत के रूप में उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट बनाएँ। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। Converter क्लास की ConvertMHTML() मेथड का उपयोग करके MHTML को DOCX परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के अनुसार तीन या अधिक पैरामीटर हो सकते हैं। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से MHTML को DOCX में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // डिफ़ॉल्ट DocSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new DocSaveOptions();

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_40}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत MHTML स्रोत को DOCX में परिवर्तित करें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित होता है।

```java
public static void ConvertMHTML(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourcePath | String | MHTML स्रोत का पूर्ण फ़ाइल पथ। |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। |

## Remarks

MHTML कनवर्टर

MHTML से DOCX रूपांतरण अक्सर विशिष्ट कार्यों के लिए [DOCX](https://docs.fileformat.com/word-processing/docx/) फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। DOCX माइक्रोसॉफ्ट वर्ड दस्तावेज़ों के लिए एक प्रसिद्ध फ़ॉर्मेट है। इसमें पाठ, तालिकाएँ, रास्टर और वेक्टर ग्राफ़िक्स, वीडियो, ध्वनि और आरेख सहित विभिन्न प्रकार का डेटा हो सकता है। यह फ़ॉर्मेट लोकप्रिय है क्योंकि यह जटिल फ़ॉर्मेटिंग सुविधाओं का समर्थन करता है और उपयोगकर्ताओं को किसी भी प्रकार का दस्तावेज़ लिखने के लिए विभिन्न विकल्प प्रदान करता है।

देखें [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) जहाँ आप ConvertMHTML() मेथड्स का उपयोग करके [`Converter`](../) क्लास के माध्यम से MHTML को DOCX में कैसे परिवर्तित करें और [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) तथा [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को कैसे लागू करें, इस बारे में जानकारी पा सकते हैं।

MHTML को DOCX में परिवर्तित करें

Converter क्लास कुछ MHTML-विशिष्ट रूपांतरण DOCX में प्रदान करती है। MHTML को DOCX में परिवर्तित करने के लिए, आपको कुछ सरल चरणों वाले परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय MHTML (.mht) फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप मानक या कस्टम विशिष्ट स्ट्रीम को भी रूपांतरण स्रोत के रूप में उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट बनाएँ। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। Converter क्लास की ConvertMHTML() मेथड का उपयोग करके MHTML को DOCX परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के अनुसार तीन या अधिक पैरामीटर हो सकते हैं। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से MHTML को DOCX में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // डिफ़ॉल्ट DocSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new DocSaveOptions();

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_8}

URL द्वारा प्रस्तुत MHTML स्रोत को परिवर्तित करें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित होता है।

```java
public static void ConvertMHTML(Url sourceUrl, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceUrl | Url | MHTML स्रोत दस्तावेज़ [`URL`](../../../com.aspose.html/url/) - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | ज्ञात (देखें [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन। |

## Remarks

MHTML कनवर्टर

MHTML से DOCX रूपांतरण अक्सर विशिष्ट कार्यों के लिए [DOCX](https://docs.fileformat.com/word-processing/docx/) फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। DOCX माइक्रोसॉफ्ट वर्ड दस्तावेज़ों के लिए एक प्रसिद्ध फ़ॉर्मेट है। इसमें पाठ, तालिकाएँ, रास्टर और वेक्टर ग्राफ़िक्स, वीडियो, ध्वनि और आरेख सहित विभिन्न प्रकार का डेटा हो सकता है। यह फ़ॉर्मेट लोकप्रिय है क्योंकि यह जटिल फ़ॉर्मेटिंग सुविधाओं का समर्थन करता है और उपयोगकर्ताओं को किसी भी प्रकार का दस्तावेज़ लिखने के लिए विभिन्न विकल्प प्रदान करता है।

देखें [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) जहाँ आप ConvertMHTML() मेथड्स का उपयोग करके [`Converter`](../) क्लास के माध्यम से MHTML को DOCX में कैसे परिवर्तित करें और [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) तथा [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को कैसे लागू करें, इस बारे में जानकारी पा सकते हैं।

MHTML को DOCX में परिवर्तित करें

Converter क्लास कुछ MHTML-विशिष्ट रूपांतरण DOCX में प्रदान करती है। MHTML को DOCX में परिवर्तित करने के लिए, आपको कुछ सरल चरणों वाले परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय MHTML (.mht) फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप मानक या कस्टम विशिष्ट स्ट्रीम को भी रूपांतरण स्रोत के रूप में उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट बनाएँ। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। Converter क्लास की ConvertMHTML() मेथड का उपयोग करके MHTML को DOCX परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के अनुसार तीन या अधिक पैरामीटर हो सकते हैं। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से MHTML को DOCX में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // इनपुट फ़ाइल पथ के आधार पर URL बनाएं
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // डिफ़ॉल्ट DocSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new DocSaveOptions();

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_16}

इनपुट स्ट्रीम द्वारा प्रस्तुत MHTML स्रोत को परिवर्तित करें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित होता है।

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | MHTML रूपांतरण इनपुट डेटा स्ट्रीम। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | ज्ञात (देखें [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन। |

## Remarks

MHTML कनवर्टर

MHTML से DOCX रूपांतरण अक्सर विशिष्ट कार्यों के लिए [DOCX](https://docs.fileformat.com/word-processing/docx/) फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। DOCX माइक्रोसॉफ्ट वर्ड दस्तावेज़ों के लिए एक प्रसिद्ध फ़ॉर्मेट है। इसमें पाठ, तालिकाएँ, रास्टर और वेक्टर ग्राफ़िक्स, वीडियो, ध्वनि और आरेख सहित विभिन्न प्रकार का डेटा हो सकता है। यह फ़ॉर्मेट लोकप्रिय है क्योंकि यह जटिल फ़ॉर्मेटिंग सुविधाओं का समर्थन करता है और उपयोगकर्ताओं को किसी भी प्रकार का दस्तावेज़ लिखने के लिए विभिन्न विकल्प प्रदान करता है।

देखें [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) जहाँ आप ConvertMHTML() मेथड्स का उपयोग करके [`Converter`](../) क्लास के माध्यम से MHTML को DOCX में कैसे परिवर्तित करें और [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) तथा [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को कैसे लागू करें, इस बारे में जानकारी पा सकते हैं।

MHTML को DOCX में परिवर्तित करें

Converter क्लास कुछ MHTML-विशिष्ट रूपांतरण DOCX में प्रदान करती है। MHTML को DOCX में परिवर्तित करने के लिए, आपको कुछ सरल चरणों वाले परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय MHTML (.mht) फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप मानक या कस्टम विशिष्ट स्ट्रीम को भी रूपांतरण स्रोत के रूप में उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट बनाएँ। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। Converter क्लास की ConvertMHTML() मेथड का उपयोग करके MHTML को DOCX परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के अनुसार तीन या अधिक पैरामीटर हो सकते हैं। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से MHTML को DOCX में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // डिफ़ॉल्ट DocSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new DocSaveOptions();

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_32}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत MHTML स्रोत को DOCX में परिवर्तित करें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित होता है।

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourcePath | String | MHTML स्रोत का पूर्ण फ़ाइल पथ। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। |

## Remarks

MHTML कनवर्टर

MHTML से DOCX रूपांतरण अक्सर विशिष्ट कार्यों के लिए [DOCX](https://docs.fileformat.com/word-processing/docx/) फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। DOCX माइक्रोसॉफ्ट वर्ड दस्तावेज़ों के लिए एक प्रसिद्ध फ़ॉर्मेट है। इसमें पाठ, तालिकाएँ, रास्टर और वेक्टर ग्राफ़िक्स, वीडियो, ध्वनि और आरेख सहित विभिन्न प्रकार का डेटा हो सकता है। यह फ़ॉर्मेट लोकप्रिय है क्योंकि यह जटिल फ़ॉर्मेटिंग सुविधाओं का समर्थन करता है और उपयोगकर्ताओं को किसी भी प्रकार का दस्तावेज़ लिखने के लिए विभिन्न विकल्प प्रदान करता है।

देखें [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) जहाँ आप ConvertMHTML() मेथड्स का उपयोग करके [`Converter`](../) क्लास के माध्यम से MHTML को DOCX में कैसे परिवर्तित करें और [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) तथा [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को कैसे लागू करें, इस बारे में जानकारी पा सकते हैं।

MHTML को DOCX में परिवर्तित करें

Converter क्लास कुछ MHTML-विशिष्ट रूपांतरण DOCX में प्रदान करती है। MHTML को DOCX में परिवर्तित करने के लिए, आपको कुछ सरल चरणों वाले परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय MHTML (.mht) फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप मानक या कस्टम विशिष्ट स्ट्रीम को भी रूपांतरण स्रोत के रूप में उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट बनाएँ। आप विकल्प पैरामीटर के रूप में configuration भी जोड़ सकते हैं। Converter क्लास की ConvertMHTML() मेथड का उपयोग करके MHTML को DOCX परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के अनुसार तीन या अधिक पैरामीटर हो सकते हैं। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से MHTML को DOCX में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // डिफ़ॉल्ट DocSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new DocSaveOptions();

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml}

[`URL`](../../../com.aspose.html/url/) द्वारा प्रस्तुत MHTML स्रोत को परिवर्तित करें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित होता है।

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceUrl | Url | MHTML स्रोत दस्तावेज़ [`URL`](../../../com.aspose.html/url/) - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। |

## Remarks

MHTML कनवर्टर

MHTML से DOCX रूपांतरण अक्सर विशिष्ट कार्यों के लिए [DOCX](https://docs.fileformat.com/word-processing/docx/) फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। DOCX माइक्रोसॉफ्ट वर्ड दस्तावेज़ों के लिए एक प्रसिद्ध फ़ॉर्मेट है। इसमें पाठ, तालिकाएँ, रास्टर और वेक्टर ग्राफ़िक्स, वीडियो, ध्वनि और आरेख सहित विभिन्न प्रकार का डेटा हो सकता है। यह फ़ॉर्मेट लोकप्रिय है क्योंकि यह जटिल फ़ॉर्मेटिंग सुविधाओं का समर्थन करता है और उपयोगकर्ताओं को किसी भी प्रकार का दस्तावेज़ लिखने के लिए विभिन्न विकल्प प्रदान करता है।

देखें [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) जहाँ आप ConvertMHTML() मेथड्स का उपयोग करके [`Converter`](../) क्लास के माध्यम से MHTML को DOCX में कैसे परिवर्तित करें और [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) तथा [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को कैसे लागू करें, इस बारे में जानकारी पा सकते हैं।

MHTML को DOCX में परिवर्तित करें

Converter क्लास कुछ MHTML-विशिष्ट रूपांतरण DOCX में प्रदान करती है। MHTML को DOCX में परिवर्तित करने के लिए, आपको कुछ सरल चरणों वाले परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय MHTML (.mht) फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप मानक या कस्टम विशिष्ट स्ट्रीम को भी रूपांतरण स्रोत के रूप में उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट बनाएँ। आप विकल्प पैरामीटर के रूप में configuration भी जोड़ सकते हैं। Converter क्लास की ConvertMHTML() मेथड का उपयोग करके MHTML को DOCX परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के अनुसार तीन या अधिक पैरामीटर हो सकते हैं। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से MHTML को DOCX में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // इनपुट फ़ाइल पथ के आधार पर URL बनाएं
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // डिफ़ॉल्ट DocSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new DocSaveOptions();

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source folder path.

*OutputFolder - user output folder path.

### संबंधित देखें

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, PdfSaveOptions, String) {#convertmhtml_29}

इनपुट स्ट्रीम द्वारा प्रस्तुत MHTML स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित pdf फ़ाइल है।

```java
public static void ConvertMHTML(Stream stream, PdfSaveOptions options, String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | MHTML रूपांतरण इनपुट डेटा स्ट्रीम। |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण pdf फ़ाइल पथ। |

## Remarks

MHTML कनवर्टर

MHTML से PDF रूपांतरण अक्सर विशिष्ट कार्यों के लिए [PDF](https://docs.fileformat.com/pdf/) फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। PDF में कई लाभ होते हैं जो अन्य फ़ाइलों में नहीं होते। उदाहरण के लिए, कई प्रोग्राम और ऐप्स PDF दस्तावेज़ों का समर्थन करते हैं; PDF फ़ाइलें प्रिंटिंग के लिए अनुकूलित होती हैं, और वे आपके दस्तावेज़ों की भौतिक प्रतियां बनाने के लिए आदर्श हैं; आप PDF फ़ाइलों के लिए सुरक्षा सेटिंग्स कॉन्फ़िगर कर सकते हैं - प्रिंटिंग, संपादन, इलेक्ट्रॉनिक सिग्नेचर आदि को अक्षम कर सकते हैं।

देखें [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), जहाँ आप ConvertMHTML() मेथड्स का उपयोग करके [`Converter`](../) क्लास के माध्यम से MHTML को PDF में कैसे परिवर्तित करें और [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) तथा [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को कैसे लागू करें, इस बारे में जानकारी पा सकते हैं।

MHTML को PDF में बदलें

Converter क्लास कुछ MHTML‑विशिष्ट रूपांतरण PDF में प्रदान करती है। MHTML को PDF में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। स्थानीय मौजूद MHTML (.mht) फ़ाइल या रिमोट URL को रूपांतरण स्रोत के रूप में पहचानें। आप स्रोत के रूप में मानक या कस्टम विशिष्ट [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) का भी उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट बनाएं। आप वैकल्पिक पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर के साथ MHTML को PDF परिणाम के रूप में सहेजने के लिए Converter क्लास की ConvertMHTML() मेथड का उपयोग करें। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) प्रदान करता है जो MHTML को उच्च गुणवत्ता, आसान और तेज़ी से PDF में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // डिफ़ॉल्ट PdfSaveOptions ऑब्जेक्ट को परिभाषित करें
      var options = new PdfSaveOptions();

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, PdfSaveOptions, String) {#convertmhtml_45}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत MHTML स्रोत को PDF में परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित PDF फ़ाइल है।

```java
public static void ConvertMHTML(String sourcePath, PdfSaveOptions options, String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourcePath | String | MHTML स्रोत का पूर्ण फ़ाइल पथ। |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण pdf फ़ाइल पथ। |

## Remarks

MHTML कनवर्टर

MHTML से PDF रूपांतरण अक्सर विशिष्ट कार्यों के लिए [PDF](https://docs.fileformat.com/pdf/) फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। PDF में कई लाभ होते हैं जो अन्य फ़ाइलों में नहीं होते। उदाहरण के लिए, कई प्रोग्राम और ऐप्स PDF दस्तावेज़ों का समर्थन करते हैं; PDF फ़ाइलें प्रिंटिंग के लिए अनुकूलित होती हैं, और वे आपके दस्तावेज़ों की भौतिक प्रतियां बनाने के लिए आदर्श हैं; आप PDF फ़ाइलों के लिए सुरक्षा सेटिंग्स कॉन्फ़िगर कर सकते हैं - प्रिंटिंग, संपादन, इलेक्ट्रॉनिक सिग्नेचर आदि को अक्षम कर सकते हैं।

देखें [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), जहाँ आप ConvertMHTML() मेथड्स का उपयोग करके [`Converter`](../) क्लास के माध्यम से MHTML को PDF में कैसे परिवर्तित करें और [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) तथा [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को कैसे लागू करें, इस बारे में जानकारी पा सकते हैं।

MHTML को PDF में बदलें

Converter क्लास कुछ MHTML‑विशिष्ट रूपांतरण PDF में प्रदान करती है। MHTML को PDF में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। स्थानीय मौजूद MHTML (.mht) फ़ाइल या रिमोट URL को रूपांतरण स्रोत के रूप में पहचानें। आप स्रोत के रूप में मानक या कस्टम विशिष्ट [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) का भी उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट बनाएं। आप वैकल्पिक पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर के साथ MHTML को PDF परिणाम के रूप में सहेजने के लिए Converter क्लास की ConvertMHTML() मेथड का उपयोग करें। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) प्रदान करता है जो MHTML को उच्च गुणवत्ता, आसान और तेज़ी से PDF में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // डिफ़ॉल्ट PdfSaveOptions ऑब्जेक्ट को परिभाषित करें
      var options = new PdfSaveOptions();

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, PdfSaveOptions, String) {#convertmhtml_13}

URL द्वारा प्रस्तुत MHTML स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित PDF फ़ाइल है।

```java
public static void ConvertMHTML(Url sourceUrl, PdfSaveOptions options, String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceUrl | Url | MHTML स्रोत दस्तावेज़ URL - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण pdf फ़ाइल पथ। |

## Remarks

MHTML कनवर्टर

MHTML से PDF रूपांतरण अक्सर विशिष्ट कार्यों के लिए [PDF](https://docs.fileformat.com/pdf/) फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। PDF में कई लाभ होते हैं जो अन्य फ़ाइलों में नहीं होते। उदाहरण के लिए, कई प्रोग्राम और ऐप्स PDF दस्तावेज़ों का समर्थन करते हैं; PDF फ़ाइलें प्रिंटिंग के लिए अनुकूलित होती हैं, और वे आपके दस्तावेज़ों की भौतिक प्रतियां बनाने के लिए आदर्श हैं; आप PDF फ़ाइलों के लिए सुरक्षा सेटिंग्स कॉन्फ़िगर कर सकते हैं - प्रिंटिंग, संपादन, इलेक्ट्रॉनिक सिग्नेचर आदि को अक्षम कर सकते हैं।

देखें [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), जहाँ आप ConvertMHTML() मेथड्स का उपयोग करके [`Converter`](../) क्लास के माध्यम से MHTML को PDF में कैसे परिवर्तित करें और [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) तथा [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को कैसे लागू करें, इस बारे में जानकारी पा सकते हैं।

MHTML को PDF में बदलें

Converter क्लास कुछ MHTML‑विशिष्ट रूपांतरण PDF में प्रदान करती है। MHTML को PDF में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। स्थानीय मौजूद MHTML (.mht) फ़ाइल या रिमोट URL को रूपांतरण स्रोत के रूप में पहचानें। आप स्रोत के रूप में मानक या कस्टम विशिष्ट [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) का भी उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट बनाएं। आप वैकल्पिक पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर के साथ MHTML को PDF परिणाम के रूप में सहेजने के लिए Converter क्लास की ConvertMHTML() मेथड का उपयोग करें। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) प्रदान करता है जो MHTML को उच्च गुणवत्ता, आसान और तेज़ी से PDF में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // इनपुट फ़ाइल पथ के आधार पर URL बनाएं
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // डिफ़ॉल्ट PdfSaveOptions ऑब्जेक्ट को परिभाषित करें
      var options = new PdfSaveOptions();

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, PdfSaveOptions, String) {#convertmhtml_21}

इनपुट स्ट्रीम द्वारा प्रस्तुत MHTML स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित pdf फ़ाइल है।

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | MHTML रूपांतरण इनपुट डेटा स्ट्रीम। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण pdf फ़ाइल पथ। |

## Remarks

MHTML कनवर्टर

MHTML से PDF रूपांतरण अक्सर विशिष्ट कार्यों के लिए [PDF](https://docs.fileformat.com/pdf/) फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। PDF में कई लाभ होते हैं जो अन्य फ़ाइलों में नहीं होते। उदाहरण के लिए, कई प्रोग्राम और ऐप्स PDF दस्तावेज़ों का समर्थन करते हैं; PDF फ़ाइलें प्रिंटिंग के लिए अनुकूलित होती हैं, और वे आपके दस्तावेज़ों की भौतिक प्रतियां बनाने के लिए आदर्श हैं; आप PDF फ़ाइलों के लिए सुरक्षा सेटिंग्स कॉन्फ़िगर कर सकते हैं - प्रिंटिंग, संपादन, इलेक्ट्रॉनिक सिग्नेचर आदि को अक्षम कर सकते हैं।

देखें [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), जहाँ आप ConvertMHTML() मेथड्स का उपयोग करके [`Converter`](../) क्लास के माध्यम से MHTML को PDF में कैसे परिवर्तित करें और [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) तथा [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को कैसे लागू करें, इस बारे में जानकारी पा सकते हैं।

MHTML को PDF में बदलें

Converter क्लास कुछ MHTML‑विशिष्ट रूपांतरण PDF में प्रदान करती है। MHTML को PDF में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। स्थानीय मौजूद MHTML (.mht) फ़ाइल या रिमोट URL को रूपांतरण स्रोत के रूप में पहचानें। आप स्रोत के रूप में मानक या कस्टम विशिष्ट [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) का भी उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट बनाएं। आप वैकल्पिक पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर के साथ MHTML को PDF परिणाम के रूप में सहेजने के लिए Converter क्लास की ConvertMHTML() मेथड का उपयोग करें। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) प्रदान करता है जो MHTML को उच्च गुणवत्ता, आसान और तेज़ी से PDF में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // डिफ़ॉल्ट PdfSaveOptions ऑब्जेक्ट को परिभाषित करें
      var options = new PdfSaveOptions();

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, PdfSaveOptions, String) {#convertmhtml_37}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत MHTML स्रोत को PDF में परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित PDF फ़ाइल है।

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourcePath | String | MHTML स्रोत फ़ाइल पथ। इसे वर्तमान डायरेक्टरी पथ के साथ मिलाकर एक पूर्ण URL बनाया जाएगा। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण pdf फ़ाइल पथ। |

## Remarks

MHTML कनवर्टर

MHTML से PDF रूपांतरण अक्सर विशिष्ट कार्यों के लिए [PDF](https://docs.fileformat.com/pdf/) फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। PDF में कई लाभ होते हैं जो अन्य फ़ाइलों में नहीं होते। उदाहरण के लिए, कई प्रोग्राम और ऐप्स PDF दस्तावेज़ों का समर्थन करते हैं; PDF फ़ाइलें प्रिंटिंग के लिए अनुकूलित होती हैं, और वे आपके दस्तावेज़ों की भौतिक प्रतियां बनाने के लिए आदर्श हैं; आप PDF फ़ाइलों के लिए सुरक्षा सेटिंग्स कॉन्फ़िगर कर सकते हैं - प्रिंटिंग, संपादन, इलेक्ट्रॉनिक सिग्नेचर आदि को अक्षम कर सकते हैं।

देखें [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), जहाँ आप ConvertMHTML() मेथड्स का उपयोग करके [`Converter`](../) क्लास के माध्यम से MHTML को PDF में कैसे परिवर्तित करें और [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) तथा [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को कैसे लागू करें, इस बारे में जानकारी पा सकते हैं।

MHTML को PDF में बदलें

Converter क्लास कुछ MHTML‑विशिष्ट रूपांतरण PDF में प्रदान करती है। MHTML को PDF में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। स्थानीय मौजूद MHTML (.mht) फ़ाइल या रिमोट URL को रूपांतरण स्रोत के रूप में पहचानें। आप स्रोत के रूप में मानक या कस्टम विशिष्ट [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) का भी उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट बनाएं। आप वैकल्पिक पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर के साथ MHTML को PDF परिणाम के रूप में सहेजने के लिए Converter क्लास की ConvertMHTML() मेथड का उपयोग करें। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) प्रदान करता है जो MHTML को उच्च गुणवत्ता, आसान और तेज़ी से PDF में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // डिफ़ॉल्ट PdfSaveOptions ऑब्जेक्ट को परिभाषित करें
      var options = new PdfSaveOptions();

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, PdfSaveOptions, String) {#convertmhtml_5}

URL द्वारा प्रस्तुत MHTML स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित PDF फ़ाइल है।

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceUrl | Url | MHTML स्रोत दस्तावेज़ URL - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण pdf फ़ाइल पथ। |

## Remarks

MHTML कनवर्टर

MHTML से PDF रूपांतरण अक्सर विशिष्ट कार्यों के लिए [PDF](https://docs.fileformat.com/pdf/) फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। PDF में कई लाभ होते हैं जो अन्य फ़ाइलों में नहीं होते। उदाहरण के लिए, कई प्रोग्राम और ऐप्स PDF दस्तावेज़ों का समर्थन करते हैं; PDF फ़ाइलें प्रिंटिंग के लिए अनुकूलित होती हैं, और वे आपके दस्तावेज़ों की भौतिक प्रतियां बनाने के लिए आदर्श हैं; आप PDF फ़ाइलों के लिए सुरक्षा सेटिंग्स कॉन्फ़िगर कर सकते हैं - प्रिंटिंग, संपादन, इलेक्ट्रॉनिक सिग्नेचर आदि को अक्षम कर सकते हैं।

देखें [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), जहाँ आप ConvertMHTML() मेथड्स का उपयोग करके [`Converter`](../) क्लास के माध्यम से MHTML को PDF में कैसे परिवर्तित करें और [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) तथा [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को कैसे लागू करें, इस बारे में जानकारी पा सकते हैं।

MHTML को PDF में बदलें

Converter क्लास कुछ MHTML‑विशिष्ट रूपांतरण PDF में प्रदान करती है। MHTML को PDF में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। स्थानीय मौजूद MHTML (.mht) फ़ाइल या रिमोट URL को रूपांतरण स्रोत के रूप में पहचानें। आप स्रोत के रूप में मानक या कस्टम विशिष्ट [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) का भी उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट बनाएं। आप वैकल्पिक पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर के साथ MHTML को PDF परिणाम के रूप में सहेजने के लिए Converter क्लास की ConvertMHTML() मेथड का उपयोग करें। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) प्रदान करता है जो MHTML को उच्च गुणवत्ता, आसान और तेज़ी से PDF में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // इनपुट फ़ाइल पथ के आधार पर URL बनाएं
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // डिफ़ॉल्ट PdfSaveOptions ऑब्जेक्ट को परिभाषित करें
      var options = new PdfSaveOptions();

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_28}

इनपुट स्ट्रीम द्वारा प्रस्तुत MHTML स्रोत को परिवर्तित करें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित होता है।

```java
public static void ConvertMHTML(Stream stream, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | MHTML रूपांतरण इनपुट डेटा स्ट्रीम। |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | ज्ञात (देखें [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन। |

## Remarks

MHTML कनवर्टर

MHTML से PDF रूपांतरण अक्सर विशिष्ट कार्यों के लिए [PDF](https://docs.fileformat.com/pdf/) फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। PDF में कई लाभ होते हैं जो अन्य फ़ाइलों में नहीं होते। उदाहरण के लिए, कई प्रोग्राम और ऐप्स PDF दस्तावेज़ों का समर्थन करते हैं; PDF फ़ाइलें प्रिंटिंग के लिए अनुकूलित होती हैं, और वे आपके दस्तावेज़ों की भौतिक प्रतियां बनाने के लिए आदर्श हैं; आप PDF फ़ाइलों के लिए सुरक्षा सेटिंग्स कॉन्फ़िगर कर सकते हैं - प्रिंटिंग, संपादन, इलेक्ट्रॉनिक सिग्नेचर आदि को अक्षम कर सकते हैं।

देखें [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), जहाँ आप ConvertMHTML() मेथड्स का उपयोग करके [`Converter`](../) क्लास के माध्यम से MHTML को PDF में कैसे परिवर्तित करें और [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) तथा [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को कैसे लागू करें, इस बारे में जानकारी पा सकते हैं।

MHTML को PDF में बदलें

Converter क्लास कुछ MHTML‑विशिष्ट रूपांतरण PDF में प्रदान करती है। MHTML को PDF में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। स्थानीय मौजूद MHTML (.mht) फ़ाइल या रिमोट URL को रूपांतरण स्रोत के रूप में पहचानें। आप स्रोत के रूप में मानक या कस्टम विशिष्ट [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) का भी उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट बनाएं। आप वैकल्पिक पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर के साथ MHTML को PDF परिणाम के रूप में सहेजने के लिए Converter क्लास की ConvertMHTML() मेथड का उपयोग करें। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) प्रदान करता है जो MHTML को उच्च गुणवत्ता, आसान और तेज़ी से PDF में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // डिफ़ॉल्ट PdfSaveOptions ऑब्जेक्ट को परिभाषित करें
      var options = new PdfSaveOptions();

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_44}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत MHTML स्रोत को PDF में बदलें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित होता है।

```java
public static void ConvertMHTML(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourcePath | String | MHTML स्रोत फ़ाइल पथ। इसे वर्तमान डायरेक्टरी पथ के साथ मिलाकर एक पूर्ण URL बनाया जाएगा। |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। |

## Remarks

MHTML कनवर्टर

MHTML से PDF रूपांतरण अक्सर विशिष्ट कार्यों के लिए [PDF](https://docs.fileformat.com/pdf/) फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। PDF में कई लाभ होते हैं जो अन्य फ़ाइलों में नहीं होते। उदाहरण के लिए, कई प्रोग्राम और ऐप्स PDF दस्तावेज़ों का समर्थन करते हैं; PDF फ़ाइलें प्रिंटिंग के लिए अनुकूलित होती हैं, और वे आपके दस्तावेज़ों की भौतिक प्रतियां बनाने के लिए आदर्श हैं; आप PDF फ़ाइलों के लिए सुरक्षा सेटिंग्स कॉन्फ़िगर कर सकते हैं - प्रिंटिंग, संपादन, इलेक्ट्रॉनिक सिग्नेचर आदि को अक्षम कर सकते हैं।

देखें [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), जहाँ आप ConvertMHTML() मेथड्स का उपयोग करके [`Converter`](../) क्लास के माध्यम से MHTML को PDF में कैसे परिवर्तित करें और [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) तथा [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को कैसे लागू करें, इस बारे में जानकारी पा सकते हैं।

MHTML को PDF में बदलें

Converter क्लास कुछ MHTML‑विशिष्ट रूपांतरण PDF में प्रदान करती है। MHTML को PDF में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। स्थानीय मौजूद MHTML (.mht) फ़ाइल या रिमोट URL को रूपांतरण स्रोत के रूप में पहचानें। आप स्रोत के रूप में मानक या कस्टम विशिष्ट [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) का भी उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट बनाएं। आप वैकल्पिक पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर के साथ MHTML को PDF परिणाम के रूप में सहेजने के लिए Converter क्लास की ConvertMHTML() मेथड का उपयोग करें। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) प्रदान करता है जो MHTML को उच्च गुणवत्ता, आसान और तेज़ी से PDF में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // डिफ़ॉल्ट PdfSaveOptions ऑब्जेक्ट को परिभाषित करें
      var options = new PdfSaveOptions();

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_12}

URL द्वारा प्रस्तुत MHTML स्रोत को परिवर्तित करें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित होता है।

```java
public static void ConvertMHTML(Url sourceUrl, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceUrl | Url | MHTML स्रोत दस्तावेज़ URL - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। |

## Remarks

MHTML कनवर्टर

MHTML से PDF रूपांतरण अक्सर विशिष्ट कार्यों के लिए [PDF](https://docs.fileformat.com/pdf/) फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। PDF में कई लाभ होते हैं जो अन्य फ़ाइलों में नहीं होते। उदाहरण के लिए, कई प्रोग्राम और ऐप्स PDF दस्तावेज़ों का समर्थन करते हैं; PDF फ़ाइलें प्रिंटिंग के लिए अनुकूलित होती हैं, और वे आपके दस्तावेज़ों की भौतिक प्रतियां बनाने के लिए आदर्श हैं; आप PDF फ़ाइलों के लिए सुरक्षा सेटिंग्स कॉन्फ़िगर कर सकते हैं - प्रिंटिंग, संपादन, इलेक्ट्रॉनिक सिग्नेचर आदि को अक्षम कर सकते हैं।

देखें [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), जहाँ आप ConvertMHTML() मेथड्स का उपयोग करके [`Converter`](../) क्लास के माध्यम से MHTML को PDF में कैसे परिवर्तित करें और [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) तथा [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को कैसे लागू करें, इस बारे में जानकारी पा सकते हैं।

MHTML को PDF में बदलें

Converter क्लास कुछ MHTML‑विशिष्ट रूपांतरण PDF में प्रदान करती है। MHTML को PDF में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। स्थानीय मौजूद MHTML (.mht) फ़ाइल या रिमोट URL को रूपांतरण स्रोत के रूप में पहचानें। आप स्रोत के रूप में मानक या कस्टम विशिष्ट [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) का भी उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट बनाएं। आप वैकल्पिक पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर के साथ MHTML को PDF परिणाम के रूप में सहेजने के लिए Converter क्लास की ConvertMHTML() मेथड का उपयोग करें। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) प्रदान करता है जो MHTML को उच्च गुणवत्ता, आसान और तेज़ी से PDF में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // इनपुट फ़ाइल पथ के आधार पर URL बनाएं
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // डिफ़ॉल्ट PdfSaveOptions ऑब्जेक्ट को परिभाषित करें
      var options = new PdfSaveOptions();

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_20}

इनपुट स्ट्रीम द्वारा प्रस्तुत MHTML स्रोत को परिवर्तित करें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित होता है।

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | MHTML रूपांतरण इनपुट डेटा स्ट्रीम। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। |

## Remarks

MHTML कनवर्टर

MHTML से PDF रूपांतरण अक्सर विशिष्ट कार्यों के लिए [PDF](https://docs.fileformat.com/pdf/) फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। PDF में कई लाभ होते हैं जो अन्य फ़ाइलों में नहीं होते। उदाहरण के लिए, कई प्रोग्राम और ऐप्स PDF दस्तावेज़ों का समर्थन करते हैं; PDF फ़ाइलें प्रिंटिंग के लिए अनुकूलित होती हैं, और वे आपके दस्तावेज़ों की भौतिक प्रतियां बनाने के लिए आदर्श हैं; आप PDF फ़ाइलों के लिए सुरक्षा सेटिंग्स कॉन्फ़िगर कर सकते हैं - प्रिंटिंग, संपादन, इलेक्ट्रॉनिक सिग्नेचर आदि को अक्षम कर सकते हैं।

देखें [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), जहाँ आप ConvertMHTML() मेथड्स का उपयोग करके [`Converter`](../) क्लास के माध्यम से MHTML को PDF में कैसे परिवर्तित करें और [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) तथा [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को कैसे लागू करें, इस बारे में जानकारी पा सकते हैं।

MHTML को PDF में बदलें

Converter क्लास कुछ MHTML‑विशिष्ट रूपांतरण PDF में प्रदान करती है। MHTML को PDF में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। स्थानीय मौजूद MHTML (.mht) फ़ाइल या रिमोट URL को रूपांतरण स्रोत के रूप में पहचानें। आप स्रोत के रूप में मानक या कस्टम विशिष्ट [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) का भी उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट बनाएं। आप वैकल्पिक पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर के साथ MHTML को PDF परिणाम के रूप में सहेजने के लिए Converter क्लास की ConvertMHTML() मेथड का उपयोग करें। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) प्रदान करता है जो MHTML को उच्च गुणवत्ता, आसान और तेज़ी से PDF में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // डिफ़ॉल्ट PdfSaveOptions ऑब्जेक्ट को परिभाषित करें
      var options = new PdfSaveOptions();

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_36}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत MHTML स्रोत को PDF में बदलें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित होता है।

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourcePath | String | MHTML स्रोत का पूर्ण फ़ाइल पथ। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। |

## Remarks

MHTML कनवर्टर

MHTML से PDF रूपांतरण अक्सर विशिष्ट कार्यों के लिए [PDF](https://docs.fileformat.com/pdf/) फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। PDF में कई लाभ होते हैं जो अन्य फ़ाइलों में नहीं होते। उदाहरण के लिए, कई प्रोग्राम और ऐप्स PDF दस्तावेज़ों का समर्थन करते हैं; PDF फ़ाइलें प्रिंटिंग के लिए अनुकूलित होती हैं, और वे आपके दस्तावेज़ों की भौतिक प्रतियां बनाने के लिए आदर्श हैं; आप PDF फ़ाइलों के लिए सुरक्षा सेटिंग्स कॉन्फ़िगर कर सकते हैं - प्रिंटिंग, संपादन, इलेक्ट्रॉनिक सिग्नेचर आदि को अक्षम कर सकते हैं।

देखें [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), जहाँ आप ConvertMHTML() मेथड्स का उपयोग करके [`Converter`](../) क्लास के माध्यम से MHTML को PDF में कैसे परिवर्तित करें और [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) तथा [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को कैसे लागू करें, इस बारे में जानकारी पा सकते हैं।

MHTML को PDF में बदलें

Converter क्लास कुछ MHTML‑विशिष्ट रूपांतरण PDF में प्रदान करती है। MHTML को PDF में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। स्थानीय मौजूद MHTML (.mht) फ़ाइल या रिमोट URL को रूपांतरण स्रोत के रूप में पहचानें। आप स्रोत के रूप में मानक या कस्टम विशिष्ट [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) का भी उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट बनाएं। आप वैकल्पिक पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर के साथ MHTML को PDF परिणाम के रूप में सहेजने के लिए Converter क्लास की ConvertMHTML() मेथड का उपयोग करें। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) प्रदान करता है जो MHTML को उच्च गुणवत्ता, आसान और तेज़ी से PDF में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // डिफ़ॉल्ट PdfSaveOptions ऑब्जेक्ट को परिभाषित करें
      var options = new PdfSaveOptions();

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_4}

[`URL`](../../../com.aspose.html/url/) द्वारा प्रस्तुत MHTML स्रोत को परिवर्तित करें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित होता है।

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceUrl | Url | MHTML स्रोत दस्तावेज़ URL - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। |

## Remarks

MHTML कनवर्टर

MHTML से PDF रूपांतरण अक्सर विशिष्ट कार्यों के लिए [PDF](https://docs.fileformat.com/pdf/) फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। PDF में कई लाभ होते हैं जो अन्य फ़ाइलों में नहीं होते। उदाहरण के लिए, कई प्रोग्राम और ऐप्स PDF दस्तावेज़ों का समर्थन करते हैं; PDF फ़ाइलें प्रिंटिंग के लिए अनुकूलित होती हैं, और वे आपके दस्तावेज़ों की भौतिक प्रतियां बनाने के लिए आदर्श हैं; आप PDF फ़ाइलों के लिए सुरक्षा सेटिंग्स कॉन्फ़िगर कर सकते हैं - प्रिंटिंग, संपादन, इलेक्ट्रॉनिक सिग्नेचर आदि को अक्षम कर सकते हैं।

देखें [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), जहाँ आप ConvertMHTML() मेथड्स का उपयोग करके [`Converter`](../) क्लास के माध्यम से MHTML को PDF में कैसे परिवर्तित करें और [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) तथा [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को कैसे लागू करें, इस बारे में जानकारी पा सकते हैं।

MHTML को PDF में बदलें

Converter क्लास कुछ MHTML‑विशिष्ट रूपांतरण PDF में प्रदान करती है। MHTML को PDF में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। स्थानीय मौजूद MHTML (.mht) फ़ाइल या रिमोट URL को रूपांतरण स्रोत के रूप में पहचानें। आप स्रोत के रूप में मानक या कस्टम विशिष्ट [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) का भी उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट बनाएं। आप वैकल्पिक पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर के साथ MHTML को PDF परिणाम के रूप में सहेजने के लिए Converter क्लास की ConvertMHTML() मेथड का उपयोग करें। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) प्रदान करता है जो MHTML को उच्च गुणवत्ता, आसान और तेज़ी से PDF में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // इनपुट फ़ाइल पथ के आधार पर URL बनाएं
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // डिफ़ॉल्ट PdfSaveOptions ऑब्जेक्ट को परिभाषित करें
      var options = new PdfSaveOptions();

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, ImageSaveOptions, String) {#convertmhtml_27}

इनपुट स्ट्रीम द्वारा प्रस्तुत MHTML स्रोत को छवि में परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित छवि फ़ाइल है।

```java
public static void ConvertMHTML(Stream stream, ImageSaveOptions options, String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | MHTML रूपांतरण इनपुट डेटा स्ट्रीम। |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), आदि निर्दिष्ट कर सकते हैं। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण इमेज फ़ाइल पथ। |

## Remarks

MHTML कनवर्टर

[MHTML] एक्सटेंशन वाली फ़ाइलें वेब पेज आर्काइव फ़ॉर्मेट को दर्शाती हैं जिसे कई विभिन्न एप्लिकेशन बना सकते हैं। यह फ़ॉर्मेट आर्काइव फ़ॉर्मेट के रूप में जाना जाता है क्योंकि यह वेब HTML कोड और संबंधित संसाधनों को एक ही फ़ाइल में सहेजता है। इन संसाधनों में वेबपेज से जुड़े सभी चीज़ें शामिल हैं जैसे छवियां, एप्पलेट्स, एनीमेशन, ऑडियो फ़ाइलें आदि। MHTML फ़ाइलें विभिन्न एप्लिकेशन जैसे Internet Explorer और Microsoft Word में खोली जा सकती हैं। फ़ॉर्मेट की वास्तविक विशिष्टताएँ [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557) द्वारा विस्तृत हैं।

लेख देखें, जहाँ आप Converter क्लास की ConvertMHTML() मेथड्स का उपयोग करके MHTML को विभिन्न फ़ॉर्मेट में इमेज में बदलने की जानकारी और [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) तथा [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को कैसे लागू करें, पा सकते हैं।

MHTML को इमेज में बदलें

Converter क्लास कुछ MHTML‑विशिष्ट रूपांतरण इमेज में प्रदान करती है। समर्थित फ़ॉर्मेट हैं [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) और [TIFF](https://docs.fileformat.com/image/tiff/)। MHTML को इमेज में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। स्थानीय मौजूद MHTML (.mht) फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप स्रोत के रूप में मानक या कस्टम विशिष्ट स्ट्रीम का भी उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट बनाएं। डिफ़ॉल्ट इमेज फ़ॉर्मेट PNG है। आप वैकल्पिक पैरामीटर के रूप में configuration भी जोड़ सकते हैं। उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर के साथ MHTML को इमेज परिणाम के रूप में सहेजने के लिए Converter क्लास की ConvertMHTML() मेथड का उपयोग करें। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) प्रदान करता है जो MHTML को उच्च गुणवत्ता, आसान और तेज़ी से jpeg फ़ाइल में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // डिफ़ॉल्ट ImageSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, ImageSaveOptions, String) {#convertmhtml_43}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत MHTML स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित छवि फ़ाइल है।

```java
public static void ConvertMHTML(String sourcePath, ImageSaveOptions options, String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourcePath | String | MHTML स्रोत का पूर्ण फ़ाइल पथ। |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), आदि निर्दिष्ट कर सकते हैं। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण इमेज फ़ाइल पथ। |

## Remarks

MHTML कनवर्टर

[MHTML] एक्सटेंशन वाली फ़ाइलें वेब पेज आर्काइव फ़ॉर्मेट को दर्शाती हैं जिसे कई विभिन्न एप्लिकेशन बना सकते हैं। यह फ़ॉर्मेट आर्काइव फ़ॉर्मेट के रूप में जाना जाता है क्योंकि यह वेब HTML कोड और संबंधित संसाधनों को एक ही फ़ाइल में सहेजता है। इन संसाधनों में वेबपेज से जुड़े सभी चीज़ें शामिल हैं जैसे छवियां, एप्पलेट्स, एनीमेशन, ऑडियो फ़ाइलें आदि। MHTML फ़ाइलें विभिन्न एप्लिकेशन जैसे Internet Explorer और Microsoft Word में खोली जा सकती हैं। फ़ॉर्मेट की वास्तविक विशिष्टताएँ [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557) द्वारा विस्तृत हैं।

लेख देखें, जहाँ आप Converter क्लास की ConvertMHTML() मेथड्स का उपयोग करके MHTML को विभिन्न फ़ॉर्मेट में इमेज में बदलने की जानकारी और [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) तथा [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को कैसे लागू करें, पा सकते हैं।

MHTML को इमेज में बदलें

Converter क्लास कुछ MHTML‑विशिष्ट रूपांतरण इमेज में प्रदान करती है। समर्थित फ़ॉर्मेट हैं [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) और [TIFF](https://docs.fileformat.com/image/tiff/)। MHTML को इमेज में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। स्थानीय मौजूद MHTML (.mht) फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप स्रोत के रूप में मानक या कस्टम विशिष्ट स्ट्रीम का भी उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट बनाएं। डिफ़ॉल्ट इमेज फ़ॉर्मेट PNG है। आप वैकल्पिक पैरामीटर के रूप में configuration भी जोड़ सकते हैं। उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर के साथ MHTML को इमेज परिणाम के रूप में सहेजने के लिए Converter क्लास की ConvertMHTML() मेथड का उपयोग करें। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) प्रदान करता है जो MHTML को उच्च गुणवत्ता, आसान और तेज़ी से jpeg फ़ाइल में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // डिफ़ॉल्ट ImageSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, ImageSaveOptions, String) {#convertmhtml_11}

URL द्वारा प्रस्तुत MHTML स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित इमेज फ़ाइल है।

```java
public static void ConvertMHTML(Url sourceUrl, ImageSaveOptions options, String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceUrl | Url | MHTML स्रोत दस्तावेज़ URL - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), आदि निर्दिष्ट कर सकते हैं। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण इमेज फ़ाइल पथ। |

## Remarks

MHTML कनवर्टर

[MHTML] एक्सटेंशन वाली फ़ाइलें वेब पेज आर्काइव फ़ॉर्मेट को दर्शाती हैं जिसे कई विभिन्न एप्लिकेशन बना सकते हैं। यह फ़ॉर्मेट आर्काइव फ़ॉर्मेट के रूप में जाना जाता है क्योंकि यह वेब HTML कोड और संबंधित संसाधनों को एक ही फ़ाइल में सहेजता है। इन संसाधनों में वेबपेज से जुड़े सभी चीज़ें शामिल हैं जैसे छवियां, एप्पलेट्स, एनीमेशन, ऑडियो फ़ाइलें आदि। MHTML फ़ाइलें विभिन्न एप्लिकेशन जैसे Internet Explorer और Microsoft Word में खोली जा सकती हैं। फ़ॉर्मेट की वास्तविक विशिष्टताएँ [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557) द्वारा विस्तृत हैं।

लेख देखें, जहाँ आप Converter क्लास की ConvertMHTML() मेथड्स का उपयोग करके MHTML को विभिन्न फ़ॉर्मेट में इमेज में बदलने की जानकारी और [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) तथा [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को कैसे लागू करें, पा सकते हैं।

MHTML को इमेज में बदलें

Converter क्लास कुछ MHTML‑विशिष्ट रूपांतरण इमेज में प्रदान करती है। समर्थित फ़ॉर्मेट हैं [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) और [TIFF](https://docs.fileformat.com/image/tiff/)। MHTML को इमेज में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। स्थानीय मौजूद MHTML (.mht) फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप स्रोत के रूप में मानक या कस्टम विशिष्ट स्ट्रीम का भी उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट बनाएं। डिफ़ॉल्ट इमेज फ़ॉर्मेट PNG है। आप वैकल्पिक पैरामीटर के रूप में configuration भी जोड़ सकते हैं। उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर के साथ MHTML को इमेज परिणाम के रूप में सहेजने के लिए Converter क्लास की ConvertMHTML() मेथड का उपयोग करें। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) प्रदान करता है जो MHTML को उच्च गुणवत्ता, आसान और तेज़ी से jpeg फ़ाइल में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // इनपुट फ़ाइल पथ के आधार पर URL बनाएं
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // डिफ़ॉल्ट ImageSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, ImageSaveOptions, String) {#convertmhtml_19}

इनपुट स्ट्रीम द्वारा प्रस्तुत MHTML स्रोत को छवि में परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित छवि फ़ाइल है।

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | MHTML रूपांतरण इनपुट डेटा स्ट्रीम। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), आदि निर्दिष्ट कर सकते हैं। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण इमेज फ़ाइल पथ। |

## Remarks

MHTML कनवर्टर

[MHTML] एक्सटेंशन वाली फ़ाइलें वेब पेज आर्काइव फ़ॉर्मेट को दर्शाती हैं जिसे कई विभिन्न एप्लिकेशन बना सकते हैं। यह फ़ॉर्मेट आर्काइव फ़ॉर्मेट के रूप में जाना जाता है क्योंकि यह वेब HTML कोड और संबंधित संसाधनों को एक ही फ़ाइल में सहेजता है। इन संसाधनों में वेबपेज से जुड़े सभी चीज़ें शामिल हैं जैसे छवियां, एप्पलेट्स, एनीमेशन, ऑडियो फ़ाइलें आदि। MHTML फ़ाइलें विभिन्न एप्लिकेशन जैसे Internet Explorer और Microsoft Word में खोली जा सकती हैं। फ़ॉर्मेट की वास्तविक विशिष्टताएँ [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557) द्वारा विस्तृत हैं।

लेख देखें, जहाँ आप Converter क्लास की ConvertMHTML() मेथड्स का उपयोग करके MHTML को विभिन्न फ़ॉर्मेट में इमेज में बदलने की जानकारी और [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) तथा [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को कैसे लागू करें, पा सकते हैं।

MHTML को इमेज में बदलें

Converter क्लास कुछ MHTML‑विशिष्ट रूपांतरण इमेज में प्रदान करती है। समर्थित फ़ॉर्मेट हैं [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) और [TIFF](https://docs.fileformat.com/image/tiff/)। MHTML को इमेज में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। स्थानीय मौजूद MHTML (.mht) फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप स्रोत के रूप में मानक या कस्टम विशिष्ट स्ट्रीम का भी उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट बनाएं। डिफ़ॉल्ट इमेज फ़ॉर्मेट PNG है। आप वैकल्पिक पैरामीटर के रूप में configuration भी जोड़ सकते हैं। उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर के साथ MHTML को इमेज परिणाम के रूप में सहेजने के लिए Converter क्लास की ConvertMHTML() मेथड का उपयोग करें। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) प्रदान करता है जो MHTML को उच्च गुणवत्ता, आसान और तेज़ी से jpeg फ़ाइल में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // डिफ़ॉल्ट ImageSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new ImageSaveOptions();

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, ImageSaveOptions, String) {#convertmhtml_35}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत MHTML स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित छवि फ़ाइल है।

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourcePath | String | MHTML स्रोत का पूर्ण फ़ाइल पथ। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), आदि निर्दिष्ट कर सकते हैं। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण इमेज फ़ाइल पथ। |

## Remarks

MHTML कनवर्टर

[MHTML] एक्सटेंशन वाली फ़ाइलें वेब पेज आर्काइव फ़ॉर्मेट को दर्शाती हैं जिसे कई विभिन्न एप्लिकेशन बना सकते हैं। यह फ़ॉर्मेट आर्काइव फ़ॉर्मेट के रूप में जाना जाता है क्योंकि यह वेब HTML कोड और संबंधित संसाधनों को एक ही फ़ाइल में सहेजता है। इन संसाधनों में वेबपेज से जुड़े सभी चीज़ें शामिल हैं जैसे छवियां, एप्पलेट्स, एनीमेशन, ऑडियो फ़ाइलें आदि। MHTML फ़ाइलें विभिन्न एप्लिकेशन जैसे Internet Explorer और Microsoft Word में खोली जा सकती हैं। फ़ॉर्मेट की वास्तविक विशिष्टताएँ [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557) द्वारा विस्तृत हैं।

लेख देखें, जहाँ आप Converter क्लास की ConvertMHTML() मेथड्स का उपयोग करके MHTML को विभिन्न फ़ॉर्मेट में इमेज में बदलने की जानकारी और [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) तथा [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को कैसे लागू करें, पा सकते हैं।

MHTML को इमेज में बदलें

Converter क्लास कुछ MHTML‑विशिष्ट रूपांतरण इमेज में प्रदान करती है। समर्थित फ़ॉर्मेट हैं [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) और [TIFF](https://docs.fileformat.com/image/tiff/)। MHTML को इमेज में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। स्थानीय मौजूद MHTML (.mht) फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप स्रोत के रूप में मानक या कस्टम विशिष्ट स्ट्रीम का भी उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट बनाएं। डिफ़ॉल्ट इमेज फ़ॉर्मेट PNG है। आप वैकल्पिक पैरामीटर के रूप में configuration भी जोड़ सकते हैं। उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर के साथ MHTML को इमेज परिणाम के रूप में सहेजने के लिए Converter क्लास की ConvertMHTML() मेथड का उपयोग करें। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) प्रदान करता है जो MHTML को उच्च गुणवत्ता, आसान और तेज़ी से jpeg फ़ाइल में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // डिफ़ॉल्ट ImageSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new ImageSaveOptions();

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, ImageSaveOptions, String) {#convertmhtml_3}

URL द्वारा प्रस्तुत MHTML स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित इमेज फ़ाइल है।

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceUrl | Url | MHTML स्रोत दस्तावेज़ URL - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), आदि निर्दिष्ट कर सकते हैं। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण इमेज फ़ाइल पथ। |

## Remarks

MHTML कनवर्टर

[MHTML] एक्सटेंशन वाली फ़ाइलें वेब पेज आर्काइव फ़ॉर्मेट को दर्शाती हैं जिसे कई विभिन्न एप्लिकेशन बना सकते हैं। यह फ़ॉर्मेट आर्काइव फ़ॉर्मेट के रूप में जाना जाता है क्योंकि यह वेब HTML कोड और संबंधित संसाधनों को एक ही फ़ाइल में सहेजता है। इन संसाधनों में वेबपेज से जुड़े सभी चीज़ें शामिल हैं जैसे छवियां, एप्पलेट्स, एनीमेशन, ऑडियो फ़ाइलें आदि। MHTML फ़ाइलें विभिन्न एप्लिकेशन जैसे Internet Explorer और Microsoft Word में खोली जा सकती हैं। फ़ॉर्मेट की वास्तविक विशिष्टताएँ [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557) द्वारा विस्तृत हैं।

लेख देखें, जहाँ आप Converter क्लास की ConvertMHTML() मेथड्स का उपयोग करके MHTML को विभिन्न फ़ॉर्मेट में इमेज में बदलने की जानकारी और [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) तथा [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को कैसे लागू करें, पा सकते हैं।

MHTML को इमेज में बदलें

Converter क्लास कुछ MHTML‑विशिष्ट रूपांतरण इमेज में प्रदान करती है। समर्थित फ़ॉर्मेट हैं [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) और [TIFF](https://docs.fileformat.com/image/tiff/)। MHTML को इमेज में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। स्थानीय मौजूद MHTML (.mht) फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप स्रोत के रूप में मानक या कस्टम विशिष्ट स्ट्रीम का भी उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट बनाएं। डिफ़ॉल्ट इमेज फ़ॉर्मेट PNG है। आप वैकल्पिक पैरामीटर के रूप में configuration भी जोड़ सकते हैं। उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर के साथ MHTML को इमेज परिणाम के रूप में सहेजने के लिए Converter क्लास की ConvertMHTML() मेथड का उपयोग करें। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) प्रदान करता है जो MHTML को उच्च गुणवत्ता, आसान और तेज़ी से jpeg फ़ाइल में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // इनपुट फ़ाइल पथ के आधार पर URL बनाएं
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // डिफ़ॉल्ट ImageSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new ImageSaveOptions();

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_26}

इनपुट स्ट्रीम द्वारा प्रस्तुत MHTML स्रोत को परिवर्तित करें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित होता है।

```java
public static void ConvertMHTML(Stream stream, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | MHTML रूपांतरण इनपुट डेटा स्ट्रीम। |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), आदि निर्दिष्ट कर सकते हैं। |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। |

## Remarks

MHTML कनवर्टर

[MHTML] एक्सटेंशन वाली फ़ाइलें वेब पेज आर्काइव फ़ॉर्मेट को दर्शाती हैं जिसे कई विभिन्न एप्लिकेशन बना सकते हैं। यह फ़ॉर्मेट आर्काइव फ़ॉर्मेट के रूप में जाना जाता है क्योंकि यह वेब HTML कोड और संबंधित संसाधनों को एक ही फ़ाइल में सहेजता है। इन संसाधनों में वेबपेज से जुड़े सभी चीज़ें शामिल हैं जैसे छवियां, एप्पलेट्स, एनीमेशन, ऑडियो फ़ाइलें आदि। MHTML फ़ाइलें विभिन्न एप्लिकेशन जैसे Internet Explorer और Microsoft Word में खोली जा सकती हैं। फ़ॉर्मेट की वास्तविक विशिष्टताएँ [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557) द्वारा विस्तृत हैं।

लेख देखें, जहाँ आप Converter क्लास की ConvertMHTML() मेथड्स का उपयोग करके MHTML को विभिन्न फ़ॉर्मेट में इमेज में बदलने की जानकारी और [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) तथा [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को कैसे लागू करें, पा सकते हैं।

MHTML को इमेज में बदलें

Converter क्लास कुछ MHTML‑विशिष्ट रूपांतरण इमेज में प्रदान करती है। समर्थित फ़ॉर्मेट हैं [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) और [TIFF](https://docs.fileformat.com/image/tiff/)। MHTML को इमेज में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। स्थानीय मौजूद MHTML (.mht) फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप स्रोत के रूप में मानक या कस्टम विशिष्ट स्ट्रीम का भी उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट बनाएं। डिफ़ॉल्ट इमेज फ़ॉर्मेट PNG है। आप वैकल्पिक पैरामीटर के रूप में configuration भी जोड़ सकते हैं। उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर के साथ MHTML को इमेज परिणाम के रूप में सहेजने के लिए Converter क्लास की ConvertMHTML() मेथड का उपयोग करें। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) प्रदान करता है जो MHTML को उच्च गुणवत्ता, आसान और तेज़ी से jpeg फ़ाइल में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // डिफ़ॉल्ट ImageSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new ImageSaveOptions();

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_42}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत MHTML स्रोत को इमेज में बदलें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित होता है।

```java
public static void ConvertMHTML(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourcePath | String | MHTML स्रोत का पूर्ण फ़ाइल पथ। |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), आदि निर्दिष्ट कर सकते हैं। |
| provider | ICreateStreamProvider | ज्ञात (देखें [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन। |

## Remarks

MHTML कनवर्टर

[MHTML] एक्सटेंशन वाली फ़ाइलें वेब पेज आर्काइव फ़ॉर्मेट को दर्शाती हैं जिसे कई विभिन्न एप्लिकेशन बना सकते हैं। यह फ़ॉर्मेट आर्काइव फ़ॉर्मेट के रूप में जाना जाता है क्योंकि यह वेब HTML कोड और संबंधित संसाधनों को एक ही फ़ाइल में सहेजता है। इन संसाधनों में वेबपेज से जुड़े सभी चीज़ें शामिल हैं जैसे छवियां, एप्पलेट्स, एनीमेशन, ऑडियो फ़ाइलें आदि। MHTML फ़ाइलें विभिन्न एप्लिकेशन जैसे Internet Explorer और Microsoft Word में खोली जा सकती हैं। फ़ॉर्मेट की वास्तविक विशिष्टताएँ [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557) द्वारा विस्तृत हैं।

लेख देखें, जहाँ आप Converter क्लास की ConvertMHTML() मेथड्स का उपयोग करके MHTML को विभिन्न फ़ॉर्मेट में इमेज में बदलने की जानकारी और [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) तथा [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को कैसे लागू करें, पा सकते हैं।

MHTML को इमेज में बदलें

Converter क्लास कुछ MHTML‑विशिष्ट रूपांतरण इमेज में प्रदान करती है। समर्थित फ़ॉर्मेट हैं [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) और [TIFF](https://docs.fileformat.com/image/tiff/)। MHTML को इमेज में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। स्थानीय मौजूद MHTML (.mht) फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप स्रोत के रूप में मानक या कस्टम विशिष्ट स्ट्रीम का भी उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट बनाएं। डिफ़ॉल्ट इमेज फ़ॉर्मेट PNG है। आप वैकल्पिक पैरामीटर के रूप में configuration भी जोड़ सकते हैं। उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर के साथ MHTML को इमेज परिणाम के रूप में सहेजने के लिए Converter क्लास की ConvertMHTML() मेथड का उपयोग करें। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) प्रदान करता है जो MHTML को उच्च गुणवत्ता, आसान और तेज़ी से jpeg फ़ाइल में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // डिफ़ॉल्ट ImageSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new ImageSaveOptions();

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_10}

URL द्वारा प्रस्तुत MHTML स्रोत को परिवर्तित करें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित होता है।

```java
public static void ConvertMHTML(Url sourceUrl, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceUrl | Url | MHTML स्रोत दस्तावेज़ URL - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), आदि निर्दिष्ट कर सकते हैं। |
| provider | ICreateStreamProvider | ज्ञात (देखें [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन। |

## Remarks

MHTML कनवर्टर

[MHTML] एक्सटेंशन वाली फ़ाइलें वेब पेज आर्काइव फ़ॉर्मेट को दर्शाती हैं जिसे कई विभिन्न एप्लिकेशन बना सकते हैं। यह फ़ॉर्मेट आर्काइव फ़ॉर्मेट के रूप में जाना जाता है क्योंकि यह वेब HTML कोड और संबंधित संसाधनों को एक ही फ़ाइल में सहेजता है। इन संसाधनों में वेबपेज से जुड़े सभी चीज़ें शामिल हैं जैसे छवियां, एप्पलेट्स, एनीमेशन, ऑडियो फ़ाइलें आदि। MHTML फ़ाइलें विभिन्न एप्लिकेशन जैसे Internet Explorer और Microsoft Word में खोली जा सकती हैं। फ़ॉर्मेट की वास्तविक विशिष्टताएँ [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557) द्वारा विस्तृत हैं।

लेख देखें, जहाँ आप Converter क्लास की ConvertMHTML() मेथड्स का उपयोग करके MHTML को विभिन्न फ़ॉर्मेट में इमेज में बदलने की जानकारी और [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) तथा [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को कैसे लागू करें, पा सकते हैं।

MHTML को इमेज में बदलें

Converter क्लास कुछ MHTML‑विशिष्ट रूपांतरण इमेज में प्रदान करती है। समर्थित फ़ॉर्मेट हैं [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) और [TIFF](https://docs.fileformat.com/image/tiff/)। MHTML को इमेज में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। स्थानीय मौजूद MHTML (.mht) फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप स्रोत के रूप में मानक या कस्टम विशिष्ट स्ट्रीम का भी उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट बनाएं। डिफ़ॉल्ट इमेज फ़ॉर्मेट PNG है। आप वैकल्पिक पैरामीटर के रूप में configuration भी जोड़ सकते हैं। उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर के साथ MHTML को इमेज परिणाम के रूप में सहेजने के लिए Converter क्लास की ConvertMHTML() मेथड का उपयोग करें। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) प्रदान करता है जो MHTML को उच्च गुणवत्ता, आसान और तेज़ी से jpeg फ़ाइल में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // इनपुट फ़ाइल पथ के आधार पर URL बनाएं
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // डिफ़ॉल्ट ImageSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new ImageSaveOptions(ImageFormat.Tiff);

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_18}

इनपुट स्ट्रीम द्वारा प्रस्तुत MHTML स्रोत को परिवर्तित करें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित होता है।

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | MHTML रूपांतरण इनपुट डेटा स्ट्रीम। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), आदि निर्दिष्ट कर सकते हैं। |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। |

## Remarks

MHTML कनवर्टर

[MHTML] एक्सटेंशन वाली फ़ाइलें वेब पेज आर्काइव फ़ॉर्मेट को दर्शाती हैं जिसे कई विभिन्न एप्लिकेशन बना सकते हैं। यह फ़ॉर्मेट आर्काइव फ़ॉर्मेट के रूप में जाना जाता है क्योंकि यह वेब HTML कोड और संबंधित संसाधनों को एक ही फ़ाइल में सहेजता है। इन संसाधनों में वेबपेज से जुड़े सभी चीज़ें शामिल हैं जैसे छवियां, एप्पलेट्स, एनीमेशन, ऑडियो फ़ाइलें आदि। MHTML फ़ाइलें विभिन्न एप्लिकेशन जैसे Internet Explorer और Microsoft Word में खोली जा सकती हैं। फ़ॉर्मेट की वास्तविक विशिष्टताएँ [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557) द्वारा विस्तृत हैं।

लेख देखें, जहाँ आप Converter क्लास की ConvertMHTML() मेथड्स का उपयोग करके MHTML को विभिन्न फ़ॉर्मेट में इमेज में बदलने की जानकारी और [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) तथा [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को कैसे लागू करें, पा सकते हैं।

MHTML को इमेज में बदलें

Converter क्लास कुछ MHTML‑विशिष्ट रूपांतरण इमेज में प्रदान करती है। समर्थित फ़ॉर्मेट हैं [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) और [TIFF](https://docs.fileformat.com/image/tiff/)। MHTML को इमेज में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। स्थानीय मौजूद MHTML (.mht) फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप स्रोत के रूप में मानक या कस्टम विशिष्ट स्ट्रीम का भी उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट बनाएं। डिफ़ॉल्ट इमेज फ़ॉर्मेट PNG है। आप वैकल्पिक पैरामीटर के रूप में configuration भी जोड़ सकते हैं। उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर के साथ MHTML को इमेज परिणाम के रूप में सहेजने के लिए Converter क्लास की ConvertMHTML() मेथड का उपयोग करें। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) प्रदान करता है जो MHTML को उच्च गुणवत्ता, आसान और तेज़ी से jpeg फ़ाइल में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // डिफ़ॉल्ट ImageSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new ImageSaveOptions();

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_34}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत MHTML स्रोत को इमेज में बदलें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित होता है।

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourcePath | String | MHTML स्रोत का पूर्ण फ़ाइल पथ। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), आदि निर्दिष्ट कर सकते हैं। |
| provider | ICreateStreamProvider | ` interface` का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। |

## Remarks

MHTML कनवर्टर

[MHTML] एक्सटेंशन वाली फ़ाइलें वेब पेज आर्काइव फ़ॉर्मेट को दर्शाती हैं जिसे कई विभिन्न एप्लिकेशन बना सकते हैं। यह फ़ॉर्मेट आर्काइव फ़ॉर्मेट के रूप में जाना जाता है क्योंकि यह वेब HTML कोड और संबंधित संसाधनों को एक ही फ़ाइल में सहेजता है। इन संसाधनों में वेबपेज से जुड़े सभी चीज़ें शामिल हैं जैसे छवियां, एप्पलेट्स, एनीमेशन, ऑडियो फ़ाइलें आदि। MHTML फ़ाइलें विभिन्न एप्लिकेशन जैसे Internet Explorer और Microsoft Word में खोली जा सकती हैं। फ़ॉर्मेट की वास्तविक विशिष्टताएँ [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557) द्वारा विस्तृत हैं।

लेख देखें, जहाँ आप Converter क्लास की ConvertMHTML() मेथड्स का उपयोग करके MHTML को विभिन्न फ़ॉर्मेट में इमेज में बदलने की जानकारी और [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) तथा [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को कैसे लागू करें, पा सकते हैं।

MHTML को इमेज में बदलें

Converter क्लास कुछ MHTML‑विशिष्ट रूपांतरण इमेज में प्रदान करती है। समर्थित फ़ॉर्मेट हैं [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) और [TIFF](https://docs.fileformat.com/image/tiff/)। MHTML को इमेज में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। स्थानीय मौजूद MHTML (.mht) फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप स्रोत के रूप में मानक या कस्टम विशिष्ट स्ट्रीम का भी उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट बनाएं। डिफ़ॉल्ट इमेज फ़ॉर्मेट PNG है। आप वैकल्पिक पैरामीटर के रूप में configuration भी जोड़ सकते हैं। उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर के साथ MHTML को इमेज परिणाम के रूप में सहेजने के लिए Converter क्लास की ConvertMHTML() मेथड का उपयोग करें। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) प्रदान करता है जो MHTML को उच्च गुणवत्ता, आसान और तेज़ी से jpeg फ़ाइल में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // डिफ़ॉल्ट ImageSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new ImageSaveOptions();

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_2}

URL द्वारा प्रस्तुत MHTML स्रोत को परिवर्तित करें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित होता है।

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceUrl | Url | MHTML स्रोत दस्तावेज़ URL - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), आदि निर्दिष्ट कर सकते हैं। |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। |

## Remarks

MHTML कनवर्टर

[MHTML] एक्सटेंशन वाली फ़ाइलें वेब पेज आर्काइव फ़ॉर्मेट को दर्शाती हैं जिसे कई विभिन्न एप्लिकेशन बना सकते हैं। यह फ़ॉर्मेट आर्काइव फ़ॉर्मेट के रूप में जाना जाता है क्योंकि यह वेब HTML कोड और संबंधित संसाधनों को एक ही फ़ाइल में सहेजता है। इन संसाधनों में वेबपेज से जुड़े सभी चीज़ें शामिल हैं जैसे छवियां, एप्पलेट्स, एनीमेशन, ऑडियो फ़ाइलें आदि। MHTML फ़ाइलें विभिन्न एप्लिकेशन जैसे Internet Explorer और Microsoft Word में खोली जा सकती हैं। फ़ॉर्मेट की वास्तविक विशिष्टताएँ [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557) द्वारा विस्तृत हैं।

लेख देखें, जहाँ आप Converter क्लास की ConvertMHTML() मेथड्स का उपयोग करके MHTML को विभिन्न फ़ॉर्मेट में इमेज में बदलने की जानकारी और [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) तथा [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को कैसे लागू करें, पा सकते हैं।

MHTML को इमेज में बदलें

Converter क्लास कुछ MHTML‑विशिष्ट रूपांतरण इमेज में प्रदान करती है। समर्थित फ़ॉर्मेट हैं [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) और [TIFF](https://docs.fileformat.com/image/tiff/)। MHTML को इमेज में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। स्थानीय मौजूद MHTML (.mht) फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप स्रोत के रूप में मानक या कस्टम विशिष्ट स्ट्रीम का भी उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट बनाएं। डिफ़ॉल्ट इमेज फ़ॉर्मेट PNG है। आप वैकल्पिक पैरामीटर के रूप में configuration भी जोड़ सकते हैं। उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर के साथ MHTML को इमेज परिणाम के रूप में सहेजने के लिए Converter क्लास की ConvertMHTML() मेथड का उपयोग करें। ऑनलाइन MHTML कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) प्रदान करता है जो MHTML को उच्च गुणवत्ता, आसान और तेज़ी से jpeg फ़ाइल में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // इनपुट फ़ाइल पथ के आधार पर URL बनाएं
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // डिफ़ॉल्ट ImageSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new ImageSaveOptions(ImageFormat.Bmp);

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

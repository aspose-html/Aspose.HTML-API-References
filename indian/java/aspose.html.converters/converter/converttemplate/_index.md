---
title: "Converter.ConvertTemplate"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "Converter मेथड। HTMLDocument द्वारा प्रस्तुत टेम्पलेट स्रोत को टेम्पलेट डेटा XML JSON के साथ मिलाएँ। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित HTML फ़ाइल है।"
type: docs

url: /hi/java/com.aspose.html.converters/converter/converttemplate/
---
## ConvertTemplate(HTMLDocument, TemplateData, TemplateLoadOptions, String) {#converttemplate_7}

[`HTMLDocument`](../../../com.aspose.html/htmldocument/) द्वारा प्रस्तुत टेम्पलेट स्रोत को टेम्पलेट डेटा (XML, JSON) के साथ मिलाएँ। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित HTML फ़ाइल है।

```java
public static void ConvertTemplate(HTMLDocument template, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| template | HTMLDocument | [`HTMLDocument`](../../../com.aspose.html/htmldocument/) द्वारा प्रस्तुत स्रोत स्केलेटन को मिलाना। |
| डेटा | TemplateData | मर्जिंग के लिए टेम्प्लेट डेटा - प्रतिस्थापन (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) ऑब्जेक्ट इंस्टेंस। यह निर्धारित करने के लिए उपयोग किया जाता है कि टेम्प्लेट और डेटा आइटम नाम केस की परवाह किए बिना मेल खाते हैं या नहीं (विकल्प)। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण HTML फ़ाइल पथ। |

## टिप्पणियाँ

टेम्प्लेट मर्जर

टेम्प्लेट मर्जिंग का विचार यह है कि एक HTML दस्तावेज़ को HTML टेम्प्लेट के आधार पर बनाया जाए और इसे डेटा स्रोत से भर दिया जाए। Aspose.HTML टेम्प्लेट्स के साथ काम करने और विभिन्न डेटा स्रोत प्रकारों, जैसे XML और JSON, के लिए इनलाइन एक्सप्रेशन सिंटैक्स प्रदान करता है। अधिक जानकारी के लिए [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) देखें जहाँ आप टेम्प्लेट मर्जिंग और ConvertTemplate() मेथड के उपयोग के बारे में अधिक जानकारी पा सकते हैं।

रूपांतरण (मर्जिंग) चरण

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

टेम्प्लेट स्रोत। फ़ाइल, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ऑब्जेक्ट इंस्टेंस या यहाँ तक कि इनलाइन कंटेंट द्वारा HTML टेम्प्लेट स्रोत को परिभाषित करें। रूपांतरण परिणाम। आप सीधे परिणामी HTMLDocument प्राप्त कर सकते हैं या मेथड सिग्नेचर के आधार पर परिणाम आउटपुट फ़ाइल पथ को परिभाषित कर सकते हैं। [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) का इंस्टेंस बनाएं। टेम्प्लेट को डेटा के साथ मर्ज करने के लिए Converter क्लास की ConvertTemplate() मेथड का उपयोग करें। आप वैकल्पिक पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // फ़ॉर्म कंकाल HTML स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // फ़ॉर्म XML (JSON) टेम्प्लेट डेटा फ़ाइल पथ
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");
      
      // TemplateData ऑब्जेक्ट इंस्टेंस को परिभाषित करें
      var templateData = new TemplateData(templateDataPath);

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // डिफ़ॉल्ट TemplateLoadOptions ऑब्जेक्ट को परिभाषित करें
      var options = new TemplateLoadOptions();

      // फ़ॉर्म HTML दस्तावेज़ को रूपांतरण स्रोत के रूप में
      var document = new HTMLDocument(sourcePath, new Configuration());

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertTemplate(document, templateData, options, resultPath);

      // संसाधनों को साफ़ करें
      document.Dispose();





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### संबंधित देखें

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, TemplateData, TemplateLoadOptions, String) {#converttemplate_9}

[`URL`](../../../com.aspose.html/url/) द्वारा प्रस्तुत टेम्प्लेट HTML स्रोत को टेम्प्लेट डेटा (XML, JSON) के साथ मर्ज करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित HTML फ़ाइल है।

```java
public static void ConvertTemplate(Url url, TemplateData data, TemplateLoadOptions options, 
    String outputPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| url | Url | [`URL`](../../../com.aspose.html/url/) द्वारा प्रस्तुत HTML स्रोत कंकाल को मर्ज किया जा रहा है। |
| डेटा | TemplateData | मर्जिंग के लिए टेम्प्लेट डेटा - प्रतिस्थापन (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) ऑब्जेक्ट इंस्टेंस। यह निर्धारित करने के लिए उपयोग किया जाता है कि टेम्प्लेट और डेटा आइटम नाम केस की परवाह किए बिना मेल खाते हैं या नहीं (विकल्प)। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण HTML फ़ाइल पथ। |

## टिप्पणियाँ

टेम्प्लेट मर्जर

टेम्प्लेट मर्जिंग का विचार यह है कि एक HTML दस्तावेज़ को HTML टेम्प्लेट के आधार पर बनाया जाए और इसे डेटा स्रोत से भर दिया जाए। Aspose.HTML टेम्प्लेट्स के साथ काम करने और विभिन्न डेटा स्रोत प्रकारों, जैसे XML और JSON, के लिए इनलाइन एक्सप्रेशन सिंटैक्स प्रदान करता है। अधिक जानकारी के लिए [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) देखें जहाँ आप टेम्प्लेट मर्जिंग और ConvertTemplate() मेथड के उपयोग के बारे में अधिक जानकारी पा सकते हैं।

रूपांतरण (मर्जिंग) चरण

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

टेम्प्लेट स्रोत। फ़ाइल, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ऑब्जेक्ट इंस्टेंस या यहाँ तक कि इनलाइन कंटेंट द्वारा HTML टेम्प्लेट स्रोत को परिभाषित करें। रूपांतरण परिणाम। आप सीधे परिणामी HTMLDocument प्राप्त कर सकते हैं या मेथड सिग्नेचर के आधार पर परिणाम आउटपुट फ़ाइल पथ को परिभाषित कर सकते हैं। [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) का इंस्टेंस बनाएं। टेम्प्लेट को डेटा के साथ मर्ज करने के लिए Converter क्लास की ConvertTemplate() मेथड का उपयोग करें। आप वैकल्पिक पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // फ़ॉर्म कंकाल HTML स्रोत URL
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // फ़ॉर्म XML (JSON) टेम्प्लेट डेटा फ़ाइल पथ
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // TemplateData ऑब्जेक्ट इंस्टेंस को परिभाषित करें
      var templateData = new TemplateData(templateDataPath);

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // डिफ़ॉल्ट TemplateLoadOptions ऑब्जेक्ट को परिभाषित करें
      var options = new TemplateLoadOptions();

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertTemplate(sourceUrl, templateData, options, resultPath);





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### संबंधित देखें

* class [Url](../../../com.aspose.html/url/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_8}

[`URL`](../../../com.aspose.html/url/) द्वारा प्रस्तुत टेम्प्लेट HTML स्रोत को टेम्प्लेट डेटा (XML, JSON) के साथ मर्ज करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित HTML फ़ाइल है।

```java
public static void ConvertTemplate(Url url, Configuration configuration, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| url | Url | [`URL`](../../../com.aspose.html/url/) द्वारा प्रस्तुत HTML स्रोत कंकाल को मर्ज किया जा रहा है। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट को दर्शाता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| डेटा | TemplateData | मर्जिंग के लिए टेम्प्लेट डेटा - प्रतिस्थापन (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) ऑब्जेक्ट इंस्टेंस। यह निर्धारित करने के लिए उपयोग किया जाता है कि टेम्प्लेट और डेटा आइटम नाम केस की परवाह किए बिना मेल खाते हैं या नहीं (विकल्प)। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण HTML फ़ाइल पथ। |

## टिप्पणियाँ

टेम्प्लेट मर्जर

टेम्प्लेट मर्जिंग का विचार यह है कि एक HTML दस्तावेज़ को HTML टेम्प्लेट के आधार पर बनाया जाए और इसे डेटा स्रोत से भर दिया जाए। Aspose.HTML टेम्प्लेट्स के साथ काम करने और विभिन्न डेटा स्रोत प्रकारों, जैसे XML और JSON, के लिए इनलाइन एक्सप्रेशन सिंटैक्स प्रदान करता है। अधिक जानकारी के लिए [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) देखें जहाँ आप टेम्प्लेट मर्जिंग और ConvertTemplate() मेथड के उपयोग के बारे में अधिक जानकारी पा सकते हैं।

रूपांतरण (मर्जिंग) चरण

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

टेम्प्लेट स्रोत। फ़ाइल, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ऑब्जेक्ट इंस्टेंस या यहाँ तक कि इनलाइन कंटेंट द्वारा HTML टेम्प्लेट स्रोत को परिभाषित करें। रूपांतरण परिणाम। आप सीधे परिणामी HTMLDocument प्राप्त कर सकते हैं या मेथड सिग्नेचर के आधार पर परिणाम आउटपुट फ़ाइल पथ को परिभाषित कर सकते हैं। [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) का इंस्टेंस बनाएं। टेम्प्लेट को डेटा के साथ मर्ज करने के लिए Converter क्लास की ConvertTemplate() मेथड का उपयोग करें। आप वैकल्पिक पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // फ़ॉर्म कंकाल HTML स्रोत URL
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // फ़ॉर्म XML (JSON) टेम्प्लेट डेटा फ़ाइल पथ
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // TemplateData ऑब्जेक्ट इंस्टेंस को परिभाषित करें 
      var templateData = new TemplateData(templateDataPath);

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // डिफ़ॉल्ट TemplateLoadOptions ऑब्जेक्ट को परिभाषित करें
      var options = new TemplateLoadOptions();

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertTemplate(sourceUrl, new Configuration(), templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### संबंधित देखें

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, TemplateData, TemplateLoadOptions, String) {#converttemplate_11}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत टेम्प्लेट HTML स्रोत को टेम्प्लेट डेटा (XML, JSON) के साथ मिलाएँ। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित html फ़ाइल है।

```java
public static void ConvertTemplate(String sourcePath, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| sourcePath | String | पूर्ण फ़ाइल पथ द्वारा प्रस्तुत HTML स्रोत कंकाल को मर्ज किया जा रहा है। |
| डेटा | TemplateData | मर्जिंग के लिए टेम्प्लेट डेटा - प्रतिस्थापन (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) ऑब्जेक्ट इंस्टेंस। यह निर्धारित करने के लिए उपयोग किया जाता है कि टेम्प्लेट और डेटा आइटम नाम केस की परवाह किए बिना मेल खाते हैं या नहीं (विकल्प)। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण HTML फ़ाइल पथ। |

## टिप्पणियाँ

टेम्प्लेट मर्जर

टेम्प्लेट मर्जिंग का विचार यह है कि एक HTML दस्तावेज़ को HTML टेम्प्लेट के आधार पर बनाया जाए और इसे डेटा स्रोत से भर दिया जाए। Aspose.HTML टेम्प्लेट्स के साथ काम करने और विभिन्न डेटा स्रोत प्रकारों, जैसे XML और JSON, के लिए इनलाइन एक्सप्रेशन सिंटैक्स प्रदान करता है। अधिक जानकारी के लिए [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) देखें जहाँ आप टेम्प्लेट मर्जिंग और ConvertTemplate() मेथड के उपयोग के बारे में अधिक जानकारी पा सकते हैं।

रूपांतरण (मर्जिंग) चरण

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

टेम्प्लेट स्रोत। फ़ाइल, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ऑब्जेक्ट इंस्टेंस या यहाँ तक कि इनलाइन कंटेंट द्वारा HTML टेम्प्लेट स्रोत को परिभाषित करें। रूपांतरण परिणाम। आप सीधे परिणामी HTMLDocument प्राप्त कर सकते हैं या मेथड सिग्नेचर के आधार पर परिणाम आउटपुट फ़ाइल पथ को परिभाषित कर सकते हैं। [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) का इंस्टेंस बनाएं। टेम्प्लेट को डेटा के साथ मर्ज करने के लिए Converter क्लास की ConvertTemplate() मेथड का उपयोग करें। आप वैकल्पिक पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // फ़ॉर्म कंकाल HTML स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // फ़ॉर्म XML (JSON) टेम्प्लेट डेटा फ़ाइल पथ
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // TemplateData ऑब्जेक्ट इंस्टेंस को परिभाषित करें
      var templateData = new TemplateData(templateDataPath);

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // डिफ़ॉल्ट TemplateLoadOptions ऑब्जेक्ट को परिभाषित करें
      var options = new TemplateLoadOptions();

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertTemplate(sourcePath, templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### संबंधित देखें

* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_10}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत टेम्प्लेट HTML स्रोत को टेम्प्लेट डेटा (XML, JSON) के साथ मिलाएँ। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित html फ़ाइल है।

```java
public static void ConvertTemplate(String sourcePath, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options, String outputPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| sourcePath | String | पूर्ण फ़ाइल पथ द्वारा प्रस्तुत HTML स्रोत कंकाल को मर्ज किया जा रहा है। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट को दर्शाता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| डेटा | TemplateData | मर्जिंग के लिए टेम्प्लेट डेटा - प्रतिस्थापन (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) ऑब्जेक्ट इंस्टेंस। यह निर्धारित करने के लिए उपयोग किया जाता है कि टेम्प्लेट और डेटा आइटम नाम केस की परवाह किए बिना मेल खाते हैं या नहीं (विकल्प)। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण HTML फ़ाइल पथ। |

## टिप्पणियाँ

टेम्प्लेट मर्जर

टेम्प्लेट मर्जिंग का विचार यह है कि एक HTML दस्तावेज़ को HTML टेम्प्लेट के आधार पर बनाया जाए और इसे डेटा स्रोत से भर दिया जाए। Aspose.HTML टेम्प्लेट्स के साथ काम करने और विभिन्न डेटा स्रोत प्रकारों, जैसे XML और JSON, के लिए इनलाइन एक्सप्रेशन सिंटैक्स प्रदान करता है। अधिक जानकारी के लिए [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) देखें जहाँ आप टेम्प्लेट मर्जिंग और ConvertTemplate() मेथड के उपयोग के बारे में अधिक जानकारी पा सकते हैं।

रूपांतरण (मर्जिंग) चरण

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

टेम्प्लेट स्रोत। फ़ाइल, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ऑब्जेक्ट इंस्टेंस या यहाँ तक कि इनलाइन कंटेंट द्वारा HTML टेम्प्लेट स्रोत को परिभाषित करें। रूपांतरण परिणाम। आप सीधे परिणामी HTMLDocument प्राप्त कर सकते हैं या मेथड सिग्नेचर के आधार पर परिणाम आउटपुट फ़ाइल पथ को परिभाषित कर सकते हैं। [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) का इंस्टेंस बनाएं। टेम्प्लेट को डेटा के साथ मर्ज करने के लिए Converter क्लास की ConvertTemplate() मेथड का उपयोग करें। आप वैकल्पिक पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // फ़ॉर्म कंकाल HTML स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // फ़ॉर्म XML (JSON) टेम्प्लेट डेटा फ़ाइल पथ
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // TemplateData ऑब्जेक्ट इंस्टेंस को परिभाषित करें
      var templateData = new TemplateData(templateDataPath);

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // डिफ़ॉल्ट TemplateLoadOptions ऑब्जेक्ट को परिभाषित करें
      var options = new TemplateLoadOptions();

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertTemplate(sourcePath, new Configuration(), templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### संबंधित देखें

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, TemplateData, TemplateLoadOptions, String) {#converttemplate_13}

इनलाइन सामग्री द्वारा प्रस्तुत टेम्प्लेट HTML स्रोत को टेम्प्लेट डेटा (XML, JSON) के साथ मिलाएँ। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित html फ़ाइल है।

```java
public static void ConvertTemplate(String content, String baseUrl, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| सामग्री | String | इनलाइन स्ट्रिंग कंटेंट द्वारा प्रस्तुत HTML स्रोत कंकाल को मर्ज किया जा रहा है। |
| baseUrl | String | HTML टेम्प्लेट का बेस URI। यह वर्तमान डायरेक्टरी पथ के साथ मिलकर एक पूर्ण URL बनाएगा। |
| डेटा | TemplateData | मर्जिंग के लिए टेम्प्लेट डेटा - प्रतिस्थापन (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) ऑब्जेक्ट इंस्टेंस। यह निर्धारित करने के लिए उपयोग किया जाता है कि टेम्प्लेट और डेटा आइटम नाम केस की परवाह किए बिना मेल खाते हैं या नहीं (विकल्प)। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण HTML फ़ाइल पथ। |

## टिप्पणियाँ

टेम्प्लेट मर्जर

टेम्प्लेट मर्जिंग का विचार यह है कि एक HTML दस्तावेज़ को HTML टेम्प्लेट के आधार पर बनाया जाए और इसे डेटा स्रोत से भर दिया जाए। Aspose.HTML टेम्प्लेट्स के साथ काम करने और विभिन्न डेटा स्रोत प्रकारों, जैसे XML और JSON, के लिए इनलाइन एक्सप्रेशन सिंटैक्स प्रदान करता है। अधिक जानकारी के लिए [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) देखें जहाँ आप टेम्प्लेट मर्जिंग और ConvertTemplate() मेथड के उपयोग के बारे में अधिक जानकारी पा सकते हैं।

रूपांतरण (मर्जिंग) चरण

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

टेम्प्लेट स्रोत। फ़ाइल, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ऑब्जेक्ट इंस्टेंस या यहाँ तक कि इनलाइन कंटेंट द्वारा HTML टेम्प्लेट स्रोत को परिभाषित करें। रूपांतरण परिणाम। आप सीधे परिणामी HTMLDocument प्राप्त कर सकते हैं या मेथड सिग्नेचर के आधार पर परिणाम आउटपुट फ़ाइल पथ को परिभाषित कर सकते हैं। [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) का इंस्टेंस बनाएं। टेम्प्लेट को डेटा के साथ मर्ज करने के लिए Converter क्लास की ConvertTemplate() मेथड का उपयोग करें। आप वैकल्पिक पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
	  // फ़ॉर्म इनलाइन स्रोत कंटेंट को टेम्प्लेट के रूप में
      String templateContent =
        "<html>" + 
        "<body>" +
        "<div data_merge=\"{{#foreach Person}}\">" +
        "<p>{{Title}}</p>" +
        "<p>Name: {{Name}} Surname: {{Surname}}</p>" +
        "<p>Address:</p>" +
        "<p>{{Address.Number}}, {{Address.Street}} {{Address.City}}</p>" +
        "</div>" +
        "</body></html>";
       
      // फ़ॉर्म XML (JSON) टेम्प्लेट डेटा फ़ाइल पथ
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // TemplateData ऑब्जेक्ट इंस्टेंस को परिभाषित करें
      var templateData = new TemplateData(templateDataPath);

      // फ़ॉर्म आउटपुट को मर्जिंग परिणाम के रूप में 
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // डिफ़ॉल्ट TemplateLoadOptions ऑब्जेक्ट को परिभाषित करें
      var options = new TemplateLoadOptions();
	  
      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertTemplate(templateContent, String.Empty, templateData, options, resultFilePath);

*TemplateFolder - user template data folder.
*OutputFolder - user output file path.

Below is sample data file to merge with source

<?xml version="1.0" encoding="utf-8" ?>
<Data>
	<Person>
	<Title>Title 1</Title>
	<Name>John</Name>
	<Surname>Smith</Surname>
	<Address>
		<Number>200</Number>
		<Street>Austin rd.</Street>
		<City>Dallas</City>
	</Address>
	</Person>
	<Person>
	<Title>Title 2</Title>
	<Name>Mike</Name>
	<Surname>Milbert</Surname>
	<Address>
		<Number>126</Number>
		<Street>First Avenue</Street>
		<City>Chicago</City>
	</Address>
	</Person>
</Data>
```

### संबंधित देखें

* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_12}

इनलाइन सामग्री द्वारा प्रस्तुत टेम्प्लेट HTML स्रोत को टेम्प्लेट डेटा (XML, JSON) के साथ मिलाएँ। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित html फ़ाइल है।

```java
public static void ConvertTemplate(String content, String baseUrl, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options, String outputPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| सामग्री | String | इनलाइन स्ट्रिंग कंटेंट द्वारा प्रस्तुत HTML स्रोत कंकाल को मर्ज किया जा रहा है। |
| baseUrl | String | HTML टेम्प्लेट का बेस URI। यह वर्तमान डायरेक्टरी पथ के साथ मिलकर एक पूर्ण URL बनाएगा। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट को दर्शाता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| डेटा | TemplateData | मर्जिंग के लिए टेम्प्लेट डेटा - प्रतिस्थापन (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) ऑब्जेक्ट इंस्टेंस। यह निर्धारित करने के लिए उपयोग किया जाता है कि टेम्प्लेट और डेटा आइटम नाम केस की परवाह किए बिना मेल खाते हैं या नहीं (विकल्प)। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण HTML फ़ाइल पथ। |

## टिप्पणियाँ

टेम्प्लेट मर्जर

टेम्प्लेट मर्जिंग का विचार यह है कि एक HTML दस्तावेज़ को HTML टेम्प्लेट के आधार पर बनाया जाए और इसे डेटा स्रोत से भर दिया जाए। Aspose.HTML टेम्प्लेट्स के साथ काम करने और विभिन्न डेटा स्रोत प्रकारों, जैसे XML और JSON, के लिए इनलाइन एक्सप्रेशन सिंटैक्स प्रदान करता है। अधिक जानकारी के लिए [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) देखें जहाँ आप टेम्प्लेट मर्जिंग और ConvertTemplate() मेथड के उपयोग के बारे में अधिक जानकारी पा सकते हैं।

रूपांतरण (मर्जिंग) चरण

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

टेम्प्लेट स्रोत। फ़ाइल, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ऑब्जेक्ट इंस्टेंस या यहाँ तक कि इनलाइन कंटेंट द्वारा HTML टेम्प्लेट स्रोत को परिभाषित करें। रूपांतरण परिणाम। आप सीधे परिणामी HTMLDocument प्राप्त कर सकते हैं या मेथड सिग्नेचर के आधार पर परिणाम आउटपुट फ़ाइल पथ को परिभाषित कर सकते हैं। [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) का इंस्टेंस बनाएं। टेम्प्लेट को डेटा के साथ मर्ज करने के लिए Converter क्लास की ConvertTemplate() मेथड का उपयोग करें। आप वैकल्पिक पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
   // फ़ॉर्म इनलाइन स्रोत कंटेंट को टेम्प्लेट के रूप में
   String templateContent =
    "<html>" + 
    "<body>" +
    "<div data_merge=\"{{#foreach Person}}\">" +
    "<p>{{Title}}</p>" +
    "<p>Name: {{Name}} Surname: {{Surname}}</p>" +
    "<p>Address:</p>" +
    "<p>{{Address.Number}}, {{Address.Street}} {{Address.City}}</p>" +
    "</div>" +
    "</body></html>";
    
   // फ़ॉर्म XML (JSON) टेम्प्लेट डेटा फ़ाइल पथ
   var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

   // TemplateData ऑब्जेक्ट इंस्टेंस को परिभाषित करें
   var templateData = new TemplateData(templateDataPath);

   // फ़ॉर्म आउटपुट को मर्जिंग परिणाम के रूप में 
   var resultFilePath = Path.Combine(OutputFolder, "result.html");

   // configuration ऑब्जेक्ट इंस्टेंस को परिभाषित करें
   var configuration = new Configuration();

   // डिफ़ॉल्ट TemplateLoadOptions ऑब्जेक्ट को परिभाषित करें
   var options = new TemplateLoadOptions();

   // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
   Converter.ConvertTemplate(templateContent, String.Empty,
        configuration, templateData, options, resultFilePath);
```

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

नीचे स्रोत को टेम्पलेट के रूप में मिलाने के लिए डेटा फ़ाइल है

```java
<?xml version="1.0" encoding="utf-8" ?>
<Data>
	<Person>
	<Title>Title 1</Title>
	<Name>John</Name>
	<Surname>Smith</Surname>
	<Address>
		<Number>200</Number>
		<Street>Austin rd.</Street>
		<City>Dallas</City>
	</Address>
	</Person>
	<Person>
	<Title>Title 2</Title>
	<Name>Mike</Name>
	<Surname>Milbert</Surname>
	<Address>
		<Number>126</Number>
		<Street>First Avenue</Street>
		<City>Chicago</City>
	</Address>
	</Person>
</Data>
```

### संबंधित देखें

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(HTMLDocument, TemplateData, TemplateLoadOptions) {#converttemplate}

टेम्पलेट डेटा (XML, JSON) के साथ प्रस्तुत किए गए [`HTMLDocument`](../../../com.aspose.html/htmldocument/) स्रोत को मिलाएँ। परिणाम एक नया निर्मित HTMLDocument है जिसे फ़ाइल के रूप में सहेजा जा सकता है।

```java
public static HTMLDocument ConvertTemplate(HTMLDocument template, TemplateData data, 
    TemplateLoadOptions options)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| template | HTMLDocument | [`HTMLDocument`](../../../com.aspose.html/htmldocument/) द्वारा प्रस्तुत स्रोत स्केलेटन को मिलाना। |
| डेटा | TemplateData | मर्जिंग के लिए टेम्प्लेट डेटा - प्रतिस्थापन (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) ऑब्जेक्ट इंस्टेंस। यह निर्धारित करने के लिए उपयोग किया जाता है कि टेम्प्लेट और डेटा आइटम नाम केस की परवाह किए बिना मेल खाते हैं या नहीं (विकल्प)। |

### रिटर्न वैल्यू

नया निर्मित [`HTMLDocument`](../../../com.aspose.html/htmldocument/) रूपांतरण परिणाम के रूप में जिसे आउटपुट फ़ाइल पथ के माध्यम से सहेजा जा सकता है।

## टिप्पणियाँ

टेम्प्लेट मर्जर

टेम्प्लेट मर्जिंग का विचार यह है कि एक HTML दस्तावेज़ को HTML टेम्प्लेट के आधार पर बनाया जाए और इसे डेटा स्रोत से भर दिया जाए। Aspose.HTML टेम्प्लेट्स के साथ काम करने और विभिन्न डेटा स्रोत प्रकारों, जैसे XML और JSON, के लिए इनलाइन एक्सप्रेशन सिंटैक्स प्रदान करता है। अधिक जानकारी के लिए [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) देखें जहाँ आप टेम्प्लेट मर्जिंग और ConvertTemplate() मेथड के उपयोग के बारे में अधिक जानकारी पा सकते हैं।

रूपांतरण (मर्जिंग) चरण

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

टेम्प्लेट स्रोत। फ़ाइल, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ऑब्जेक्ट इंस्टेंस या यहाँ तक कि इनलाइन कंटेंट द्वारा HTML टेम्प्लेट स्रोत को परिभाषित करें। रूपांतरण परिणाम। आप सीधे परिणामी HTMLDocument प्राप्त कर सकते हैं या मेथड सिग्नेचर के आधार पर परिणाम आउटपुट फ़ाइल पथ को परिभाषित कर सकते हैं। [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) का इंस्टेंस बनाएं। टेम्प्लेट को डेटा के साथ मर्ज करने के लिए Converter क्लास की ConvertTemplate() मेथड का उपयोग करें। आप वैकल्पिक पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // फ़ॉर्म कंकाल HTML स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // फ़ॉर्म XML (JSON) टेम्प्लेट डेटा फ़ाइल पथ
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // TemplateData ऑब्जेक्ट इंस्टेंस को परिभाषित करें
      var templateData = new TemplateData(templateDataPath);

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // डिफ़ॉल्ट TemplateLoadOptions ऑब्जेक्ट को परिभाषित करें
      var options = new TemplateLoadOptions();
      
      // फ़ॉर्म HTML दस्तावेज़ को रूपांतरण स्रोत के रूप में
      using (var template = new HTMLDocument(sourcePath, new Configuration()))
      {
        // रूपांतरण प्रक्रिया शुरू करें
        var document = Converter.ConvertTemplate(template, templateData, options);
         
        // परिणाम को लिंक्ड संसाधनों के साथ सहेजें
        document.Save(new Url(resultPath));
      }





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### संबंधित देखें

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, TemplateData, TemplateLoadOptions) {#converttemplate_2}

टेम्पलेट डेटा (XML, JSON) के साथ प्रस्तुत किए गए [`URL`](../../../com.aspose.html/url/) HTML स्रोत को मिलाएँ। परिणाम एक नया निर्मित [`HTMLDocument`](../../../com.aspose.html/htmldocument/) है जिसे फ़ाइल के रूप में सहेजा जा सकता है।

```java
public static HTMLDocument ConvertTemplate(Url url, TemplateData data, TemplateLoadOptions options)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| url | Url | [`URL`](../../../com.aspose.html/url/) द्वारा प्रस्तुत HTML स्रोत कंकाल को मर्ज किया जा रहा है। |
| डेटा | TemplateData | मर्जिंग के लिए टेम्प्लेट डेटा - प्रतिस्थापन (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) ऑब्जेक्ट इंस्टेंस। यह निर्धारित करने के लिए उपयोग किया जाता है कि टेम्प्लेट और डेटा आइटम नाम केस की परवाह किए बिना मेल खाते हैं या नहीं (विकल्प)। |

### रिटर्न वैल्यू

नया निर्मित [`HTMLDocument`](../../../com.aspose.html/htmldocument/) रूपांतरण परिणाम के रूप में जिसे आउटपुट फ़ाइल पथ के माध्यम से सहेजा जा सकता है।

## टिप्पणियाँ

टेम्प्लेट मर्जर

टेम्प्लेट मर्जिंग का विचार यह है कि एक HTML दस्तावेज़ को HTML टेम्प्लेट के आधार पर बनाया जाए और इसे डेटा स्रोत से भर दिया जाए। Aspose.HTML टेम्प्लेट्स के साथ काम करने और विभिन्न डेटा स्रोत प्रकारों, जैसे XML और JSON, के लिए इनलाइन एक्सप्रेशन सिंटैक्स प्रदान करता है। अधिक जानकारी के लिए [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) देखें जहाँ आप टेम्प्लेट मर्जिंग और ConvertTemplate() मेथड के उपयोग के बारे में अधिक जानकारी पा सकते हैं।

रूपांतरण (मर्जिंग) चरण

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

टेम्प्लेट स्रोत। फ़ाइल, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ऑब्जेक्ट इंस्टेंस या यहाँ तक कि इनलाइन कंटेंट द्वारा HTML टेम्प्लेट स्रोत को परिभाषित करें। रूपांतरण परिणाम। आप सीधे परिणामी HTMLDocument प्राप्त कर सकते हैं या मेथड सिग्नेचर के आधार पर परिणाम आउटपुट फ़ाइल पथ को परिभाषित कर सकते हैं। [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) का इंस्टेंस बनाएं। टेम्प्लेट को डेटा के साथ मर्ज करने के लिए Converter क्लास की ConvertTemplate() मेथड का उपयोग करें। आप वैकल्पिक पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // स्केलेटन HTML स्रोत फ़ाइल बनाने के लिए URL बनाएं
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // फ़ॉर्म XML (JSON) टेम्प्लेट डेटा फ़ाइल पथ
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // TemplateData ऑब्जेक्ट इंस्टेंस को परिभाषित करें
      var templateData = new TemplateData(templateDataPath);

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // डिफ़ॉल्ट TemplateLoadOptions ऑब्जेक्ट को परिभाषित करें
      var options = new TemplateLoadOptions();

      // रूपांतरण प्रक्रिया शुरू करें
      using (var document = Converter.ConvertTemplate(sourceUrl, templateData, options))
      {
        // परिणाम को लिंक्ड संसाधनों के साथ सहेजें
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### संबंधित देखें

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Url](../../../com.aspose.html/url/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_1}

टेम्पलेट डेटा (XML, JSON) के साथ प्रस्तुत किए गए [`URL`](../../../com.aspose.html/url/) HTML स्रोत को मिलाएँ। परिणाम एक नया निर्मित [`HTMLDocument`](../../../com.aspose.html/htmldocument/) है जिसे फ़ाइल के रूप में सहेजा जा सकता है।

```java
public static HTMLDocument ConvertTemplate(Url url, Configuration configuration, TemplateData data, 
    TemplateLoadOptions options)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| url | Url | [`URL`](../../../com.aspose.html/url/) द्वारा प्रस्तुत HTML स्रोत कंकाल को मर्ज किया जा रहा है। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट को दर्शाता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| डेटा | TemplateData | मर्जिंग के लिए टेम्प्लेट डेटा - प्रतिस्थापन (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) ऑब्जेक्ट इंस्टेंस। यह निर्धारित करने के लिए उपयोग किया जाता है कि टेम्प्लेट और डेटा आइटम नाम केस की परवाह किए बिना मेल खाते हैं या नहीं (विकल्प)। |

### रिटर्न वैल्यू

नया निर्मित [`HTMLDocument`](../../../com.aspose.html/htmldocument/) रूपांतरण परिणाम के रूप में जिसे आउटपुट फ़ाइल पथ के माध्यम से सहेजा जा सकता है।

## टिप्पणियाँ

टेम्प्लेट मर्जर

टेम्प्लेट मर्जिंग का विचार यह है कि एक HTML दस्तावेज़ को HTML टेम्प्लेट के आधार पर बनाया जाए और इसे डेटा स्रोत से भर दिया जाए। Aspose.HTML टेम्प्लेट्स के साथ काम करने और विभिन्न डेटा स्रोत प्रकारों, जैसे XML और JSON, के लिए इनलाइन एक्सप्रेशन सिंटैक्स प्रदान करता है। अधिक जानकारी के लिए [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) देखें जहाँ आप टेम्प्लेट मर्जिंग और ConvertTemplate() मेथड के उपयोग के बारे में अधिक जानकारी पा सकते हैं।

रूपांतरण (मर्जिंग) चरण

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

टेम्प्लेट स्रोत। फ़ाइल, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ऑब्जेक्ट इंस्टेंस या यहाँ तक कि इनलाइन कंटेंट द्वारा HTML टेम्प्लेट स्रोत को परिभाषित करें। रूपांतरण परिणाम। आप सीधे परिणामी HTMLDocument प्राप्त कर सकते हैं या मेथड सिग्नेचर के आधार पर परिणाम आउटपुट फ़ाइल पथ को परिभाषित कर सकते हैं। [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) का इंस्टेंस बनाएं। टेम्प्लेट को डेटा के साथ मर्ज करने के लिए Converter क्लास की ConvertTemplate() मेथड का उपयोग करें। आप वैकल्पिक पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // स्केलेटन HTML स्रोत फ़ाइल बनाने के लिए URL बनाएं
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // फ़ॉर्म XML (JSON) टेम्प्लेट डेटा फ़ाइल पथ
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // TemplateData ऑब्जेक्ट इंस्टेंस को परिभाषित करें
      var templateData = new TemplateData(templateDataPath);

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // डिफ़ॉल्ट TemplateLoadOptions ऑब्जेक्ट को परिभाषित करें
      var options = new TemplateLoadOptions();

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      using (var document = Converter.ConvertTemplate(sourceUrl, new Configuration(), templateData, options))
      {
        // परिणाम को लिंक्ड संसाधनों के साथ सहेजें
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### संबंधित देखें

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, TemplateData, TemplateLoadOptions) {#converttemplate_4}

टेम्पलेट डेटा (XML, JSON) के साथ पूर्ण फ़ाइल पथ द्वारा प्रस्तुत टेम्पलेट HTML स्रोत को मिलाएँ। परिणाम एक नया निर्मित [`HTMLDocument`](../../../com.aspose.html/htmldocument/) है जिसे फ़ाइल के रूप में सहेजा जा सकता है।

```java
public static HTMLDocument ConvertTemplate(String sourcePath, TemplateData data, 
    TemplateLoadOptions options)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| sourcePath | String | पूर्ण फ़ाइल पथ द्वारा प्रस्तुत HTML स्रोत कंकाल को मर्ज किया जा रहा है। |
| डेटा | TemplateData | मर्जिंग के लिए टेम्प्लेट डेटा - प्रतिस्थापन (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) ऑब्जेक्ट इंस्टेंस। यह निर्धारित करने के लिए उपयोग किया जाता है कि टेम्प्लेट और डेटा आइटम नाम केस की परवाह किए बिना मेल खाते हैं या नहीं (विकल्प)। |

### रिटर्न वैल्यू

नया निर्मित [`HTMLDocument`](../../../com.aspose.html/htmldocument/) रूपांतरण परिणाम के रूप में जिसे आउटपुट फ़ाइल पथ के माध्यम से सहेजा जा सकता है।

## टिप्पणियाँ

टेम्प्लेट मर्जर

टेम्प्लेट मर्जिंग का विचार यह है कि एक HTML दस्तावेज़ को HTML टेम्प्लेट के आधार पर बनाया जाए और इसे डेटा स्रोत से भर दिया जाए। Aspose.HTML टेम्प्लेट्स के साथ काम करने और विभिन्न डेटा स्रोत प्रकारों, जैसे XML और JSON, के लिए इनलाइन एक्सप्रेशन सिंटैक्स प्रदान करता है। अधिक जानकारी के लिए [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) देखें जहाँ आप टेम्प्लेट मर्जिंग और ConvertTemplate() मेथड के उपयोग के बारे में अधिक जानकारी पा सकते हैं।

रूपांतरण (मर्जिंग) चरण

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

टेम्प्लेट स्रोत। फ़ाइल, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ऑब्जेक्ट इंस्टेंस या यहाँ तक कि इनलाइन कंटेंट द्वारा HTML टेम्प्लेट स्रोत को परिभाषित करें। रूपांतरण परिणाम। आप सीधे परिणामी HTMLDocument प्राप्त कर सकते हैं या मेथड सिग्नेचर के आधार पर परिणाम आउटपुट फ़ाइल पथ को परिभाषित कर सकते हैं। [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) का इंस्टेंस बनाएं। टेम्प्लेट को डेटा के साथ मर्ज करने के लिए Converter क्लास की ConvertTemplate() मेथड का उपयोग करें। आप वैकल्पिक पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // फ़ॉर्म कंकाल HTML स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // फ़ॉर्म XML (JSON) टेम्प्लेट डेटा फ़ाइल पथ
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // TemplateData ऑब्जेक्ट इंस्टेंस को परिभाषित करें
      var templateData = new TemplateData(templateDataPath);

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // डिफ़ॉल्ट TemplateLoadOptions ऑब्जेक्ट को परिभाषित करें
      var options = new TemplateLoadOptions();

      // रूपांतरण प्रक्रिया शुरू करें
      using (var document = Converter.ConvertTemplate(sourcePath, templateData, options))
      {
        // परिणाम को लिंक्ड संसाधनों के साथ सहेजें
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### संबंधित देखें

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_3}

टेम्पलेट डेटा (XML, JSON) के साथ पूर्ण फ़ाइल पथ द्वारा प्रस्तुत टेम्पलेट HTML स्रोत को मिलाएँ। परिणाम एक नया निर्मित [`HTMLDocument`](../../../com.aspose.html/htmldocument/) है जिसे फ़ाइल के रूप में सहेजा जा सकता है।

```java
public static HTMLDocument ConvertTemplate(String sourcePath, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| sourcePath | String | पूर्ण फ़ाइल पथ द्वारा प्रस्तुत HTML स्रोत कंकाल को मर्ज किया जा रहा है। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट को दर्शाता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| डेटा | TemplateData | मर्जिंग के लिए टेम्प्लेट डेटा - प्रतिस्थापन (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) ऑब्जेक्ट इंस्टेंस। यह निर्धारित करने के लिए उपयोग किया जाता है कि टेम्प्लेट और डेटा आइटम नाम केस की परवाह किए बिना मेल खाते हैं या नहीं (विकल्प)। |

### रिटर्न वैल्यू

नया निर्मित [`HTMLDocument`](../../../com.aspose.html/htmldocument/) रूपांतरण परिणाम के रूप में जिसे आउटपुट फ़ाइल पथ के माध्यम से सहेजा जा सकता है।

## टिप्पणियाँ

टेम्प्लेट मर्जर

टेम्प्लेट मर्जिंग का विचार यह है कि एक HTML दस्तावेज़ को HTML टेम्प्लेट के आधार पर बनाया जाए और इसे डेटा स्रोत से भर दिया जाए। Aspose.HTML टेम्प्लेट्स के साथ काम करने और विभिन्न डेटा स्रोत प्रकारों, जैसे XML और JSON, के लिए इनलाइन एक्सप्रेशन सिंटैक्स प्रदान करता है। अधिक जानकारी के लिए [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) देखें जहाँ आप टेम्प्लेट मर्जिंग और ConvertTemplate() मेथड के उपयोग के बारे में अधिक जानकारी पा सकते हैं।

रूपांतरण (मर्जिंग) चरण

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

टेम्प्लेट स्रोत। फ़ाइल, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ऑब्जेक्ट इंस्टेंस या यहाँ तक कि इनलाइन कंटेंट द्वारा HTML टेम्प्लेट स्रोत को परिभाषित करें। रूपांतरण परिणाम। आप सीधे परिणामी HTMLDocument प्राप्त कर सकते हैं या मेथड सिग्नेचर के आधार पर परिणाम आउटपुट फ़ाइल पथ को परिभाषित कर सकते हैं। [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) का इंस्टेंस बनाएं। टेम्प्लेट को डेटा के साथ मर्ज करने के लिए Converter क्लास की ConvertTemplate() मेथड का उपयोग करें। आप वैकल्पिक पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // फ़ॉर्म कंकाल HTML स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // फ़ॉर्म XML (JSON) टेम्प्लेट डेटा फ़ाइल पथ
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // TemplateData ऑब्जेक्ट इंस्टेंस को परिभाषित करें
      var templateData = new TemplateData(templateDataPath);

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // डिफ़ॉल्ट TemplateLoadOptions ऑब्जेक्ट को परिभाषित करें
      var options = new TemplateLoadOptions();

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      using (var document = Converter.ConvertTemplate(sourcePath, new Configuration(), templateData, options))
      {
        // परिणाम को लिंक्ड संसाधनों के साथ सहेजें
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### संबंधित देखें

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, TemplateData, TemplateLoadOptions) {#converttemplate_6}

टेम्पलेट डेटा (XML, JSON) के साथ इनलाइन सामग्री द्वारा प्रस्तुत टेम्पलेट HTML स्रोत को मिलाएँ। परिणाम एक नया निर्मित [`HTMLDocument`](../../../com.aspose.html/htmldocument/) है जिसे फ़ाइल के रूप में सहेजा जा सकता है।

```java
public static HTMLDocument ConvertTemplate(String content, String baseUrl, TemplateData data, 
    TemplateLoadOptions options)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| सामग्री | String | इनलाइन स्ट्रिंग कंटेंट द्वारा प्रस्तुत HTML स्रोत कंकाल को मर्ज किया जा रहा है। |
| baseUrl | String | HTML टेम्प्लेट का बेस URI। यह वर्तमान डायरेक्टरी पथ के साथ मिलकर एक पूर्ण URL बनाएगा। |
| डेटा | TemplateData | मर्जिंग के लिए टेम्प्लेट डेटा - प्रतिस्थापन (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) ऑब्जेक्ट इंस्टेंस। यह निर्धारित करने के लिए उपयोग किया जाता है कि टेम्प्लेट और डेटा आइटम नाम केस की परवाह किए बिना मेल खाते हैं या नहीं (विकल्प)। |

### रिटर्न वैल्यू

नया निर्मित [`HTMLDocument`](../../../com.aspose.html/htmldocument/) रूपांतरण परिणाम के रूप में जिसे आउटपुट फ़ाइल पथ के माध्यम से सहेजा जा सकता है।

## टिप्पणियाँ

टेम्प्लेट मर्जर

टेम्प्लेट मर्जिंग का विचार यह है कि एक HTML दस्तावेज़ को HTML टेम्प्लेट के आधार पर बनाया जाए और इसे डेटा स्रोत से भर दिया जाए। Aspose.HTML टेम्प्लेट्स के साथ काम करने और विभिन्न डेटा स्रोत प्रकारों, जैसे XML और JSON, के लिए इनलाइन एक्सप्रेशन सिंटैक्स प्रदान करता है। अधिक जानकारी के लिए [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) देखें जहाँ आप टेम्प्लेट मर्जिंग और ConvertTemplate() मेथड के उपयोग के बारे में अधिक जानकारी पा सकते हैं।

रूपांतरण (मर्जिंग) चरण

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

टेम्प्लेट स्रोत। फ़ाइल, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ऑब्जेक्ट इंस्टेंस या यहाँ तक कि इनलाइन कंटेंट द्वारा HTML टेम्प्लेट स्रोत को परिभाषित करें। रूपांतरण परिणाम। आप सीधे परिणामी HTMLDocument प्राप्त कर सकते हैं या मेथड सिग्नेचर के आधार पर परिणाम आउटपुट फ़ाइल पथ को परिभाषित कर सकते हैं। [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) का इंस्टेंस बनाएं। टेम्प्लेट को डेटा के साथ मर्ज करने के लिए Converter क्लास की ConvertTemplate() मेथड का उपयोग करें। आप वैकल्पिक पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // फ़ॉर्म इनलाइन स्रोत कंटेंट को टेम्प्लेट के रूप में
      String templateContent =
        "<html>" +
        "<body>" +
        "<div data_merge=\"{{#foreach Person}}\">" +
        "<p>{{Title}}</p>" +
        "<p>Name: {{Name}} Surname: {{Surname}}</p>" +
        "<p>Address:</p>" +
        "<p>{{Address.Number}}, {{Address.Street}} {{Address.City}}</p>" +
        "</div>" +
        "</body></html>";

      // फ़ॉर्म XML (JSON) टेम्प्लेट डेटा फ़ाइल पथ
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // TemplateData ऑब्जेक्ट इंस्टेंस को परिभाषित करें
      var templateData = new TemplateData(templateDataPath);

      // फ़ॉर्म आउटपुट को मर्जिंग परिणाम के रूप में 
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // डिफ़ॉल्ट TemplateLoadOptions ऑब्जेक्ट को परिभाषित करें
      var options = new TemplateLoadOptions();

      // रूपांतरण प्रक्रिया शुरू करें और परिणाम सहेजें
      using (var document = Converter.ConvertTemplate(
        templateContent, String.Empty,
        templateData,
        options))
      {
        document.Save(new Url(resultFilePath));
      }
```

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### संबंधित देखें

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_5}

टेम्पलेट डेटा (XML, JSON) के साथ इनलाइन सामग्री द्वारा प्रस्तुत टेम्पलेट HTML स्रोत को मिलाएँ। परिणाम एक नया निर्मित [`HTMLDocument`](../../../com.aspose.html/htmldocument/) है जिसे फ़ाइल के रूप में सहेजा जा सकता है।

```java
public static HTMLDocument ConvertTemplate(String content, String baseUrl, 
    Configuration configuration, TemplateData data, TemplateLoadOptions options)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| सामग्री | String | इनलाइन स्ट्रिंग कंटेंट द्वारा प्रस्तुत HTML स्रोत कंकाल को मर्ज किया जा रहा है। |
| baseUrl | String | HTML टेम्प्लेट का बेस URI। यह वर्तमान डायरेक्टरी पथ के साथ मिलकर एक पूर्ण URL बनाएगा। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट को दर्शाता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| डेटा | TemplateData | मर्जिंग के लिए टेम्प्लेट डेटा - प्रतिस्थापन (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) ऑब्जेक्ट इंस्टेंस। यह निर्धारित करने के लिए उपयोग किया जाता है कि टेम्प्लेट और डेटा आइटम नाम केस की परवाह किए बिना मेल खाते हैं या नहीं (विकल्प)। |

### रिटर्न वैल्यू

नया निर्मित [`HTMLDocument`](../../../com.aspose.html/htmldocument/) रूपांतरण परिणाम के रूप में जिसे आउटपुट फ़ाइल पथ के माध्यम से सहेजा जा सकता है।

## टिप्पणियाँ

टेम्प्लेट मर्जर

टेम्प्लेट मर्जिंग का विचार यह है कि एक HTML दस्तावेज़ को HTML टेम्प्लेट के आधार पर बनाया जाए और इसे डेटा स्रोत से भर दिया जाए। Aspose.HTML टेम्प्लेट्स के साथ काम करने और विभिन्न डेटा स्रोत प्रकारों, जैसे XML और JSON, के लिए इनलाइन एक्सप्रेशन सिंटैक्स प्रदान करता है। अधिक जानकारी के लिए [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) देखें जहाँ आप टेम्प्लेट मर्जिंग और ConvertTemplate() मेथड के उपयोग के बारे में अधिक जानकारी पा सकते हैं।

रूपांतरण (मर्जिंग) चरण

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

टेम्प्लेट स्रोत। फ़ाइल, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ऑब्जेक्ट इंस्टेंस या यहाँ तक कि इनलाइन कंटेंट द्वारा HTML टेम्प्लेट स्रोत को परिभाषित करें। रूपांतरण परिणाम। आप सीधे परिणामी HTMLDocument प्राप्त कर सकते हैं या मेथड सिग्नेचर के आधार पर परिणाम आउटपुट फ़ाइल पथ को परिभाषित कर सकते हैं। [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) का इंस्टेंस बनाएं। टेम्प्लेट को डेटा के साथ मर्ज करने के लिए Converter क्लास की ConvertTemplate() मेथड का उपयोग करें। आप वैकल्पिक पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // फ़ॉर्म इनलाइन स्रोत कंटेंट को टेम्प्लेट के रूप में
      String templateContent =
        "<html>" + 
        "<body>" +
        "<div data_merge=\"{{#foreach Person}}\">" +
        "<p>{{Title}}</p>" +
        "<p>Name: {{Name}} Surname: {{Surname}}</p>" +
        "<p>Address:</p>" +
        "<p>{{Address.Number}}, {{Address.Street}} {{Address.City}}</p>" +
        "</div>" +
        "</body></html>";
       
      // फ़ॉर्म XML (JSON) टेम्प्लेट डेटा फ़ाइल पथ
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // TemplateData ऑब्जेक्ट इंस्टेंस को परिभाषित करें
      var templateData = new TemplateData(templateDataPath);

      // फ़ॉर्म आउटपुट को मर्जिंग परिणाम के रूप में 
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // configuration ऑब्जेक्ट इंस्टेंस को परिभाषित करें
      var configuration = new Configuration();

      // डिफ़ॉल्ट TemplateLoadOptions ऑब्जेक्ट को परिभाषित करें
      var options = new TemplateLoadOptions();

      // रूपांतरण प्रक्रिया शुरू करें और परिणाम सहेजें
      using (var document = Converter.ConvertTemplate(
        templateContent, String.Empty,
        configuration,
        templateData,
        options))
      {
        document.Save(new Url(resultFilePath));
      }
```

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### संबंधित देखें

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

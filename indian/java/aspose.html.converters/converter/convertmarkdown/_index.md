---
title: "Converter.ConvertMarkdown"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "Converter मेथड। इनपुट स्ट्रीम द्वारा प्रस्तुत MD मार्कडाउन स्रोत को HTML में परिवर्तित करें। परिणाम HTMLDocument है जिसे आउटपुट फ़ाइल पथ के माध्यम से सहेजा जा सकता है।"
type: docs

url: /hi/java/com.aspose.html.converters/converter/convertmarkdown/
---
## ConvertMarkdown(Stream, String) {#convertmarkdown}

इनपुट स्ट्रीम द्वारा प्रस्तुत MD (मार्कडाउन) स्रोत को HTML में परिवर्तित करें। परिणाम [`HTMLDocument`](../../../com.aspose.html/htmldocument/) है जिसे आउटपुट फ़ाइल पथ के माध्यम से सहेजा जा सकता है।

```java
public static HTMLDocument ConvertMarkdown(Stream stream, String baseUri)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | MD (मार्कडाउन) रूपांतरण इनपुट डेटा स्ट्रीम। |
| baseUri | String | दस्तावेज़ का बेस URI। इसे वर्तमान निर्देशिका पथ के साथ मिलाकर एक पूर्ण URL बनाया जाएगा। |

### रिटर्न वैल्यू

नया निर्मित [`HTMLDocument`](../../../com.aspose.html/htmldocument/) रूपांतरण परिणाम के रूप में जिसे आउटपुट फ़ाइल पथ के माध्यम से सहेजा जा सकता है।

## टिप्पणियाँ

मार्कडाउन कनवर्टर

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

रूपांतरण चरण

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

रूपांतरण स्रोत। मौजूदा स्थानीय MD फ़ाइल का पता लगाएँ या इनपुट डेटा स्ट्रीम को रूपांतरण स्रोत के रूप में बनाएं। रूपांतरण परिणाम। आप सीधे [`HTMLDocument`](../../../com.aspose.html/htmldocument/) प्राप्त कर सकते हैं या मेथड सिग्नेचर के आधार पर परिणाम आउटपुट फ़ाइल पथ निर्धारित कर सकते हैं। Converter क्लास की ConvertMarkdown() मेथड का उपयोग करके MD को HTML परिणाम के रूप में सहेजें। आप वैकल्पिक पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। ऑनलाइन MD कनवर्टर

आप भी एक मुफ्त ऑनलाइन [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) में रुचि ले सकते हैं जो उच्च गुणवत्ता, आसान और तेज़ी से MD को HTML में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें! आप अन्य ऑनलाइन MD कनवर्टर्स भी देख सकते हैं: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) और उपयुक्त [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/) खोजें।

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.html");
       
      // स्रोत फ़ाइल को स्ट्रीम के रूप में खोलें
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // रूपांतरण प्रक्रिया शुरू करें
        var document = Converter.ConvertMarkdown(sourceStream, String.Empty);
         
        // रूपांतरण परिणाम सहेजें
        document.Save(resultPath);
      }





*InputFolder - user source folder path.



```

*OutputFolder - user output file path.

### संबंधित देखें

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, Configuration) {#convertmarkdown_1}

इनपुट स्ट्रीम द्वारा प्रस्तुत MD (मार्कडाउन) स्रोत को HTML में परिवर्तित करें। परिणाम [`HTMLDocument`](../../../com.aspose.html/htmldocument/) है जिसे आउटपुट फ़ाइल पथ के माध्यम से सहेजा जा सकता है।

```java
public static HTMLDocument ConvertMarkdown(Stream stream, String baseUri, 
    Configuration configuration)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | MD (मार्कडाउन) रूपांतरण इनपुट डेटा स्ट्रीम। |
| baseUri | String | दस्तावेज़ का बेस URI। इसे वर्तमान निर्देशिका पथ के साथ मिलाकर एक पूर्ण URL बनाया जाएगा। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट को दर्शाता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |

### रिटर्न वैल्यू

नया निर्मित [`HTMLDocument`](../../../com.aspose.html/htmldocument/) रूपांतरण परिणाम के रूप में जिसे आउटपुट फ़ाइल पथ के माध्यम से सहेजा जा सकता है।

## टिप्पणियाँ

मार्कडाउन कनवर्टर

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

रूपांतरण चरण

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

रूपांतरण स्रोत। मौजूदा स्थानीय MD फ़ाइल का पता लगाएँ या इनपुट डेटा स्ट्रीम को रूपांतरण स्रोत के रूप में बनाएं। रूपांतरण परिणाम। आप सीधे [`HTMLDocument`](../../../com.aspose.html/htmldocument/) प्राप्त कर सकते हैं या मेथड सिग्नेचर के आधार पर परिणाम आउटपुट फ़ाइल पथ निर्धारित कर सकते हैं। Converter क्लास की ConvertMarkdown() मेथड का उपयोग करके MD को HTML परिणाम के रूप में सहेजें। आप वैकल्पिक पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। ऑनलाइन MD कनवर्टर

आप भी एक मुफ्त ऑनलाइन [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) में रुचि ले सकते हैं जो उच्च गुणवत्ता, आसान और तेज़ी से MD को HTML में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें! आप अन्य ऑनलाइन MD कनवर्टर्स भी देख सकते हैं: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) और उपयुक्त [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/) खोजें।

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // स्रोत फ़ाइल को स्ट्रीम के रूप में खोलें
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
        var document = Converter.ConvertMarkdown(sourceStream, String.Empty, new Configuration());

        // रूपांतरण परिणाम सहेजें
        document.Save(resultPath);
      }





*InputFolder - user source folder path.

```

*OutputFolder - user output file path.

### संबंधित देखें

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, String) {#convertmarkdown_5}

इनपुट स्ट्रीम द्वारा प्रस्तुत MD (markdown) स्रोत को html में परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित html फ़ाइल है।

```java
public static void ConvertMarkdown(Stream stream, String baseUri, String outputPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | MD (मार्कडाउन) रूपांतरण इनपुट डेटा स्ट्रीम। |
| baseUri | String | दस्तावेज़ का बेस URI। इसे वर्तमान निर्देशिका पथ के साथ मिलाकर एक पूर्ण URL बनाया जाएगा। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण HTML फ़ाइल पथ। |

## टिप्पणियाँ

मार्कडाउन कनवर्टर

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

रूपांतरण चरण

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

रूपांतरण स्रोत। मौजूदा स्थानीय MD फ़ाइल का पता लगाएँ या इनपुट डेटा स्ट्रीम को रूपांतरण स्रोत के रूप में बनाएं। रूपांतरण परिणाम। आप सीधे [`HTMLDocument`](../../../com.aspose.html/htmldocument/) प्राप्त कर सकते हैं या मेथड सिग्नेचर के आधार पर परिणाम आउटपुट फ़ाइल पथ निर्धारित कर सकते हैं। Converter क्लास की ConvertMarkdown() मेथड का उपयोग करके MD को HTML परिणाम के रूप में सहेजें। आप वैकल्पिक पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। ऑनलाइन MD कनवर्टर

आप भी एक मुफ्त ऑनलाइन [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) में रुचि ले सकते हैं जो उच्च गुणवत्ता, आसान और तेज़ी से MD को HTML में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें! आप अन्य ऑनलाइन MD कनवर्टर्स भी देख सकते हैं: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) और उपयुक्त [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/) खोजें।

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // स्रोत फ़ाइल को स्ट्रीम के रूप में खोलें
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // रूपांतरण प्रक्रिया शुरू करें
        Converter.ConvertMarkdown(sourceStream, String.Empty, resultPath);
      }





*InputFolder - user source folder path.

```

*OutputFolder - user output file path.

### संबंधित देखें

* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, Configuration, String) {#convertmarkdown_4}

इनपुट स्ट्रीम द्वारा प्रस्तुत MD (markdown) स्रोत को html में परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित html फ़ाइल है।

```java
public static void ConvertMarkdown(Stream stream, String baseUri, Configuration configuration, 
    String outputPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | MD (मार्कडाउन) रूपांतरण इनपुट डेटा स्ट्रीम। |
| baseUri | String | दस्तावेज़ का बेस URI। इसे वर्तमान निर्देशिका पथ के साथ मिलाकर एक पूर्ण URL बनाया जाएगा। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट को दर्शाता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण HTML फ़ाइल पथ। |

## टिप्पणियाँ

मार्कडाउन कनवर्टर

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

रूपांतरण चरण

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

रूपांतरण स्रोत। मौजूदा स्थानीय MD फ़ाइल का पता लगाएँ या इनपुट डेटा स्ट्रीम को रूपांतरण स्रोत के रूप में बनाएं। रूपांतरण परिणाम। आप सीधे [`HTMLDocument`](../../../com.aspose.html/htmldocument/) प्राप्त कर सकते हैं या मेथड सिग्नेचर के आधार पर परिणाम आउटपुट फ़ाइल पथ निर्धारित कर सकते हैं। Converter क्लास की ConvertMarkdown() मेथड का उपयोग करके MD को HTML परिणाम के रूप में सहेजें। आप वैकल्पिक पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। ऑनलाइन MD कनवर्टर

आप भी एक मुफ्त ऑनलाइन [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) में रुचि ले सकते हैं जो उच्च गुणवत्ता, आसान और तेज़ी से MD को HTML में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें! आप अन्य ऑनलाइन MD कनवर्टर्स भी देख सकते हैं: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) और उपयुक्त [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/) खोजें।

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // स्रोत फ़ाइल को स्ट्रीम के रूप में खोलें
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
        Converter.ConvertMarkdown(sourceStream, String.Empty, new Configuration(), resultPath);
      }
```

*InputFolder - user source folder path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String) {#convertmarkdown_2}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत MD (मार्कडाउन) स्रोत को HTML में परिवर्तित करें। परिणाम [`HTMLDocument`](../../../com.aspose.html/htmldocument/) है जिसे आउटपुट फ़ाइल पथ के माध्यम से सहेजा जा सकता है।

```java
public static HTMLDocument ConvertMarkdown(String sourcePath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| sourcePath | String | MD (मार्कडाउन) स्रोत पूर्ण फ़ाइल पथ। |

### रिटर्न वैल्यू

नया निर्मित [`HTMLDocument`](../../../com.aspose.html/htmldocument/) रूपांतरण परिणाम के रूप में जिसे आउटपुट फ़ाइल पथ के माध्यम से सहेजा जा सकता है।

## टिप्पणियाँ

मार्कडाउन कनवर्टर

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

रूपांतरण चरण

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

रूपांतरण स्रोत। मौजूदा स्थानीय MD फ़ाइल का पता लगाएँ या इनपुट डेटा स्ट्रीम को रूपांतरण स्रोत के रूप में बनाएं। रूपांतरण परिणाम। आप सीधे [`HTMLDocument`](../../../com.aspose.html/htmldocument/) प्राप्त कर सकते हैं या मेथड सिग्नेचर के आधार पर परिणाम आउटपुट फ़ाइल पथ निर्धारित कर सकते हैं। Converter क्लास की ConvertMarkdown() मेथड का उपयोग करके MD को HTML परिणाम के रूप में सहेजें। आप वैकल्पिक पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। ऑनलाइन MD कनवर्टर

आप भी एक मुफ्त ऑनलाइन [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) में रुचि ले सकते हैं जो उच्च गुणवत्ता, आसान और तेज़ी से MD को HTML में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें! आप अन्य ऑनलाइन MD कनवर्टर्स भी देख सकते हैं: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) और उपयुक्त [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/) खोजें।

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // रूपांतरण प्रक्रिया शुरू करें
      using (HTMLDocument document = Converter.ConvertMarkdown(sourcePath))
      {
        // रूपांतरण परिणाम को स्थानीय फ़ाइल के रूप में सहेजें
        document.Save(resultPath);
      }
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### संबंधित देखें

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, Configuration) {#convertmarkdown_3}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत MD (मार्कडाउन) स्रोत को HTML में परिवर्तित करें। परिणाम [`HTMLDocument`](../../../com.aspose.html/htmldocument/) है जिसे आउटपुट फ़ाइल पथ के माध्यम से सहेजा जा सकता है।

```java
public static HTMLDocument ConvertMarkdown(String sourcePath, Configuration configuration)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| sourcePath | String | MD (मार्कडाउन) स्रोत पूर्ण फ़ाइल पथ। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट को दर्शाता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |

### रिटर्न वैल्यू

नया निर्मित [`HTMLDocument`](../../../com.aspose.html/htmldocument/) रूपांतरण परिणाम के रूप में जिसे आउटपुट फ़ाइल पथ के माध्यम से सहेजा जा सकता है।

## टिप्पणियाँ

मार्कडाउन कनवर्टर

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

रूपांतरण चरण

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

रूपांतरण स्रोत। मौजूदा स्थानीय MD फ़ाइल का पता लगाएँ या इनपुट डेटा स्ट्रीम को रूपांतरण स्रोत के रूप में बनाएं। रूपांतरण परिणाम। आप सीधे [`HTMLDocument`](../../../com.aspose.html/htmldocument/) प्राप्त कर सकते हैं या मेथड सिग्नेचर के आधार पर परिणाम आउटपुट फ़ाइल पथ निर्धारित कर सकते हैं। Converter क्लास की ConvertMarkdown() मेथड का उपयोग करके MD को HTML परिणाम के रूप में सहेजें। आप वैकल्पिक पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। ऑनलाइन MD कनवर्टर

आप भी एक मुफ्त ऑनलाइन [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) में रुचि ले सकते हैं जो उच्च गुणवत्ता, आसान और तेज़ी से MD को HTML में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें! आप अन्य ऑनलाइन MD कनवर्टर्स भी देख सकते हैं: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) और उपयुक्त [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/) खोजें।

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      using (HTMLDocument document = Converter.ConvertMarkdown(sourcePath, new Configuration()))
      {
        // रूपांतरण परिणाम को स्थानीय फ़ाइल के रूप में सहेजें
        document.Save(resultPath);
      }
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### संबंधित देखें

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, String) {#convertmarkdown_7}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत MD (markdown) स्रोत को html में परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित html फ़ाइल है।

```java
public static void ConvertMarkdown(String sourcePath, String outputPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| sourcePath | String | स्रोत Markdown फ़ाइल का पथ। इसे वर्तमान डायरेक्टरी पथ के साथ मिलाकर एक पूर्ण URL बनाया जाएगा। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण HTML फ़ाइल पथ। |

## टिप्पणियाँ

मार्कडाउन कनवर्टर

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

रूपांतरण चरण

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

रूपांतरण स्रोत। मौजूदा स्थानीय MD फ़ाइल का पता लगाएँ या इनपुट डेटा स्ट्रीम को रूपांतरण स्रोत के रूप में बनाएं। रूपांतरण परिणाम। आप सीधे [`HTMLDocument`](../../../com.aspose.html/htmldocument/) प्राप्त कर सकते हैं या मेथड सिग्नेचर के आधार पर परिणाम आउटपुट फ़ाइल पथ निर्धारित कर सकते हैं। Converter क्लास की ConvertMarkdown() मेथड का उपयोग करके MD को HTML परिणाम के रूप में सहेजें। आप वैकल्पिक पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। ऑनलाइन MD कनवर्टर

आप भी एक मुफ्त ऑनलाइन [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) में रुचि ले सकते हैं जो उच्च गुणवत्ता, आसान और तेज़ी से MD को HTML में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें! आप अन्य ऑनलाइन MD कनवर्टर्स भी देख सकते हैं: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) और उपयुक्त [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/) खोजें।

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMarkdown(sourcePath, resultPath);
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### संबंधित देखें

* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, Configuration, String) {#convertmarkdown_6}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत MD (markdown) स्रोत को html में परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित html फ़ाइल है।

```java
public static void ConvertMarkdown(String sourcePath, Configuration configuration, 
    String outputPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| sourcePath | String | स्रोत Markdown फ़ाइल का पथ। इसे वर्तमान डायरेक्टरी पथ के साथ मिलाकर एक पूर्ण URL बनाया जाएगा। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट को दर्शाता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण HTML फ़ाइल पथ। |

## टिप्पणियाँ

मार्कडाउन कनवर्टर

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

रूपांतरण चरण

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

रूपांतरण स्रोत। मौजूदा स्थानीय MD फ़ाइल का पता लगाएँ या इनपुट डेटा स्ट्रीम को रूपांतरण स्रोत के रूप में बनाएं। रूपांतरण परिणाम। आप सीधे [`HTMLDocument`](../../../com.aspose.html/htmldocument/) प्राप्त कर सकते हैं या मेथड सिग्नेचर के आधार पर परिणाम आउटपुट फ़ाइल पथ निर्धारित कर सकते हैं। Converter क्लास की ConvertMarkdown() मेथड का उपयोग करके MD को HTML परिणाम के रूप में सहेजें। आप वैकल्पिक पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। ऑनलाइन MD कनवर्टर

आप भी एक मुफ्त ऑनलाइन [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) में रुचि ले सकते हैं जो उच्च गुणवत्ता, आसान और तेज़ी से MD को HTML में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें! आप अन्य ऑनलाइन MD कनवर्टर्स भी देख सकते हैं: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) और उपयुक्त [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/) खोजें।

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // फ़ॉर्म स्रोत फ़ाइल पथ
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertMarkdown(sourcePath, new Configuration(), resultPath);
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### संबंधित देखें

* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

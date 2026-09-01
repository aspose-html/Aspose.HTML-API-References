---
title: "Converter.ConvertEPUB"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "Converter मेथड। डेटा इनपुट स्ट्रीम द्वारा प्रस्तुत EPUB स्रोत को बदलें। परिणाम वह फ़ाइल है जो आउटपुट फ़ाइल पथ द्वारा निर्मित होती है।"
type: docs

url: /hi/java/com.aspose.html.converters/converter/convertepub/
---
## ConvertEPUB(Stream, ImageSaveOptions, String) {#convertepub_27}

डेटा इनपुट स्ट्रीम द्वारा प्रस्तुत EPUB स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित फ़ाइल है।

```java
public static void ConvertEPUB(Stream stream, ImageSaveOptions options, String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | इनपुट स्ट्रीम को रूपांतरण स्रोत के रूप में उपयोग करें। |
| options | ImageSaveOptions | नए निर्मित इमेज विकल्प जैसे फ़ॉर्मेट, रिज़ॉल्यूशन आदि। देखें [`ImageSaveOptions `] क्लास और [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/#save-options). |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण इमेज फ़ाइल पथ। |

## Remarks

EPUB को इमेज में कैसे बदलें

EPUB एक ई-बुक फ़ाइल फ़ॉर्मेट है जो एक मानक डिजिटल प्रकाशन फ़ॉर्मेट प्रदान करता है। इसे International Digital Publishing Forum (IDPF) ने बनाया था, और अब यह कई ई-रीडर और सॉफ़्टवेयर एप्लिकेशन द्वारा समर्थित है।

EPUB फ़ाइलों को PNG फ़ॉर्मेट में बदलना उपयोगी हो सकता है यदि आपको फ़ाइलों को PowerPoint प्रस्तुति में शामिल करना है या ईमेल द्वारा भेजना है। कृपया उन्हें इमेज फ़ॉर्मेट में बदलें और अपनी इच्छा अनुसार उपयोग करें! वांछित परिणाम प्राप्त करने के लिए आप अतिरिक्त रूपांतरण पैरामीटर का उपयोग कर सकते हैं।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें Converter क्लास का उपयोग करके कैसे निष्पादित करें, इस बारे में जानकारी प्रदान करता है, जो सभी लो‑लेवल रूपांतरण ऑपरेशन्स को एक ही क्लास में समूहित करता है ताकि वे आरामदायक और उपयोग में आसान हों। EPUB Converter गाइड में, आप निम्नलिखित लेख पाएंगे:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

EPUB को इमेज में बदलें

EPUB को इमेज फ़ाइल फ़ॉर्मेट में बदलने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

निर्दिष्ट पथ पर मौजूदा EPUB फ़ाइल के आधार पर URL निर्धारित करें। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें। आवश्यक ImageFormat के साथ एक नया [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट बनाएं। डिफ़ॉल्ट रूप से, Format प्रॉपर्टी PNG है। EPUB को इमेज के रूप में सहेजने के लिए Converter क्लास की ConvertEPUB() मेथड का उपयोग करें। आपको इमेज रूपांतरण के लिए ImageSaveOptions और Configuration ऑब्जेक्ट भी पास करने की आवश्यकता है। ऑनलाइन EPUB कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) कनवर्टर प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से EPUB को PNG इमेज में बदलता है। बस अपनी फ़ाइलें अपलोड करें, कनवर्ट करें और कुछ सेकंड में परिणाम प्राप्त करें!

आप विशेष इमेज फ़ॉर्मेट रूपांतरण में भी रुचि रख सकते हैं

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// स्ट्रीम के रूप में पढ़ने के लिए मौजूदा फ़ाइल खोलें
var inputStream = System.IO.File.OpenRead(Path.Combine(InputFolder, "sample.epub"));

// आउटपुट फ़ाइल पथ निर्धारित करें
var resultPath = Path.Combine(OutputFolder, "sample.png");

// डिफ़ॉल्ट विकल्प इंस्टेंस निर्धारित करें
var options = new ImageSaveOptions();

// रूपांतरण प्रक्रिया शुरू करें
Converter.ConvertEPUB(inputStream, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, ImageSaveOptions, String) {#convertepub_43}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत EPUB स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित इमेज फ़ाइल है। इमेज फ़ॉर्मेट ImageSaveOptions ऑब्जेक्ट द्वारा निर्दिष्ट किया गया है।

```java
public static void ConvertEPUB(String sourcePath, ImageSaveOptions options, String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourcePath | String | इनपुट पैरामीटर के रूप में EPUB स्रोत फ़ाइल पथ। |
| options | ImageSaveOptions | ImageSaveOptions ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), आदि निर्दिष्ट कर सकते हैं। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण इमेज फ़ाइल पथ। |

## Remarks

EPUB को इमेज में कैसे बदलें

EPUB एक ई-बुक फ़ाइल फ़ॉर्मेट है जो एक मानक डिजिटल प्रकाशन फ़ॉर्मेट प्रदान करता है। इसे International Digital Publishing Forum (IDPF) ने बनाया था, और अब यह कई ई-रीडर और सॉफ़्टवेयर एप्लिकेशन द्वारा समर्थित है।

EPUB फ़ाइलों को PNG फ़ॉर्मेट में बदलना उपयोगी हो सकता है यदि आपको फ़ाइलों को PowerPoint प्रस्तुति में शामिल करना है या ईमेल द्वारा भेजना है। कृपया उन्हें इमेज फ़ॉर्मेट में बदलें और अपनी इच्छा अनुसार उपयोग करें! वांछित परिणाम प्राप्त करने के लिए आप अतिरिक्त रूपांतरण पैरामीटर का उपयोग कर सकते हैं।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें Converter क्लास का उपयोग करके कैसे निष्पादित करें, इस बारे में जानकारी प्रदान करता है, जो सभी लो‑लेवल रूपांतरण ऑपरेशन्स को एक ही क्लास में समूहित करता है ताकि वे आरामदायक और उपयोग में आसान हों। EPUB Converter गाइड में, आप निम्नलिखित लेख पाएंगे:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

EPUB को इमेज में बदलें

EPUB को इमेज फ़ाइल फ़ॉर्मेट में बदलने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

निर्दिष्ट पथ पर मौजूदा EPUB फ़ाइल के आधार पर URL निर्धारित करें। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें। आवश्यक ImageFormat के साथ एक नया [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट बनाएं। डिफ़ॉल्ट रूप से, Format प्रॉपर्टी PNG है। EPUB को इमेज के रूप में सहेजने के लिए Converter क्लास की ConvertEPUB() मेथड का उपयोग करें। आपको इमेज रूपांतरण के लिए ImageSaveOptions और Configuration ऑब्जेक्ट भी पास करने की आवश्यकता है। ऑनलाइन EPUB कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) कनवर्टर प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से EPUB को PNG इमेज में बदलता है। बस अपनी फ़ाइलें अपलोड करें, कनवर्ट करें और कुछ सेकंड में परिणाम प्राप्त करें!

आप विशेष इमेज फ़ॉर्मेट रूपांतरण में भी रुचि रख सकते हैं

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// फ़ॉर्म स्रोत फ़ाइल पथ
var sourcePath = Path.Combine(InputFolder, "sample.epub"); 

// आउटपुट परिणाम फ़ाइल पथ बनाएं
var resultPath = Path.Combine(OutputFolder, "sample.png"); 

// डिफ़ॉल्ट ImageSaveOptions ऑब्जेक्ट इंस्टेंस निर्धारित करें
var options = new ImageSaveOptions(); 

// रूपांतरण प्रक्रिया शुरू करें
Converter.ConvertEPUB(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - custom output folder path.

### संबंधित देखें

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, ImageSaveOptions, String) {#convertepub_11}

URL द्वारा परिभाषित EPUB स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित इमेज फ़ाइल है। इमेज फ़ॉर्मेट ImageSaveOptions ऑब्जेक्ट द्वारा निर्दिष्ट किया गया है।

```java
public static void ConvertEPUB(Url sourceUrl, ImageSaveOptions options, String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceUrl | Url | EPUB स्रोत URL - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| options | ImageSaveOptions | ImageSaveOptions ऑब्जेक्ट का उपयोग आपको रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) आदि निर्दिष्ट कर सकते हैं। देखें [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/) क्लास। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण इमेज फ़ाइल पथ। |

## Remarks

EPUB को इमेज में कैसे बदलें

EPUB एक ई-बुक फ़ाइल फ़ॉर्मेट है जो एक मानक डिजिटल प्रकाशन फ़ॉर्मेट प्रदान करता है। इसे International Digital Publishing Forum (IDPF) ने बनाया था, और अब यह कई ई-रीडर और सॉफ़्टवेयर एप्लिकेशन द्वारा समर्थित है।

EPUB फ़ाइलों को PNG फ़ॉर्मेट में बदलना उपयोगी हो सकता है यदि आपको फ़ाइलों को PowerPoint प्रस्तुति में शामिल करना है या ईमेल द्वारा भेजना है। कृपया उन्हें इमेज फ़ॉर्मेट में बदलें और अपनी इच्छा अनुसार उपयोग करें! वांछित परिणाम प्राप्त करने के लिए आप अतिरिक्त रूपांतरण पैरामीटर का उपयोग कर सकते हैं।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें Converter क्लास का उपयोग करके कैसे निष्पादित करें, इस बारे में जानकारी प्रदान करता है, जो सभी लो‑लेवल रूपांतरण ऑपरेशन्स को एक ही क्लास में समूहित करता है ताकि वे आरामदायक और उपयोग में आसान हों। EPUB Converter गाइड में, आप निम्नलिखित लेख पाएंगे:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

EPUB को इमेज में बदलें

EPUB को इमेज फ़ाइल फ़ॉर्मेट में बदलने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

निर्दिष्ट पथ पर मौजूदा EPUB फ़ाइल के आधार पर URL निर्धारित करें। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें। आवश्यक ImageFormat के साथ एक नया [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट बनाएं। डिफ़ॉल्ट रूप से, Format प्रॉपर्टी PNG है। EPUB को इमेज के रूप में सहेजने के लिए Converter क्लास की ConvertEPUB() मेथड का उपयोग करें। आपको इमेज रूपांतरण के लिए ImageSaveOptions और Configuration ऑब्जेक्ट भी पास करने की आवश्यकता है। ऑनलाइन EPUB कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) कनवर्टर प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से EPUB को PNG इमेज में बदलता है। बस अपनी फ़ाइलें अपलोड करें, कनवर्ट करें और कुछ सेकंड में परिणाम प्राप्त करें!

आप विशेष इमेज फ़ॉर्मेट रूपांतरण में भी रुचि रख सकते हैं

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// इनपुट फ़ाइल पथ के आधार पर URL बनाएं
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// आउटपुट परिणाम फ़ाइल पथ बनाएं
var resultPath = Path.Combine(OutputFolder, "sample.png");

// डिफ़ॉल्ट विकल्प इंस्टेंस निर्धारित करें
var options = new ImageSaveOptions();

// रूपांतरण प्रक्रिया शुरू करें
Converter.ConvertEPUB(sourceUrl, options, resultPath);
```

*InputFolder - user input folder path.

*OutputFolder - user output folder.

### संबंधित देखें

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, ImageSaveOptions, String) {#convertepub_19}

डेटा इनपुट स्ट्रीम द्वारा प्रस्तुत EPUB स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित इमेज फ़ाइल है। इमेज फ़ॉर्मेट ImageSaveOptions ऑब्जेक्ट द्वारा निर्दिष्ट किया गया है।

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | इनपुट स्ट्रीम को रूपांतरण स्रोत के रूप में उपयोग करें। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | ImageSaveOptions | ImageSaveOptions ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), आदि निर्दिष्ट कर सकते हैं। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण इमेज फ़ाइल पथ। |

## Remarks

EPUB को इमेज में कैसे बदलें

EPUB एक ई-बुक फ़ाइल फ़ॉर्मेट है जो एक मानक डिजिटल प्रकाशन फ़ॉर्मेट प्रदान करता है। इसे International Digital Publishing Forum (IDPF) ने बनाया था, और अब यह कई ई-रीडर और सॉफ़्टवेयर एप्लिकेशन द्वारा समर्थित है।

EPUB फ़ाइलों को PNG फ़ॉर्मेट में बदलना उपयोगी हो सकता है यदि आपको फ़ाइलों को PowerPoint प्रस्तुति में शामिल करना है या ईमेल द्वारा भेजना है। कृपया उन्हें इमेज फ़ॉर्मेट में बदलें और अपनी इच्छा अनुसार उपयोग करें! वांछित परिणाम प्राप्त करने के लिए आप अतिरिक्त रूपांतरण पैरामीटर का उपयोग कर सकते हैं।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें Converter क्लास का उपयोग करके कैसे निष्पादित करें, इस बारे में जानकारी प्रदान करता है, जो सभी लो‑लेवल रूपांतरण ऑपरेशन्स को एक ही क्लास में समूहित करता है ताकि वे आरामदायक और उपयोग में आसान हों। EPUB Converter गाइड में, आप निम्नलिखित लेख पाएंगे:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

EPUB को इमेज में बदलें

EPUB को इमेज फ़ाइल फ़ॉर्मेट में बदलने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

निर्दिष्ट पथ पर मौजूदा EPUB फ़ाइल के आधार पर URL निर्धारित करें। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें। आवश्यक ImageFormat के साथ एक नया [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट बनाएं। डिफ़ॉल्ट रूप से, Format प्रॉपर्टी PNG है। EPUB को इमेज के रूप में सहेजने के लिए Converter क्लास की ConvertEPUB() मेथड का उपयोग करें। आपको इमेज रूपांतरण के लिए ImageSaveOptions और Configuration ऑब्जेक्ट भी पास करने की आवश्यकता है। ऑनलाइन EPUB कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) कनवर्टर प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से EPUB को PNG इमेज में बदलता है। बस अपनी फ़ाइलें अपलोड करें, कनवर्ट करें और कुछ सेकंड में परिणाम प्राप्त करें!

आप विशेष इमेज फ़ॉर्मेट रूपांतरण में भी रुचि रख सकते हैं

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// स्ट्रीम के रूप में पढ़ने के लिए मौजूदा फ़ाइल खोलें
var inputStream = System.IO.File.OpenRead(Path.Combine(InputFolder, "sample.epub"));

// आउटपुट फ़ाइल पथ निर्धारित करें
var resultPath = Path.Combine(OutputFolder, "sample.png");

// डिफ़ॉल्ट विकल्प इंस्टेंस निर्धारित करें
var options = new ImageSaveOptions();

// डिफ़ॉल्ट कॉन्फ़िगरेशन ऑब्जेक्ट के साथ रूपांतरण प्रक्रिया शुरू करें
Converter.ConvertEPUB(inputStream, new Configuration(), options, resultPath);
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

## ConvertEPUB(String, Configuration, ImageSaveOptions, String) {#convertepub_35}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत EPUB स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित इमेज फ़ाइल है। इमेज फ़ॉर्मेट ImageSaveOptions ऑब्जेक्ट द्वारा निर्दिष्ट किया गया है।

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourcePath | String | इनपुट पैरामीटर के रूप में EPUB स्रोत फ़ाइल पथ। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) कॉन्टेक्स्ट ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | ImageSaveOptions | ImageSaveOptions ऑब्जेक्ट का उपयोग आपको रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) आदि निर्दिष्ट कर सकते हैं। देखें [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/) क्लास। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण इमेज फ़ाइल पथ। |

## Remarks

EPUB को इमेज में कैसे बदलें

EPUB एक ई-बुक फ़ाइल फ़ॉर्मेट है जो एक मानक डिजिटल प्रकाशन फ़ॉर्मेट प्रदान करता है। इसे International Digital Publishing Forum (IDPF) ने बनाया था, और अब यह कई ई-रीडर और सॉफ़्टवेयर एप्लिकेशन द्वारा समर्थित है।

EPUB फ़ाइलों को PNG फ़ॉर्मेट में बदलना उपयोगी हो सकता है यदि आपको फ़ाइलों को PowerPoint प्रस्तुति में शामिल करना है या ईमेल द्वारा भेजना है। कृपया उन्हें इमेज फ़ॉर्मेट में बदलें और अपनी इच्छा अनुसार उपयोग करें! वांछित परिणाम प्राप्त करने के लिए आप अतिरिक्त रूपांतरण पैरामीटर का उपयोग कर सकते हैं।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें Converter क्लास का उपयोग करके कैसे निष्पादित करें, इस बारे में जानकारी प्रदान करता है, जो सभी लो‑लेवल रूपांतरण ऑपरेशन्स को एक ही क्लास में समूहित करता है ताकि वे आरामदायक और उपयोग में आसान हों। EPUB Converter गाइड में, आप निम्नलिखित लेख पाएंगे:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

EPUB को इमेज में बदलें

EPUB को इमेज फ़ाइल फ़ॉर्मेट में बदलने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

निर्दिष्ट पथ पर मौजूदा EPUB फ़ाइल के आधार पर URL निर्धारित करें। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें। आवश्यक ImageFormat के साथ एक नया [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट बनाएं। डिफ़ॉल्ट रूप से, Format प्रॉपर्टी PNG है। EPUB को इमेज के रूप में सहेजने के लिए Converter क्लास की ConvertEPUB() मेथड का उपयोग करें। आपको इमेज रूपांतरण के लिए ImageSaveOptions और Configuration ऑब्जेक्ट भी पास करने की आवश्यकता है। ऑनलाइन EPUB कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) कनवर्टर प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से EPUB को PNG इमेज में बदलता है। बस अपनी फ़ाइलें अपलोड करें, कनवर्ट करें और कुछ सेकंड में परिणाम प्राप्त करें!

आप विशेष इमेज फ़ॉर्मेट रूपांतरण में भी रुचि रख सकते हैं

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// फ़ॉर्म स्रोत फ़ाइल पथ
var sourcePath = Path.Combine(InputFolder, "sample.epub"); 

// आउटपुट परिणाम फ़ाइल पथ बनाएं
var resultPath = Path.Combine(OutputFolder, "sample.png"); 

// डिफ़ॉल्ट ImageSaveOptions ऑब्जेक्ट इंस्टेंस निर्धारित करें
var options = new ImageSaveOptions(); 

// डिफ़ॉल्ट कॉन्फ़िगरेशन ऑब्जेक्ट के साथ रूपांतरण प्रक्रिया शुरू करें
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);
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

## ConvertEPUB(Url, Configuration, ImageSaveOptions, String) {#convertepub_3}

URL द्वारा परिभाषित EPUB स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित इमेज फ़ाइल है। इमेज फ़ॉर्मेट ImageSaveOptions ऑब्जेक्ट द्वारा निर्दिष्ट किया गया है।

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceUrl | Url | EPUB स्रोत URL - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | ImageSaveOptions | ImageSaveOptions ऑब्जेक्ट का उपयोग आपको रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। आप [page size](https://apireference.aspose.com/html/net/aspose.html.rendering/renderingoptions/properties/pagesetup), [margins](https://apireference.aspose.com/html/net/aspose.html.drawing/page/properties/margin), [CSS media-type](https://apireference.aspose.com/html/net/aspose.html.rendering/mediatype) आदि निर्दिष्ट कर सकते हैं। देखें [ImageSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/imagesaveoptions) क्लास। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण इमेज फ़ाइल पथ। |

## Remarks

EPUB को इमेज में कैसे बदलें

EPUB एक ई-बुक फ़ाइल फ़ॉर्मेट है जो एक मानक डिजिटल प्रकाशन फ़ॉर्मेट प्रदान करता है। इसे International Digital Publishing Forum (IDPF) ने बनाया था, और अब यह कई ई-रीडर और सॉफ़्टवेयर एप्लिकेशन द्वारा समर्थित है।

EPUB फ़ाइलों को PNG फ़ॉर्मेट में बदलना उपयोगी हो सकता है यदि आपको फ़ाइलों को PowerPoint प्रस्तुति में शामिल करना है या ईमेल द्वारा भेजना है। कृपया उन्हें इमेज फ़ॉर्मेट में बदलें और अपनी इच्छा अनुसार उपयोग करें! वांछित परिणाम प्राप्त करने के लिए आप अतिरिक्त रूपांतरण पैरामीटर का उपयोग कर सकते हैं।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें Converter क्लास का उपयोग करके कैसे निष्पादित करें, इस बारे में जानकारी प्रदान करता है, जो सभी लो‑लेवल रूपांतरण ऑपरेशन्स को एक ही क्लास में समूहित करता है ताकि वे आरामदायक और उपयोग में आसान हों। EPUB Converter गाइड में, आप निम्नलिखित लेख पाएंगे:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

EPUB को इमेज में बदलें

EPUB को इमेज फ़ाइल फ़ॉर्मेट में बदलने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

निर्दिष्ट पथ पर मौजूदा EPUB फ़ाइल के आधार पर URL निर्धारित करें। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें। आवश्यक ImageFormat के साथ एक नया [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट बनाएं। डिफ़ॉल्ट रूप से, Format प्रॉपर्टी PNG है। EPUB को इमेज के रूप में सहेजने के लिए Converter क्लास की ConvertEPUB() मेथड का उपयोग करें। आपको इमेज रूपांतरण के लिए ImageSaveOptions और Configuration ऑब्जेक्ट भी पास करने की आवश्यकता है। ऑनलाइन EPUB कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) कनवर्टर प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से EPUB को PNG इमेज में बदलता है। बस अपनी फ़ाइलें अपलोड करें, कनवर्ट करें और कुछ सेकंड में परिणाम प्राप्त करें!

आप विशेष इमेज फ़ॉर्मेट रूपांतरण में भी रुचि रख सकते हैं

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// इनपुट फ़ाइल पथ के आधार पर URL बनाएं
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));  

// आउटपुट फ़ाइल पथ निर्धारित करें
var resultPath = Path.Combine(OutputFolder, "sample.png"); 
 
// डिफ़ॉल्ट विकल्प इंस्टेंस निर्धारित करें
var options = new ImageSaveOptions(); 

// डिफ़ॉल्ट कॉन्फ़िगरेशन ऑब्जेक्ट के साथ रूपांतरण प्रक्रिया शुरू करें
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);  
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

## ConvertEPUB(Stream, ImageSaveOptions, ICreateStreamProvider) {#convertepub_26}

इनपुट [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) द्वारा प्रस्तुत epub स्रोत को इमेज में बदलें। परिणाम एक इमेज फ़ाइल है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस के कार्यान्वयन द्वारा बनाई गई है।

```java
public static void ConvertEPUB(Stream stream, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | इनपुट स्ट्रीम को रूपांतरण स्रोत के रूप में उपयोग करें। |
| options | ImageSaveOptions | ImageSaveOptions ऑब्जेक्ट का उपयोग आपको रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) आदि निर्दिष्ट कर सकते हैं। देखें [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/) क्लास। |
| provider | ICreateStreamProvider | `[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)` इंटरफ़ेस का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। उन्नत उदाहरण के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers)। |

## Remarks

EPUB को इमेज में कैसे बदलें

EPUB एक ई-बुक फ़ाइल फ़ॉर्मेट है जो एक मानक डिजिटल प्रकाशन फ़ॉर्मेट प्रदान करता है। इसे International Digital Publishing Forum (IDPF) ने बनाया था, और अब यह कई ई-रीडर और सॉफ़्टवेयर एप्लिकेशन द्वारा समर्थित है।

EPUB फ़ाइलों को PNG फ़ॉर्मेट में बदलना उपयोगी हो सकता है यदि आपको फ़ाइलों को PowerPoint प्रस्तुति में शामिल करना है या ईमेल द्वारा भेजना है। कृपया उन्हें इमेज फ़ॉर्मेट में बदलें और अपनी इच्छा अनुसार उपयोग करें! वांछित परिणाम प्राप्त करने के लिए आप अतिरिक्त रूपांतरण पैरामीटर का उपयोग कर सकते हैं।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें Converter क्लास का उपयोग करके कैसे निष्पादित करें, इस बारे में जानकारी प्रदान करता है, जो सभी लो‑लेवल रूपांतरण ऑपरेशन्स को एक ही क्लास में समूहित करता है ताकि वे आरामदायक और उपयोग में आसान हों। EPUB Converter गाइड में, आप निम्नलिखित लेख पाएंगे:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

EPUB को इमेज में बदलें

EPUB को इमेज फ़ाइल फ़ॉर्मेट में बदलने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण में, हम निर्दिष्ट पथ पर फ़ाइल सिस्टम से EPUB फ़ाइल को खोलने और पढ़ने के लिए System.IO.FileStream क्लास की OpenRead() मेथड का उपयोग करते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन का उपयोग करें। आवश्यक ImageFormat के साथ एक नया [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट बनाएं। डिफ़ॉल्ट रूप से, Format प्रॉपर्टी PNG है। EPUB को इमेज के रूप में सहेजने के लिए Converter क्लास की ConvertEPUB() मेथड का उपयोग करें। आपको EPUB inputStream, ImageSaveOptions, और आउटपुट स्ट्रीम को ConvertEPUB() मेथड में पास करना होगा ताकि EPUB से इमेज रूपांतरण हो सके। ऑनलाइन EPUB कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) कनवर्टर प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से EPUB को PNG इमेज में बदलता है। बस अपनी फ़ाइलें अपलोड करें, कनवर्ट करें और कुछ सेकंड में परिणाम प्राप्त करें!

आप विशेष इमेज फ़ॉर्मेट रूपांतरण में भी रुचि रख सकते हैं

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// स्ट्रीम के रूप में पढ़ने के लिए मौजूदा फ़ाइल खोलें  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// ICreateStreamProvider इंटरफ़ेस कार्यान्वयन देखें  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// डिफ़ॉल्ट विकल्प इंस्टेंस बनाएं  
var options = new ImageSaveOptions();    

// रूपांतरण प्रक्रिया शुरू करें  
Converter.ConvertEPUB(inputStream, options, sp);
```

*InputFolder - user input folder path.

*OutputFolder - user output folder path.

### संबंधित देखें

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, ImageSaveOptions, ICreateStreamProvider) {#convertepub_42}

फ़ाइल पथ द्वारा प्रस्तुत EPUB स्रोत को इमेज में बदलें। परिणाम एक इमेज फ़ाइल है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस के कार्यान्वयन द्वारा बनाई गई है।

```java
public static void ConvertEPUB(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourcePath | String | EPUB स्रोत फ़ाइल पथ। इसे वर्तमान डायरेक्टरी पथ के साथ मिलाकर एक पूर्ण URL बनाया जाएगा। |
| options | ImageSaveOptions | नए निर्मित इमेज विकल्प जैसे फ़ॉर्मेट, रिज़ॉल्यूशन आदि। देखें [`ImageSaveOptions `] क्लास और [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/#save-options). |
| provider | ICreateStreamProvider | इंटरफ़ेस का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। प्रोवाइडर्स के बारे में अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers)। |

## Remarks

EPUB को इमेज में कैसे बदलें

EPUB एक ई-बुक फ़ाइल फ़ॉर्मेट है जो एक मानक डिजिटल प्रकाशन फ़ॉर्मेट प्रदान करता है। इसे International Digital Publishing Forum (IDPF) ने बनाया था, और अब यह कई ई-रीडर और सॉफ़्टवेयर एप्लिकेशन द्वारा समर्थित है।

EPUB फ़ाइलों को PNG फ़ॉर्मेट में बदलना उपयोगी हो सकता है यदि आपको फ़ाइलों को PowerPoint प्रस्तुति में शामिल करना है या ईमेल द्वारा भेजना है। कृपया उन्हें इमेज फ़ॉर्मेट में बदलें और अपनी इच्छा अनुसार उपयोग करें! वांछित परिणाम प्राप्त करने के लिए आप अतिरिक्त रूपांतरण पैरामीटर का उपयोग कर सकते हैं।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें Converter क्लास का उपयोग करके कैसे निष्पादित करें, इस बारे में जानकारी प्रदान करता है, जो सभी लो‑लेवल रूपांतरण ऑपरेशन्स को एक ही क्लास में समूहित करता है ताकि वे आरामदायक और उपयोग में आसान हों। EPUB Converter गाइड में, आप निम्नलिखित लेख पाएंगे:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

EPUB को इमेज में बदलें

EPUB को इमेज फ़ाइल फ़ॉर्मेट में बदलने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण में, हम निर्दिष्ट पथ पर फ़ाइल सिस्टम से EPUB फ़ाइल को खोलने और पढ़ने के लिए System.IO.FileStream क्लास की OpenRead() मेथड का उपयोग करते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम ICreateStreamProvider इंटरफ़ेस कार्यान्वयन का उपयोग करें। आवश्यक ImageFormat के साथ एक नया ImageSaveOptions ऑब्जेक्ट बनाएं। डिफ़ॉल्ट रूप से, Format प्रॉपर्टी PNG है। EPUB को इमेज के रूप में सहेजने के लिए Converter क्लास की ConvertEPUB() मेथड का उपयोग करें। आपको EPUB inputStream, ImageSaveOptions, और आउटपुट स्ट्रीम को ConvertEPUB() मेथड में पास करना होगा ताकि EPUB से इमेज रूपांतरण हो सके। ऑनलाइन EPUB कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) कनवर्टर प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से EPUB को PNG इमेज में बदलता है। बस अपनी फ़ाइलें अपलोड करें, कनवर्ट करें और कुछ सेकंड में परिणाम प्राप्त करें!

आप विशेष इमेज फ़ॉर्मेट रूपांतरण में भी रुचि रख सकते हैं

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

दो लाइनों के कोड से EPUB को JPG में बदलें

```java
import System.IO;
import com.aspose.html.converters;
import com.aspose.html.rendering.image;
import com.aspose.html.saving;
...
// पढ़ने के लिए एक मौजूदा EPUB फ़ाइल खोलें।
import var stream = File.OpenRead(DataDir + "input.epub");

// ConvertEPUB मेथड को कॉल करें ताकि EPUB कोड को JPG छवि में परिवर्तित किया जा सके
Converter.ConvertEPUB(stream, new ImageSaveOptions(ImageFormat.Jpeg), Path.Combine(OutputDir, "convert-by-two-lines.jpg"));
```

*DataDir - user source file path.

*OutputDir - user output file path.

### संबंधित देखें

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, ImageSaveOptions, ICreateStreamProvider) {#convertepub_10}

URL द्वारा प्रस्तुत EPUB स्रोत को छवि में परिवर्तित करें। परिणाम एक छवि फ़ाइल है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस के कार्यान्वयन द्वारा बनाई गई है।

```java
public static void ConvertEPUB(Url sourceUrl, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceUrl | Url | EPUB स्रोत URL - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| options | ImageSaveOptions | ImageSaveOptions ऑब्जेक्ट का उपयोग आपको रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) आदि निर्दिष्ट कर सकते हैं। देखें [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/) क्लास। |
| provider | ICreateStreamProvider | इंटरफ़ेस का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। प्रोवाइडर्स के बारे में अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers)। |

## Remarks

EPUB को इमेज में कैसे बदलें

EPUB एक ई-बुक फ़ाइल फ़ॉर्मेट है जो एक मानक डिजिटल प्रकाशन फ़ॉर्मेट प्रदान करता है। इसे International Digital Publishing Forum (IDPF) ने बनाया था, और अब यह कई ई-रीडर और सॉफ़्टवेयर एप्लिकेशन द्वारा समर्थित है।

EPUB फ़ाइलों को PNG फ़ॉर्मेट में बदलना उपयोगी हो सकता है यदि आपको फ़ाइलों को PowerPoint प्रस्तुति में शामिल करना है या ईमेल द्वारा भेजना है। कृपया उन्हें इमेज फ़ॉर्मेट में बदलें और अपनी इच्छा अनुसार उपयोग करें! वांछित परिणाम प्राप्त करने के लिए आप अतिरिक्त रूपांतरण पैरामीटर का उपयोग कर सकते हैं।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें Converter क्लास का उपयोग करके कैसे निष्पादित करें, इस बारे में जानकारी प्रदान करता है, जो सभी लो‑लेवल रूपांतरण ऑपरेशन्स को एक ही क्लास में समूहित करता है ताकि वे आरामदायक और उपयोग में आसान हों। EPUB Converter गाइड में, आप निम्नलिखित लेख पाएंगे:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

EPUB को इमेज में बदलें

EPUB को इमेज फ़ाइल फ़ॉर्मेट में बदलने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण में, हम निर्दिष्ट पथ पर फ़ाइल सिस्टम से EPUB फ़ाइल को खोलने और पढ़ने के लिए System.IO.FileStream क्लास की OpenRead() मेथड का उपयोग करते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम ICreateStreamProvider इंटरफ़ेस कार्यान्वयन का उपयोग करें। आवश्यक ImageFormat के साथ एक नया ImageSaveOptions ऑब्जेक्ट बनाएं। डिफ़ॉल्ट रूप से, Format प्रॉपर्टी PNG है। EPUB को इमेज के रूप में सहेजने के लिए Converter क्लास की ConvertEPUB() मेथड का उपयोग करें। आपको EPUB inputStream, ImageSaveOptions, और आउटपुट स्ट्रीम को ConvertEPUB() मेथड में पास करना होगा ताकि EPUB से इमेज रूपांतरण हो सके। ऑनलाइन EPUB कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) कनवर्टर प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से EPUB को PNG इमेज में बदलता है। बस अपनी फ़ाइलें अपलोड करें, कनवर्ट करें और कुछ सेकंड में परिणाम प्राप्त करें!

आप विशेष इमेज फ़ॉर्मेट रूपांतरण में भी रुचि रख सकते हैं

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

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
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// ICreateStreamProvider इंटरफ़ेस कार्यान्वयन देखें  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// डिफ़ॉल्ट विकल्प इंस्टेंस बनाएं  
var options = new ImageSaveOptions();

// रूपांतरण प्रक्रिया शुरू करें  
Converter.ConvertEPUB(sourceUrl, options, sp);
```

*InputFolder - user input folder.

*OutputFolder - user output folder.

*ImageSaveOptions supposes PNG format of new formed image.

### संबंधित देखें

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertepub_18}

इनपुट [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) द्वारा प्रस्तुत epub स्रोत को इमेज में बदलें। परिणाम एक इमेज फ़ाइल है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस के कार्यान्वयन द्वारा बनाई गई है।

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | इनपुट स्ट्रीम को रूपांतरण स्रोत के रूप में उपयोग करें। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | ImageSaveOptions | ImageSaveOptions ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), आदि निर्दिष्ट कर सकते हैं। |
| प्रोवाइडर | ICreateStreamProvider | इंटरफ़ेस का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। |

## Remarks

EPUB को इमेज में कैसे बदलें

EPUB एक ई-बुक फ़ाइल फ़ॉर्मेट है जो एक मानक डिजिटल प्रकाशन फ़ॉर्मेट प्रदान करता है। इसे International Digital Publishing Forum (IDPF) ने बनाया था, और अब यह कई ई-रीडर और सॉफ़्टवेयर एप्लिकेशन द्वारा समर्थित है।

EPUB फ़ाइलों को PNG फ़ॉर्मेट में बदलना उपयोगी हो सकता है यदि आपको फ़ाइलों को PowerPoint प्रस्तुति में शामिल करना है या ईमेल द्वारा भेजना है। कृपया उन्हें इमेज फ़ॉर्मेट में बदलें और अपनी इच्छा अनुसार उपयोग करें! वांछित परिणाम प्राप्त करने के लिए आप अतिरिक्त रूपांतरण पैरामीटर का उपयोग कर सकते हैं।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें Converter क्लास का उपयोग करके कैसे निष्पादित करें, इस बारे में जानकारी प्रदान करता है, जो सभी लो‑लेवल रूपांतरण ऑपरेशन्स को एक ही क्लास में समूहित करता है ताकि वे आरामदायक और उपयोग में आसान हों। EPUB Converter गाइड में, आप निम्नलिखित लेख पाएंगे:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

EPUB को इमेज में बदलें

EPUB को इमेज फ़ाइल फ़ॉर्मेट में बदलने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण में, हम निर्दिष्ट पथ पर फ़ाइल सिस्टम से EPUB फ़ाइल को खोलने और पढ़ने के लिए System.IO.FileStream क्लास की OpenRead() मेथड का उपयोग करते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम ICreateStreamProvider इंटरफ़ेस कार्यान्वयन का उपयोग करें। आवश्यक ImageFormat के साथ एक नया ImageSaveOptions ऑब्जेक्ट बनाएं। डिफ़ॉल्ट रूप से, Format प्रॉपर्टी PNG है। EPUB को इमेज के रूप में सहेजने के लिए Converter क्लास की ConvertEPUB() मेथड का उपयोग करें। आपको EPUB inputStream, ImageSaveOptions, और आउटपुट स्ट्रीम को ConvertEPUB() मेथड में पास करना होगा ताकि EPUB से इमेज रूपांतरण हो सके। ऑनलाइन EPUB कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) कनवर्टर प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से EPUB को PNG इमेज में बदलता है। बस अपनी फ़ाइलें अपलोड करें, कनवर्ट करें और कुछ सेकंड में परिणाम प्राप्त करें!

आप विशेष इमेज फ़ॉर्मेट रूपांतरण में भी रुचि रख सकते हैं

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// स्ट्रीम के रूप में पढ़ने के लिए मौजूदा फ़ाइल खोलें  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  


// ICreateStreamProvider इंटरफ़ेस कार्यान्वयन देखें  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  


// डिफ़ॉल्ट विकल्प इंस्टेंस बनाएं  
var options = new ImageSaveOptions();    


// डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें।
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

*ImageSaveOptions supposes PNG format of new formed image.

### संबंधित देखें

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertepub_34}

फ़ाइल पथ द्वारा प्रस्तुत EPUB स्रोत को छवि में परिवर्तित करें। परिणाम एक छवि फ़ाइल है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस के कार्यान्वयन द्वारा बनाई गई है।

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourcePath | String | फ़ाइल पथ द्वारा परिभाषित EPUB स्रोत। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | ImageSaveOptions | ImageSaveOptions ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), आदि निर्दिष्ट कर सकते हैं। |
| provider | ICreateStreamProvider | इंटरफ़ेस का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। ICreateStreamProvider कार्यान्वयन का उदाहरण देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers)। |

## Remarks

EPUB को इमेज में कैसे बदलें

EPUB एक ई-बुक फ़ाइल फ़ॉर्मेट है जो एक मानक डिजिटल प्रकाशन फ़ॉर्मेट प्रदान करता है। इसे International Digital Publishing Forum (IDPF) ने बनाया था, और अब यह कई ई-रीडर और सॉफ़्टवेयर एप्लिकेशन द्वारा समर्थित है।

EPUB फ़ाइलों को PNG फ़ॉर्मेट में बदलना उपयोगी हो सकता है यदि आपको फ़ाइलों को PowerPoint प्रस्तुति में शामिल करना है या ईमेल द्वारा भेजना है। कृपया उन्हें इमेज फ़ॉर्मेट में बदलें और अपनी इच्छा अनुसार उपयोग करें! वांछित परिणाम प्राप्त करने के लिए आप अतिरिक्त रूपांतरण पैरामीटर का उपयोग कर सकते हैं।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें Converter क्लास का उपयोग करके कैसे निष्पादित करें, इस बारे में जानकारी प्रदान करता है, जो सभी लो‑लेवल रूपांतरण ऑपरेशन्स को एक ही क्लास में समूहित करता है ताकि वे आरामदायक और उपयोग में आसान हों। EPUB Converter गाइड में, आप निम्नलिखित लेख पाएंगे:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

EPUB को इमेज में बदलें

EPUB को इमेज फ़ाइल फ़ॉर्मेट में बदलने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण में, हम निर्दिष्ट पथ पर फ़ाइल सिस्टम से EPUB फ़ाइल को खोलने और पढ़ने के लिए System.IO.FileStream क्लास की OpenRead() मेथड का उपयोग करते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम ICreateStreamProvider इंटरफ़ेस कार्यान्वयन का उपयोग करें। आवश्यक ImageFormat के साथ एक नया ImageSaveOptions ऑब्जेक्ट बनाएं। डिफ़ॉल्ट रूप से, Format प्रॉपर्टी PNG है। EPUB को इमेज के रूप में सहेजने के लिए Converter क्लास की ConvertEPUB() मेथड का उपयोग करें। आपको EPUB inputStream, ImageSaveOptions, और आउटपुट स्ट्रीम को ConvertEPUB() मेथड में पास करना होगा ताकि EPUB से इमेज रूपांतरण हो सके। ऑनलाइन EPUB कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) कनवर्टर प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से EPUB को PNG इमेज में बदलता है। बस अपनी फ़ाइलें अपलोड करें, कनवर्ट करें और कुछ सेकंड में परिणाम प्राप्त करें!

आप विशेष इमेज फ़ॉर्मेट रूपांतरण में भी रुचि रख सकते हैं

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// फ़ॉर्म स्रोत फ़ाइल पथ
var sourcePath = Path.Combine(InputFolder, "sample.epub"); 

// ICreateStreamProvider इंटरफ़ेस कार्यान्वयन देखें  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// डिफ़ॉल्ट ImageSaveOptions ऑब्जेक्ट इंस्टेंस निर्धारित करें
var options = new ImageSaveOptions(); 

// डिफ़ॉल्ट कॉन्फ़िगरेशन ऑब्जेक्ट के साथ रूपांतरण प्रक्रिया शुरू करें
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);
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

## ConvertEPUB(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertepub_2}

URL द्वारा प्रस्तुत epub स्रोत को छवि में बदलें। परिणाम इमेज फ़ाइल है जो [ICreateStreamProvider](https://apireference.aspose.com/html/net/aspose.html.io/icreatestreamprovider) इंटरफ़ेस के कार्यान्वयन द्वारा निर्मित होती है।

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceUrl | Url | EPUB स्रोत URL - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | ImageSaveOptions | ImageSaveOptions ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), आदि निर्दिष्ट कर सकते हैं। |
| provider | ICreateStreamProvider | इंटरफ़ेस का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। ICreateStreamProvider कार्यान्वयन का उदाहरण देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers)। |

## Remarks

EPUB को इमेज में कैसे बदलें

EPUB एक ई-बुक फ़ाइल फ़ॉर्मेट है जो एक मानक डिजिटल प्रकाशन फ़ॉर्मेट प्रदान करता है। इसे International Digital Publishing Forum (IDPF) ने बनाया था, और अब यह कई ई-रीडर और सॉफ़्टवेयर एप्लिकेशन द्वारा समर्थित है।

EPUB फ़ाइलों को PNG फ़ॉर्मेट में बदलना उपयोगी हो सकता है यदि आपको फ़ाइलों को PowerPoint प्रस्तुति में शामिल करना है या ईमेल द्वारा भेजना है। कृपया उन्हें इमेज फ़ॉर्मेट में बदलें और अपनी इच्छा अनुसार उपयोग करें! वांछित परिणाम प्राप्त करने के लिए आप अतिरिक्त रूपांतरण पैरामीटर का उपयोग कर सकते हैं।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें Converter क्लास का उपयोग करके कैसे निष्पादित करें, इस बारे में जानकारी प्रदान करता है, जो सभी लो‑लेवल रूपांतरण ऑपरेशन्स को एक ही क्लास में समूहित करता है ताकि वे आरामदायक और उपयोग में आसान हों। EPUB Converter गाइड में, आप निम्नलिखित लेख पाएंगे:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

EPUB को इमेज में बदलें

EPUB को इमेज फ़ाइल फ़ॉर्मेट में बदलने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण में, हम निर्दिष्ट पथ पर फ़ाइल सिस्टम से EPUB फ़ाइल को खोलने और पढ़ने के लिए System.IO.FileStream क्लास की OpenRead() मेथड का उपयोग करते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम ICreateStreamProvider इंटरफ़ेस कार्यान्वयन का उपयोग करें। आवश्यक ImageFormat के साथ एक नया ImageSaveOptions ऑब्जेक्ट बनाएं। डिफ़ॉल्ट रूप से, Format प्रॉपर्टी PNG है। EPUB को इमेज के रूप में सहेजने के लिए Converter क्लास की ConvertEPUB() मेथड का उपयोग करें। आपको EPUB inputStream, ImageSaveOptions, और आउटपुट स्ट्रीम को ConvertEPUB() मेथड में पास करना होगा ताकि EPUB से इमेज रूपांतरण हो सके। ऑनलाइन EPUB कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) कनवर्टर प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से EPUB को PNG इमेज में बदलता है। बस अपनी फ़ाइलें अपलोड करें, कनवर्ट करें और कुछ सेकंड में परिणाम प्राप्त करें!

आप विशेष इमेज फ़ॉर्मेट रूपांतरण में भी रुचि रख सकते हैं

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;
...
// इनपुट फ़ाइल पथ द्वारा स्रोत URL बनाएं
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// ICreateStreamProvider इंटरफ़ेस कार्यान्वयन देखें  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// डिफ़ॉल्ट विकल्प इंस्टेंस बनाएं  
var options = new ImageSaveOptions();

// डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, sp);

```

*InputFolder - user source file path.

*OutputFolder - user output file path.

*ImageSaveOptions supposes PNG format of new formed image.

### संबंधित देखें

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, XpsSaveOptions, String) {#convertepub_31}

इनपुट स्ट्रीम द्वारा प्रस्तुत epub स्रोत को xps में परिवर्तित करें। परिणाम पूर्ण पथ द्वारा परिभाषित xps फ़ाइल है।

```java
public static void ConvertEPUB(Stream stream, XpsSaveOptions options, String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | Stream | रूपांतरण स्रोत के रूप में इनपुट स्ट्रीम। स्ट्रीम विनिर्देश देखें [official source](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0)। |
| options | XpsSaveOptions | रूपांतरण विकल्प। [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट का उपयोग आपको रेंडरिंग प्रक्रिया को समायोजित करने की अनुमति देता है; आप पृष्ठ आकार, मार्जिन, CSS आदि निर्दिष्ट कर सकते हैं। |
| outputPath | String | .xps फ़ाइल का पूर्ण पथ आउटपुट रूपांतरण परिणाम के रूप में। |

## Remarks

EPUB को XPS में कैसे परिवर्तित करें

एक XPS फ़ाइल पृष्ठ लेआउट फ़ाइलों को दर्शाती है जो माइक्रोसॉफ्ट द्वारा बनाई गई XML पेपर स्पेसिफिकेशन्स पर आधारित हैं। इसे EMF फ़ाइल फ़ॉर्मेट के विकल्प के रूप में विकसित किया गया था और यह PDF फ़ॉर्मेट के समान है, लेकिन दस्तावेज़ के लेआउट, स्वरूप और प्रिंटिंग जानकारी में XML का उपयोग करता है।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें कैसे निष्पादित करें, इस बारे में जानकारी प्रदान करता है, जिसमें एक [`Converter`](../) क्लास का उपयोग किया गया है जो सभी लो-लेवल रूपांतरण ऑपरेशन्स को एक ही क्लास में समूहित करता है ताकि इसे आरामदायक और आसान उपयोग किया जा सके। EPUB कनवर्टर XPS विशिष्ट गाइड में, आप निम्नलिखित लेख पाएँगे:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

EPUB को XPS में परिवर्तित करें

EPUB को XPS फ़ाइल फ़ॉर्मेट में परिवर्तित करने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण के लिए, हम स्रोत फ़ाइल पथ को ConvertEPUB मेथड के पहले पैरामीटर के रूप में परिभाषित कर सकते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम ICreateStreamProvider इंटरफ़ेस कार्यान्वयन का उपयोग करें। हम परिणाम आउटपुट फ़ाइल पथ को एक सरल विकल्प के रूप में भी उपयोग कर सकते हैं। पृष्ठ आकार, मार्जिन, CSS आदि जैसे वांछित पैरामीटरों के साथ एक नया XpsSaveOptions ऑब्जेक्ट बनाएं। XpsSaveOptions क्लास का डिफ़ॉल्ट इंस्टेंस उपयोग करना संभव है। EPUB को XPS फ़ाइल के रूप में सहेजने के लिए स्थैतिक Converter क्लास की ConvertEPUB() मेथड का उपयोग करें। रूपांतरण प्रक्रिया शुरू करने के लिए आपको EPUB स्रोत डेटा, XpsSaveOptions, और आउटपुट डेटा बफ़र को किसी भी रूप में पास करना होगा। ऑनलाइन EPUB से XPS कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) कनवर्टर प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से EPUB को XPS फ़ाइल में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System.Drawing;
import com.aspose.html.drawing;
...
  // पढ़ने के लिए एक मौजूदा EPUB फ़ाइल खोलें
  using var stream = File.OpenRead(DataDir + "input.epub");

  // परिवर्तित फ़ाइल को सहेजने के लिए पथ तैयार करें
  String savePath = Path.Combine(OutputDir, "input-options.xps");
   
  // XpsSaveOptions का एक इंस्टेंस बनाएं। पृष्ठ आकार सेट करें और पृष्ठभूमि रंग को LightGray में बदलें
  var options = new XpsSaveOptions()
  {
    PageSetup =
      {
        AnyPage = new Page()
        {
          Size = new com.aspose.html.drawing.Size(Length.FromPixels(500), Length.FromPixels(500))
        }
      },
    BackgroundColor = Color.LightGray
  };
   
  // EPUB को XPS में परिवर्तित करने के लिए ConvertEPUB मेथड को कॉल करें
  Converter.ConvertEPUB(stream, options, savePath); 
```

*DataDir - some user input folder.

*OutputDir - user output folder.

### संबंधित देखें

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, XpsSaveOptions, String) {#convertepub_47}

इनपुट EPUB फ़ाइल पथ द्वारा प्रस्तुत epub स्रोत को xps में परिवर्तित करें। परिणाम पूर्ण पथ द्वारा परिभाषित xps फ़ाइल है।

```java
public static void ConvertEPUB(String sourcePath, XpsSaveOptions options, String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourcePath | String | EPUB स्रोत फ़ाइल पथ। इसे वर्तमान डायरेक्टरी पथ के साथ मिलाकर एक पूर्ण URL बनाया जाएगा। |
| options | XpsSaveOptions | रूपांतरण विकल्प। [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट का उपयोग आपको रेंडरिंग प्रक्रिया को समायोजित करने की अनुमति देता है; आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media type`](../../../com.aspose.html.rendering/mediatype/), आदि निर्दिष्ट कर सकते हैं। |
| outputPath | String | .xps फ़ाइल का पूर्ण पथ आउटपुट रूपांतरण परिणाम के रूप में। |

## Remarks

EPUB को XPS में कैसे परिवर्तित करें

एक XPS फ़ाइल पृष्ठ लेआउट फ़ाइलों को दर्शाती है जो माइक्रोसॉफ्ट द्वारा बनाई गई XML पेपर स्पेसिफिकेशन्स पर आधारित हैं। इसे EMF फ़ाइल फ़ॉर्मेट के विकल्प के रूप में विकसित किया गया था और यह PDF फ़ॉर्मेट के समान है, लेकिन दस्तावेज़ के लेआउट, स्वरूप और प्रिंटिंग जानकारी में XML का उपयोग करता है।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें कैसे निष्पादित करें, इस बारे में जानकारी प्रदान करता है, जिसमें एक [`Converter`](../) क्लास का उपयोग किया गया है जो सभी लो-लेवल रूपांतरण ऑपरेशन्स को एक ही क्लास में समूहित करता है ताकि इसे आरामदायक और आसान उपयोग किया जा सके। EPUB कनवर्टर XPS विशिष्ट गाइड में, आप निम्नलिखित लेख पाएँगे:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

EPUB को XPS में परिवर्तित करें

EPUB को XPS फ़ाइल फ़ॉर्मेट में परिवर्तित करने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण के लिए, हम स्रोत फ़ाइल पथ को ConvertEPUB मेथड के पहले पैरामीटर के रूप में परिभाषित कर सकते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम ICreateStreamProvider इंटरफ़ेस कार्यान्वयन का उपयोग करें। हम परिणाम आउटपुट फ़ाइल पथ को एक सरल विकल्प के रूप में भी उपयोग कर सकते हैं। पृष्ठ आकार, मार्जिन, CSS आदि जैसे वांछित पैरामीटरों के साथ एक नया XpsSaveOptions ऑब्जेक्ट बनाएं। XpsSaveOptions क्लास का डिफ़ॉल्ट इंस्टेंस उपयोग करना संभव है। EPUB को XPS फ़ाइल के रूप में सहेजने के लिए स्थैतिक Converter क्लास की ConvertEPUB() मेथड का उपयोग करें। रूपांतरण प्रक्रिया शुरू करने के लिए आपको EPUB स्रोत डेटा, [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/), और आउटपुट डेटा बफ़र को किसी भी रूप में पास करना होगा। ऑनलाइन EPUB से XPS कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) कनवर्टर प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से EPUB को XPS फ़ाइल में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;
import com.aspose.html.saving;
import com.aspose.html.converters;
...
// फ़ॉर्म स्रोत फ़ाइल पथ
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// आउटपुट परिणाम फ़ाइल पथ बनाएं
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// डिफ़ॉल्ट विकल्प इंस्टेंस बनाएं  
var options = new XpsSaveOptions();

// डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
Converter.ConvertEPUB(sourcePath, options, resultPath);  
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, XpsSaveOptions, String) {#convertepub_15}

URL द्वारा प्रस्तुत epub स्रोत को पूर्ण पथ द्वारा परिभाषित xps फ़ाइल में परिवर्तित करें। देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/).

```java
public static void ConvertEPUB(Url sourceUrl, XpsSaveOptions options, String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceUrl | Url | EPUB स्रोत URL - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| options | XpsSaveOptions | रूपांतरण विकल्प। [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट का उपयोग आपको रेंडरिंग प्रक्रिया को समायोजित करने की अनुमति देता है; आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media type`](../../../com.aspose.html.rendering/mediatype/), आदि निर्दिष्ट कर सकते हैं। |
| outputPath | String | .xps फ़ाइल का पूर्ण पथ आउटपुट रूपांतरण परिणाम के रूप में। |

## Remarks

EPUB को XPS में कैसे परिवर्तित करें

एक XPS फ़ाइल पृष्ठ लेआउट फ़ाइलों को दर्शाती है जो माइक्रोसॉफ्ट द्वारा बनाई गई XML पेपर स्पेसिफिकेशन्स पर आधारित हैं। इसे EMF फ़ाइल फ़ॉर्मेट के विकल्प के रूप में विकसित किया गया था और यह PDF फ़ॉर्मेट के समान है, लेकिन दस्तावेज़ के लेआउट, स्वरूप और प्रिंटिंग जानकारी में XML का उपयोग करता है।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें कैसे निष्पादित करें, इस बारे में जानकारी प्रदान करता है, जिसमें एक [`Converter`](../) क्लास का उपयोग किया गया है जो सभी लो-लेवल रूपांतरण ऑपरेशन्स को एक ही क्लास में समूहित करता है ताकि इसे आरामदायक और आसान उपयोग किया जा सके। EPUB कनवर्टर XPS विशिष्ट गाइड में, आप निम्नलिखित लेख पाएँगे:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

EPUB को XPS में परिवर्तित करें

EPUB को XPS फ़ाइल फ़ॉर्मेट में परिवर्तित करने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण के लिए, हम स्रोत फ़ाइल पथ को ConvertEPUB मेथड के पहले पैरामीटर के रूप में परिभाषित कर सकते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम ICreateStreamProvider इंटरफ़ेस कार्यान्वयन का उपयोग करें। हम परिणाम आउटपुट फ़ाइल पथ के रूप में अधिक सरल विकल्प का उपयोग कर सकते हैं। पृष्ठ आकार, मार्जिन, CSS आदि जैसे वांछित पैरामीटरों की संख्या के साथ एक नया XpsSaveOptions ऑब्जेक्ट बनाएं। XpsSaveOptions क्लास का डिफ़ॉल्ट इंस्टेंस उपयोग करना संभव है। EPUB को XPS फ़ाइल के रूप में सहेजने के लिए स्थिर Converter क्लास की ConvertEPUB() मेथड का उपयोग करें। रूपांतरण प्रक्रिया शुरू करने के लिए आपको EPUB स्रोत डेटा, XpsSaveOptions, और आउटपुट डेटा बफ़र को किसी भी रूप में पास करना होगा।

ऑनलाइन EPUB से XPS रूपांतरणकर्ता

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) कनवर्टर प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से EPUB को XPS फ़ाइल में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;
...
// इनपुट फ़ाइल पथ द्वारा स्रोत URL बनाएं
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// आउटपुट परिणाम फ़ाइल पथ बनाएं
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// डिफ़ॉल्ट विकल्प इंस्टेंस बनाएं  
var options = new XpsSaveOptions();

// रूपांतरण प्रक्रिया शुरू करें
Converter.ConvertEPUB(sourceUrl, options, resultPath);





*InputFolder - user input directory.

```

*OutputFolder - user output directory.

### संबंधित देखें

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, XpsSaveOptions, String) {#convertepub_23}

इनपुट [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) द्वारा प्रस्तुत epub स्रोत को xps में परिवर्तित करें। परिणाम पूर्ण पथ द्वारा परिभाषित xps फ़ाइल है।

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | इनपुट स्ट्रीम को रूपांतरण स्रोत के रूप में उपयोग करें। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | XpsSaveOptions | रूपांतरण विकल्प। [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट का उपयोग आपको रेंडरिंग प्रक्रिया को समायोजित करने की अनुमति देता है; आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media type`](../../../com.aspose.html.rendering/mediatype/), आदि निर्दिष्ट कर सकते हैं। |
| outputPath | String | .xps फ़ाइल का पूर्ण पथ आउटपुट रूपांतरण परिणाम के रूप में। |

## Remarks

EPUB को XPS में कैसे परिवर्तित करें

एक XPS फ़ाइल पृष्ठ लेआउट फ़ाइलों को दर्शाती है जो माइक्रोसॉफ्ट द्वारा बनाई गई XML पेपर स्पेसिफिकेशन्स पर आधारित हैं। इसे EMF फ़ाइल फ़ॉर्मेट के विकल्प के रूप में विकसित किया गया था और यह PDF फ़ॉर्मेट के समान है, लेकिन दस्तावेज़ के लेआउट, स्वरूप और प्रिंटिंग जानकारी में XML का उपयोग करता है।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें कैसे निष्पादित करें, इस बारे में जानकारी प्रदान करता है, जिसमें एक [`Converter`](../) क्लास का उपयोग किया गया है जो सभी लो-लेवल रूपांतरण ऑपरेशन्स को एक ही क्लास में समूहित करता है ताकि इसे आरामदायक और आसान उपयोग किया जा सके। EPUB कनवर्टर XPS विशिष्ट गाइड में, आप निम्नलिखित लेख पाएँगे:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

EPUB को XPS में परिवर्तित करें

EPUB को XPS फ़ाइल फ़ॉर्मेट में परिवर्तित करने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण के लिए, हम स्रोत फ़ाइल पथ को ConvertEPUB मेथड के पहले पैरामीटर के रूप में परिभाषित कर सकते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम ICreateStreamProvider इंटरफ़ेस कार्यान्वयन का उपयोग करें। हम परिणाम आउटपुट फ़ाइल पथ के रूप में अधिक सरल विकल्प का उपयोग कर सकते हैं। पृष्ठ आकार, मार्जिन, CSS आदि जैसे वांछित पैरामीटरों की संख्या के साथ एक नया XpsSaveOptions ऑब्जेक्ट बनाएं। XpsSaveOptions क्लास का डिफ़ॉल्ट इंस्टेंस उपयोग करना संभव है। EPUB को XPS फ़ाइल के रूप में सहेजने के लिए स्थिर Converter क्लास की ConvertEPUB() मेथड का उपयोग करें। रूपांतरण प्रक्रिया शुरू करने के लिए आपको EPUB स्रोत डेटा, XpsSaveOptions, और आउटपुट डेटा बफ़र को किसी भी रूप में पास करना होगा। आप उस कॉन्फ़िगरेशन का उपयोग कर सकते हैं जो [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है और एप्लिकेशन के पर्यावरण सेटिंग्स को सेट करने के लिए उपयोग किया जाता है। Online EPUB to XPS converter

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) कनवर्टर प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से EPUB को XPS फ़ाइल में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;
...

// पढ़ने के लिए एक मौजूदा EPUB फ़ाइल खोलें
import var stream = File.OpenRead(DataDir + "input.epub");

// परिवर्तित फ़ाइल को सहेजने के लिए पथ तैयार करें 
String savePath = Path.Combine(OutputDir, "input-output.xps");       
   
// XpsSaveOptions को आरंभ करें 
var options = new XpsSaveOptions();
   
// EPUB को XPS में परिवर्तित करने के लिए ConvertEPUB मेथड को कॉल करें
Converter.ConvertEPUB(stream, new Configuration(), options, savePath);





*DataDir - user input folder.

```

*OutputDir - user output folder.

### संबंधित देखें

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, XpsSaveOptions, String) {#convertepub_39}

इनपुट EPUB फ़ाइल पथ द्वारा प्रस्तुत epub स्रोत को xps में परिवर्तित करें। परिणाम पूर्ण पथ द्वारा परिभाषित xps फ़ाइल है।

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourcePath | String | EPUB स्रोत फ़ाइल पथ। इसे वर्तमान डायरेक्टरी पथ के साथ मिलाकर एक पूर्ण URL बनाया जाएगा। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) कॉन्टेक्स्ट ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | XpsSaveOptions | रूपांतरण विकल्प। [XpsSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions) ऑब्जेक्ट का उपयोग आपको रेंडरिंग प्रक्रिया को समायोजित करने की अनुमति देता है; आप पृष्ठ आकार, मार्जिन, CSS आदि निर्दिष्ट कर सकते हैं। |
| outputPath | String | .xps फ़ाइल का पूर्ण पथ आउटपुट रूपांतरण परिणाम के रूप में। |

## Remarks

EPUB को XPS में कैसे परिवर्तित करें

एक XPS फ़ाइल पृष्ठ लेआउट फ़ाइलों को दर्शाती है जो माइक्रोसॉफ्ट द्वारा बनाई गई XML पेपर स्पेसिफिकेशन्स पर आधारित हैं। इसे EMF फ़ाइल फ़ॉर्मेट के विकल्प के रूप में विकसित किया गया था और यह PDF फ़ॉर्मेट के समान है, लेकिन दस्तावेज़ के लेआउट, स्वरूप और प्रिंटिंग जानकारी में XML का उपयोग करता है।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें कैसे निष्पादित करें, इस बारे में जानकारी प्रदान करता है, जिसमें एक [`Converter`](../) क्लास का उपयोग किया गया है जो सभी लो-लेवल रूपांतरण ऑपरेशन्स को एक ही क्लास में समूहित करता है ताकि इसे आरामदायक और आसान उपयोग किया जा सके। EPUB कनवर्टर XPS विशिष्ट गाइड में, आप निम्नलिखित लेख पाएँगे:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

EPUB को XPS में परिवर्तित करें

EPUB को XPS फ़ाइल फ़ॉर्मेट में परिवर्तित करने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण के लिए, हम स्रोत फ़ाइल पथ को ConvertEPUB मेथड के पहले पैरामीटर के रूप में परिभाषित कर सकते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम ICreateStreamProvider इंटरफ़ेस कार्यान्वयन का उपयोग करें। हम परिणाम आउटपुट फ़ाइल पथ के रूप में अधिक सरल विकल्प का उपयोग कर सकते हैं। पृष्ठ आकार, मार्जिन, CSS आदि जैसे वांछित पैरामीटरों की संख्या के साथ एक नया XpsSaveOptions ऑब्जेक्ट बनाएं। XpsSaveOptions क्लास का डिफ़ॉल्ट इंस्टेंस उपयोग करना संभव है। EPUB को XPS फ़ाइल के रूप में सहेजने के लिए स्थिर Converter क्लास की ConvertEPUB() मेथड का उपयोग करें। रूपांतरण प्रक्रिया शुरू करने के लिए आपको EPUB स्रोत डेटा, XpsSaveOptions, और आउटपुट डेटा बफ़र को किसी भी रूप में पास करना होगा। आप उस कॉन्फ़िगरेशन का उपयोग कर सकते हैं जो [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है और एप्लिकेशन के पर्यावरण सेटिंग्स को सेट करने के लिए उपयोग किया जाता है। Online EPUB to XPS converter

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) कनवर्टर प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से EPUB को XPS फ़ाइल में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;
import com.aspose.html.saving;
import com.aspose.html.converters;
...
// फ़ॉर्म स्रोत फ़ाइल पथ
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// आउटपुट परिणाम फ़ाइल पथ बनाएं
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// डिफ़ॉल्ट विकल्प इंस्टेंस बनाएं  
var options = new XpsSaveOptions();

// डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);  
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

## ConvertEPUB(Url, Configuration, XpsSaveOptions, String) {#convertepub_7}

URL द्वारा प्रस्तुत epub स्रोत को पूर्ण पथ द्वारा परिभाषित xps फ़ाइल में परिवर्तित करें। देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/).

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceUrl | Url | EPUB स्रोत URL - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) कॉन्टेक्स्ट ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | XpsSaveOptions | रूपांतरण विकल्प। [XpsSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions) ऑब्जेक्ट का उपयोग आपको रेंडरिंग प्रक्रिया को समायोजित करने की अनुमति देता है; आप पृष्ठ आकार, मार्जिन, CSS आदि निर्दिष्ट कर सकते हैं। |
| outputPath | String | .xps फ़ाइल का पूर्ण पथ आउटपुट रूपांतरण परिणाम के रूप में। |

## Remarks

EPUB को XPS में कैसे परिवर्तित करें

एक XPS फ़ाइल पृष्ठ लेआउट फ़ाइलों को दर्शाती है जो माइक्रोसॉफ्ट द्वारा बनाई गई XML पेपर स्पेसिफिकेशन्स पर आधारित हैं। इसे EMF फ़ाइल फ़ॉर्मेट के विकल्प के रूप में विकसित किया गया था और यह PDF फ़ॉर्मेट के समान है, लेकिन दस्तावेज़ के लेआउट, स्वरूप और प्रिंटिंग जानकारी में XML का उपयोग करता है।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें कैसे निष्पादित करें, इस बारे में जानकारी प्रदान करता है, जिसमें एक [`Converter`](../) क्लास का उपयोग किया गया है जो सभी लो-लेवल रूपांतरण ऑपरेशन्स को एक ही क्लास में समूहित करता है ताकि इसे आरामदायक और आसान उपयोग किया जा सके। EPUB कनवर्टर XPS विशिष्ट गाइड में, आप निम्नलिखित लेख पाएँगे:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

EPUB को XPS में परिवर्तित करें

EPUB को XPS फ़ाइल फ़ॉर्मेट में परिवर्तित करने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण के लिए, हम स्रोत फ़ाइल पथ को ConvertEPUB मेथड के पहले पैरामीटर के रूप में परिभाषित कर सकते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम ICreateStreamProvider इंटरफ़ेस कार्यान्वयन का उपयोग करें। हम परिणाम आउटपुट फ़ाइल पथ के रूप में अधिक सरल विकल्प का उपयोग कर सकते हैं। पृष्ठ आकार, मार्जिन, CSS आदि जैसे वांछित पैरामीटरों की संख्या के साथ एक नया XpsSaveOptions ऑब्जेक्ट बनाएं। XpsSaveOptions क्लास का डिफ़ॉल्ट इंस्टेंस उपयोग करना संभव है। EPUB को XPS फ़ाइल के रूप में सहेजने के लिए स्थिर Converter क्लास की ConvertEPUB() मेथड का उपयोग करें। रूपांतरण प्रक्रिया शुरू करने के लिए आपको EPUB स्रोत डेटा, XpsSaveOptions, और आउटपुट डेटा बफ़र को किसी भी रूप में पास करना होगा। आप उस कॉन्फ़िगरेशन का उपयोग कर सकते हैं जो [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है और एप्लिकेशन के पर्यावरण सेटिंग्स को सेट करने के लिए उपयोग किया जाता है। Online EPUB to XPS converter

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) कनवर्टर प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से EPUB को XPS फ़ाइल में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;
import com.aspose.html.saving;
import com.aspose.html.converters;
...
// इनपुट फ़ाइल पथ द्वारा स्रोत URL बनाएं
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// आउटपुट परिणाम फ़ाइल पथ बनाएं
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// डिफ़ॉल्ट विकल्प इंस्टेंस बनाएं  
var options = new XpsSaveOptions();

// डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें 
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertEPUB(Stream, XpsSaveOptions, ICreateStreamProvider) {#convertepub_30}

इनपुट [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) द्वारा प्रस्तुत epub स्रोत को xps में परिवर्तित करें। परिणाम वह xps आउटपुट डेटा है जो ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा परिभाषित है।

```java
public static void ConvertEPUB(Stream stream, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | इनपुट स्ट्रीम को रूपांतरण स्रोत के रूप में उपयोग करें। |
| options | XpsSaveOptions | रूपांतरण विकल्प। [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट का उपयोग आपको रेंडरिंग प्रक्रिया को समायोजित करने की अनुमति देता है; आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) आदि निर्दिष्ट कर सकते हैं। |
| provider | ICreateStreamProvider | इंटरफ़ेस का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers) में ICreateStreamProvider कार्यान्वयन का उदाहरण देखें। |

## Remarks

EPUB को XPS में कैसे परिवर्तित करें

एक XPS फ़ाइल पृष्ठ लेआउट फ़ाइलों को दर्शाती है जो माइक्रोसॉफ्ट द्वारा बनाई गई XML पेपर स्पेसिफिकेशन्स पर आधारित हैं। इसे EMF फ़ाइल फ़ॉर्मेट के विकल्प के रूप में विकसित किया गया था और यह PDF फ़ॉर्मेट के समान है, लेकिन दस्तावेज़ के लेआउट, स्वरूप और प्रिंटिंग जानकारी में XML का उपयोग करता है।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें कैसे निष्पादित करें, इस बारे में जानकारी प्रदान करता है, जिसमें एक [`Converter`](../) क्लास का उपयोग किया गया है जो सभी लो-लेवल रूपांतरण ऑपरेशन्स को एक ही क्लास में समूहित करता है ताकि इसे आरामदायक और आसान उपयोग किया जा सके। EPUB कनवर्टर XPS विशिष्ट गाइड में, आप निम्नलिखित लेख पाएँगे:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

EPUB को XPS में परिवर्तित करें

EPUB को XPS फ़ाइल फ़ॉर्मेट में परिवर्तित करने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण के लिए, हम स्रोत फ़ाइल पथ को ConvertEPUB मेथड के पहले पैरामीटर के रूप में परिभाषित कर सकते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम ICreateStreamProvider इंटरफ़ेस कार्यान्वयन का उपयोग करें। हम परिणाम आउटपुट फ़ाइल पथ के रूप में अधिक सरल विकल्प का उपयोग कर सकते हैं। पृष्ठ आकार, मार्जिन, CSS आदि जैसे वांछित पैरामीटरों की संख्या के साथ एक नया XpsSaveOptions ऑब्जेक्ट बनाएं। XpsSaveOptions क्लास का डिफ़ॉल्ट इंस्टेंस उपयोग करना संभव है। EPUB को XPS फ़ाइल के रूप में सहेजने के लिए स्थिर Converter क्लास की ConvertEPUB() मेथड का उपयोग करें। रूपांतरण प्रक्रिया शुरू करने के लिए आपको EPUB स्रोत डेटा, XpsSaveOptions, और आउटपुट डेटा बफ़र को किसी भी रूप में पास करना होगा। आप उस कॉन्फ़िगरेशन का उपयोग कर सकते हैं जो [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है और एप्लिकेशन के पर्यावरण सेटिंग्स को सेट करने के लिए उपयोग किया जाता है। Online EPUB to XPS converter

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) कनवर्टर प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से EPUB को XPS फ़ाइल में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;
import Aspose.Html;
import System.Linq;
import com.aspose.html.converters;
import com.aspose.html.saving;
...
 // MemoryStreamProvider का एक इंस्टेंस बनाएं
 using var streamProvider = new MemoryStreamProvider();

 // पढ़ने के लिए एक मौजूदा EPUB फ़ाइल खोलें
 using var stream = File.OpenRead(DataDir + "input.epub");
  
 // परिवर्तित फ़ाइल को सहेजने के लिए पथ तैयार करें
 String savePath = Path.Combine(OutputDir, "stream-provider.xps");
  
 // MemoryStreamProvider क्लास का उपयोग करके EPUB को XPS में परिवर्तित करें
 Converter.ConvertEPUB(stream, new XpsSaveOptions(), streamProvider);
  
 // परिणाम डेटा को शामिल करने वाले मेमोरी स्ट्रीम तक पहुंच प्राप्त करें
 var memory = streamProvider.Streams.First();
 memory.Seek(0, SeekOrigin.Begin);

 // परिणाम डेटा को आउटपुट फ़ाइल में फ्लश करें
 using (FileStream fs = File.Create(savePath))
 {
  memory.CopyTo(fs);
 }
```

*DataDir - user source file path.

*OutputDir- user output file path.

*See MemoryStreamProvider class as ICreateStreamProvider implementation in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers).

### संबंधित देखें

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, XpsSaveOptions, ICreateStreamProvider) {#convertepub_46}

इनपुट EPUB फ़ाइल पथ द्वारा प्रस्तुत epub स्रोत को xps में परिवर्तित करें। परिणाम वह xps आउटपुट डेटा है जो ज्ञात या कस्टम [`ICreateStreamProvider `](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा परिभाषित है।

```java
public static void ConvertEPUB(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourcePath | String | EPUB स्रोत फ़ाइल पथ। इसे वर्तमान डायरेक्टरी पथ के साथ मिलाकर एक पूर्ण URL बनाया जाएगा। |
| options | XpsSaveOptions | रूपांतरण विकल्प। [XpsSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions) ऑब्जेक्ट का उपयोग आपको रेंडरिंग प्रक्रिया को समायोजित करने की अनुमति देता है; आप पृष्ठ आकार, मार्जिन, CSS आदि निर्दिष्ट कर सकते हैं। |
| provider | ICreateStreamProvider | इंटरफ़ेस का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers) में उन्नत उदाहरण देखें। |

## Remarks

EPUB को XPS में कैसे परिवर्तित करें

एक XPS फ़ाइल पृष्ठ लेआउट फ़ाइलों को दर्शाती है जो माइक्रोसॉफ्ट द्वारा बनाई गई XML पेपर स्पेसिफिकेशन्स पर आधारित हैं। इसे EMF फ़ाइल फ़ॉर्मेट के विकल्प के रूप में विकसित किया गया था और यह PDF फ़ॉर्मेट के समान है, लेकिन दस्तावेज़ के लेआउट, स्वरूप और प्रिंटिंग जानकारी में XML का उपयोग करता है।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें कैसे निष्पादित करें, इस बारे में जानकारी प्रदान करता है, जिसमें एक [`Converter`](../) क्लास का उपयोग किया गया है जो सभी लो-लेवल रूपांतरण ऑपरेशन्स को एक ही क्लास में समूहित करता है ताकि इसे आरामदायक और आसान उपयोग किया जा सके। EPUB कनवर्टर XPS विशिष्ट गाइड में, आप निम्नलिखित लेख पाएँगे:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

EPUB को XPS में परिवर्तित करें

EPUB को XPS फ़ाइल फ़ॉर्मेट में परिवर्तित करने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण के लिए, हम स्रोत फ़ाइल पथ को ConvertEPUB मेथड के पहले पैरामीटर के रूप में परिभाषित कर सकते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम ICreateStreamProvider इंटरफ़ेस कार्यान्वयन का उपयोग करें। हम परिणाम आउटपुट फ़ाइल पथ को एक सरल विकल्प के रूप में भी उपयोग कर सकते हैं। पृष्ठ आकार, मार्जिन, CSS आदि जैसे वांछित पैरामीटरों के साथ एक नया XpsSaveOptions ऑब्जेक्ट बनाएं। XpsSaveOptions क्लास का डिफ़ॉल्ट इंस्टेंस उपयोग करना संभव है। EPUB को XPS फ़ाइल के रूप में सहेजने के लिए स्थैतिक Converter क्लास की ConvertEPUB() मेथड का उपयोग करें। रूपांतरण प्रक्रिया शुरू करने के लिए आपको EPUB स्रोत डेटा, XpsSaveOptions, और आउटपुट डेटा बफ़र को किसी भी रूप में पास करना होगा। ऑनलाइन EPUB से XPS कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) कनवर्टर प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से EPUB को XPS फ़ाइल में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// फ़ॉर्म स्रोत फ़ाइल पथ
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// ICreateStreamProvider इंटरफ़ेस कार्यान्वयन देखें  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// डिफ़ॉल्ट विकल्प इंस्टेंस बनाएं  
var options = new XpsSaveOptions();

// डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
Converter.ConvertEPUB(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, XpsSaveOptions, ICreateStreamProvider) {#convertepub_14}

URL द्वारा प्रस्तुत epub स्रोत को पूर्ण पथ द्वारा परिभाषित xps फ़ाइल में परिवर्तित करें। परिणाम वह xps आउटपुट डेटा है जो ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा परिभाषित है।

```java
public static void ConvertEPUB(Url sourceUrl, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceUrl | Url | EPUB स्रोत URL - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| options | XpsSaveOptions | रूपांतरण विकल्प। [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट का उपयोग आपको रेंडरिंग प्रक्रिया को समायोजित करने की अनुमति देता है; आप पृष्ठ आकार, मार्जिन, CSS आदि निर्दिष्ट कर सकते हैं। देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#save-options)। |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers) में उन्नत उदाहरण देखें। |

## Remarks

EPUB को XPS में कैसे परिवर्तित करें

एक XPS फ़ाइल पृष्ठ लेआउट फ़ाइलों को दर्शाती है जो माइक्रोसॉफ्ट द्वारा बनाई गई XML पेपर स्पेसिफिकेशन्स पर आधारित हैं। इसे EMF फ़ाइल फ़ॉर्मेट के विकल्प के रूप में विकसित किया गया था और यह PDF फ़ॉर्मेट के समान है, लेकिन दस्तावेज़ के लेआउट, स्वरूप और प्रिंटिंग जानकारी में XML का उपयोग करता है।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें कैसे निष्पादित करें, इस बारे में जानकारी प्रदान करता है, जिसमें एक [`Converter`](../) क्लास का उपयोग किया गया है जो सभी लो-लेवल रूपांतरण ऑपरेशन्स को एक ही क्लास में समूहित करता है ताकि इसे आरामदायक और आसान उपयोग किया जा सके। EPUB कनवर्टर XPS विशिष्ट गाइड में, आप निम्नलिखित लेख पाएँगे:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

EPUB को XPS में परिवर्तित करें

EPUB को XPS फ़ाइल फ़ॉर्मेट में परिवर्तित करने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण के लिए, हम स्रोत फ़ाइल पथ को ConvertEPUB मेथड के पहले पैरामीटर के रूप में परिभाषित कर सकते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन का उपयोग करें। हम परिणाम आउटपुट फ़ाइल पथ के रूप में अधिक सरल विकल्प का उपयोग कर सकते हैं। पृष्ठ आकार, मार्जिन, CSS आदि जैसे वांछित पैरामीटरों की संख्या के साथ एक नया XpsSaveOptions ऑब्जेक्ट बनाएं। XpsSaveOptions क्लास का डिफ़ॉल्ट इंस्टेंस उपयोग करना संभव है। EPUB को XPS फ़ाइल के रूप में सहेजने के लिए स्थिर Converter क्लास की ConvertEPUB() मेथड का उपयोग करें। रूपांतरण प्रक्रिया शुरू करने के लिए आपको EPUB स्रोत डेटा, XpsSaveOptions, और आउटपुट डेटा बफ़र को किसी भी रूप में पास करना होगा। Online EPUB to XPS converter

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) कनवर्टर प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से EPUB को XPS फ़ाइल में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// इनपुट फ़ाइल पथ द्वारा स्रोत URL बनाएं
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// ICreateStreamProvider इंटरफ़ेस कार्यान्वयन देखें  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// डिफ़ॉल्ट विकल्प इंस्टेंस बनाएं  
var options = new XpsSaveOptions();

// रूपांतरण प्रक्रिया शुरू करें
Converter.ConvertEPUB(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertepub_22}

इनपुट [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) द्वारा प्रस्तुत epub स्रोत को xps में परिवर्तित करें। परिणाम वह xps आउटपुट डेटा है जो ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा परिभाषित है।

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | इनपुट स्ट्रीम को रूपांतरण स्रोत के रूप में उपयोग करें। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | XpsSaveOptions | रूपांतरण विकल्प। [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट का उपयोग आपको रेंडरिंग प्रक्रिया को समायोजित करने की अनुमति देता है; आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) आदि निर्दिष्ट कर सकते हैं। |
| provider | ICreateStreamProvider | `[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)` इंटरफ़ेस का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers) में उन्नत उदाहरण देखें। |

## Remarks

EPUB को XPS में कैसे परिवर्तित करें

एक XPS फ़ाइल पृष्ठ लेआउट फ़ाइलों को दर्शाती है जो माइक्रोसॉफ्ट द्वारा बनाई गई XML पेपर स्पेसिफिकेशन्स पर आधारित हैं। इसे EMF फ़ाइल फ़ॉर्मेट के विकल्प के रूप में विकसित किया गया था और यह PDF फ़ॉर्मेट के समान है, लेकिन दस्तावेज़ के लेआउट, स्वरूप और प्रिंटिंग जानकारी में XML का उपयोग करता है।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें कैसे निष्पादित करें, इस बारे में जानकारी प्रदान करता है, जिसमें एक [`Converter`](../) क्लास का उपयोग किया गया है जो सभी लो-लेवल रूपांतरण ऑपरेशन्स को एक ही क्लास में समूहित करता है ताकि इसे आरामदायक और आसान उपयोग किया जा सके। EPUB कनवर्टर XPS विशिष्ट गाइड में, आप निम्नलिखित लेख पाएँगे:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

EPUB को XPS में परिवर्तित करें

EPUB को XPS फ़ाइल फ़ॉर्मेट में परिवर्तित करने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण के लिए, हम स्रोत फ़ाइल पथ को ConvertEPUB मेथड के पहले पैरामीटर के रूप में परिभाषित कर सकते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन का उपयोग करें। हम परिणाम आउटपुट फ़ाइल पथ के रूप में अधिक सरल विकल्प का उपयोग कर सकते हैं। पृष्ठ आकार, मार्जिन, CSS आदि जैसे वांछित पैरामीटरों की संख्या के साथ एक नया XpsSaveOptions ऑब्जेक्ट बनाएं। XpsSaveOptions क्लास का डिफ़ॉल्ट इंस्टेंस उपयोग करना संभव है। EPUB को XPS फ़ाइल के रूप में सहेजने के लिए स्थिर Converter क्लास की ConvertEPUB() मेथड का उपयोग करें। रूपांतरण प्रक्रिया शुरू करने के लिए आपको EPUB स्रोत डेटा, XpsSaveOptions, और आउटपुट डेटा बफ़र को किसी भी रूप में पास करना होगा। आप उस कॉन्फ़िगरेशन का उपयोग कर सकते हैं जो [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है और एप्लिकेशन के पर्यावरण सेटिंग्स को सेट करने के लिए उपयोग किया जाता है। Online EPUB to XPS converter

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) कनवर्टर प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से EPUB को XPS फ़ाइल में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// स्ट्रीम के रूप में पढ़ने के लिए मौजूदा फ़ाइल खोलें  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// ICreateStreamProvider इंटरफ़ेस कार्यान्वयन देखें  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// डिफ़ॉल्ट विकल्प इंस्टेंस बनाएं  
var options = new XpsSaveOptions();

// डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);
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

## ConvertEPUB(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertepub_38}

इनपुट EPUB फ़ाइल पथ द्वारा प्रस्तुत epub स्रोत को xps में परिवर्तित करें। परिणाम वह xps आउटपुट डेटा है जो ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा परिभाषित है।

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourcePath | String | EPUB स्रोत फ़ाइल पथ। इसे वर्तमान डायरेक्टरी पथ के साथ मिलाकर एक पूर्ण URL बनाया जाएगा। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | XpsSaveOptions | रूपांतरण विकल्प। [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट का उपयोग आपको रेंडरिंग प्रक्रिया को समायोजित करने की अनुमति देता है; आप पृष्ठ आकार, मार्जिन, CSS आदि निर्दिष्ट कर सकते हैं। |
| provider | ICreateStreamProvider | `[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)` इंटरफ़ेस का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers) में उन्नत उदाहरण देखें। |

## Remarks

EPUB को XPS में कैसे परिवर्तित करें

एक XPS फ़ाइल पृष्ठ लेआउट फ़ाइलों को दर्शाती है जो माइक्रोसॉफ्ट द्वारा बनाई गई XML पेपर स्पेसिफिकेशन्स पर आधारित हैं। इसे EMF फ़ाइल फ़ॉर्मेट के विकल्प के रूप में विकसित किया गया था और यह PDF फ़ॉर्मेट के समान है, लेकिन दस्तावेज़ के लेआउट, स्वरूप और प्रिंटिंग जानकारी में XML का उपयोग करता है।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें कैसे निष्पादित करें, इस बारे में जानकारी प्रदान करता है, जिसमें एक [`Converter`](../) क्लास का उपयोग किया गया है जो सभी लो-लेवल रूपांतरण ऑपरेशन्स को एक ही क्लास में समूहित करता है ताकि इसे आरामदायक और आसान उपयोग किया जा सके। EPUB कनवर्टर XPS विशिष्ट गाइड में, आप निम्नलिखित लेख पाएँगे:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

EPUB को XPS में परिवर्तित करें

EPUB को XPS फ़ाइल फ़ॉर्मेट में परिवर्तित करने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण के लिए, हम स्रोत फ़ाइल पथ को ConvertEPUB मेथड के पहले पैरामीटर के रूप में परिभाषित कर सकते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम ICreateStreamProvider इंटरफ़ेस कार्यान्वयन का उपयोग करें। हम परिणाम आउटपुट फ़ाइल पथ के रूप में अधिक सरल विकल्प का उपयोग कर सकते हैं। पृष्ठ आकार, मार्जिन, CSS आदि जैसे वांछित पैरामीटरों की संख्या के साथ एक नया XpsSaveOptions ऑब्जेक्ट बनाएं। XpsSaveOptions क्लास का डिफ़ॉल्ट इंस्टेंस उपयोग करना संभव है। EPUB को XPS फ़ाइल के रूप में सहेजने के लिए स्थिर Converter क्लास की ConvertEPUB() मेथड का उपयोग करें। रूपांतरण प्रक्रिया शुरू करने के लिए आपको EPUB स्रोत डेटा, XpsSaveOptions, और आउटपुट डेटा बफ़र को किसी भी रूप में पास करना होगा। आप उस कॉन्फ़िगरेशन का उपयोग कर सकते हैं जो [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है और एप्लिकेशन के पर्यावरण सेटिंग्स को सेट करने के लिए उपयोग किया जाता है। Online EPUB to XPS converter

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) कनवर्टर प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से EPUB को XPS फ़ाइल में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// फ़ॉर्म स्रोत फ़ाइल पथ
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// ICreateStreamProvider इंटरफ़ेस कार्यान्वयन देखें  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// डिफ़ॉल्ट विकल्प इंस्टेंस बनाएं  
var options = new XpsSaveOptions();

// डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);
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

## ConvertEPUB(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertepub_6}

URL द्वारा प्रस्तुत epub स्रोत को पूर्ण पथ द्वारा परिभाषित xps फ़ाइल में परिवर्तित करें। परिणाम वह xps आउटपुट डेटा है जो ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा परिभाषित है।

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceUrl | Url | EPUB स्रोत URL - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | XpsSaveOptions | रूपांतरण विकल्प। [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट का उपयोग आपको रेंडरिंग प्रक्रिया को समायोजित करने की अनुमति देता है; आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) आदि निर्दिष्ट कर सकते हैं। देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#save-options)। |
| provider | ICreateStreamProvider | `[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)` इंटरफ़ेस का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers) में उन्नत उदाहरण देखें। |

## Remarks

EPUB को XPS में कैसे परिवर्तित करें

एक XPS फ़ाइल पृष्ठ लेआउट फ़ाइलों को दर्शाती है जो माइक्रोसॉफ्ट द्वारा बनाई गई XML पेपर स्पेसिफिकेशन्स पर आधारित हैं। इसे EMF फ़ाइल फ़ॉर्मेट के विकल्प के रूप में विकसित किया गया था और यह PDF फ़ॉर्मेट के समान है, लेकिन दस्तावेज़ के लेआउट, स्वरूप और प्रिंटिंग जानकारी में XML का उपयोग करता है।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें कैसे निष्पादित करें, इस बारे में जानकारी प्रदान करता है, जिसमें एक [`Converter`](../) क्लास का उपयोग किया गया है जो सभी लो-लेवल रूपांतरण ऑपरेशन्स को एक ही क्लास में समूहित करता है ताकि इसे आरामदायक और आसान उपयोग किया जा सके। EPUB कनवर्टर XPS विशिष्ट गाइड में, आप निम्नलिखित लेख पाएँगे:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

EPUB को XPS में परिवर्तित करें

EPUB को XPS फ़ाइल फ़ॉर्मेट में परिवर्तित करने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण के लिए, हम स्रोत फ़ाइल पथ को ConvertEPUB मेथड के पहले पैरामीटर के रूप में परिभाषित कर सकते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम ICreateStreamProvider इंटरफ़ेस कार्यान्वयन का उपयोग करें। हम परिणाम आउटपुट फ़ाइल पथ के रूप में अधिक सरल विकल्प का उपयोग कर सकते हैं। पृष्ठ आकार, मार्जिन, CSS आदि जैसे वांछित पैरामीटरों की संख्या के साथ एक नया XpsSaveOptions ऑब्जेक्ट बनाएं। XpsSaveOptions क्लास का डिफ़ॉल्ट इंस्टेंस उपयोग करना संभव है। EPUB को XPS फ़ाइल के रूप में सहेजने के लिए स्थिर Converter क्लास की ConvertEPUB() मेथड का उपयोग करें। रूपांतरण प्रक्रिया शुरू करने के लिए आपको EPUB स्रोत डेटा, XpsSaveOptions, और आउटपुट डेटा बफ़र को किसी भी रूप में पास करना होगा। आप उस कॉन्फ़िगरेशन का उपयोग कर सकते हैं जो [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है और एप्लिकेशन के पर्यावरण सेटिंग्स को सेट करने के लिए उपयोग किया जाता है। Online EPUB to XPS converter

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) कनवर्टर प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से EPUB को XPS फ़ाइल में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// इनपुट फ़ाइल पथ द्वारा स्रोत URL बनाएं
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// आउटपुट परिणाम फ़ाइल पथ बनाएं
var resultPath = Path.Combine(OutputFolder, " sample.xps");

// डिफ़ॉल्ट विकल्प इंस्टेंस बनाएं  
var options = new XpsSaveOptions();

// डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertEPUB(Stream, DocSaveOptions, String) {#convertepub_25}

पूर्ण पथ द्वारा प्रस्तुत EPUB स्रोत फ़ाइल को DOCX में परिवर्तित करें। परिणाम पूर्ण पथ द्वारा परिभाषित docx फ़ाइल है।

```java
public static void ConvertEPUB(Stream stream, DocSaveOptions options, String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | Stream | रूपांतरण स्रोत इनपुट [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) द्वारा प्रस्तुत किया गया है। |
| options | DocSaveOptions | रूपांतरण विकल्प। [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/)ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को समायोजित करने में सक्षम बनाता है; आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), आदि निर्दिष्ट कर सकते हैं। देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | .docx फ़ाइल का पूर्ण पथ आउटपुट रूपांतरण परिणाम के रूप में। |

## Remarks

EPUB को DOCX में कैसे बदलें

DOCX माइक्रोसॉफ्ट वर्ड दस्तावेज़ों के लिए एक प्रसिद्ध फ़ॉर्मेट है। यह फ़ॉर्मेट लोकप्रिय है क्योंकि यह विभिन्न फ़ॉर्मेटिंग सुविधाओं का समर्थन करता है और उपयोगकर्ताओं को किसी भी प्रकार के दस्तावेज़ लिखने के लिए कई विकल्प प्रदान करता है। DOCX फ़ाइलें वर्ड 2007 और उसके बाद के संस्करणों में खोली जा सकती हैं, लेकिन पुराने MS Word संस्करणों में नहीं, जो DOC फ़ाइल एक्सटेंशन का समर्थन करते हैं। EPUB से DOCX रूपांतरण अक्सर DOCX फ़ॉर्मेट का उपयोग विशेष उपयोगकर्ता कार्यों के लिए करने हेतु आवश्यक होता है।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें कैसे निष्पादित करें, इस बारे में जानकारी प्रदान करता है, जिसमें एक [`Converter`](../) क्लास का उपयोग किया जाता है जो सभी लो‑लेवल रूपांतरण ऑपरेशनों को एक ही क्लास में समूहित करता है ताकि वे आरामदायक और उपयोग में आसान हों। EPUB Converter DOCX विशिष्ट गाइड में, आप निम्नलिखित लेख पाएँगे:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB को DOCX में बदलें

EPUB को DOCX फ़ाइल फ़ॉर्मेट में बदलने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण के लिए, हम स्रोत फ़ाइल पथ को ConvertEPUB मेथड के पहले पैरामीटर के रूप में परिभाषित कर सकते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम ICreateStreamProvider इंटरफ़ेस कार्यान्वयन का उपयोग करें। हम परिणाम आउटपुट फ़ाइल पथ को एक सरल विकल्प के रूप में भी उपयोग कर सकते हैं। पेज साइज, मार्जिन, CSS आदि जैसे वांछित पैरामीटरों के साथ एक नया DocSaveOptions ऑब्जेक्ट बनाएँ। DocSaveOptions क्लास का डिफ़ॉल्ट इंस्टेंस उपयोग करना संभव है। EPUB को DOCX फ़ाइल के रूप में सहेजने के लिए स्थिर Converter क्लास की ConvertEPUB() मेथड का उपयोग करें। आपको EPUB स्रोत डेटा को फ़ाइल पथ या इनपुट स्ट्रीम के रूप में, साथ ही Url, DocSaveOptions इंस्टेंस, और आउटपुट डेटा बफ़र को किसी भी रूप में पास करना होगा ताकि रूपांतरण प्रक्रिया शुरू की जा सके। आप उस कॉन्फ़िगरेशन का उपयोग कर सकते हैं जो एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने हेतु उपयोग किया जाता है, यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट दर्शाता है। ऑनलाइन EPUB से DOCX कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) कनवर्टर प्रदान करता है जो EPUB को उच्च गुणवत्ता, आसान और तेज़ी से DOCX फ़ाइल में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// स्ट्रीम के रूप में पढ़ने के लिए मौजूदा फ़ाइल खोलें  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// आउटपुट परिणाम फ़ाइल पथ बनाएं
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// डिफ़ॉल्ट विकल्प इंस्टेंस बनाएं  
var options = new DocSaveOptions();   

// रूपांतरण प्रक्रिया शुरू करें
Converter.ConvertEPUB(inputStream, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, DocSaveOptions, String) {#convertepub_41}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत EPUB स्रोत को DOCX में परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित docx फ़ाइल है।

```java
public static void ConvertEPUB(String sourcePath, DocSaveOptions options, String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourcePath | String | इनपुट पैरामीटर के रूप में EPUB स्रोत फ़ाइल पथ। |
| options | DocSaveOptions | रूपांतरण विकल्प। [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/)ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को समायोजित करने में सक्षम बनाता है; आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/),[` margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), आदि निर्दिष्ट कर सकते हैं। देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | .docx फ़ाइल का पूर्ण पथ आउटपुट रूपांतरण परिणाम के रूप में। |

## Remarks

EPUB को DOCX में कैसे बदलें

DOCX माइक्रोसॉफ्ट वर्ड दस्तावेज़ों के लिए एक प्रसिद्ध फ़ॉर्मेट है। यह फ़ॉर्मेट लोकप्रिय है क्योंकि यह विभिन्न फ़ॉर्मेटिंग सुविधाओं का समर्थन करता है और उपयोगकर्ताओं को किसी भी प्रकार के दस्तावेज़ लिखने के लिए कई विकल्प प्रदान करता है। DOCX फ़ाइलें वर्ड 2007 और उसके बाद के संस्करणों में खोली जा सकती हैं, लेकिन पुराने MS Word संस्करणों में नहीं, जो DOC फ़ाइल एक्सटेंशन का समर्थन करते हैं। EPUB से DOCX रूपांतरण अक्सर DOCX फ़ॉर्मेट का उपयोग विशेष उपयोगकर्ता कार्यों के लिए करने हेतु आवश्यक होता है।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें कैसे निष्पादित करें, इस बारे में जानकारी प्रदान करता है, जिसमें एक [`Converter`](../) क्लास का उपयोग किया जाता है जो सभी लो‑लेवल रूपांतरण ऑपरेशनों को एक ही क्लास में समूहित करता है ताकि वे आरामदायक और उपयोग में आसान हों। EPUB Converter DOCX विशिष्ट गाइड में, आप निम्नलिखित लेख पाएँगे:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB को DOCX में बदलें

EPUB को DOCX फ़ाइल फ़ॉर्मेट में बदलने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण के लिए, हम स्रोत फ़ाइल पथ को ConvertEPUB मेथड के पहले पैरामीटर के रूप में परिभाषित कर सकते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम ICreateStreamProvider इंटरफ़ेस कार्यान्वयन का उपयोग करें। हम परिणाम आउटपुट फ़ाइल पथ को एक सरल विकल्प के रूप में भी उपयोग कर सकते हैं। पेज साइज, मार्जिन, CSS आदि जैसे वांछित पैरामीटरों के साथ एक नया DocSaveOptions ऑब्जेक्ट बनाएँ। DocSaveOptions क्लास का डिफ़ॉल्ट इंस्टेंस उपयोग करना संभव है। EPUB को DOCX फ़ाइल के रूप में सहेजने के लिए स्थिर Converter क्लास की ConvertEPUB() मेथड का उपयोग करें। आपको EPUB स्रोत डेटा को फ़ाइल पथ या इनपुट स्ट्रीम के रूप में, साथ ही Url, DocSaveOptions इंस्टेंस, और आउटपुट डेटा बफ़र को किसी भी रूप में पास करना होगा ताकि रूपांतरण प्रक्रिया शुरू की जा सके। आप उस कॉन्फ़िगरेशन का उपयोग कर सकते हैं जो एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने हेतु उपयोग किया जाता है, यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट दर्शाता है। ऑनलाइन EPUB से DOCX कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) कनवर्टर प्रदान करता है जो EPUB को उच्च गुणवत्ता, आसान और तेज़ी से DOCX फ़ाइल में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// फ़ॉर्म स्रोत फ़ाइल पथ
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// आउटपुट परिणाम फ़ाइल पथ बनाएं
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// डिफ़ॉल्ट विकल्प इंस्टेंस निर्धारित करें
var options = new DocSaveOptions();

// रूपांतरण प्रक्रिया शुरू करें
Converter.ConvertEPUB(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, DocSaveOptions, String) {#convertepub_9}

URL द्वारा प्रस्तुत EPUB स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित docx फ़ाइल है।

```java
public static void ConvertEPUB(Url sourceUrl, DocSaveOptions options, String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceUrl | Url | EPUB स्रोत URL - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) का उपयोग रेंडरिंग प्रक्रिया को समायोजित करने में सक्षम बनाता है; आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`resolutions`](../../../com.aspose.html.rendering.image/imagerenderingoptions/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), आदि निर्दिष्ट कर सकते हैं। देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | .docx फ़ाइल का पूर्ण पथ आउटपुट रूपांतरण परिणाम के रूप में। |

## Remarks

EPUB को DOCX में कैसे बदलें

DOCX माइक्रोसॉफ्ट वर्ड दस्तावेज़ों के लिए एक प्रसिद्ध फ़ॉर्मेट है। यह फ़ॉर्मेट लोकप्रिय है क्योंकि यह विभिन्न फ़ॉर्मेटिंग सुविधाओं का समर्थन करता है और उपयोगकर्ताओं को किसी भी प्रकार के दस्तावेज़ लिखने के लिए कई विकल्प प्रदान करता है। DOCX फ़ाइलें वर्ड 2007 और उसके बाद के संस्करणों में खोली जा सकती हैं, लेकिन पुराने MS Word संस्करणों में नहीं, जो DOC फ़ाइल एक्सटेंशन का समर्थन करते हैं। EPUB से DOCX रूपांतरण अक्सर DOCX फ़ॉर्मेट का उपयोग विशेष उपयोगकर्ता कार्यों के लिए करने हेतु आवश्यक होता है।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें कैसे निष्पादित करें, इस बारे में जानकारी प्रदान करता है, जिसमें एक [`Converter`](../) क्लास का उपयोग किया जाता है जो सभी लो‑लेवल रूपांतरण ऑपरेशनों को एक ही क्लास में समूहित करता है ताकि वे आरामदायक और उपयोग में आसान हों। EPUB Converter DOCX विशिष्ट गाइड में, आप निम्नलिखित लेख पाएँगे:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB को DOCX में बदलें

EPUB को DOCX फ़ाइल फ़ॉर्मेट में बदलने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण के लिए, हम स्रोत फ़ाइल पथ को ConvertEPUB मेथड के पहले पैरामीटर के रूप में परिभाषित कर सकते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम ICreateStreamProvider इंटरफ़ेस कार्यान्वयन का उपयोग करें। हम परिणाम आउटपुट फ़ाइल पथ को एक सरल विकल्प के रूप में भी उपयोग कर सकते हैं। पेज साइज, मार्जिन, CSS आदि जैसे वांछित पैरामीटरों के साथ एक नया DocSaveOptions ऑब्जेक्ट बनाएँ। DocSaveOptions क्लास का डिफ़ॉल्ट इंस्टेंस उपयोग करना संभव है। EPUB को DOCX फ़ाइल के रूप में सहेजने के लिए स्थिर Converter क्लास की ConvertEPUB() मेथड का उपयोग करें। आपको EPUB स्रोत डेटा को फ़ाइल पथ या इनपुट स्ट्रीम के रूप में, साथ ही Url, DocSaveOptions इंस्टेंस, और आउटपुट डेटा बफ़र को किसी भी रूप में पास करना होगा ताकि रूपांतरण प्रक्रिया शुरू की जा सके। आप उस कॉन्फ़िगरेशन का उपयोग कर सकते हैं जो एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने हेतु उपयोग किया जाता है, यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट दर्शाता है। ऑनलाइन EPUB से DOCX कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) कनवर्टर प्रदान करता है जो EPUB को उच्च गुणवत्ता, आसान और तेज़ी से DOCX फ़ाइल में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// इनपुट फ़ाइल पथ द्वारा स्रोत URL बनाएं
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// आउटपुट परिणाम फ़ाइल पथ बनाएं
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// डिफ़ॉल्ट विकल्प इंस्टेंस निर्धारित करें
var options = new DocSaveOptions();

// रूपांतरण प्रक्रिया शुरू करें
Converter.ConvertEPUB(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, DocSaveOptions, String) {#convertepub_17}

डेटा इनपुट स्ट्रीम द्वारा प्रस्तुत EPUB स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित docx फ़ाइल है।

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | इनपुट स्ट्रीम को रूपांतरण स्रोत के रूप में उपयोग करें। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | DocSaveOptions | रूपांतरण विकल्प। [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/)ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को समायोजित करने में सक्षम बनाता है; आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), आदि निर्दिष्ट कर सकते हैं। देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | .docx फ़ाइल का पूर्ण पथ आउटपुट रूपांतरण परिणाम के रूप में। |

## Remarks

EPUB को DOCX में कैसे बदलें

DOCX माइक्रोसॉफ्ट वर्ड दस्तावेज़ों के लिए एक प्रसिद्ध फ़ॉर्मेट है। यह फ़ॉर्मेट लोकप्रिय है क्योंकि यह विभिन्न फ़ॉर्मेटिंग सुविधाओं का समर्थन करता है और उपयोगकर्ताओं को किसी भी प्रकार के दस्तावेज़ लिखने के लिए कई विकल्प प्रदान करता है। DOCX फ़ाइलें वर्ड 2007 और उसके बाद के संस्करणों में खोली जा सकती हैं, लेकिन पुराने MS Word संस्करणों में नहीं, जो DOC फ़ाइल एक्सटेंशन का समर्थन करते हैं। EPUB से DOCX रूपांतरण अक्सर DOCX फ़ॉर्मेट का उपयोग विशेष उपयोगकर्ता कार्यों के लिए करने हेतु आवश्यक होता है।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें कैसे निष्पादित करें, इस बारे में जानकारी प्रदान करता है, जिसमें एक [`Converter`](../) क्लास का उपयोग किया जाता है जो सभी लो‑लेवल रूपांतरण ऑपरेशनों को एक ही क्लास में समूहित करता है ताकि वे आरामदायक और उपयोग में आसान हों। EPUB Converter DOCX विशिष्ट गाइड में, आप निम्नलिखित लेख पाएँगे:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB को DOCX में बदलें

EPUB को DOCX फ़ाइल फ़ॉर्मेट में बदलने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण के लिए, हम स्रोत फ़ाइल पथ को ConvertEPUB मेथड के पहले पैरामीटर के रूप में परिभाषित कर सकते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम ICreateStreamProvider इंटरफ़ेस कार्यान्वयन का उपयोग करें। हम परिणाम आउटपुट फ़ाइल पथ को एक सरल विकल्प के रूप में भी उपयोग कर सकते हैं। पेज साइज, मार्जिन, CSS आदि जैसे वांछित पैरामीटरों के साथ एक नया DocSaveOptions ऑब्जेक्ट बनाएँ। DocSaveOptions क्लास का डिफ़ॉल्ट इंस्टेंस उपयोग करना संभव है। EPUB को DOCX फ़ाइल के रूप में सहेजने के लिए स्थिर Converter क्लास की ConvertEPUB() मेथड का उपयोग करें। आपको EPUB स्रोत डेटा को फ़ाइल पथ या इनपुट स्ट्रीम के रूप में, साथ ही Url, DocSaveOptions इंस्टेंस, और आउटपुट डेटा बफ़र को किसी भी रूप में पास करना होगा ताकि रूपांतरण प्रक्रिया शुरू की जा सके। आप उस कॉन्फ़िगरेशन का उपयोग कर सकते हैं जो एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने हेतु उपयोग किया जाता है, यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट दर्शाता है। ऑनलाइन EPUB से DOCX कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) कनवर्टर प्रदान करता है जो EPUB को उच्च गुणवत्ता, आसान और तेज़ी से DOCX फ़ाइल में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// स्ट्रीम के रूप में पढ़ने के लिए मौजूदा फ़ाइल खोलें  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// आउटपुट परिणाम फ़ाइल पथ बनाएं
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// डिफ़ॉल्ट विकल्प इंस्टेंस बनाएं  
var options = new DocSaveOptions();   

// डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें 
Converter.ConvertEPUB(inputStream, new Configuration(), options, resultPath);
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

## ConvertEPUB(String, Configuration, DocSaveOptions, String) {#convertepub_33}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत EPUB स्रोत को DOCX में परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित docx फ़ाइल है।

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourcePath | String | EPUB स्रोत फ़ाइल पथ। इसे वर्तमान डायरेक्टरी पथ के साथ मिलाकर एक पूर्ण URL बनाया जाएगा। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | DocSaveOptions | रूपांतरण विकल्प। [DocSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/docsaveoptions)object उपयोग रेंडरिंग प्रक्रिया को समायोजित करने में सक्षम बनाता है; आप पेज साइज, मार्जिन, CSS, आदि निर्दिष्ट कर सकते हैं। देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | .docx फ़ाइल का पूर्ण पथ आउटपुट रूपांतरण परिणाम के रूप में। |

## Remarks

EPUB को DOCX में कैसे बदलें

DOCX माइक्रोसॉफ्ट वर्ड दस्तावेज़ों के लिए एक प्रसिद्ध फ़ॉर्मेट है। यह फ़ॉर्मेट लोकप्रिय है क्योंकि यह विभिन्न फ़ॉर्मेटिंग सुविधाओं का समर्थन करता है और उपयोगकर्ताओं को किसी भी प्रकार के दस्तावेज़ लिखने के लिए कई विकल्प प्रदान करता है। DOCX फ़ाइलें वर्ड 2007 और उसके बाद के संस्करणों में खोली जा सकती हैं, लेकिन पुराने MS Word संस्करणों में नहीं, जो DOC फ़ाइल एक्सटेंशन का समर्थन करते हैं। EPUB से DOCX रूपांतरण अक्सर DOCX फ़ॉर्मेट का उपयोग विशेष उपयोगकर्ता कार्यों के लिए करने हेतु आवश्यक होता है।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें कैसे निष्पादित करें, इस बारे में जानकारी प्रदान करता है, जिसमें एक [`Converter`](../) क्लास का उपयोग किया जाता है जो सभी लो‑लेवल रूपांतरण ऑपरेशनों को एक ही क्लास में समूहित करता है ताकि वे आरामदायक और उपयोग में आसान हों। EPUB Converter DOCX विशिष्ट गाइड में, आप निम्नलिखित लेख पाएँगे:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB को DOCX में बदलें

EPUB को DOCX फ़ाइल फ़ॉर्मेट में बदलने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण के लिए, हम स्रोत फ़ाइल पथ को ConvertEPUB मेथड के पहले पैरामीटर के रूप में परिभाषित कर सकते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम ICreateStreamProvider इंटरफ़ेस कार्यान्वयन का उपयोग करें। हम परिणाम आउटपुट फ़ाइल पथ को एक सरल विकल्प के रूप में भी उपयोग कर सकते हैं। पेज साइज, मार्जिन, CSS आदि जैसे वांछित पैरामीटरों के साथ एक नया DocSaveOptions ऑब्जेक्ट बनाएँ। DocSaveOptions क्लास का डिफ़ॉल्ट इंस्टेंस उपयोग करना संभव है। EPUB को DOCX फ़ाइल के रूप में सहेजने के लिए स्थिर Converter क्लास की ConvertEPUB() मेथड का उपयोग करें। आपको EPUB स्रोत डेटा को फ़ाइल पथ या इनपुट स्ट्रीम के रूप में, साथ ही Url, DocSaveOptions इंस्टेंस, और आउटपुट डेटा बफ़र को किसी भी रूप में पास करना होगा ताकि रूपांतरण प्रक्रिया शुरू की जा सके। आप उस कॉन्फ़िगरेशन का उपयोग कर सकते हैं जो एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने हेतु उपयोग किया जाता है, यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट दर्शाता है। ऑनलाइन EPUB से DOCX कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) कनवर्टर प्रदान करता है जो EPUB को उच्च गुणवत्ता, आसान और तेज़ी से DOCX फ़ाइल में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// फ़ॉर्म स्रोत फ़ाइल पथ
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// आउटपुट परिणाम फ़ाइल पथ बनाएं
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// डिफ़ॉल्ट विकल्प इंस्टेंस निर्धारित करें
var options = new DocSaveOptions();

// डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);
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

## ConvertEPUB(Url, Configuration, DocSaveOptions, String) {#convertepub_1}

URL द्वारा प्रस्तुत EPUB स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित docx फ़ाइल है।

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceUrl | Url | EPUB स्रोत URL - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) का उपयोग रेंडरिंग प्रक्रिया को समायोजित करने में सक्षम बनाता है; आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`resolutions`](../../../com.aspose.html.rendering.image/imagerenderingoptions/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), आदि निर्दिष्ट कर सकते हैं। देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | .docx फ़ाइल का पूर्ण पथ आउटपुट रूपांतरण परिणाम के रूप में। |

## Remarks

EPUB को DOCX में कैसे बदलें

DOCX माइक्रोसॉफ्ट वर्ड दस्तावेज़ों के लिए एक प्रसिद्ध फ़ॉर्मेट है। यह फ़ॉर्मेट लोकप्रिय है क्योंकि यह विभिन्न फ़ॉर्मेटिंग सुविधाओं का समर्थन करता है और उपयोगकर्ताओं को किसी भी प्रकार के दस्तावेज़ लिखने के लिए कई विकल्प प्रदान करता है। DOCX फ़ाइलें वर्ड 2007 और उसके बाद के संस्करणों में खोली जा सकती हैं, लेकिन पुराने MS Word संस्करणों में नहीं, जो DOC फ़ाइल एक्सटेंशन का समर्थन करते हैं। EPUB से DOCX रूपांतरण अक्सर DOCX फ़ॉर्मेट का उपयोग विशेष उपयोगकर्ता कार्यों के लिए करने हेतु आवश्यक होता है।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें कैसे निष्पादित करें, इस बारे में जानकारी प्रदान करता है, जिसमें एक [`Converter`](../) क्लास का उपयोग किया जाता है जो सभी लो‑लेवल रूपांतरण ऑपरेशनों को एक ही क्लास में समूहित करता है ताकि वे आरामदायक और उपयोग में आसान हों। EPUB Converter DOCX विशिष्ट गाइड में, आप निम्नलिखित लेख पाएँगे:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB को DOCX में बदलें

EPUB को DOCX फ़ाइल फ़ॉर्मेट में बदलने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण के लिए, हम स्रोत फ़ाइल पथ को ConvertEPUB मेथड के पहले पैरामीटर के रूप में परिभाषित कर सकते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम ICreateStreamProvider इंटरफ़ेस कार्यान्वयन का उपयोग करें। हम परिणाम आउटपुट फ़ाइल पथ को एक सरल विकल्प के रूप में भी उपयोग कर सकते हैं। पेज साइज, मार्जिन, CSS आदि जैसे वांछित पैरामीटरों के साथ एक नया DocSaveOptions ऑब्जेक्ट बनाएँ। DocSaveOptions क्लास का डिफ़ॉल्ट इंस्टेंस उपयोग करना संभव है। EPUB को DOCX फ़ाइल के रूप में सहेजने के लिए स्थिर Converter क्लास की ConvertEPUB() मेथड का उपयोग करें। आपको EPUB स्रोत डेटा को फ़ाइल पथ या इनपुट स्ट्रीम के रूप में, साथ ही Url, DocSaveOptions इंस्टेंस, और आउटपुट डेटा बफ़र को किसी भी रूप में पास करना होगा ताकि रूपांतरण प्रक्रिया शुरू की जा सके। आप उस कॉन्फ़िगरेशन का उपयोग कर सकते हैं जो एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने हेतु उपयोग किया जाता है, यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट दर्शाता है। ऑनलाइन EPUB से DOCX कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) कनवर्टर प्रदान करता है जो EPUB को उच्च गुणवत्ता, आसान और तेज़ी से DOCX फ़ाइल में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// इनपुट फ़ाइल पथ द्वारा स्रोत URL बनाएं
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// रूपांतरण परिणाम फ़ाइल पथ
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// डिफ़ॉल्ट विकल्प इंस्टेंस बनाएं  
var options = new DocSaveOptions();

// डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें।
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertEPUB(Stream, DocSaveOptions, ICreateStreamProvider) {#convertepub_24}

EPUB स्रोत को इनपुट स्ट्रीम के रूप में DOCX में परिवर्तित करें। परिणाम ICreateStreamProvider कार्यान्वयन द्वारा निर्मित docx फ़ाइल है।

```java
public static void ConvertEPUB(Stream stream, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | इनपुट स्ट्रीम को रूपांतरण स्रोत के रूप में उपयोग करें। |
| options | DocSaveOptions | रूपांतरण विकल्प। [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/)ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को समायोजित करने में सक्षम बनाता है; आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), आदि निर्दिष्ट कर सकते हैं। देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। देखें उन्नत उदाहरण [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Remarks

EPUB को DOCX में कैसे बदलें

DOCX माइक्रोसॉफ्ट वर्ड दस्तावेज़ों के लिए एक प्रसिद्ध फ़ॉर्मेट है। यह फ़ॉर्मेट लोकप्रिय है क्योंकि यह विभिन्न फ़ॉर्मेटिंग सुविधाओं का समर्थन करता है और उपयोगकर्ताओं को किसी भी प्रकार के दस्तावेज़ लिखने के लिए कई विकल्प प्रदान करता है। DOCX फ़ाइलें वर्ड 2007 और उसके बाद के संस्करणों में खोली जा सकती हैं, लेकिन पुराने MS Word संस्करणों में नहीं, जो DOC फ़ाइल एक्सटेंशन का समर्थन करते हैं। EPUB से DOCX रूपांतरण अक्सर DOCX फ़ॉर्मेट का उपयोग विशेष उपयोगकर्ता कार्यों के लिए करने हेतु आवश्यक होता है।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें कैसे निष्पादित करें, इस बारे में जानकारी प्रदान करता है, जिसमें एक [`Converter`](../) क्लास का उपयोग किया जाता है जो सभी लो‑लेवल रूपांतरण ऑपरेशनों को एक ही क्लास में समूहित करता है ताकि वे आरामदायक और उपयोग में आसान हों। EPUB Converter DOCX विशिष्ट गाइड में, आप निम्नलिखित लेख पाएँगे:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB को DOCX में बदलें

EPUB को DOCX फ़ाइल फ़ॉर्मेट में बदलने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण के लिए, हम स्रोत फ़ाइल पथ को ConvertEPUB मेथड के पहले पैरामीटर के रूप में परिभाषित कर सकते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम ICreateStreamProvider इंटरफ़ेस कार्यान्वयन का उपयोग करें। हम परिणाम आउटपुट फ़ाइल पथ को एक सरल विकल्प के रूप में भी उपयोग कर सकते हैं। पेज साइज, मार्जिन, CSS आदि जैसे वांछित पैरामीटरों के साथ एक नया DocSaveOptions ऑब्जेक्ट बनाएँ। DocSaveOptions क्लास का डिफ़ॉल्ट इंस्टेंस उपयोग करना संभव है। EPUB को DOCX फ़ाइल के रूप में सहेजने के लिए स्थिर Converter क्लास की ConvertEPUB() मेथड का उपयोग करें। आपको EPUB स्रोत डेटा को फ़ाइल पथ या इनपुट स्ट्रीम के रूप में, साथ ही Url, DocSaveOptions इंस्टेंस, और आउटपुट डेटा बफ़र को किसी भी रूप में पास करना होगा ताकि रूपांतरण प्रक्रिया शुरू की जा सके। आप उस कॉन्फ़िगरेशन का उपयोग कर सकते हैं जो एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने हेतु उपयोग किया जाता है, यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट दर्शाता है। ऑनलाइन EPUB से DOCX कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) कनवर्टर प्रदान करता है जो EPUB को उच्च गुणवत्ता, आसान और तेज़ी से DOCX फ़ाइल में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// स्ट्रीम के रूप में पढ़ने के लिए मौजूदा फ़ाइल खोलें  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// ICreateStreamProvider इंटरफ़ेस कार्यान्वयन देखें  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// डिफ़ॉल्ट विकल्प इंस्टेंस बनाएं  
var options = new DocSaveOptions();   

// रूपांतरण प्रक्रिया शुरू करें
Converter.ConvertEPUB(inputStream, options, sp);
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

## ConvertEPUB(String, DocSaveOptions, ICreateStreamProvider) {#convertepub_40}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत EPUB स्रोत को DOCX में बदलें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) कार्यान्वयन द्वारा निर्मित होता है।

```java
public static void ConvertEPUB(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourcePath | String | EPUB स्रोत फ़ाइल पथ। इसे वर्तमान डायरेक्टरी पथ के साथ मिलाकर एक पूर्ण URL बनाया जाएगा। |
| options | DocSaveOptions | रूपांतरण विकल्प। [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/)ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को समायोजित करने में सक्षम बनाता है; आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), आदि निर्दिष्ट कर सकते हैं। देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। देखें उन्नत उदाहरण [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Remarks

EPUB को DOCX में कैसे बदलें

DOCX माइक्रोसॉफ्ट वर्ड दस्तावेज़ों के लिए एक प्रसिद्ध फ़ॉर्मेट है। यह फ़ॉर्मेट लोकप्रिय है क्योंकि यह विभिन्न फ़ॉर्मेटिंग सुविधाओं का समर्थन करता है और उपयोगकर्ताओं को किसी भी प्रकार के दस्तावेज़ लिखने के लिए कई विकल्प प्रदान करता है। DOCX फ़ाइलें वर्ड 2007 और उसके बाद के संस्करणों में खोली जा सकती हैं, लेकिन पुराने MS Word संस्करणों में नहीं, जो DOC फ़ाइल एक्सटेंशन का समर्थन करते हैं। EPUB से DOCX रूपांतरण अक्सर DOCX फ़ॉर्मेट का उपयोग विशेष उपयोगकर्ता कार्यों के लिए करने हेतु आवश्यक होता है।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें कैसे निष्पादित करें, इस बारे में जानकारी प्रदान करता है, जिसमें एक [`Converter`](../) क्लास का उपयोग किया जाता है जो सभी लो‑लेवल रूपांतरण ऑपरेशनों को एक ही क्लास में समूहित करता है ताकि वे आरामदायक और उपयोग में आसान हों। EPUB Converter DOCX विशिष्ट गाइड में, आप निम्नलिखित लेख पाएँगे:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB को DOCX में बदलें

EPUB को DOCX फ़ाइल फ़ॉर्मेट में बदलने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण के लिए, हम स्रोत फ़ाइल पथ को ConvertEPUB मेथड के पहले पैरामीटर के रूप में परिभाषित कर सकते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम ICreateStreamProvider इंटरफ़ेस कार्यान्वयन का उपयोग करें। हम परिणाम आउटपुट फ़ाइल पथ को एक सरल विकल्प के रूप में भी उपयोग कर सकते हैं। पेज साइज, मार्जिन, CSS आदि जैसे वांछित पैरामीटरों के साथ एक नया DocSaveOptions ऑब्जेक्ट बनाएँ। DocSaveOptions क्लास का डिफ़ॉल्ट इंस्टेंस उपयोग करना संभव है। EPUB को DOCX फ़ाइल के रूप में सहेजने के लिए स्थिर Converter क्लास की ConvertEPUB() मेथड का उपयोग करें। आपको EPUB स्रोत डेटा को फ़ाइल पथ या इनपुट स्ट्रीम के रूप में, साथ ही Url, DocSaveOptions इंस्टेंस, और आउटपुट डेटा बफ़र को किसी भी रूप में पास करना होगा ताकि रूपांतरण प्रक्रिया शुरू की जा सके। आप उस कॉन्फ़िगरेशन का उपयोग कर सकते हैं जो एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने हेतु उपयोग किया जाता है, यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट दर्शाता है। ऑनलाइन EPUB से DOCX कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) कनवर्टर प्रदान करता है जो EPUB को उच्च गुणवत्ता, आसान और तेज़ी से DOCX फ़ाइल में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

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
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// ICreateStreamProvider इंटरफ़ेस कार्यान्वयन देखें  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// डिफ़ॉल्ट विकल्प इंस्टेंस बनाएं  
var options = new DocSaveOptions ();   

// रूपांतरण प्रक्रिया शुरू करें  
Converter.ConvertEPUB(sourcePath, options, sp);
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

## ConvertEPUB(Url, DocSaveOptions, ICreateStreamProvider) {#convertepub_8}

URL द्वारा प्रस्तुत EPUB स्रोत को परिवर्तित करें। परिणाम आउटपुट डेटा है जो ICreateStreamProvider इंटरफ़ेस कार्यान्वयन द्वारा बनाया गया है।

```java
public static void ConvertEPUB(Url sourceUrl, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceUrl | Url | EPUB स्रोत URL - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) का उपयोग रेंडरिंग प्रक्रिया को समायोजित करने में सक्षम बनाता है; आप पेज साइज, मार्जिन, रिज़ॉल्यूशन, CSS आदि निर्दिष्ट कर सकते हैं। देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। देखें उन्नत उदाहरण [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Remarks

EPUB को DOCX में कैसे बदलें

DOCX माइक्रोसॉफ्ट वर्ड दस्तावेज़ों के लिए एक प्रसिद्ध फ़ॉर्मेट है। यह फ़ॉर्मेट लोकप्रिय है क्योंकि यह विभिन्न फ़ॉर्मेटिंग सुविधाओं का समर्थन करता है और उपयोगकर्ताओं को किसी भी प्रकार के दस्तावेज़ लिखने के लिए कई विकल्प प्रदान करता है। DOCX फ़ाइलें वर्ड 2007 और उसके बाद के संस्करणों में खोली जा सकती हैं, लेकिन पुराने MS Word संस्करणों में नहीं, जो DOC फ़ाइल एक्सटेंशन का समर्थन करते हैं। EPUB से DOCX रूपांतरण अक्सर DOCX फ़ॉर्मेट का उपयोग विशेष उपयोगकर्ता कार्यों के लिए करने हेतु आवश्यक होता है।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें कैसे निष्पादित करें, इस बारे में जानकारी प्रदान करता है, जिसमें एक [`Converter`](../) क्लास का उपयोग किया जाता है जो सभी लो‑लेवल रूपांतरण ऑपरेशनों को एक ही क्लास में समूहित करता है ताकि वे आरामदायक और उपयोग में आसान हों। EPUB Converter DOCX विशिष्ट गाइड में, आप निम्नलिखित लेख पाएँगे:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB को DOCX में बदलें

EPUB को DOCX फ़ाइल फ़ॉर्मेट में बदलने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण के लिए, हम स्रोत फ़ाइल पथ को ConvertEPUB मेथड के पहले पैरामीटर के रूप में परिभाषित कर सकते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम ICreateStreamProvider इंटरफ़ेस कार्यान्वयन का उपयोग करें। हम परिणाम आउटपुट फ़ाइल पथ को एक सरल विकल्प के रूप में भी उपयोग कर सकते हैं। पेज साइज, मार्जिन, CSS आदि जैसे वांछित पैरामीटरों के साथ एक नया DocSaveOptions ऑब्जेक्ट बनाएँ। DocSaveOptions क्लास का डिफ़ॉल्ट इंस्टेंस उपयोग करना संभव है। EPUB को DOCX फ़ाइल के रूप में सहेजने के लिए स्थिर Converter क्लास की ConvertEPUB() मेथड का उपयोग करें। आपको EPUB स्रोत डेटा को फ़ाइल पथ या इनपुट स्ट्रीम के रूप में, साथ ही Url, DocSaveOptions इंस्टेंस, और आउटपुट डेटा बफ़र को किसी भी रूप में पास करना होगा ताकि रूपांतरण प्रक्रिया शुरू की जा सके। आप उस कॉन्फ़िगरेशन का उपयोग कर सकते हैं जो एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने हेतु उपयोग किया जाता है, यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट दर्शाता है। ऑनलाइन EPUB से DOCX कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) कनवर्टर प्रदान करता है जो EPUB को उच्च गुणवत्ता, आसान और तेज़ी से DOCX फ़ाइल में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// इनपुट फ़ाइल पथ द्वारा स्रोत URL बनाएं
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// ICreateStreamProvider इंटरफ़ेस कार्यान्वयन देखें  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// डिफ़ॉल्ट विकल्प इंस्टेंस बनाएं  
var options = new DocSaveOptions ();   

// रूपांतरण प्रक्रिया शुरू करें
Converter.ConvertEPUB(sourceUrl, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### संबंधित देखें

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertepub_16}

डेटा इनपुट स्ट्रीम द्वारा प्रस्तुत EPUB स्रोत को परिवर्तित करें। परिणाम आउटपुट डेटा है जो ICreateStreamProvider इंटरफ़ेस कार्यान्वयन द्वारा बनाया गया है।

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | इनपुट स्ट्रीम को रूपांतरण स्रोत के रूप में उपयोग करें। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) का उपयोग रेंडरिंग प्रक्रिया को समायोजित करने में सक्षम बनाता है; आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`resolutions`](../../../com.aspose.html.rendering.image/imagerenderingoptions/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), आदि निर्दिष्ट कर सकते हैं। देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। देखें उन्नत उदाहरण [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Remarks

EPUB को DOCX में कैसे बदलें

DOCX माइक्रोसॉफ्ट वर्ड दस्तावेज़ों के लिए एक प्रसिद्ध फ़ॉर्मेट है। यह फ़ॉर्मेट लोकप्रिय है क्योंकि यह विभिन्न फ़ॉर्मेटिंग सुविधाओं का समर्थन करता है और उपयोगकर्ताओं को किसी भी प्रकार के दस्तावेज़ लिखने के लिए कई विकल्प प्रदान करता है। DOCX फ़ाइलें वर्ड 2007 और उसके बाद के संस्करणों में खोली जा सकती हैं, लेकिन पुराने MS Word संस्करणों में नहीं, जो DOC फ़ाइल एक्सटेंशन का समर्थन करते हैं। EPUB से DOCX रूपांतरण अक्सर DOCX फ़ॉर्मेट का उपयोग विशेष उपयोगकर्ता कार्यों के लिए करने हेतु आवश्यक होता है।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें कैसे निष्पादित करें, इस बारे में जानकारी प्रदान करता है, जिसमें एक [`Converter`](../) क्लास का उपयोग किया जाता है जो सभी लो‑लेवल रूपांतरण ऑपरेशनों को एक ही क्लास में समूहित करता है ताकि वे आरामदायक और उपयोग में आसान हों। EPUB Converter DOCX विशिष्ट गाइड में, आप निम्नलिखित लेख पाएँगे:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB को DOCX में बदलें

EPUB को DOCX फ़ाइल फ़ॉर्मेट में बदलने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण के लिए, हम स्रोत फ़ाइल पथ को ConvertEPUB मेथड के पहले पैरामीटर के रूप में परिभाषित कर सकते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम ICreateStreamProvider इंटरफ़ेस कार्यान्वयन का उपयोग करें। हम परिणाम आउटपुट फ़ाइल पथ को एक सरल विकल्प के रूप में भी उपयोग कर सकते हैं। एक नया [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट बनाएँ जिसमें पेज साइज, मार्जिन, CSS आदि जैसे वांछित पैरामीटर हों। DocSaveOptions क्लास का डिफ़ॉल्ट इंस्टेंस उपयोग करना संभव है। स्थिर Converter क्लास की ConvertEPUB() मेथड का उपयोग करके EPUB को DOCX फ़ाइल के रूप में सहेजें। आपको EPUB स्रोत डेटा को फ़ाइल पथ या इनपुट स्ट्रीम के रूप में, साथ ही Url, DocSaveOptions इंस्टेंस, और आउटपुट डेटा बफ़र को किसी भी रूप में पास करना होगा ताकि रूपांतरण प्रक्रिया शुरू की जा सके। आप उस कॉन्फ़िगरेशन का उपयोग कर सकते हैं जो एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने हेतु उपयोग किया जाता है, यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट दर्शाता है। ऑनलाइन EPUB से DOCX कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) कनवर्टर प्रदान करता है जो EPUB को उच्च गुणवत्ता, आसान और तेज़ी से DOCX फ़ाइल में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// स्ट्रीम के रूप में पढ़ने के लिए मौजूदा फ़ाइल खोलें  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// ICreateStreamProvider इंटरफ़ेस कार्यान्वयन देखें  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// डिफ़ॉल्ट विकल्प इंस्टेंस बनाएं  
var options = new DocSaveOptions();   

// डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें 
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### संबंधित देखें

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertepub_32}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत EPUB स्रोत को DOCX में बदलें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित होता है।

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourcePath | String | EPUB स्रोत फ़ाइल पथ। इसे वर्तमान डायरेक्टरी पथ के साथ मिलाकर एक पूर्ण URL बनाया जाएगा। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | DocSaveOptions | रूपांतरण विकल्प। [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/)ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को समायोजित करने में सक्षम बनाता है; आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), आदि निर्दिष्ट कर सकते हैं। देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। देखें उन्नत उदाहरण [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Remarks

EPUB को DOCX में कैसे बदलें

DOCX माइक्रोसॉफ्ट वर्ड दस्तावेज़ों के लिए एक प्रसिद्ध फ़ॉर्मेट है। यह फ़ॉर्मेट लोकप्रिय है क्योंकि यह विभिन्न फ़ॉर्मेटिंग सुविधाओं का समर्थन करता है और उपयोगकर्ताओं को किसी भी प्रकार के दस्तावेज़ लिखने के लिए कई विकल्प प्रदान करता है। DOCX फ़ाइलें वर्ड 2007 और उसके बाद के संस्करणों में खोली जा सकती हैं, लेकिन पुराने MS Word संस्करणों में नहीं, जो DOC फ़ाइल एक्सटेंशन का समर्थन करते हैं। EPUB से DOCX रूपांतरण अक्सर DOCX फ़ॉर्मेट का उपयोग विशेष उपयोगकर्ता कार्यों के लिए करने हेतु आवश्यक होता है।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें कैसे निष्पादित करें, इस बारे में जानकारी प्रदान करता है, जिसमें एक [`Converter`](../) क्लास का उपयोग किया जाता है जो सभी लो‑लेवल रूपांतरण ऑपरेशनों को एक ही क्लास में समूहित करता है ताकि वे आरामदायक और उपयोग में आसान हों। EPUB Converter DOCX विशिष्ट गाइड में, आप निम्नलिखित लेख पाएँगे:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB को DOCX में बदलें

EPUB को DOCX फ़ाइल फ़ॉर्मेट में बदलने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण के लिए, हम स्रोत फ़ाइल पथ को ConvertEPUB मेथड के पहले पैरामीटर के रूप में परिभाषित कर सकते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम ICreateStreamProvider इंटरफ़ेस कार्यान्वयन का उपयोग करें। हम परिणाम आउटपुट फ़ाइल पथ को एक सरल विकल्प के रूप में भी उपयोग कर सकते हैं। एक नया [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट बनाएँ जिसमें पेज साइज, मार्जिन, CSS आदि जैसे वांछित पैरामीटर हों। DocSaveOptions क्लास का डिफ़ॉल्ट इंस्टेंस उपयोग करना संभव है। स्थिर Converter क्लास की ConvertEPUB() मेथड का उपयोग करके EPUB को DOCX फ़ाइल के रूप में सहेजें। आपको EPUB स्रोत डेटा को फ़ाइल पथ या इनपुट स्ट्रीम के रूप में, साथ ही Url, DocSaveOptions इंस्टेंस, और आउटपुट डेटा बफ़र को किसी भी रूप में पास करना होगा ताकि रूपांतरण प्रक्रिया शुरू की जा सके। आप उस कॉन्फ़िगरेशन का उपयोग कर सकते हैं जो एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने हेतु उपयोग किया जाता है, यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट दर्शाता है। ऑनलाइन EPUB से DOCX कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) कनवर्टर प्रदान करता है जो EPUB को उच्च गुणवत्ता, आसान और तेज़ी से DOCX फ़ाइल में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

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
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// ICreateStreamProvider इंटरफ़ेस कार्यान्वयन देखें  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// डिफ़ॉल्ट विकल्प इंस्टेंस बनाएं  
var options = new DocSaveOptions ();   

// रूपांतरण प्रक्रिया शुरू करें  
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);
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

## ConvertEPUB(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertepub}

URL द्वारा प्रस्तुत EPUB स्रोत को बदलें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित होता है।

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceUrl | Url | EPUB स्रोत URL - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) कॉन्टेक्स्ट ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) का उपयोग रेंडरिंग प्रक्रिया को समायोजित करने में सक्षम बनाता है; आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`resolutions`](../../../com.aspose.html.rendering.image/imagerenderingoptions/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), आदि निर्दिष्ट कर सकते हैं। देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। देखें उन्नत उदाहरण [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Remarks

EPUB को DOCX में कैसे बदलें

DOCX माइक्रोसॉफ्ट वर्ड दस्तावेज़ों के लिए एक प्रसिद्ध फ़ॉर्मेट है। यह फ़ॉर्मेट लोकप्रिय है क्योंकि यह विभिन्न फ़ॉर्मेटिंग सुविधाओं का समर्थन करता है और उपयोगकर्ताओं को किसी भी प्रकार के दस्तावेज़ लिखने के लिए कई विकल्प प्रदान करता है। DOCX फ़ाइलें वर्ड 2007 और उसके बाद के संस्करणों में खोली जा सकती हैं, लेकिन पुराने MS Word संस्करणों में नहीं, जो DOC फ़ाइल एक्सटेंशन का समर्थन करते हैं। EPUB से DOCX रूपांतरण अक्सर DOCX फ़ॉर्मेट का उपयोग विशेष उपयोगकर्ता कार्यों के लिए करने हेतु आवश्यक होता है।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें कैसे निष्पादित करें, इस बारे में जानकारी प्रदान करता है, जिसमें एक [`Converter`](../) क्लास का उपयोग किया जाता है जो सभी लो‑लेवल रूपांतरण ऑपरेशनों को एक ही क्लास में समूहित करता है ताकि वे आरामदायक और उपयोग में आसान हों। EPUB Converter DOCX विशिष्ट गाइड में, आप निम्नलिखित लेख पाएँगे:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB को DOCX में बदलें

EPUB को DOCX फ़ाइल फ़ॉर्मेट में बदलने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण के लिए, हम स्रोत फ़ाइल पथ को ConvertEPUB मेथड के पहले पैरामीटर के रूप में परिभाषित कर सकते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम ICreateStreamProvider इंटरफ़ेस कार्यान्वयन का उपयोग करें। हम परिणाम आउटपुट फ़ाइल पथ को एक सरल विकल्प के रूप में भी उपयोग कर सकते हैं। एक नया [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट बनाएँ जिसमें पेज साइज, मार्जिन, CSS आदि जैसे वांछित पैरामीटर हों। DocSaveOptions क्लास का डिफ़ॉल्ट इंस्टेंस उपयोग करना संभव है। स्थिर Converter क्लास की ConvertEPUB() मेथड का उपयोग करके EPUB को DOCX फ़ाइल के रूप में सहेजें। आपको EPUB स्रोत डेटा को फ़ाइल पथ या इनपुट स्ट्रीम के रूप में, साथ ही Url, DocSaveOptions इंस्टेंस, और आउटपुट डेटा बफ़र को किसी भी रूप में पास करना होगा ताकि रूपांतरण प्रक्रिया शुरू की जा सके। आप उस कॉन्फ़िगरेशन का उपयोग कर सकते हैं जो एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने हेतु उपयोग किया जाता है, यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट दर्शाता है। ऑनलाइन EPUB से DOCX कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) कनवर्टर प्रदान करता है जो EPUB को उच्च गुणवत्ता, आसान और तेज़ी से DOCX फ़ाइल में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

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
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// ICreateStreamProvider इंटरफ़ेस कार्यान्वयन देखें  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// डिफ़ॉल्ट विकल्प इंस्टेंस बनाएं  
var options = new DocSaveOptions();   

// डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें 
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, sp);





*InputFolder - user source file path.



```

*OutputFolder - user output file path.

### संबंधित देखें

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, PdfSaveOptions, String) {#convertepub_29}

डेटा इनपुट स्ट्रीम द्वारा प्रस्तुत EPUB स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित pdf फ़ाइल है।

```java
public static void ConvertEPUB(Stream stream, PdfSaveOptions options, String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | इनपुट पैरामीटर के रूप में EPUB स्रोत फ़ाइल पथ। |
| options | PdfSaveOptions | रूपांतरण विकल्प। [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/)ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को समायोजित करने में सक्षम बनाता है; आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), आदि निर्दिष्ट कर सकते हैं। देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | .pdf फ़ाइल का पूर्ण पथ आउटपुट रूपांतरण परिणाम के रूप में। |

## Remarks

EPUB को PDF में कैसे बदलें

EPUB एक ई‑बुक फ़ाइल फ़ॉर्मेट है जो एक मानक डिजिटल प्रकाशन फ़ॉर्मेट प्रदान करता है। इसे इंटरनेशनल डिजिटल पब्लिशिंग फ़ोरम ([IDPF](http://idpf.org/)) द्वारा बनाया गया है, और अब यह कई ई‑रीडर्स और सॉफ़्टवेयर एप्लिकेशनों द्वारा समर्थित है। EPUB से PDF रूपांतरण अक्सर PDF फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। PDF फ़ाइल फ़ॉर्मेट में टेक्स्ट, इमेज, हाइपरलिंक, फ़ॉर्म‑फ़ील्ड, रिच मीडिया, मेटाडेटा आदि जैसी जानकारी रखने की पूरी क्षमता होती है। PDF फ़ाइलें Adobe Acrobat Reader/Writer और अधिकांश आधुनिक ब्राउज़रों जैसे Chrome, Safari, Firefox में खोली जा सकती हैं। वे प्रिंटिंग के लिए अनुकूलित हैं, और आपके दस्तावेज़ों की भौतिक प्रतियां बनाने के लिए आदर्श हैं; आप PDF के लिए सुरक्षा सेटिंग्स भी कॉन्फ़िगर कर सकते हैं।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें एक [`Converter`](../) क्लास का उपयोग करके कैसे किया जाए, इस बारे में जानकारी प्रदान करता है, जो सभी लो‑लेवल रूपांतरण कार्यों को एक ही क्लास में समूहित करता है ताकि वे आरामदायक और उपयोग में आसान हों। EPUB Converter PDF विशिष्ट गाइड में, आप निम्न लेख पाएँगे:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB को PDF में बदलें

EPUB को PDF फ़ाइल फ़ॉर्मेट में बदलने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण के लिए, हम स्रोत फ़ाइल पथ को ConvertEPUB मेथड के पहले पैरामीटर के रूप में परिभाषित कर सकते हैं। वैकल्पिक रूप से हम इनपुट स्ट्रीम या Url ऑब्जेक्ट इंस्टेंस का उपयोग कर सकते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम ICreateStreamProvider इंटरफ़ेस इम्प्लीमेंटेशन का उपयोग करें। हम परिणाम आउटपुट फ़ाइल पथ को भी सरल विकल्प के रूप में उपयोग कर सकते हैं। पेज आकार, मार्जिन, CSS आदि जैसे वांछित पैरामीटरों के साथ एक नया PdfSaveOptions ऑब्जेक्ट बनाएँ। PdfSaveOptions क्लास का डिफ़ॉल्ट इंस्टेंस उपयोग करना संभव है। स्थैतिक Converter क्लास की ConvertEPUB() मेथड का उपयोग करके EPUB को PDF फ़ाइल के रूप में सहेजें। आपको EPUB स्रोत डेटा को फ़ाइल पथ या इनपुट स्ट्रीम के साथ-साथ Url, PdfSaveOptions इंस्टेंस, और आउटपुट डेटा बफ़र किसी भी रूप में पास करना होगा ताकि रूपांतरण प्रक्रिया शुरू हो सके। आप कॉन्फ़िगरेशन का उपयोग कर सकते हैं जो [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट का प्रतिनिधित्व करता है और एप्लिकेशन के पर्यावरण सेटिंग्स को सेट करने के लिए उपयोग किया जाता है। ऑनलाइन EPUB से PDF रूपांतरणकर्ता

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) कन्वर्टर प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से EPUB को PDF फ़ाइल में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// स्ट्रीम के रूप में पढ़ने के लिए मौजूदा फ़ाइल खोलें  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// फ़ॉर्म परिणाम फ़ाइल पथ  
var resultPath = Path.Combine(OutputFolder, "sample.pdf"));  

// डिफ़ॉल्ट विकल्प इंस्टेंस बनाएं  
var options = new PdfSaveOptions();   

// रूपांतरण प्रक्रिया शुरू करें  
Converter.ConvertEPUB(inputStream, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, PdfSaveOptions, String) {#convertepub_45}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत EPUB स्रोत को PDF में परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित pdf फ़ाइल है।

```java
public static void ConvertEPUB(String sourcePath, PdfSaveOptions options, String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourcePath | String | EPUB स्रोत फ़ाइल पथ। इसे वर्तमान डायरेक्टरी पथ के साथ मिलाकर एक पूर्ण URL बनाया जाएगा। |
| options | PdfSaveOptions | रूपांतरण विकल्प। [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/)ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को समायोजित करने में सक्षम बनाता है; आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), आदि निर्दिष्ट कर सकते हैं। देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | .pdf फ़ाइल का पूर्ण पथ आउटपुट रूपांतरण परिणाम के रूप में। |

## Remarks

EPUB को PDF में कैसे बदलें

EPUB एक ई‑बुक फ़ाइल फ़ॉर्मेट है जो एक मानक डिजिटल प्रकाशन फ़ॉर्मेट प्रदान करता है। इसे इंटरनेशनल डिजिटल पब्लिशिंग फ़ोरम ([IDPF](http://idpf.org/)) द्वारा बनाया गया है, और अब यह कई ई‑रीडर्स और सॉफ़्टवेयर एप्लिकेशनों द्वारा समर्थित है। EPUB से PDF रूपांतरण अक्सर PDF फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। PDF फ़ाइल फ़ॉर्मेट में टेक्स्ट, इमेज, हाइपरलिंक, फ़ॉर्म‑फ़ील्ड, रिच मीडिया, मेटाडेटा आदि जैसी जानकारी रखने की पूरी क्षमता होती है। PDF फ़ाइलें Adobe Acrobat Reader/Writer और अधिकांश आधुनिक ब्राउज़रों जैसे Chrome, Safari, Firefox में खोली जा सकती हैं। वे प्रिंटिंग के लिए अनुकूलित हैं, और आपके दस्तावेज़ों की भौतिक प्रतियां बनाने के लिए आदर्श हैं; आप PDF के लिए सुरक्षा सेटिंग्स भी कॉन्फ़िगर कर सकते हैं।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें एक [`Converter`](../) क्लास का उपयोग करके कैसे किया जाए, इस बारे में जानकारी प्रदान करता है, जो सभी लो‑लेवल रूपांतरण कार्यों को एक ही क्लास में समूहित करता है ताकि वे आरामदायक और उपयोग में आसान हों। EPUB Converter PDF विशिष्ट गाइड में, आप निम्न लेख पाएँगे:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB को PDF में बदलें

EPUB को PDF फ़ाइल फ़ॉर्मेट में बदलने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण के लिए, हम स्रोत फ़ाइल पथ को ConvertEPUB मेथड के पहले पैरामीटर के रूप में परिभाषित कर सकते हैं। वैकल्पिक रूप से हम इनपुट स्ट्रीम या Url ऑब्जेक्ट इंस्टेंस का उपयोग कर सकते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम ICreateStreamProvider इंटरफ़ेस इम्प्लीमेंटेशन का उपयोग करें। हम परिणाम आउटपुट फ़ाइल पथ को भी सरल विकल्प के रूप में उपयोग कर सकते हैं। पेज आकार, मार्जिन, CSS आदि जैसे वांछित पैरामीटरों के साथ एक नया PdfSaveOptions ऑब्जेक्ट बनाएँ। PdfSaveOptions क्लास का डिफ़ॉल्ट इंस्टेंस उपयोग करना संभव है। स्थैतिक Converter क्लास की ConvertEPUB() मेथड का उपयोग करके EPUB को PDF फ़ाइल के रूप में सहेजें। आपको EPUB स्रोत डेटा को फ़ाइल पथ या इनपुट स्ट्रीम के साथ-साथ Url, PdfSaveOptions इंस्टेंस, और आउटपुट डेटा बफ़र किसी भी रूप में पास करना होगा ताकि रूपांतरण प्रक्रिया शुरू हो सके। आप कॉन्फ़िगरेशन का उपयोग कर सकते हैं जो [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट का प्रतिनिधित्व करता है और एप्लिकेशन के पर्यावरण सेटिंग्स को सेट करने के लिए उपयोग किया जाता है। ऑनलाइन EPUB से PDF रूपांतरणकर्ता

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) कन्वर्टर प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से EPUB को PDF फ़ाइल में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// फ़ॉर्म स्रोत फ़ाइल पथ
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// आउटपुट परिणाम फ़ाइल पथ बनाएं
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// डिफ़ॉल्ट विकल्प इंस्टेंस निर्धारित करें
var options = new PdfSaveOptions();

// रूपांतरण प्रक्रिया शुरू करें
Converter.ConvertEPUB(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, PdfSaveOptions, String) {#convertepub_13}

URL द्वारा प्रस्तुत EPUB स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित pdf फ़ाइल है।

```java
public static void ConvertEPUB(Url sourceUrl, PdfSaveOptions options, String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceUrl | Url | EPUB स्रोत URL - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है; आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`file permissions`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) आदि निर्दिष्ट कर सकते हैं। देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options)। |
| outputPath | String | .pdf फ़ाइल का पूर्ण पथ आउटपुट रूपांतरण परिणाम के रूप में। |

## Remarks

EPUB को PDF में कैसे बदलें

EPUB एक ई‑बुक फ़ाइल फ़ॉर्मेट है जो एक मानक डिजिटल प्रकाशन फ़ॉर्मेट प्रदान करता है। इसे इंटरनेशनल डिजिटल पब्लिशिंग फ़ोरम ([IDPF](http://idpf.org/)) द्वारा बनाया गया है, और अब यह कई ई‑रीडर्स और सॉफ़्टवेयर एप्लिकेशनों द्वारा समर्थित है। EPUB से PDF रूपांतरण अक्सर PDF फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। PDF फ़ाइल फ़ॉर्मेट में टेक्स्ट, इमेज, हाइपरलिंक, फ़ॉर्म‑फ़ील्ड, रिच मीडिया, मेटाडेटा आदि जैसी जानकारी रखने की पूरी क्षमता होती है। PDF फ़ाइलें Adobe Acrobat Reader/Writer और अधिकांश आधुनिक ब्राउज़रों जैसे Chrome, Safari, Firefox में खोली जा सकती हैं। वे प्रिंटिंग के लिए अनुकूलित हैं, और आपके दस्तावेज़ों की भौतिक प्रतियां बनाने के लिए आदर्श हैं; आप PDF के लिए सुरक्षा सेटिंग्स भी कॉन्फ़िगर कर सकते हैं।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें एक [`Converter`](../) क्लास का उपयोग करके कैसे किया जाए, इस बारे में जानकारी प्रदान करता है, जो सभी लो‑लेवल रूपांतरण कार्यों को एक ही क्लास में समूहित करता है ताकि वे आरामदायक और उपयोग में आसान हों। EPUB Converter PDF विशिष्ट गाइड में, आप निम्न लेख पाएँगे:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB को PDF में बदलें

EPUB को PDF फ़ाइल फ़ॉर्मेट में बदलने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण के लिए, हम स्रोत फ़ाइल पथ को ConvertEPUB मेथड के पहले पैरामीटर के रूप में परिभाषित कर सकते हैं। वैकल्पिक रूप से हम इनपुट स्ट्रीम या Url ऑब्जेक्ट इंस्टेंस का उपयोग कर सकते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम ICreateStreamProvider इंटरफ़ेस इम्प्लीमेंटेशन का उपयोग करें। हम परिणाम आउटपुट फ़ाइल पथ को भी सरल विकल्प के रूप में उपयोग कर सकते हैं। पेज आकार, मार्जिन, CSS आदि जैसे वांछित पैरामीटरों के साथ एक नया PdfSaveOptions ऑब्जेक्ट बनाएँ। PdfSaveOptions क्लास का डिफ़ॉल्ट इंस्टेंस उपयोग करना संभव है। स्थैतिक Converter क्लास की ConvertEPUB() मेथड का उपयोग करके EPUB को PDF फ़ाइल के रूप में सहेजें। आपको EPUB स्रोत डेटा को फ़ाइल पथ या इनपुट स्ट्रीम के साथ-साथ Url, PdfSaveOptions इंस्टेंस, और आउटपुट डेटा बफ़र किसी भी रूप में पास करना होगा ताकि रूपांतरण प्रक्रिया शुरू हो सके। आप कॉन्फ़िगरेशन का उपयोग कर सकते हैं जो [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट का प्रतिनिधित्व करता है और एप्लिकेशन के पर्यावरण सेटिंग्स को सेट करने के लिए उपयोग किया जाता है। ऑनलाइन EPUB से PDF रूपांतरणकर्ता

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) कन्वर्टर प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से EPUB को PDF फ़ाइल में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;
import com.aspose.html.saving;  
import com.aspose.html.converters; 

// इनपुट फ़ाइल पथ के आधार पर URL बनाएं
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// आउटपुट परिणाम फ़ाइल पथ बनाएं
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// डिफ़ॉल्ट विकल्प इंस्टेंस निर्धारित करें
var options = new com.aspose.html.saving.PdfSaveOptions();

// रूपांतरण प्रक्रिया शुरू करें
Converter.ConvertEPUB(sourceUrl, options, resultPath);
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

## ConvertEPUB(Stream, Configuration, PdfSaveOptions, String) {#convertepub_21}

डेटा इनपुट स्ट्रीम द्वारा प्रस्तुत EPUB स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित pdf फ़ाइल है।

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | इनपुट स्ट्रीम को रूपांतरण स्रोत के रूप में उपयोग करें। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | PdfSaveOptions | रूपांतरण विकल्प। [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/)ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को समायोजित करने में सक्षम बनाता है; आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), आदि निर्दिष्ट कर सकते हैं। देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | .pdf फ़ाइल का पूर्ण पथ आउटपुट रूपांतरण परिणाम के रूप में। |

## Remarks

EPUB को PDF में कैसे बदलें

EPUB एक ई‑बुक फ़ाइल फ़ॉर्मेट है जो एक मानक डिजिटल प्रकाशन फ़ॉर्मेट प्रदान करता है। इसे इंटरनेशनल डिजिटल पब्लिशिंग फ़ोरम ([IDPF](http://idpf.org/)) द्वारा बनाया गया है, और अब यह कई ई‑रीडर्स और सॉफ़्टवेयर एप्लिकेशनों द्वारा समर्थित है। EPUB से PDF रूपांतरण अक्सर PDF फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। PDF फ़ाइल फ़ॉर्मेट में टेक्स्ट, इमेज, हाइपरलिंक, फ़ॉर्म‑फ़ील्ड, रिच मीडिया, मेटाडेटा आदि जैसी जानकारी रखने की पूरी क्षमता होती है। PDF फ़ाइलें Adobe Acrobat Reader/Writer और अधिकांश आधुनिक ब्राउज़रों जैसे Chrome, Safari, Firefox में खोली जा सकती हैं। वे प्रिंटिंग के लिए अनुकूलित हैं, और आपके दस्तावेज़ों की भौतिक प्रतियां बनाने के लिए आदर्श हैं; आप PDF के लिए सुरक्षा सेटिंग्स भी कॉन्फ़िगर कर सकते हैं।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें एक [`Converter`](../) क्लास का उपयोग करके कैसे किया जाए, इस बारे में जानकारी प्रदान करता है, जो सभी लो‑लेवल रूपांतरण कार्यों को एक ही क्लास में समूहित करता है ताकि वे आरामदायक और उपयोग में आसान हों। EPUB Converter PDF विशिष्ट गाइड में, आप निम्न लेख पाएँगे:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB को PDF में बदलें

EPUB को PDF फ़ाइल फ़ॉर्मेट में बदलने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण के लिए, हम स्रोत फ़ाइल पथ को ConvertEPUB मेथड के पहले पैरामीटर के रूप में परिभाषित कर सकते हैं। वैकल्पिक रूप से हम इनपुट स्ट्रीम या Url ऑब्जेक्ट इंस्टेंस का उपयोग कर सकते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम ICreateStreamProvider इंटरफ़ेस इम्प्लीमेंटेशन का उपयोग करें। हम परिणाम आउटपुट फ़ाइल पथ को भी सरल विकल्प के रूप में उपयोग कर सकते हैं। पेज आकार, मार्जिन, CSS आदि जैसे वांछित पैरामीटरों के साथ एक नया PdfSaveOptions ऑब्जेक्ट बनाएँ। PdfSaveOptions क्लास का डिफ़ॉल्ट इंस्टेंस उपयोग करना संभव है। स्थैतिक Converter क्लास की ConvertEPUB() मेथड का उपयोग करके EPUB को PDF फ़ाइल के रूप में सहेजें। आपको EPUB स्रोत डेटा को फ़ाइल पथ या इनपुट स्ट्रीम के साथ-साथ Url, PdfSaveOptions इंस्टेंस, और आउटपुट डेटा बफ़र किसी भी रूप में पास करना होगा ताकि रूपांतरण प्रक्रिया शुरू हो सके। आप कॉन्फ़िगरेशन का उपयोग कर सकते हैं जो [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट का प्रतिनिधित्व करता है और एप्लिकेशन के पर्यावरण सेटिंग्स को सेट करने के लिए उपयोग किया जाता है। ऑनलाइन EPUB से PDF रूपांतरणकर्ता

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) कन्वर्टर प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से EPUB को PDF फ़ाइल में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// स्ट्रीम के रूप में पढ़ने के लिए मौजूदा फ़ाइल खोलें  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// फ़ॉर्म परिणाम फ़ाइल पथ  
var resultPath = Path.Combine(OutputFolder, "sample.pdf"));  

// डिफ़ॉल्ट विकल्प इंस्टेंस बनाएं  
var options = new PdfSaveOptions();   

// डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें 
Converter.ConvertEPUB(inputStream, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### संबंधित देखें

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, PdfSaveOptions, String) {#convertepub_37}

डेटा इनपुट स्ट्रीम द्वारा प्रस्तुत EPUB स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित pdf फ़ाइल है।

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourcePath | String | EPUB स्रोत फ़ाइल पथ। इसे वर्तमान डायरेक्टरी पथ के साथ मिलाकर एक पूर्ण URL बनाया जाएगा। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | PdfSaveOptions | रूपांतरण विकल्प। [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/)ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को समायोजित करने में सक्षम बनाता है; आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), आदि निर्दिष्ट कर सकते हैं। देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | .pdf फ़ाइल का पूर्ण पथ आउटपुट रूपांतरण परिणाम के रूप में। |

## Remarks

EPUB को PDF में कैसे बदलें

EPUB एक ई‑बुक फ़ाइल फ़ॉर्मेट है जो एक मानक डिजिटल प्रकाशन फ़ॉर्मेट प्रदान करता है। इसे इंटरनेशनल डिजिटल पब्लिशिंग फ़ोरम ([IDPF](http://idpf.org/)) द्वारा बनाया गया है, और अब यह कई ई‑रीडर्स और सॉफ़्टवेयर एप्लिकेशनों द्वारा समर्थित है। EPUB से PDF रूपांतरण अक्सर PDF फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। PDF फ़ाइल फ़ॉर्मेट में टेक्स्ट, इमेज, हाइपरलिंक, फ़ॉर्म‑फ़ील्ड, रिच मीडिया, मेटाडेटा आदि जैसी जानकारी रखने की पूरी क्षमता होती है। PDF फ़ाइलें Adobe Acrobat Reader/Writer और अधिकांश आधुनिक ब्राउज़रों जैसे Chrome, Safari, Firefox में खोली जा सकती हैं। वे प्रिंटिंग के लिए अनुकूलित हैं, और आपके दस्तावेज़ों की भौतिक प्रतियां बनाने के लिए आदर्श हैं; आप PDF के लिए सुरक्षा सेटिंग्स भी कॉन्फ़िगर कर सकते हैं।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें एक [`Converter`](../) क्लास का उपयोग करके कैसे किया जाए, इस बारे में जानकारी प्रदान करता है, जो सभी लो‑लेवल रूपांतरण कार्यों को एक ही क्लास में समूहित करता है ताकि वे आरामदायक और उपयोग में आसान हों। EPUB Converter PDF विशिष्ट गाइड में, आप निम्न लेख पाएँगे:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB को PDF में बदलें

EPUB को PDF फ़ाइल फ़ॉर्मेट में बदलने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण के लिए, हम स्रोत फ़ाइल पथ को ConvertEPUB मेथड के पहले पैरामीटर के रूप में परिभाषित कर सकते हैं। वैकल्पिक रूप से हम इनपुट स्ट्रीम या Url ऑब्जेक्ट इंस्टेंस का उपयोग कर सकते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम ICreateStreamProvider इंटरफ़ेस इम्प्लीमेंटेशन का उपयोग करें। हम परिणाम आउटपुट फ़ाइल पथ को भी सरल विकल्प के रूप में उपयोग कर सकते हैं। पेज आकार, मार्जिन, CSS आदि जैसे वांछित पैरामीटरों के साथ एक नया PdfSaveOptions ऑब्जेक्ट बनाएँ। PdfSaveOptions क्लास का डिफ़ॉल्ट इंस्टेंस उपयोग करना संभव है। स्थैतिक Converter क्लास की ConvertEPUB() मेथड का उपयोग करके EPUB को PDF फ़ाइल के रूप में सहेजें। आपको EPUB स्रोत डेटा को फ़ाइल पथ या इनपुट स्ट्रीम के साथ-साथ Url, PdfSaveOptions इंस्टेंस, और आउटपुट डेटा बफ़र किसी भी रूप में पास करना होगा ताकि रूपांतरण प्रक्रिया शुरू हो सके। आप कॉन्फ़िगरेशन का उपयोग कर सकते हैं जो [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट का प्रतिनिधित्व करता है और एप्लिकेशन के पर्यावरण सेटिंग्स को सेट करने के लिए उपयोग किया जाता है। ऑनलाइन EPUB से PDF रूपांतरणकर्ता

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) कन्वर्टर प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से EPUB को PDF फ़ाइल में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// फ़ॉर्म स्रोत फ़ाइल पथ
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// आउटपुट परिणाम फ़ाइल पथ बनाएं
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// डिफ़ॉल्ट विकल्प इंस्टेंस निर्धारित करें
var options = new PdfSaveOptions();

// डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### संबंधित देखें

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, Configuration, PdfSaveOptions, String) {#convertepub_5}

URL द्वारा प्रस्तुत EPUB स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित pdf फ़ाइल है।

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceUrl | Url | EPUB स्रोत URL - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) कॉन्टेक्स्ट ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है; आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`file permissions`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) आदि निर्दिष्ट कर सकते हैं। देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options)। |
| outputPath | String | .pdf फ़ाइल का पूर्ण पथ आउटपुट रूपांतरण परिणाम के रूप में। |

## Remarks

EPUB को PDF में कैसे बदलें

EPUB एक ई‑बुक फ़ाइल फ़ॉर्मेट है जो एक मानक डिजिटल प्रकाशन फ़ॉर्मेट प्रदान करता है। इसे इंटरनेशनल डिजिटल पब्लिशिंग फ़ोरम ([IDPF](http://idpf.org/)) द्वारा बनाया गया है, और अब यह कई ई‑रीडर्स और सॉफ़्टवेयर एप्लिकेशनों द्वारा समर्थित है। EPUB से PDF रूपांतरण अक्सर PDF फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। PDF फ़ाइल फ़ॉर्मेट में टेक्स्ट, इमेज, हाइपरलिंक, फ़ॉर्म‑फ़ील्ड, रिच मीडिया, मेटाडेटा आदि जैसी जानकारी रखने की पूरी क्षमता होती है। PDF फ़ाइलें Adobe Acrobat Reader/Writer और अधिकांश आधुनिक ब्राउज़रों जैसे Chrome, Safari, Firefox में खोली जा सकती हैं। वे प्रिंटिंग के लिए अनुकूलित हैं, और आपके दस्तावेज़ों की भौतिक प्रतियां बनाने के लिए आदर्श हैं; आप PDF के लिए सुरक्षा सेटिंग्स भी कॉन्फ़िगर कर सकते हैं।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें एक [`Converter`](../) क्लास का उपयोग करके कैसे किया जाए, इस बारे में जानकारी प्रदान करता है, जो सभी लो‑लेवल रूपांतरण कार्यों को एक ही क्लास में समूहित करता है ताकि वे आरामदायक और उपयोग में आसान हों। EPUB Converter PDF विशिष्ट गाइड में, आप निम्न लेख पाएँगे:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB को PDF में बदलें

EPUB को PDF फ़ाइल फ़ॉर्मेट में बदलने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण के लिए, हम स्रोत फ़ाइल पथ को ConvertEPUB मेथड के पहले पैरामीटर के रूप में परिभाषित कर सकते हैं। वैकल्पिक रूप से हम इनपुट स्ट्रीम या Url ऑब्जेक्ट इंस्टेंस का उपयोग कर सकते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम ICreateStreamProvider इंटरफ़ेस इम्प्लीमेंटेशन का उपयोग करें। हम परिणाम आउटपुट फ़ाइल पथ को भी सरल विकल्प के रूप में उपयोग कर सकते हैं। पेज आकार, मार्जिन, CSS आदि जैसे वांछित पैरामीटरों के साथ एक नया PdfSaveOptions ऑब्जेक्ट बनाएँ। PdfSaveOptions क्लास का डिफ़ॉल्ट इंस्टेंस उपयोग करना संभव है। स्थैतिक Converter क्लास की ConvertEPUB() मेथड का उपयोग करके EPUB को PDF फ़ाइल के रूप में सहेजें। आपको EPUB स्रोत डेटा को फ़ाइल पथ या इनपुट स्ट्रीम के साथ-साथ Url, PdfSaveOptions इंस्टेंस, और आउटपुट डेटा बफ़र किसी भी रूप में पास करना होगा ताकि रूपांतरण प्रक्रिया शुरू हो सके। आप कॉन्फ़िगरेशन का उपयोग कर सकते हैं जो [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट का प्रतिनिधित्व करता है और एप्लिकेशन के पर्यावरण सेटिंग्स को सेट करने के लिए उपयोग किया जाता है। ऑनलाइन EPUB से PDF रूपांतरणकर्ता

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) कन्वर्टर प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से EPUB को PDF फ़ाइल में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

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
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// आउटपुट परिणाम फ़ाइल पथ बनाएं
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// डिफ़ॉल्ट विकल्प इंस्टेंस निर्धारित करें
var options = new PdfSaveOptions();

// डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.



```

*OutputFolder - user output file path.

### संबंधित देखें

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, PdfSaveOptions, ICreateStreamProvider) {#convertepub_28}

डेटा इनपुट स्ट्रीम द्वारा प्रस्तुत EPUB स्रोत को बदलें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस इम्प्लीमेंटेशन द्वारा निर्मित होता है।

```java
public static void ConvertEPUB(Stream stream, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | इनपुट स्ट्रीम को रूपांतरण स्रोत के रूप में उपयोग करें। |
| options | PdfSaveOptions | रूपांतरण विकल्प। [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/)ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को समायोजित करने में सक्षम बनाता है; आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), आदि निर्दिष्ट कर सकते हैं। देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | ज्ञात (देखें [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन। |

## Remarks

EPUB को PDF में कैसे बदलें

EPUB एक ई‑बुक फ़ाइल फ़ॉर्मेट है जो एक मानक डिजिटल प्रकाशन फ़ॉर्मेट प्रदान करता है। इसे इंटरनेशनल डिजिटल पब्लिशिंग फ़ोरम ([IDPF](http://idpf.org/)) द्वारा बनाया गया है, और अब यह कई ई‑रीडर्स और सॉफ़्टवेयर एप्लिकेशनों द्वारा समर्थित है। EPUB से PDF रूपांतरण अक्सर PDF फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। PDF फ़ाइल फ़ॉर्मेट में टेक्स्ट, इमेज, हाइपरलिंक, फ़ॉर्म‑फ़ील्ड, रिच मीडिया, मेटाडेटा आदि जैसी जानकारी रखने की पूरी क्षमता होती है। PDF फ़ाइलें Adobe Acrobat Reader/Writer और अधिकांश आधुनिक ब्राउज़रों जैसे Chrome, Safari, Firefox में खोली जा सकती हैं। वे प्रिंटिंग के लिए अनुकूलित हैं, और आपके दस्तावेज़ों की भौतिक प्रतियां बनाने के लिए आदर्श हैं; आप PDF के लिए सुरक्षा सेटिंग्स भी कॉन्फ़िगर कर सकते हैं।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें एक [`Converter`](../) क्लास का उपयोग करके कैसे किया जाए, इस बारे में जानकारी प्रदान करता है, जो सभी लो‑लेवल रूपांतरण कार्यों को एक ही क्लास में समूहित करता है ताकि वे आरामदायक और उपयोग में आसान हों। EPUB Converter PDF विशिष्ट गाइड में, आप निम्न लेख पाएँगे:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB को PDF में बदलें

EPUB को PDF फ़ाइल फ़ॉर्मेट में बदलने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण के लिए, हम स्रोत फ़ाइल पथ को ConvertEPUB मेथड के पहले पैरामीटर के रूप में परिभाषित कर सकते हैं। वैकल्पिक रूप से हम इनपुट स्ट्रीम या Url ऑब्जेक्ट इंस्टेंस का उपयोग कर सकते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम ICreateStreamProvider इंटरफ़ेस इम्प्लीमेंटेशन का उपयोग करें। हम परिणाम आउटपुट फ़ाइल पथ को भी सरल विकल्प के रूप में उपयोग कर सकते हैं। पेज आकार, मार्जिन, CSS आदि जैसे वांछित पैरामीटरों के साथ एक नया PdfSaveOptions ऑब्जेक्ट बनाएँ। PdfSaveOptions क्लास का डिफ़ॉल्ट इंस्टेंस उपयोग करना संभव है। स्थैतिक Converter क्लास की ConvertEPUB() मेथड का उपयोग करके EPUB को PDF फ़ाइल के रूप में सहेजें। आपको EPUB स्रोत डेटा को फ़ाइल पथ या इनपुट स्ट्रीम के साथ-साथ Url, PdfSaveOptions इंस्टेंस, और आउटपुट डेटा बफ़र किसी भी रूप में पास करना होगा ताकि रूपांतरण प्रक्रिया शुरू हो सके। आप कॉन्फ़िगरेशन का उपयोग कर सकते हैं जो [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट का प्रतिनिधित्व करता है और एप्लिकेशन के पर्यावरण सेटिंग्स को सेट करने के लिए उपयोग किया जाता है। ऑनलाइन EPUB से PDF रूपांतरणकर्ता

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) कन्वर्टर प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से EPUB को PDF फ़ाइल में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// स्ट्रीम के रूप में पढ़ने के लिए मौजूदा फ़ाइल खोलें  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// ICreateStreamProvider इंटरफ़ेस कार्यान्वयन देखें  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// डिफ़ॉल्ट विकल्प इंस्टेंस बनाएं  
var options = new PdfSaveOptions ();   

// रूपांतरण प्रक्रिया शुरू करें  
Converter.ConvertEPUB(inputStream, options, sp);
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

## ConvertEPUB(String, PdfSaveOptions, ICreateStreamProvider) {#convertepub_44}

पूरा फ़ाइल पथ द्वारा प्रस्तुत EPUB स्रोत को PDF में बदलें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस इम्प्लीमेंटेशन द्वारा निर्मित होता है।

```java
public static void ConvertEPUB(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourcePath | String | EPUB स्रोत फ़ाइल पथ। इसे वर्तमान डायरेक्टरी पथ के साथ मिलाकर एक पूर्ण URL बनाया जाएगा। |
| options | PdfSaveOptions | रूपांतरण विकल्प। [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/)ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को समायोजित करने में सक्षम बनाता है; आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), आदि निर्दिष्ट कर सकते हैं। देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। उन्नत उदाहरण के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers)। |

## Remarks

EPUB को PDF में कैसे बदलें

EPUB एक ई‑बुक फ़ाइल फ़ॉर्मेट है जो एक मानक डिजिटल प्रकाशन फ़ॉर्मेट प्रदान करता है। इसे इंटरनेशनल डिजिटल पब्लिशिंग फ़ोरम ([IDPF](http://idpf.org/)) द्वारा बनाया गया है, और अब यह कई ई‑रीडर्स और सॉफ़्टवेयर एप्लिकेशनों द्वारा समर्थित है। EPUB से PDF रूपांतरण अक्सर PDF फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। PDF फ़ाइल फ़ॉर्मेट में टेक्स्ट, इमेज, हाइपरलिंक, फ़ॉर्म‑फ़ील्ड, रिच मीडिया, मेटाडेटा आदि जैसी जानकारी रखने की पूरी क्षमता होती है। PDF फ़ाइलें Adobe Acrobat Reader/Writer और अधिकांश आधुनिक ब्राउज़रों जैसे Chrome, Safari, Firefox में खोली जा सकती हैं। वे प्रिंटिंग के लिए अनुकूलित हैं, और आपके दस्तावेज़ों की भौतिक प्रतियां बनाने के लिए आदर्श हैं; आप PDF के लिए सुरक्षा सेटिंग्स भी कॉन्फ़िगर कर सकते हैं।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें एक [`Converter`](../) क्लास का उपयोग करके कैसे किया जाए, इस बारे में जानकारी प्रदान करता है, जो सभी लो‑लेवल रूपांतरण कार्यों को एक ही क्लास में समूहित करता है ताकि वे आरामदायक और उपयोग में आसान हों। EPUB Converter PDF विशिष्ट गाइड में, आप निम्न लेख पाएँगे:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB को PDF में बदलें

EPUB को PDF फ़ाइल फ़ॉर्मेट में बदलने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण के लिए, हम स्रोत फ़ाइल पथ को ConvertEPUB मेथड के पहले पैरामीटर के रूप में परिभाषित कर सकते हैं। वैकल्पिक रूप से हम इनपुट स्ट्रीम या Url ऑब्जेक्ट इंस्टेंस का उपयोग कर सकते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम ICreateStreamProvider इंटरफ़ेस इम्प्लीमेंटेशन का उपयोग करें। हम परिणाम आउटपुट फ़ाइल पथ को भी सरल विकल्प के रूप में उपयोग कर सकते हैं। पेज आकार, मार्जिन, CSS आदि जैसे वांछित पैरामीटरों के साथ एक नया PdfSaveOptions ऑब्जेक्ट बनाएँ। PdfSaveOptions क्लास का डिफ़ॉल्ट इंस्टेंस उपयोग करना संभव है। स्थैतिक Converter क्लास की ConvertEPUB() मेथड का उपयोग करके EPUB को PDF फ़ाइल के रूप में सहेजें। आपको EPUB स्रोत डेटा को फ़ाइल पथ या इनपुट स्ट्रीम के साथ-साथ Url, PdfSaveOptions इंस्टेंस, और आउटपुट डेटा बफ़र किसी भी रूप में पास करना होगा ताकि रूपांतरण प्रक्रिया शुरू हो सके। आप कॉन्फ़िगरेशन का उपयोग कर सकते हैं जो [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट का प्रतिनिधित्व करता है और एप्लिकेशन के पर्यावरण सेटिंग्स को सेट करने के लिए उपयोग किया जाता है। ऑनलाइन EPUB से PDF रूपांतरणकर्ता

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) कन्वर्टर प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से EPUB को PDF फ़ाइल में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

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
var sourcePath = Path.Combine(InputFolder, "sample.epub");  

// ICreateStreamProvider इंटरफ़ेस कार्यान्वयन देखें  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// डिफ़ॉल्ट विकल्प इंस्टेंस बनाएं  
var options = new PdfSaveOptions();   

// रूपांतरण प्रक्रिया शुरू करें  
Converter.ConvertEPUB(sourcePath, options, sp);
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

## ConvertEPUB(Url, PdfSaveOptions, ICreateStreamProvider) {#convertepub_12}

URL द्वारा प्रस्तुत EPUB स्रोत को बदलें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित होता है।

```java
public static void ConvertEPUB(Url sourceUrl, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceUrl | Url | EPUB स्रोत URL - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है; आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`file permissions`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) आदि निर्दिष्ट कर सकते हैं। देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options)। |
| provider | ICreateStreamProvider | [ICreateStreamProvider](https://apireference.aspose.com/svg/net/aspose.svg.io/icreatestreamprovider) इंटरफ़ेस का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। उन्नत उदाहरण के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers)। |

## Remarks

EPUB को PDF में कैसे बदलें

EPUB एक ई‑बुक फ़ाइल फ़ॉर्मेट है जो एक मानक डिजिटल प्रकाशन फ़ॉर्मेट प्रदान करता है। इसे इंटरनेशनल डिजिटल पब्लिशिंग फ़ोरम ([IDPF](http://idpf.org/)) द्वारा बनाया गया है, और अब यह कई ई‑रीडर्स और सॉफ़्टवेयर एप्लिकेशनों द्वारा समर्थित है। EPUB से PDF रूपांतरण अक्सर PDF फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। PDF फ़ाइल फ़ॉर्मेट में टेक्स्ट, इमेज, हाइपरलिंक, फ़ॉर्म‑फ़ील्ड, रिच मीडिया, मेटाडेटा आदि जैसी जानकारी रखने की पूरी क्षमता होती है। PDF फ़ाइलें Adobe Acrobat Reader/Writer और अधिकांश आधुनिक ब्राउज़रों जैसे Chrome, Safari, Firefox में खोली जा सकती हैं। वे प्रिंटिंग के लिए अनुकूलित हैं, और आपके दस्तावेज़ों की भौतिक प्रतियां बनाने के लिए आदर्श हैं; आप PDF के लिए सुरक्षा सेटिंग्स भी कॉन्फ़िगर कर सकते हैं।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें एक [`Converter`](../) क्लास का उपयोग करके कैसे किया जाए, इस बारे में जानकारी प्रदान करता है, जो सभी लो‑लेवल रूपांतरण कार्यों को एक ही क्लास में समूहित करता है ताकि वे आरामदायक और उपयोग में आसान हों। EPUB Converter PDF विशिष्ट गाइड में, आप निम्न लेख पाएँगे:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB को PDF में बदलें

EPUB को PDF फ़ाइल फ़ॉर्मेट में बदलने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण के लिए, हम स्रोत फ़ाइल पथ को ConvertEPUB मेथड के पहले पैरामीटर के रूप में परिभाषित कर सकते हैं। वैकल्पिक रूप से हम इनपुट स्ट्रीम या Url ऑब्जेक्ट इंस्टेंस का उपयोग कर सकते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम ICreateStreamProvider इंटरफ़ेस इम्प्लीमेंटेशन का उपयोग करें। हम परिणाम आउटपुट फ़ाइल पथ को भी सरल विकल्प के रूप में उपयोग कर सकते हैं। पेज आकार, मार्जिन, CSS आदि जैसे वांछित पैरामीटरों के साथ एक नया PdfSaveOptions ऑब्जेक्ट बनाएँ। PdfSaveOptions क्लास का डिफ़ॉल्ट इंस्टेंस उपयोग करना संभव है। स्थैतिक Converter क्लास की ConvertEPUB() मेथड का उपयोग करके EPUB को PDF फ़ाइल के रूप में सहेजें। आपको EPUB स्रोत डेटा को फ़ाइल पथ या इनपुट स्ट्रीम के साथ-साथ Url, PdfSaveOptions इंस्टेंस, और आउटपुट डेटा बफ़र किसी भी रूप में पास करना होगा ताकि रूपांतरण प्रक्रिया शुरू हो सके। आप कॉन्फ़िगरेशन का उपयोग कर सकते हैं जो [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट का प्रतिनिधित्व करता है और एप्लिकेशन के पर्यावरण सेटिंग्स को सेट करने के लिए उपयोग किया जाता है। ऑनलाइन EPUB से PDF रूपांतरणकर्ता

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) कन्वर्टर प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से EPUB को PDF फ़ाइल में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

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
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// ICreateStreamProvider इंटरफ़ेस कार्यान्वयन देखें  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));

// डिफ़ॉल्ट विकल्प इंस्टेंस निर्धारित करें
var options = new PdfSaveOptions();

// रूपांतरण प्रक्रिया शुरू करें
Converter.ConvertEPUB(sourceUrl, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### संबंधित देखें

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertepub_20}

डेटा इनपुट स्ट्रीम द्वारा प्रस्तुत EPUB स्रोत को बदलें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस इम्प्लीमेंटेशन द्वारा निर्मित होता है।

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | इनपुट स्ट्रीम को रूपांतरण स्रोत के रूप में उपयोग करें। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) संदर्भ ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | PdfSaveOptions | रूपांतरण विकल्प। [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/)ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को समायोजित करने में सक्षम बनाता है; आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), आदि निर्दिष्ट कर सकते हैं। देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। उन्नत उदाहरण के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers)। |

## Remarks

EPUB को PDF में कैसे बदलें

EPUB एक ई‑बुक फ़ाइल फ़ॉर्मेट है जो एक मानक डिजिटल प्रकाशन फ़ॉर्मेट प्रदान करता है। इसे इंटरनेशनल डिजिटल पब्लिशिंग फ़ोरम ([IDPF](http://idpf.org/)) द्वारा बनाया गया है, और अब यह कई ई‑रीडर्स और सॉफ़्टवेयर एप्लिकेशनों द्वारा समर्थित है। EPUB से PDF रूपांतरण अक्सर PDF फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। PDF फ़ाइल फ़ॉर्मेट में टेक्स्ट, इमेज, हाइपरलिंक, फ़ॉर्म‑फ़ील्ड, रिच मीडिया, मेटाडेटा आदि जैसी जानकारी रखने की पूरी क्षमता होती है। PDF फ़ाइलें Adobe Acrobat Reader/Writer और अधिकांश आधुनिक ब्राउज़रों जैसे Chrome, Safari, Firefox में खोली जा सकती हैं। वे प्रिंटिंग के लिए अनुकूलित हैं, और आपके दस्तावेज़ों की भौतिक प्रतियां बनाने के लिए आदर्श हैं; आप PDF के लिए सुरक्षा सेटिंग्स भी कॉन्फ़िगर कर सकते हैं।

Aspose.HTML की मुख्य विशेषता रूपांतरण फ़ीचर है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल पुस्तकों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। [`com.aspose.html.converters`](../) पैकेज रूपांतरण मेथड्स तक आसान पहुँच प्रदान करता है। यह विभिन्न लोकप्रिय फ़ॉर्मेट्स जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में व्यापक [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें एक [`Converter`](../) क्लास का उपयोग करके कैसे किया जाए, इस बारे में जानकारी प्रदान करता है, जो सभी लो‑लेवल रूपांतरण कार्यों को एक ही क्लास में समूहित करता है ताकि वे आरामदायक और उपयोग में आसान हों। EPUB Converter PDF विशिष्ट गाइड में, आप निम्न लेख पाएँगे:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB को PDF में बदलें

EPUB को PDF फ़ाइल फ़ॉर्मेट में बदलने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण के लिए, हम स्रोत फ़ाइल पथ को ConvertEPUB मेथड के पहले पैरामीटर के रूप में परिभाषित कर सकते हैं। वैकल्पिक रूप से हम इनपुट स्ट्रीम या Url ऑब्जेक्ट इंस्टेंस का उपयोग कर सकते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम ICreateStreamProvider इंटरफ़ेस इम्प्लीमेंटेशन का उपयोग करें। हम परिणाम आउटपुट फ़ाइल पथ को भी सरल विकल्प के रूप में उपयोग कर सकते हैं। पेज आकार, मार्जिन, CSS आदि जैसे वांछित पैरामीटरों के साथ एक नया PdfSaveOptions ऑब्जेक्ट बनाएँ। PdfSaveOptions क्लास का डिफ़ॉल्ट इंस्टेंस उपयोग करना संभव है। स्थैतिक Converter क्लास की ConvertEPUB() मेथड का उपयोग करके EPUB को PDF फ़ाइल के रूप में सहेजें। आपको EPUB स्रोत डेटा को फ़ाइल पथ या इनपुट स्ट्रीम के साथ-साथ Url, PdfSaveOptions इंस्टेंस, और आउटपुट डेटा बफ़र किसी भी रूप में पास करना होगा ताकि रूपांतरण प्रक्रिया शुरू हो सके। आप कॉन्फ़िगरेशन का उपयोग कर सकते हैं जो [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट का प्रतिनिधित्व करता है और एप्लिकेशन के पर्यावरण सेटिंग्स को सेट करने के लिए उपयोग किया जाता है। ऑनलाइन EPUB से PDF रूपांतरणकर्ता

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) कन्वर्टर प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से EPUB को PDF फ़ाइल में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// स्ट्रीम के रूप में पढ़ने के लिए मौजूदा फ़ाइल खोलें  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// ICreateStreamProvider इंटरफ़ेस कार्यान्वयन देखें  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// डिफ़ॉल्ट विकल्प इंस्टेंस बनाएं  
var options = new PdfSaveOptions ();   

// डिफ़ॉल्ट कॉन्फ़िगरेशन ऑब्जेक्ट के साथ रूपांतरण प्रक्रिया शुरू करें  
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);
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

## ConvertEPUB(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertepub_36}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत EPUB स्रोत को PDF में परिवर्तित करें। परिणाम आउटपुट डेटा है जो ICreateStreamProvider इंटरफ़ेस कार्यान्वयन द्वारा बनाया गया है।

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourcePath | String | EPUB स्रोत फ़ाइल पथ। इसे वर्तमान डायरेक्टरी पथ के साथ मिलाकर एक पूर्ण URL बनाया जाएगा। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) कॉन्टेक्स्ट ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | PdfSaveOptions | रूपांतरण विकल्प। [PdfSaveOption](https://apireference.aspose.com/html/net/aspose.html.saving/pdfsaveoptions) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है; आप पेज आकार, मार्जिन, CSS आदि निर्दिष्ट कर सकते हैं। देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options)। |
| provider | ICreateStreamProvider | [ICreateStreamProvider](https://apireference.aspose.com/svg/net/aspose.svg.io/icreatestreamprovider) इंटरफ़ेस का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। उन्नत उदाहरण के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers)। |

## Remarks

EPUB को PDF में कैसे बदलें

EPUB एक ई‑बुक फ़ाइल फ़ॉर्मेट है जो एक मानक डिजिटल प्रकाशन फ़ॉर्मेट प्रदान करता है। इसे इंटरनेशनल डिजिटल पब्लिशिंग फ़ोरम ([IDPF](http://idpf.org/)) द्वारा बनाया गया है, और अब यह कई ई‑रीडर्स और सॉफ़्टवेयर एप्लिकेशनों द्वारा समर्थित है। EPUB से PDF रूपांतरण अक्सर PDF फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। PDF फ़ाइल फ़ॉर्मेट में टेक्स्ट, इमेज, हाइपरलिंक, फ़ॉर्म‑फ़ील्ड, रिच मीडिया, मेटाडेटा आदि जैसी जानकारी रखने की पूरी क्षमता होती है। PDF फ़ाइलें Adobe Acrobat Reader/Writer और अधिकांश आधुनिक ब्राउज़रों जैसे Chrome, Safari, Firefox में खोली जा सकती हैं। वे प्रिंटिंग के लिए अनुकूलित हैं, और आपके दस्तावेज़ों की भौतिक प्रतियां बनाने के लिए आदर्श हैं; आप PDF के लिए सुरक्षा सेटिंग्स भी कॉन्फ़िगर कर सकते हैं।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें एक [`Converter`](../) क्लास का उपयोग करके कैसे किया जाए, इस बारे में जानकारी प्रदान करता है, जो सभी लो‑लेवल रूपांतरण कार्यों को एक ही क्लास में समूहित करता है ताकि वे आरामदायक और उपयोग में आसान हों। EPUB Converter PDF विशिष्ट गाइड में, आप निम्न लेख पाएँगे:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB को PDF में बदलें

EPUB को PDF फ़ाइल फ़ॉर्मेट में बदलने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण के लिए, हम स्रोत फ़ाइल पथ को ConvertEPUB मेथड के पहले पैरामीटर के रूप में परिभाषित कर सकते हैं। वैकल्पिक रूप से हम इनपुट स्ट्रीम या Url ऑब्जेक्ट इंस्टेंस का उपयोग कर सकते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम ICreateStreamProvider इंटरफ़ेस इम्प्लीमेंटेशन का उपयोग करें। हम परिणाम आउटपुट फ़ाइल पथ को भी सरल विकल्प के रूप में उपयोग कर सकते हैं। पेज आकार, मार्जिन, CSS आदि जैसे वांछित पैरामीटरों के साथ एक नया PdfSaveOptions ऑब्जेक्ट बनाएँ। PdfSaveOptions क्लास का डिफ़ॉल्ट इंस्टेंस उपयोग करना संभव है। स्थैतिक Converter क्लास की ConvertEPUB() मेथड का उपयोग करके EPUB को PDF फ़ाइल के रूप में सहेजें। आपको EPUB स्रोत डेटा को फ़ाइल पथ या इनपुट स्ट्रीम के साथ-साथ Url, PdfSaveOptions इंस्टेंस, और आउटपुट डेटा बफ़र किसी भी रूप में पास करना होगा ताकि रूपांतरण प्रक्रिया शुरू हो सके। आप कॉन्फ़िगरेशन का उपयोग कर सकते हैं जो [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट का प्रतिनिधित्व करता है और एप्लिकेशन के पर्यावरण सेटिंग्स को सेट करने के लिए उपयोग किया जाता है। ऑनलाइन EPUB से PDF रूपांतरणकर्ता

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) कन्वर्टर प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से EPUB को PDF फ़ाइल में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

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
var sourcePath = Path.Combine(InputFolder, "sample.epub");  

// ICreateStreamProvider इंटरफ़ेस कार्यान्वयन देखें  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// डिफ़ॉल्ट विकल्प इंस्टेंस बनाएं  
var options = new PdfSaveOptions();   

// डिफ़ॉल्ट कॉन्फ़िगरेशन ऑब्जेक्ट के साथ रूपांतरण प्रक्रिया शुरू करें 
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### संबंधित देखें

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertepub_4}

URL द्वारा प्रस्तुत EPUB स्रोत को बदलें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित होता है।

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceUrl | Url | EPUB स्रोत URL - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) कॉन्टेक्स्ट ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है; आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`file permissions`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) आदि निर्दिष्ट कर सकते हैं। देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options)। |
| provider | ICreateStreamProvider | [ICreateStreamProvider](https://apireference.aspose.com/svg/net/aspose.svg.io/icreatestreamprovider) इंटरफ़ेस का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। उन्नत उदाहरण के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers)। |

## Remarks

EPUB को PDF में कैसे बदलें

EPUB एक ई‑बुक फ़ाइल फ़ॉर्मेट है जो एक मानक डिजिटल प्रकाशन फ़ॉर्मेट प्रदान करता है। इसे इंटरनेशनल डिजिटल पब्लिशिंग फ़ोरम ([IDPF](http://idpf.org/)) द्वारा बनाया गया है, और अब यह कई ई‑रीडर्स और सॉफ़्टवेयर एप्लिकेशनों द्वारा समर्थित है। EPUB से PDF रूपांतरण अक्सर PDF फ़ॉर्मेट का लाभ उठाने के लिए आवश्यक होता है। PDF फ़ाइल फ़ॉर्मेट में टेक्स्ट, इमेज, हाइपरलिंक, फ़ॉर्म‑फ़ील्ड, रिच मीडिया, मेटाडेटा आदि जैसी जानकारी रखने की पूरी क्षमता होती है। PDF फ़ाइलें Adobe Acrobat Reader/Writer और अधिकांश आधुनिक ब्राउज़रों जैसे Chrome, Safari, Firefox में खोली जा सकती हैं। वे प्रिंटिंग के लिए अनुकूलित हैं, और आपके दस्तावेज़ों की भौतिक प्रतियां बनाने के लिए आदर्श हैं; आप PDF के लिए सुरक्षा सेटिंग्स भी कॉन्फ़िगर कर सकते हैं।

Aspose.HTML की मुख्य विशेषता रूपांतरण सुविधा है। EPUB एक ओपन XML‑आधारित फ़ॉर्मेट है डिजिटल किताबों और प्रकाशनों के लिए, जिसे स्मार्टफ़ोन, टैबलेट और कंप्यूटर पर देखा और पढ़ा जा सकता है। com.aspose.html.converters पैकेज रूपांतरण मेथड्स तक आसान पहुंच प्रदान करता है। यह लोकप्रिय फ़ॉर्मेट जैसे [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), और [GIF](https://docs.fileformat.com/image/gif/) में [EPUB](https://docs.fileformat.com/ebook/epub/) रूपांतरण की विस्तृत श्रृंखला प्रदान करता है।

यह अनुभाग समर्थित EPUB रूपांतरण परिदृश्यों की सूची और उन्हें एक [`Converter`](../) क्लास का उपयोग करके कैसे किया जाए, इस बारे में जानकारी प्रदान करता है, जो सभी लो‑लेवल रूपांतरण कार्यों को एक ही क्लास में समूहित करता है ताकि वे आरामदायक और उपयोग में आसान हों। EPUB Converter PDF विशिष्ट गाइड में, आप निम्न लेख पाएँगे:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB को PDF में बदलें

EPUB को PDF फ़ाइल फ़ॉर्मेट में बदलने के लिए, आपको कुछ चरणों का पालन करना चाहिए:

एक मौजूदा EPUB फ़ाइल खोलें। उदाहरण के लिए, हम स्रोत फ़ाइल पथ को ConvertEPUB मेथड के पहले पैरामीटर के रूप में परिभाषित कर सकते हैं। वैकल्पिक रूप से हम इनपुट स्ट्रीम या Url ऑब्जेक्ट इंस्टेंस का उपयोग कर सकते हैं। आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम ICreateStreamProvider इंटरफ़ेस इम्प्लीमेंटेशन का उपयोग करें। हम परिणाम आउटपुट फ़ाइल पथ को भी सरल विकल्प के रूप में उपयोग कर सकते हैं। पेज आकार, मार्जिन, CSS आदि जैसे वांछित पैरामीटरों के साथ एक नया PdfSaveOptions ऑब्जेक्ट बनाएँ। PdfSaveOptions क्लास का डिफ़ॉल्ट इंस्टेंस उपयोग करना संभव है। स्थैतिक Converter क्लास की ConvertEPUB() मेथड का उपयोग करके EPUB को PDF फ़ाइल के रूप में सहेजें। आपको EPUB स्रोत डेटा को फ़ाइल पथ या इनपुट स्ट्रीम के साथ-साथ Url, PdfSaveOptions इंस्टेंस, और आउटपुट डेटा बफ़र किसी भी रूप में पास करना होगा ताकि रूपांतरण प्रक्रिया शुरू हो सके। आप कॉन्फ़िगरेशन का उपयोग कर सकते हैं जो [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट का प्रतिनिधित्व करता है और एप्लिकेशन के पर्यावरण सेटिंग्स को सेट करने के लिए उपयोग किया जाता है। ऑनलाइन EPUB से PDF रूपांतरणकर्ता

Aspose.HTML एक मुफ्त ऑनलाइन [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) कन्वर्टर प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से EPUB को PDF फ़ाइल में बदलता है। बस फ़ाइलें अपलोड करें, उन्हें बदलें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से पूर्ण उदाहरण और डेटा फ़ाइलें डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// इनपुट फ़ाइल पथ के आधार पर URL बनाएं
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// ICreateStreamProvider इंटरफ़ेस कार्यान्वयन देखें  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));

// डिफ़ॉल्ट विकल्प इंस्टेंस निर्धारित करें
var options = new PdfSaveOptions();

// डिफ़ॉल्ट कॉन्फ़िगरेशन ऑब्जेक्ट के साथ रूपांतरण प्रक्रिया शुरू करें
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, sp);
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

---
title: "Converter.ConvertSVG"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "Converter मेथड। SVGDocument द्वारा प्रस्तुत SVG स्रोत को परिवर्तित करें। परिणाम ICreateStreamProvider इंटरफ़ेस कार्यान्वयन द्वारा निर्मित आउटपुट डेटा है"
type: docs

url: /hi/java/com.aspose.html.converters/converter/convertsvg/
---
## ConvertSVG(SVGDocument, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_6}

[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) द्वारा प्रस्तुत SVG स्रोत को परिवर्तित करें। परिणाम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित आउटपुट डेटा है।

```java
public static void ConvertSVG(SVGDocument document, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| document | SVGDocument | [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) द्वारा प्रस्तुत रूपांतरण स्रोत। |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट का उपयोग आपको रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options)। |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) देखें जहाँ आप ConvertSVG() मेथड्स का उपयोग करके SVG को XPS में परिवर्तित करने की जानकारी और [`Converter`](../) क्लास तथा [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को लागू करने के बारे में जानकारी पा सकते हैं।

SVG को XPS में परिवर्तित करें

Converter क्लास कई SVG-विशिष्ट रूपांतरण XPS में प्रदान करती है। SVG को XPS में परिवर्तित करने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। एक मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में भी परिभाषित कर सकते हैं या यहाँ तक कि स्ट्रिंग स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट बनाएं। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। उपयोगकर्ता परिदृश्य पर निर्भर तीन या अधिक पैरामीटर के साथ SVG को XPS परिणाम के रूप में सहेजने के लिए Converter क्लास की ConvertSVG() मेथड का उपयोग करें। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से SVG को XPS में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // डिफ़ॉल्ट XpsSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new XpsSaveOptions();

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // SVG दस्तावेज़ को रूपांतरण स्रोत के रूप में बनाएं
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
			// डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
			Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_22}

`[`URL`](../../../com.aspose.html/url/)` द्वारा प्रस्तुत SVG स्रोत को परिवर्तित करें। परिणाम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित आउटपुट डेटा है।

```java
public static void ConvertSVG(Url url, XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| url | Url | SVG स्रोत दस्तावेज़ [`URL`](../../../com.aspose.html/url/) - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| options | XpsSaveOptions | `XpsSaveOptions` ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। |
| provider | ICreateStreamProvider | ज्ञात (देखें [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) देखें जहाँ आप ConvertSVG() मेथड्स का उपयोग करके SVG को XPS में परिवर्तित करने की जानकारी और [`Converter`](../) क्लास तथा [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को लागू करने के बारे में जानकारी पा सकते हैं।

SVG को XPS में परिवर्तित करें

Converter क्लास कई SVG-विशिष्ट रूपांतरण XPS में प्रदान करती है। SVG को XPS में परिवर्तित करने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। एक मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में भी परिभाषित कर सकते हैं या यहाँ तक कि स्ट्रिंग स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट बनाएं। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। उपयोगकर्ता परिदृश्य पर निर्भर तीन या अधिक पैरामीटर के साथ SVG को XPS परिणाम के रूप में सहेजने के लिए Converter क्लास की ConvertSVG() मेथड का उपयोग करें। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से SVG को XPS में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // डिफ़ॉल्ट XpsSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new XpsSaveOptions();

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(sourceUrl, options, sp);
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

## ConvertSVG(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_14}

`[`URL`](../../../com.aspose.html/url/)` द्वारा प्रस्तुत SVG स्रोत को परिवर्तित करें। परिणाम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित आउटपुट डेटा है।

```java
public static void ConvertSVG(Url url, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| url | Url | SVG स्रोत दस्तावेज़ [`URL`](../../../com.aspose.html/url/) - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट को दर्शाता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट का उपयोग आपको रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options)। |
| provider | ICreateStreamProvider | ज्ञात (देखें [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) देखें जहाँ आप ConvertSVG() मेथड्स का उपयोग करके SVG को XPS में परिवर्तित करने की जानकारी और [`Converter`](../) क्लास तथा [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को लागू करने के बारे में जानकारी पा सकते हैं।

SVG को XPS में परिवर्तित करें

Converter क्लास कई SVG-विशिष्ट रूपांतरण XPS में प्रदान करती है। SVG को XPS में परिवर्तित करने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। एक मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में भी परिभाषित कर सकते हैं या यहाँ तक कि स्ट्रिंग स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट बनाएं। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। उपयोगकर्ता परिदृश्य पर निर्भर तीन या अधिक पैरामीटर के साथ SVG को XPS परिणाम के रूप में सहेजने के लिए Converter क्लास की ConvertSVG() मेथड का उपयोग करें। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से SVG को XPS में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // डिफ़ॉल्ट XpsSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new XpsSaveOptions();

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
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

## ConvertSVG(String, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_38}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत SVG स्रोत को XPS में परिवर्तित करें। परिणाम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित आउटपुट डेटा है।

```java
public static void ConvertSVG(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| sourcePath | String | SVG स्रोत पूर्ण फ़ाइल पथ। |
| options | XpsSaveOptions | `XpsSaveOptions` ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) देखें जहाँ आप ConvertSVG() मेथड्स का उपयोग करके SVG को XPS में परिवर्तित करने की जानकारी और [`Converter`](../) क्लास तथा [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को लागू करने के बारे में जानकारी पा सकते हैं।

SVG को XPS में परिवर्तित करें

Converter क्लास कई SVG-विशिष्ट रूपांतरण XPS में प्रदान करती है। SVG को XPS में परिवर्तित करने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। एक मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में भी परिभाषित कर सकते हैं या यहाँ तक कि स्ट्रिंग स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट बनाएं। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। उपयोगकर्ता परिदृश्य पर निर्भर तीन या अधिक पैरामीटर के साथ SVG को XPS परिणाम के रूप में सहेजने के लिए Converter क्लास की ConvertSVG() मेथड का उपयोग करें। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से SVG को XPS में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // डिफ़ॉल्ट XpsSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new XpsSaveOptions();

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(sourcePath, options, sp);
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

## ConvertSVG(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_30}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत SVG स्रोत को XPS में परिवर्तित करें। परिणाम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित आउटपुट डेटा है।

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| sourcePath | String | SVG स्रोत पूर्ण फ़ाइल पथ। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट को दर्शाता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट का उपयोग आपको रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options)। |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) देखें जहाँ आप ConvertSVG() मेथड्स का उपयोग करके SVG को XPS में परिवर्तित करने की जानकारी और [`Converter`](../) क्लास तथा [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को लागू करने के बारे में जानकारी पा सकते हैं।

SVG को XPS में परिवर्तित करें

Converter क्लास कई SVG-विशिष्ट रूपांतरण XPS में प्रदान करती है। SVG को XPS में परिवर्तित करने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। एक मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में भी परिभाषित कर सकते हैं या यहाँ तक कि स्ट्रिंग स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट बनाएं। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। उपयोगकर्ता परिदृश्य पर निर्भर तीन या अधिक पैरामीटर के साथ SVG को XPS परिणाम के रूप में सहेजने के लिए Converter क्लास की ConvertSVG() मेथड का उपयोग करें। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से SVG को XPS में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // डिफ़ॉल्ट XpsSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new XpsSaveOptions();

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
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

## ConvertSVG(String, String, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_54}

इनलाइन सामग्री द्वारा प्रस्तुत SVG स्रोत को XPS में परिवर्तित करें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित है।

```java
public static void ConvertSVG(String content, String baseUri, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| सामग्री | String | String के रूप में इनलाइन SVG सामग्री। |
| baseUri | String | दस्तावेज़ का बेस URI। इसे वर्तमान निर्देशिका पथ के साथ मिलाकर एक पूर्ण URL बनाया जाएगा। |
| options | XpsSaveOptions | `XpsSaveOptions` ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) देखें जहाँ आप ConvertSVG() मेथड्स का उपयोग करके SVG को XPS में परिवर्तित करने की जानकारी और [`Converter`](../) क्लास तथा [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को लागू करने के बारे में जानकारी पा सकते हैं।

SVG को XPS में परिवर्तित करें

Converter क्लास कई SVG-विशिष्ट रूपांतरण XPS में प्रदान करती है। SVG को XPS में परिवर्तित करने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। एक मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में भी परिभाषित कर सकते हैं या यहाँ तक कि स्ट्रिंग स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट बनाएं। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। उपयोगकर्ता परिदृश्य पर निर्भर तीन या अधिक पैरामीटर के साथ SVG को XPS परिणाम के रूप में सहेजने के लिए Converter क्लास की ConvertSVG() मेथड का उपयोग करें। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से SVG को XPS में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // डिफ़ॉल्ट XpsSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new XpsSaveOptions();

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### संबंधित देखें

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_46}

इनलाइन सामग्री द्वारा प्रस्तुत SVG स्रोत को XPS में परिवर्तित करें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित है।

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| सामग्री | String | String के रूप में इनलाइन SVG सामग्री। |
| baseUri | String | दस्तावेज़ का बेस URI। इसे वर्तमान निर्देशिका पथ के साथ मिलाकर एक पूर्ण URL बनाया जाएगा। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट को दर्शाता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट का उपयोग आपको रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options)। |
| provider | ICreateStreamProvider | ज्ञात (देखें [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) देखें जहाँ आप ConvertSVG() मेथड्स का उपयोग करके SVG को XPS में परिवर्तित करने की जानकारी और [`Converter`](../) क्लास तथा [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को लागू करने के बारे में जानकारी पा सकते हैं।

SVG को XPS में परिवर्तित करें

Converter क्लास कई SVG-विशिष्ट रूपांतरण XPS में प्रदान करती है। SVG को XPS में परिवर्तित करने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। एक मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में भी परिभाषित कर सकते हैं या यहाँ तक कि स्ट्रिंग स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट बनाएं। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। उपयोगकर्ता परिदृश्य पर निर्भर तीन या अधिक पैरामीटर के साथ SVG को XPS परिणाम के रूप में सहेजने के लिए Converter क्लास की ConvertSVG() मेथड का उपयोग करें। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से SVG को XPS में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // डिफ़ॉल्ट XpsSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new XpsSaveOptions();

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
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

## ConvertSVG(SVGDocument, DocSaveOptions, String) {#convertsvg_1}

[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) द्वारा प्रस्तुत SVG स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित DOCX फ़ाइल है।

```java
public static void ConvertSVG(SVGDocument source, DocSaveOptions options, String outputPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| source | SVGDocument | [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) द्वारा प्रस्तुत रूपांतरण स्रोत। |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण docx फ़ाइल पाथ। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

इस [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) को देखें जहाँ आपको SVG को [DOCX](https://docs.fileformat.com/word-processing/docx/) में परिवर्तित करने के बारे में जानकारी मिलती है, Converter क्लास की ConvertSVG() मेथड्स का उपयोग करके और कैसे [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें।

SVG को DOCX में परिवर्तित करें

Converter क्लास कई SVG विशिष्ट रूपांतरण DOCX में प्रदान करती है। SVG को DOCX में परिवर्तित करने के लिए, आपको कुछ सरल चरणों वाले परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि String स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। एक नया [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ बनाएं। आप वैकल्पिक रूप से [`configuration`](../../../com.aspose.html/configuration/) को विकल्प पैरामीटर के रूप में जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को DOCX परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर होते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) प्रदान करता है जो SVG को DOCX में उच्च गुणवत्ता, आसान और तेज़ी से परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // डिफ़ॉल्ट DocSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new DocSaveOptions();

      // SVG दस्तावेज़ को रूपांतरण स्रोत के रूप में बनाएं
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, DocSaveOptions, String) {#convertsvg_17}

[`URL`](../../../com.aspose.html/url/) द्वारा प्रस्तुत SVG स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित DOCX फ़ाइल है।

```java
public static void ConvertSVG(Url url, DocSaveOptions options, String outputPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| url | Url | SVG स्रोत दस्तावेज़ [`URL`](../../../com.aspose.html/url/) - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण docx फ़ाइल पाथ। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

इस [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) को देखें जहाँ आपको SVG को [DOCX](https://docs.fileformat.com/word-processing/docx/) में परिवर्तित करने के बारे में जानकारी मिलती है, Converter क्लास की ConvertSVG() मेथड्स का उपयोग करके और कैसे [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें।

SVG को DOCX में परिवर्तित करें

Converter क्लास कई SVG विशिष्ट रूपांतरण DOCX में प्रदान करती है। SVG को DOCX में परिवर्तित करने के लिए, आपको कुछ सरल चरणों वाले परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि String स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। एक नया [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ बनाएं। आप वैकल्पिक रूप से [`configuration`](../../../com.aspose.html/configuration/) को विकल्प पैरामीटर के रूप में जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को DOCX परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर होते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) प्रदान करता है जो SVG को DOCX में उच्च गुणवत्ता, आसान और तेज़ी से परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // इनपुट फ़ाइल पथ के आधार पर Url बनाएं
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // डिफ़ॉल्ट DocSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new DocSaveOptions();

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(sourceUrl, options, resultPath);





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

## ConvertSVG(Url, Configuration, DocSaveOptions, String) {#convertsvg_9}

[`URL`](../../../com.aspose.html/url/) द्वारा प्रस्तुत SVG स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित DOCX फ़ाइल है।

```java
public static void ConvertSVG(Url url, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| url | Url | SVG स्रोत दस्तावेज़ [`URL`](../../../com.aspose.html/url/) - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट को दर्शाता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण docx फ़ाइल पाथ। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

इस [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) को देखें जहाँ आपको SVG को [DOCX](https://docs.fileformat.com/word-processing/docx/) में परिवर्तित करने के बारे में जानकारी मिलती है, Converter क्लास की ConvertSVG() मेथड्स का उपयोग करके और कैसे [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें।

SVG को DOCX में परिवर्तित करें

Converter क्लास कई SVG विशिष्ट रूपांतरण DOCX में प्रदान करती है। SVG को DOCX में परिवर्तित करने के लिए, आपको कुछ सरल चरणों वाले परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि String स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। एक नया [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ बनाएं। आप वैकल्पिक रूप से [`configuration`](../../../com.aspose.html/configuration/) को विकल्प पैरामीटर के रूप में जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को DOCX परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर होते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) प्रदान करता है जो SVG को DOCX में उच्च गुणवत्ता, आसान और तेज़ी से परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // इनपुट फ़ाइल पथ के आधार पर Url बनाएं
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // डिफ़ॉल्ट DocSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new DocSaveOptions();

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### संबंधित देखें

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, DocSaveOptions, String) {#convertsvg_33}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत SVG स्रोत को DOCX में परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित DOCX फ़ाइल है।

```java
public static void ConvertSVG(String sourcePath, DocSaveOptions options, String outputPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| sourcePath | String | SVG स्रोत पूर्ण फ़ाइल पथ। |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण docx फ़ाइल पाथ। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

इस [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) को देखें जहाँ आपको SVG को [DOCX](https://docs.fileformat.com/word-processing/docx/) में परिवर्तित करने के बारे में जानकारी मिलती है, Converter क्लास की ConvertSVG() मेथड्स का उपयोग करके और कैसे [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें।

SVG को DOCX में परिवर्तित करें

Converter क्लास कई SVG विशिष्ट रूपांतरण DOCX में प्रदान करती है। SVG को DOCX में परिवर्तित करने के लिए, आपको कुछ सरल चरणों वाले परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि String स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। एक नया [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ बनाएं। आप वैकल्पिक रूप से [`configuration`](../../../com.aspose.html/configuration/) को विकल्प पैरामीटर के रूप में जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को DOCX परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर होते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) प्रदान करता है जो SVG को DOCX में उच्च गुणवत्ता, आसान और तेज़ी से परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // डिफ़ॉल्ट DocSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new DocSaveOptions();

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(sourcePath, options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### संबंधित देखें

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, DocSaveOptions, String) {#convertsvg_25}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत SVG स्रोत को DOCX में परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित DOCX फ़ाइल है।

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| sourcePath | String | SVG स्रोत पूर्ण फ़ाइल पथ। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट को दर्शाता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण docx फ़ाइल पाथ। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

इस [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) को देखें जहाँ आपको SVG को [DOCX](https://docs.fileformat.com/word-processing/docx/) में परिवर्तित करने के बारे में जानकारी मिलती है, Converter क्लास की ConvertSVG() मेथड्स का उपयोग करके और कैसे [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें।

SVG को DOCX में परिवर्तित करें

Converter क्लास कई SVG विशिष्ट रूपांतरण DOCX में प्रदान करती है। SVG को DOCX में परिवर्तित करने के लिए, आपको कुछ सरल चरणों वाले परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि String स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। एक नया [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ बनाएं। आप वैकल्पिक रूप से [`configuration`](../../../com.aspose.html/configuration/) को विकल्प पैरामीटर के रूप में जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को DOCX परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर होते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) प्रदान करता है जो SVG को DOCX में उच्च गुणवत्ता, आसान और तेज़ी से परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // डिफ़ॉल्ट DocSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new DocSaveOptions();

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
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

## ConvertSVG(String, String, DocSaveOptions, String) {#convertsvg_49}

इनलाइन सामग्री द्वारा प्रस्तुत SVG स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित docx फ़ाइल है।

```java
public static void ConvertSVG(String content, String baseUri, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| सामग्री | String | String के रूप में इनलाइन SVG सामग्री। |
| baseUri | String | दस्तावेज़ का बेस URI। इसे वर्तमान निर्देशिका पथ के साथ मिलाकर एक पूर्ण URL बनाया जाएगा। |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण docx फ़ाइल पाथ। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

इस [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) को देखें जहाँ आपको SVG को [DOCX](https://docs.fileformat.com/word-processing/docx/) में परिवर्तित करने के बारे में जानकारी मिलती है, Converter क्लास की ConvertSVG() मेथड्स का उपयोग करके और कैसे [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें।

SVG को DOCX में परिवर्तित करें

Converter क्लास कई SVG विशिष्ट रूपांतरण DOCX में प्रदान करती है। SVG को DOCX में परिवर्तित करने के लिए, आपको कुछ सरल चरणों वाले परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि String स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। एक नया [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ बनाएं। आप वैकल्पिक रूप से [`configuration`](../../../com.aspose.html/configuration/) को विकल्प पैरामीटर के रूप में जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को DOCX परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर होते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) प्रदान करता है जो SVG को DOCX में उच्च गुणवत्ता, आसान और तेज़ी से परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // इनलाइन SVG सामग्री को फ़ॉर्म करें
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // डिफ़ॉल्ट DocSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new DocSaveOptions();

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### संबंधित देखें

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, DocSaveOptions, String) {#convertsvg_41}

इनलाइन सामग्री द्वारा प्रस्तुत SVG स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित docx फ़ाइल है।

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| सामग्री | String | String के रूप में इनलाइन SVG सामग्री। |
| baseUri | String | दस्तावेज़ का बेस URI। इसे वर्तमान निर्देशिका पथ के साथ मिलाकर एक पूर्ण URL बनाया जाएगा। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट को दर्शाता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण docx फ़ाइल पाथ। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

इस [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) को देखें जहाँ आपको SVG को [DOCX](https://docs.fileformat.com/word-processing/docx/) में परिवर्तित करने के बारे में जानकारी मिलती है, Converter क्लास की ConvertSVG() मेथड्स का उपयोग करके और कैसे [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें।

SVG को DOCX में परिवर्तित करें

Converter क्लास कई SVG विशिष्ट रूपांतरण DOCX में प्रदान करती है। SVG को DOCX में परिवर्तित करने के लिए, आपको कुछ सरल चरणों वाले परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि String स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। एक नया [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ बनाएं। आप वैकल्पिक रूप से [`configuration`](../../../com.aspose.html/configuration/) को विकल्प पैरामीटर के रूप में जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को DOCX परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर होते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) प्रदान करता है जो SVG को DOCX में उच्च गुणवत्ता, आसान और तेज़ी से परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // इनलाइन SVG सामग्री को फ़ॉर्म करें
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // डिफ़ॉल्ट DocSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new DocSaveOptions();

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### संबंधित देखें

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, DocSaveOptions, ICreateStreamProvider) {#convertsvg}

[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) द्वारा प्रस्तुत SVG स्रोत को परिवर्तित करें। परिणाम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित आउटपुट डेटा है।

```java
public static void ConvertSVG(SVGDocument document, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| document | SVGDocument | [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) द्वारा प्रस्तुत रूपांतरण स्रोत। |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)। |
| provider | ICreateStreamProvider | ज्ञात (देखें [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

इस [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) को देखें जहाँ आपको SVG को [DOCX](https://docs.fileformat.com/word-processing/docx/) में परिवर्तित करने के बारे में जानकारी मिलती है, Converter क्लास की ConvertSVG() मेथड्स का उपयोग करके और कैसे [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें।

SVG को DOCX में परिवर्तित करें

Converter क्लास कई SVG विशिष्ट रूपांतरण DOCX में प्रदान करती है। SVG को DOCX में परिवर्तित करने के लिए, आपको कुछ सरल चरणों वाले परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि String स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। एक नया [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ बनाएं। आप वैकल्पिक रूप से [`configuration`](../../../com.aspose.html/configuration/) को विकल्प पैरामीटर के रूप में जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को DOCX परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर होते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) प्रदान करता है जो SVG को DOCX में उच्च गुणवत्ता, आसान और तेज़ी से परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // डिफ़ॉल्ट DocSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new DocSaveOptions();

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // SVG दस्तावेज़ को रूपांतरण स्रोत के रूप में बनाएं
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, DocSaveOptions, ICreateStreamProvider) {#convertsvg_16}

`[`URL`](../../../com.aspose.html/url/)` द्वारा प्रस्तुत SVG स्रोत को परिवर्तित करें। परिणाम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित आउटपुट डेटा है।

```java
public static void ConvertSVG(Url url, DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| url | Url | SVG स्रोत दस्तावेज़ [`URL`](../../../com.aspose.html/url/) - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)। |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

इस [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) को देखें जहाँ आपको SVG को [DOCX](https://docs.fileformat.com/word-processing/docx/) में परिवर्तित करने के बारे में जानकारी मिलती है, Converter क्लास की ConvertSVG() मेथड्स का उपयोग करके और कैसे [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें।

SVG को DOCX में परिवर्तित करें

Converter क्लास कई SVG विशिष्ट रूपांतरण DOCX में प्रदान करती है। SVG को DOCX में परिवर्तित करने के लिए, आपको कुछ सरल चरणों वाले परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि String स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। एक नया [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ बनाएं। आप वैकल्पिक रूप से [`configuration`](../../../com.aspose.html/configuration/) को विकल्प पैरामीटर के रूप में जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को DOCX परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर होते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) प्रदान करता है जो SVG को DOCX में उच्च गुणवत्ता, आसान और तेज़ी से परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // इनपुट फ़ाइल पथ के आधार पर Url बनाएं
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // डिफ़ॉल्ट DocSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new DocSaveOptions();

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(sourceUrl, options, sp);





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

## ConvertSVG(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_8}

[`URL`](../../../com.aspose.html/url/) द्वारा प्रस्तुत SVG स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित DOCX फ़ाइल है।

```java
public static void ConvertSVG(Url url, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| url | Url | SVG स्रोत दस्तावेज़ [`URL`](../../../com.aspose.html/url/) - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट को दर्शाता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)। |
| provider | ICreateStreamProvider | ज्ञात (देखें [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

इस [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) को देखें जहाँ आपको SVG को [DOCX](https://docs.fileformat.com/word-processing/docx/) में परिवर्तित करने के बारे में जानकारी मिलती है, Converter क्लास की ConvertSVG() मेथड्स का उपयोग करके और कैसे [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें।

SVG को DOCX में परिवर्तित करें

Converter क्लास कई SVG विशिष्ट रूपांतरण DOCX में प्रदान करती है। SVG को DOCX में परिवर्तित करने के लिए, आपको कुछ सरल चरणों वाले परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि String स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। एक नया [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ बनाएं। आप वैकल्पिक रूप से [`configuration`](../../../com.aspose.html/configuration/) को विकल्प पैरामीटर के रूप में जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को DOCX परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर होते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) प्रदान करता है जो SVG को DOCX में उच्च गुणवत्ता, आसान और तेज़ी से परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // इनपुट फ़ाइल पथ के आधार पर Url बनाएं
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // डिफ़ॉल्ट DocSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new DocSaveOptions();

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);





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

## ConvertSVG(String, DocSaveOptions, ICreateStreamProvider) {#convertsvg_32}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत SVG स्रोत को DOCX में परिवर्तित करें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित है।

```java
public static void ConvertSVG(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| sourcePath | String | SVG स्रोत पूर्ण फ़ाइल पथ। |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)। |
| provider | ICreateStreamProvider | ज्ञात (देखें [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

इस [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) को देखें जहाँ आपको SVG को [DOCX](https://docs.fileformat.com/word-processing/docx/) में परिवर्तित करने के बारे में जानकारी मिलती है, Converter क्लास की ConvertSVG() मेथड्स का उपयोग करके और कैसे [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें।

SVG को DOCX में परिवर्तित करें

Converter क्लास कई SVG विशिष्ट रूपांतरण DOCX में प्रदान करती है। SVG को DOCX में परिवर्तित करने के लिए, आपको कुछ सरल चरणों वाले परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि String स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। एक नया [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ बनाएं। आप वैकल्पिक रूप से [`configuration`](../../../com.aspose.html/configuration/) को विकल्प पैरामीटर के रूप में जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को DOCX परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर होते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) प्रदान करता है जो SVG को DOCX में उच्च गुणवत्ता, आसान और तेज़ी से परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // डिफ़ॉल्ट DocSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new DocSaveOptions();

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(sourcePath, options, sp);
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

## ConvertSVG(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_24}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत SVG स्रोत को DOCX में परिवर्तित करें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित है।

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| sourcePath | String | SVG स्रोत पूर्ण फ़ाइल पथ। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट को दर्शाता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)। |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

इस [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) को देखें जहाँ आपको SVG को [DOCX](https://docs.fileformat.com/word-processing/docx/) में परिवर्तित करने के बारे में जानकारी मिलती है, Converter क्लास की ConvertSVG() मेथड्स का उपयोग करके और कैसे [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें।

SVG को DOCX में परिवर्तित करें

Converter क्लास कई SVG विशिष्ट रूपांतरण DOCX में प्रदान करती है। SVG को DOCX में परिवर्तित करने के लिए, आपको कुछ सरल चरणों वाले परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि String स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। एक नया [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ बनाएं। आप वैकल्पिक रूप से [`configuration`](../../../com.aspose.html/configuration/) को विकल्प पैरामीटर के रूप में जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को DOCX परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर होते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) प्रदान करता है जो SVG को DOCX में उच्च गुणवत्ता, आसान और तेज़ी से परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // डिफ़ॉल्ट DocSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new DocSaveOptions();

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
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

## ConvertSVG(String, String, DocSaveOptions, ICreateStreamProvider) {#convertsvg_48}

इनलाइन सामग्री द्वारा प्रस्तुत SVG स्रोत को DOCX में परिवर्तित करें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित है।

```java
public static void ConvertSVG(String content, String baseUri, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| सामग्री | String | String के रूप में इनलाइन SVG सामग्री। |
| baseUri | String | दस्तावेज़ का बेस URI। इसे वर्तमान निर्देशिका पथ के साथ मिलाकर एक पूर्ण URL बनाया जाएगा। |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)। |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

इस [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) को देखें जहाँ आपको SVG को [DOCX](https://docs.fileformat.com/word-processing/docx/) में परिवर्तित करने के बारे में जानकारी मिलती है, Converter क्लास की ConvertSVG() मेथड्स का उपयोग करके और कैसे [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें।

SVG को DOCX में परिवर्तित करें

Converter क्लास कई SVG विशिष्ट रूपांतरण DOCX में प्रदान करती है। SVG को DOCX में परिवर्तित करने के लिए, आपको कुछ सरल चरणों वाले परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि String स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। एक नया [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ बनाएं। आप वैकल्पिक रूप से [`configuration`](../../../com.aspose.html/configuration/) को विकल्प पैरामीटर के रूप में जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को DOCX परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर होते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) प्रदान करता है जो SVG को DOCX में उच्च गुणवत्ता, आसान और तेज़ी से परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // डिफ़ॉल्ट DocSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new DocSaveOptions();

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### संबंधित देखें

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_40}

इनलाइन सामग्री द्वारा प्रस्तुत SVG स्रोत को DOCX में परिवर्तित करें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित है।

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| सामग्री | String | String के रूप में इनलाइन SVG सामग्री। |
| baseUri | String | दस्तावेज़ का बेस URI। इसे वर्तमान निर्देशिका पथ के साथ मिलाकर एक पूर्ण URL बनाया जाएगा। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट को दर्शाता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)। |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

इस [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) को देखें जहाँ आपको SVG को [DOCX](https://docs.fileformat.com/word-processing/docx/) में परिवर्तित करने के बारे में जानकारी मिलती है, Converter क्लास की ConvertSVG() मेथड्स का उपयोग करके और कैसे [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें।

SVG को DOCX में परिवर्तित करें

Converter क्लास कई SVG विशिष्ट रूपांतरण DOCX में प्रदान करती है। SVG को DOCX में परिवर्तित करने के लिए, आपको कुछ सरल चरणों वाले परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि String स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। एक नया [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) ऑब्जेक्ट विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ बनाएं। आप वैकल्पिक रूप से [`configuration`](../../../com.aspose.html/configuration/) को विकल्प पैरामीटर के रूप में जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को DOCX परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर होते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) प्रदान करता है जो SVG को DOCX में उच्च गुणवत्ता, आसान और तेज़ी से परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // डिफ़ॉल्ट DocSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new DocSaveOptions();

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
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

## ConvertSVG(SVGDocument, PdfSaveOptions, String) {#convertsvg_5}

[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) द्वारा प्रस्तुत SVG स्रोत को PDF में परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित PDF फ़ाइल है।

```java
public static void ConvertSVG(SVGDocument source, PdfSaveOptions options, String outputPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| source | SVGDocument | [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) द्वारा प्रस्तुत रूपांतरण स्रोत। |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण pdf फ़ाइल पथ। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

इस [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) को देखें जहाँ आपको SVG को PDF में परिवर्तित करने की जानकारी मिलती है, [`Converter`](../) क्लास की ConvertSVG() मेथड्स का उपयोग करके और कैसे [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें।

SVG को PDF में परिवर्तित करें

Converter क्लास कई SVG विशिष्ट रूपांतरण PDF में प्रदान करती है। SVG को PDF में परिवर्तित करने के लिए, आपको कुछ सरल चरणों वाले परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि String स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। एक नया [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ बनाएं। आप वैकल्पिक रूप से [`configuration`](../../../com.aspose.html/configuration/) को विकल्प पैरामीटर के रूप में जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को PDF परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर होते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) प्रदान करता है जो SVG को PDF में उच्च गुणवत्ता, आसान और तेज़ी से परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // डिफ़ॉल्ट PdfSaveOptions ऑब्जेक्ट परिभाषित करें
      var options = new PdfSaveOptions();

      // SVG दस्तावेज़ को रूपांतरण स्रोत के रूप में बनाएं
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, PdfSaveOptions, String) {#convertsvg_21}

[`URL`](../../../com.aspose.html/url/) द्वारा प्रस्तुत SVG स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित PDF फ़ाइल है।

```java
public static void ConvertSVG(Url url, PdfSaveOptions options, String outputPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| url | Url | SVG स्रोत दस्तावेज़ [`URL`](../../../com.aspose.html/url/) - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण pdf फ़ाइल पथ। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

इस [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) को देखें जहाँ आपको SVG को PDF में परिवर्तित करने की जानकारी मिलती है, [`Converter`](../) क्लास की ConvertSVG() मेथड्स का उपयोग करके और कैसे [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें।

SVG को PDF में परिवर्तित करें

Converter क्लास कई SVG विशिष्ट रूपांतरण PDF में प्रदान करती है। SVG को PDF में परिवर्तित करने के लिए, आपको कुछ सरल चरणों वाले परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि String स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। एक नया [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ बनाएं। आप वैकल्पिक रूप से [`configuration`](../../../com.aspose.html/configuration/) को विकल्प पैरामीटर के रूप में जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को PDF परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर होते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) प्रदान करता है जो SVG को PDF में उच्च गुणवत्ता, आसान और तेज़ी से परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // इनपुट फ़ाइल पथ के आधार पर Url बनाएं
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // डिफ़ॉल्ट PdfSaveOptions ऑब्जेक्ट परिभाषित करें
      var options = new PdfSaveOptions();

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(sourceUrl, options, resultPath);
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

## ConvertSVG(Url, Configuration, PdfSaveOptions, String) {#convertsvg_13}

[`URL`](../../../com.aspose.html/url/) द्वारा प्रस्तुत SVG स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित PDF फ़ाइल है।

```java
public static void ConvertSVG(Url url, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| url | Url | SVG स्रोत दस्तावेज़ [`URL`](../../../com.aspose.html/url/) - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट को दर्शाता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण pdf फ़ाइल पथ। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

इस [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) को देखें जहाँ आपको SVG को PDF में परिवर्तित करने की जानकारी मिलती है, [`Converter`](../) क्लास की ConvertSVG() मेथड्स का उपयोग करके और कैसे [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें।

SVG को PDF में परिवर्तित करें

Converter क्लास कई SVG विशिष्ट रूपांतरण PDF में प्रदान करती है। SVG को PDF में परिवर्तित करने के लिए, आपको कुछ सरल चरणों वाले परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि String स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। एक नया [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ बनाएं। आप वैकल्पिक रूप से [`configuration`](../../../com.aspose.html/configuration/) को विकल्प पैरामीटर के रूप में जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को PDF परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर होते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) प्रदान करता है जो SVG को PDF में उच्च गुणवत्ता, आसान और तेज़ी से परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // इनपुट फ़ाइल पथ के आधार पर Url बनाएं
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // डिफ़ॉल्ट PdfSaveOptions ऑब्जेक्ट परिभाषित करें
      var options = new PdfSaveOptions();

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertSVG(String, PdfSaveOptions, String) {#convertsvg_37}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत SVG स्रोत को PDF में परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित PDF फ़ाइल है।

```java
public static void ConvertSVG(String sourcePath, PdfSaveOptions options, String outputPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| sourcePath | String | SVG स्रोत पूर्ण फ़ाइल पथ। |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण pdf फ़ाइल पथ। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

इस [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) को देखें जहाँ आपको SVG को PDF में परिवर्तित करने की जानकारी मिलती है, [`Converter`](../) क्लास की ConvertSVG() मेथड्स का उपयोग करके और कैसे [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें।

SVG को PDF में परिवर्तित करें

Converter क्लास कई SVG विशिष्ट रूपांतरण PDF में प्रदान करती है। SVG को PDF में परिवर्तित करने के लिए, आपको कुछ सरल चरणों वाले परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि String स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। एक नया [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ बनाएं। आप वैकल्पिक रूप से [`configuration`](../../../com.aspose.html/configuration/) को विकल्प पैरामीटर के रूप में जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को PDF परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर होते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) प्रदान करता है जो SVG को PDF में उच्च गुणवत्ता, आसान और तेज़ी से परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // डिफ़ॉल्ट PdfSaveOptions ऑब्जेक्ट परिभाषित करें
      var options = new PdfSaveOptions();

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, PdfSaveOptions, String) {#convertsvg_29}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत SVG स्रोत को PDF में परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित PDF फ़ाइल है।

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| sourcePath | String | SVG स्रोत पूर्ण फ़ाइल पथ। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट को दर्शाता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण pdf फ़ाइल पथ। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

इस [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) को देखें जहाँ आपको SVG को PDF में परिवर्तित करने की जानकारी मिलती है, [`Converter`](../) क्लास की ConvertSVG() मेथड्स का उपयोग करके और कैसे [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें।

SVG को PDF में परिवर्तित करें

Converter क्लास कई SVG विशिष्ट रूपांतरण PDF में प्रदान करती है। SVG को PDF में परिवर्तित करने के लिए, आपको कुछ सरल चरणों वाले परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि String स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। एक नया [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ बनाएं। आप वैकल्पिक रूप से [`configuration`](../../../com.aspose.html/configuration/) को विकल्प पैरामीटर के रूप में जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को PDF परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर होते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) प्रदान करता है जो SVG को PDF में उच्च गुणवत्ता, आसान और तेज़ी से परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // डिफ़ॉल्ट PdfSaveOptions ऑब्जेक्ट परिभाषित करें
      var options = new PdfSaveOptions();

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
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

## ConvertSVG(String, String, PdfSaveOptions, String) {#convertsvg_53}

इनलाइन सामग्री द्वारा प्रस्तुत SVG स्रोत को PDF में परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित pdf फ़ाइल है।

```java
public static void ConvertSVG(String content, String baseUri, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| सामग्री | String | String के रूप में इनलाइन SVG सामग्री। |
| baseUri | String | दस्तावेज़ का बेस URI। इसे वर्तमान निर्देशिका पथ के साथ मिलाकर एक पूर्ण URL बनाया जाएगा। |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण pdf फ़ाइल पथ। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

इस [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) को देखें जहाँ आपको SVG को PDF में परिवर्तित करने की जानकारी मिलती है, [`Converter`](../) क्लास की ConvertSVG() मेथड्स का उपयोग करके और कैसे [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें।

SVG को PDF में परिवर्तित करें

Converter क्लास कई SVG विशिष्ट रूपांतरण PDF में प्रदान करती है। SVG को PDF में परिवर्तित करने के लिए, आपको कुछ सरल चरणों वाले परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि String स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। एक नया [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ बनाएं। आप वैकल्पिक रूप से [`configuration`](../../../com.aspose.html/configuration/) को विकल्प पैरामीटर के रूप में जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को PDF परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर होते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) प्रदान करता है जो SVG को PDF में उच्च गुणवत्ता, आसान और तेज़ी से परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // इनलाइन SVG सामग्री को फ़ॉर्म करें
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // डिफ़ॉल्ट PdfSaveOptions ऑब्जेक्ट परिभाषित करें
      var options = new PdfSaveOptions();

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### संबंधित देखें

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, PdfSaveOptions, String) {#convertsvg_45}

इनलाइन सामग्री द्वारा प्रस्तुत SVG स्रोत को PDF में परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित pdf फ़ाइल है।

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| सामग्री | String | String के रूप में इनलाइन SVG सामग्री। |
| baseUri | String | दस्तावेज़ का बेस URI। इसे वर्तमान निर्देशिका पथ के साथ मिलाकर एक पूर्ण URL बनाया जाएगा। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट को दर्शाता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण pdf फ़ाइल पथ। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

इस [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) को देखें जहाँ आपको SVG को PDF में परिवर्तित करने की जानकारी मिलती है, [`Converter`](../) क्लास की ConvertSVG() मेथड्स का उपयोग करके और कैसे [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें।

SVG को PDF में परिवर्तित करें

Converter क्लास कई SVG विशिष्ट रूपांतरण PDF में प्रदान करती है। SVG को PDF में परिवर्तित करने के लिए, आपको कुछ सरल चरणों वाले परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि String स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। एक नया [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ बनाएं। आप वैकल्पिक रूप से [`configuration`](../../../com.aspose.html/configuration/) को विकल्प पैरामीटर के रूप में जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को PDF परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर होते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) प्रदान करता है जो SVG को PDF में उच्च गुणवत्ता, आसान और तेज़ी से परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // इनलाइन SVG सामग्री को फ़ॉर्म करें
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // डिफ़ॉल्ट PdfSaveOptions ऑब्जेक्ट परिभाषित करें
      var options = new PdfSaveOptions();

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### संबंधित देखें

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_4}

[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) द्वारा प्रस्तुत SVG स्रोत को PDF में परिवर्तित करें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित है।

```java
public static void ConvertSVG(SVGDocument document, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| document | SVGDocument | [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) द्वारा प्रस्तुत रूपांतरण स्रोत। |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)। |
| provider | ICreateStreamProvider | ज्ञात (देखें [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

इस [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) को देखें जहाँ आपको SVG को PDF में परिवर्तित करने की जानकारी मिलती है, [`Converter`](../) क्लास की ConvertSVG() मेथड्स का उपयोग करके और कैसे [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें।

SVG को PDF में परिवर्तित करें

Converter क्लास कई SVG विशिष्ट रूपांतरण PDF में प्रदान करती है। SVG को PDF में परिवर्तित करने के लिए, आपको कुछ सरल चरणों वाले परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि String स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। एक नया [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ बनाएं। आप वैकल्पिक रूप से [`configuration`](../../../com.aspose.html/configuration/) को विकल्प पैरामीटर के रूप में जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को PDF परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर होते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) प्रदान करता है जो SVG को PDF में उच्च गुणवत्ता, आसान और तेज़ी से परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // डिफ़ॉल्ट PdfSaveOptions ऑब्जेक्ट परिभाषित करें
      var options = new PdfSaveOptions();

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // SVG दस्तावेज़ को रूपांतरण स्रोत के रूप में बनाएं
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_20}

`[`URL`](../../../com.aspose.html/url/)` द्वारा प्रस्तुत SVG स्रोत को परिवर्तित करें। परिणाम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित आउटपुट डेटा है।

```java
public static void ConvertSVG(Url url, PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| url | Url | SVG स्रोत दस्तावेज़ [`URL`](../../../com.aspose.html/url/) - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)। |
| provider | ICreateStreamProvider | ज्ञात (देखें [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

इस [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) को देखें जहाँ आपको SVG को PDF में परिवर्तित करने की जानकारी मिलती है, [`Converter`](../) क्लास की ConvertSVG() मेथड्स का उपयोग करके और कैसे [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें।

SVG को PDF में परिवर्तित करें

Converter क्लास कई SVG विशिष्ट रूपांतरण PDF में प्रदान करती है। SVG को PDF में परिवर्तित करने के लिए, आपको कुछ सरल चरणों वाले परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि String स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। एक नया [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ बनाएं। आप वैकल्पिक रूप से [`configuration`](../../../com.aspose.html/configuration/) को विकल्प पैरामीटर के रूप में जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को PDF परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर होते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) प्रदान करता है जो SVG को PDF में उच्च गुणवत्ता, आसान और तेज़ी से परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // इनपुट फ़ाइल पथ के आधार पर Url बनाएं
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // डिफ़ॉल्ट PdfSaveOptions ऑब्जेक्ट परिभाषित करें
      var options = new PdfSaveOptions();

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(sourceUrl, options, sp);
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

## ConvertSVG(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_12}

`[`URL`](../../../com.aspose.html/url/)` द्वारा प्रस्तुत SVG स्रोत को परिवर्तित करें। परिणाम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित आउटपुट डेटा है।

```java
public static void ConvertSVG(Url url, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| url | Url | SVG स्रोत दस्तावेज़ [`URL`](../../../com.aspose.html/url/) - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट को दर्शाता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)। |
| provider | ICreateStreamProvider | ज्ञात (देखें [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

इस [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) को देखें जहाँ आपको SVG को PDF में परिवर्तित करने की जानकारी मिलती है, [`Converter`](../) क्लास की ConvertSVG() मेथड्स का उपयोग करके और कैसे [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें।

SVG को PDF में परिवर्तित करें

Converter क्लास कई SVG विशिष्ट रूपांतरण PDF में प्रदान करती है। SVG को PDF में परिवर्तित करने के लिए, आपको कुछ सरल चरणों वाले परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि String स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। एक नया [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ बनाएं। आप वैकल्पिक रूप से [`configuration`](../../../com.aspose.html/configuration/) को विकल्प पैरामीटर के रूप में जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को PDF परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर होते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) प्रदान करता है जो SVG को PDF में उच्च गुणवत्ता, आसान और तेज़ी से परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // इनपुट फ़ाइल पथ के आधार पर Url बनाएं
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // डिफ़ॉल्ट PdfSaveOptions ऑब्जेक्ट परिभाषित करें
      var options = new PdfSaveOptions();

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
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

## ConvertSVG(String, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_36}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत SVG स्रोत को PDF में परिवर्तित करें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित है।

```java
public static void ConvertSVG(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| sourcePath | String | SVG स्रोत पूर्ण फ़ाइल पथ। |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)। |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

इस [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) को देखें जहाँ आपको SVG को PDF में परिवर्तित करने की जानकारी मिलती है, [`Converter`](../) क्लास की ConvertSVG() मेथड्स का उपयोग करके और कैसे [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें।

SVG को PDF में परिवर्तित करें

Converter क्लास कई SVG विशिष्ट रूपांतरण PDF में प्रदान करती है। SVG को PDF में परिवर्तित करने के लिए, आपको कुछ सरल चरणों वाले परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि String स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। एक नया [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ बनाएं। आप वैकल्पिक रूप से [`configuration`](../../../com.aspose.html/configuration/) को विकल्प पैरामीटर के रूप में जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को PDF परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर होते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) प्रदान करता है जो SVG को PDF में उच्च गुणवत्ता, आसान और तेज़ी से परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // डिफ़ॉल्ट PdfSaveOptions ऑब्जेक्ट परिभाषित करें
      var options = new PdfSaveOptions();

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(sourcePath, options, sp);
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

## ConvertSVG(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_28}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत SVG स्रोत को PDF में परिवर्तित करें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित है।

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| sourcePath | String | SVG स्रोत पूर्ण फ़ाइल पथ। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट को दर्शाता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)। |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

इस [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) को देखें जहाँ आपको SVG को PDF में परिवर्तित करने की जानकारी मिलती है, [`Converter`](../) क्लास की ConvertSVG() मेथड्स का उपयोग करके और कैसे [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें।

SVG को PDF में परिवर्तित करें

Converter क्लास कई SVG विशिष्ट रूपांतरण PDF में प्रदान करती है। SVG को PDF में परिवर्तित करने के लिए, आपको कुछ सरल चरणों वाले परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि String स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। एक नया [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ बनाएं। आप वैकल्पिक रूप से [`configuration`](../../../com.aspose.html/configuration/) को विकल्प पैरामीटर के रूप में जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को PDF परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर होते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) प्रदान करता है जो SVG को PDF में उच्च गुणवत्ता, आसान और तेज़ी से परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // डिफ़ॉल्ट PdfSaveOptions ऑब्जेक्ट परिभाषित करें
      var options = new PdfSaveOptions();

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
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

## ConvertSVG(String, String, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_52}

इनलाइन सामग्री द्वारा प्रस्तुत SVG स्रोत को PDF में परिवर्तित करें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित है।

```java
public static void ConvertSVG(String content, String baseUri, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| सामग्री | String | String के रूप में इनलाइन SVG सामग्री। |
| baseUri | String | दस्तावेज़ का बेस URI। इसे वर्तमान निर्देशिका पथ के साथ मिलाकर एक पूर्ण URL बनाया जाएगा। |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)। |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

इस [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) को देखें जहाँ आपको SVG को PDF में परिवर्तित करने की जानकारी मिलती है, [`Converter`](../) क्लास की ConvertSVG() मेथड्स का उपयोग करके और कैसे [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें।

SVG को PDF में परिवर्तित करें

Converter क्लास कई SVG विशिष्ट रूपांतरण PDF में प्रदान करती है। SVG को PDF में परिवर्तित करने के लिए, आपको कुछ सरल चरणों वाले परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि String स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। एक नया [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ बनाएं। आप वैकल्पिक रूप से [`configuration`](../../../com.aspose.html/configuration/) को विकल्प पैरामीटर के रूप में जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को PDF परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर होते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) प्रदान करता है जो SVG को PDF में उच्च गुणवत्ता, आसान और तेज़ी से परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // डिफ़ॉल्ट PdfSaveOptions ऑब्जेक्ट परिभाषित करें
      var options = new PdfSaveOptions();

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### संबंधित देखें

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_44}

इनलाइन सामग्री द्वारा प्रस्तुत SVG स्रोत को PDF में परिवर्तित करें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित है।

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| सामग्री | String | String के रूप में इनलाइन SVG सामग्री। |
| baseUri | String | दस्तावेज़ का बेस URI। इसे वर्तमान निर्देशिका पथ के साथ मिलाकर एक पूर्ण URL बनाया जाएगा। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट को दर्शाता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)। |
| provider | ICreateStreamProvider | ज्ञात (देखें [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

इस [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) को देखें जहाँ आपको SVG को PDF में परिवर्तित करने की जानकारी मिलती है, [`Converter`](../) क्लास की ConvertSVG() मेथड्स का उपयोग करके और कैसे [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें।

SVG को PDF में परिवर्तित करें

Converter क्लास कई SVG विशिष्ट रूपांतरण PDF में प्रदान करती है। SVG को PDF में परिवर्तित करने के लिए, आपको कुछ सरल चरणों वाले परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि String स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। एक नया [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ऑब्जेक्ट विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ बनाएं। आप वैकल्पिक रूप से [`configuration`](../../../com.aspose.html/configuration/) को विकल्प पैरामीटर के रूप में जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को PDF परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के आधार पर तीन या अधिक पैरामीटर होते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) प्रदान करता है जो SVG को PDF में उच्च गुणवत्ता, आसान और तेज़ी से परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // डिफ़ॉल्ट PdfSaveOptions ऑब्जेक्ट परिभाषित करें
      var options = new PdfSaveOptions();

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
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

## ConvertSVG(SVGDocument, ImageSaveOptions, String) {#convertsvg_3}

[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) द्वारा प्रस्तुत SVG स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित छवि फ़ाइल है।

```java
public static void ConvertSVG(SVGDocument source, ImageSaveOptions options, String outputPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| source | SVGDocument | [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) द्वारा प्रस्तुत रूपांतरण स्रोत। |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) आदि निर्दिष्ट कर सकते हैं। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण इमेज फ़ाइल पथ। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

जहाँ आप ConvertSVG() मेथड्स का उपयोग करके SVG को JPG में परिवर्तित करने के बारे में जानकारी पा सकते हैं, उस [लेख](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) को देखें, जो [`Converter`](../) क्लास से संबंधित है और कैसे [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें। अन्य लोकप्रिय इमेज फ़ॉर्मैट से संबंधित लेख: [SVG से PNG रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG से BMP रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG से GIF रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) और [SVG से TIFF रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG को छवि में परिवर्तित करें

Converter क्लास लोकप्रिय फ़ॉर्मैट में छवि में कई SVG‑विशिष्ट रूपांतरण प्रदान करती है। SVG को छवि में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि स्ट्रिंग स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन का उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट बनाएं। ध्यान दें कि डिफ़ॉल्ट इमेज फ़ॉर्मैट PNG है। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को इमेज परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के अनुसार तीन या अधिक पैरामीटर हो सकते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG से JPG कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-jpg) प्रदान करता है जो उच्च गुणवत्ता, सरलता और तेज़ी से SVG को JPG में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, उन्हें परिवर्तित करें और कुछ ही सेकंड में परिणाम प्राप्त करें!

विभिन्न फ़ॉर्मैट के लिए अन्य लोकप्रिय इमेज कनवर्टर यहाँ पाए जा सकते हैं: [SVG से PNG कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG से BMP कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG से GIF कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-gif) और [SVG से TIFF कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // डिफ़ॉल्ट ImageSaveOptions ऑब्जेक्ट को परिभाषित करें
      var options = new ImageSaveOptions();

      // SVG दस्तावेज़ को रूपांतरण स्रोत के रूप में बनाएं
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, ImageSaveOptions, String) {#convertsvg_19}

[`URL`](../../../com.aspose.html/url/) द्वारा प्रस्तुत SVG स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित छवि फ़ाइल है।

```java
public static void ConvertSVG(Url url, ImageSaveOptions options, String outputPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| url | Url | SVG स्रोत दस्तावेज़ [`URL`](../../../com.aspose.html/url/) - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) आदि निर्दिष्ट कर सकते हैं। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण इमेज फ़ाइल पथ। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

जहाँ आप ConvertSVG() मेथड्स का उपयोग करके SVG को JPG में परिवर्तित करने के बारे में जानकारी पा सकते हैं, उस [लेख](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) को देखें, जो [`Converter`](../) क्लास से संबंधित है और कैसे [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें। अन्य लोकप्रिय इमेज फ़ॉर्मैट से संबंधित लेख: [SVG से PNG रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG से BMP रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG से GIF रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) और [SVG से TIFF रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG को छवि में परिवर्तित करें

Converter क्लास लोकप्रिय फ़ॉर्मैट में छवि में कई SVG‑विशिष्ट रूपांतरण प्रदान करती है। SVG को छवि में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि स्ट्रिंग स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन का उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट बनाएं। ध्यान दें कि डिफ़ॉल्ट इमेज फ़ॉर्मैट PNG है। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को इमेज परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के अनुसार तीन या अधिक पैरामीटर हो सकते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG से JPG कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-jpg) प्रदान करता है जो उच्च गुणवत्ता, सरलता और तेज़ी से SVG को JPG में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, उन्हें परिवर्तित करें और कुछ ही सेकंड में परिणाम प्राप्त करें!

विभिन्न फ़ॉर्मैट के लिए अन्य लोकप्रिय इमेज कनवर्टर यहाँ पाए जा सकते हैं: [SVG से PNG कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG से BMP कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG से GIF कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-gif) और [SVG से TIFF कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // इनपुट फ़ाइल पथ के आधार पर Url बनाएं
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // डिफ़ॉल्ट ImageSaveOptions ऑब्जेक्ट को परिभाषित करें
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(sourceUrl, options, resultPath);
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

## ConvertSVG(Url, Configuration, ImageSaveOptions, String) {#convertsvg_11}

[`URL`](../../../com.aspose.html/url/) द्वारा प्रस्तुत SVG स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित छवि फ़ाइल है।

```java
public static void ConvertSVG(Url url, Configuration configuration, ImageSaveOptions options, 
    String outputPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| url | Url | SVG स्रोत दस्तावेज़ [`URL`](../../../com.aspose.html/url/) - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट को दर्शाता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) आदि निर्दिष्ट कर सकते हैं। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण इमेज फ़ाइल पथ। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

जहाँ आप ConvertSVG() मेथड्स का उपयोग करके SVG को JPG में परिवर्तित करने के बारे में जानकारी पा सकते हैं, उस [लेख](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) को देखें, जो [`Converter`](../) क्लास से संबंधित है और कैसे [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें। अन्य लोकप्रिय इमेज फ़ॉर्मैट से संबंधित लेख: [SVG से PNG रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG से BMP रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG से GIF रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) और [SVG से TIFF रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG को छवि में परिवर्तित करें

Converter क्लास लोकप्रिय फ़ॉर्मैट में छवि में कई SVG‑विशिष्ट रूपांतरण प्रदान करती है। SVG को छवि में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि स्ट्रिंग स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन का उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट बनाएं। ध्यान दें कि डिफ़ॉल्ट इमेज फ़ॉर्मैट PNG है। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को इमेज परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के अनुसार तीन या अधिक पैरामीटर हो सकते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG से JPG कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-jpg) प्रदान करता है जो उच्च गुणवत्ता, सरलता और तेज़ी से SVG को JPG में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, उन्हें परिवर्तित करें और कुछ ही सेकंड में परिणाम प्राप्त करें!

विभिन्न फ़ॉर्मैट के लिए अन्य लोकप्रिय इमेज कनवर्टर यहाँ पाए जा सकते हैं: [SVG से PNG कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG से BMP कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG से GIF कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-gif) और [SVG से TIFF कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // इनपुट फ़ाइल पथ के आधार पर Url बनाएं
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // डिफ़ॉल्ट ImageSaveOptions ऑब्जेक्ट को परिभाषित करें
      var options = new ImageSaveOptions();

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertSVG(String, ImageSaveOptions, String) {#convertsvg_35}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत SVG स्रोत को इमेज में परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित इमेज फ़ाइल है।

```java
public static void ConvertSVG(String sourcePath, ImageSaveOptions options, String outputPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| sourcePath | String | SVG स्रोत पूर्ण फ़ाइल पथ। |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) आदि निर्दिष्ट कर सकते हैं। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण इमेज फ़ाइल पथ। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

जहाँ आप ConvertSVG() मेथड्स का उपयोग करके SVG को JPG में परिवर्तित करने के बारे में जानकारी पा सकते हैं, उस [लेख](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) को देखें, जो [`Converter`](../) क्लास से संबंधित है और कैसे [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें। अन्य लोकप्रिय इमेज फ़ॉर्मैट से संबंधित लेख: [SVG से PNG रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG से BMP रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG से GIF रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) और [SVG से TIFF रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG को छवि में परिवर्तित करें

Converter क्लास लोकप्रिय फ़ॉर्मैट में छवि में कई SVG‑विशिष्ट रूपांतरण प्रदान करती है। SVG को छवि में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि स्ट्रिंग स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन का उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट बनाएं। ध्यान दें कि डिफ़ॉल्ट इमेज फ़ॉर्मैट PNG है। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को इमेज परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के अनुसार तीन या अधिक पैरामीटर हो सकते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG से JPG कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-jpg) प्रदान करता है जो उच्च गुणवत्ता, सरलता और तेज़ी से SVG को JPG में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, उन्हें परिवर्तित करें और कुछ ही सेकंड में परिणाम प्राप्त करें!

विभिन्न फ़ॉर्मैट के लिए अन्य लोकप्रिय इमेज कनवर्टर यहाँ पाए जा सकते हैं: [SVG से PNG कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG से BMP कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG से GIF कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-gif) और [SVG से TIFF कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // डिफ़ॉल्ट ImageSaveOptions ऑब्जेक्ट को परिभाषित करें
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, ImageSaveOptions, String) {#convertsvg_27}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत SVG स्रोत को इमेज में परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित इमेज फ़ाइल है।

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| sourcePath | String | SVG स्रोत पूर्ण फ़ाइल पथ। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट को दर्शाता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) आदि निर्दिष्ट कर सकते हैं। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण इमेज फ़ाइल पथ। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

जहाँ आप ConvertSVG() मेथड्स का उपयोग करके SVG को JPG में परिवर्तित करने के बारे में जानकारी पा सकते हैं, उस [लेख](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) को देखें, जो [`Converter`](../) क्लास से संबंधित है और कैसे [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें। अन्य लोकप्रिय इमेज फ़ॉर्मैट से संबंधित लेख: [SVG से PNG रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG से BMP रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG से GIF रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) और [SVG से TIFF रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG को छवि में परिवर्तित करें

Converter क्लास लोकप्रिय फ़ॉर्मैट में छवि में कई SVG‑विशिष्ट रूपांतरण प्रदान करती है। SVG को छवि में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि स्ट्रिंग स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन का उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट बनाएं। ध्यान दें कि डिफ़ॉल्ट इमेज फ़ॉर्मैट PNG है। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को इमेज परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के अनुसार तीन या अधिक पैरामीटर हो सकते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG से JPG कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-jpg) प्रदान करता है जो उच्च गुणवत्ता, सरलता और तेज़ी से SVG को JPG में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, उन्हें परिवर्तित करें और कुछ ही सेकंड में परिणाम प्राप्त करें!

विभिन्न फ़ॉर्मैट के लिए अन्य लोकप्रिय इमेज कनवर्टर यहाँ पाए जा सकते हैं: [SVG से PNG कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG से BMP कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG से GIF कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-gif) और [SVG से TIFF कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // डिफ़ॉल्ट ImageSaveOptions ऑब्जेक्ट को परिभाषित करें
      var options = new ImageSaveOptions();

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
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

## ConvertSVG(String, String, ImageSaveOptions, String) {#convertsvg_51}

इनलाइन सामग्री द्वारा प्रस्तुत SVG स्रोत को इमेज में परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित इमेज फ़ाइल है।

```java
public static void ConvertSVG(String content, String baseUri, ImageSaveOptions options, 
    String outputPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| सामग्री | String | String के रूप में इनलाइन SVG सामग्री। |
| baseUri | String | दस्तावेज़ का बेस URI। इसे वर्तमान निर्देशिका पथ के साथ मिलाकर एक पूर्ण URL बनाया जाएगा। |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) आदि निर्दिष्ट कर सकते हैं। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण इमेज फ़ाइल पथ। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

जहाँ आप ConvertSVG() मेथड्स का उपयोग करके SVG को JPG में परिवर्तित करने के बारे में जानकारी पा सकते हैं, उस [लेख](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) को देखें, जो [`Converter`](../) क्लास से संबंधित है और कैसे [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें। अन्य लोकप्रिय इमेज फ़ॉर्मैट से संबंधित लेख: [SVG से PNG रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG से BMP रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG से GIF रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) और [SVG से TIFF रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG को छवि में परिवर्तित करें

Converter क्लास लोकप्रिय फ़ॉर्मैट में छवि में कई SVG‑विशिष्ट रूपांतरण प्रदान करती है। SVG को छवि में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि स्ट्रिंग स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन का उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट बनाएं। ध्यान दें कि डिफ़ॉल्ट इमेज फ़ॉर्मैट PNG है। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को इमेज परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के अनुसार तीन या अधिक पैरामीटर हो सकते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG से JPG कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-jpg) प्रदान करता है जो उच्च गुणवत्ता, सरलता और तेज़ी से SVG को JPG में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, उन्हें परिवर्तित करें और कुछ ही सेकंड में परिणाम प्राप्त करें!

विभिन्न फ़ॉर्मैट के लिए अन्य लोकप्रिय इमेज कनवर्टर यहाँ पाए जा सकते हैं: [SVG से PNG कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG से BMP कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG से GIF कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-gif) और [SVG से TIFF कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // इनलाइन SVG सामग्री को फ़ॉर्म करें
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // डिफ़ॉल्ट ImageSaveOptions ऑब्जेक्ट को परिभाषित करें
      var options = new ImageSaveOptions();

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### संबंधित देखें

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, ImageSaveOptions, String) {#convertsvg_43}

इनलाइन सामग्री द्वारा प्रस्तुत SVG स्रोत को इमेज में परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित इमेज फ़ाइल है।

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| सामग्री | String | String के रूप में इनलाइन SVG सामग्री। |
| baseUri | String | दस्तावेज़ का बेस URI। इसे वर्तमान निर्देशिका पथ के साथ मिलाकर एक पूर्ण URL बनाया जाएगा। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट को दर्शाता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) आदि निर्दिष्ट कर सकते हैं। |
| outputPath | String | आउटपुट रूपांतरण परिणाम के रूप में पूर्ण इमेज फ़ाइल पथ। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

जहाँ आप ConvertSVG() मेथड्स का उपयोग करके SVG को JPG में परिवर्तित करने के बारे में जानकारी पा सकते हैं, उस [लेख](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) को देखें, जो [`Converter`](../) क्लास से संबंधित है और कैसे [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें। अन्य लोकप्रिय इमेज फ़ॉर्मैट से संबंधित लेख: [SVG से PNG रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG से BMP रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG से GIF रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) और [SVG से TIFF रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG को छवि में परिवर्तित करें

Converter क्लास लोकप्रिय फ़ॉर्मैट में छवि में कई SVG‑विशिष्ट रूपांतरण प्रदान करती है। SVG को छवि में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि स्ट्रिंग स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन का उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट बनाएं। ध्यान दें कि डिफ़ॉल्ट इमेज फ़ॉर्मैट PNG है। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को इमेज परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के अनुसार तीन या अधिक पैरामीटर हो सकते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG से JPG कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-jpg) प्रदान करता है जो उच्च गुणवत्ता, सरलता और तेज़ी से SVG को JPG में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, उन्हें परिवर्तित करें और कुछ ही सेकंड में परिणाम प्राप्त करें!

विभिन्न फ़ॉर्मैट के लिए अन्य लोकप्रिय इमेज कनवर्टर यहाँ पाए जा सकते हैं: [SVG से PNG कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG से BMP कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG से GIF कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-gif) और [SVG से TIFF कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // इनलाइन SVG सामग्री को फ़ॉर्म करें
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // डिफ़ॉल्ट ImageSaveOptions ऑब्जेक्ट को परिभाषित करें
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### संबंधित देखें

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_2}

[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) द्वारा प्रस्तुत SVG स्रोत को परिवर्तित करें। परिणाम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित आउटपुट डेटा है।

```java
public static void ConvertSVG(SVGDocument document, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| document | SVGDocument | [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) द्वारा प्रस्तुत रूपांतरण स्रोत। |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) आदि निर्दिष्ट कर सकते हैं। |
| provider | ICreateStreamProvider | ज्ञात (देखें [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

जहाँ आप ConvertSVG() मेथड्स का उपयोग करके SVG को JPG में परिवर्तित करने के बारे में जानकारी पा सकते हैं, उस [लेख](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) को देखें, जो [`Converter`](../) क्लास से संबंधित है और कैसे [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें। अन्य लोकप्रिय इमेज फ़ॉर्मैट से संबंधित लेख: [SVG से PNG रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG से BMP रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG से GIF रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) और [SVG से TIFF रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG को छवि में परिवर्तित करें

Converter क्लास लोकप्रिय फ़ॉर्मैट में छवि में कई SVG‑विशिष्ट रूपांतरण प्रदान करती है। SVG को छवि में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि स्ट्रिंग स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन का उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट बनाएं। ध्यान दें कि डिफ़ॉल्ट इमेज फ़ॉर्मैट PNG है। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को इमेज परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के अनुसार तीन या अधिक पैरामीटर हो सकते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG से JPG कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-jpg) प्रदान करता है जो उच्च गुणवत्ता, सरलता और तेज़ी से SVG को JPG में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, उन्हें परिवर्तित करें और कुछ ही सेकंड में परिणाम प्राप्त करें!

विभिन्न फ़ॉर्मैट के लिए अन्य लोकप्रिय इमेज कनवर्टर यहाँ पाए जा सकते हैं: [SVG से PNG कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG से BMP कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG से GIF कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-gif) और [SVG से TIFF कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // डिफ़ॉल्ट ImageSaveOptions ऑब्जेक्ट को परिभाषित करें
      var options = new ImageSaveOptions();

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // SVG दस्तावेज़ को रूपांतरण स्रोत के रूप में बनाएं
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // रूपांतरण प्रक्रिया शुरू करें
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_18}

`[`URL`](../../../com.aspose.html/url/)` द्वारा प्रस्तुत SVG स्रोत को परिवर्तित करें। परिणाम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित आउटपुट डेटा है।

```java
public static void ConvertSVG(Url url, ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| url | Url | SVG स्रोत दस्तावेज़ [`URL`](../../../com.aspose.html/url/) - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) आदि निर्दिष्ट कर सकते हैं। |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

जहाँ आप ConvertSVG() मेथड्स का उपयोग करके SVG को JPG में परिवर्तित करने के बारे में जानकारी पा सकते हैं, उस [लेख](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) को देखें, जो [`Converter`](../) क्लास से संबंधित है और कैसे [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें। अन्य लोकप्रिय इमेज फ़ॉर्मैट से संबंधित लेख: [SVG से PNG रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG से BMP रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG से GIF रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) और [SVG से TIFF रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG को छवि में परिवर्तित करें

Converter क्लास लोकप्रिय फ़ॉर्मैट में छवि में कई SVG‑विशिष्ट रूपांतरण प्रदान करती है। SVG को छवि में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि स्ट्रिंग स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन का उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट बनाएं। ध्यान दें कि डिफ़ॉल्ट इमेज फ़ॉर्मैट PNG है। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को इमेज परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के अनुसार तीन या अधिक पैरामीटर हो सकते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG से JPG कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-jpg) प्रदान करता है जो उच्च गुणवत्ता, सरलता और तेज़ी से SVG को JPG में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, उन्हें परिवर्तित करें और कुछ ही सेकंड में परिणाम प्राप्त करें!

विभिन्न फ़ॉर्मैट के लिए अन्य लोकप्रिय इमेज कनवर्टर यहाँ पाए जा सकते हैं: [SVG से PNG कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG से BMP कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG से GIF कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-gif) और [SVG से TIFF कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // इनपुट फ़ाइल पथ के आधार पर Url बनाएं
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // डिफ़ॉल्ट ImageSaveOptions ऑब्जेक्ट को परिभाषित करें
      var options = new ImageSaveOptions(ImageFormat.Bmp);

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(sourceUrl, options, sp);
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

## ConvertSVG(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_10}

`[`URL`](../../../com.aspose.html/url/)` द्वारा प्रस्तुत SVG स्रोत को परिवर्तित करें। परिणाम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित आउटपुट डेटा है।

```java
public static void ConvertSVG(Url url, Configuration configuration, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| url | Url | SVG स्रोत दस्तावेज़ [`URL`](../../../com.aspose.html/url/) - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट को दर्शाता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) आदि निर्दिष्ट कर सकते हैं। |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

जहाँ आप ConvertSVG() मेथड्स का उपयोग करके SVG को JPG में परिवर्तित करने के बारे में जानकारी पा सकते हैं, उस [लेख](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) को देखें, जो [`Converter`](../) क्लास से संबंधित है और कैसे [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें। अन्य लोकप्रिय इमेज फ़ॉर्मैट से संबंधित लेख: [SVG से PNG रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG से BMP रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG से GIF रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) और [SVG से TIFF रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG को छवि में परिवर्तित करें

Converter क्लास लोकप्रिय फ़ॉर्मैट में छवि में कई SVG‑विशिष्ट रूपांतरण प्रदान करती है। SVG को छवि में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि स्ट्रिंग स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन का उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट बनाएं। ध्यान दें कि डिफ़ॉल्ट इमेज फ़ॉर्मैट PNG है। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को इमेज परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के अनुसार तीन या अधिक पैरामीटर हो सकते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG से JPG कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-jpg) प्रदान करता है जो उच्च गुणवत्ता, सरलता और तेज़ी से SVG को JPG में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, उन्हें परिवर्तित करें और कुछ ही सेकंड में परिणाम प्राप्त करें!

विभिन्न फ़ॉर्मैट के लिए अन्य लोकप्रिय इमेज कनवर्टर यहाँ पाए जा सकते हैं: [SVG से PNG कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG से BMP कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG से GIF कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-gif) और [SVG से TIFF कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // इनपुट फ़ाइल पथ के आधार पर Url बनाएं
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // डिफ़ॉल्ट ImageSaveOptions ऑब्जेक्ट को परिभाषित करें
      var options = new ImageSaveOptions();

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
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

---

## ConvertSVG(String, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_34}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत SVG स्रोत को छवि में परिवर्तित करें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित है।

```java
public static void ConvertSVG(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| sourcePath | String | SVG स्रोत पूर्ण फ़ाइल पथ। |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) आदि निर्दिष्ट कर सकते हैं। |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

जहाँ आप ConvertSVG() मेथड्स का उपयोग करके SVG को JPG में परिवर्तित करने के बारे में जानकारी पा सकते हैं, उस [लेख](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) को देखें, जो [`Converter`](../) क्लास से संबंधित है और कैसे [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें। अन्य लोकप्रिय इमेज फ़ॉर्मैट से संबंधित लेख: [SVG से PNG रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG से BMP रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG से GIF रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) और [SVG से TIFF रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG को छवि में परिवर्तित करें

Converter क्लास लोकप्रिय फ़ॉर्मैट में छवि में कई SVG‑विशिष्ट रूपांतरण प्रदान करती है। SVG को छवि में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि स्ट्रिंग स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन का उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट बनाएं। ध्यान दें कि डिफ़ॉल्ट इमेज फ़ॉर्मैट PNG है। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को इमेज परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के अनुसार तीन या अधिक पैरामीटर हो सकते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG से JPG कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-jpg) प्रदान करता है जो उच्च गुणवत्ता, सरलता और तेज़ी से SVG को JPG में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, उन्हें परिवर्तित करें और कुछ ही सेकंड में परिणाम प्राप्त करें!

विभिन्न फ़ॉर्मैट के लिए अन्य लोकप्रिय इमेज कनवर्टर यहाँ पाए जा सकते हैं: [SVG से PNG कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG से BMP कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG से GIF कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-gif) और [SVG से TIFF कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // डिफ़ॉल्ट ImageSaveOptions ऑब्जेक्ट को परिभाषित करें
      var options = new ImageSaveOptions();

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(sourcePath, options, sp);
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

## ConvertSVG(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_26}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत SVG स्रोत को छवि में परिवर्तित करें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित है।

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| sourcePath | String | SVG स्रोत पूर्ण फ़ाइल पथ। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट को दर्शाता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) आदि निर्दिष्ट कर सकते हैं। |
| provider | ICreateStreamProvider | ज्ञात (देखें [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

जहाँ आप ConvertSVG() मेथड्स का उपयोग करके SVG को JPG में परिवर्तित करने के बारे में जानकारी पा सकते हैं, उस [लेख](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) को देखें, जो [`Converter`](../) क्लास से संबंधित है और कैसे [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें। अन्य लोकप्रिय इमेज फ़ॉर्मैट से संबंधित लेख: [SVG से PNG रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG से BMP रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG से GIF रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) और [SVG से TIFF रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG को छवि में परिवर्तित करें

Converter क्लास लोकप्रिय फ़ॉर्मैट में छवि में कई SVG‑विशिष्ट रूपांतरण प्रदान करती है। SVG को छवि में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि स्ट्रिंग स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन का उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट बनाएं। ध्यान दें कि डिफ़ॉल्ट इमेज फ़ॉर्मैट PNG है। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को इमेज परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के अनुसार तीन या अधिक पैरामीटर हो सकते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG से JPG कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-jpg) प्रदान करता है जो उच्च गुणवत्ता, सरलता और तेज़ी से SVG को JPG में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, उन्हें परिवर्तित करें और कुछ ही सेकंड में परिणाम प्राप्त करें!

विभिन्न फ़ॉर्मैट के लिए अन्य लोकप्रिय इमेज कनवर्टर यहाँ पाए जा सकते हैं: [SVG से PNG कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG से BMP कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG से GIF कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-gif) और [SVG से TIFF कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // डिफ़ॉल्ट ImageSaveOptions ऑब्जेक्ट को परिभाषित करें
      var options = new ImageSaveOptions(ImageFormat.Tiff);

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
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

## ConvertSVG(String, String, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_50}

इनलाइन सामग्री द्वारा प्रस्तुत SVG स्रोत को छवि में परिवर्तित करें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित है।

```java
public static void ConvertSVG(String content, String baseUri, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| सामग्री | String | String के रूप में इनलाइन SVG सामग्री। |
| baseUri | String | दस्तावेज़ का बेस URI। इसे वर्तमान निर्देशिका पथ के साथ मिलाकर एक पूर्ण URL बनाया जाएगा। |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) आदि निर्दिष्ट कर सकते हैं। |
| provider | ICreateStreamProvider | ज्ञात (देखें [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

जहाँ आप ConvertSVG() मेथड्स का उपयोग करके SVG को JPG में परिवर्तित करने के बारे में जानकारी पा सकते हैं, उस [लेख](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) को देखें, जो [`Converter`](../) क्लास से संबंधित है और कैसे [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें। अन्य लोकप्रिय इमेज फ़ॉर्मैट से संबंधित लेख: [SVG से PNG रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG से BMP रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG से GIF रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) और [SVG से TIFF रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG को छवि में परिवर्तित करें

Converter क्लास लोकप्रिय फ़ॉर्मैट में छवि में कई SVG‑विशिष्ट रूपांतरण प्रदान करती है। SVG को छवि में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि स्ट्रिंग स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन का उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट बनाएं। ध्यान दें कि डिफ़ॉल्ट इमेज फ़ॉर्मैट PNG है। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को इमेज परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के अनुसार तीन या अधिक पैरामीटर हो सकते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG से JPG कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-jpg) प्रदान करता है जो उच्च गुणवत्ता, सरलता और तेज़ी से SVG को JPG में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, उन्हें परिवर्तित करें और कुछ ही सेकंड में परिणाम प्राप्त करें!

विभिन्न फ़ॉर्मैट के लिए अन्य लोकप्रिय इमेज कनवर्टर यहाँ पाए जा सकते हैं: [SVG से PNG कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG से BMP कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG से GIF कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-gif) और [SVG से TIFF कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // डिफ़ॉल्ट ImageSaveOptions ऑब्जेक्ट को परिभाषित करें
      var options = new ImageSaveOptions();

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### संबंधित देखें

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_42}

इनलाइन सामग्री द्वारा प्रस्तुत SVG स्रोत को छवि में परिवर्तित करें। परिणाम आउटपुट डेटा है जो [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन द्वारा निर्मित है।

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| सामग्री | String | String के रूप में इनलाइन SVG सामग्री। |
| baseUri | String | दस्तावेज़ का बेस URI। इसे वर्तमान निर्देशिका पथ के साथ मिलाकर एक पूर्ण URL बनाया जाएगा। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट को दर्शाता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। आप [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) आदि निर्दिष्ट कर सकते हैं। |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) का कार्यान्वयन, जिसका उपयोग आउटपुट स्ट्रीम प्राप्त करने के लिए किया जाएगा। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

जहाँ आप ConvertSVG() मेथड्स का उपयोग करके SVG को JPG में परिवर्तित करने के बारे में जानकारी पा सकते हैं, उस [लेख](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) को देखें, जो [`Converter`](../) क्लास से संबंधित है और कैसे [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर लागू करें। अन्य लोकप्रिय इमेज फ़ॉर्मैट से संबंधित लेख: [SVG से PNG रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG से BMP रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG से GIF रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) और [SVG से TIFF रूपांतरण](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG को छवि में परिवर्तित करें

Converter क्लास लोकप्रिय फ़ॉर्मैट में छवि में कई SVG‑विशिष्ट रूपांतरण प्रदान करती है। SVG को छवि में बदलने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप वैकल्पिक रूप से [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में परिभाषित कर सकते हैं या यहाँ तक कि स्ट्रिंग स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ को परिभाषित करें या आउटपुट डेटा बफ़र के रूप में ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन का उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ऑब्जेक्ट बनाएं। ध्यान दें कि डिफ़ॉल्ट इमेज फ़ॉर्मैट PNG है। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। Converter क्लास की ConvertSVG() मेथड का उपयोग करके SVG को इमेज परिणाम के रूप में सहेजें, जिसमें उपयोगकर्ता परिदृश्य के अनुसार तीन या अधिक पैरामीटर हो सकते हैं। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG से JPG कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-jpg) प्रदान करता है जो उच्च गुणवत्ता, सरलता और तेज़ी से SVG को JPG में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, उन्हें परिवर्तित करें और कुछ ही सेकंड में परिणाम प्राप्त करें!

विभिन्न फ़ॉर्मैट के लिए अन्य लोकप्रिय इमेज कनवर्टर यहाँ पाए जा सकते हैं: [SVG से PNG कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG से BMP कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG से GIF कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-gif) और [SVG से TIFF कनवर्टर](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider कार्यान्वयन में से एक का उपयोग करें
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // डिफ़ॉल्ट ImageSaveOptions ऑब्जेक्ट को परिभाषित करें
      var options = new ImageSaveOptions();

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
```

*OutputFolder - user output file path.

### संबंधित देखें

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, XpsSaveOptions, String) {#convertsvg_7}

[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) द्वारा प्रस्तुत SVG स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित xps फ़ाइल है।

```java
public static void ConvertSVG(SVGDocument source, XpsSaveOptions options, String outputPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| source | SVGDocument | [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) द्वारा प्रस्तुत रूपांतरण स्रोत। |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट का उपयोग आपको रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options)। |
| outputPath | String | आउटपुट परिवर्तन परिणाम के रूप में पूर्ण xps फ़ाइल पथ। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) देखें जहाँ आप ConvertSVG() मेथड्स का उपयोग करके SVG को XPS में परिवर्तित करने की जानकारी और [`Converter`](../) क्लास तथा [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को लागू करने के बारे में जानकारी पा सकते हैं।

SVG को XPS में परिवर्तित करें

Converter क्लास कई SVG-विशिष्ट रूपांतरण XPS में प्रदान करती है। SVG को XPS में परिवर्तित करने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। एक मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में भी परिभाषित कर सकते हैं या यहाँ तक कि स्ट्रिंग स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट बनाएं। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। उपयोगकर्ता परिदृश्य पर निर्भर तीन या अधिक पैरामीटर के साथ SVG को XPS परिणाम के रूप में सहेजने के लिए Converter क्लास की ConvertSVG() मेथड का उपयोग करें। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से SVG को XPS में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result");

      // डिफ़ॉल्ट XpsSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new XpsSaveOptions();

      // SVG दस्तावेज़ को रूपांतरण स्रोत के रूप में बनाएं
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
		// डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
		Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, XpsSaveOptions, String) {#convertsvg_23}

[`URL`](../../../com.aspose.html/url/) द्वारा प्रस्तुत SVG स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित xps फ़ाइल है।

```java
public static void ConvertSVG(Url url, XpsSaveOptions options, String outputPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| url | Url | SVG स्रोत दस्तावेज़ [`URL`](../../../com.aspose.html/url/) - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट का उपयोग आपको रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options)। |
| outputPath | String | आउटपुट परिवर्तन परिणाम के रूप में पूर्ण xps फ़ाइल पथ। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) देखें जहाँ आप ConvertSVG() मेथड्स का उपयोग करके SVG को XPS में परिवर्तित करने की जानकारी और [`Converter`](../) क्लास तथा [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को लागू करने के बारे में जानकारी पा सकते हैं।

SVG को XPS में परिवर्तित करें

Converter क्लास कई SVG-विशिष्ट रूपांतरण XPS में प्रदान करती है। SVG को XPS में परिवर्तित करने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। एक मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में भी परिभाषित कर सकते हैं या यहाँ तक कि स्ट्रिंग स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट बनाएं। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। उपयोगकर्ता परिदृश्य पर निर्भर तीन या अधिक पैरामीटर के साथ SVG को XPS परिणाम के रूप में सहेजने के लिए Converter क्लास की ConvertSVG() मेथड का उपयोग करें। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से SVG को XPS में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // इनपुट फ़ाइल पथ के आधार पर Url बनाएं
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // डिफ़ॉल्ट XpsSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new XpsSaveOptions();

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(sourceUrl, options, resultPath);
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

## ConvertSVG(Url, Configuration, XpsSaveOptions, String) {#convertsvg_15}

[`URL`](../../../com.aspose.html/url/) द्वारा प्रस्तुत SVG स्रोत को परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित xps फ़ाइल है।

```java
public static void ConvertSVG(Url url, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| url | Url | SVG स्रोत दस्तावेज़ [`URL`](../../../com.aspose.html/url/) - एक सार्वभौमिक पहचानकर्ता (URL) का ऑब्जेक्ट प्रतिनिधित्व प्रदान करता है। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट को दर्शाता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट का उपयोग आपको रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options)। |
| outputPath | String | आउटपुट परिवर्तन परिणाम के रूप में पूर्ण xps फ़ाइल पथ। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) देखें जहाँ आप ConvertSVG() मेथड्स का उपयोग करके SVG को XPS में परिवर्तित करने की जानकारी और [`Converter`](../) क्लास तथा [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को लागू करने के बारे में जानकारी पा सकते हैं।

SVG को XPS में परिवर्तित करें

Converter क्लास कई SVG-विशिष्ट रूपांतरण XPS में प्रदान करती है। SVG को XPS में परिवर्तित करने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। एक मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में भी परिभाषित कर सकते हैं या यहाँ तक कि स्ट्रिंग स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट बनाएं। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। उपयोगकर्ता परिदृश्य पर निर्भर तीन या अधिक पैरामीटर के साथ SVG को XPS परिणाम के रूप में सहेजने के लिए Converter क्लास की ConvertSVG() मेथड का उपयोग करें। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से SVG को XPS में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // इनपुट फ़ाइल पथ के आधार पर Url बनाएं
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // डिफ़ॉल्ट XpsSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new XpsSaveOptions();

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### संबंधित देखें

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, XpsSaveOptions, String) {#convertsvg_39}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत SVG स्रोत को XPS में परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित XPS फ़ाइल है।

```java
public static void ConvertSVG(String sourcePath, XpsSaveOptions options, String outputPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| sourcePath | String | SVG स्रोत पूर्ण फ़ाइल पथ। |
| options | XpsSaveOptions | `XpsSaveOptions` ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। |
| outputPath | String | आउटपुट परिवर्तन परिणाम के रूप में पूर्ण xps फ़ाइल पथ। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) देखें जहाँ आप ConvertSVG() मेथड्स का उपयोग करके SVG को XPS में परिवर्तित करने की जानकारी और [`Converter`](../) क्लास तथा [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को लागू करने के बारे में जानकारी पा सकते हैं।

SVG को XPS में परिवर्तित करें

Converter क्लास कई SVG-विशिष्ट रूपांतरण XPS में प्रदान करती है। SVG को XPS में परिवर्तित करने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। एक मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में भी परिभाषित कर सकते हैं या यहाँ तक कि स्ट्रिंग स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट बनाएं। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। उपयोगकर्ता परिदृश्य पर निर्भर तीन या अधिक पैरामीटर के साथ SVG को XPS परिणाम के रूप में सहेजने के लिए Converter क्लास की ConvertSVG() मेथड का उपयोग करें। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से SVG को XPS में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // डिफ़ॉल्ट XpsSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new XpsSaveOptions();

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### संबंधित देखें

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, XpsSaveOptions, String) {#convertsvg_31}

पूर्ण फ़ाइल पथ द्वारा प्रस्तुत SVG स्रोत को XPS में परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित XPS फ़ाइल है।

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| sourcePath | String | SVG स्रोत पूर्ण फ़ाइल पथ। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट को दर्शाता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट का उपयोग आपको रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options)। |
| outputPath | String | आउटपुट परिवर्तन परिणाम के रूप में पूर्ण xps फ़ाइल पथ। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) देखें जहाँ आप ConvertSVG() मेथड्स का उपयोग करके SVG को XPS में परिवर्तित करने की जानकारी और [`Converter`](../) क्लास तथा [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को लागू करने के बारे में जानकारी पा सकते हैं।

SVG को XPS में परिवर्तित करें

Converter क्लास कई SVG-विशिष्ट रूपांतरण XPS में प्रदान करती है। SVG को XPS में परिवर्तित करने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। एक मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में भी परिभाषित कर सकते हैं या यहाँ तक कि स्ट्रिंग स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट बनाएं। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। उपयोगकर्ता परिदृश्य पर निर्भर तीन या अधिक पैरामीटर के साथ SVG को XPS परिणाम के रूप में सहेजने के लिए Converter क्लास की ConvertSVG() मेथड का उपयोग करें। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से SVG को XPS में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // डिफ़ॉल्ट XpsSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new XpsSaveOptions();

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
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

## ConvertSVG(String, String, XpsSaveOptions, String) {#convertsvg_55}

इनलाइन सामग्री द्वारा प्रस्तुत SVG स्रोत को XPS में परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित xps फ़ाइल है।

```java
public static void ConvertSVG(String content, String baseUri, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| सामग्री | String | String के रूप में इनलाइन SVG सामग्री। |
| baseUri | String | दस्तावेज़ का बेस URI। इसे वर्तमान निर्देशिका पथ के साथ मिलाकर एक पूर्ण URL बनाया जाएगा। |
| options | XpsSaveOptions | `XpsSaveOptions` ऑब्जेक्ट का उपयोग रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। |
| outputPath | String | आउटपुट परिवर्तन परिणाम के रूप में पूर्ण xps फ़ाइल पथ। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) देखें जहाँ आप ConvertSVG() मेथड्स का उपयोग करके SVG को XPS में परिवर्तित करने की जानकारी और [`Converter`](../) क्लास तथा [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को लागू करने के बारे में जानकारी पा सकते हैं।

SVG को XPS में परिवर्तित करें

Converter क्लास कई SVG-विशिष्ट रूपांतरण XPS में प्रदान करती है। SVG को XPS में परिवर्तित करने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। एक मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में भी परिभाषित कर सकते हैं या यहाँ तक कि स्ट्रिंग स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट बनाएं। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। उपयोगकर्ता परिदृश्य पर निर्भर तीन या अधिक पैरामीटर के साथ SVG को XPS परिणाम के रूप में सहेजने के लिए Converter क्लास की ConvertSVG() मेथड का उपयोग करें। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से SVG को XPS में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // इनलाइन SVG सामग्री को फ़ॉर्म करें
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // डिफ़ॉल्ट XpsSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new XpsSaveOptions();

      // रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### संबंधित देखें

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, XpsSaveOptions, String) {#convertsvg_47}

इनलाइन सामग्री द्वारा प्रस्तुत SVG स्रोत को XPS में परिवर्तित करें। परिणाम आउटपुट फ़ाइल पथ द्वारा निर्मित xps फ़ाइल है।

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| सामग्री | String | String के रूप में इनलाइन SVG सामग्री। |
| baseUri | String | दस्तावेज़ का बेस URI। इसे वर्तमान निर्देशिका पथ के साथ मिलाकर एक पूर्ण URL बनाया जाएगा। |
| configuration | Configuration | पर्यावरण कॉन्फ़िगरेशन। यह [`configuration`](../../../com.aspose.html/configuration/) कॉन्टेक्स्ट ऑब्जेक्ट को दर्शाता है जिसका उपयोग एप्लिकेशन के लिए पर्यावरण सेटिंग्स को सेट करने में किया जाता है। |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट का उपयोग आपको रेंडरिंग प्रक्रिया को ट्यून करने की अनुमति देता है। अधिक जानकारी के लिए देखें [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options)। |
| outputPath | String | आउटपुट परिवर्तन परिणाम के रूप में पूर्ण xps फ़ाइल पथ। |

## टिप्पणियाँ

SVG कनवर्टर

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) देखें जहाँ आप ConvertSVG() मेथड्स का उपयोग करके SVG को XPS में परिवर्तित करने की जानकारी और [`Converter`](../) क्लास तथा [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) और [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) पैरामीटर को लागू करने के बारे में जानकारी पा सकते हैं।

SVG को XPS में परिवर्तित करें

Converter क्लास कई SVG-विशिष्ट रूपांतरण XPS में प्रदान करती है। SVG को XPS में परिवर्तित करने के लिए, आपको कुछ चरणों वाले सरल परिदृश्यों में से एक का पालन करना चाहिए:

रूपांतरण स्रोत। एक मौजूदा स्थानीय SVG फ़ाइल या रिमोट [`Url`](../../../com.aspose.html/url/) को रूपांतरण स्रोत के रूप में पहचानें। आप [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को रूपांतरण स्रोत के रूप में भी परिभाषित कर सकते हैं या यहाँ तक कि स्ट्रिंग स्रोत द्वारा प्रस्तुत इनलाइन SVG सामग्री का उपयोग कर सकते हैं। रूपांतरण परिणाम। परिणाम आउटपुट फ़ाइल पथ निर्धारित करें या ज्ञात या कस्टम [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) इंटरफ़ेस कार्यान्वयन को आउटपुट डेटा बफ़र के रूप में उपयोग करें। विशिष्ट या डिफ़ॉल्ट सेटिंग्स के साथ नया [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ऑब्जेक्ट बनाएं। आप विकल्प पैरामीटर के रूप में [`configuration`](../../../com.aspose.html/configuration/) भी जोड़ सकते हैं। उपयोगकर्ता परिदृश्य पर निर्भर तीन या अधिक पैरामीटर के साथ SVG को XPS परिणाम के रूप में सहेजने के लिए Converter क्लास की ConvertSVG() मेथड का उपयोग करें। ऑनलाइन SVG कनवर्टर

Aspose.HTML एक मुफ्त ऑनलाइन [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) प्रदान करता है जो उच्च गुणवत्ता, आसान और तेज़ी से SVG को XPS में परिवर्तित करता है। बस फ़ाइलें अपलोड करें, परिवर्तित करें और कुछ सेकंड में परिणाम प्राप्त करें!

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // इनलाइन SVG सामग्री को फ़ॉर्म करें
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // फ़ॉर्म परिणाम फ़ाइल पथ
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // डिफ़ॉल्ट XpsSaveOptions ऑब्जेक्ट निर्धारित करें
      var options = new XpsSaveOptions();

      // डिफ़ॉल्ट कॉन्फ़िगरेशन के साथ रूपांतरण प्रक्रिया शुरू करें
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### संबंधित देखें

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

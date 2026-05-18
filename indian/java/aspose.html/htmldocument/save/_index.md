---
title: "HTMLDocument.Save"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "HTMLDocument मेथड। दस्तावेज़ को निर्दिष्ट URL द्वारा स्थानीय फ़ाइल में सहेजता है। इस दस्तावेज़ में उपयोग किए गए सभी संसाधन एक सन्निहित फ़ोल्डर में सहेजे जाएंगे जिसका नाम output_file_name _files के रूप में बनाया जाएगा।"
type: docs

url: /hi/java/com.aspose.html/htmldocument/save/
---
## Save(Url) {#save_5}

दस्तावेज़ को निर्दिष्ट url द्वारा स्थानीय फ़ाइल में सहेजता है। इस दस्तावेज़ में उपयोग किए गए सभी संसाधनों को एक सन्निहित फ़ोल्डर में सहेजा जाएगा, जिसका नाम output_file_name + "_files" के रूप में बनाया जाएगा।

```java
public void Save(Url url)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| url | Url | आउटपुट फ़ाइल के लिए स्थानीय [`URL`](../../url/)। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentException | यदि निर्दिष्ट `url` एक वैध स्थानीय फ़ाइल URL नहीं है तो यह उत्पन्न होता है। |

## टिप्पणियाँ

HTML सहेजें

अधिकांश कार्यों के लिए, जिन्हें आपको करना है, दस्तावेज़ को सहेजना आवश्यक है। एक बार जब आप मौजूदा फ़ाइल लोड कर लेते हैं या शून्य से एक HTML दस्तावेज़ बनाते हैं, तो आप अपने परिवर्तन को HTMLDocument.Save() मेथड्स में से किसी एक का उपयोग करके सहेज सकते हैं। ये मेथड्स पथ, URL या आउटपुट स्टोरेज द्वारा निर्दिष्ट स्थानीय फ़ाइल में HTML सहेजने की अनुमति देते हैं। सहेजने के बारे में अधिक जानने के लिए [documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) देखें।

Save(Url) मेथड

HTML दस्तावेज़ सहेजने के लिए पूर्ण Url पथ - 'outputFilePath' निर्दिष्ट करना आवश्यक है। Url(url) कंस्ट्रक्टर निर्दिष्ट url के साथ [`Url`](../../url/) क्लास का एक इंस्टेंस बनाता है। फिर आपको इस इंस्टेंस को Save(Url) मेथड में पास करना चाहिए। दस्तावेज़ निर्दिष्ट url द्वारा स्थानीय फ़ाइल में सहेजा जाएगा। इस दस्तावेज़ में उपयोग किए गए सभी संसाधन एक सन्निहित फ़ोल्डर में सहेजे जाएंगे, जिसका नाम output_file_name + "_files" होगा।

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System;
import System.IO;
import Aspose.Html;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
        
	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	document.Save(new Url(outputFilePath));
}
```

*inputHtmlPath - user input html file.

*outputHtmlPath - user output folder path.

### संबंधित देखें

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler) {#save}

दस्तावेज़ की सामग्री और संसाधनों को [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/) का उपयोग करके सहेजता है।

```java
public void Save(ResourceHandler resourceHandler)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| resourceHandler | ResourceHandler | संसाधन हैंडलर [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)। |

### संबंधित देखें

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String) {#save_10}

दस्तावेज़ को निर्दिष्ट पथ वाली स्थानीय फ़ाइल में सहेजता है। इस दस्तावेज़ में उपयोग किए गए सभी संसाधन एक सन्निहित फ़ोल्डर में सहेजे जाएंगे, जिसका नाम इस प्रकार निर्मित होगा: output_file_name + "_files"।

```java
public void Save(String path)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| पथ | String | आउटपुट फ़ाइल के लिए स्थानीय फ़ाइल सिस्टम पथ। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentException | यदि निर्दिष्ट `path` एक वैध स्थानीय फ़ाइल पथ नहीं है तो यह उत्पन्न होता है। |

## टिप्पणियाँ

HTML सहेजें

अधिकांश कार्यों के लिए, जिन्हें आपको करना है, दस्तावेज़ को सहेजना आवश्यक है। एक बार जब आप मौजूदा फ़ाइल लोड कर लेते हैं या शून्य से एक HTML दस्तावेज़ बनाते हैं, तो आप अपने परिवर्तन को HTMLDocument.Save() मेथड्स में से किसी एक का उपयोग करके सहेज सकते हैं। ये मेथड्स पथ, URL या आउटपुट स्टोरेज द्वारा निर्दिष्ट स्थानीय फ़ाइल में HTML सहेजने की अनुमति देते हैं। सहेजने के बारे में अधिक जानने के लिए [documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) देखें।

Save(String) मेथड एक पैरामीटर के रूप में आउटपुट फ़ाइल के लिए स्थानीय फ़ाइल सिस्टम पथ लेता है और HTML दस्तावेज़ को निर्दिष्ट पथ वाली स्थानीय फ़ाइल में सहेजता है। दस्तावेज़ में उपयोग किए गए सभी संसाधन एक सन्निहित फ़ोल्डर में सहेजे जाएंगे।

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System;
import System.IO;
import Aspose.Html;
...
 using (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (outputHtmlPath == null)
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	document.Save(outputFilePath);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output directory path.

### संबंधित देखें

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, HTMLSaveFormat) {#save_11}

दस्तावेज़ को निर्दिष्ट path द्वारा स्थानीय फ़ाइल में सहेजता है। इस दस्तावेज़ में उपयोग किए गए सभी संसाधनों को एक सन्निहित फ़ोल्डर में सहेजा जाएगा, जिसका नाम output_file_name + "_files" के रूप में बनाया जाएगा।

```java
public void Save(String path, HTMLSaveFormat saveFormat)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| पथ | String | आउटपुट फ़ाइल के लिए स्थानीय फ़ाइल पथ। |
| saveFormat | HTMLSaveFormat | दस्तावेज़ जिस प्रारूप में सहेजा जाता है। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentException | यदि निर्दिष्ट `path` एक वैध स्थानीय फ़ाइल पथ नहीं है तो यह उत्पन्न होता है। |

## टिप्पणियाँ

HTML सहेजें

अधिकांश कार्यों के लिए, जिन्हें आपको करना है, दस्तावेज़ को सहेजना आवश्यक है। एक बार जब आप मौजूदा फ़ाइल लोड कर लेते हैं या शून्य से एक HTML दस्तावेज़ बनाते हैं, तो आप अपने परिवर्तन को HTMLDocument.Save() मेथड्स में से किसी एक का उपयोग करके सहेज सकते हैं। ये मेथड्स पथ, URL या आउटपुट स्टोरेज द्वारा निर्दिष्ट स्थानीय फ़ाइल में HTML सहेजने की अनुमति देते हैं। सहेजने के बारे में अधिक जानने के लिए [documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) देखें।

Save(String, HTMLSaveFormat) मेथड

Save(String, HTMLSaveFormat) मेथड पैरामीटर के रूप में आउटपुट फ़ाइल के लिए स्थानीय फ़ाइल सिस्टम पथ और saveFormat लेता है। The [`HTMLSaveFormat`](../../../com.aspose.html.saving/htmlsaveformat/) एन्यूमरेशन निर्दिष्ट करता है कि दस्तावेज़ किस फ़ॉर्मेट में सहेजा जाता है, यह HTML, MHTML और MD फ़ॉर्मेट हो सकते हैं। मेथड निर्दिष्ट फ़ॉर्मेट में HTML दस्तावेज़ को स्थानीय फ़ाइल में सहेजता है। दस्तावेज़ में उपयोग किए गए सभी संसाधन निकटवर्ती फ़ोल्डर में सहेजे जाएंगे।

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
# HTML input file content
<!DOCTYPE html>
<html lang="en"
   xmlns:xml="http://www.w3.org/XML/1998/package">
<head>
  <meta charset="UTF-8">
  <link rel="stylesheet" href="styles/main.css">
  <title>Title</title>
</head>
<body>
<div id="uniqueIdentifier">Container with ID - identifier</div>
<div class="custom-class">Customized by css class container</div>

<div>
  <p class="pStyle">First styled by pStyle class paragraph</p>
  <p class="pStyle">Second styled by pStyle class paragraph</p>
  <p class="pStyle">Third styled by pStyle class paragraph</p>
  <span class="pStyle">Span styled by pStyle</span>
</div>

<math xmlns="http://www.w3.org/1998/Math/MathML">
  <mrow>...</mrow>
</math>

<div id="smart class">
  <p id="p1" class="ddd kkk">Paragraph styled by class name =ddd kkk=</p>
  <p id="p2" class="ddd fff">Paragraph styled by class name =ddd fff=</p>
  <p id="p3" class="kkk fff">Paragraph styled by class name =kkk fff=</p>
</div>

</body>
</html>

# C# code
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}
	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtml");
	document.Save(outputFilePath, HTMLSaveFormat.MHTML);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

# Content of result file

MIME-Version: 1.0

Content-Type: Multipart/related; boundary="boundary";type=Text/HTML

--boundary

Content-Type: text/html;

Content-Location: result.mhtml

&lt;!DOCTYPE html&gt;&lt;html lang="en" xmlns:xml="http://www.w3.org/XML/1998/package"&gt;&lt;head&gt;

&lt;meta charset="UTF-8"&gt;

&lt;link rel="stylesheet" href="main.css"&gt;

&lt;title&gt;शीर्षक&lt;/title&gt;

&lt;/head&gt;

&lt;body&gt;

&lt;div id="uniqueIdentifier"&gt;आईडी के साथ कंटेनर - पहचानकर्ता&lt;/div&gt;

&lt;div class="custom-class"&gt;सीएसएस क्लास कंटेनर द्वारा अनुकूलित&lt;/div&gt;

&lt;div&gt;

&lt;p class="pStyle"&gt;पहला पैराग्राफ pStyle क्लास द्वारा स्टाइल किया गया&lt;/p&gt;

&lt;p class="pStyle"&gt;दूसरा पैराग्राफ pStyle क्लास द्वारा स्टाइल किया गया&lt;/p&gt;

&lt;p class="pStyle"&gt;तीसरा पैराग्राफ pStyle क्लास द्वारा स्टाइल किया गया&lt;/p&gt;

&lt;span class="pStyle"&gt;स्पैन pStyle द्वारा स्टाइल किया गया&lt;/span&gt;

&lt;/div&gt;

&lt;math xmlns="http://www.w3.org/1998/Math/MathML"&gt;

&lt;mrow&gt;...&lt;/mrow&gt;

&lt;/math&gt;

&lt;div id="smart class"&gt;

&lt;p id="p1" class="ddd kkk"&gt;क्लास नाम =ddd kkk= द्वारा स्टाइल किया गया पैराग्राफ&lt;/p&gt;

&lt;p id="p2" class="ddd fff"&gt;क्लास नाम =ddd fff= द्वारा स्टाइल किया गया पैराग्राफ&lt;/p&gt;

&lt;p id="p3" class="kkk fff"&gt;क्लास नाम =kkk fff= द्वारा स्टाइल किया गया पैराग्राफ&lt;/p&gt;

&lt;/div&gt;

&lt;div&gt;DIV तत्व से नमस्ते&lt;/div&gt;&lt;/body&gt;&lt;/html&gt;

--boundary

Content-Type: text/css;

Content-Location: main.css

.custom-class { color: yellow; background-color: blueviolet; margin-top: 10pt; margin-right: 10pt; margin-bottom: 10pt; margin-left: 10pt; }.pStyle { font-

--boundary--

### संबंधित देखें

* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveFormat) {#save_6}

दस्तावेज़ को निर्दिष्ट url द्वारा स्थानीय फ़ाइल में सहेजता है। इस दस्तावेज़ में उपयोग किए गए सभी संसाधनों को एक सन्निहित फ़ोल्डर में सहेजा जाएगा, जिसका नाम output_file_name + "_files" के रूप में बनाया जाएगा।

```java
public void Save(Url url, HTMLSaveFormat saveFormat)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| url | Url | आउटपुट फ़ाइल के लिए स्थानीय URL। |
| saveFormat | HTMLSaveFormat | दस्तावेज़ जिस प्रारूप में सहेजा जाता है। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentException | यदि निर्दिष्ट `url` एक वैध स्थानीय फ़ाइल URL नहीं है तो यह उत्पन्न होता है। |

## टिप्पणियाँ

HTML सहेजें

अधिकांश कार्यों के लिए, जिन्हें आपको करना है, दस्तावेज़ को सहेजना आवश्यक है। एक बार जब आप मौजूदा फ़ाइल लोड कर लेते हैं या शून्य से एक HTML दस्तावेज़ बनाते हैं, तो आप अपने परिवर्तन को HTMLDocument.Save() मेथड्स में से किसी एक का उपयोग करके सहेज सकते हैं। ये मेथड्स पथ, URL या आउटपुट स्टोरेज द्वारा निर्दिष्ट स्थानीय फ़ाइल में HTML सहेजने की अनुमति देते हैं। सहेजने के बारे में अधिक जानने के लिए [documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) देखें।

Save(Url, HTMLSaveFormat) मेथड

HTML दस्तावेज़ को सहेजने के लिए पूर्ण Url पथ - 'outputFilePath' निर्दिष्ट करना आवश्यक है। Url(url) कन्स्ट्रक्टर निर्दिष्ट url के साथ [`Url`](../../url/) क्लास का एक इंस्टेंस बनाता है। [`HTMLSaveFormat`](../../../com.aspose.html.saving/htmlsaveformat/) एनेमरेशन उस फ़ॉर्मेट को निर्दिष्ट करता है जिसमें दस्तावेज़ सहेजा जाता है, यह HTML, MHTML और MD फ़ॉर्मेट हो सकते हैं। फिर आपको पैरामीटर को Save(url, saveFormat) मेथड में पास करना चाहिए। दस्तावेज़ निर्दिष्ट फ़ॉर्मेट में स्थानीय फ़ाइल में url द्वारा निर्दिष्ट स्थान पर सहेजा जाएगा।

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtml");
	document.Save(new Url(outputFilePath), HTMLSaveFormat.MHTML);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output directory path.

### संबंधित देखें

* class [Url](../../url/)
* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, HTMLSaveFormat) {#save_1}

दस्तावेज़ की सामग्री और संसाधनों को [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/) का उपयोग करके सहेजता है।

```java
public void Save(ResourceHandler resourceHandler, HTMLSaveFormat saveFormat)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| resourceHandler | ResourceHandler | संसाधन हैंडलर [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)। |
| saveFormat | HTMLSaveFormat | दस्तावेज़ जिस प्रारूप में सहेजा जाता है। |

### संबंधित देखें

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, HTMLSaveOptions) {#save_12}

दस्तावेज़ को निर्दिष्ट पथ वाली स्थानीय फ़ाइल में सहेजता है। इस दस्तावेज़ में उपयोग किए गए सभी संसाधन एक सन्निहित फ़ोल्डर में सहेजे जाएंगे, जिसका नाम इस प्रकार निर्मित होगा: output_file_name + "_files"।

```java
public void Save(String path, HTMLSaveOptions saveOptions)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| पथ | String | आउटपुट फ़ाइल का स्थानीय पथ। |
| saveOptions | HTMLSaveOptions | [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) ऑब्जेक्ट संसाधन हैंडलिंग प्रक्रिया प्रबंधन के लिए है। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentException | यदि निर्दिष्ट `path` एक वैध स्थानीय फ़ाइल पथ नहीं है तो यह उत्पन्न होता है। |

## टिप्पणियाँ

HTML सहेजें

अधिकांश कार्यों के लिए, जिन्हें आपको करना है, दस्तावेज़ को सहेजना आवश्यक है। एक बार जब आप मौजूदा फ़ाइल लोड कर लेते हैं या शून्य से एक HTML दस्तावेज़ बनाते हैं, तो आप अपने परिवर्तन को HTMLDocument.Save() मेथड्स में से किसी एक का उपयोग करके सहेज सकते हैं। ये मेथड्स पथ, URL या आउटपुट स्टोरेज द्वारा निर्दिष्ट स्थानीय फ़ाइल में HTML सहेजने की अनुमति देते हैं। सहेजने के बारे में अधिक जानने के लिए [documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) देखें।

Save(String, HTMLSaveOptions) मेथड

Save(String, HTMLSaveOptions) मेथड पैरामीटर के रूप में आउटपुट फ़ाइल के लिए स्थानीय फ़ाइल सिस्टम पाथ, [HTMLSaveOptions](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) क्लास का एक इंस्टेंस लेता है और संसाधनों के साथ HTML दस्तावेज़ को निर्दिष्ट पाथ की स्थानीय फ़ाइल में सहेजता है। HTMLSaveOptions() कन्स्ट्रक्टर एक सहेजने विकल्पों का इंस्टेंस बनाता है जिसमें [`ResourceHandlingOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) प्रॉपर्टीज़ होती हैं जो संसाधन हैंडलिंग के कॉन्फ़िगरेशन के लिए उपयोग होती हैं। दस्तावेज़ में उपयोग किए गए सभी संसाधन एक सटे हुए फ़ोल्डर में सहेजे जाएंगे।

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	// विकल्प क्लास इंस्टेंस को परिभाषित करें
	var options = new HTMLSaveOptions();
	// पृष्ठ हैंडलिंग प्रतिबंध
	options.ResourceHandlingOptions.MaxHandlingDepth = 1;
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### संबंधित देखें

* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveOptions) {#save_7}

दस्तावेज़ को निर्दिष्ट url द्वारा स्थानीय फ़ाइल में सहेजता है। इस दस्तावेज़ में उपयोग किए गए सभी संसाधनों को एक सन्निहित फ़ोल्डर में सहेजा जाएगा, जिसका नाम इस प्रकार बनाया जाएगा: output_file_name + "_files"।

```java
public void Save(Url url, HTMLSaveOptions saveOptions)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| url | Url | आउटपुट फ़ाइल के लिए स्थानीय [`URL`](../../url/)। |
| saveOptions | HTMLSaveOptions | [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) ऑब्जेक्ट संसाधन हैंडलिंग प्रक्रिया प्रबंधन के लिए है। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentException | यदि निर्दिष्ट `url` एक वैध स्थानीय फ़ाइल URL नहीं है तो यह उत्पन्न होता है। |

## टिप्पणियाँ

HTML सहेजें

अधिकांश कार्यों के लिए, जिन्हें आपको करना है, दस्तावेज़ को सहेजना आवश्यक है। एक बार जब आप मौजूदा फ़ाइल लोड कर लेते हैं या शून्य से एक HTML दस्तावेज़ बनाते हैं, तो आप अपने परिवर्तन को HTMLDocument.Save() मेथड्स में से किसी एक का उपयोग करके सहेज सकते हैं। ये मेथड्स पथ, URL या आउटपुट स्टोरेज द्वारा निर्दिष्ट स्थानीय फ़ाइल में HTML सहेजने की अनुमति देते हैं। सहेजने के बारे में अधिक जानने के लिए [documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) देखें।

Save(Url, HTMLSaveOptions) मेथड

HTML दस्तावेज़ को सहेजने के लिए पूर्ण Url पथ निर्दिष्ट करना आवश्यक है। Url(url) कन्स्ट्रक्टर निर्दिष्ट url के साथ [`Url`](../../url/) क्लास का एक इंस्टेंस बनाता है। HTMLSaveOptions() कन्स्ट्रक्टर [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) क्लास का एक इंस्टेंस बनाता है जिसमें ResourceHandlingOptions प्रॉपर्टीज़ होती हैं जो संसाधन हैंडलिंग के कॉन्फ़िगरेशन के लिए उपयोग होती हैं। Save(url, saveOptions) मेथड पैरामीटर लेता है और संसाधनों के साथ HTML दस्तावेज़ को url द्वारा निर्दिष्ट स्थानीय फ़ाइल में सहेजता है।

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	// विकल्प क्लास इंस्टेंस को परिभाषित करें
	var options = new HTMLSaveOptions();
	// पृष्ठ हैंडलिंग प्रतिबंध
	options.ResourceHandlingOptions.MaxHandlingDepth = 1;
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### संबंधित देखें

* class [Url](../../url/)
* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, HTMLSaveOptions) {#save_2}

दस्तावेज़ की सामग्री और संसाधनों को [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/) का उपयोग करके सहेजता है।

```java
public void Save(ResourceHandler resourceHandler, HTMLSaveOptions saveOptions)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| resourceHandler | ResourceHandler | संसाधन हैंडलर [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)। |
| saveOptions | HTMLSaveOptions | HTML सहेजने विकल्प। |

### संबंधित देखें

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, MarkdownSaveOptions) {#save_13}

दस्तावेज़ को निर्दिष्ट पथ वाली स्थानीय फ़ाइल में सहेजता है। इस दस्तावेज़ में उपयोग किए गए सभी संसाधन एक सन्निहित फ़ोल्डर में सहेजे जाएंगे, जिसका नाम इस प्रकार निर्मित होगा: output_file_name + "_files"।

```java
public void Save(String path, MarkdownSaveOptions saveOptions)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| पथ | String | आउटपुट फ़ाइल का स्थानीय पथ। |
| saveOptions | MarkdownSaveOptions | [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) ऑब्जेक्ट उपयोग आपको रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। अधिक जानकारी के लिए [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options) देखें। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentException | यदि निर्दिष्ट `path` एक वैध स्थानीय फ़ाइल पथ नहीं है तो यह उत्पन्न होता है। |

## टिप्पणियाँ

HTML सहेजें

अधिकांश कार्यों के लिए, जिन्हें आपको करना है, दस्तावेज़ को सहेजना आवश्यक है। एक बार जब आप मौजूदा फ़ाइल लोड कर लेते हैं या शून्य से एक HTML दस्तावेज़ बनाते हैं, तो आप अपने परिवर्तन को HTMLDocument.Save() मेथड्स में से किसी एक का उपयोग करके सहेज सकते हैं। ये मेथड्स पथ, URL या आउटपुट स्टोरेज द्वारा निर्दिष्ट स्थानीय फ़ाइल में HTML सहेजने की अनुमति देते हैं। सहेजने के बारे में अधिक जानने के लिए [documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) देखें।

Save(String, MarkdownSaveOptions) मेथड

दस्तावेज़ को सहेजने के लिए आउटपुट फ़ाइल के लिए स्थानीय फ़ाइल सिस्टम पाथ निर्दिष्ट करना आवश्यक है। MarkdownSaveOptions() कन्स्ट्रक्टर [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) क्लास का एक इंस्टेंस बनाता है जिसमें कई प्रॉपर्टीज़ होती हैं। उदाहरण के लिए, आप markdown फ़ॉर्मेटिंग शैली सेट कर सकते हैं, पूर्वनिर्धारित GitLab Flavored Markdown संगत विकल्पों का उपयोग कर सकते हैं और संसाधन हैंडलिंग को कॉन्फ़िगर कर सकते हैं। Save(path, saveOptions) मेथड आउटपुट फ़ाइल के स्थानीय फ़ाइल सिस्टम पाथ और विकल्प इंस्टेंस को पैरामीटर के रूप में लेता है और HTML को संसाधनों के साथ एक Markdown दस्तावेज़ के रूप में निर्दिष्ट पाथ की स्थानीय फ़ाइल में सहेजता है।

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
     
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.md");
	// विकल्प क्लास इंस्टेंस को परिभाषित करें
	var options = new MarkdownSaveOptions();
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file.

*outputHtmlPath - user output folder path.

### संबंधित देखें

* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, MarkdownSaveOptions) {#save_8}

दस्तावेज़ को निर्दिष्ट url द्वारा स्थानीय फ़ाइल में सहेजता है। इस दस्तावेज़ में उपयोग किए गए सभी संसाधनों को एक सन्निहित फ़ोल्डर में सहेजा जाएगा, जिसका नाम इस प्रकार बनाया जाएगा: output_file_name + "_files"।

```java
public void Save(Url url, MarkdownSaveOptions saveOptions)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| url | Url | आउटपुट फ़ाइल के लिए स्थानीय [`URL`](../../url/)। |
| saveOptions | MarkdownSaveOptions | [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) ऑब्जेक्ट उपयोग आपको रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। अधिक जानकारी के लिए [documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options) देखें। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentException | यदि निर्दिष्ट `url` एक वैध स्थानीय फ़ाइल URL नहीं है तो यह उत्पन्न होता है। |

## टिप्पणियाँ

HTML सहेजें

अधिकांश कार्यों के लिए, जिन्हें आपको करना है, दस्तावेज़ को सहेजना आवश्यक है। एक बार जब आप मौजूदा फ़ाइल लोड कर लेते हैं या शून्य से एक HTML दस्तावेज़ बनाते हैं, तो आप अपने परिवर्तन को HTMLDocument.Save() मेथड्स में से किसी एक का उपयोग करके सहेज सकते हैं। ये मेथड्स पथ, URL या आउटपुट स्टोरेज द्वारा निर्दिष्ट स्थानीय फ़ाइल में HTML सहेजने की अनुमति देते हैं। सहेजने के बारे में अधिक जानने के लिए [documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) देखें।

Save(Url, MarkdownSaveOptions) मेथड

दस्तावेज़ को सहेजने के लिए पूर्ण Url पथ निर्दिष्ट करना आवश्यक है। Url(url) कन्स्ट्रक्टर निर्दिष्ट url के साथ [`Url`](../../url/) क्लास का एक इंस्टेंस बनाता है। MarkdownSaveOptions() कन्स्ट्रक्टर [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) क्लास का एक इंस्टेंस बनाता है जिसमें कई प्रॉपर्टीज़ होती हैं। उदाहरण के लिए, आप Markdown फ़ॉर्मेटिंग शैली सेट कर सकते हैं, पूर्वनिर्धारित GitLab Flavored Markdown संगत विकल्पों का उपयोग कर सकते हैं और संसाधन हैंडलिंग को कॉन्फ़िगर कर सकते हैं। Save(url, saveOptions) मेथड url और सहेजने विकल्प इंस्टेंस को पैरामीटर के रूप में लेता है और दस्तावेज़ को संसाधनों के साथ url द्वारा निर्दिष्ट स्थानीय फ़ाइल में सहेजता है।

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.md");
	// विकल्प क्लास इंस्टेंस को परिभाषित करें
	var options = new MarkdownSaveOptions();
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### संबंधित देखें

* class [Url](../../url/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, MarkdownSaveOptions) {#save_3}

दस्तावेज़ की सामग्री और संसाधनों को [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/) का उपयोग करके सहेजता है।

```java
public void Save(ResourceHandler resourceHandler, MarkdownSaveOptions saveOptions)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| resourceHandler | ResourceHandler | संसाधन हैंडलर [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)। |
| saveOptions | MarkdownSaveOptions | Markdown सहेजने विकल्प। |

### संबंधित देखें

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, MHTMLSaveOptions) {#save_14}

दस्तावेज़ को निर्दिष्ट पथ वाली स्थानीय फ़ाइल में सहेजता है। इस दस्तावेज़ में उपयोग किए गए सभी संसाधन एक सन्निहित फ़ोल्डर में सहेजे जाएंगे, जिसका नाम इस प्रकार निर्मित होगा: output_file_name + "_files"।

```java
public void Save(String path, MHTMLSaveOptions saveOptions)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| पथ | String | आउटपुट फ़ाइल का स्थानीय पथ। |
| saveOptions | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) ऑब्जेक्ट उपयोग आपको रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। अधिक जानकारी के लिए [documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options) देखें। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentException | यदि निर्दिष्ट `path` एक वैध स्थानीय फ़ाइल पथ नहीं है तो यह उत्पन्न होता है। |

## टिप्पणियाँ

HTML सहेजें

अधिकांश कार्यों के लिए, जिन्हें आपको करना है, दस्तावेज़ को सहेजना आवश्यक है। एक बार जब आप मौजूदा फ़ाइल लोड कर लेते हैं या शून्य से एक HTML दस्तावेज़ बनाते हैं, तो आप अपने परिवर्तन को HTMLDocument.Save() मेथड्स में से किसी एक का उपयोग करके सहेज सकते हैं। ये मेथड्स पथ, URL या आउटपुट स्टोरेज द्वारा निर्दिष्ट स्थानीय फ़ाइल में HTML सहेजने की अनुमति देते हैं। सहेजने के बारे में अधिक जानने के लिए [documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) देखें।

Save(String, MHTMLSaveOptions) मेथड

दस्तावेज़ सहेजने के लिए आउटपुट फ़ाइल का स्थानीय फ़ाइल‑सिस्टम पथ निर्दिष्ट करना आवश्यक है। MHTMLSaveOptions() कंस्ट्रक्टर [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) क्लास का एक इंस्टेंस प्रारंभ करता है जिसमें ResourceHandlingOptions प्रॉपर्टी होती है, जिसका उपयोग संसाधनों के प्रबंधन की कॉन्फ़िगरेशन के लिए किया जाता है। Save(path, saveOptions) मेथड स्थानीय फ़ाइल‑सिस्टम पथ और एक save options इंस्टेंस को पैरामीटर के रूप में लेता है और HTML को MHTML दस्तावेज़ के रूप में निर्दिष्ट पथ वाली स्थानीय फ़ाइल में सहेजता है।

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtm");
	// विकल्प क्लास इंस्टेंस को परिभाषित करें
	var options = new MHTMLSaveOptions();
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### संबंधित देखें

* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, MHTMLSaveOptions) {#save_9}

दस्तावेज़ को निर्दिष्ट url द्वारा स्थानीय फ़ाइल में सहेजता है। इस दस्तावेज़ में उपयोग किए गए सभी संसाधनों को एक सन्निहित फ़ोल्डर में सहेजा जाएगा, जिसका नाम इस प्रकार बनाया जाएगा: output_file_name + "_files"।

```java
public void Save(Url url, MHTMLSaveOptions saveOptions)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| url | Url | आउटपुट फ़ाइल के लिए स्थानीय URL। |
| saveOptions | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) ऑब्जेक्ट उपयोग आपको रेंडरिंग प्रक्रिया को ट्यून करने में सक्षम बनाता है। अधिक जानकारी के लिए [documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options) देखें। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentException | यदि निर्दिष्ट `url` एक वैध स्थानीय फ़ाइल URL नहीं है तो यह उत्पन्न होता है। |

## टिप्पणियाँ

HTML सहेजें

अधिकांश कार्यों के लिए, जिन्हें आपको करना है, दस्तावेज़ को सहेजना आवश्यक है। एक बार जब आप मौजूदा फ़ाइल लोड कर लेते हैं या शून्य से एक HTML दस्तावेज़ बनाते हैं, तो आप अपने परिवर्तन को HTMLDocument.Save() मेथड्स में से किसी एक का उपयोग करके सहेज सकते हैं। ये मेथड्स पथ, URL या आउटपुट स्टोरेज द्वारा निर्दिष्ट स्थानीय फ़ाइल में HTML सहेजने की अनुमति देते हैं। सहेजने के बारे में अधिक जानने के लिए [documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) देखें।

Save(Url, MHTMLSaveOptions) मेथड

दस्तावेज़ सहेजने के लिए पूर्ण Url पथ निर्दिष्ट करना आवश्यक है। Url(url) कंस्ट्रक्टर निर्दिष्ट url के साथ [`Url`](../../url/) क्लास का एक इंस्टेंस बनाता है। MHTMLSaveOptions() कंस्ट्रक्टर [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) क्लास का एक इंस्टेंस प्रारंभ करता है जिसमें ResourceHandlingOptions प्रॉपर्टी होती है, जिसका उपयोग संसाधनों के प्रबंधन की कॉन्फ़िगरेशन के लिए किया जाता है। Save(url, saveOptions) मेथड url और विकल्पों को पैरामीटर के रूप में लेता है और HTML को MHTML दस्तावेज़ के रूप में निर्दिष्ट url वाली स्थानीय फ़ाइल में सहेजता है।

स्रोत कोड

आप पूर्ण उदाहरण और डेटा फ़ाइलें [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) से डाउनलोड कर सकते हैं।

## उदाहरण

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtm");
	// विकल्प क्लास इंस्टेंस को परिभाषित करें
	var options = new MHTMLSaveOptions();
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input file path.

*outputHtmlPath - user output folder path.

### संबंधित देखें

* class [Url](../../url/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, MHTMLSaveOptions) {#save_4}

दस्तावेज़ की सामग्री और संसाधनों को [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/) का उपयोग करके सहेजता है।

```java
public void Save(ResourceHandler resourceHandler, MHTMLSaveOptions saveOptions)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| resourceHandler | ResourceHandler | संसाधन हैंडलर [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)। |
| saveOptions | MHTMLSaveOptions | MHTML सहेजने विकल्प। |

### संबंधित देखें

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

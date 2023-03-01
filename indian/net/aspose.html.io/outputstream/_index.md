---
title: Class OutputStream
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Aspose.Html.IO.OutputStream कक्ष. एक सरगेट स्ट्रम वस्तवक आउटपुट स्ट्रम क लपेटत है और उस तक पहुंच क नयंत्रत करत है OutputStream इसमें URI डेट हत है ज आउटपुट स्ट्रम के स्थन क वर्णन करत है
type: docs
weight: 3750
url: /hi/net/aspose.html.io/outputstream/
---
## OutputStream class

एक सरोगेट स्ट्रीम वास्तविक आउटपुट स्ट्रीम को लपेटता है और उस तक पहुंच को नियंत्रित करता है। `OutputStream` इसमें URI डेटा होता है जो आउटपुट स्ट्रीम के स्थान का वर्णन करता है।

```csharp
public class OutputStream : Stream
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [OutputStream](outputstream/)(Stream, string) | का एक नया उदाहरण प्रारंभ करता है`OutputStream` वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| override [CanRead](../../aspose.html.io/outputstream/canread/) { get; } | एक मान प्राप्त करता है जो इंगित करता है कि लपेटा गया आउटपुट स्ट्रीम पढ़ने का समर्थन करता है या नहीं। |
| override [CanSeek](../../aspose.html.io/outputstream/canseek/) { get; } | एक मान प्राप्त करता है जो इंगित करता है कि लपेटा गया आउटपुट स्ट्रीम खोज का समर्थन करता है या नहीं। |
| override [CanWrite](../../aspose.html.io/outputstream/canwrite/) { get; } | एक मान प्राप्त करता है जो इंगित करता है कि लपेटा गया आउटपुट स्ट्रीम लेखन का समर्थन करता है या नहीं। |
| override [Length](../../aspose.html.io/outputstream/length/) { get; } | लिपटे आउटपुट स्ट्रीम के बाइट्स में लंबाई प्राप्त करता है। |
| override [Position](../../aspose.html.io/outputstream/position/) { get; set; } | लिपटे आउटपुट स्ट्रीम के भीतर स्थिति प्राप्त या सेट करता है। |
| [Uri](../../aspose.html.io/outputstream/uri/) { get; } | स्ट्रीम स्थान का यूआरआई प्राप्त करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| override [Close](../../aspose.html.io/outputstream/close/)() | लिपटे आउटपुट स्ट्रीम और वर्तमान स्ट्रीम को बंद करता है। |
| override [Flush](../../aspose.html.io/outputstream/flush/)() | लिपटे आउटपुट स्ट्रीम के लिए सभी बफ़र्स को साफ़ करता है और किसी भी बफ़र किए गए डेटा को अंतर्निहित डिवाइस पर लिखा जाता है। |
| override [Read](../../aspose.html.io/outputstream/read/)(byte[], int, int) | लपेटे गए आउटपुट स्ट्रीम से बाइट्स के अनुक्रम को पढ़ता है और स्ट्रीम के भीतर स्थिति को बाइट्स की संख्या से आगे बढ़ाता है। |
| override [Seek](../../aspose.html.io/outputstream/seek/)(long, SeekOrigin) | लिपटे आउटपुट स्ट्रीम के भीतर स्थिति सेट करता है। |
| override [SetLength](../../aspose.html.io/outputstream/setlength/)(long) | लिपटे आउटपुट स्ट्रीम की लंबाई निर्धारित करता है। |
| override [Write](../../aspose.html.io/outputstream/write/)(byte[], int, int) | लपेटे गए आउटपुट स्ट्रीम में बाइट्स का अनुक्रम लिखता है और इस स्ट्रीम के भीतर वर्तमान स्थिति को बाइट्स की संख्या से आगे बढ़ाता है। |

### यह सभी देखें

* नाम स्थान [Aspose.Html.IO](../../aspose.html.io/)
* सभा [Aspose.HTML](../../)



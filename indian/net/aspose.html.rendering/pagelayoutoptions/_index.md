---
title: Enum PageLayoutOptions
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Aspose.Html.Rendering.PageLayoutOptions एनुम. उन फ़्लैग्स क नर्दष्ट करत है ज अन्य पेजसेटअप वकल्पं के सथ मलकर पेजं के आकर और लेआउट क नर्धरण करते हैं इन फ़्लैग्स क उनके ववरण के अनुसर एक सथ जड़ ज सकत है
type: docs
weight: 4380
url: /hi/net/aspose.html.rendering/pagelayoutoptions/
---
## PageLayoutOptions enumeration

उन फ़्लैग्स को निर्दिष्ट करता है जो अन्य पेजसेटअप विकल्पों के साथ मिलकर पेजों के आकार और लेआउट का निर्धारण करते हैं। इन फ़्लैग्स को उनके विवरण के अनुसार एक साथ जोड़ा जा सकता है।

```csharp
[Flags]
public enum PageLayoutOptions
```

### मान

| नाम | कीमत | विवरण |
| --- | --- | --- |
| None | `0` | डिफ़ॉल्ट मान जो इंगित करता है कि PageLayoutOptions पृष्ठों के आकार और लेआउट को प्रभावित नहीं करेगा। |
| FitToContentWidth | `1` | यह ध्वज इंगित करता है कि पृष्ठों की चौड़ाई सामग्री आकार से ही निर्धारित होती है, न कि निर्दिष्ट पृष्ठ चौड़ाई से। प्रत्येक पृष्ठ के लिए सामग्री की चौड़ाई की गणना अलग-अलग की जाती है। |
| UseWidestPage | `2` | के साथ संयुक्त होने परFitToContentWidth इंगित करता है कि प्रत्येक पृष्ठ की चौड़ाई समान होगी और सभी पृष्ठों में सबसे व्यापक सामग्री आकार के बराबर होगी। |
| FitToWidestContentWidth | `3` | यह फ़्लैग इंगित करता है कि पृष्ठ की चौड़ाई सामग्री आकार से ही निर्धारित की जाती है, न कि निर्दिष्ट पृष्ठ चौड़ाई से. प्रत्येक पृष्ठ की चौड़ाई समान होगी और सभी पृष्ठों में सबसे व्यापक सामग्री आकार के बराबर होगी. |
| FitToContentHeight | `10` | यह ध्वज इंगित करता है कि पृष्ठ की ऊंचाई सामग्री आकार से ही निर्धारित होती है, निर्दिष्ट पृष्ठ ऊंचाई से नहीं। यदि यह ध्वज निर्दिष्ट किया गया है तो सभी दस्तावेज़ सामग्री एक पृष्ठ पर स्थित होगी। |
| ScaleToPageWidth | `100` | यह फ़्लैग इंगित करता है कि दस्तावेज़ की सामग्री को उस पृष्ठ पर फिट करने के लिए स्केल किया जाएगा जहां उपलब्ध पृष्ठ चौड़ाई और अतिव्यापी सामग्री के बीच का अंतर सबसे बड़ा है। यह इससे टकराता हैFitToContentWidth फ़्लैग और यदि दोनों फ़्लैग केवल निर्दिष्ट हैंScaleToPageWidth असर पड़ेगा. |
| ScaleToPageHeight | `1000` | यह फ़्लैग इंगित करता है कि दस्तावेज़ की सामग्री को पहले पृष्ठ की ऊंचाई पर फ़िट करने के लिए स्केल किया जाएगा. यह इससे टकराता हैFitToContentHeight फ़्लैग और यदि दोनों फ़्लैग केवल निर्दिष्ट हैंScaleToPageHeight प्रभावी होगा. सभी दस्तावेज़ सामग्री केवल एक पृष्ठ पर रखी जाएगी. |

### यह सभी देखें

* नाम स्थान [Aspose.Html.Rendering](../../aspose.html.rendering/)
* सभा [Aspose.HTML](../../)


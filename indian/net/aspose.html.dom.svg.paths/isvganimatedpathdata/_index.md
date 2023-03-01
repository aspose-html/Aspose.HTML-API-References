---
title: Interface ISVGAnimatedPathData
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Aspose.Html.Dom.Svg.Paths.ISVGAnimatedPathData इंटरफेस. वह SVGAnimatedPathData इंटरफ़ेस उन तत्वं क समर्थन करत है जनके पस ड वशेषत है ज एसवज पथ डेट रखत है और उस वशेषत क एनमेट करने क क्षमत क समर्थन करत है
type: docs
weight: 1680
url: /hi/net/aspose.html.dom.svg.paths/isvganimatedpathdata/
---
## ISVGAnimatedPathData interface

वह SVGAnimatedPathData इंटरफ़ेस उन तत्वों का समर्थन करता है जिनके पास 'डी' विशेषता है जो एसवीजी पथ डेटा रखता है, और उस विशेषता को एनिमेट करने की क्षमता का समर्थन करता है।

```csharp
public interface ISVGAnimatedPathData
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AnimatedPathSegList](../../aspose.html.dom.svg.paths/isvganimatedpathdata/animatedpathseglist/) { get; } | एसवीजी के सिंटैक्स के साथ वन-फॉर-वन से मेल खाने वाले फॉर्म में 'डी' विशेषता की वर्तमान एनिमेटेड सामग्री तक पहुंच प्रदान करता है। यदि दी गई विशेषता या संपत्ति को एनिमेटेड किया जा रहा है, तो विशेषता या संपत्ति का वर्तमान एनिमेटेड मूल्य शामिल है, और वस्तु और उसकी सामग्री दोनों ही केवल पढ़ने के लिए हैं। यदि दी गई विशेषता या गुण वर्तमान में एनिमेट नहीं किया जा रहा है, तो इसमें पथसेगलिस्ट के समान मान शामिल हैं. |
| [PathSegList](../../aspose.html.dom.svg.paths/isvganimatedpathdata/pathseglist/) { get; } | एसवीजी के सिंटैक्स के साथ वन-फॉर-वन से मेल खाने वाले फॉर्म में 'डी' विशेषता के आधार (यानी, स्थिर) सामग्री तक पहुंच प्रदान करता है। इस प्रकार, यदि 'डी' विशेषता में एक "एब्सोल्यूट मूवटो (एम)" और एक "एब्सोल्यूट आर्कटो (ए)" कमांड है, तो पाथसेगलिस्ट में दो प्रविष्टियां होंगी: एक SVG_PATHSEG_MOVETO_ABS और एक SVG_PATHSEG_ARC_ABS. |

### यह सभी देखें

* नाम स्थान [Aspose.Html.Dom.Svg.Paths](../../aspose.html.dom.svg.paths/)
* सभा [Aspose.HTML](../../)



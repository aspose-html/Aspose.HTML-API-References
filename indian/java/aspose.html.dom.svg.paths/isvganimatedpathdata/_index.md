---
title: "ISVGAnimatedPathData इंटरफ़ेस"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.dom.svg.paths.ISVGAnimatedPathData इंटरफ़ेस। यह SVGAnimatedPathData इंटरफ़ेस उन तत्वों का समर्थन करता है जिनमें d एट्रिब्यूट होता है जो SVG पाथ डेटा रखता है और उस एट्रिब्यूट को एनीमेट करने की क्षमता का समर्थन करता है।"
type: docs

url: /hi/java/com.aspose.html.dom.svg.paths/isvganimatedpathdata/
---
## ISVGAnimatedPathData interface

यह SVGAnimatedPathData इंटरफ़ेस उन तत्वों का समर्थन करता है जिनमें ‘d’ एट्रिब्यूट होता है जो SVG पाथ डेटा रखता है, और उस एट्रिब्यूट को एनीमेट करने की क्षमता प्रदान करता है।

```java
public interface ISVGAnimatedPathData
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [getAnimatedPathSegList](../../com.aspose.html.dom.svg.paths/isvganimatedpathdata/animatedpathseglist/) वर्तमान एनीमेटेड ‘d’ एट्रिब्यूट की सामग्री तक पहुँच प्रदान करता है जो SVG की सिंटैक्स के साथ एक‑से‑एक मेल खाती है। यदि दिया गया एट्रिब्यूट या प्रॉपर्टी एनीमेटेड है, तो एट्रिब्यूट या प्रॉपर्टी का वर्तमान एनीमेटेड मान शामिल करता है, और ऑब्जेक्ट तथा उसकी सामग्री केवल‑पढ़ने योग्य हैं। यदि दिया गया एट्रिब्यूट या प्रॉपर्टी वर्तमान में एनीमेटेड नहीं है, तो यह pathSegList के समान मान रखता है। |
| [getPathSegList](../../com.aspose.html.dom.svg.paths/isvganimatedpathdata/pathseglist/) ‘d’ एट्रिब्यूट की बेस (अर्थात स्थिर) सामग्री तक पहुँच प्रदान करता है जो SVG की सिंटैक्स के साथ एक‑से‑एक मेल खाती है। इसलिए, यदि ‘d’ एट्रिब्यूट में एक "absolute moveto (M)" और एक "absolute arcto (A)" कमांड है, तो pathSegList में दो प्रविष्टियाँ होंगी: एक SVG_PATHSEG_MOVETO_ABS और एक SVG_PATHSEG_ARC_ABS। |

### संबंधित देखें

* package [com.aspose.html.dom.svg.paths](../../com.aspose.html.dom.svg.paths/)
* package [Aspose.HTML](../../)

---
title: "com.aspose.html.drawing"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.drawing पैकेज में ऑब्जेक्ट और इंटरफ़ेस होते हैं जो मापन और इकाइयों को निर्दिष्ट करने के साथ-साथ ब्रश, रंग और फ़ॉन्ट जैसे ड्राइंग एट्रिब्यूट ऑब्जेक्ट प्रदान करते हैं।"
type: docs

url: /hi/java/com.aspose.html.drawing/
---
**com.aspose.html.drawing** पैकेज में माप और इकाइयों को निर्दिष्ट करने के साथ-साथ ब्रश, रंग और फ़ॉन्ट जैसे ड्राइंग एट्रिब्यूट ऑब्जेक्ट्स के लिए ऑब्जेक्ट्स और इंटरफ़ेस शामिल हैं।

## क्लासेस

| क्लास | विवरण |
| --- | --- |
| [Angle](./angle/) | कोण डेटा प्रकार |
| [Color](./color/) | Color क्लास आपको रंगों को Red-Green-Blue (RGB) मान, Hue-Saturation-Luminosity (HSL) मान, Hue-Saturation-Value (HSV) मान, Hue-Whiteness-Blackness (HWB) मान, lightness-A-B (LAB) मान, Luminance-Chroma-Hue (LCH) मान, Cyan-Magenta-Yellow-Key (CMYK) मान, Natural colors (NCOL) मान, या रंग नाम से निर्दिष्ट करने देता है। एक Alpha चैनल भी उपलब्ध है जो पारदर्शिता दर्शाता है। |
| [Dimension](./dimension/) | आयामों के लिए बेस क्लास प्रदान करता है। सामान्य शब्द 'dimension' एक संख्या को दर्शाता है जिसके साथ इकाई जुड़ी होती है, और इसे [`UnitType`](../com.aspose.html.drawing/unittype/) द्वारा दर्शाया जाता है। |
| [Frequency](./frequency/) | 'frequency' इकाई। |
| [Length](./length/) | लंबाई मापन इकाई को दर्शाता है। |
| [LengthOrAuto](./lengthorauto/) | भंडारण लंबाई या 'auto' इकाइयों के लिए कंटेनर को दर्शाता है। |
| [Margin](./margin/) | पेज मार्जिन को दर्शाता है। |
| [Numeric](./numeric/) | संख्यात्मक प्रकारों के लिए बेस क्लास प्रदान करता है। |
| [Page](./page/) | पेज ऑब्जेक्ट को दर्शाता है जो कॉन्फ़िगरेशन आउटपुट पेज के लिए उपयोग होता है। पेज आकार के लिए डिफ़ॉल्ट मान A4 (210x297mm) है। |
| [Resolution](./resolution/) | रिज़ॉल्यूशन इकाई को दर्शाता है। |
| [Size](./size/) | ऊँचाई और चौड़ाई निर्दिष्ट करने वाले मानों को संग्रहीत करता है। |
| [Time](./time/) | समय इकाई को दर्शाता है। |
| [Unit](./unit/) | मापन इकाइयों के लिए बेस क्लास प्रदान करता है। |
| [UnitType](./unittype/) | मापन इकाई को निर्दिष्ट करता है। |
## इंटरफ़ेस

| इंटरफ़ेस | विवरण |
| --- | --- |
| [IBrush](./ibrush/) | ब्रश प्रकार प्राप्त करने के लिए मेथड घोषित करता है। |
| [IColorComponents](./icolorcomponents/) | रंग घटकों को प्रोसेस करने के लिए मेथड और प्रॉपर्टीज़ घोषित करता है। |
| [IDrawingFactory](./idrawingfactory/) | ड्राइंग-संबंधित ऑब्जेक्ट बनाने के लिए फ़ैक्ट्री को दर्शाता है। |
| [IGradientBrush](./igradientbrush/) | ग्रेडिएंट ब्रश के सामान्य प्रॉपर्टीज़ प्राप्त करने के लिए मेथड्स घोषित करें। |
| [IInterpolationColor](./iinterpolationcolor/) | इंटरपोलेशन रंग प्राप्त करने के लिए विधियों को घोषित करता है। |
| [ILinearGradientBrush](./ilineargradientbrush/) | एक रैखिक ग्रेडिएंट के साथ ब्रश इंटरफ़ेस को परिभाषित करता है। |
| [IMatrix](./imatrix/) | रूपांतरणों के लिए उपयोग की जाने वाली मैट्रिक्स का प्रतिनिधित्व करता है। |
| [ISolidBrush](./isolidbrush/) | एकल रंग के ब्रश इंटरफ़ेस को परिभाषित करता है। |
| [ITextureBrush](./itexturebrush/) | एक छवि का उपयोग करके आकार के अंदरूनी भाग को भरने वाले ब्रश इंटरफ़ेस को परिभाषित करता है। |
| [ITransformableBrush](./itransformablebrush/) | रूपांतरण मैट्रिक्स और रैप मोड प्राप्त करने के लिए विधियों को घोषित करता है। |
| [ITrueTypeFont](./itruetypefont/) | TrueType फ़ॉन्ट के साथ काम करने के लिए विधियों को घोषित करता है। |
## एन्यूमरेशन

| एन्यूमरेशन | विवरण |
| --- | --- |
| [BrushType](./brushtype/) | ब्रश के प्रकार को निर्दिष्ट करता है। |
| [ColorModel](./colormodel/) | यह एनेमरेशन रंग घटकों के साथ काम करने के लिए रंग मॉडल चुनने हेतु उपयोग किया जाता है। |
| [SpreadMode](./spreadmode/) | जब बनावट या ग्रेडिएंट भरे जाने वाले क्षेत्र से छोटा हो तो वह कैसे टाइल किया जाता है, यह निर्दिष्ट करता है। |
| [WebFontStyle](./webfontstyle/) | पाठ पर लागू स्वरूपण को निर्दिष्ट करता है। |
| [WebImageFormat](./webimageformat/) | समर्थित छवि स्वरूपों को निर्दिष्ट करता है। |
| [WebMatrixOrder](./webmatrixorder/) | मैट्रिक्स रूपांतरणों के लागू होने के क्रम को निर्दिष्ट करता है। |

---
title: "SVGPathSeg क्लास"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.dom.svg.paths.SVGPathSeg class. SVGPathSeg इंटरफ़ेस एक बेस इंटरफ़ेस है जो पाथ डेटा विनिर्देशन के भीतर एकल कमांड के अनुरूप है।"
type: docs

url: /hi/java/com.aspose.html.dom.svg.paths/svgpathseg/
---
## SVGPathSeg class

SVGPathSeg इंटरफ़ेस एक बेस इंटरफ़ेस है जो पाथ डेटा स्पेसिफिकेशन के भीतर एकल कमांड से मेल खाता है।

```java
public abstract class SVGPathSeg : SVGValueType
```

## गुण

| नाम | विवरण |
| --- | --- |
| [getPathSegType](../../com.aspose.html.dom.svg.paths/svgpathseg/pathsegtype/) पाथ सेगमेंट का प्रकार जैसा कि इस इंटरफ़ेस पर परिभाषित स्थिरांक में से एक द्वारा निर्दिष्ट किया गया है। |
| [getPathSegTypeAsLetter](../../com.aspose.html.dom.svg.paths/svgpathseg/pathsegtypeasletter/) पाथ सेगमेंट का प्रकार, संबंधित एक‑अक्षर कमांड नाम द्वारा निर्दिष्ट। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | अप्रबंधित और - वैकल्पिक रूप से - प्रबंधित संसाधनों को रिलीज़ करता है। |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | यह मेथड ECMAScript ऑब्जेक्ट को पुनः प्राप्त करने के लिए उपयोग किया जाता है। |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| const [PATHSEG_ARC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_abs/) | एक "absolute arcto" (A) पाथ डेटा कमांड के अनुरूप है। |
| const [PATHSEG_ARC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_rel/) | एक "relative arcto" (a) पाथ डेटा कमांड के अनुरूप है। |
| const [PATHSEG_CLOSEPATH](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_closepath/) | एक "closepath" (z) पाथ डेटा कमांड के अनुरूप है। |
| const [PATHSEG_CURVETO_CUBIC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_abs/) | एक "absolute cubic Bézier curveto" (C) पाथ डेटा कमांड के अनुरूप है। |
| const [PATHSEG_CURVETO_CUBIC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_rel/) | एक "relative cubic Bézier curveto" (c) पाथ डेटा कमांड के अनुरूप है। |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_abs/) | एक "absolute smooth cubic curveto" (S) पाथ डेटा कमांड के अनुरूप है। |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_rel/) | एक "relative smooth cubic curveto" (s) पाथ डेटा कमांड के अनुरूप है। |
| const [PATHSEG_CURVETO_QUADRATIC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_abs/) | एक "absolute quadratic Bézier curveto" (Q) पाथ डेटा कमांड के अनुरूप है। |
| const [PATHSEG_CURVETO_QUADRATIC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_rel/) | एक "relative quadratic Bézier curveto" (q) पाथ डेटा कमांड के अनुरूप है। |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_abs/) | एक "absolute smooth quadratic curveto" (T) पाथ डेटा कमांड के अनुरूप है। |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_rel/) | एक "relative smooth quadratic curveto" (t) पाथ डेटा कमांड के अनुरूप है। |
| const [PATHSEG_LINETO_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_abs/) | एक "absolute lineto" (L) पाथ डेटा कमांड के अनुरूप है। |
| const [PATHSEG_LINETO_HORIZONTAL_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_abs/) | एक "absolute horizontal lineto" (H) पाथ डेटा कमांड के अनुरूप है। |
| const [PATHSEG_LINETO_HORIZONTAL_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_rel/) | एक "relative horizontal lineto" (h) पाथ डेटा कमांड के अनुरूप है। |
| const [PATHSEG_LINETO_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_rel/) | एक "relative lineto" (l) पाथ डेटा कमांड के अनुरूप है। |
| const [PATHSEG_LINETO_VERTICAL_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_abs/) | एक "absolute vertical lineto" (V) पाथ डेटा कमांड के अनुरूप है। |
| const [PATHSEG_LINETO_VERTICAL_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_rel/) | एक "relative vertical lineto" (v) पाथ डेटा कमांड के अनुरूप है। |
| const [PATHSEG_MOVETO_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_abs/) | एक "absolute moveto" (M) पाथ डेटा कमांड के अनुरूप है। |
| const [PATHSEG_MOVETO_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_rel/) | एक "relative moveto" (m) पाथ डेटा कमांड के अनुरूप है। |
| const [PATHSEG_UNKNOWN](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_unknown/) | इकाई प्रकार पूर्वनिर्धारित प्रकारों में से नहीं है। इस प्रकार का नया मान परिभाषित करने या मौजूदा मान को इस प्रकार में बदलने का प्रयास करना अमान्य है। |

### संबंधित देखें

* class [SVGValueType](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/)
* package [com.aspose.html.dom.svg.paths](../../com.aspose.html.dom.svg.paths/)
* package [Aspose.HTML](../../)

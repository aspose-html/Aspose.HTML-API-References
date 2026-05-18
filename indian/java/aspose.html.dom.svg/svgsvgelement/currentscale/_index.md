---
title: "SVGSVGElement.CurrentScale"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "SVGSVGElement प्रॉपर्टी। सबसे बाहरी svg तत्व पर यह attribute प्रारंभिक दृश्य के सापेक्ष वर्तमान स्केल फैक्टर दर्शाता है, जिससे उपयोगकर्ता की ज़ूमिंग और पैनिंग ऑपरेशन्स को ध्यान में रखा जाता है, जैसा कि Magnification और panning में वर्णित है। DOM attributes currentScale और currentTranslate 2x3 मैट्रिक्स a b c d e f के बराबर होते हैं: currentScale 0 0 currentScale currentTranslate.x currentTranslate.y। यदि magnification सक्षम है, अर्थात zoomAndPan=magnify, तो प्रभाव ऐसा है जैसे SVG दस्तावेज़ फ्रैगमेंट के सबसे बाहरी स्तर पर एक अतिरिक्त रूपांतरण लगाया गया हो, यानी सबसे बाहरी svg तत्व के बाहर। जब इसे किसी ऐसे svg तत्व पर एक्सेस किया जाता है जो सबसे बाहरी नहीं है, तो इस attribute के व्यवहार को निर्धारित नहीं किया जा सकता।"
type: docs

url: /hi/java/com.aspose.html.dom.svg/svgsvgelement/currentscale/
---
## SVGSVGElement.CurrentScale property

सबसे बाहरी svg तत्व पर, यह attribute प्रारंभिक दृश्य के सापेक्ष वर्तमान स्केल फैक्टर दर्शाता है, जिससे उपयोगकर्ता की ज़ूमिंग और पैनिंग ऑपरेशन्स को ध्यान में रखा जाता है, जैसा कि Magnification और panning में बताया गया है। DOM attributes currentScale और currentTranslate 2x3 मैट्रिक्स [a b c d e f] = [currentScale 0 0 currentScale currentTranslate.x currentTranslate.y] के बराबर हैं। यदि \"magnification\" सक्षम है (जैसे, zoomAndPan=\"magnify\"), तो प्रभाव ऐसा है जैसे SVG दस्तावेज़ फ्रैगमेंट के सबसे बाहरी स्तर पर एक अतिरिक्त रूपांतरण लगाया गया हो (अर्थात, सबसे बाहरी svg तत्व के बाहर)। जब इसे किसी ‘svg’ तत्व पर एक्सेस किया जाता है जो सबसे बाहरी नहीं है, तो इस attribute के व्यवहार को निर्धारित नहीं किया जा सकता।

```java
public float CurrentScale { get; set; }
```

### Property Value

वर्तमान स्केल।

### संबंधित देखें

* class [SVGSVGElement](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

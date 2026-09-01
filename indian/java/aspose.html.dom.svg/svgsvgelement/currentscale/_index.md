---
title: "SVGSVGElement.CurrentScale"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "SVGSVGElement प्रॉपर्टी। बाहरी सबसे बाहरी svg तत्व पर यह एट्रिब्यूट प्रारंभिक दृश्य की तुलना में वर्तमान स्केल फ़ैक्टर को दर्शाता है, जिससे उपयोगकर्ता के ज़ूम और पैनिंग ऑपरेशन्स को ध्यान में रखा जाता है, जैसा कि Magnification और panning में वर्णित है। DOM एट्रिब्यूट currentScale और currentTranslate 2x3 मैट्रिक्स a b c d e f के बराबर होते हैं: currentScale 0 0 currentScale currentTranslate.x currentTranslate.y। यदि magnification सक्षम है, अर्थात् zoomAndPan=\"magnify\", तो प्रभाव ऐसा है जैसे SVG दस्तावेज़ फ्रैगमेंट के सबसे बाहरी स्तर पर एक अतिरिक्त ट्रांसफ़ॉर्मेशन जोड़ा गया हो, यानी सबसे बाहरी svg तत्व के बाहर। जब इसे किसी ऐसे svg तत्व पर एक्सेस किया जाता है जो सबसे बाहरी नहीं है, तो इस एट्रिब्यूट के व्यवहार को परिभाषित नहीं किया गया है।"
type: docs

url: /hi/java/com.aspose.html.dom.svg/svgsvgelement/currentscale/
---
## SVGSVGElement.CurrentScale property

सबसे बाहरी svg तत्व पर, यह एट्रिब्यूट प्रारंभिक दृश्य की तुलना में वर्तमान स्केल फ़ैक्टर को दर्शाता है, जिससे उपयोगकर्ता के ज़ूम और पैनिंग ऑपरेशन्स को ध्यान में रखा जाता है, जैसा कि Magnification और panning में बताया गया है। DOM एट्रिब्यूट currentScale और currentTranslate 2x3 मैट्रिक्स [a b c d e f] = [currentScale 0 0 currentScale currentTranslate.x currentTranslate.y] के बराबर हैं। यदि "magnification" सक्षम है (उदाहरण के लिए, zoomAndPan="magnify"), तो प्रभाव ऐसा है जैसे SVG दस्तावेज़ फ्रैगमेंट के सबसे बाहरी स्तर पर एक अतिरिक्त ट्रांसफ़ॉर्मेशन जोड़ा गया हो (अर्थात् सबसे बाहरी svg तत्व के बाहर)। जब इसे किसी ऐसे ‘svg’ तत्व पर एक्सेस किया जाता है जो सबसे बाहरी नहीं है, तो इस एट्रिब्यूट के व्यवहार को परिभाषित नहीं किया गया है।

```java
public float CurrentScale { get; set; }
```

### Property Value

वर्तमान स्केल।

### संबंधित देखें

* class [SVGSVGElement](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

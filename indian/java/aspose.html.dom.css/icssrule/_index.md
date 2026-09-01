---
title: "ICSSRule इंटरफ़ेस"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.dom.css.ICSSRule इंटरफ़ेस। CSSRule इंटरफ़ेस किसी भी प्रकार के CSS कथन के लिए अमूर्त बेस इंटरफ़ेस है। इसमें नियम सेट और एट-रूल दोनों शामिल हैं। एक इम्प्लीमेंटेशन को अपेक्षित है कि वह CSS स्टाइल शीट में निर्दिष्ट सभी नियमों को संरक्षित रखे, भले ही वह नियम पार्सर द्वारा पहचाना न गया हो। अपरिचित नियमों को इस इंटरफ़ेस का उपयोग करके दर्शाया जाता है।"
type: docs

url: /hi/java/com.aspose.html.dom.css/icssrule/
---
## ICSSRule interface

CSSRule इंटरफ़ेस किसी भी प्रकार के CSS कथन के लिए सारभूत बेस इंटरफ़ेस है। इसमें नियम सेट और एट-रूल दोनों शामिल हैं। एक इम्प्लीमेंटेशन से अपेक्षा की जाती है कि वह CSS स्टाइल शीट में निर्दिष्ट सभी नियमों को संरक्षित रखे, भले ही नियम पार्सर द्वारा पहचाना न गया हो। अपरिचित नियमों को इस इंटरफ़ेस का उपयोग करके दर्शाया जाता है।

```java
public interface ICSSRule
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
[getCSSText]
[setCSSText] The cssText property of the `CSSRule` interface returns the actual text of a [`CSSStyleSheet`](../icssstylesheet/) style-rule. |
| [getParentRule](../../com.aspose.html.dom.css/icssrule/parentrule/) यदि यह नियम किसी अन्य नियम के भीतर स्थित है (जैसे @media ब्लॉक के भीतर एक स्टाइल नियम), तो यह वह कंटेनिंग नियम है। यदि यह नियम किसी अन्य नियम के भीतर नेस्टेड नहीं है, तो यह null लौटाता है। |
| [getParentStyleSheet](../../com.aspose.html.dom.css/icssrule/parentstylesheet/) `CSSRule` इंटरफ़ेस की parentStyleSheet प्रॉपर्टी वह [`StyleSheet`](../istylesheet/) ऑब्जेक्ट लौटाती है जिसमें वर्तमान नियम परिभाषित है। |
| [getType](../../com.aspose.html.dom.css/icssrule/type/) नियम का प्रकार, जैसा कि [CSSOM # dom-cssrule-type](https://drafts.csswg.org/cssom/#dom-cssrule-type) में परिभाषित है। अपेक्षा है कि बाइंडिंग-विशिष्ट कास्टिंग मेथड्स का उपयोग करके CSSRule इंटरफ़ेस के एक इंस्टेंस को उस प्रकार द्वारा संकेतित विशिष्ट डेराइव्ड इंटरफ़ेस में कास्ट किया जा सके। |

### संबंधित देखें

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)

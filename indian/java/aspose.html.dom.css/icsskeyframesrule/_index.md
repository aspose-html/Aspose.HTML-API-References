---
title: "ICSSKeyframesRule इंटरफ़ेस"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.dom.css.ICSSKeyframesRule इंटरफ़ेस। CSSKeyframeRule इंटरफ़ेस की name प्रॉपर्टी एनीमेशन का नाम प्राप्त करती और सेट करती है जैसा कि animation-name प्रॉपर्टी में उपयोग किया जाता है।"
type: docs

url: /hi/java/com.aspose.html.dom.css/icsskeyframesrule/
---
## ICSSKeyframesRule interface

CSSKeyframeRule इंटरफ़ेस की name प्रॉपर्टी एनीमेशन-नाम प्रॉपर्टी द्वारा उपयोग किए गए एनीमेशन का नाम प्राप्त करती है और सेट करती है।

```java
public interface ICSSKeyframesRule : ICSSRule
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [getCSSRules](../../com.aspose.html.dom.css/icsskeyframesrule/cssrules/) [`CSSKeyframeRule`](../icsskeyframerule/) इंटरफ़ेस की रीड-ओनली cssRules प्रॉपर्टी एक [`CSSRuleList`](../icssrulelist/) लौटाती है जिसमें keyframes at-rule की नियम शामिल होते हैं। |
| [getName](../../com.aspose.html.dom.css/icsskeyframesrule/name/) [`CSSKeyframeRule`](../icsskeyframerule/) इंटरफ़ेस की name प्रॉपर्टी एनीमेशन का नाम प्राप्त करती और सेट करती है जैसा कि animation-name प्रॉपर्टी में उपयोग किया जाता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [appendRule](../../com.aspose.html.dom.css/icsskeyframesrule/appendrule/)(String) | appendRule मेथड पास किए गए [`CSSKeyframeRule`](../icsskeyframerule/) को keyframes नियम संग्रह के अंत में जोड़ता है। |
| [deleteRule](../../com.aspose.html.dom.css/icsskeyframesrule/deleterule/)(String) | deleteRule मेथड पास किए गए कुंजी के साथ [`CSSKeyframeRule`](../icsskeyframerule/) को हटाता है। यदि इस कुंजी वाला कोई नियम मौजूद नहीं है, तो मेथड कुछ नहीं करता। |
| [findRule](../../com.aspose.html.dom.css/icsskeyframesrule/findrule/)(String) | findRule मेथड पास किए गए कुंजी से मेल खाने वाला नियम लौटाता है। यदि ऐसा कोई नियम नहीं है, तो null मान लौटाया जाता है। |

### संबंधित देखें

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)

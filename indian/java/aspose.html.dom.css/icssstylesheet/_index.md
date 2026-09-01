---
title: "ICSSStyleSheet इंटरफ़ेस"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.dom.css.ICSSStyleSheet इंटरफ़ेस। CSSStyleSheet इंटरफ़ेस एकल CSS स्टाइलशीट का प्रतिनिधित्व करता है और आपको स्टाइलशीट में सम्मिलित नियमों की सूची की जाँच और संशोधन करने देता है। यह अपने पैरेंट IStyleSheet से प्रॉपर्टीज़ और मेथड्स को विरासत में प्राप्त करता है।"
type: docs

url: /hi/java/com.aspose.html.dom.css/icssstylesheet/
---
## ICSSStyleSheet interface

CSSStyleSheet इंटरफ़ेस एकल CSS स्टाइलशीट का प्रतिनिधित्व करता है, और आपको स्टाइलशीट में सम्मिलित नियमों की सूची की जाँच और संशोधन करने देता है। यह अपने पैरेंट, [`IStyleSheet`](../istylesheet/) से प्रॉपर्टीज़ और मेथड्स को विरासत में प्राप्त करता है।

एक स्टाइलशीट में [`ICSSRule`](../icssrule/) ऑब्जेक्ट्स का संग्रह होता है जो स्टाइलशीट में प्रत्येक नियम का प्रतिनिधित्व करते हैं। नियमों को एक [`ICSSRuleList`](../icssrulelist/) में रखा जाता है, जिसे स्टाइलशीट की cssRules प्रॉपर्टी से प्राप्त किया जा सकता है।

उदाहरण के लिए, एक नियम एक [`ICSSStyleRule`](../icssstylerule/) ऑब्जेक्ट हो सकता है जिसमें कोई शैली जैसे कि शामिल हो।

```java
h1, h2 {   font-size: 16pt; }
```

एक अन्य नियम एक एट-रूल हो सकता है जैसे @import या @media, आदि।

```java
public interface ICSSStyleSheet : IStyleSheet
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [getCSSRules](../../com.aspose.html.dom.css/icssstylesheet/cssrules/) पढ़ने-केवल CSSStyleSheet प्रॉपर्टी cssRules एक लाइव [`CSSRuleList`](../icssrulelist/) लौटाती है जो स्टाइलशीट में सम्मिलित प्रत्येक CSS नियम की वास्तविक‑समय, अद्यतन सूची प्रदान करती है। सूची में प्रत्येक आइटम एक [`CSSRule`](../icssrule/) है जो एकल नियम को परिभाषित करता है। |
| [getOwnerRule](../../com.aspose.html.dom.css/icssstylesheet/ownerrule/) पढ़ने-केवल CSSStyleSheet प्रॉपर्टी ownerRule वह [`CSSImportRule`](../icssimportrule/) लौटाती है जो @import एट‑रूल के अनुरूप है जिसने स्टाइलशीट को दस्तावेज़ में आयात किया था। यदि स्टाइलशीट को @import द्वारा दस्तावेज़ में आयात नहीं किया गया, तो लौटाया गया मान null होता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [deleteRule](../../com.aspose.html.dom.css/icssstylesheet/deleterule/)(int) | `CSSStyleSheet` मेथड deleteRule() स्टाइलशीट ऑब्जेक्ट से एक नियम हटाता है। |
| [insertRule](../../com.aspose.html.dom.css/icssstylesheet/insertrule/)(String, int) | CSSStyleSheet.insertRule() मेथड वर्तमान स्टाइलशीट में एक नया CSS नियम सम्मिलित करता है, कुछ प्रतिबंधों के साथ। |

## Remarks

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

संदर्भ

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # cssstylesheet](https://drafts.csswg.org/cssom/#cssstylesheet) – The CSSOM definition.

### संबंधित देखें

* interface [IStyleSheet](../istylesheet/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)

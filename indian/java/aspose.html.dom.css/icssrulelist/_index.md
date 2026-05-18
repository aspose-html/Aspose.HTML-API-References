---
title: "ICSSRuleList इंटरफ़ेस"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.dom.css.ICSSRuleList इंटरफ़ेस। एक CSSRuleList केवल-पढ़ने योग्य CSSRule ऑब्जेक्ट्स का क्रमबद्ध संग्रह दर्शाता है।"
type: docs

url: /hi/java/com.aspose.html.dom.css/icssrulelist/
---
## ICSSRuleList interface

एक CSSRuleList केवल-पढ़ने योग्य [`CSSRule`](../icssrule/) ऑब्जेक्ट्स का क्रमबद्ध संग्रह दर्शाता है।

हालांकि CSSRuleList ऑब्जेक्ट केवल-पढ़ने योग्य है और सीधे संशोधित नहीं किया जा सकता, इसे एक लाइव ऑब्जेक्ट माना जाता है, क्योंकि सामग्री समय के साथ बदल सकती है।

[`CSSRule`](../icssrule/) ऑब्जेक्ट्स द्वारा लौटाए गए अंतर्निहित नियमों को संपादित करने के लिए, CSSStyleSheet.insertRule() और CSSStyleSheet.deleteRule() का उपयोग करें, जो [`CSSStyleSheet`](../icssstylesheet/) की विधियां हैं।

```java
public interface ICSSRuleList : IEnumerable<ICSSRule>
```

## गुण

| नाम | विवरण |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/icssrulelist/item/) मेथड item() (http://www.w3.org/TR/DOM-Level-2-Style/css.html#CSS-CSSRuleList) द्वारा एक CSS नियम पुनः प्राप्त करने के लिए उपयोग किया जाता है। इस संग्रह में क्रम CSS स्टाइल शीट में नियमों के क्रम को दर्शाता है। यदि इंडेक्स सूची में नियमों की संख्या के बराबर या उससे अधिक है, तो यह null लौटाता है। |
| [getLength](../../com.aspose.html.dom.css/icssrulelist/length/) `CSSRuleList` इंटरफ़ेस की length प्रॉपर्टी सूची में मौजूद [`CSSRule`](../icssrule/) ऑब्जेक्ट्स की संख्या लौटाती है। |

### संबंधित देखें

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)

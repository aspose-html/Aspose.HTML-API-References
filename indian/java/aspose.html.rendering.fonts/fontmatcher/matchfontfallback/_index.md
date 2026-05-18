---
title: "FontMatcher.MatchFontFallback"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "FontMatcher मेथड। यह मेथड तब कॉल किया जाता है जब फ़ॉन्ट लुकअप फ़ोल्डरों में उपयुक्त फ़ॉन्ट नहीं मिलता। इसे फ़ॉन्टMatchingProperties के आधार पर सही प्रकार का फ़ॉन्ट लौटाना चाहिए जो charCode को रेंडर कर सके या यदि ऐसा फ़ॉन्ट उपलब्ध नहीं है तो null लौटाए।"
type: docs

url: /hi/java/com.aspose.html.rendering.fonts/fontmatcher/matchfontfallback/
---
## FontMatcher.MatchFontFallback method

यह मेथड तब कॉल किया जाता है जब फ़ॉन्ट लुकअप फ़ोल्डरों में कोई उपयुक्त फ़ॉन्ट नहीं मिलता। इसे *fontMatchingProperties* के आधार पर सही प्रकार का फ़ॉन्ट लौटाना चाहिए जो *charCode* को रेंडर कर सके, या यदि ऐसा फ़ॉन्ट उपलब्ध नहीं है तो `null` लौटाए।

```java
public abstract byte[] MatchFontFallback(FontMatchingProperties fontMatchingProperties, 
    uint charCode)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| fontMatchingProperties | FontMatchingProperties | मैच किए गए फ़ॉन्ट की प्रॉपर्टीज़। |
| charCode | UInt32 | मैच किए गए फ़ॉन्ट का उपयोग करके रेंडर किए जाने वाले अक्षर का कोड। |

### रिटर्न वैल्यू

फ़ॉन्ट डेटा या `null` शामिल करने वाला बाइट एरे।

### संबंधित देखें

* class [FontMatchingProperties](../../fontmatchingproperties/)
* class [FontMatcher](../)
* package [com.aspose.html.rendering.fonts](../../../com.aspose.html.rendering.fonts/)
* package [Aspose.HTML](../../../)

---
title: "ICSSValueList इंटरफ़ेस"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.dom.css.ICSSValueList इंटरफ़ेस। CSSValueList इंटरफ़ेस CSSValue इंटरफ़ेस से व्युत्पन्न है और CSS मानों के क्रमबद्ध संग्रह का सार प्रदान करता है।"
type: docs

url: /hi/java/com.aspose.html.dom.css/icssvaluelist/
---
## ICSSValueList interface

CSSValueList इंटरफ़ेस [`CSSValue`](../cssvalue/) इंटरफ़ेस से व्युत्पन्न है और CSS मानों के क्रमबद्ध संग्रह का सार प्रदान करता है।

कुछ प्रॉपर्टीज़ अपने सिंटैक्स में खाली सूची की अनुमति देती हैं। उस स्थिति में, ये प्रॉपर्टीज़ none पहचानकर्ता लेती हैं। इसलिए, एक खाली सूची का अर्थ है कि प्रॉपर्टी का मान none है।

CSSValueList में आइटम्स को एक पूर्णांक इंडेक्स के माध्यम से एक्सेस किया जा सकता है, जो 0 से शुरू होता है।

```java
public interface ICSSValueList
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/icssvaluelist/item/) यह मेथड एक CSSValue को क्रमिक इंडेक्स द्वारा प्राप्त करने के लिए उपयोग किया जाता है। इस संग्रह में क्रम CSS स्टाइल प्रॉपर्टी के मानों के क्रम को दर्शाता है। यदि इंडेक्स सूची में मानों की संख्या से बड़ा या बराबर है, तो यह null लौटाता है। |
| [getLength](../../com.aspose.html.dom.css/icssvaluelist/length/) CSSValueList इंटरफ़ेस की length रीड-ओनली प्रॉपर्टी सूची में CSSValues की संख्या दर्शाती है। इंडेक्स के वैध मानों की सीमा 0 से length-1 तक, दोनों सहित, है। |

## Remarks

यह इंटरफ़ेस टाइप्ड CSS ऑब्जेक्ट मॉडल बनाने के प्रयास का हिस्सा था। इस प्रयास को छोड़ दिया गया है, और अधिकांश ब्राउज़र इसे लागू नहीं करते हैं।

अपने उद्देश्य को प्राप्त करने के लिए, आप उपयोग कर सकते हैं:

अटाइप्ड [CSS Object Model](https://drafts.csswg.org/cssom/), व्यापक रूप से समर्थित, या आधुनिक [CSS Typed Object Model API](https://drafts.css-houdini.org/css-typed-om/#stylevalue-objects), कम समर्थित और प्रयोगात्मक माना जाता है।

### संबंधित देखें

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)

---
title: "ICSSValueList इंटरफ़ेस"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.dom.css.ICSSValueList इंटरफ़ेस। CSSValueList इंटरफ़ेस CSSValue इंटरफ़ेस से व्युत्पन्न है और CSS मानों के क्रमबद्ध संग्रह का अमूर्त प्रतिनिधित्व प्रदान करता है।"
type: docs

url: /hi/java/com.aspose.html.dom.css/icssvaluelist/
---
## ICSSValueList interface

CSSValueList इंटरफ़ेस [`CSSValue`](../cssvalue/) इंटरफ़ेस से व्युत्पन्न है और CSS मानों के क्रमबद्ध संग्रह का अमूर्त प्रतिनिधित्व प्रदान करता है।

कुछ प्रॉपर्टी अपने सिंटैक्स में खाली सूची की अनुमति देती हैं। ऐसे मामलों में, इन प्रॉपर्टी में none पहचानकर्ता लिया जाता है। इसलिए, खाली सूची का अर्थ है कि प्रॉपर्टी का मान none है।

CSSValueList में आइटम एक पूर्णांक इंडेक्स द्वारा पहुँचा जा सकता है, जो 0 से शुरू होता है।

```java
public interface ICSSValueList
```

## गुण

| नाम | विवरण |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/icssvaluelist/item/) यह मेथड क्रमिक इंडेक्स द्वारा एक CSSValue प्राप्त करने के लिए उपयोग किया जाता है। इस संग्रह में क्रम CSS शैली प्रॉपर्टी के मानों के क्रम को दर्शाता है। यदि इंडेक्स सूची में मानों की संख्या से बड़ा या बराबर है, तो यह null लौटाता है। |
| [getLength](../../com.aspose.html.dom.css/icssvaluelist/length/) CSSValueList इंटरफ़ेस की length पढ़ने‑के‑लिए‑केवल एट्रिब्यूट सूची में CSSValues की संख्या दर्शाती है। इंडेक्स के मान्य मानों की सीमा 0 से length‑1 तक, दोनों सहित है। |

## टिप्पणियाँ

यह इंटरफ़ेस टाइप्ड CSS ऑब्जेक्ट मॉडल बनाने के प्रयास का हिस्सा था। इस प्रयास को छोड़ दिया गया है, और अधिकांश ब्राउज़र इसे लागू नहीं करते।

अपने उद्देश्य को प्राप्त करने के लिए, आप उपयोग कर सकते हैं:

अटाइप्ड [CSS Object Model](https://drafts.csswg.org/cssom/), जो व्यापक रूप से समर्थित है, या आधुनिक [CSS Typed Object Model API](https://drafts.css-houdini.org/css-typed-om/#stylevalue-objects), जो कम समर्थित है और प्रयोगात्मक माना जाता है।

### संबंधित देखें

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)

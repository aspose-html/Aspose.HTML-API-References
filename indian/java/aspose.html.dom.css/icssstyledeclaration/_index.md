---
title: "ICSSStyleDeclaration इंटरफ़ेस"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.dom.css.ICSSStyleDeclaration इंटरफ़ेस। CSSStyleDeclaration इंटरफ़ेस एक ऑब्जेक्ट का प्रतिनिधित्व करता है जो एक CSS घोषणा ब्लॉक है और स्टाइल जानकारी तथा विभिन्न स्टाइल-संबंधी मेथड्स और प्रॉपर्टीज़ को उजागर करता है।"
type: docs

url: /hi/java/com.aspose.html.dom.css/icssstyledeclaration/
---
## ICSSStyleDeclaration interface

CSSStyleDeclaration इंटरफ़ेस एक ऑब्जेक्ट का प्रतिनिधित्व करता है जो एक CSS घोषणा ब्लॉक है, और शैली जानकारी तथा विभिन्न शैली-संबंधित विधियों और गुणों को उजागर करता है।

एक CSSStyleDeclaration ऑब्जेक्ट को तीन विभिन्न API के माध्यम से उजागर किया जा सकता है:

Via HTMLElement.style, जो एकल तत्व की इनलाइन स्टाइल्स को संभालता है। Via the [`CSSStyleSheet`](../icssstylesheet/) API. उदाहरण के लिए, document.styleSheets[0].cssRules[0].style पहला CSS नियम दस्तावेज़ की पहली स्टाइलशीट में एक `CSSStyleDeclaration` ऑब्जेक्ट लौटाता है। Via Window.getComputedStyle(), जो `CSSStyleDeclaration` ऑब्जेक्ट को एक रीड-ओनली इंटरफ़ेस के रूप में उजागर करता है।

```java
public interface ICSSStyleDeclaration : ICSS2Properties, IEnumerable<String>
```

## गुण

| नाम | विवरण |
| --- | --- |
[getCSSText]
[setCSSText] The parsable textual representation of the declaration block (excluding the surrounding curly braces). Setting this attribute will result in the parsing of the new value and resetting of all the properties in the declaration block including the removal or addition of properties. |
| [getItem](../../com.aspose.html.dom.css/icssstyledeclaration/item/) इस घोषणा ब्लॉक में स्पष्ट रूप से सेट की गई प्रॉपर्टीज़ को पुनः प्राप्त करने के लिए उपयोग किया जाता है। इस मेथड का उपयोग करके प्राप्त प्रॉपर्टीज़ का क्रम उन सेट किए जाने के क्रम के समान नहीं होना आवश्यक है। इस मेथड का उपयोग इस घोषणा ब्लॉक में सभी प्रॉपर्टीज़ पर इटरेट करने के लिए किया जा सकता है। |
| [getLength](../../com.aspose.html.dom.css/icssstyledeclaration/length/) रीड-ओनली प्रॉपर्टी इस CSS घोषणा ब्लॉक में स्पष्ट रूप से सेट की गई प्रॉपर्टीज़ की संख्या को एक पूर्णांक के रूप में लौटाती है। वैध इंडेक्स की सीमा 0 से length-1 तक, दोनों सहित, है। |
| [getParentRule](../../com.aspose.html.dom.css/icssstyledeclaration/parentrule/) CSSStyleDeclaration.parentRule रीड-ओनली प्रॉपर्टी एक CSSRule लौटाती है जो इस स्टाइल ब्लॉक का पैरेंट है, उदाहरण के लिए एक [`CSSStyleRule`](../icssstylerule/) जो CSS सिलेक्टर के लिए स्टाइल का प्रतिनिधित्व करता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [getPropertyCSSValue](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/)(String) | यदि इस घोषणा ब्लॉक में कोई CSS प्रॉपर्टी स्पष्ट रूप से सेट की गई है तो उसकी वैल्यू के ऑब्जेक्ट प्रतिनिधित्व को पुनः प्राप्त करने के लिए उपयोग किया जाता है। यदि प्रॉपर्टी शॉर्टहैंड प्रॉपर्टी है तो यह मेथड null लौटाता है। शॉर्टहैंड प्रॉपर्टी वैल्यूज़ को केवल स्ट्रिंग्स के रूप में एक्सेस और संशोधित किया जा सकता है, getPropertyValue और setProperty मेथड्स का उपयोग करके। |
| [getPropertyPriority](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertypriority/)(String) | यदि इस घोषणा ब्लॉक में कोई CSS प्रॉपर्टी स्पष्ट रूप से सेट की गई है तो उसकी प्राथमिकता (जैसे "important" क्वालिफायर) को पुनः प्राप्त करने के लिए उपयोग किया जाता है। |
| [getPropertyValue](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertyvalue/)(String) | CSSStyleDeclaration.getPropertyValue() मेथड इंटरफ़ेस एक स्ट्रिंग लौटाता है जिसमें निर्दिष्ट CSS प्रॉपर्टी का मान होता है। |
| [removeProperty](../../com.aspose.html.dom.css/icssstyledeclaration/removeproperty/)(String) | CSSStyleDeclaration.removeProperty() मेथड इंटरफ़ेस एक CSS स्टाइल घोषणा ऑब्जेक्ट से प्रॉपर्टी को हटाता है। |
| [setProperty](../../com.aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty)(String, String) | CSSStyleDeclaration.setProperty() मेथड इंटरफ़ेस इस घोषणा ब्लॉक में डिफ़ॉल्ट प्राथमिकता के साथ प्रॉपर्टी वैल्यू सेट करने के लिए उपयोग किया जाता है। डिफ़ॉल्ट प्राथमिकता "important" नहीं है, अर्थात् String.Empty |
| [setProperty](../../com.aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty_1)(String, String, String) | CSSStyleDeclaration.setProperty() मेथड इंटरफ़ेस इस घोषणा ब्लॉक में डिफ़ॉल्ट प्राथमिकता के साथ प्रॉपर्टी वैल्यू सेट करने के लिए उपयोग किया जाता है। डिफ़ॉल्ट प्राथमिकता "important" नहीं है, अर्थात् String.Empty |

## टिप्पणियाँ

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

संदर्भ

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # cssstyledeclaration](https://drafts.csswg.org/cssom/#cssstyledeclaration) – The CSSOM definition.

### संबंधित देखें

* interface [ICSS2Properties](../icss2properties/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)

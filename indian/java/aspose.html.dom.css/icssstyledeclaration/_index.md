---
title: "ICSSStyleDeclaration इंटरफ़ेस"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.dom.css.ICSSStyleDeclaration इंटरफ़ेस। CSSStyleDeclaration इंटरफ़ेस एक ऑब्जेक्ट का प्रतिनिधित्व करता है जो एक CSS घोषणा ब्लॉक है और स्टाइल जानकारी तथा विभिन्न स्टाइल-संबंधी मेथड्स और प्रॉपर्टीज़ को उजागर करता है।"
type: docs

url: /hi/java/com.aspose.html.dom.css/icssstyledeclaration/
---
## ICSSStyleDeclaration interface

CSSStyleDeclaration इंटरफ़ेस एक ऑब्जेक्ट का प्रतिनिधित्व करता है जो एक CSS घोषणा ब्लॉक है, और शैली जानकारी तथा विभिन्न शैली‑संबंधी विधियों और गुणों को उजागर करता है।

एक CSSStyleDeclaration ऑब्जेक्ट को तीन विभिन्न API का उपयोग करके उजागर किया जा सकता है:

HTMLElement.style के माध्यम से, जो एकल तत्व की इनलाइन स्टाइल्स को संभालता है।[`CSSStyleSheet`](../icssstylesheet/) API के माध्यम से। उदाहरण के लिए, document.styleSheets[0].cssRules[0].style दस्तावेज़ की पहली स्टाइलशीट में पहले CSS नियम पर एक `CSSStyleDeclaration` ऑब्जेक्ट लौटाता है। Window.getComputedStyle() के माध्यम से, जो `CSSStyleDeclaration` ऑब्जेक्ट को एक केवल-पढ़ने योग्य इंटरफ़ेस के रूप में उजागर करता है।

```java
public interface ICSSStyleDeclaration : ICSS2Properties, IEnumerable<String>
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
[getCSSText]
[setCSSText] The parsable textual representation of the declaration block (excluding the surrounding curly braces). Setting this attribute will result in the parsing of the new value and resetting of all the properties in the declaration block including the removal or addition of properties. |
| [getItem](../../com.aspose.html.dom.css/icssstyledeclaration/item/) इस घोषणा ब्लॉक में स्पष्ट रूप से सेट की गई प्रॉपर्टीज़ को पुनः प्राप्त करने के लिए उपयोग किया जाता है। इस मेथड का उपयोग करके प्राप्त प्रॉपर्टीज़ का क्रम वह क्रम नहीं होना आवश्यक है जिसमें उन्हें सेट किया गया था। इस मेथड का उपयोग इस घोषणा ब्लॉक की सभी प्रॉपर्टीज़ पर इटररेट करने के लिए किया जा सकता है। |
| [getLength](../../com.aspose.html.dom.css/icssstyledeclaration/length/) यह केवल-पढ़ने योग्य प्रॉपर्टी इस CSS घोषणा ब्लॉक में स्पष्ट रूप से सेट की गई प्रॉपर्टीज़ की पूर्णांक संख्या लौटाती है। मान्य सूचकांकों की सीमा 0 से length-1 तक, दोनों सहित, है। |
| [getParentRule](../../com.aspose.html.dom.css/icssstyledeclaration/parentrule/) CSSStyleDeclaration.parentRule केवल-पढ़ने योग्य प्रॉपर्टी एक CSSRule लौटाती है जो इस स्टाइल ब्लॉक का पैरेंट है, उदाहरण के लिए एक [`CSSStyleRule`](../icssstylerule/) जो एक CSS सेलेक्टर के लिए स्टाइल का प्रतिनिधित्व करता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [getPropertyCSSValue](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/)(String) | इस घोषणा ब्लॉक के भीतर यदि कोई CSS प्रॉपर्टी स्पष्ट रूप से सेट की गई हो, तो उसकी मान की ऑब्जेक्ट प्रतिनिधित्व को पुनः प्राप्त करने के लिए उपयोग किया जाता है। यदि प्रॉपर्टी शॉर्टहैंड प्रॉपर्टी है तो यह मेथड null लौटाता है। शॉर्टहैंड प्रॉपर्टी मानों को केवल स्ट्रिंग्स के रूप में ही एक्सेस और संशोधित किया जा सकता है, getPropertyValue और setProperty मेथड्स का उपयोग करके। |
| [getPropertyPriority](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertypriority/)(String) | यदि इस घोषणा ब्लॉक में प्रॉपर्टी स्पष्ट रूप से सेट की गई हो, तो CSS प्रॉपर्टी की प्राथमिकता (जैसे "important" क्वालिफायर) को पुनः प्राप्त करने के लिए उपयोग किया जाता है। |
| [getPropertyValue](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertyvalue/)(String) | CSSStyleDeclaration.getPropertyValue() मेथड इंटरफ़ेस एक स्ट्रिंग लौटाता है जिसमें निर्दिष्ट CSS प्रॉपर्टी का मान होता है। |
| [removeProperty](../../com.aspose.html.dom.css/icssstyledeclaration/removeproperty/)(String) | CSSStyleDeclaration.removeProperty() मेथड इंटरफ़ेस एक CSS स्टाइल घोषणा ऑब्जेक्ट से प्रॉपर्टी को हटाता है। |
| [setProperty](../../com.aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty)(String, String) | CSSStyleDeclaration.setProperty() मेथड इंटरफ़ेस इस घोषणा ब्लॉक के भीतर डिफ़ॉल्ट प्राथमिकता के साथ प्रॉपर्टी मान सेट करने के लिए उपयोग किया जाता है। डिफ़ॉल्ट प्राथमिकता "important" नहीं है, अर्थात् String.Empty |
| [setProperty](../../com.aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty_1)(String, String, String) | CSSStyleDeclaration.setProperty() मेथड इंटरफ़ेस इस घोषणा ब्लॉक के भीतर डिफ़ॉल्ट प्राथमिकता के साथ प्रॉपर्टी मान सेट करने के लिए उपयोग किया जाता है। डिफ़ॉल्ट प्राथमिकता "important" नहीं है, अर्थात् String.Empty |

## Remarks

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

संदर्भ

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # cssstyledeclaration](https://drafts.csswg.org/cssom/#cssstyledeclaration) – The CSSOM definition.

### संबंधित देखें

* interface [ICSS2Properties](../icss2properties/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)

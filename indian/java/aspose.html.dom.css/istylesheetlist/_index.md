---
title: "IStyleSheetList इंटरफ़ेस"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.dom.css.IStyleSheetList इंटरफ़ेस। StyleSheetList इंटरफ़ेस CSSStyleSheet ऑब्जेक्ट्स की एक सूची का प्रतिनिधित्व करता है। इस ऑब्जेक्ट का एक इंस्टेंस Document.styleSheets द्वारा लौटाया जा सकता है।"
type: docs

url: /hi/java/com.aspose.html.dom.css/istylesheetlist/
---
## IStyleSheetList interface

StyleSheetList इंटरफ़ेस [`CSSStyleSheet`](../icssstylesheet/) ऑब्जेक्ट्स की एक सूची का प्रतिनिधित्व करता है। इस ऑब्जेक्ट का एक इंस्टेंस [`Document.styleSheets`](../../com.aspose.html.dom/document/stylesheets/) द्वारा लौटाया जा सकता है।

ऑब्जेक्ट के समर्थित प्रॉपर्टी इंडेक्स 0 से लेकर संग्रह द्वारा प्रतिनिधित्व किए गए CSS स्टाइल शीट्स की संख्या से एक कम तक की रेंज में संख्याएँ हैं। यदि ऐसी कोई CSS स्टाइल शीट नहीं है, तो कोई समर्थित प्रॉपर्टी इंडेक्स नहीं होते।

```java
public interface IStyleSheetList : IEnumerable<ICSSStyleSheet>
```

## गुण

| नाम | विवरण |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/istylesheetlist/item/) item(index) मेथड को संग्रह में indexवें [`CSS style sheet`](../icssstylesheet/) को लौटाना चाहिए। यदि संग्रह में वह indexवाँ ऑब्जेक्ट नहीं है, तो मेथड null लौटाएगा। |
| [getLength](../../com.aspose.html.dom.css/istylesheetlist/length/) length एट्रिब्यूट को संग्रह द्वारा प्रतिनिधित्व किए गए CSS स्टाइल शीट्स की संख्या लौटानी चाहिए। वैध चाइल्ड स्टाइलशीट इंडेक्स की रेंज 0 से length-1 तक (समावेशी) है। |

## टिप्पणियाँ

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

संदर्भ

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # stylesheetlist](https://drafts.csswg.org/cssom/#stylesheetlist) – The CSSOM definition.

### संबंधित देखें

* interface [ICSSStyleSheet](../icssstylesheet/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)

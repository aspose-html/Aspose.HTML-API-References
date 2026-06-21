---
title: "IStyleSheet इंटरफ़ेस"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.dom.css.IStyleSheet इंटरफ़ेस। StyleSheet इंटरफ़ेस किसी भी प्रकार की स्टाइल शीट के लिए एब्स्ट्रैक्ट बेस इंटरफ़ेस है। यह एक संरचित दस्तावेज़ से जुड़ी एकल स्टाइल शीट का प्रतिनिधित्व करता है। HTML में StyleSheet इंटरफ़ेस या तो HTML LINK एलिमेंट के माध्यम से शामिल बाहरी स्टाइल शीट या इनलाइन STYLE एलिमेंट का प्रतिनिधित्व करता है। XML में यह इंटरफ़ेस स्टाइल शीट प्रोसेसिंग इंस्ट्रक्शन के माध्यम से शामिल बाहरी स्टाइल शीट का प्रतिनिधित्व करता है। CSS स्टाइल शीट्स आगे अधिक विशेषीकृत CSSStyleSheet इंटरफ़ेस को लागू करेंगे।"
type: docs

url: /hi/java/com.aspose.html.dom.css/istylesheet/
---
## IStyleSheet interface

StyleSheet इंटरफ़ेस किसी भी प्रकार की स्टाइल शीट के लिए एब्स्ट्रैक्ट बेस इंटरफ़ेस है। यह एक संरचित दस्तावेज़ से जुड़ी एकल स्टाइल शीट का प्रतिनिधित्व करता है। HTML में, StyleSheet इंटरफ़ेस या तो HTML LINK एलिमेंट के माध्यम से शामिल बाहरी स्टाइल शीट या इनलाइन STYLE एलिमेंट का प्रतिनिधित्व करता है। XML में, यह इंटरफ़ेस स्टाइल शीट प्रोसेसिंग इंस्ट्रक्शन के माध्यम से शामिल बाहरी स्टाइल शीट का प्रतिनिधित्व करता है। CSS स्टाइल शीट्स आगे अधिक विशेषीकृत [`CSSStyleSheet`](../icssstylesheet/) इंटरफ़ेस को लागू करेंगे।

साथ ही देखें [CSS Object Model (CSSOM) # StyleSheet Interface Specification](https://drafts.csswg.org/cssom/#the-stylesheet-interface)।

```java
public interface IStyleSheet
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
[getDisabled]
[setDisabled] The disabled property of the `StyleSheet` interface determines whether the style sheet is prevented from applying to the document. |
| [getHref](../../com.aspose.html.dom.css/istylesheet/href/) `StyleSheet` इंटरफ़ेस की href प्रॉपर्टी स्टाइल शीट का स्थान लौटाती है। |
| [getMedia](../../com.aspose.html.dom.css/istylesheet/media/) `StyleSheet` इंटरफ़ेस की media प्रॉपर्टी स्टाइल जानकारी के इच्छित लक्ष्य मीडिया को निर्दिष्ट करती है। यह एक रीड-ओनली, एरे-समतुल्य [`MediaList`](../imedialist/) ऑब्जेक्ट है और इसे deleteMedium() से हटाया जा सकता है और appendMedium() से जोड़ा जा सकता है। |
| [getOwnerNode](../../com.aspose.html.dom.css/istylesheet/ownernode/) वह नोड जो इस स्टाइल शीट को दस्तावेज़ से जोड़ता है। HTML के लिए, यह संबंधित LINK या STYLE एलिमेंट हो सकता है। XML के लिए, यह लिंकिंग प्रोसेसिंग इंस्ट्रक्शन हो सकता है। उन स्टाइल शीट्स के लिए जो अन्य स्टाइल शीट्स द्वारा शामिल की गई हैं, इस एट्रिब्यूट का मान null है। |
| [getParentStyleSheet](../../com.aspose.html.dom.css/istylesheet/parentstylesheet/) उन स्टाइल शीट भाषाओं के लिए जो स्टाइल शीट इन्क्लूजन की अवधारणा का समर्थन करती हैं, यह एट्रिब्यूट शामिल करने वाली स्टाइल शीट को दर्शाता है, यदि मौजूद हो। यदि स्टाइल शीट शीर्ष-स्तर की स्टाइल शीट है, या भाषा इन्क्लूजन का समर्थन नहीं करती, तो इस एट्रिब्यूट का मान null है। |
| [getTitle](../../com.aspose.html.dom.css/istylesheet/title/) `StyleSheet` इंटरफ़ेस की title प्रॉपर्टी वर्तमान स्टाइल शीट का सलाहकार शीर्षक लौटाती है। |
| [getType](../../com.aspose.html.dom.css/istylesheet/type/) यह इस स्टाइल शीट के लिए स्टाइल शीट भाषा निर्दिष्ट करता है। स्टाइल शीट भाषा को एक कंटेंट टाइप (जैसे "text/css") के रूप में निर्दिष्ट किया जाता है। |

## Remarks

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

संदर्भ

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[The StyleSheet Interface](https://drafts.csswg.org/cssom/#the-stylesheet-interface) – The official CSSOM definition.

### संबंधित देखें

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)

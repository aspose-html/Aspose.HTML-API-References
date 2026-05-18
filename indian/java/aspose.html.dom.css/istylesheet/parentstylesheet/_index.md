---
title: "IStyleSheet.ParentStyleSheet"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "IStyleSheet property. उन style sheet भाषाओं के लिए जो style sheet inclusion की अवधारणा का समर्थन करती हैं, यह attribute शामिल करने वाले style sheet को दर्शाता है यदि वह मौजूद है। यदि style sheet शीर्ष-स्तर का style sheet है या style sheet भाषा inclusion का समर्थन नहीं करती है तो इस attribute का मान null होता है।"
type: docs

url: /hi/java/com.aspose.html.dom.css/istylesheet/parentstylesheet/
---
## IStyleSheet.ParentStyleSheet property

उन style sheet भाषाओं के लिए जो style sheet inclusion की अवधारणा का समर्थन करती हैं, यह attribute शामिल करने वाले style sheet को दर्शाता है, यदि वह मौजूद है। यदि style sheet शीर्ष-स्तर का style sheet है, या style sheet भाषा inclusion का समर्थन नहीं करती है, तो इस attribute का मान null है।

```java
public IStyleSheet ParentStyleSheet { get; }
```

### Property Value

parentStyleSheet एट्रिब्यूट को पैरेंट [`CSS style sheet`](../../icssstylesheet/) लौटाना चाहिए।

## टिप्पणियाँ

यह property null लौटाती है यदि वर्तमान stylesheet शीर्ष-स्तर का stylesheet है या stylesheet inclusion समर्थित नहीं है।

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

संदर्भ

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-parentstylesheet](https://drafts.csswg.org/cssom/#dom-stylesheet-parentstylesheet) – The CSSOM definition.

### संबंधित देखें

* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

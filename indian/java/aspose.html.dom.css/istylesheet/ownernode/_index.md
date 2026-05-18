---
title: "IStyleSheet.OwnerNode"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "IStyleSheet प्रॉपर्टी। वह नोड जो इस स्टाइल शीट को दस्तावेज़ से जोड़ता है। HTML के लिए यह संबंधित LINK या STYLE तत्व हो सकता है। XML के लिए यह लिंकिंग प्रोसेसिंग इंस्ट्रक्शन हो सकता है। अन्य स्टाइल शीट्स द्वारा शामिल किए गए स्टाइल शीट्स के लिए इस एट्रिब्यूट का मान null होता है।"
type: docs

url: /hi/java/com.aspose.html.dom.css/istylesheet/ownernode/
---
## IStyleSheet.OwnerNode property

यह नोड इस स्टाइल शीट को दस्तावेज़ से जोड़ता है। HTML के लिए यह संबंधित LINK या STYLE तत्व हो सकता है। XML के लिए यह लिंकिंग प्रोसेसिंग इंस्ट्रक्शन हो सकता है। अन्य स्टाइल शीट्स द्वारा शामिल किए गए स्टाइल शीट्स के लिए इस एट्रिब्यूट का मान null होता है।

```java
public Node OwnerNode { get; }
```

### Property Value

ownerNode एट्रिब्यूट को मालिक नोड लौटाना चाहिए।

## टिप्पणियाँ

अन्य स्टाइल शीट्स द्वारा शामिल किए गए स्टाइल शीट्स के लिए, जैसे @import के साथ, इस प्रॉपर्टी का मान null होता है।

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

संदर्भ

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-ownernode](https://drafts.csswg.org/cssom/#dom-stylesheet-ownernode) – The CSSOM definition.

### संबंधित देखें

* class [Node](../../../com.aspose.html.dom/node/)
* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

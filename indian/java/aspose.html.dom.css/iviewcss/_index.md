---
title: "IViewCSS इंटरफ़ेस"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.dom.css.IViewCSS इंटरफ़ेस। IViewCSS इंटरफ़ेस Window ऑब्जेक्ट का एक विस्तार दर्शाता है जो किसी तत्व की सभी CSS प्रॉपर्टीज़ के मानों तक पहुँच प्रदान करता है।"
type: docs

url: /hi/java/com.aspose.html.dom.css/iviewcss/
---
## IViewCSS interface

IViewCSS इंटरफ़ेस Window ऑब्जेक्ट का एक विस्तार दर्शाता है जो किसी तत्व की सभी CSS गुणों के मानों तक पहुंच प्रदान करता है।

किसी दिए गए तत्व के लिए CSS स्टाइल को IViewCSS.GetComputedStyle() मेथड का उपयोग करके प्राप्त किया जा सकता है।

```java
public interface IViewCSS : IAbstractView
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [getComputedStyle](../../com.aspose.html.dom.css/iviewcss/getcomputedstyle/#getcomputedstyle)(Element) | IViewCSS.getComputedStyle() मेथड एक ऑब्जेक्ट लौटाता है जिसमें किसी तत्व की सभी CSS प्रॉपर्टीज़ के मान होते हैं, सक्रिय स्टाइलशीट्स लागू करने और उन मानों में मौजूद किसी भी बुनियादी गणना को हल करने के बाद। |
| [getComputedStyle](../../com.aspose.html.dom.css/iviewcss/getcomputedstyle/#getcomputedstyle_1)(Element, String) | IViewCSS.getComputedStyle() मेथड एक ऑब्जेक्ट लौटाता है जिसमें किसी तत्व की सभी CSS प्रॉपर्टीज़ के मान होते हैं, सक्रिय स्टाइलशीट्स लागू करने और उन मानों में मौजूद किसी भी बुनियादी गणना को हल करने के बाद। |

## टिप्पणियाँ

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

संदर्भ

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

### संबंधित देखें

* interface [IAbstractView](../../com.aspose.html.dom.views/iabstractview/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)

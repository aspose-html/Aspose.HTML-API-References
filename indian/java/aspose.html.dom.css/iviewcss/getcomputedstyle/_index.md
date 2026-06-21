---
title: "IViewCSS.GetComputedStyle"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "IViewCSS मेथड। IViewCSS.getComputedStyle मेथड एक ऑब्जेक्ट लौटाता है जिसमें किसी तत्व की सभी CSS प्रॉपर्टियों के मान होते हैं, सक्रिय स्टाइलशीट्स लागू करने और उन मानों की किसी भी बुनियादी गणना को हल करने के बाद।"
type: docs

url: /hi/java/com.aspose.html.dom.css/iviewcss/getcomputedstyle/
---
## GetComputedStyle(Element) {#getcomputedstyle}

IViewCSS.getComputedStyle() मेथड एक ऑब्जेक्ट लौटाता है जिसमें किसी तत्व की सभी CSS प्रॉपर्टीज़ के मान होते हैं, सक्रिय स्टाइलशीट्स लागू करने और उन मानों में मौजूद किसी भी बुनियादी गणना को हल करने के बाद।

व्यक्तिगत CSS प्रॉपर्टी मानों तक ऑब्जेक्ट द्वारा प्रदान किए गए API के माध्यम से, या CSS प्रॉपर्टी नामों के साथ इंडेक्सिंग करके पहुंचा जा सकता है।

```java
public ICSSStyleDeclaration GetComputedStyle(Element element)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| element | Element | वह [`Element`](../../../com.aspose.html.dom/element/) जिसके लिए गणना किया गया शैली प्राप्त करनी है। यह पैरामीटर null नहीं हो सकता। |

### रिटर्न वैल्यू

वापसी में मिली शैली एक लाइव [`CSSStyleDeclaration`](../../icssstyledeclaration/) ऑब्जेक्ट है, जो तत्व की शैलियों के बदलने पर स्वतः अपडेट हो जाता है।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| टाइप त्रुटि | यदि पास किया गया ऑब्जेक्ट एक Element नहीं है या pseudoElt एक वैध pseudo-element चयनकर्ता नहीं है। |

## Remarks

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

संदर्भ

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-window-getcomputedstyle](https://drafts.csswg.org/cssom/#dom-window-getcomputedstyle) – The CSSOM definition.

### संबंधित देखें

* interface [ICSSStyleDeclaration](../../icssstyledeclaration/)
* class [Element](../../../com.aspose.html.dom/element/)
* interface [IViewCSS](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

---

## GetComputedStyle(Element, String) {#getcomputedstyle_1}

IViewCSS.getComputedStyle() मेथड एक ऑब्जेक्ट लौटाता है जिसमें किसी तत्व की सभी CSS प्रॉपर्टीज़ के मान होते हैं, सक्रिय स्टाइलशीट्स लागू करने और उन मानों में मौजूद किसी भी बुनियादी गणना को हल करने के बाद।

व्यक्तिगत CSS प्रॉपर्टी मानों तक ऑब्जेक्ट द्वारा प्रदान किए गए API के माध्यम से, या CSS प्रॉपर्टी नामों के साथ इंडेक्सिंग करके पहुंचा जा सकता है।

```java
public ICSSStyleDeclaration GetComputedStyle(Element element, String pseudoElement)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| element | Element | वह [`Element`](../../../com.aspose.html.dom/element/) जिसके लिए गणना किया गया शैली प्राप्त करनी है। यह पैरामीटर null नहीं हो सकता। |
| pseudoElement | String | एक स्ट्रिंग जो मिलाने के लिए pseudo-element निर्दिष्ट करती है। वास्तविक तत्वों के लिए इसे छोड़ दिया जाता है (या null)। |

### रिटर्न वैल्यू

वापसी में मिली शैली एक लाइव [`CSSStyleDeclaration`](../../icssstyledeclaration/) ऑब्जेक्ट है, जो तत्व की शैलियों के बदलने पर स्वतः अपडेट हो जाता है।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| टाइप त्रुटि | यदि पास किया गया ऑब्जेक्ट एक Element नहीं है या pseudoElt एक वैध pseudo-element चयनकर्ता नहीं है। |

## Remarks

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

संदर्भ

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-window-getcomputedstyle](https://drafts.csswg.org/cssom/#dom-window-getcomputedstyle) – The CSSOM definition.

### संबंधित देखें

* interface [ICSSStyleDeclaration](../../icssstyledeclaration/)
* class [Element](../../../com.aspose.html.dom/element/)
* interface [IViewCSS](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

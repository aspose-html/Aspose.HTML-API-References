---
title: "ICSSValueList.Item"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "ICSSValueList प्रॉपर्टी। यह मेथड क्रमिक इंडेक्स द्वारा एक CSSValue प्राप्त करने के लिए उपयोग किया जाता है। इस संग्रह में क्रम CSS स्टाइल प्रॉपर्टी में मानों के क्रम को दर्शाता है। यदि इंडेक्स सूची में मानों की संख्या से बड़ा या बराबर है तो यह null लौटाता है।"
type: docs

url: /hi/java/com.aspose.html.dom.css/icssvaluelist/item/
---
## ICSSValueList indexer

यह विधि क्रमांकित अनुक्रम के द्वारा CSSValue पुनः प्राप्त करने के लिए उपयोग की जाती है। इस संग्रह में क्रम मान CSS शैली गुण में मानों के क्रम को दर्शाता है। यदि अनुक्रमांक सूची में मानों की संख्या के बराबर या उससे अधिक है, तो यह null लौटाता है।

इसके अलावा देखें [CSSOM](https://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113/css.html#CSS-CSSValueList)[#CSSValueList](https://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113/css.html#CSS-CSSValueList).

```java
public CSSValue this[int index] { get; }
```

### रिटर्न वैल्यू

इंडेक्स स्थिति में स्थित [`CSSValue`](../../cssvalue/) या यदि वह मान्य इंडेक्स नहीं है तो null।

### Property Value

संग्रह में इंडेक्स।

## Remarks

यह फीचर मूल रूप से [DOM Style Level 2](https://www.w3.org/TR/DOM-Level-2-Style) विनिर्देशन में परिभाषित किया गया था, लेकिन तब से इसे किसी भी मानकीकरण प्रयास से हटा दिया गया है।

इसे अब एक आधुनिक, लेकिन असंगत, [CSS Typed Object Model API](https://developer.mozilla.org/en-US/docs/Web/API/CSS_Typed_OM_API) द्वारा प्रतिस्थापित किया गया है, जो वर्तमान में मानक ट्रैक पर है।

### संबंधित देखें

* class [CSSValue](../../cssvalue/)
* interface [ICSSValueList](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

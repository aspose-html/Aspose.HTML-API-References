---
title: "HTMLTableSectionElement.InsertRow"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "HTMLTableSectionElement मेथड। इस सेक्शन में एक रो इन्सर्ट करें। नई रो इस सेक्शन में वर्तमान indexth रो के तुरंत पहले इन्सर्ट की जाती है। यदि index -1 है या इस सेक्शन में रो की संख्या के बराबर है तो नई रो को जोड़ दिया जाता है"
type: docs

url: /hi/java/com.aspose.html/htmltablesectionelement/insertrow/
---
## HTMLTableSectionElement.InsertRow method

इस सेक्शन में एक पंक्ति डालें। नई पंक्ति इस सेक्शन में वर्तमान `index`वीं पंक्ति के ठीक पहले डाली जाती है। यदि `index` -1 है या इस सेक्शन में पंक्तियों की संख्या के बराबर है, तो नई पंक्ति को अंत में जोड़ा जाता है।

```java
public HTMLElement InsertRow(int index)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | Int32 | नयी रो को इन्सर्ट करने के लिए रो नंबर। यह इंडेक्स 0 से शुरू होता है और केवल इस सेक्शन के भीतर मौजूद रो के सापेक्ष है, पूरी टेबल के सभी रो नहीं। |

### रिटर्न वैल्यू

नई बनाई गई पंक्ति।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: यदि निर्दिष्ट इंडेक्स रो की संख्या से बड़ा हो या यदि इंडेक्स -1 के अलावा कोई नकारात्मक संख्या हो तो उत्पन्न होता है। @version DOM Level 2 |

### संबंधित देखें

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableSectionElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

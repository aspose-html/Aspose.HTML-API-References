---
title: "HTMLTableRowElement.InsertCell"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "HTMLTableRowElement मेथड। इस पंक्ति में एक खाली TD सेल डालें। यदि इंडेक्स -1 है या सेलों की संख्या के बराबर है तो नया सेल जोड़ दिया जाता है"
type: docs

url: /hi/java/com.aspose.html/htmltablerowelement/insertcell/
---
## HTMLTableRowElement.InsertCell method

इस पंक्ति में एक खाली `TD` सेल डालें। यदि `index` -1 है या सेलों की संख्या के बराबर है, तो नया सेल अंत में जोड़ा जाता है।

```java
public HTMLElement InsertCell(int index)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | Int32 | सेल डालने की जगह, 0 से शुरू। |

### रिटर्न वैल्यू

नया बनाया गया सेल।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: यदि निर्दिष्ट `index` सेलों की संख्या से बड़ा है या यदि इंडेक्स -1 के अलावा कोई नकारात्मक संख्या है तो उत्पन्न होता है। @version DOM Level 2 |

### संबंधित देखें

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableRowElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

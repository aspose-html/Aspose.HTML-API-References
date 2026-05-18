---
title: "HTMLTableSectionElement.InsertRow"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "HTMLTableSectionElement मेथड। इस सेक्शन में एक पंक्ति डालें। नई पंक्ति इस सेक्शन में वर्तमान indexवीं पंक्ति के ठीक पहले डाली जाती है। यदि index -1 है या इस सेक्शन में पंक्तियों की संख्या के बराबर है तो नई पंक्ति जोड़ दी जाती है"
type: docs

url: /hi/java/com.aspose.html/htmltablesectionelement/insertrow/
---
## HTMLTableSectionElement.InsertRow method

इस सेक्शन में एक पंक्ति डालें। नई पंक्ति इस सेक्शन में वर्तमान `index`वीं पंक्ति से ठीक पहले डाली जाती है। यदि `index` -1 है या इस सेक्शन में पंक्तियों की संख्या के बराबर है, तो नई पंक्ति अंत में जोड़ी जाती है।

```java
public HTMLElement InsertRow(int index)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| index | Int32 | नयी पंक्ति डालने के लिए पंक्ति संख्या। यह index 0 से शुरू होता है और केवल इस सेक्शन के भीतर मौजूद पंक्तियों के सापेक्ष है, तालिका की सभी पंक्तियों के नहीं। |

### रिटर्न वैल्यू

नया निर्मित पंक्ति।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: यदि निर्दिष्ट index पंक्तियों की संख्या से बड़ा है या index -1 के अलावा कोई नकारात्मक संख्या है तो उत्पन्न होता है। @version DOM Level 2 |

### संबंधित देखें

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableSectionElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

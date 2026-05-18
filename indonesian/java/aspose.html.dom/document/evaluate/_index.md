---
title: "Document.Evaluate"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode Document. Mengevaluasi String ekspresi XPath dan mengembalikan hasil dengan tipe yang ditentukan jika memungkinkan."
type: docs

url: /id/java/com.aspose.html.dom/document/evaluate/
---
## Document.Evaluate method

Mengevaluasi String ekspresi XPath dan mengembalikan hasil dengan tipe yang ditentukan jika memungkinkan.

```java
public IXPathResult Evaluate(String expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ekspresi | String | String ekspresi XPath yang akan diparsing dan dievaluasi. |
| contextNode | Node | Konteks adalah node konteks untuk evaluasi ekspresi XPath ini. |
| resolver | IXPathNSResolver | Resolver memungkinkan penerjemahan semua prefiks, termasuk prefiks paket xml, dalam ekspresi XPath ke URI paket yang sesuai. |
| tipe | XPathResultType | Jika tipe tertentu ditentukan, maka hasil akan dikembalikan sebagai tipe yang bersesuaian. |
| result | Objek | Hasil menentukan objek hasil spesifik yang dapat digunakan kembali dan dikembalikan oleh metode ini. |

### Nilai Kembali

Hasil evaluasi ekspresi XPath.

### Lihat Juga

* interface [IXPathResult](../../../com.aspose.html.dom.xpath/ixpathresult/)
* class [Node](../../node/)
* interface [IXPathNSResolver](../../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* enum [XPathResultType](../../../com.aspose.html.dom.xpath/xpathresulttype/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

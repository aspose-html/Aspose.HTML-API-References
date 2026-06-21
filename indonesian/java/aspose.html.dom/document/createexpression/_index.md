---
title: "Document.CreateExpression"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode Document. Membuat ekspresi XPath yang diparsing dengan paket yang terresolusi. Ini berguna ketika sebuah ekspresi akan digunakan kembali dalam aplikasi karena memungkinkan kompilasi String ekspresi menjadi bentuk internal yang lebih efisien dan mempreresolusi semua prefiks paket yang muncul dalam ekspresi."
type: docs

url: /id/java/com.aspose.html.dom/document/createexpression/
---
## Document.CreateExpression method

Membuat ekspresi XPath yang telah diparse dengan paket yang terresolusi. Ini berguna ketika ekspresi akan digunakan kembali dalam aplikasi karena memungkinkan mengkompilasi String ekspresi menjadi bentuk internal yang lebih efisien dan mempraresolusi semua prefiks paket yang muncul dalam ekspresi.

```java
public IXPathExpression CreateExpression(String expression, IXPathNSResolver resolver)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ekspresi | String | String ekspresi XPath yang akan diurai. |
| resolver | IXPathNSResolver | `resolver` memungkinkan penerjemahan semua prefiks, termasuk prefiks paket `xml`, dalam ekspresi XPath menjadi URI paket yang sesuai. Jika ini ditetapkan sebagai `null`, setiap prefiks paket dalam ekspresi akan menyebabkan [`DOMException`](../../domexception/) dilempar dengan kode `NAMESPACE_ERR`. |

### Nilai Kembali

Bentuk terkompilasi dari ekspresi XPath.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [dOMException](../../domexception/) | INVALID_EXPRESSION_ERR: Dikeluarkan jika ekspresi tidak sah menurut aturan [`IXPathEvaluator`](../../../com.aspose.html.dom.xpath/ixpathevaluator/). |
| [dOMException](../../domexception/) | NAMESPACE_ERR: Dikeluarkan jika ekspresi berisi prefiks paket yang tidak dapat diselesaikan oleh [`IXPathNSResolver`](../../../com.aspose.html.dom.xpath/ixpathnsresolver/) yang ditentukan. |

### Lihat Juga

* interface [IXPathExpression](../../../com.aspose.html.dom.xpath/ixpathexpression/)
* interface [IXPathNSResolver](../../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

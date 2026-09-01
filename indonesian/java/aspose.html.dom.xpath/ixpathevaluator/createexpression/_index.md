---
title: "IXPathEvaluator.CreateExpression"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode IXPathEvaluator. Membuat ekspresi XPath yang telah diurai dengan paket-paket yang telah diselesaikan. Ini berguna ketika sebuah ekspresi akan digunakan kembali dalam sebuah aplikasi karena memungkinkan untuk mengkompilasi String ekspresi menjadi bentuk internal yang lebih efisien dan melakukan preresolusi semua prefiks paket yang muncul dalam ekspresi."
type: docs

url: /id/java/com.aspose.html.dom.xpath/ixpathevaluator/createexpression/
---
## IXPathEvaluator.CreateExpression method

Membuat ekspresi XPath yang telah diparse dengan paket yang terresolusi. Ini berguna ketika ekspresi akan digunakan kembali dalam aplikasi karena memungkinkan mengkompilasi String ekspresi menjadi bentuk internal yang lebih efisien dan mempraresolusi semua prefiks paket yang muncul dalam ekspresi.

```java
public IXPathExpression CreateExpression(String expression, IXPathNSResolver resolver)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ekspresi | String | String ekspresi XPath yang akan diurai. |
| resolver | IXPathNSResolver | `resolver` memungkinkan penerjemahan semua prefiks, termasuk prefiks paket `xml`, dalam ekspresi XPath menjadi URI paket yang sesuai. Jika ini ditentukan sebagai `null`, setiap prefiks paket dalam ekspresi akan menyebabkan [`DOMException`](../../../com.aspose.html.dom/domexception/) dilemparkan dengan kode `NAMESPACE_ERR`. |

### Nilai Kembali

Bentuk terkompilasi dari ekspresi XPath.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: Dikeluarkan jika ekspresi tidak sah menurut aturan [`IXPathEvaluator`](../). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NAMESPACE_ERR: Dikeluarkan jika ekspresi berisi prefiks paket yang tidak dapat diselesaikan oleh [`IXPathNSResolver`](../../ixpathnsresolver/) yang ditentukan. |

### Lihat Juga

* interface [IXPathExpression](../../ixpathexpression/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* interface [IXPathEvaluator](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)

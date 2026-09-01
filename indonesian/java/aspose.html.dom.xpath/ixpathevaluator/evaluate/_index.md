---
title: "IXPathEvaluator.Evaluate"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode IXPathEvaluator. Mengevaluasi String ekspresi XPath dan mengembalikan hasil dengan tipe yang ditentukan jika memungkinkan."
type: docs

url: /id/java/com.aspose.html.dom.xpath/ixpathevaluator/evaluate/
---
## IXPathEvaluator.Evaluate method

Mengevaluasi String ekspresi XPath dan mengembalikan hasil dengan tipe yang ditentukan jika memungkinkan.

```java
public IXPathResult Evaluate(String expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ekspresi | String | String ekspresi XPath yang akan diurai dan dievaluasi. |
| contextNode | Node | `context` adalah node konteks untuk evaluasi ekspresi XPath ini. Jika [`IXPathEvaluator`](../) diperoleh dengan melakukan casting pada [`Document`](../../../com.aspose.html.dom/document/), maka ini harus dimiliki oleh dokumen yang sama dan harus berupa [`Document`](../../../com.aspose.html.dom/document/), [`Element`](../../../com.aspose.html.dom/element/), [`Attr`](../../../com.aspose.html.dom/attr/), [`Text`](../../../com.aspose.html.dom/text/), [`CDATASection`](../../../com.aspose.html.dom/cdatasection/), [`Comment`](../../../com.aspose.html.dom/comment/), [`ProcessingInstruction`](../../../com.aspose.html.dom/processinginstruction/), atau node XPathNamespace. Jika node konteks adalah [`Text`](../../../com.aspose.html.dom/text/) atau [`CDATASection`](../../../com.aspose.html.dom/cdatasection/), maka konteks diinterpretasikan sebagai seluruh node teks logis yang dilihat oleh XPath, kecuali node tersebut kosong sehingga tidak dapat berfungsi sebagai konteks XPath. |
| resolver | IXPathNSResolver | `resolver` memungkinkan penerjemahan semua prefiks, termasuk prefiks paket `xml`, dalam ekspresi XPath menjadi URI paket yang sesuai. Jika ini ditentukan sebagai `null`, setiap prefiks paket dalam ekspresi akan menyebabkan [`DOMException`](../../../com.aspose.html.dom/domexception/) dilemparkan dengan kode `NAMESPACE_ERR`. |
| type | XPathResultType | Jika `type` tertentu ditentukan, maka hasil akan dikembalikan sebagai tipe yang bersesuaian. Untuk hasil XPath 1.0, ini harus berupa salah satu nilai dari enum [`XPathResultType`](../../xpathresulttype/). |
| result | Object | `result` menentukan objek hasil spesifik yang dapat digunakan kembali dan dikembalikan oleh metode ini. Jika ini ditentukan sebagai `null` atau implementasi tidak menggunakan kembali hasil yang ditentukan, sebuah objek hasil baru akan dibuat dan dikembalikan. Untuk hasil XPath 1.0, objek ini akan berjenis [`IXPathResult`](../../ixpathresult/). |

### Nilai Kembali

Hasil evaluasi ekspresi XPath. Untuk hasil XPath 1.0, objek ini akan berjenis [`IXPathResult`](../../ixpathresult/).

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: Dikeluarkan jika ekspresi tidak sah menurut aturan [`IXPathEvaluator`](../). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: Dikeluarkan jika hasil tidak dapat dikonversi untuk mengembalikan tipe yang ditentukan. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NAMESPACE_ERR: Dikeluarkan jika ekspresi berisi prefiks paket yang tidak dapat diselesaikan oleh [`IXPathNSResolver`](../../ixpathnsresolver/) yang ditentukan. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: Node berasal dari dokumen yang tidak didukung oleh [`IXPathEvaluator`](../). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Node bukan tipe yang diizinkan sebagai node konteks XPath atau tipe permintaan tidak diizinkan oleh [`IXPathEvaluator`](../). |

### Lihat Juga

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathEvaluator](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)

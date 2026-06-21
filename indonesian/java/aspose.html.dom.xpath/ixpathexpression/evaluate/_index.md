---
title: "IXPathExpression.Evaluate"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "IXPathExpression method. Mengevaluasi ekspresi XPath ini dan mengembalikan hasil."
type: docs

url: /id/java/com.aspose.html.dom.xpath/ixpathexpression/evaluate/
---
## IXPathExpression.Evaluate method

Mengevaluasi ekspresi XPath ini dan mengembalikan hasil.

```java
public IXPathResult Evaluate(Node contextNode, XPathResultType type, object result)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| contextNode | Node | `context` adalah node konteks untuk evaluasi ekspresi XPath ini. Jika [`IXPathEvaluator`](../../ixpathevaluator/) diperoleh dengan melakukan casting pada [`Document`](../../../com.aspose.html.dom/document/), maka ini harus dimiliki oleh dokumen yang sama dan harus berupa [`Document`](../../../com.aspose.html.dom/document/), [`Element`](../../../com.aspose.html.dom/element/), [`Attr`](../../../com.aspose.html.dom/attr/), [`Text`](../../../com.aspose.html.dom/text/), [`CDATASection`](../../../com.aspose.html.dom/cdatasection/), [`Comment`](../../../com.aspose.html.dom/comment/), [`ProcessingInstruction`](../../../com.aspose.html.dom/processinginstruction/), atau node XPathNamespace. Jika node konteks adalah [`Text`](../../../com.aspose.html.dom/text/) atau [`CDATASection`](../../../com.aspose.html.dom/cdatasection/), maka konteks diinterpretasikan sebagai seluruh node teks logis yang dilihat oleh XPath, kecuali node tersebut kosong sehingga tidak dapat berfungsi sebagai konteks XPath. |
| type | XPathResultType | Jika `type` tertentu ditentukan, maka hasil akan dipaksa untuk mengembalikan tipe yang ditentukan dengan mengandalkan konversi XPath dan akan gagal jika konversi yang diinginkan tidak memungkinkan. Ini harus salah satu nilai dari [`XPathResultType`](../../xpathresulttype/). |
| result | Object | `result` menentukan objek hasil spesifik yang dapat digunakan kembali dan dikembalikan oleh metode ini. Jika ini ditentukan sebagai `null` atau implementasi tidak menggunakan kembali hasil yang ditentukan, sebuah objek hasil baru akan dibuat dan dikembalikan. Untuk hasil XPath 1.0, objek ini akan berjenis [`IXPathResult`](../../ixpathresult/). |

### Nilai Kembali

Hasil evaluasi ekspresi XPath. Untuk hasil XPath 1.0, objek ini akan berjenis [`IXPathResult`](../../ixpathresult/).

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: Dikeluarkan jika hasil tidak dapat dikonversi untuk mengembalikan tipe yang ditentukan. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: Node berasal dari dokumen yang tidak didukung oleh [`IXPathEvaluator`](../../ixpathevaluator/) yang membuat [`IXPathExpression`](../). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Node bukan tipe yang diizinkan sebagai node konteks XPath atau tipe permintaan tidak diizinkan oleh [`IXPathExpression`](../). |

### Lihat Juga

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../com.aspose.html.dom/node/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathExpression](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)

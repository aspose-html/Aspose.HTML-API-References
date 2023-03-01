---
title: IXPathEvaluator.CreateExpression
second_title: Aspose.HTML untuk Referensi .NET API
description: IXPathEvaluator metode. Membuat ekspresi XPath yang diurai dengan ruang nama yang diselesaikan. Ini berguna saat ekspresi akan digunakan kembali dalam aplikasi karena memungkinkan untuk mengompilasi string ekspresi ke dalam bentuk internal yang lebih efisien dan melakukan preresolve semua prefiks namespace yang terjadi di dalam ekspresi.
type: docs
weight: 10
url: /id/net/aspose.html.dom.xpath/ixpathevaluator/createexpression/
---
## IXPathEvaluator.CreateExpression method

Membuat ekspresi XPath yang diurai dengan ruang nama yang diselesaikan. Ini berguna saat ekspresi akan digunakan kembali dalam aplikasi karena memungkinkan untuk mengompilasi string ekspresi ke dalam bentuk internal yang lebih efisien dan melakukan preresolve semua prefiks namespace yang terjadi di dalam ekspresi.

```csharp
public IXPathExpression CreateExpression(string expression, IXPathNSResolver resolver)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| expression | String | String ekspresi XPath yang akan diuraikan. |
| resolver | IXPathNSResolver | Itu`penyelesai` mengizinkan terjemahan semua awalan, termasuk`xml` awalan namespace, dalam ekspresi XPath menjadi URI namespace yang sesuai. Jika ini ditentukan sebagai`batal` , setiap namespace awalan dalam ekspresi akan menghasilkan[`DOMException`](../../../aspose.html.dom/domexception/) sedang dilemparkan dengan kode`NAMESPACE_ERR`. |

### Nilai Pengembalian

Bentuk terkompilasi dari ekspresi XPath.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: Dimunculkan jika ekspresi tidak sah menurut aturan[`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | NAMESPACE_ERR: Dibesarkan jika ekspresi berisi prefiks namespace yang tidak dapat diselesaikan oleh yang ditentukan[`IXPathNSResolver`](../../ixpathnsresolver/). |

### Lihat juga

* interface [IXPathExpression](../../ixpathexpression/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* interface [IXPathEvaluator](../)
* ruang nama [Aspose.Html.Dom.XPath](../../ixpathevaluator/)
* perakitan [Aspose.HTML](../../../)



---
title: Document.Evaluate
second_title: Aspose.HTML untuk Referensi .NET API
description: Document metode. Mengevaluasi string ekspresi XPath dan mengembalikan hasil dari tipe yang ditentukan jika memungkinkan.
type: docs
weight: 950
url: /id/net/aspose.html.dom/document/evaluate/
---
## Document.Evaluate method

Mengevaluasi string ekspresi XPath dan mengembalikan hasil dari tipe yang ditentukan jika memungkinkan.

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| expression | String | String ekspresi XPath yang akan diuraikan dan dievaluasi. |
| contextNode | Node | Konteksnya adalah simpul konteks untuk evaluasi ekspresi XPath ini. |
| resolver | IXPathNSResolver | Resolver mengizinkan terjemahan semua awalan, termasuk awalan xml namespace, dalam ekspresi XPath ke dalam URI namespace yang sesuai. |
| type | XPathResultType | Jika jenis tertentu ditentukan, hasilnya akan dikembalikan sebagai jenis yang sesuai. |
| result | Object | Hasilnya menentukan objek hasil tertentu yang dapat digunakan kembali dan dikembalikan oleh metode ini. |

### Nilai Pengembalian

Hasil evaluasi ekspresi XPath.

### Lihat juga

* interface [IXPathResult](../../../aspose.html.dom.xpath/ixpathresult/)
* class [Node](../../node/)
* interface [IXPathNSResolver](../../../aspose.html.dom.xpath/ixpathnsresolver/)
* enum [XPathResultType](../../../aspose.html.dom.xpath/xpathresulttype/)
* class [Document](../)
* ruang nama [Aspose.Html.Dom](../../document/)
* perakitan [Aspose.HTML](../../../)



---
title: Interface IXPathEvaluator
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Dom.XPath.IXPathEvaluator antarmuka. Evaluasi ekspresi XPath disediakan olehIXPathEvaluator .
type: docs
weight: 2560
url: /id/net/aspose.html.dom.xpath/ixpathevaluator/
---
## IXPathEvaluator interface

Evaluasi ekspresi XPath disediakan oleh`IXPathEvaluator` .

```csharp
public interface IXPathEvaluator
```

## Metode

| Nama | Keterangan |
| --- | --- |
| [CreateExpression](../../aspose.html.dom.xpath/ixpathevaluator/createexpression/)(string, IXPathNSResolver) | Membuat ekspresi XPath yang diurai dengan ruang nama yang diselesaikan. Ini berguna saat ekspresi akan digunakan kembali dalam aplikasi karena memungkinkan untuk mengompilasi string ekspresi ke dalam bentuk internal yang lebih efisien dan melakukan preresolve semua prefiks namespace yang terjadi di dalam ekspresi. |
| [CreateNSResolver](../../aspose.html.dom.xpath/ixpathevaluator/creatensresolver/)(Node) | Menyesuaikan node DOM apa pun untuk menyelesaikan ruang nama sehingga ekspresi XPath dapat dengan mudah dievaluasi relatif terhadap konteks node tempat ekspresi tersebut muncul di dalam dokumen. Adaptor ini berfungsi seperti metode DOM Level 3`lookupNamespaceURI` pada node dalam menyelesaikan namespaceURI dari awalan yang diberikan menggunakan informasi terkini yang tersedia dalam hierarki node pada saat lookupNamespaceURI dipanggil, juga menyelesaikan dengan benar awalan xml implisit. |
| [Evaluate](../../aspose.html.dom.xpath/ixpathevaluator/evaluate/)(string, Node, IXPathNSResolver, XPathResultType, object) | Mengevaluasi string ekspresi XPath dan mengembalikan hasil dari tipe yang ditentukan jika memungkinkan. |

### Lihat juga

* ruang nama [Aspose.Html.Dom.XPath](../../aspose.html.dom.xpath/)
* perakitan [Aspose.HTML](../../)



---
title: Document.CreateNSResolver
second_title: Aspose.HTML untuk Referensi .NET API
description: Document metode. Menyesuaikan node DOM apa pun untuk menyelesaikan ruang nama sehingga ekspresi XPath dapat dengan mudah dievaluasi relatif terhadap konteks node tempat ekspresi tersebut muncul di dalam dokumen. Adaptor ini berfungsi seperti metode DOM Level 3lookupNamespaceURI pada node dalam menyelesaikan namespaceURI dari awalan yang diberikan menggunakan informasi terkini yang tersedia dalam hierarki node pada saat lookupNamespaceURI dipanggil juga menyelesaikan dengan benar awalan xml implisit.
type: docs
weight: 910
url: /id/net/aspose.html.dom/document/creatensresolver/
---
## Document.CreateNSResolver method

Menyesuaikan node DOM apa pun untuk menyelesaikan ruang nama sehingga ekspresi XPath dapat dengan mudah dievaluasi relatif terhadap konteks node tempat ekspresi tersebut muncul di dalam dokumen. Adaptor ini berfungsi seperti metode DOM Level 3`lookupNamespaceURI` pada node dalam menyelesaikan namespaceURI dari awalan yang diberikan menggunakan informasi terkini yang tersedia dalam hierarki node pada saat lookupNamespaceURI dipanggil, juga menyelesaikan dengan benar awalan xml implisit.

```csharp
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| nodeResolver | Node | Node yang akan digunakan sebagai konteks untuk resolusi namespace. |

### Nilai Pengembalian

[`IXPathNSResolver`](../../../aspose.html.dom.xpath/ixpathnsresolver/) yang menyelesaikan ruang nama sehubungan dengan definisi dalam lingkup untuk node tertentu.

### Lihat juga

* interface [IXPathNSResolver](../../../aspose.html.dom.xpath/ixpathnsresolver/)
* class [Node](../../node/)
* class [Document](../)
* ruang nama [Aspose.Html.Dom](../../document/)
* perakitan [Aspose.HTML](../../../)



---
title: "IXPathEvaluator.CreateNSResolver"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode IXPathEvaluator. Menyesuaikan setiap node DOM untuk menyelesaikan paket sehingga ekspresi XPath dapat dievaluasi dengan mudah relatif terhadap konteks node tempat ia muncul dalam dokumen. Adapter ini berfungsi seperti metode DOM Level 3 lookupNamespaceURI pada node dalam menyelesaikan packageURI dari prefiks tertentu menggunakan informasi terkini yang tersedia dalam hierarki node pada saat lookupNamespaceURI dipanggil, serta secara tepat menyelesaikan prefiks xml implisit."
type: docs

url: /id/java/com.aspose.html.dom.xpath/ixpathevaluator/creatensresolver/
---
## IXPathEvaluator.CreateNSResolver method

Menyesuaikan setiap node DOM untuk menyelesaikan paket sehingga ekspresi XPath dapat dievaluasi dengan mudah relatif terhadap konteks node tempat ia muncul dalam dokumen. Adapter ini berfungsi seperti metode DOM Level 3 `lookupNamespaceURI` pada node dalam menyelesaikan packageURI dari prefiks yang diberikan menggunakan informasi terkini yang tersedia dalam hierarki node pada saat `lookupNamespaceURI` dipanggil, juga menyelesaikan prefiks xml implisit dengan benar.

```java
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nodeResolver | Node | Node yang akan digunakan sebagai konteks untuk resolusi paket. |

### Nilai Kembali

[`IXPathNSResolver`](../../ixpathnsresolver/) which resolves packages with respect to the definitions in scope for a specified node.

### Lihat Juga

* interface [IXPathNSResolver](../../ixpathnsresolver/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathEvaluator](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)

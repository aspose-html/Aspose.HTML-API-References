---
title: "Antarmuka IXPathEvaluator"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "antarmuka com.aspose.html.dom.xpath.IXPathEvaluator. Evaluasi ekspresi XPath disediakan oleh IXPathEvaluator"
type: docs

url: /id/java/com.aspose.html.dom.xpath/ixpathevaluator/
---
## IXPathEvaluator interface

Evaluasi ekspresi XPath disediakan oleh `IXPathEvaluator`.

```java
public interface IXPathEvaluator
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [createExpression](../../com.aspose.html.dom.xpath/ixpathevaluator/createexpression/)(String, IXPathNSResolver) | Membuat ekspresi XPath yang telah diparsir dengan paket yang diselesaikan. Ini berguna ketika sebuah ekspresi akan digunakan kembali dalam aplikasi karena memungkinkan kompilasi String ekspresi ke dalam bentuk internal yang lebih efisien dan menyelesaikan terlebih dahulu semua prefiks paket yang muncul dalam ekspresi. |
| [createNSResolver](../../com.aspose.html.dom.xpath/ixpathevaluator/creatensresolver/)(Node) | Menyesuaikan setiap node DOM untuk menyelesaikan paket sehingga ekspresi XPath dapat dievaluasi dengan mudah relatif terhadap konteks node tempat ia muncul dalam dokumen. Adapter ini berfungsi seperti metode DOM Level 3 `lookupNamespaceURI` pada node dalam menyelesaikan packageURI dari prefiks yang diberikan menggunakan informasi terkini yang tersedia dalam hierarki node pada saat `lookupNamespaceURI` dipanggil, juga menyelesaikan prefiks xml implisit dengan benar. |
| [evaluate](../../com.aspose.html.dom.xpath/ixpathevaluator/evaluate/)(String, Node, IXPathNSResolver, XPathResultType, object) | Mengevaluasi String ekspresi XPath dan mengembalikan hasil dengan tipe yang ditentukan jika memungkinkan. |

### Lihat Juga

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)

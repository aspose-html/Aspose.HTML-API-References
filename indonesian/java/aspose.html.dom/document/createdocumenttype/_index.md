---
title: "Document.CreateDocumentType"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode Document. Metode ini mengembalikan objek DocumentType yang dapat digunakan dengan DOMImplementation.createDocument saat pembuatan dokumen atau dapat dimasukkan ke dalam dokumen melalui metode seperti Node.insertBefore atau Node.replaceChild"
type: docs

url: /id/java/com.aspose.html.dom/document/createdocumenttype/
---
## Document.CreateDocumentType method

Metode ini mengembalikan objek [`DocumentType`](../../documenttype/) yang dapat digunakan dengan DOMImplementation.createDocument saat pembuatan dokumen atau dapat dimasukkan ke dalam dokumen melalui metode seperti Node.insertBefore() atau Node.replaceChild().

```java
public DocumentType CreateDocumentType(String name, String publicId, String systemId, 
    String internalSubset)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | String | Adalah DOMString yang berisi nama yang memenuhi syarat, seperti svg:svg. |
| publicId | String | Adalah DOMString yang berisi pengenal PUBLIC. |
| systemId | String | Adalah DOMString yang berisi pengenal SYSTEM. |
| internalSubset | String | Subset internal. |

### Nilai Kembali

The [`DocumentType`](../../documenttype/).

## Contoh

```java
var dt = document.CreateDocumentType("svg:svg", "-//W3C//DTD SVG 1.1//EN", "http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd", "");
```

### Lihat Juga

* class [DocumentType](../../documenttype/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

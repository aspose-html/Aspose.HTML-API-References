---
title: "Document.CreateElement"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode Document. Dalam dokumen HTML, metode document.createElement membuat elemen HTML yang ditentukan oleh tagName atau HTMLUnknownElement jika tagName tidak dikenali."
type: docs

url: /id/java/com.aspose.html.dom/document/createelement/
---
## Document.CreateElement method

Dalam dokumen HTML, metode document.createElement() membuat elemen HTML yang ditentukan oleh tagName, atau sebuah [`HTMLUnknownElement`](../../../com.aspose.html/htmlunknownelement/) jika tagName tidak dikenali.

```java
public Element CreateElement(String localName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| localName | String | Sebuah String yang menentukan jenis elemen yang akan dibuat. nodeName dari elemen yang dibuat diinisialisasi dengan nilai tagName. Jangan gunakan nama yang memenuhi syarat (seperti "html:a") dengan metode ini. Ketika dipanggil pada dokumen HTML, createElement() mengubah tagName menjadi huruf kecil sebelum membuat elemen. |

### Nilai Kembali

Elemen baru [`Element`](../../element/).

## Contoh

```java
var element = document.CreateElement(tagName);
```

### Lihat Juga

* class [Element](../../element/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

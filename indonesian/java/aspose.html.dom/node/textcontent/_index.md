---
title: "Node.TextContent"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Properti Node. Properti textContent dari antarmuka Node mewakili konten teks dari node dan turunannya"
type: docs

url: /id/java/com.aspose.html.dom/node/textcontent/
---
## Node.TextContent property

Properti textContent dari antarmuka [`Node`](../) mewakili konten teks dari node dan turunannya.

```java
public String TextContent { get; set; }
```

### Property Value

Sebuah String, atau null. Nilainya tergantung pada situasinya:

Jika node adalah dokumen atau doctype, textContent mengembalikan null. Catatan: Untuk mendapatkan semua teks dan data CDATA untuk seluruh dokumen, gunakan document.documentElement.textContent. Jika node adalah bagian CDATA, komentar, instruksi pemrosesan, atau node teks, textContent mengembalikan, atau mengatur, teks di dalam node, yaitu [`Node.nodeValue`](../nodevalue/). Untuk tipe node lainnya, textContent mengembalikan penggabungan textContent dari setiap node anak, kecuali komentar dan instruksi pemrosesan.

## Catatan

Referensi:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-textcontent](https://dom.spec.whatwg.org/#dom-node-textcontent).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Lihat Juga

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

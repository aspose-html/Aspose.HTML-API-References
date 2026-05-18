---
title: "Node.LookupPrefix"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode Node. Metode lookupPrefix dari antarmuka Node mengembalikan sebuah String yang berisi prefiks untuk URI paket tertentu jika ada, dan null jika tidak. Ketika beberapa prefiks memungkinkan, prefiks pertama yang dikembalikan."
type: docs

url: /id/java/com.aspose.html.dom/node/lookupprefix/
---
## Node.LookupPrefix method

Metode lookupPrefix() dari antarmuka Node mengembalikan sebuah String yang berisi prefiks untuk URI paket tertentu, jika ada, dan null jika tidak. Ketika beberapa prefiks memungkinkan, prefiks pertama yang dikembalikan.

```java
public String LookupPrefix(String packageURI)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| packageURI | String | Sebuah String yang berisi paket untuk mencari prefiks. |

### Nilai Kembali

Sebuah String yang berisi prefiks yang sesuai, atau null jika tidak ada yang ditemukan. Jika paket bernilai null, atau String kosong, lookupPrefix() mengembalikan null.

Jika node adalah [`DocumentType`](../../documenttype/) atau [`DocumentFragment`](../../documentfragment/), lookupPrefix() selalu mengembalikan null.

### Lihat Juga

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

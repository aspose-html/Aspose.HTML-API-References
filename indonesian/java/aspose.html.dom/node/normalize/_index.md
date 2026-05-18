---
title: "Node.Normalize"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode Node. Menempatkan semua node Text pada kedalaman penuh sub‑tree di bawah Node ini termasuk node atribut ke dalam bentuk normal di mana hanya struktur seperti elemen, komentar, instruksi pemrosesan, bagian CDATA, dan referensi entitas yang memisahkan node Text, yaitu tidak ada node Text yang bersebelahan maupun node Text kosong. Ini dapat digunakan untuk memastikan tampilan DOM dari sebuah dokumen sama seperti jika dokumen tersebut disimpan dan dimuat kembali, dan berguna ketika operasi seperti pencarian XPointer yang bergantung pada struktur pohon dokumen tertentu akan digunakan. Jika parameter normalize-characters dari objek DOMConfiguration yang terhubung ke Node.ownerDocument bernilai true, metode ini juga akan sepenuhnya menormalkan karakter dari node Text."
type: docs

url: /id/java/com.aspose.html.dom/node/normalize/
---
## Node.Normalize method

Menempatkan semua node [`Text`](../../text/) pada kedalaman penuh sub‑tree di bawah Node ini, termasuk node atribut, ke dalam bentuk "normal" di mana hanya struktur (misalnya [`elements`](../../element/), [`comments`](../../comment/), [`processing instructions`](../../processinginstruction/), [`CDATA sections`](../../cdatasection/), dan [`entity references`](../../entityreference/)) yang memisahkan node [`Text`](../../text/), yaitu tidak ada node Text yang bersebelahan maupun node Text kosong. Ini dapat digunakan untuk memastikan tampilan DOM dari sebuah dokumen sama seperti jika dokumen tersebut disimpan dan dimuat kembali, dan berguna ketika operasi (seperti pencarian XPointer [XPointer]) yang bergantung pada struktur pohon dokumen tertentu akan digunakan. Jika parameter "normalize-characters" dari objek [`DOMConfiguration`](../../../com.aspose.html/configuration/) yang terhubung ke [`Node.ownerDocument`](../ownerdocument/) bernilai true, metode ini juga akan sepenuhnya menormalkan karakter dari node Text.

```java
public void Normalize()
```

### Lihat Juga

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

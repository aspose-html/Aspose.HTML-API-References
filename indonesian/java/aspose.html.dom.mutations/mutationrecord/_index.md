---
title: "Kelas MutationRecord"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "com.aspose.html.dom.mutations.MutationRecord class. Sebuah MutationRecord mewakili mutasi DOM individual. Itu adalah objek yang diteruskan ke MutationCallback MutationObserver."
type: docs

url: /id/java/com.aspose.html.dom.mutations/mutationrecord/
---
## MutationRecord class

Sebuah MutationRecord mewakili mutasi DOM individual. Itu adalah objek yang diteruskan ke [`MutationObserver`](../mutationobserver/)'s [`MutationCallback`](../mutationcallback/).

```java
public class MutationRecord : DOMObject
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [getAddedNodes](../../com.aspose.html.dom.mutations/mutationrecord/addednodes/) Kembalikan node yang ditambahkan. |
| [getAttributeName](../../com.aspose.html.dom.mutations/mutationrecord/attributename/) Mengembalikan nama lokal atribut yang diubah, dan null jika tidak. |
| [getAttributeNamespace](../../com.aspose.html.dom.mutations/mutationrecord/attributepackage/) Mengembalikan paket atribut yang diubah, dan null jika tidak. |
| [getNextSibling](../../com.aspose.html.dom.mutations/mutationrecord/nextsibling/) Kembalikan saudara berikutnya dari node yang ditambahkan atau dihapus, atau null. |
| [getOldValue](../../com.aspose.html.dom.mutations/mutationrecord/oldvalue/) Nilai kembali tergantung pada tipe. Untuk "attributes", itu adalah nilai atribut yang diubah sebelum perubahan. Untuk "characterData", itu adalah data node yang diubah sebelum perubahan. Untuk "childList", itu null. |
| [getPreviousSibling](../../com.aspose.html.dom.mutations/mutationrecord/previoussibling/) Mengembalikan saudara sebelumnya dari node yang ditambahkan atau dihapus, atau null. |
| [getRemovedNodes](../../com.aspose.html.dom.mutations/mutationrecord/removednodes/) Kembalikan node yang dihapus. |
| [getTarget](../../com.aspose.html.dom.mutations/mutationrecord/target/) Mengembalikan node yang dipengaruhi mutasi, tergantung pada tipe. Untuk "attributes", itu adalah elemen yang atributnya berubah. Untuk "characterData", itu adalah node CharacterData. Untuk "childList", itu adalah node yang anak‑anaknya berubah. |
| [getType](../../com.aspose.html.dom.mutations/mutationrecord/type/) Mengembalikan "attributes" jika itu mutasi atribut, "characterData" jika itu mutasi pada node CharacterData, dan "childList" jika itu mutasi pada pohon node. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Metode ini digunakan untuk mengambil objek ECMAScript. |

### Lihat Juga

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.mutations](../../com.aspose.html.dom.mutations/)
* package [Aspose.HTML](../../)

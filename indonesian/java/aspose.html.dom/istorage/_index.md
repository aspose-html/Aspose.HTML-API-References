---
title: "IStorage Antarmuka"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "com.aspose.html.dom.IStorage antarmuka. Antarmuka ini dari Web Storage API menyediakan akses ke sesi atau penyimpanan lokal domain tertentu. Lihat spesifikasi Web Storage https//html.spec.whatwg.org/multipage/webstorage.htmlwebstorage"
type: docs

url: /id/java/com.aspose.html.dom/istorage/
---
## IStorage interface

Antarmuka ini dari Web Storage API menyediakan akses ke penyimpanan sesi atau lokal untuk domain tertentu. Lihat spesifikasi Web Storage: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage)

```java
public interface IStorage
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [getLength](../../com.aspose.html.dom/istorage/length/) Mengembalikan jumlah pasangan kunci/nilai. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [clear](../../com.aspose.html.dom/istorage/clear/)() | Menghapus semua pasangan kunci/nilai, jika ada. |
| [getItem](../../com.aspose.html.dom/istorage/getitem/)(String) | Mengembalikan nilai saat ini yang terkait dengan kunci yang diberikan, atau null jika kunci yang diberikan tidak ada. |
| [key](../../com.aspose.html.dom/istorage/key/)(long) | Mengembalikan nama kunci ke-n, atau null jika n lebih besar atau sama dengan jumlah pasangan kunci/nilai. |
| [removeItem](../../com.aspose.html.dom/istorage/removeitem/)(String) | Menghapus pasangan kunci/nilai dengan kunci yang diberikan, jika pasangan kunci/nilai dengan kunci tersebut ada. |
| [setItem](../../com.aspose.html.dom/istorage/setitem/)(String, String) | Mengatur nilai pasangan yang diidentifikasi oleh kunci ke nilai, membuat pasangan kunci/nilai baru jika sebelumnya tidak ada pasangan untuk kunci tersebut. |

### Lihat Juga

* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)

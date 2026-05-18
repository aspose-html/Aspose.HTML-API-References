---
title: "IEventListener Antarmuka"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "com.aspose.html.dom.events.IEventListener interface. Antarmuka ini adalah metode utama untuk menangani peristiwa. Pengguna mengimplementasikan antarmuka dan mendaftarkan pendengar mereka menggunakan metode tersebut. Pengguna juga harus menghapusnya setelah selesai menggunakan pendengar."
type: docs

url: /id/java/com.aspose.html.dom.events/ieventlistener/
---
## IEventListener interface

Antarmuka ini adalah metode utama untuk menangani peristiwa. Pengguna mengimplementasikan antarmuka dan mendaftarkan pendengar mereka pada sebuah menggunakan metode tersebut. Pengguna juga harus menghapus pendengar mereka setelah selesai menggunakannya.

```java
public interface IEventListener
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [handleEvent](../../com.aspose.html.dom.events/ieventlistener/handleevent/)(Event) | Metode ini dipanggil setiap kali peristiwa terjadi dengan tipe yang telah didaftarkan pada antarmuka. |

## Catatan

Ketika sebuah Node disalin menggunakan metode cloneNode, Event Listener yang terpasang pada Node sumber tidak terpasang pada Node hasil salinan. Jika pengguna menginginkan Event Listener yang sama ditambahkan ke salinan yang baru dibuat, pengguna harus menambahkannya secara manual.

### Lihat Juga

* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)

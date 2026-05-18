---
title: "Sandbox Enum"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "com.aspose.html.Sandbox enum. Sekumpulan flag sandbox adalah kumpulan nol atau lebih dari flag berikut yang digunakan untuk membatasi kemampuan sumber daya yang berpotensi tidak terpercaya"
type: docs

url: /id/java/com.aspose.html/sandbox/
---
## Sandbox enumeration

Satu set flag sandboxing adalah kumpulan nol atau lebih dari flag berikut, yang digunakan untuk membatasi kemampuan sumber daya yang berpotensi tidak terpercaya.

```java
[Flags]
public enum Sandbox
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| None | `0` | Tidak ada flag yang diatur, setiap fitur sandbox diterima |
| Navigation | `1` | Flag ini mencegah konten menavigasi konteks penjelajahan selain konteks penjelajahan sandbox itu sendiri (atau konteks penjelajahan yang lebih dalam di dalamnya), konteks penjelajahan tambahan (yang dilindungi oleh flag sandboxed auxiliary navigation browsing context yang didefinisikan berikutnya), dan konteks penjelajahan tingkat atas (yang dilindungi oleh flag sandboxed top-level navigation browsing context yang didefinisikan di bawah). Jika flag sandboxed auxiliary navigation browsing context tidak diatur, maka dalam beberapa kasus pembatasan tetap memperbolehkan popup (konteks penjelajahan tingkat atas baru) dibuka. Konteks penjelahaan ini selalu memiliki satu navigator sandboxed yang diizinkan, yang ditetapkan saat konteks penjelajahan dibuat, yang memungkinkan konteks penjelajahan yang membuatnya benar‑benar menavigasinya. (Jika tidak, flag sandboxed navigation browsing context akan mencegah mereka dinavigasi bahkan jika mereka dibuka.) |
| AuxiliaryNavigation | `2` | Flag ini mencegah konten membuat konteks penjelajahan tambahan baru, misalnya dengan menggunakan atribut target, atau metode window.open(). |
| TopLevelNavigation | `4` | Flag ini mencegah konten menavigasi konteks penjelajahan tingkat atas mereka dan mencegah konten menutup konteks penjelajahan tingkat atas mereka. Ketika flag sandboxed top-level navigation browsing context tidak diatur, konten dapat menavigasi konteks penjelajahan tingkat atasnya, tetapi konteks penjelajahan lain masih dilindungi oleh flag sandboxed navigation browsing context dan mungkin juga flag sandboxed auxiliary navigation browsing context. |
| Plugins | `8` | Flag ini mencegah konten menginstansiasi plugin, baik dengan menggunakan elemen embed, elemen object, elemen applet, atau melalui navigasi konteks penjelajahan bersarang, kecuali plugin tersebut dapat diamankan. |
| Origin | `10` | Flag ini memaksa konten ke dalam asal yang unik, sehingga mencegahnya mengakses konten lain dari asal yang sama. |
| Forms | `20` | Flag ini memblokir pengiriman formulir. |
| PointerLock | `40` | Flag ini menonaktifkan Pointer Lock API. |
| Scripts | `80` | Flag ini memblokir eksekusi skrip. |
| AutomaticFeatures | `100` | Flag ini memblokir fitur yang dipicu secara otomatis, seperti pemutaran video secara otomatis atau pemfokusan kontrol formulir secara otomatis. |
| Fullscreen | `200` | Flag ini mencegah konten menggunakan metode requestFullscreen(). |
| DocumentDomain | `400` | Flag ini mencegah konten menggunakan fitur document.domain untuk mengubah asal skrip yang efektif. |
| Images | `800` | Flag ini menonaktifkan pemuatan gambar. |

### Lihat Juga

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)

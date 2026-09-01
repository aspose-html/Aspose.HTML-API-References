---
title: "Enum Sandbox"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "enum com.aspose.html.Sandbox. Sekumpulan flag sandboxing adalah kumpulan nol atau lebih flag berikut yang digunakan untuk membatasi kemampuan sumber daya yang berpotensi tidak terpercaya"
type: docs

url: /id/java/com.aspose.html/sandbox/
---
## Sandbox enumeration

Set flag sandboxing adalah sekumpulan nol atau lebih flag berikut, yang digunakan untuk membatasi kemampuan sumber daya yang berpotensi tidak tepercaya.

```java
[Flags]
public enum Sandbox
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| None | `0` | Tidak ada flag yang diatur, setiap fitur sandbox diterima |
| Navigation | `1` | Flag ini mencegah konten menavigasi konteks penelusuran selain konteks penelusuran sandboxed itu sendiri (atau konteks penelusuran yang lebih dalam di dalamnya), konteks penelusuran tambahan (yang dilindungi oleh flag sandboxed auxiliary navigation browsing context yang didefinisikan berikutnya), dan konteks penelusuran tingkat atas (yang dilindungi oleh flag sandboxed top-level navigation browsing context yang didefinisikan di bawah). Jika flag sandboxed auxiliary navigation browsing context tidak diatur, maka dalam beberapa kasus pembatasan tetap memperbolehkan pop‑up (konteks penelusuran tingkat atas baru) dibuka. Konteks penelusuran ini selalu memiliki satu navigator sandboxed yang diizinkan, yang ditetapkan saat konteks penelusuran dibuat, yang memungkinkan konteks penelusuran yang membuatnya benar‑benar menavigasinya. (Jika tidak, flag sandboxed navigation browsing context akan mencegah mereka dinavigasi bahkan jika mereka dibuka. |
| AuxiliaryNavigation | `2` | Flag ini mencegah konten membuat konteks penelusuran tambahan baru, misalnya dengan menggunakan atribut target, atau metode window.open(). |
| TopLevelNavigation | `4` | Flag ini mencegah konten menavigasi konteks penelusuran tingkat atas mereka dan mencegah konten menutup konteks penelusuran tingkat atas mereka. Ketika flag sandboxed top-level navigation browsing context tidak diatur, konten dapat menavigasi konteks penelusuran tingkat atasnya, tetapi konteks penelusuran lain masih dilindungi oleh flag sandboxed navigation browsing context dan mungkin juga flag sandboxed auxiliary navigation browsing context. |
| Plugins | `8` | Flag ini mencegah konten menginstansiasi plugin, baik dengan menggunakan elemen embed, elemen object, elemen applet, atau melalui navigasi konteks penelusuran bersarang, kecuali plugin tersebut dapat diamankan. |
| Origin | `10` | Flag ini memaksa konten ke asal yang unik, sehingga mencegahnya mengakses konten lain dari asal yang sama. |
| Forms | `20` | Flag ini memblokir pengiriman formulir. |
| PointerLock | `40` | Flag ini menonaktifkan Pointer Lock API. |
| Scripts | `80` | Flag ini memblokir eksekusi skrip. |
| AutomaticFeatures | `100` | Flag ini memblokir fitur yang dipicu secara otomatis, seperti pemutaran video otomatis atau fokus otomatis pada kontrol formulir. |
| Fullscreen | `200` | Flag ini mencegah konten menggunakan metode requestFullscreen(). |
| DocumentDomain | `400` | Flag ini mencegah konten menggunakan fitur document.domain untuk mengubah asal skrip yang efektif. |
| Images | `800` | Flag ini menonaktifkan pemuatan gambar. |

### Lihat Juga

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)

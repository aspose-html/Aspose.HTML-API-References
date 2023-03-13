---
title: Enum Sandbox
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Sandbox enum. Set flag kotak pasir adalah kumpulan nol atau lebih dari flag berikut yang digunakan untuk membatasi kemampuan sumber daya yang berpotensi tidak dipercaya.
type: docs
weight: 4560
url: /id/net/aspose.html/sandbox/
---
## Sandbox enumeration

Set flag kotak pasir adalah kumpulan nol atau lebih dari flag berikut, yang digunakan untuk membatasi kemampuan sumber daya yang berpotensi tidak dipercaya.

```csharp
[Flags]
public enum Sandbox
```

### Nilai

| Nama | Nilai | Keterangan |
| --- | --- | --- |
| None | `0` | Tidak ada tanda yang disetel, setiap fitur kotak pasir diterima |
| Navigation | `1` | Bendera ini mencegah konten untuk menavigasi konteks penjelajahan selain dari konteks penjelajahan kotak pasir itu sendiri (atau konteks penjelajahan lebih jauh di dalamnya), konteks penjelajahan tambahan (yang dilindungi oleh tanda konteks penjelajahan navigasi tambahan kotak pasir yang ditentukan berikutnya), dan tingkat teratas konteks penjelajahan (yang dilindungi oleh bendera konteks penjelajahan navigasi tingkat atas kotak pasir yang ditentukan di bawah). Jika bendera konteks penjelajahan navigasi tambahan kotak pasir tidak disetel, maka dalam kasus tertentu pembatasan tetap memungkinkan popup (konteks penjelajahan tingkat atas yang baru) dibuka. Konteks penjelajahan ini selalu memiliki satu navigator kotak pasir yang diizinkan, yang ditetapkan saat konteks penjelajahan dibuat, yang memungkinkan konteks penjelajahan yang membuatnya untuk benar-benar menavigasinya. (Jika tidak, bendera konteks penjelajahan navigasi kotak pasir akan mencegahnya dinavigasi bahkan jika dibuka. |
| AuxiliaryNavigation | `2` | Bendera ini mencegah konten membuat konteks penelusuran tambahan baru, misalnya menggunakan atribut target, atau metode window.open(). |
| TopLevelNavigation | `4` | Bendera ini mencegah konten menavigasi konteks penelusuran tingkat atas dan mencegah konten menutup konteks penelusuran tingkat atas. Ketika bendera konteks penjelajahan navigasi tingkat atas kotak pasir tidak disetel, konten dapat menavigasi konteks penjelajahan tingkat atas, tetapi konteks penjelajahan lainnya masih dilindungi oleh bendera konteks penjelajahan navigasi kotak pasir dan mungkin bendera konteks penjelajahan navigasi tambahan kotak pasir. |
| Plugins | `8` | Bendera ini mencegah konten membuat plugin, baik menggunakan elemen sematan, elemen objek, elemen applet, atau melalui navigasi konteks penelusuran bersarang, kecuali jika plugin tersebut dapat diamankan. |
| Origin | `10` | Bendera ini memaksa konten menjadi asal yang unik, sehingga mencegahnya mengakses konten lain dari asal yang sama. |
| Forms | `20` | Bendera ini memblokir pengiriman formulir. |
| PointerLock | `40` | Bendera ini menonaktifkan Pointer Lock API. |
| Scripts | `80` | Bendera ini memblokir eksekusi skrip. |
| AutomaticFeatures | `100` | Bendera ini memblokir fitur yang memicu secara otomatis, seperti memutar video secara otomatis atau memfokuskan kontrol formulir secara otomatis. |
| Fullscreen | `200` | Bendera ini mencegah konten menggunakan metode requestFullscreen(). |
| DocumentDomain | `400` | Bendera ini mencegah konten menggunakan fitur document.domain untuk mengubah asal skrip yang efektif. |
| Images | `800` | Bendera ini menonaktifkan pemuatan gambar. |

### Lihat juga

* ruang nama [Aspose.Html](../../aspose.html/)
* perakitan [Aspose.HTML](../../)



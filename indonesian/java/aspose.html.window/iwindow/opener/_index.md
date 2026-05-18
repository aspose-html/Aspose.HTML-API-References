---
title: "IWindow.Opener"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "IWindow property. Atribut IDL opener pada objek Window saat dibaca harus mengembalikan objek WindowProxy dari konteks penjelajahan yang menjadi pembuka (opener) konteks penjelajahan saat ini, jika ada, masih tersedia, dan konteks penjelajahan saat ini belum melepaskan pembukanya; jika tidak, harus mengembalikan null. Saat ditetapkan, jika nilai baru adalah null maka konteks penjelajahan saat ini harus melepaskan pembukanya; jika nilai baru bukan null, maka agen pengguna harus memanggil metode internal DefineOwnProperty pada objek Window dengan memberikan nama properti \"opener\" sebagai kunci properti dan Property Descriptor { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } sebagai deskriptor properti, di mana value adalah nilai baru."
type: docs

url: /id/java/com.aspose.html.window/iwindow/opener/
---
## IWindow.Opener property

Atribut IDL opener pada objek Window, saat dibaca, harus mengembalikan objek WindowProxy dari konteks penjelajahan yang menjadi pembuka (opener) konteks penjelajahan saat ini, jika ada, masih tersedia, dan konteks penjelajahan saat ini belum melepaskan pembukanya; jika tidak, harus mengembalikan null. Saat ditetapkan, jika nilai baru adalah null maka konteks penjelajahan saat ini harus melepaskan pembukanya; jika nilai baru bukan null, maka agen pengguna harus memanggil metode internal [[DefineOwnProperty]] pada objek Window, memberikan nama properti "opener" sebagai kunci properti, dan Property Descriptor { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } sebagai deskriptor properti, di mana value adalah nilai baru.

```java
public IWindow Opener { get; }
```

### Property Value

Pembuka.

### Lihat Juga

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)

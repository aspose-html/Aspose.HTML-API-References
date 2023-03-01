---
title: IWindow.Opener
second_title: Aspose.HTML untuk Referensi .NET API
description: IWindow Properti. Atribut IDL pembuka pada objek Window saat mendapatkan harus mengembalikan objek WindowProxy dari konteks penelusuran dari mana konteks penelusuran saat ini dibuat konteks penelusuran pembukanya jika ada jika masih tersedia dan jika konteks penjelajahan saat ini tidak menolak pembukanya jika tidak itu harus mengembalikan nol. Pada pengaturan jika nilai baru adalah null maka konteks penjelajahan saat ini harus menolak pembukanya jika nilai baru adalah hal lain maka agen pengguna harus memanggil metode internal DefineOwnProperty dari objek Window meneruskan nama properti pembuka sebagai kunci properti dan Property Descriptor  Value nilai  Writable true Enumerable true Configurable true  sebagai deskriptor properti di mana value adalah nilai baru.
type: docs
weight: 50
url: /id/net/aspose.html.window/iwindow/opener/
---
## IWindow.Opener property

Atribut IDL pembuka pada objek Window, saat mendapatkan, harus mengembalikan objek WindowProxy dari konteks penelusuran dari mana konteks penelusuran saat ini dibuat (konteks penelusuran pembukanya), jika ada, jika masih tersedia, dan jika konteks penjelajahan saat ini tidak menolak pembukanya; jika tidak, itu harus mengembalikan nol. Pada pengaturan, jika nilai baru adalah null maka konteks penjelajahan saat ini harus menolak pembukanya; jika nilai baru adalah hal lain maka agen pengguna harus memanggil metode internal [[DefineOwnProperty]] dari objek Window, meneruskan nama properti "pembuka" sebagai kunci properti, dan Property Descriptor { [[Value]]: nilai , [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } sebagai deskriptor properti, di mana value adalah nilai baru.

```csharp
public IWindow Opener { get; }
```

### Nilai properti

Pembuka.

### Lihat juga

* interface [IWindow](../)
* ruang nama [Aspose.Html.Window](../../iwindow/)
* perakitan [Aspose.HTML](../../../)



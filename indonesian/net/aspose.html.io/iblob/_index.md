---
title: Interface IBlob
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.IO.IBlob antarmuka. Objek Blob merujuk ke urutan byte dan memiliki atribut ukuran yang merupakan jumlah total byte dalam urutan byte dan atribut tipe yang merupakan string berkode ASCII dalam huruf kecil yang mewakili jenis media dari urutan byte .
type: docs
weight: 3700
url: /id/net/aspose.html.io/iblob/
---
## IBlob interface

Objek Blob merujuk ke urutan byte, dan memiliki atribut ukuran yang merupakan jumlah total byte dalam urutan byte, dan atribut tipe, yang merupakan string berkode ASCII dalam huruf kecil yang mewakili jenis media dari urutan byte .

```csharp
public interface IBlob
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Size](../../aspose.html.io/iblob/size/) { get; } | Mengembalikan ukuran urutan byte dalam jumlah byte. Saat menerima, agen pengguna yang sesuai harus mengembalikan jumlah total byte yang dapat dibaca oleh objek FileReader atau FileReaderSync, atau 0 jika Blob tidak memiliki byte untuk dibaca . |
| [Type](../../aspose.html.io/iblob/type/) { get; } | String berenkode ASCII dalam huruf kecil mewakili jenis media Blob. Saat mendapatkannya, agen pengguna harus mengembalikan jenis Blob sebagai string berenkode ASCII dalam huruf kecil, sedemikian rupa sehingga ketika diubah menjadi byte urutan, ini adalah tipe MIME yang dapat diuraikan, atau string kosong – 0 byte – jika tipenya tidak dapat ditentukan. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [Slice](../../aspose.html.io/iblob/slice/)(ulong, ulong, string) | Mengembalikan objek Blob baru dengan byte mulai dari parameter awal opsional hingga tetapi tidak termasuk parameter akhir opsional, dan dengan atribut tipe yang merupakan nilai dari parameter contentType opsional. |

### Lihat juga

* ruang nama [Aspose.Html.IO](../../aspose.html.io/)
* perakitan [Aspose.HTML](../../)



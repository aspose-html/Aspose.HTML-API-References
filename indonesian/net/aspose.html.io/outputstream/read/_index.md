---
title: OutputStream.Read
second_title: Aspose.HTML untuk Referensi .NET API
description: OutputStream metode. Membaca urutan byte dari aliran keluaran yang dibungkus dan memajukan posisi dalam aliran dengan jumlah byte yang dibaca.
type: docs
weight: 100
url: /id/net/aspose.html.io/outputstream/read/
---
## OutputStream.Read method

Membaca urutan byte dari aliran keluaran yang dibungkus dan memajukan posisi dalam aliran dengan jumlah byte yang dibaca.

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| buffer | Byte[] | Array byte. Saat metode ini kembali, buffer berisi array byte yang ditentukan dengan nilai antara offset dan (offset + count - 1) diganti dengan byte yang dibaca dari aliran output yang dibungkus. |
| offset | Int32 | Offset byte berbasis nol dalam buffer untuk mulai menyimpan data read dari aliran output yang dibungkus. |
| count | Int32 | Jumlah maksimum byte yang akan dibaca dari aliran output yang dibungkus. |

### Nilai Pengembalian

Jumlah total byte yang dibaca ke dalam buffer. Ini bisa kurang dari jumlah byte yang diminta jika banyak byte saat ini tidak tersedia, atau nol (0) jika akhir aliran telah tercapai.

### Lihat juga

* class [OutputStream](../)
* ruang nama [Aspose.Html.IO](../../outputstream/)
* perakitan [Aspose.HTML](../../../)



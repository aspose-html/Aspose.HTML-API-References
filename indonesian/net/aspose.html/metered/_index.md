---
title: Class Metered
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Metered kelas. Menyediakan metode untuk menyetel kunci terukur.
type: docs
weight: 3830
url: /id/net/aspose.html/metered/
---
## Metered class

Menyediakan metode untuk menyetel kunci terukur.

```csharp
public class Metered
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [Metered](metered/)() | Menginisialisasi instance baru dari kelas ini. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [SetMeteredKey](../../aspose.html/metered/setmeteredkey/)(string, string) | Mengatur kunci publik dan pribadi terukur. Jika Anda membeli lisensi terukur, saat memulai aplikasi, API ini harus dipanggil, biasanya, ini sudah cukup. Namun, jika selalu gagal mengunggah data konsumsi dan melebihi 24 jam, lisensi akan disetel ke status evaluasi, untuk menghindari kasus tersebut, Anda harus memeriksa status lisensi secara berkala, jika status evaluasi, hubungi API ini lagi. |
| static [GetConsumptionCredit](../../aspose.html/metered/getconsumptioncredit/)() | Mendapat kredit konsumsi |
| static [GetConsumptionQuantity](../../aspose.html/metered/getconsumptionquantity/)() | Mendapat ukuran file konsumsi |

### Contoh

Dalam contoh ini, upaya akan dilakukan untuk menyetel kunci publik dan pribadi terukur

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

file jar komponen:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### Lihat juga

* ruang nama [Aspose.Html](../../aspose.html/)
* perakitan [Aspose.HTML](../../)



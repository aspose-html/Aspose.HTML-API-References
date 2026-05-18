---
title: "Kelas Metered"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "kelas com.aspose.html.Metered. Menyediakan metode untuk mengatur kunci bermeter"
type: docs

url: /id/java/com.aspose.html/metered/
---
## Metered class

Menyediakan metode untuk mengatur kunci bermeter.

```java
public class Metered
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Metered](metered/)() | Menginisialisasi instance baru dari kelas ini. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [setMeteredKey](../../com.aspose.html/metered/setmeteredkey/)(String, String) | Mengatur kunci publik dan privat bermeter. Jika Anda membeli lisensi bermeter, saat memulai aplikasi, API ini harus dipanggil; biasanya, ini sudah cukup. Namun, jika selalu gagal mengunggah data konsumsi dan melebihi 24 jam, lisensi akan diatur ke status evaluasi; untuk menghindari hal tersebut, Anda harus secara teratur memeriksa status lisensi, jika berada dalam status evaluasi, panggil kembali API ini. |
| static [GetConsumptionCredit](../../com.aspose.html/metered/getconsumptioncredit/)() | Mendapatkan kredit konsumsi |
| static [GetConsumptionQuantity](../../com.aspose.html/metered/getconsumptionquantity/)() | Mendapatkan ukuran file konsumsi |
| static [IsMeteredLicensed](../../com.aspose.html/metered/ismeteredlicensed/)() | Periksa apakah metered berlisensi |

## Contoh

Dalam contoh ini, akan dilakukan percobaan untuk mengatur kunci publik dan privat metered

```java
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

berkas jar komponen:

```java
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### Lihat Juga

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)

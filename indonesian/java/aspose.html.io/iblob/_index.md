---
title: "Antarmuka IBlob"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Antarmuka com.aspose.html.io.IBlob. Objek Blob mengacu pada urutan byte dan memiliki atribut size yang merupakan total jumlah byte dalam urutan tersebut serta atribut type yang merupakan String berkode ASCII dalam huruf kecil yang mewakili tipe media dari urutan byte."
type: docs

url: /id/java/com.aspose.html.io/iblob/
---
## IBlob interface

Objek Blob mengacu pada urutan byte, dan memiliki atribut size yang merupakan total jumlah byte dalam urutan byte, serta atribut type, yang merupakan String berkode ASCII dalam huruf kecil yang mewakili tipe media dari urutan byte.

```java
public interface IBlob
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [getSize](../../com.aspose.html.io/iblob/size/) Mengembalikan ukuran urutan byte dalam jumlah byte. Pada saat diakses, agen pengguna yang mematuhi harus mengembalikan total byte yang dapat dibaca oleh objek FileReader atau FileReaderSync, atau 0 jika Blob tidak memiliki byte untuk dibaca. |
| [getType](../../com.aspose.html.io/iblob/type/) String berkode ASCII dalam huruf kecil yang mewakili tipe media Blob. Pada saat diakses, agen pengguna harus mengembalikan tipe Blob sebagai String berkode ASCII dalam huruf kecil, sehingga ketika dikonversi ke urutan byte, menjadi tipe MIME yang dapat diparse, atau String kosong – 0 byte – jika tipe tidak dapat ditentukan. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [slice](../../com.aspose.html.io/iblob/slice/)(ulong, ulong, String) | Mengembalikan objek Blob baru dengan byte mulai dari parameter start opsional hingga (tetapi tidak termasuk) parameter end opsional, serta dengan atribut type yang bernilai parameter contentType opsional. |

### Lihat Juga

* package [com.aspose.html.io](../../com.aspose.html.io/)
* package [Aspose.HTML](../../)

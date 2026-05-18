---
title: "Kelas License"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "kelas com.aspose.html.License. Menyediakan metode untuk melisensikan komponen"
type: docs

url: /id/java/com.aspose.html/license/
---
## License class

Menyediakan metode untuk melisensikan komponen.

```java
public class License
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [License](license/)() | Menginisialisasi instance baru dari kelas ini. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [setLicense](../../com.aspose.html/license/setlicense/#setlicense)(Stream) | Melisensikan komponen. |
| [setLicense](../../com.aspose.html/license/setlicense/#setlicense_1)(String) | Melisensikan komponen. |

## Contoh

Dalam contoh ini, akan dicoba untuk menemukan file lisensi bernama MyLicense.lic di folder yang berisi komponen, di folder yang berisi assembly pemanggil, di folder assembly entri, dan kemudian di sumber daya tersemat dari assembly pemanggil.

```java
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

berkas jar komponen:

```java
License license = new License();
license.setLicense("MyLicense.lic");
```

### Lihat Juga

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)

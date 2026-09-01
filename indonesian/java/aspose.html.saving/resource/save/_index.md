---
title: "Resource.Save"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode Resource. Menyimpan sumber daya ke aliran yang disediakan"
type: docs

url: /id/java/com.aspose.html.saving/resource/save/
---
## Resource.Save method

Menyimpan sumber daya ke aliran yang disediakan.

```java
public Resource Save(Stream stream, ResourceHandlingContext context)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | Aliran | Aliran tempat sumber daya akan disimpan. |
| konteks | ResourceHandlingContext | Konteks penanganan sumber daya. |

### Nilai Kembali

Sumber daya ini agar Anda dapat men-chain pemanggilan.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| InvalidOperationException | Dilempar jika [`OutputUrl`](../outputurl/) bernilai `null`. [`OutputUrl`](../outputurl/) harus ditentukan sebelum menyimpan sumber daya karena jika tidak tidak mungkin menentukan referensi yang tepat dalam sumber daya yang merujuk ke yang ini. |

### Lihat Juga

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* package [com.aspose.html.saving](../../../com.aspose.html.saving/)
* package [Aspose.HTML](../../../)

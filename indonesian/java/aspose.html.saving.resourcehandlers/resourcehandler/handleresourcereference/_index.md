---
title: "ResourceHandler.HandleResourceReference"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode ResourceHandler. Metode ini bertanggung jawab untuk menangani referensi sumber daya. Dalam metode ini Anda dapat menentukan bagaimana referensi ke sumber daya yang sedang ditangani akan terlihat."
type: docs

url: /id/java/com.aspose.html.saving.resourcehandlers/resourcehandler/handleresourcereference/
---
## ResourceHandler.HandleResourceReference method

Metode ini bertanggung jawab untuk menangani referensi sumber daya. Dalam metode ini, Anda dapat mengatur bagaimana referensi ke sumber daya yang sedang ditangani akan terlihat.

```java
public String HandleResourceReference(Resource resource, ResourceHandlingContext context)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| resource | Resource | [`Resource`](../../../com.aspose.html.saving/resource/) yang akan ditangani. |
| konteks | ResourceHandlingContext | Konteks penanganan sumber daya. |

### Nilai Kembali

String yang akan ditulis ke sumber daya induk dan yang mewakili referensi ke sumber daya yang saat ini sedang ditangani.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| InvalidOperationException | Dikembalikan jika [`OutputUrl`](../../../com.aspose.html.saving/resource/outputurl/) bernilai `null` dan [`Status`](../../../com.aspose.html.saving/resource/status/) adalah Saved. [`OutputUrl`](../../../com.aspose.html.saving/resource/outputurl/) harus ditentukan untuk sumber daya yang disimpan karena jika tidak tidak mungkin menentukan referensi yang tepat dalam sumber daya yang merujuk ke yang ini. |

### Lihat Juga

* class [Resource](../../../com.aspose.html.saving/resource/)
* class [ResourceHandlingContext](../../../com.aspose.html.saving/resourcehandlingcontext/)
* class [ResourceHandler](../)
* package [com.aspose.html.saving.ResourceHandlers](../../../com.aspose.html.saving.resourcehandlers/)
* package [Aspose.HTML](../../../)

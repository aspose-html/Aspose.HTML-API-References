---
title: "Enum HTMLSaveFormat"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Enum com.aspose.html.saving.HTMLSaveFormat. Menentukan format di mana dokumen disimpan. Anda dapat menemukan informasi lebih lanjut tentang menyimpan HTMLDocument dalam artikel."
type: docs

url: /id/java/com.aspose.html.saving/htmlsaveformat/
---
## HTMLSaveFormat enumeration

Menentukan format di mana dokumen disimpan. Anda dapat menemukan informasi lebih lanjut tentang menyimpan [`HTMLDocument`](../../com.aspose.html/htmldocument/) dalam [artikel](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/).

```java
public enum HTMLSaveFormat
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Original | `0` | Dokumen akan disimpan dalam format aslinya. |
| Markdown | `1` | Dokumen akan disimpan sebagai Markdown. |
| MHTML | `2` | Dokumen akan disimpan sebagai MHTML. |

## Catatan

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Contoh

```java
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
  // Siapkan jalur output untuk penyimpanan dokumen
  String documentPath = Path.Combine(OutputDir, "save-to-MD.md");

  // Siapkan kode HTML
  var html_code = "<H2>Hello World!</H2>";
   
  // Inisialisasi dokumen dari variabel String
  using (var document = new HTMLDocument(html_code, "."))
  {
    // Simpan dokumen sebagai file Markdown
    document.Save(documentPath, HTMLSaveFormat.Markdown);
  }
```

*OutputDir - user output folder path.

### Lihat Juga

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)

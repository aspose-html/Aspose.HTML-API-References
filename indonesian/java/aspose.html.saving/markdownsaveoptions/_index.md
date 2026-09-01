---
title: "Kelas MarkdownSaveOptions"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "com.aspose.html.saving.MarkdownSaveOptions class. Mewakili opsi penyimpanan Markdown. Misalnya Anda dapat mengatur gaya pemformatan markdown menggunakan opsi yang kompatibel dengan GitLab Flavored Markdown yang telah ditentukan dan mengonfigurasi penanganan sumber daya. Lihat info lebih lanjut di artikel"
type: docs

url: /id/java/com.aspose.html.saving/markdownsaveoptions/
---
## MarkdownSaveOptions class

Mewakili opsi penyimpanan Markdown. Misalnya, Anda dapat mengatur gaya pemformatan markdown, menggunakan opsi kompatibel GitLab Flavored Markdown yang telah ditentukan, dan mengonfigurasi penanganan sumber daya. Lihat info lebih lanjut di [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options).

```java
public class MarkdownSaveOptions : SaveOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions/)() | Menginisialisasi instance baru dari kelas `MarkdownSaveOptions`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| static [getDefault](../../com.aspose.html.saving/markdownsaveoptions/default/) Mengembalikan sekumpulan opsi yang kompatibel dengan dokumentasi Markdown default. |
| static [getGit](../../com.aspose.html.saving/markdownsaveoptions/git/) Mengembalikan sekumpulan opsi yang kompatibel dengan GitLab Flavored Markdown. |
[getFeatures]
[setFeatures] Flag set that controls which elements are converted to markdown. |
[getFormatter]
[setFormatter] Gets or sets the markdown formatting style. |
| [getResourceHandlingOptions](../../com.aspose.html.saving/saveoptions/resourcehandlingoptions/) Mendapatkan objek [`ResourceHandlingOptions`](../resourcehandlingoptions/) yang digunakan untuk konfigurasi penanganan sumber daya. |

## Catatan

Anda dapat menemukan contoh lengkap dan file data di [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
import System.IO;
...
	 // Siapkan jalur untuk menyimpan file yang dikonversi
      String savePath = Path.Combine(OutputDir, "options-output.md");

      // Siapkan kode HTML dan simpan ke file
      var code = "<h1>Header 1</h1>" +
            "<h2>Header 2</h2>" +
            "<p>Hello, World!!</p>" +
            "<a href='aspose.com'>aspose</a>";
      File.WriteAllText(Path.Combine(OutputDir, "options.html"), code);

      // Buat sebuah instance dari SaveOptions dan atur aturan: 
      // - hanya elemen <a> dan <p> yang akan dikonversi ke Markdown
      var options = new MarkdownSaveOptions();
      options.Features = MarkdownFeatures.Link | MarkdownFeatures.AutomaticParagraph;

      // Panggil metode ConvertHTML untuk mengonversi HTML ke Markdown.
      Converter.ConvertHTML(Path.Combine(OutputDir, "options.html"), options, savePath);
```

### Lihat Juga

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)

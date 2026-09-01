---
title: "Kelas DocSaveOptions"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "com.aspose.html.saving.DocSaveOptions class. Kelas data opsi khusus. Dengan menetapkan properti Anda dapat mengelola karakteristik rendering seperti resolusi, ukuran halaman, warna latar belakang serta opsi khusus dokumen seperti penyematan font. Info lebih lanjut lihat artikel dokumentasi"
type: docs

url: /id/java/com.aspose.html.saving/docsaveoptions/
---
## DocSaveOptions class

Kelas data opsi spesifik. Dengan menetapkan properti, Anda dapat mengelola karakteristik rendering seperti resolusi, ukuran halaman, warna latar belakang serta opsi spesifik dokumen seperti penyematan font. Info lebih lanjut lihat di dokumentasi [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#save-options).

```java
public class DocSaveOptions : DocRenderingOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [DocSaveOptions](docsaveoptions/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Mendapatkan objek [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) yang digunakan untuk konfigurasi pemrosesan properti css. |
[getDocumentFormat]
[setDocumentFormat] Gets or sets the file format of the output document. The default value is DOCX. |
[getFontEmbeddingRule]
[setFontEmbeddingRule] Gets or sets the font embedding rule. The default value is None. |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | Mengatur atau mendapatkan resolusi horizontal untuk gambar internal (yang digunakan selama pemrosesan filter), dalam piksel per inci. Secara default properti ini adalah 300 dpi. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Mendapatkan objek pengaturan halaman yang digunakan untuk konfigurasi output page-set. |
| [verticalResolution](../../com.aspose.html.rendering/renderingoptions/verticalresolution/) { get; set; } | Mengatur atau mendapatkan resolusi vertikal untuk gambar internal (yang digunakan selama pemrosesan filter), dalam piksel per inci. Secara default properti ini adalah 300 dpi. |

## Catatan

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.drawing;
import com.aspose.html.saving;
import System;
...
 // Siapkan jalur ke file HTML sumber
      String documentPath = Path.Combine(DataDir, "canvas.html");

      // Siapkan jalur untuk menyimpan file yang dikonversi
      String savePath = Path.Combine(OutputDir, "canvas-output-options.docx");

      // Inisialisasi dokumen HTML dari file
      using var document = new HTMLDocument(documentPath);

      // Inisialisasi DocSaveOptions. Atur ukuran halaman 600x400 piksel dan margin
      var options = new DocSaveOptions();
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(600, 400), new Margin(10, 10, 10, 10));

      // Konversi HTML ke DOCX
      Converter.ConvertHTML(document, options, savePath);
```

*OutputDir - custom output folder path.

### Lihat Juga

* class [DocRenderingOptions](../../com.aspose.html.rendering.doc/docrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)

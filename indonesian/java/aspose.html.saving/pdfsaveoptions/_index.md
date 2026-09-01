---
title: "Kelas PdfSaveOptions"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "kelas com.aspose.html.saving.PdfSaveOptions. Kelas data spesifik menyediakan beberapa properti untuk mengelola hasil konversi. Misalnya PageSetup menentukan karakteristik halaman. Lihat artikel dokumentasi"
type: docs

url: /id/java/com.aspose.html.saving/pdfsaveoptions/
---
## PdfSaveOptions class

Kelas data spesifik menyediakan beberapa properti untuk mengelola hasil konversi. Misalnya [`PageSetup`](../../com.aspose.html.rendering/pagesetup/) menentukan karakteristik halaman. Lihat dokumentasi [artikel](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions).

```java
public class PdfSaveOptions : PdfRenderingOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Mendapatkan objek [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) yang digunakan untuk konfigurasi pemrosesan properti css. |
| [getDocumentInfo](../../com.aspose.html.rendering.pdf/pdfrenderingoptions/documentinfo/) Berisi informasi tentang dokumen PDF output. |
[getEncryption]
[setEncryption] Gets or sets a encryption details. If not set, then no encryption will be performed. |
[getFormFieldBehaviour]
[setFormFieldBehaviour] Specifies the behavior of form fields in the output PDF document. |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | Mengatur atau mendapatkan resolusi horizontal untuk gambar internal (yang digunakan selama pemrosesan filter), dalam piksel per inci. Secara default properti ini adalah 300 dpi. |
[getIsTaggedPdf]
[setIsTaggedPdf] Creates a tag structure if `true`. |
[getJpegQuality]
[setJpegQuality] Specifies the quality of JPEG compression for images (if JPEG compression is used). Default is 95. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Mendapatkan objek pengaturan halaman yang digunakan untuk konfigurasi output page-set. |
| [verticalResolution](../../com.aspose.html.rendering/renderingoptions/verticalresolution/) { get; set; } | Mengatur atau mendapatkan resolusi vertikal untuk gambar internal (yang digunakan selama pemrosesan filter), dalam piksel per inci. Secara default properti ini adalah 300 dpi. |

## Catatan

Anda dapat menemukan contoh lengkap dan file data di [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
...
 	 // Siapkan jalur ke file HTML sumber
      String documentPath = Path.Combine(DataDir, "drawing.html");

      // Siapkan jalur untuk menyimpan file yang dikonversi
      String savePath = Path.Combine(OutputDir, "drawing-options.pdf");

      // Inisialisasi dokumen HTML dari file
      using var document = new HTMLDocument(documentPath);

      // Inisialisasi PdfSaveOptions. Atur ukuran halaman 600x300 piksel, margin, 
      // resolusi dan ubah warna latar belakang menjadi AliceBlue 
      var options = new PdfSaveOptions()
      {         
        HorizontalResolution = 200,
        VerticalResolution = 200,
        BackgroundColor = Color.AliceBlue,
        JpegQuality = 100
      };
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(600, 300), new Margin(20, 10, 10, 10));      

      // Konversi HTML ke PDF
      Converter.ConvertHTML(document, options, savePath);
```

### Lihat Juga

* class [PdfRenderingOptions](../../com.aspose.html.rendering.pdf/pdfrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)

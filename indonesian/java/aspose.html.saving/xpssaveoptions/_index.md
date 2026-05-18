---
title: "Kelas XpsSaveOptions"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "kelas com.aspose.html.saving.XpsSaveOptions. Kelas data opsi khusus menyediakan beberapa properti untuk mengelola hasil konversi. Misalnya PageSetup menentukan karakteristik halaman. Lihat artikel dokumentasi."
type: docs

url: /id/java/com.aspose.html.saving/xpssaveoptions/
---
## XpsSaveOptions class

Kelas data opsi khusus menyediakan beberapa properti untuk mengelola hasil konversi. Misalnya [`PageSetup`](../../com.aspose.html.rendering/pagesetup/) menentukan karakteristik halaman. Lihat dokumentasi [artikel](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#save-options).

```java
public class XpsSaveOptions : XpsRenderingOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [XpsSaveOptions](xpssaveoptions/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Mendapatkan objek [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) yang digunakan untuk konfigurasi pemrosesan properti css. |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | Mengatur atau mendapatkan resolusi horizontal untuk gambar internal (yang digunakan selama pemrosesan filter), dalam piksel per inci. Secara default properti ini adalah 300 dpi. |
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
	  String documentPath = Path.Combine(OutputDir, "save-options.html");
      String savePath = Path.Combine(OutputDir, "save-options-output.xps");

      // Siapkan kode HTML dan simpan ke sebuah file
      var code = "<h1> XpsSaveOptions Class</h1>\r\n" +
            "<p>Using XpsSaveOptions Class, you can programmatically apply a wide range of conversion parameters such as BackgroundColor, PageSetup, etc.</p>\r\n";

      File.WriteAllText(documentPath, code);

      // Inisialisasi Dokumen HTML dari file html
      using var document = new HTMLDocument(documentPath);
       
      // Atur ukuran halaman, margin, dan ubah warna latar belakang menjadi AntiqueWhite
      var options = new XpsSaveOptions()
      {
        BackgroundColor = Color.AntiqueWhite
      };
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(Length.FromInches(4.9f), Length.FromInches(3.5f)), new Margin(30, 20, 10, 10));

      // Konversi HTML ke XPS
      Converter.ConvertHTML(document, options, savePath); 
```

### Lihat Juga

* class [XpsRenderingOptions](../../com.aspose.html.rendering.xps/xpsrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)

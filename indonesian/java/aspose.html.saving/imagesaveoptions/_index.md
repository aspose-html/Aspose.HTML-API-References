---
title: "Kelas ImageSaveOptions"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Kelas com.aspose.html.saving.ImageSaveOptions. Kelas data opsi khusus. Ini menyediakan properti untuk mengelola resolusi hasil gambar, penyaringan, kualitas, format serta pengaturan halaman, dan lain-lain. Informasi lebih lanjut dapat Anda temukan di artikel dokumentasi"
type: docs

url: /id/java/com.aspose.html.saving/imagesaveoptions/
---
## ImageSaveOptions class

Kelas data opsi spesifik. Kelas ini menyediakan properti untuk mengelola resolusi hasil gambar, kualitas penyaringan, format, serta pengaturan halaman, dll. Info lebih lanjut dapat Anda peroleh di dokumentasi [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#save-options).

```java
public class ImageSaveOptions : ImageRenderingOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ImageSaveOptions](imagesaveoptions/#constructor)() | Menginisialisasi instance baru dari kelas `ImageSaveOptions`; Png akan digunakan sebagai format gambar default. |
| [ImageSaveOptions](imagesaveoptions/#constructor_1)(ImageFormat) | Format gambar [`ImageFormat`](../../com.aspose.html.rendering.image/imageformat/) berdasarkan inisialisasi |

## Properti

| Nama | Deskripsi |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
[getCompression]
[setCompression] Sets or gets Tagged Image File Format (TIFF) [`Compression`](../../com.aspose.html.rendering.image/compression/). By default this property is LZW. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Mendapatkan objek [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) yang digunakan untuk konfigurasi pemrosesan properti css. |
[getFormat]
[setFormat] Sets or gets [`ImageFormat`](../../com.aspose.html.rendering.image/imageformat/). By default this property is Png. |
| [horizontalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | Mengatur atau mendapatkan resolusi horizontal untuk gambar keluaran dan internal (yang digunakan selama pemrosesan filter), dalam piksel per inci. Secara default properti ini adalah 300 dpi. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Mendapatkan objek pengaturan halaman yang digunakan untuk konfigurasi output page-set. |
| [getText](../../com.aspose.html.rendering.image/imagerenderingoptions/text/) Mendapatkan objek [`TextOptions`](../../com.aspose.html.rendering.image/textoptions/) yang digunakan untuk konfigurasi perenderan teks. |
[getUseAntialiasing]
[setUseAntialiasing] Specifies whether to use antialiasing. By default, antialiasing is enabled. |
| [verticalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | Mengatur atau mendapatkan resolusi vertikal untuk gambar keluaran dan internal (yang digunakan selama pemrosesan filter), dalam piksel per inci. Secara default properti ini adalah 300 dpi. |

## Catatan

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.drawing;
import com.aspose.html.rendering.image;
import com.aspose.html.saving;
...
      // Siapkan jalur ke file HTML sumber
      String documentPath = Path.Combine(DataDir, "nature.html");

      // Siapkan path untuk menyimpan file yang dikonversi 
      String savePath = Path.Combine(OutputDir, "nature-output-options.png");

      // Inisialisasi dokumen HTML dari file
      using var document = new HTMLDocument(documentPath);

      // Inisialisasi ImageSaveOptions       
      var options = new ImageSaveOptions()
      {
        SmoothingMode = SmoothingMode.Default,
        HorizontalResolution = 100,
        VerticalResolution = 100,
        BackgroundColor = Color.Beige
      };

      // Konversi HTML ke PNG
      Converter.ConvertHTML(document, options, savePath);
```

### Lihat Juga

* class [ImageRenderingOptions](../../com.aspose.html.rendering.image/imagerenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)

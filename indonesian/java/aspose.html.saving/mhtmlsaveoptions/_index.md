---
title: "Kelas MHTMLSaveOptions"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Kelas com.aspose.html.saving.MHTMLSaveOptions. Mewakili opsi penyimpanan MHTML. Dengan menetapkan properti tertentu Anda dapat mengelola pemrosesan sumber daya seperti kedalaman penanganan maksimum dan sebagainya. Info lebih lanjut lihat pada artikel dokumentasi"
type: docs

url: /id/java/com.aspose.html.saving/mhtmlsaveoptions/
---
## MHTMLSaveOptions class

Mewakili opsi penyimpanan MHTML. Dengan menetapkan properti tertentu, Anda dapat mengelola pemrosesan sumber daya seperti kedalaman penanganan maksimum, dan lain-lain. Info lebih lanjut dapat dilihat di dokumentasi [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options).

```java
public class MHTMLSaveOptions : SaveOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [MHTMLSaveOptions](mhtmlsaveoptions/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
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
	 // Siapkan kode HTML dengan tautan ke file lain dan simpan ke file sebagai 'document.html'
      var code = "<span>Hello, World!!</span> " +
            "<a href='document2.html'>click</a>";
      File.WriteAllText("document.html", code);

      // Siapkan kode HTML dan simpan ke file sebagai 'document2.html'
      code = @"<span>Hello, World!!</span>";
      File.WriteAllText("document2.html", code);
       
      String savePath = Path.Combine(OutputDir, "output-options.mht");

      // Ubah nilai kedalaman penautan sumber daya menjadi 1 untuk mengonversi dokumen dengan sumber daya yang ditautkan secara langsung
      var options = new MHTMLSaveOptions()
      {
        ResourceHandlingOptions =
        {
          MaxHandlingDepth = 1
        }
      };

      // Konversi HTML ke MHTML
      Converter.ConvertHTML("document.html", options, savePath);  
```

### Lihat Juga

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)

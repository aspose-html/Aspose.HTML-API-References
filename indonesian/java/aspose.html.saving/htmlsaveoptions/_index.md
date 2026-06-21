---
title: "Kelas HTMLSaveOptions"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "kelas com.aspose.html.saving.HTMLSaveOptions. Mewakili opsi penyimpanan HTML. Dengan menetapkan properti tertentu Anda dapat mengelola pemrosesan sumber daya seperti kedalaman penanganan maksimum dan sebagainya. Informasi lebih lanjut lihat artikel dokumentasi"
type: docs

url: /id/java/com.aspose.html.saving/htmlsaveoptions/
---
## HTMLSaveOptions class

Mewakili opsi penyimpanan HTML. Dengan menetapkan properti tertentu, Anda dapat mengelola pemrosesan sumber daya seperti kedalaman penanganan maksimum dan sebagainya. Info lebih lanjut lihat di dokumentasi [article](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/).

```java
public class HTMLSaveOptions : SaveOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [HTMLSaveOptions](htmlsaveoptions/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
[getDocumentType]
[setDocumentType] Gets or sets the output document type. |
| [getResourceHandlingOptions](../../com.aspose.html.saving/saveoptions/resourcehandlingoptions/) Mendapatkan objek [`ResourceHandlingOptions`](../resourcehandlingoptions/) yang digunakan untuk konfigurasi penanganan sumber daya. |
[getSerializeInputValue]
[setSerializeInputValue] This option controls whether to serialize the value of the [`HTMLInputElement`](../../com.aspose.html/htmlinputelement/)'s or the [`HTMLTextAreaElement`](../../com.aspose.html/htmltextareaelement/)'s "value" property into the "value" attribute. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| const [AUTO](../../com.aspose.html.saving/htmlsaveoptions/auto/) | Tipe dokumen output akan dipilih secara otomatis. |
| const [HTML](../../com.aspose.html.saving/htmlsaveoptions/html/) | Dokumen akan disimpan sebagai HTML. |
| const [XHTML](../../com.aspose.html.saving/htmlsaveoptions/xhtml/) | Dokumen akan disimpan sebagai XHTML. |

## Catatan

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Contoh

```java
import Aspose.Html;
import com.aspose.html.dom.svg;
import com.aspose.html.saving;
import System;
...
     // Siapkan jalur output untuk dokumen HTML
      String documentPath = Path.Combine(OutputDir, "save-with-linked-file.html");

      // Siapkan file HTML sederhana dengan dokumen yang ditautkan
      File.WriteAllText(documentPath, "<p>Hello World!</p>" +
                      "<a href='linked.html'>linked file</a>");

      // Siapkan file HTML sederhana yang ditautkan
      File.WriteAllText(Path.Combine(OutputDir, "linked.html"), "<p>Hello linked file!</p>");

      // Muat "save-with-linked-file.html" ke memori
      using (var document = new HTMLDocument(documentPath))
      {
        // Buat instance opsi penyimpanan
        var options = new HTMLSaveOptions();

        // Baris berikut dengan nilai '0' memotong semua file HTML terhubung lainnya saat menyimpan instance ini
        // Jika Anda menghapus baris ini atau mengubah nilai menjadi '1', file 'linked.html' juga akan disimpan ke folder output
        options.ResourceHandlingOptions.MaxHandlingDepth = 1;

        // Simpan dokumen dengan opsi penyimpanan
        document.Save(Path.Combine(OutputDir, "save-with-linked-file_out.html"), options);
      }
```

*OutputDir - user output folder.

### Lihat Juga

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
